# chan.py 算法实现参考

> chan.py (C2-chanlun-v2/backend/3rd/chan.py) 代码结构与核心实现

## 1. 项目结构

```
chan.py/
├── Bi/                  # 笔 (Bi) 模块
│   ├── Bi.py           # 笔类定义
│   ├── BiList.py       # 笔列表管理
│   └── BiConfig.py     # 笔配置
├── Seg/                 # 线段 (Segment) 模块
│   ├── Seg.py          # 线段类定义
│   ├── SegListChan.py  # 缠论线段识别
│   ├── SegListComm.py # 线段列表通用逻辑
│   └── EigenFX.py      # 特征序列分型处理
├── ZS/                  # 中枢 (Zone) 模块
│   ├── ZS.py           # 中枢类定义
│   ├── ZSList.py       # 中枢列表管理
│   └── ZSConfig.py     # 中枢配置
├── KLine/               # K线模块
│   ├── KLine_Unit.py   # 单根K线
│   ├── KLine_List.py   # K线序列
│   └── KLine.py        # K线处理
├── BuySellPoint/        # 买卖点模块
├── Common/              # 公共模块
│   ├── CEnum.py        # 枚举定义
│   ├── ChanException.py # 异常处理
│   └── CTime.py        # 时间处理
└── Chan.py              # 主入口类
```

## 2. 核心类关系

```
CChan (主类)
  ↓
  ├── kl_datas: Dict[KL_TYPE, CKLine_List]
  │         ↓
  │         CKLine_List
  │             ↓
  │             cal_bi() → CBiList (笔列表)
  │             cal_seg_and_zs() → CSegList + CZSList
  │
  └── CBiList (笔列表)
        ↓
        cal_seg() → CSegList (线段列表)
              ↓
              cal_zs() → CZSList (中枢列表)
```

## 3. 笔的实现

### 3.1 笔类定义

```python
# chan.py/Bi/Bi.py
class CBi:
    def __init__(self, begin_klc: CKLine, end_klc: CKLine, idx: int, is_sure: bool):
        self.__dir = None                    # UP/DOWN
        self.__idx = idx                     # 笔序号
        self.__begin_klc = begin_klc         # 起始K线组合
        self.__end_klc = end_klc             # 结束K线组合
        self.__is_sure = is_sure             # 是否确定
        
        # 双向链表
        self.next: Optional[CBi] = None
        self.pre: Optional[CBi] = None
        
        # 关联
        self.parent_seg: Optional[CSeg] = None  # 所属线段
        self.bsp: Optional[CBS_Point] = None    # 买卖点
```

### 3.2 关键方法

```python
class CBi:
    def is_up(self) -> bool:
        return self.__dir == BI_DIR.UP
    
    def is_down(self) -> bool:
        return self.__dir == BI_DIR.DOWN
    
    def get_begin_val(self) -> float:
        """获取笔起点值"""
        return self.begin_klc.low if self.is_up() else self.begin_klc.high
    
    def get_end_val(self) -> float:
        """获取笔终点值"""
        return self.end_klc.high if self.is_up() else self.end_klc.low
    
    def _low(self) -> float:
        """笔的最低点"""
        return min(klc.low for klc in self.klc_lst)
    
    def _high(self) -> float:
        """笔的最高点"""
        return max(klc.high for klc in self.klc_lst)
```

### 3.3 笔列表处理

```python
# chan.py/Bi/BiList.py
class CBiList(List[CBi]):
    def __init__(self, kl_type: KL_TYPE, conf: CBiConfig):
        self.kl_type = kl_type
        self.conf = conf
        self.lst: List[CBi] = []
    
    def update(self, klc_lst: CKLine_List):
        """更新笔列表"""
        # 1. 处理包含关系
        # 2. 识别分型
        # 3. 构建笔
```

## 4. 线段的实现

### 4.1 线段类定义

