# 缠论量化知识索引

> 本目录存放缠论量化相关的算法规范，来源：缠中说禅博客原文 + chan.py 开源实现

## 文档列表

| 文件 | 主题 | 核心内容 |
|------|------|----------|
| [bi_algorithm.md](bi_algorithm.md) | 笔的算法 | 分型定义、包含关系处理、笔的构成条件 |
| [seg_feature_sequence.md](seg_feature_sequence.md) | 线段特征序列 | 特征序列概念、两种划分情况、分型判定 |
| [seg_breakdown_cases.md](seg_breakdown_cases.md) | 线段破坏 | 第一类破坏（缺口）、第二类破坏（第二特征序列） |
| [zs_algorithm.md](zs_algorithm.md) | 中枢算法 | 中枢定义、构成条件、级别、延伸与破坏 |
| [buysell_point_algorithm.md](buysell_point_algorithm.md) | 买卖点算法 | 三类买卖点、背驰判定、操作策略 |
| [chan_py_implementation.md](chan_py_implementation.md) | chan.py实现 | 代码结构、核心类、使用示例 |

## 快速导航

### 基础概念

- **分型**：顶分型 / 底分型 → [bi_algorithm.md](bi_algorithm.md)
- **笔**：由分型构成的基本单元 → [bi_algorithm.md](bi_algorithm.md)
- **线段**：至少3笔构成 → [seg_feature_sequence.md](seg_feature_sequence.md)
- **中枢**：3个次级别走势重叠 → [zs_algorithm.md](zs_algorithm.md)

### 核心算法

- **特征序列法**：线段划分标准 → [seg_feature_sequence.md](seg_feature_sequence.md)
- **线段破坏判定**：两种情况 → [seg_breakdown_cases.md](seg_breakdown_cases.md)
- **中枢构建**：识别与级别 → [zs_algorithm.md](zs_algorithm.md)
- **买卖点判定**：三类买卖点 → [buysell_point_algorithm.md](buysell_point_algorithm.md)

### 代码实现

- **chan.py 结构**：项目结构、核心类 → [chan_py_implementation.md](chan_py_implementation.md)
- **笔的实现**：CBi 类 → [chan_py_implementation.md](chan_py_implementation.md)
- **线段实现**：CEigenFX, CSeg → [chan_py_implementation.md](chan_py_implementation.md)
- **中枢实现**：CZS 类 → [chan_py_implementation.md](chan_py_implementation.md)

## 知识来源

1. **缠中说禅博客**：第62-108课系列文章
2. **chan.py**：`/root/workspace/projects/C2-chanlun-v2/backend/3rd/chan.py/`

## 更新日志

- 2026-04-12: 初始创建