```python
# chan.py/Seg/Seg.py
class CSeg(Generic[LINE_TYPE]):
    def __init__(self, idx: int, start_bi: LINE_TYPE, end_bi: LINE_TYPE, 
                 is_sure=True, seg_dir=None, reason="normal"):
        self.idx = idx
        self.start_bi = start_bi           # 起始笔
        self.end_bi = end_bi               # 结束笔
        self.is_sure = is_sure              # 是否确定
        self.dir = end_bi.dir if seg_dir is None else seg_dir
        
        self.zs_lst: List[CZS] = []        # 中枢列表
        self.bi_list: List[LINE_TYPE] = []  # 包含的笔
        
        # 双向链表
        self.pre: Optional[CSeg] = None
        self.next: Optional[CSeg] = None
```

### 4.2 特征序列分型处理

```python
# chan.py/Seg/EigenFX.py
class CEigenFX:
    """特征序列分型处理"""
    
    def __init__(self, direction: BI_DIR, lv=SEG_TYPE.BI):
        self.direction = direction   # 特征序列方向
        self.lst: List[CBi] = []     # 特征序列元素
        self.ele = [None, None, None]  # 分型三元素
    
    def add(self, bi: CBi) -> bool:
        """添加笔到特征序列
        
        Returns:
            True - 形成分型
            False - 未形成分型
        """
        # 检查笔方向是否匹配
        # 添加到特征序列
        # 检查是否形成分型
    
    def can_be_end(self, bi_lst: CBiList) -> Optional[bool]:
        """判断是否可以结束线段
        
        Returns:
            True  - 情况一（缺口存在）
            None  - 情况二（需观察第二特征序列）
            False - 不能结束
        """
```

### 4.3 线段识别主逻辑

```python
# chan.py/Seg/SegListChan.py
class CSegListChan(CSegListComm):
    def update(self, bi_lst: CBiList):
        """更新线段列表"""
        self.do_init()
        if len(self) == 0:
            self.cal_seg_sure(bi_lst, begin_idx=0)
        else:
            self.cal_seg_sure(bi_lst, begin_idx=self[-1].end_bi.idx+1)
        self.collect_left_seg(bi_lst)
    
    def cal_seg_sure(self, bi_lst: CBiList, begin_idx: int):
        """确认线段"""
        up_eigen = CEigenFX(BI_DIR.UP)    # 向上线段的特征序列（下降笔）
        down_eigen = CEigenFX(BI_DIR.DOWN) # 向下线段的特征序列（上升笔）
        
        for bi in bi_lst[begin_idx:]:
            # 根据笔方向添加到对应特征序列
            # 检查是否形成特征序列分型
            if fx_eigen:
                self.treat_fx_eigen(fx_eigen, bi_lst)
```

### 4.4 线段破坏判定

```python
def treat_fx_eigen(self, fx_eigen, bi_lst: CBiList):
    _test = fx_eigen.can_be_end(bi_lst)
    end_bi_idx = fx_eigen.GetPeakBiIdx()
    
    if _test in [True, None]:
        # True: 情况一（有缺口，正常结束）
        # None: 情况二（需观察第二特征序列）
        is_true = _test is not None
        self.add_new_seg(bi_lst, end_bi_idx, is_sure=is_true and fx_eigen.all_bi_is_sure())
```

## 5. 中枢的实现

### 5.1 中枢类定义

```python
# chan.py/ZS/ZS.py
class CZS(Generic[LINE_TYPE]):
    def __init__(self, lst: Optional[List[LINE_TYPE]], is_sure=True):
        # 中枢区间
        self.__begin = lst[0].get_begin_klu()  # 起始K线
        self.__end = lst[-1].get_end_klu()     # 结束K线
        
        # 中枢区间（ZG, ZD）
        self.__low = max(bi._low() for bi in lst)   # ZG: 最高低点
        self.__high = min(bi._high() for bi in lst)  # ZD: 最低高点
        self.__mid = (self.__low + self.__high) / 2  # 中轴
        
        # 极值范围
        self.__peak_low = min(bi._low() for bi in lst)
        self.__peak_high = max(bi._high() for bi in lst)
        
        # 进出的笔
        self.__bi_in = lst[0]    # 进中枢的那笔
        self.__bi_out = lst[-1]  # 出中枢的那笔
```

### 5.2 中枢判定

```python
class CZS:
    def in_range(self, item) -> bool:
        """检查笔/线段是否在中枢范围内"""
        return item._low() <= self.high and item._high() >= self.low
    
    def is_one_bi_zs(self) -> bool:
        """判断是否单笔中枢"""
        return self.begin_bi.idx == self.end_bi.idx
```

### 5.3 中枢合并

```python
def combine(self, zs2: 'CZS', combine_mode) -> bool:
    """合并两个中枢"""
    if combine_mode == 'zs':
        # 中枢区间重叠则合并
        if has_overlap(self.low, self.high, zs2.low, zs2.high, equal=True):
            self.do_combine(zs2)
            return True
    elif combine_mode == 'peak':
        # 极值重叠则合并
        if has_overlap(self.peak_low, self.peak_high, zs2.peak_low, zs2.peak_high):
            self.do_combine(zs2)
            return True
```

## 6. 枚举定义

```python
# chan.py/Common/CEnum.py

# K线周期
class KL_TYPE(Enum):
    K_1M = auto()
    K_5M = auto()
    K_15M = auto()
    K_30M = auto()
    K_60M = auto()
    K_DAY = auto()
    K_WEEK = auto()
    K_MONTH = auto()

# 笔/线段方向
class BI_DIR(Enum):
    UP = auto()
    DOWN = auto()

# 分型类型
class FX_TYPE(Enum):
    TOP = auto()    # 顶分型
    BOTTOM = auto() # 底分型

# 线段级别
class SEG_TYPE(Enum):
    BI = auto()     # 笔级别
    SEG = auto()    # 线段级别
    ZS = auto()      # 中枢级别
```

## 7. 主流程

### 7.1 初始化

```python
# chan.py/Chan.py
class CChan:
    def __init__(self, code, lv_list=None, config=None, ...):
        # lv_list: [KL_TYPE.K_DAY, KL_TYPE.K_60M]
        self.lv_list = lv_list
        self.conf = config or CChanConfig()
        self.kl_datas: Dict[KL_TYPE, CKLine_List] = {}
```

### 7.2 计算流程

```python
def load(self):
    for lv in self.lv_list:
        for klu in self.get_kl_data(lv):
            self.kl_datas[lv].add_klu(klu)
    
    # 计算笔
    for lv in self.lv_list:
        self.kl_datas[lv].cal_bi()
    
    # 计算线段和中枢
    for lv in self.lv_list:
        self.kl_datas[lv].cal_seg_and_zs()
```

## 8. 配置参数

### 8.1 笔配置

```python
# chan.py/Bi/BiConfig.py
class CBiConfig:
    min_kline_cnt: int = 1  # 笔的最小K线数
    skip_include: bool = False
```

### 8.2 线段配置

```python
# chan.py/Seg/SegConfig.py
class CSegConfig:
    lv: SEG_TYPE = SEG_TYPE.BI  # 线段级别
```

### 8.3 整体配置

```python
# chan.py/ChanConfig.py
class CChanConfig:
    trigger_step: bool = False       # 分步计算
    skip_step: int = 0               # 跳过的步数
    auto_skip_illegal_sub_lv: bool = True  # 自动跳过非法次级别
```

## 9. 使用示例

```python
from Chan import CChan
from Common.CEnum import KL_TYPE

# 创建实例
chan = CChan(
    code="000001.SZ",
    lv_list=[KL_TYPE.K_DAY, KL_TYPE.K_60M],  # 多级别
)

# 获取结果
bi_list = chan.kl_datas[KL_TYPE.K_DAY].bi_list
seg_list = chan.kl_datas[KL_TYPE.K_DAY].seg_list
zs_list = chan.kl_datas[KL_TYPE.K_DAY].zs_list
```

## 10. 参考资料

- chan.py 项目：`/root/workspace/projects/C2-chanlun-v2/backend/3rd/chan.py/`
- 参考文档：`docs/stone/笔的算法规范.md`, `docs/stone/线段划分的特征序列法.md`, `docs/stone/线段破坏的两种情况.md`, `docs/stone/中枢构建算法.md`