# 缠论知识要点与学习路径梳理计划

**Session ID:** ses_426eccc34ffeQZ6ELDlmJQFryU
**Created:** 1/20/2026, 9:44:32 AM
**Updated:** 1/20/2026, 9:45:57 AM

---

## User

根据本网站内容,系统梳理缠论的知识要点和学习路径.

---

## Assistant (Plan · minimax-m2.1-free · 6.1s)

_Thinking:_

用户希望我根据网站内容系统梳理缠论的知识要点和学习路径。

首先，我需要了解这个网站的内容结构。从工作目录来看，这是一个博客项目。我需要：

1. 首先了解网站的结构和内容
2. 找到与缠论相关的文章/内容
3. 分析缠论知识的组织方式
4. 梳理知识要点和学习路径

由于我处于只读模式，我不能进行任何文件修改。我需要使用搜索和阅读工具来探索网站内容。

让我先了解网站的结构。


我来帮你梳理缠论的知识要点和学习路径。首先，让我探索网站内容结构。

```
Tool: bash

**Input:**
```json
{
  "command": "ls -la",
  "description": "List files in working directory"
}
```
**Output:**
```
total 1056
drwxr-xr-x@  20 jiangtao  staff     640  1 17 09:37 .
drwxr-xr-x@  38 jiangtao  staff    1216  1 17 09:10 ..
drwxr-xr-x@  18 jiangtao  staff     576  1 17 09:42 .docusaurus
drwxr-xr-x@  14 jiangtao  staff     448  1 17 18:23 .git
drwxr-xr-x@   3 jiangtao  staff      96  1 17 09:11 .github
-rw-r--r--@   1 jiangtao  staff     233  1 17 09:11 .gitignore
-rw-r--r--@   1 jiangtao  staff   11357  1 17 09:11 LICENSE
-rw-r--r--@   1 jiangtao  staff     809  1 17 10:14 README.md
-rw-r--r--@   1 jiangtao  staff      89  1 17 09:11 babel.config.js
drwxr-xr-x@  77 jiangtao  staff    2464  1 17 22:16 build
drwxr-xr-x@  67 jiangtao  staff    2144  1 17 09:11 docs
-rw-r--r--@   1 jiangtao  staff   10119  1 17 09:59 docusaurus.config.js
drwxr-xr-x@ 747 jiangtao  staff   23904  1 17 09:40 node_modules
-rw-r--r--@   1 jiangtao  staff    1315  1 17 09:11 package.json
drwxr-xr-x@  21 jiangtao  staff     672  1 17 09:11 sidebars
-rw-r--r--@   1 jiangtao  staff    2403  1 17 09:11 sidebars.js
drwxr-xr-x@   7 jiangtao  staff     224  1 17 09:11 src
drwxr-xr-x@   8 jiangtao  staff     256  1 17 09:11 static
-rw-r--r--@   1 jiangtao  staff     190  1 17 09:11 tsconfig.json
-rw-r--r--@   1 jiangtao  staff  490563  1 17 09:11 yarn.lock

```
```

```
Tool: glob

**Input:**
```json
{
  "pattern": "**/*.md"
}
```
**Output:**
```
/Users/jiangtao/workspace/study/chzhshch-blog/README.md
/Users/jiangtao/workspace/study/chzhshch-blog/static/README.md
/Users/jiangtao/workspace/study/chzhshch-blog/src/pages/markdown-page.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/sorryforleaving.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/mindset.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/music.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/maopoetry2.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/toughyear.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/chitchat.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/claimforcompensation.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/he.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/historicalevaluation.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/disease01.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/maoandluxun.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/marketcancerandnextweekagenda.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/firsttouchwithcancer.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/freedomofexpression.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/shamelessopeningceremony.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/64.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/70.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/castration.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/71.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/65.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/chanmedicine.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/66.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/67.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/63.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/announcement.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/68.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/54.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/60.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/55.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/61.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/56.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/62.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/53.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/57.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/50.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/44.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/45.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/51.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/46.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/52.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/43.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/47.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/40.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/41.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/42.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/39.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/37.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/35.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/36.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/31.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/30.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/34.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/33.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/27.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/26.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/32.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/25.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/20060808.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/21.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/24.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/23.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/20060709.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/22.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/20060507.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/20060319.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/20060402.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/20060328.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/20060417.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/20060418.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/20060317.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/20060419.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/20060316.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/20060213.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/200603151949.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/20060315.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/20060311.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/20060225.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/20060211.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/20060209.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/20060206.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/15.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/20.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/14.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/17.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/20060204.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/13.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/12.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/16.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/11.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/05.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/04.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/10.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/07.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/03.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/02.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/06.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/01.md

(Results are truncated. Consider using a more specific path or pattern.)
```
```

```
Tool: glob

**Input:**
```json
{
  "pattern": "**/*.qmd"
}
```
**Output:**
```
No files found
```
```

---

## Assistant (Plan · minimax-m2.1-free · 4.7s)

_Thinking:_

我看到了这是一个Docusaurus静态网站生成器构建的博客项目。我需要找到与缠论相关的内容。让我：

1. 先看看docs目录下有哪些子目录和文件
2. 搜索与"缠论"相关的内容

```
Tool: bash

**Input:**
```json
{
  "command": "ls -la docs/",
  "description": "List docs directory contents"
}
```
**Output:**
```
total 848
drwxr-xr-x@  67 jiangtao  staff    2144  1 17 09:11 .
drwxr-xr-x@  20 jiangtao  staff     640  1 17 09:37 ..
-rw-r--r--@   1 jiangtao  staff     238  1 17 09:11 1weekleave.md
drwxr-xr-x@  22 jiangtao  staff     704  1 17 09:11 2002posts
-rw-r--r--@   1 jiangtao  staff     911  1 17 09:11 3305points.md
-rw-r--r--@   1 jiangtao  staff    1538  1 17 09:11 3656points.md
-rw-r--r--@   1 jiangtao  staff     936  1 17 09:11 bgmusicusage.md
-rw-r--r--@   1 jiangtao  staff    1891  1 17 09:11 biggestmistake.md
drwxr-xr-x@  12 jiangtao  staff     384  1 17 09:11 categories
-rw-r--r--@   1 jiangtao  staff     820  1 17 09:11 cduploads.md
-rw-r--r--@   1 jiangtao  staff    6827  1 17 09:11 challengemen.md
-rw-r--r--@   1 jiangtao  staff    2423  1 17 09:11 chzhshchonline.md
drwxr-xr-x@ 117 jiangtao  staff    3744  1 17 09:11 confucius
-rw-r--r--@   1 jiangtao  staff    1810  1 17 09:11 culturalrevolution.md
-rw-r--r--@   1 jiangtao  staff    1619  1 17 09:11 democracy.md
-rw-r--r--@   1 jiangtao  staff    1002  1 17 09:11 diseasesummary.md
-rw-r--r--@   1 jiangtao  staff     817  1 17 09:11 donate.md
-rw-r--r--@   1 jiangtao  staff    3250  1 17 09:11 download.md
-rw-r--r--@   1 jiangtao  staff    1751  1 17 09:11 earthquake.md
drwxr-xr-x@ 453 jiangtao  staff   14496  1 17 09:11 economics
-rw-r--r--@   1 jiangtao  staff    1234  1 17 09:11 englandteam.md
drwxr-xr-x@  38 jiangtao  staff    1216  1 17 09:11 entertainment
-rw-r--r--@   1 jiangtao  staff    2006  1 17 09:11 equalitystory.md
drwxr-xr-x@ 108 jiangtao  staff    3456  1 17 09:11 essays
-rw-r--r--@   1 jiangtao  staff     143  1 17 09:11 failtopost.md
-rw-r--r--@   1 jiangtao  staff    2568  1 17 09:11 femalerightsdeclaration2.md
-rw-r--r--@   1 jiangtao  staff     396  1 17 09:11 fluctuating.md
drwxr-xr-x@  22 jiangtao  staff     704  1 17 09:11 fluid
drwxr-xr-x@  32 jiangtao  staff    1024  1 17 09:11 fundanalysis
-rw-r--r--@   1 jiangtao  staff    1898  1 17 09:11 heidegger.md
-rw-r--r--@   1 jiangtao  staff   13969  1 17 09:11 heritagedestruction.md
drwxr-xr-x@  11 jiangtao  staff     352  1 17 09:11 identity
-rw-r--r--@   1 jiangtao  staff    2826  1 17 22:11 intro.md
-rw-r--r--@   1 jiangtao  staff    2885  1 17 09:11 legalityofrc.md
-rw-r--r--@   1 jiangtao  staff    4973  1 17 09:11 lvshi.md
-rw-r--r--@   1 jiangtao  staff    2004  1 17 09:11 maddo.md
-rw-r--r--@   1 jiangtao  staff    1821  1 17 09:11 maopoetry.md
-rw-r--r--@   1 jiangtao  staff    1824  1 17 09:11 maopoetry2.md
-rw-r--r--@   1 jiangtao  staff    1227  1 17 09:11 marketanalysisasusual.md
drwxr-xr-x@  17 jiangtao  staff     544  1 17 09:11 math
-rw-r--r--@   1 jiangtao  staff   17281  1 17 09:11 mindset.md
drwxr-xr-x@  68 jiangtao  staff    2176  1 17 09:11 music
-rw-r--r--@   1 jiangtao  staff   88647  1 17 09:11 music.md
-rw-r--r--@   1 jiangtao  staff     646  1 17 09:11 newbgmusic.md
-rw-r--r--@   1 jiangtao  staff    3817  1 17 09:11 nohumanity.md
-rw-r--r--@   1 jiangtao  staff     878  1 17 09:11 noticeofleave.md
drwxr-xr-x@  28 jiangtao  staff     896  1 17 09:11 others
-rw-r--r--@   1 jiangtao  staff     273  1 17 09:11 pauseduring51holiday.md
-rw-r--r--@   1 jiangtao  staff     501  1 17 09:11 playissue.md
drwxr-xr-x@  97 jiangtao  staff    3104  1 17 09:11 poems
-rw-r--r--@   1 jiangtao  staff    2052  1 17 09:11 publicexpense.md
drwxr-xr-x@ 122 jiangtao  staff    3904  1 17 09:11 qiangguo
drwxr-xr-x@   4 jiangtao  staff     128  1 17 09:11 references
-rw-r--r--@   1 jiangtao  staff    1833  1 17 09:11 schubert.md
-rw-r--r--@   1 jiangtao  staff    1761  1 17 09:11 someteacher.md
-rw-r--r--@   1 jiangtao  staff     732  1 17 09:11 sorryforleaving.md
-rw-r--r--@   1 jiangtao  staff     642  1 17 09:11 statement0804.md
drwxr-xr-x@ 623 jiangtao  staff   19936  1 17 09:11 stocks
-rw-r--r--@   1 jiangtao  staff     199  1 17 09:11 suffering.md
drwxr-xr-x@  50 jiangtao  staff    1600  1 17 09:11 tangfen
drwxr-xr-x@  82 jiangtao  staff    2624  1 17 09:11 tianya
drwxr-xr-x@  12 jiangtao  staff     384  1 17 09:11 timeline
-rw-r--r--@   1 jiangtao  staff  124599  1 17 09:11 timeline.md
-rw-r--r--@   1 jiangtao  staff    1966  1 17 09:11 vernacularchinese.md
-rw-r--r--@   1 jiangtao  staff    5926  1 17 09:11 wulv.md
drwxr-xr-x@  85 jiangtao  staff    2720  1 17 09:11 zen
-rw-r--r--@   1 jiangtao  staff    3055  1 17 09:11 zhouxiaochuan.md

```
```

```
Tool: grep

**Input:**
```json
{
  "pattern": "缠论"
}
```
**Output:**
```
Found 85 matches
/Users/jiangtao/workspace/study/chzhshch-blog/docusaurus.config.js:
  Line 268:         {name: 'description', content: '缠中说禅, 缠论, 全球第一博客'}

/Users/jiangtao/workspace/study/chzhshch-blog/static/html/xueqiucontent.html:
  Line 395: font-size:11.0000pt;" ><font face="宋体" >【关于缠论】看你很用功，回复一下。缠的体系庞杂却一以贯之。从最初的均线缠绕，到级别中枢，再到顶分笔与线段，最后又是系列一招鲜的防狼术，盖因韭菜们智力太低、贪念太重、索求太多又不得要领，不得已才从简入繁，再由繁入简。个中无奈，为人师者都必有体会。</font></span><span style="mso-spacerun:'yes';font-family:Calibri;color:rgb(223,64,42);
  Line 396: font-size:11.0000pt;" ><font face="宋体" >对于缠论，划线是初学者行为，从</font>1<font face="宋体" >分图开始苛求精准往往谬之甚远。学缠者众，小成者稀，大成者更是万里挑一。大道至简，顺势而为。缠之道，无非级别与中枢；缠之势，藏于大盘。先大盘，再个股，这叫顺势。重个股，轻大盘，这是学缠者之通病。大盘走势是无数合力之结果，大而化之更准：</font><font face="Calibri" >15</font><font face="宋体" >分顶背驰则空，</font><font face="Calibri" >15</font><font face="宋体" >分底背弛则多，第一中枢突破后弱回调则大干快上。顺势即择时，择时之后才是选股：大盘空则全空，大盘多可潜伏个股一买，也可跟随龙头三买。定好级别，看准大势，精选个股，而不是相反</font></span><span style="mso-spacerun:'yes';font-family:Calibri;color:rgb(51,53,60);
  Line 1055: font-size:11.0000pt;" >:&nbsp;1<font face="宋体" >、老夫不姓黄</font><font face="Calibri" >&nbsp;2</font><font face="宋体" >、缠论主要看形态，你舍本逐末了</font><font face="Calibri" >&nbsp;3</font><font face="宋体" >、月复利</font><font face="Calibri" >10</font><font face="宋体" >个点，很高了，何必再贪？</font><font face="Calibri" >4</font><font face="宋体" >、学缠者众，缠君及缠论的硬伤以后会细说。之前发过一个贴，你先看着【关于缠论】缠的体系庞杂却一以贯之。从最初的均线缠绕，到级别中枢，再到顶分笔与线段，最后又是系列一招鲜的防狼术，盖因韭菜们智力太低、贪念太重、索求太多又不得要领，不得已才从简入繁，再由繁入简。个中无奈，为人师者都必有体会。对于缠论，划线是初学者行为，从</font><font face="Calibri" >1</font><font face="宋体" >分图开始苛求精准往往谬之甚远。学缠者众，小成者稀，大成者更是万里挑一。大道至简，顺势而为。缠之道，无非级别与中枢；缠之势，藏于大盘。先大盘，再个股，这叫顺势。重个股，轻大盘，这是学缠者之通病。大盘走势是无数合力之结果，大而化之更准：</font><font face="Calibri" >15</font><font face="宋体" >分顶背驰则空，</font><font face="Calibri" >15</font><font face="宋体" >分底背弛则多，第一中枢突破后弱回调则大干快上。顺势即择时，择时之后才是选股：大盘空则全空，大盘多可潜伏个股一买，也可跟随龙头三买。定好级别，看准大势，精选个股，而不是相反。</font><font face="Calibri" >//</font></span><span><a href="http://xueqiu.com/n/%E5%A4%A7%E9%A3%9Eaaron" ><u><span style="mso-spacerun:'yes';font-family:Calibri;color:rgb(0,56,132);
  Line 1102: font-size:11.0000pt;" >:<font face="宋体" >老先生学过缠论吗？感觉和缠论的三买好像啊</font></span><span style="mso-spacerun:'yes';font-family:Calibri;font-size:10.5000pt;" ><o:p></o:p></span></p><p class=MsoNormal ><a name="8051-1524963562398" ></a><span style="mso-spacerun:'yes';font-family:Calibri;color:rgb(51,53,60);
  Line 1146: font-size:11.0000pt;" >:&nbsp;<font face="宋体" >无论是均线，通道，还是缠论的中枢，你只需要掌握一个就好。一招鲜，吃遍天。</font></span><span style="mso-spacerun:'yes';font-family:Calibri;color:rgb(223,64,42);
  Line 1278: font-size:12.0000pt;" ><font face="宋体" >这种十步急杀、一步一个万人坑的走势，你说自己在元旦前走掉，要么是运气，要么就是神仙。死多不懂技术，无非一路死扛；所谓空头，肯定就是一群享受了两个跌停板再无脑割肉的投机客，后面眼看着涨了，他也真就踏空了。这才是市场真实的境况，不是你看到的满屏事后诸葛。具体到形态，这是一波</font>15F<font face="宋体" >趋势底背产生的反弹（这里用缠论看最清楚），要按小级别做，不能马上看反转，上去再回杀一下也是常态，更是常识。反转与否要看蓝筹、看上证，这里才有主力资金动向，小板蹦蹦跳跳反映的是市场情绪。你看，这样就明了了：形态、资金与情绪，这才是一个完整的交易体系。最好的形态学是波浪与缠论，市场情绪看板块，其实关照内心更好，你绝望了市场也就有希望了。更精细的技术在回贴里，你问我答，主贴说太多会误人子弟，尤其是价投。最后提醒一句，无论多久，后面若回本，建议先把杠杆卸掉。这不是你能驾驭的工具。要学会理性投资，而不是一味豪赌。真要赌，愿赌服输。你一定输。</font></span><span style="mso-spacerun:'yes';font-family:Calibri;font-size:10.5000pt;" ><o:p></o:p></span></p><p class=MsoNormal ><a name="3912-1524963562446" ></a><span><a href="http://xueqiu.com/S/SH000001" ><u><span style="mso-spacerun:'yes';font-family:Calibri;color:rgb(0,56,132);
  Line 1323: font-size:11.0000pt;" >1<font face="宋体" >、老夫不姓黄</font><font face="Calibri" >&nbsp;2</font><font face="宋体" >、缠论主要看形态，你舍本逐末了</font><font face="Calibri" >&nbsp;3</font><font face="宋体" >、月复利</font><font face="Calibri" >10</font><font face="宋体" >个点，很高了，何必再贪？</font><font face="Calibri" >4</font><font face="宋体" >、学缠者众，缠君及缠论的硬伤以后会细说。之前发过一个贴，你先看着【关于缠论】缠的体系庞杂却一以贯之。从最初的均线缠绕，到级别中枢，再到顶分笔与线段，最后又是系列一招鲜的防狼术，盖因韭菜们智力太低、贪念太重、索求太多又不得要领，不得已才从简入繁，再由繁入简。个中无奈，为人师者都必有体会。对于缠论，划线是初学者行为，从</font><font face="Calibri" >1</font><font face="宋体" >分图开始苛求精准往往谬之甚远。学缠者众，小成者稀，大成者更是万里挑一。大道至简，顺势而为。缠之道，无非级别与中枢；缠之势，藏于大盘。先大盘，再个股，这叫顺势。重个股，轻大盘，这是学缠者之通病。大盘走势是无数合力之结果，大而化之更准：</font><font face="Calibri" >15</font><font face="宋体" >分顶背驰则空，</font><font face="Calibri" >15</font><font face="宋体" >分底背弛则多，第一中枢突破后弱回调则大干快上。顺势即择时，择时之后才是选股：大盘空则全空，大盘多可潜伏个股一买，也可跟随龙头三买。定好级别，看准大势，精选个股，而不是相反。</font></span><span style="mso-spacerun:'yes';font-family:Calibri;font-size:10.5000pt;" ><o:p></o:p></span></p><p class=MsoNormal ><a name="3245-1524963562456" ></a><span style="mso-spacerun:'yes';font-family:Calibri;color:rgb(51,53,60);
  Line 1350: font-size:10.5000pt;background:rgb(255,255,255);mso-highlight:rgb(255,255,255);" ><font face="宋体" >先生，缠论已经少有人提，</font>2010-12<font face="宋体" >年我也研究验证过</font><font face="Calibri" >3</font><font face="宋体" >年，那是一种特殊的情怀，从先生的语句中，能够感觉到您是比较中意缠论的，请问您是</font><font face="Calibri" >06-07</font><font face="宋体" >年追过缠师实时贴的旧人吗？缠师的大部分帖子我都浇过水，可惜去晚了</font></span><span style="mso-spacerun:'yes';font-family:Calibri;font-size:10.5000pt;" ><o:p></o:p></span></p><p class=MsoNormal ><a name="2181-1524963562461" ></a><span style="mso-spacerun:'yes';font-family:Calibri;color:rgb(57,57,57);
  Line 1457: font-size:12.0000pt;" ><font face="宋体" >最后一贴。说说缠论、后市，再道个别。</font></span><span style="mso-spacerun:'yes';font-family:Calibri;font-size:10.5000pt;" ><o:p></o:p></span></p><p class=MsoNormal ><a name="5844-1524963562485" ></a><b style="mso-bidi-font-weight:normal" ><span style="mso-spacerun:'yes';font-family:Calibri;color:rgb(51,53,60);
  Line 1462: font-size:12.0000pt;" >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<font face="宋体" >到此为止吧。你要关注的只有缠论。这是缠君毕生心血的凝聚。</font></span><span style="mso-spacerun:'yes';font-family:Calibri;font-size:10.5000pt;" ><o:p></o:p></span></p><p class=MsoNormal ><a name="2870-1524963562488" ></a><span style="mso-spacerun:'yes';font-family:Calibri;color:rgb(57,57,57);
  Line 1463: font-size:12.0000pt;" >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<font face="宋体" >缠论是一个未竟的庞杂体系。证道修行是核心。内容包罗哲学、数学、宗教、文化、历史、文学、音乐、政治、经济等等，最后才是</font><font face="Calibri" >108</font><font face="宋体" >篇</font><font face="Calibri" >“</font><font face="宋体" >教你炒股票</font><font face="Calibri" >”</font><font face="宋体" >。缠无疑是个智慧绝伦手眼通天的人物。以上每一个领域，缠之论述，俱有慧见且属上乘。缠名缠中说禅，是冀于红尘缠绕、</font><font face="Calibri" >K</font><font face="宋体" >线纠缠之中，顿悟禅道。</font></span><span style="mso-spacerun:'yes';font-family:Calibri;color:rgb(223,64,42);
  Line 1464: font-size:12.0000pt;" ><font face="宋体" >以禅入缠论，方能窥见路径，证得始终</font></span><span style="mso-spacerun:'yes';font-family:Calibri;color:rgb(57,57,57);
  Line 1466: font-size:12.0000pt;" ><font face="宋体" >缠论在禅中。这是缠之本</font></span><span style="mso-spacerun:'yes';font-family:Calibri;color:rgb(57,57,57);
  Line 1468: font-size:12.0000pt;" >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<font face="宋体" >缠论股票的核心是级别和中枢。离开级别，无所谓多空。离开中枢，无所谓走势。不同级别的走势同源同构，买点卖点才可以层层递归。同源同构一说，是缠论区别其他技术的核心所在，所谓走势终完美无非也是同源同构说的形态演绎。从年线到分时图，</font><font face="Calibri" >K</font><font face="宋体" >线之所以可用一种技术进行分析解剖，背后便是</font><font face="Calibri" >“</font><font face="宋体" >道生一</font><font face="Calibri" >&nbsp;</font><font face="宋体" >一生二</font><font face="Calibri" >&nbsp;</font><font face="宋体" >二生三</font><font face="Calibri" >&nbsp;</font><font face="宋体" >三生万物</font><font face="Calibri" >”</font><font face="宋体" >的道理。这个道理，宗教信仰不足解释，实证科学无法证伪，你究竟是信还是不信？这是一个天大的问题。你的回答决定了你的成就，也决定了你最终该不该学缠。这是</font></span><span style="mso-spacerun:'yes';font-family:Calibri;color:rgb(223,64,42);
  Line 1472: font-size:12.0000pt;" ><font face="宋体" >对于不能由禅入缠论的学徒</font></span><span style="mso-spacerun:'yes';font-family:Calibri;color:rgb(57,57,57);
  Line 1473: font-size:12.0000pt;" ><font face="宋体" >，最有用的章节是中间部门。前面说均线及后面讲分型，可看可不看。均线是个引子，分型向上的精细分析是缠自证的体系，大多数人容易迷失其中失了本义（这部分于缠本人是屠龙刀，于他人只能算一把菜刀，内力差别太大，运用起来自然云壤之别）。只有中间部分，模糊中有精确，恰到好处，也最有实战价值。缠论的三个买点和卖点，真正需要掌握的只有一，后面二三，只是一的不同应用罢了。一买的形态结构体现为一波三折，背后的心理即</font><font face="Calibri" >“</font><font face="宋体" >一鼓作气、再而衰、三而竭</font><font face="Calibri" >”</font><font face="宋体" >，形态情绪都有了，再观察这一过程中量能的大小变化，基本便可确定一买的出现（一卖反过来）。预测各级别的顶底，缠论无疑是最好的技术，兼顾了形态和情绪，指标用的是</font><font face="Calibri" >macd</font><font face="宋体" >。再加上量能分析会更好。顶底区域还需要观察板块和人气股表现，缠君</font><font face="Calibri" >08</font><font face="宋体" >年时日无多，有些意犹未尽，这部分需要学缠者自己去领悟。</font></span><span style="mso-spacerun:'yes';font-family:Calibri;color:rgb(223,64,42);
  Line 1478: font-size:12.0000pt;" ><font face="宋体" >缠论最好的应用是在指数，而非个股</font></span><span style="mso-spacerun:'yes';font-family:Calibri;color:rgb(57,57,57);
  Line 1479: font-size:12.0000pt;" ><font face="宋体" >。指数是市场合力的结果，不会被操纵，分析起来条理清晰，易于指导操作。对于趋势投资者，市场弱势，最好的操作是不操作，用缠论耐心等待买点最为精准。市场一旦转好，缠论用处其实不大，这时候需要的是盘感、经验和胆识，一买二买反应迟钝，即使最具爆发力的三买，这时也比不上游资的追涨及打板技术。这是必须要明确的。</font></span><span style="mso-spacerun:'yes';font-family:Calibri;color:rgb(223,64,42);
  Line 1480: font-size:12.0000pt;" ><font face="宋体" >更高明一些，指数或期指用缠论看趋势，选股用巴菲特定价值，应该是最好的价值趋势投资了</font></span><span style="mso-spacerun:'yes';font-family:Calibri;color:rgb(57,57,57);
  Line 1482: font-size:12.0000pt;" >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<font face="宋体" >真传一句话，假传万卷书。关于缠论，就到这里。最后顺带说一句，缠君当年力推过的两支票，三九与屯河，都是在炒宁高宁。作为最擅长资本运作的红色掌门人，宁高宁已经是各路资金很有默契的市场概念了。宁高宁现在离开了中粮，去了哪里是很值得关注的。只是关注，不是推荐，更不是让你炒。</font></span><span style="mso-spacerun:'yes';font-family:Calibri;font-size:10.5000pt;" ><o:p></o:p></span></p><p class=MsoNormal ><a name="7964-1524963562500" ></a><span style="mso-spacerun:'yes';font-family:Calibri;color:rgb(57,57,57);
  Line 1511: font-size:12.0000pt;" >&nbsp;<font face="宋体" >老兄的技术很全面，缠论功夫也很扎实。私募成绩那么好，还能果断抽身，高手风范。希望有机会能当面请教。</font></span><span style="mso-spacerun:'yes';font-family:Calibri;font-size:10.5000pt;" ><o:p></o:p></span></p><p class=MsoNormal ><a name="9861-1524963562523" ></a><span><a href="http://xueqiu.com/n/%E5%BC%82%E7%AB%AF%E7%8C%8E%E6%89%8B" ><u><span style="mso-spacerun:'yes';font-family:Calibri;color:rgb(0,56,132);

/Users/jiangtao/workspace/study/chzhshch-blog/docs/timeline/stocks/054.md:
  Line 356: 问题2：力度上，g1d2>g2d3>g3d4,相对来说，后者都是前者的盘整背驰。很多人说背了又背，缠论不灵了。其实这里每次盘背都回探前低，从而完成了有理论保证的最低限度的回抽，所以没有什么不对。<br/>

/Users/jiangtao/workspace/study/chzhshch-blog/docs/timeline/fluid/1819.md:
  Line 155: MM 按你说的如果汉奸手上的银行 如果有了缠论的买卖点 要不要执行啊 是不是因为你和他们的战斗 就不看那些了 <br/>

/Users/jiangtao/workspace/study/chzhshch-blog/docs/timeline/economics/fightback.md:
  Line 224: 权证的特征就是变动快,反应灵敏,缠论在上面的买卖点几乎是一闪而过.<br/>

/Users/jiangtao/workspace/study/chzhshch-blog/docs/timeline/economics/embarrassedzhou.md:
  Line 340: 不过，我家人对我学习缠论做以下评价——这是本人有史以来唯一一次主动性刻苦学习、努力钻研。 

/Users/jiangtao/workspace/study/chzhshch-blog/docs/timeline/economics/currencywarssequel5.md:
  Line 193: 博主，我是缠论初学者。特请教：

/Users/jiangtao/workspace/study/chzhshch-blog/docs/timeline/economics/anotherchallenge.md:
  Line 204: 缠mm，为什么缠论理论上很清楚，但一但实际操作，又晕了。郁闷！<br/>

/Users/jiangtao/workspace/study/chzhshch-blog/docs/timeline/economics/allinvestors.md:
  Line 88: 缠姐　　　缠论是不是最后都可以简化为，在级别的前提下，最后一个中枢与当下走势之间的关系　　　来指导操作 

/Users/jiangtao/workspace/study/chzhshch-blog/docs/timeline/economics/3850points.md:
  Line 177: 我学缠论，刚看到29课。请问“该趋势最后一个中枢的级别扩展中”，最后说的，这种情况和盘整背驰中转化为第三类买卖点不同。那种情况下，反弹的级别一定比最后一个中枢低。而这种情况，反弹的级别一定大于或等于最后一个中枢的。<br/>
  Line 231: 看了缠论，真的觉的能开宗力派，就象笑傲江湖的剑宗。废话不说，问个小问题，一分钟走势，它每个K线应分钟时间内的分笔总和，一分钟中枢到底是在分钟线段中，还是Z字形分钟走势，不过我觉得都无所谓，不阻碍判断，只是想更明白点

/Users/jiangtao/workspace/study/chzhshch-blog/docs/timeline/economics/20070809.md:
  Line 165: 缠主好！中枢的划分真难！笔，线段是原料，枢象是一个个迷宫，这是学习缠论的关键对吗？

/Users/jiangtao/workspace/study/chzhshch-blog/docs/timeline/confucius/chitchat.md:
  Line 169: 刚学缠论不久，看到第14 15课，其中提到缠中说禅趋势力度：前一“吻”的结束与后一“吻”开始由短线均线与长期均线相交所形成的面积。在前后两个同向趋势中,当缠中说禅趋势力度比上一次缠中说禅趋势力度要弱，就形成“背驰”<br/>

/Users/jiangtao/workspace/study/chzhshch-blog/docs/timeline/confucius/52.md:
  Line 317: 您的联通今天走得很强，昨晚学习着缠论就开了小差：女王在联通里打仗，一定是龙争虎斗，听了“远离毒品”的告诫，作为小散我先闪了，在一旁为女王喝彩比较合适，并时刻关注30分钟走势中枢的突破，祝您成功。 
  Line 569: =======问这个问题，没好好学习缠论，没有不透风的墙，走势会提前反映消息的。

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/fluid1819.md:
  Line 155: MM 按你说的如果汉奸手上的银行 如果有了缠论的买卖点 要不要执行啊 是不是因为你和他们的战斗 就不看那些了 <br/>

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/fightback.md:
  Line 224: 权证的特征就是变动快,反应灵敏,缠论在上面的买卖点几乎是一闪而过.<br/>

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/embarrassedzhou.md:
  Line 340: 不过，我家人对我学习缠论做以下评价——这是本人有史以来唯一一次主动性刻苦学习、努力钻研。 

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/currencywarssequel5.md:
  Line 193: 博主，我是缠论初学者。特请教：

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/confucius52.md:
  Line 325: 您的联通今天走得很强，昨晚学习着缠论就开了小差：女王在联通里打仗，一定是龙争虎斗，听了“远离毒品”的告诫，作为小散我先闪了，在一旁为女王喝彩比较合适，并时刻关注30分钟走势中枢的突破，祝您成功。 
  Line 577: =======问这个问题，没好好学习缠论，没有不透风的墙，走势会提前反映消息的。

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/chitchat.md:
  Line 169: 刚学缠论不久，看到第14 15课，其中提到缠中说禅趋势力度：前一“吻”的结束与后一“吻”开始由短线均线与长期均线相交所形成的面积。在前后两个同向趋势中,当缠中说禅趋势力度比上一次缠中说禅趋势力度要弱，就形成“背驰”<br/>

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/allinvestors.md:
  Line 88: 缠姐　　　缠论是不是最后都可以简化为，在级别的前提下，最后一个中枢与当下走势之间的关系　　　来指导操作 

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/anotherchallenge.md:
  Line 204: 缠mm，为什么缠论理论上很清楚，但一但实际操作，又晕了。郁闷！<br/>

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/3850points.md:
  Line 183: 我学缠论，刚看到29课。请问“该趋势最后一个中枢的级别扩展中”，最后说的，这种情况和盘整背驰中转化为第三类买卖点不同。那种情况下，反弹的级别一定比最后一个中枢低。而这种情况，反弹的级别一定大于或等于最后一个中枢的。<br/>
  Line 237: 看了缠论，真的觉的能开宗力派，就象笑傲江湖的剑宗。废话不说，问个小问题，一分钟走势，它每个K线应分钟时间内的分笔总和，一分钟中枢到底是在分钟线段中，还是Z字形分钟走势，不过我觉得都无所谓，不阻碍判断，只是想更明白点

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/20070809.md:
  Line 165: 缠主好！中枢的划分真难！笔，线段是原料，枢象是一个个迷宫，这是学习缠论的关键对吗？

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/054.md:
  Line 356: 问题2：力度上，g1d2>g2d3>g3d4,相对来说，后者都是前者的盘整背驰。很多人说背了又背，缠论不灵了。其实这里每次盘背都回探前低，从而完成了有理论保证的最低限度的回抽，所以没有什么不对。<br/>

/Users/jiangtao/workspace/study/chzhshch-blog/docs/identity/tianyapost.md:
  Line 533: 我和缠交往有几年了，虽然从不讨论关于缠论。其实，在和缠交往的几年中，我甚至不知道缠就是缠，缠也从来没有说起过。显示中的缠远不想网络上那样耐心、善于沟通和交流。也从没有以缠和炫耀自己，从不张扬。
  Line 580: 这样李彪就是缠，这么简单都领不清，还学缠论的啊，滚远些
  Line 586: 这样李彪就是缠，这么简单都领不清，还学缠论的啊，滚远些 =========================不错 出来卖 还总监 你这总监卖什么价呀？？？你哪鸡鸣狗盗的下流杂志卖什么价呀？？？ 我纷飞去窑子里消费 都不会去消费你那比婊子还贱的《鸡精分析》破杂志 还什么“财富网” 你们都是穷疯了吧！！！缠是谁 关你这贱货什么鸟事呀？？？你有什么权利叫任何人滚 你开了这里谁的薪水呀？？？<br/>
  Line 602: 十年前有幸和彪共事过,那时缠论已成形,趋势级别为核心,辅以均线macd定强弱多空,本人略懂理解为道氏理论和四度空间的数学式精确深化表达,彪当时笑着点头...<br/>
  Line 603: 惊闻噩信,再细读缠博客,深叹缠论博大精深,已成公式定理!!回首彪的风采,历历在目,不由黯然神伤!愿彪在天堂快乐幸福!!安息吧!!谨此吊唁永远的良师益友!

/Users/jiangtao/workspace/study/chzhshch-blog/docs/identity/dfdaily2.md:
  Line 158: ### 虔诚的缠迷：三大“弟子”传承缠论
  Line 188: “缠中说禅论坛”便是“缠迷”们研究缠论、切磋“武艺”的精神家园之一。“石猴”、“市场先生”和“爱笑的小鱼”则是其中三名资深“学长”。
  Line 192: **打造“猎鲸船”缠论课堂**
  Line 196: 据“石猴”本人所撰：“石猴”之名意在表明缠论为菩提祖师之道，而当时的自己则似孙悟空；“猎鲸船”，意在吸收消化缠论，以供更多人学习、使用。
  Line 200: 数月后，一次偶然机会，“石猴”看到了缠的文字。在他看来，缠论将阴阳之道完美地运用到股票上。虽然这时的“石猴”接触股票仅有一个月，但他已有将缠论研究到底，并将其发扬光大的想法。
  Line 202: 于是，2007年6月24日，“石猴”在新浪开博。自此这里成为缠论的第二课堂。“石猴”会“冷不丁”地在自己的“猎鲸船”中跟踪分析缠师当天的图形，为未参透缠师图形的缠迷们解疑释惑。
  Line 204: 在经历了一些难免的偏差之后，“石猴”对缠论的理解加深。他在“猎鲸船”上先后发布了“缠中说禅教你炒股票——石猴学习系列”、“缠中说禅顶翻东西经济学摘录”，2008年后，“石猴”开始运用缠论独立解盘。
  Line 206: 开博半年后，“石猴”学长语重心长地向学弟学妹们说：学习缠论最重要的是心态，切勿焦躁，“由缠论而经济自由，一年半载能成真吗？”“ 其实我觉得缠论很重要的一点，不是教我们一个做股票的方法，而是让我们重新开始学习和思考，缠论让大家重新激起早已忘记的学习和思考能力，这才是缠最大的功德。”
  Line 208: 2008年10月10日，缠停博后，“石猴”沿用缠论继续进行了两个月的解盘，之后就在这只猎鲸船上消失了。直到2009年3月14日——也就是本报揭秘缠中说禅身份当天。
  Line 214: **把缠论整理成典藏**
  Line 216: 比起“石猴”对缠论的实战应用，“市场学生”更像是缠的“乖乖徒”。他收集与缠有关的言论、帖子和缠论。在缠停博后，他还把两年来缠的博客整理成集。他就像一个传教士，编撰着一本关于缠论的典藏全集。
  Line 220: 2008年5月12日，“市场学生”在新浪开博。而这距离缠公布癌症确诊消息仅半个月。从后来“市场学生”所做之事可推测，他从开博那天起，就决定利用这片天空为缠论服务。
  Line 222: 一年多来，在“市场学生”的新浪博客97篇的博文中，有27篇是关于缠的。其中有缠的博客、缠迷的回复、缠论的整理。
  Line 224: 事实上，在去年4月得知“缠师”身患绝症后，“市场学生”便开始日以继夜地整理缠的博文全集。原计划半年后进行文集的更新工作。但由于缠10月5日发文后一直未更新，“市场学生”深感不安，10月7日，“一种责任感使我放下手中的缠论学习，开始更新缠师博文全集。”
  Line 228: 10月10日后，缠的博客再未更新过。但“市场学生”却没有终止对缠论的总结。
  Line 230: 2009年1月，距离缠停博已有3个月。“市场学生”发文除表示对“缠师”的尊敬之外，还推断缠是女性而非男性，更不是李彪。不过，他也说：“不管缠师是否李彪，抓紧学好缠论自立才是最应该做的，也才真正对得起缠师这两年来的苦心传授。”
  Line 252: “庐山真面目”是论坛的高手，他仔细调查后，基本判断“缠师”确实已逝，而且其就是李彪。但是他说，并不是说缠走了就是对缠的不敬，说缠还生就是缠的真正爱护者。缠的生不能给缠论增辉，缠的死也无损于缠论。他说：“那些连缠已走这一事实都不能直面的，愿意继续把缠当女皇的，就继续吧。 ”“告知大家，无非就是讲了一个大家关心的事实，大家可以放下杂念，继续学习。”
  Line 254: 这就是缠迷。无论怎样，缠迷最后的落脚点都是将缠论继承并发扬光大，因为“缠师”带给了他们一个可能自由的精神家园，所以他们要守护它。
  Line 264: ### 缠论精髓19条：得吾道者三人足矣

/Users/jiangtao/workspace/study/chzhshch-blog/docs/identity/simujianghu.md:
  Line 98: 李彪的“缠论”十分博大精深，如前所述，他在操盘风格上当属技术派，在二级市场圈，最知名的莫过于其首创的“跌停板洗盘吸筹法”。

/Users/jiangtao/workspace/study/chzhshch-blog/docs/fluid/1819.md:
  Line 155: MM 按你说的如果汉奸手上的银行 如果有了缠论的买卖点 要不要执行啊 是不是因为你和他们的战斗 就不看那些了 <br/>

/Users/jiangtao/workspace/study/chzhshch-blog/docs/economics/fightback.md:
  Line 224: 权证的特征就是变动快,反应灵敏,缠论在上面的买卖点几乎是一闪而过.<br/>

/Users/jiangtao/workspace/study/chzhshch-blog/docs/economics/embarrassedzhou.md:
  Line 340: 不过，我家人对我学习缠论做以下评价——这是本人有史以来唯一一次主动性刻苦学习、努力钻研。 

/Users/jiangtao/workspace/study/chzhshch-blog/docs/economics/currencywarssequel5.md:
  Line 193: 博主，我是缠论初学者。特请教：

/Users/jiangtao/workspace/study/chzhshch-blog/docs/economics/anotherchallenge.md:
  Line 204: 缠mm，为什么缠论理论上很清楚，但一但实际操作，又晕了。郁闷！<br/>

/Users/jiangtao/workspace/study/chzhshch-blog/docs/economics/allinvestors.md:
  Line 88: 缠姐　　　缠论是不是最后都可以简化为，在级别的前提下，最后一个中枢与当下走势之间的关系　　　来指导操作 

/Users/jiangtao/workspace/study/chzhshch-blog/docs/economics/3850points.md:
  Line 177: 我学缠论，刚看到29课。请问“该趋势最后一个中枢的级别扩展中”，最后说的，这种情况和盘整背驰中转化为第三类买卖点不同。那种情况下，反弹的级别一定比最后一个中枢低。而这种情况，反弹的级别一定大于或等于最后一个中枢的。<br/>
  Line 231: 看了缠论，真的觉的能开宗力派，就象笑傲江湖的剑宗。废话不说，问个小问题，一分钟走势，它每个K线应分钟时间内的分笔总和，一分钟中枢到底是在分钟线段中，还是Z字形分钟走势，不过我觉得都无所谓，不阻碍判断，只是想更明白点

/Users/jiangtao/workspace/study/chzhshch-blog/docs/economics/20070809.md:
  Line 165: 缠主好！中枢的划分真难！笔，线段是原料，枢象是一个个迷宫，这是学习缠论的关键对吗？

/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/chitchat.md:
  Line 169: 刚学缠论不久，看到第14 15课，其中提到缠中说禅趋势力度：前一“吻”的结束与后一“吻”开始由短线均线与长期均线相交所形成的面积。在前后两个同向趋势中,当缠中说禅趋势力度比上一次缠中说禅趋势力度要弱，就形成“背驰”<br/>

/Users/jiangtao/workspace/study/chzhshch-blog/docs/confucius/52.md:
  Line 317: 您的联通今天走得很强，昨晚学习着缠论就开了小差：女王在联通里打仗，一定是龙争虎斗，听了“远离毒品”的告诫，作为小散我先闪了，在一旁为女王喝彩比较合适，并时刻关注30分钟走势中枢的突破，祝您成功。 
  Line 569: =======问这个问题，没好好学习缠论，没有不透风的墙，走势会提前反映消息的。
```
```

---

## Assistant (Plan · minimax-m2.1-free · 5.7s)

_Thinking:_

我看到这是一个关于"缠中说禅"的博客网站。缠论是一种股票技术分析方法，由缠中说禅（李彪）创立。让我进一步探索与缠论相关的核心内容，包括"教你炒股票"系列文章。

```
Tool: glob

**Input:**
```json
{
  "pattern": "docs/**/教你炒股票*"
}
```
**Output:**
```
No files found
```
```

```
Tool: glob

**Input:**
```json
{
  "pattern": "docs/**/*stocks*"
}
```
**Output:**
```
/Users/jiangtao/workspace/study/chzhshch-blog/docs/timeline/poems/shameonstockstoday.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/timeline/essays/stocksmusicetc.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/timeline/economics/stockschat.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/timeline/economics/stocksandmantra.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/timeline/economics/stockshigh.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/timeline/economics/simplestockshardlife.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/timeline/economics/shinystocks.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/timeline/economics/politicallystockselecting.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/timeline/economics/makemoneyonstocks.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/timeline/economics/gstocks.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/timeline/economics/fewwordsaboutstocks.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/timeline/economics/chinastocksvalue.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/timeline/economics/aboutstocksmarket.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/timeline/economics/aboutstocks.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/stockshigh.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/stocksmusicetc.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/stocksandmantra.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/stockschat.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/simplestockshardlife.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/shinystocks.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/politicallystockselecting.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/makemoneyonstocks.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/gstocks.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/fewwordsaboutstocks.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/chinastocksvalue.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/aboutstocksmarket.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/aboutstocks.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/poems/shameonstockstoday.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/fundanalysis/justifychinastocksvalue.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/fundanalysis/hkstocksexpress.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/fundanalysis/brightfuturefochinastocks.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/essays/stocksmusicetc.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/economics/stockshigh.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/economics/stocksandmantra.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/economics/stockschat.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/economics/shinystocks.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/economics/simplestockshardlife.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/economics/politicallystockselecting.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/economics/makemoneyonstocks.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/economics/gstocks.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/economics/fewwordsaboutstocks.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/economics/chinastocksvalue.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/economics/aboutstocks.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/economics/aboutstocksmarket.md
/Users/jiangtao/workspace/study/chzhshch-blog/docs/categories/stocks.md
```
```

```
Tool: bash

**Input:**
```json
{
  "command": "ls -la docs/stocks/ | head -50",
  "description": "List stocks directory"
}
```
**Output:**
```
total 10912
drwxr-xr-x@ 623 jiangtao  staff  19936  1 17 09:11 .
drwxr-xr-x@  67 jiangtao  staff   2144  1 17 09:11 ..
-rw-r--r--@   1 jiangtao  staff   3787  1 17 09:11 001.md
-rw-r--r--@   1 jiangtao  staff   2932  1 17 09:11 002.md
-rw-r--r--@   1 jiangtao  staff   2021  1 17 09:11 003.md
-rw-r--r--@   1 jiangtao  staff   2848  1 17 09:11 004.md
-rw-r--r--@   1 jiangtao  staff   2410  1 17 09:11 005.md
-rw-r--r--@   1 jiangtao  staff   6797  1 17 09:11 006.md
-rw-r--r--@   1 jiangtao  staff  11422  1 17 09:11 007.md
-rw-r--r--@   1 jiangtao  staff  12646  1 17 09:11 008.md
-rw-r--r--@   1 jiangtao  staff  25241  1 17 09:11 009.md
-rw-r--r--@   1 jiangtao  staff  31348  1 17 09:11 010.md
-rw-r--r--@   1 jiangtao  staff  17305  1 17 09:11 011.md
-rw-r--r--@   1 jiangtao  staff  14595  1 17 09:11 012.md
-rw-r--r--@   1 jiangtao  staff  20299  1 17 09:11 013.md
-rw-r--r--@   1 jiangtao  staff  18935  1 17 09:11 014.md
-rw-r--r--@   1 jiangtao  staff  13946  1 17 09:11 015.md
-rw-r--r--@   1 jiangtao  staff  33629  1 17 09:11 016.md
-rw-r--r--@   1 jiangtao  staff  29458  1 17 09:11 017.md
-rw-r--r--@   1 jiangtao  staff  10126  1 17 09:11 018.md
-rw-r--r--@   1 jiangtao  staff  16626  1 17 09:11 019.md
-rw-r--r--@   1 jiangtao  staff  18561  1 17 09:11 020.md
-rw-r--r--@   1 jiangtao  staff  18288  1 17 09:11 021.md
-rw-r--r--@   1 jiangtao  staff  21444  1 17 09:11 022.md
-rw-r--r--@   1 jiangtao  staff  26809  1 17 09:11 023.md
-rw-r--r--@   1 jiangtao  staff  27395  1 17 09:11 024.md
-rw-r--r--@   1 jiangtao  staff  25565  1 17 09:11 025.md
-rw-r--r--@   1 jiangtao  staff  29238  1 17 09:11 026.md
-rw-r--r--@   1 jiangtao  staff  24948  1 17 09:11 027.md
-rw-r--r--@   1 jiangtao  staff  41441  1 17 09:11 028.md
-rw-r--r--@   1 jiangtao  staff  23224  1 17 09:11 029.md
-rw-r--r--@   1 jiangtao  staff  28393  1 17 09:11 030.md
-rw-r--r--@   1 jiangtao  staff  33681  1 17 09:11 031.md
-rw-r--r--@   1 jiangtao  staff  29145  1 17 09:11 032.md
-rw-r--r--@   1 jiangtao  staff  25079  1 17 09:11 033.md
-rw-r--r--@   1 jiangtao  staff   7100  1 17 09:11 034.md
-rw-r--r--@   1 jiangtao  staff  10785  1 17 09:11 035.md
-rw-r--r--@   1 jiangtao  staff   9484  1 17 09:11 036.md
-rw-r--r--@   1 jiangtao  staff   4967  1 17 09:11 037.md
-rw-r--r--@   1 jiangtao  staff  19210  1 17 09:11 038.md
-rw-r--r--@   1 jiangtao  staff  12305  1 17 09:11 039.md
-rw-r--r--@   1 jiangtao  staff  11878  1 17 09:11 040.md
-rw-r--r--@   1 jiangtao  staff   6864  1 17 09:11 041.md
-rw-r--r--@   1 jiangtao  staff  23466  1 17 09:11 042.md
-rw-r--r--@   1 jiangtao  staff  14426  1 17 09:11 043.md
-rw-r--r--@   1 jiangtao  staff  10070  1 17 09:11 044.md
-rw-r--r--@   1 jiangtao  staff  19755  1 17 09:11 045.md
-rw-r--r--@   1 jiangtao  staff  19709  1 17 09:11 046.md
-rw-r--r--@   1 jiangtao  staff  12268  1 17 09:11 047.md

```
```

---

## Assistant (Plan · minimax-m2.1-free · 5.5s)

_Thinking:_

我发现 docs/stocks/ 目录下有001-047的系列文章，这应该就是缠论的"教你炒股票"系列文章。让我继续查看完整的文件列表，然后阅读一些关键文章来理解缠论的知识体系。

```
Tool: bash

**Input:**
```json
{
  "command": "ls docs/stocks/*.md | wc -l && ls docs/stocks/*.md | tail -30",
  "description": "Count and list stocks articles"
}
```
**Output:**
```
     621
docs/stocks/weekendconcert24.md
docs/stocks/weekendconcert28.md
docs/stocks/weekendconcert37.md
docs/stocks/weekendeffect.md
docs/stocks/weeklinegapfilled.md
docs/stocks/weekslump.md
docs/stocks/welltrainedbrains.md
docs/stocks/westernmedicine.md
docs/stocks/whatisdualstructure.md
docs/stocks/whipsawing.md
docs/stocks/whoami.md
docs/stocks/whynottreatbyzazen.md
docs/stocks/windrising.md
docs/stocks/windstorm.md
docs/stocks/winestockwarn.md
docs/stocks/wolves.md
docs/stocks/woollyheaded.md
docs/stocks/wulv.md
docs/stocks/xianduanchangsha.md
docs/stocks/xianghuoju.md
docs/stocks/yearlybottom.md
docs/stocks/yesterdaymarket.md
docs/stocks/yetanothershortopportunity.md
docs/stocks/zazen01.md
docs/stocks/zazen02.md
docs/stocks/zazen03.md
docs/stocks/zazen15.md
docs/stocks/zazen24.md
docs/stocks/zazen30.md
docs/stocks/zhongguancun.md

```
```

```
Tool: read

**Input:**
```json
{
  "filePath": "/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/001.md"
}
```
**Output:**
```
<file>
00001| ---
00002| id: '001'
00003| title: ''
00004| hide_table_of_contents: true
00005| ---
00006| 
00007| import useBaseUrl from '@docusaurus/useBaseUrl';
00008| 
00009| # 教你炒股票1：不会赢钱的经济人，只是废人！
00010| 
00011| > 2006/6/7 18:08:15
00012| 
00013| :::warning 网友配图，请自行鉴别
00014| <div style={{textAlign: 'left'}}>
00015| <img src={useBaseUrl('/img/stocks/001/1.png')} style={{marginTop: "15px", width: 1000}} />
00016| </div>
00017| :::
00018| 
00019| “教你炒股票”这样的题目，全中国不会有第二人比本ID更适合写的。当然，股票是炒出来的，不是写出来的，因此也从未想过写这样的题目。但任何事情都是有缘起的，缘分到了，也不妨写上一写。
00020|  
00021| 人，总是很奇怪的，就算是很聪明的人，或者在其他行业很成功的人，一旦进入资本市场，就像换了人。虚拟和现实的鸿沟使得干实业的，且不说期货了，就算到风险小多的股市，也很少能干好的。而习惯在虚拟市场玩游戏的，基本很难回头去弄实业，这些例子都太多了。
00022| 
00023| 周围朋友和经济有关的，干金融的比较多，也有几个干实业的。去年人民币放开后，有次和他们一起玩，偶然聊起股票。当时给他们的意见是，由于资源的全球化升势及人民币的升值，国内实业将有很大的困难，而虚拟市场由于对资本的吸纳作用将大有改观，会出现一个至少是大X浪级别的行情，劝他们应该分流部分资金到资本市场来。由于前几年资本市场上出事的人一拨接一拨，这帮家伙很犹豫，一晃就把时间过了。
00024| 
00025| 今年，过完春节，这帮家伙突然开始不断骚扰本ID，说要入市。本ID当时已经忙得无暇分身，对他们一番数落，然后告诉他们，现在是个人都能挣钱，自己玩去，没空理你们。
00026| 
00027| 进入三、四月份，当时有色等行情已经很火暴，这帮家伙想大进又怕风险，一直在小打小闹。有一天，又在一起玩，他们一定要本ID选择一些具体的股票。因为这两年一直有很多外资大基金进来接触要收中国快速消费品的企业，还有就是一些大的周期行业将面临重组，就让他们去关注这两类股票和权证。
00028| 
00029| 五月份后，股市大涨，大家都很忙，中旬时又有机会碰头，一问之下，基本都没怎么大买，买了的也没几个站就下车了。他们都显得很烦躁，不断问有什么可买的。既有点可怜又有点烦他们，怎么在市场外弄得好好的，一到市场里都成这样了？就有点敷衍地告诉他们，去买深沪两地3元上下的本地股，而且告诉他们，这样下去肯定要出问题的，最好自己好好学学，别人怎么厉害也不可能整天像照顾小孩一样看着。
00030| 
00031| :::warning 网友配图，请自行鉴别
00032| <div style={{textAlign: 'left'}}>
00033| <img src={useBaseUrl('/img/stocks/001/2.png')} style={{marginTop: "15px", width: 1000}} />
00034| </div>
00035| :::
00036| 
00037| 上周日，又碰在一起。这几位，大概都一肚子股票了，这次个个神采飞扬；大概又都刨了几本书，听了几股评，看了几杂志，更是口水喷喷地这面那面、一线二线地专家了，1800、2000、2500点地牛人了。这市场，还真能改造人！只是这市场的绞肉机，又有新货了。
00038| 
00039| 有人说，市场是老人挣新人的钱，而市场中的老人，套个10年8年的一抓一大把。其实，市场从来都是明白人挣糊涂人的钱。在市场经济中，只要你参与到经济中来，就是经济人了，经济人当然就以挣钱为目的，特别在资本市场中，没有慈善家，只有赢家和输家。而不会赢钱的经济人，只是废人！无论你在其他方面如何成功，到了市场里，赢输就是唯一标准，除此之外，都是废话。
00040|  
00041| （待续）

(End of file - total 41 lines)
</file>
```
```

```
Tool: read

**Input:**
```json
{
  "filePath": "/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/002.md"
}
```
**Output:**
```
<file>
00001| ---
00002| id: '002'
00003| title: ''
00004| hide_table_of_contents: true
00005| ---
00006| 
00007| import useBaseUrl from '@docusaurus/useBaseUrl';
00008| 
00009| # 教你炒股票2：没有庄家，有的只是赢家和输家！
00010| 
00011| > 2006/6/7 22:41:27
00012| 
00013| <div style={{textAlign: 'center'}}>
00014| <img src={useBaseUrl('/img/stocks/002/1.png')} style={{marginTop: "0px", marginBottom: "10px", width: 560}} />
00015| </div>
00016| 
00017| 庄家这种动物对大多数人来说很神秘，对本ID来说就太稀松平常了。庄家和散户这种二元对立，大概比较适合现代中国人的思维模式，因此就变得如此的常识，但常识往往就是共同谬误的同义词，不仅是所谓的散户，而且很多的所谓庄家，也就牺牲其中。
00018|  
00019| 一般定义中的所谓庄家，就是那些拿着大量资金，能控制股票走势的人。在有关庄家的神话中，庄家被描述成无所不能的，既能超越技术指标、更能超越基本面，大势大盘就更不在话下了。这里说的还只是个股的庄家，至于国家级的庄家，更成了所谓散户的上帝。关于这些庄家上帝的传闻在市场中一秒钟都不曾消停，构成了常识的谬误流播。
00020| 
00021| 但所谓的庄家，前赴后继，尸骨早堆成了山。前几天在一个私人聚会里，还碰到一个50年代的老大叔，说已经准备了二十亿，要坐庄，让本ID去联系一下某某公司的头。那人也是有头有脸的人了，不想当众奚落他，暗地里把他嘲笑了一番，简直是脑子锈着了。
00022| 
00023| 当然，即使庄家的神话已经如此常识，这种傻人还是一直、也会继续前赴后继的。而正因为这种傻人如此的多，猎人打起猎来才能收获丰富。看到越摆庄家谱的，猎人就越高兴，反正这类型的，基本在市场上混个几年就基本尸骨无存了。
00024| 
00025| 市场没有什么庄家，有的只是赢家和输家！有的只是各种类型的动物，还有极少数的高明猎手。市场就是一个围猎的游戏，当你只有一把小弓箭，你可以去打野兔；当你有了屠龙刀，抓几条蛇来玩当然就没劲了，关键你是否有屠龙刀！
00026| 
00027| （待续）
00028| 
00029| ## 回复
00030| 
00031| <div class='blog-comment'>
00032| <span class='blog-comment-chan'>石猴</span> 2007-09-04 22:23:28<br/>
00033| 
00034| 看题图 000008，这是什么鸟股啊，复权价格居然最高到 126，99 年一年从八元窜至 120，2000 年一年又跌回 20，尤其是 2001 年一月从 50 惨跌到 20，真不知道那两年煎熬了多少人，现在说不定还有人在站岗呢，惨烈，庄也死得很惨吧。
00035| 
00036| 从月图上画分笔，历史的底倒是很容易找，日线背驰也很清楚，厉害（小缠的理论厉害），有兴趣可以去我博客看下日线图的分段。
00037| </div>
00038| 
00039| <div class='blog-comment'>
00040| <span class='blog-comment-chan'>股盲</span> 2007-09-22 22:04:29<br/>
00041| 000008 就是传说中的亿安科技，成为那些在寒风凛冽的山顶上站岗的人一生的痛。
00042| </div>

(End of file - total 42 lines)
</file>
```
```

---

## Assistant (Plan · minimax-m2.1-free · 5.6s)

_Thinking:_

现在我开始看到缠论的核心文章系列。让我继续阅读更多文章，特别是关于缠论核心概念的文章，比如分型、笔、线段、中枢、买卖点等。

```
Tool: read

**Input:**
```json
{
  "filePath": "/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/009.md"
}
```
**Output:**
```
<file>
00001| ---
00002| id: '009'
00003| title: ''
00004| hide_table_of_contents: true
00005| ---
00006| 
00007| import useBaseUrl from '@docusaurus/useBaseUrl';
00008| 
00009| # 教你炒股票9：甄别“早泄”男的数学原则！
00010| 
00011| > 2006/11/22 12:00:00
00012| 
00013| 设计一个程序，将所有投资对象进行分类，只搞那些能搞的，这是投资的第一原则。在分类中，所应用的程序可以各色各样，但有一点是肯定的，即没有任何一个程序可以使得所选能搞的最终都百分百能被搞得高潮迭起，就像没有任何一个挑选面首的程序使得所选能搞的最终都能百分百被搞得高潮迭起。因为任何操作程序都必然面对“早泄”问题，就像任何关于面首的选择都必然面临“早泄”男的甄别问题。
00014|  
00015| 而甄别“早泄”之所以困难重重，使得无数所谓高手死无葬身之地，是因为“早泄”这事还真得真刀真枪地实干才能发现，这比ED的甄别可复杂多了、风险大多了。ED，不需要深入介入就可趁早发现，但“早泄”不可以，怎么都要试上一试，而这玩意是一锤子的买卖，这次行还不能保证下次就一定行，因此要有效甄别、及早发现而减少损失就成了一个头号难题。许多所谓高手会宣称，出现什么情况，这股票就会涨。但实际上，任何一种情况，都有着极高百分比的可能会出现“早泄”，确定能搞的突然就变成不能搞了，使得介入变成了套牢。这种情况，在投资里简直太常见了。
00016| 
00017| 那么，如何甄别“早泄”男？首要的就是严格的资金管理，一旦出现“早泄”现象，必须马上退出，即使下面突然又不“早泄”了，又强力高潮了，也必须这样干。而且“早泄”特敏感，一个偶尔的因素就可能导致，而要重新再来，还要等待一个长的不应期，一个长的调整过后，即使会高潮不断，也浪费了时间，有这时间，可搞的东西多了去了，这世界又不只有一个面首、一只股票。当然，这里说的只是基本原则，如果有一套严格的分批介入和退出程序，这一切都变得简单。资金管理问题，涉及面很广，以后会专门分析介绍，这里说的是另一个方面，就是如何能在投资领域尽量避免碰到“早泄”男。
00018| 
00019| “早泄”出现的根本原因在于介入程序出现破缺，出现程序所不能概括的异常情况，这对于所有程序都是必然存在的。而一个程序出现异常，也就是出现“早泄”的概率有多大，这是可以通过长期的数据测试来确定的。最简单的就是抛硬币，正面买、背面不买，这样也算一个介入程序，但这样一个程序的“早泄”率，至少是50% 以上。现在的问题其实很简单，就是如何发现一个“早泄”率特别低的介入程序。但答案很不幸，任何一个孤立的程序都不会有太低的“早泄”率，如果一个程序的“早泄”率低于10%，那就是超一流的程序了，按照这个程序，你投资10次，最多失误1次，这样的程序是很厉害的，基本没有。
00020| 
00021| 但问题不像表面所见那么糟，在数学中，有一个乘法原则可以完全解决这个问题。假设三个互相独立的程序的“早泄”率分别为30%、40%、30%，这都是很普通的并不出色的程序。那么由这三个程序组成的程序组，其“早泄”率就是30%\*40%\*30%=3.6%，也就是说，按这个程序组，干100次，只会出现不到4次的“早泄”，这绝对是一个惊人的结果。即使对于选面首来说，有这样的高效率，大概连武则天大姐都要满意了。
00022| 
00023| 现在，问题的关键变成，如何去寻找这三个互相独立的程序。首先，技术指标，都单纯涉及价量的输入而来，都不是独立的，只需要选择任意一个技术指标构成一个买卖程序就可以。对于水平高点的人来说，一个带均线和成交量的K线图，比任何技术指标都有意义。其次，任何一个股票都不是独立的，在整个股票市场中，处在一定的比价关系中，这个比价关系的变动，也可以构成一个买卖系统，这个买卖系统是和市场资金的流向相关的，一切与市场资金相关的系统，都不能与之独立；最后，可以选择基本面构成一个甄别“早泄”男程序，但这个基本面不是单纯指公司赢利之类的，像本ID在前几期所说，国航李总当兵出身不会让自己的股票长期跌破发行价这么没面子，还有认沽权证基本不会让兑现等等，这才是更重要的基本面，这需要对市场的参与者、对人性有更多的了解才可能精通。
00024| 
00025| 当然，上面这三个独立的程序只是本ID随手而写，任何人都可以设计自己的独立交易程序组，但原则是一致的，就是三个程序组之间必须是互相独立的，像人气指标和资金面其实是一回事情，各种技术指标都是互相相关的等等，如果把三个非独立的程序弄在一起，一点意义都没有。就像有人告诉你，面首的鼻子大就不会“早泄”，另一个告诉你耳朵大不会“早泄”，第三个告诉你胡子多不会“早泄”，如果真按这三样来选人，估计连武则天大姐的奶妈的邻居的奶妈的邻居的奶妈的奶妈的奶妈，都会不满意的。
00026| 
00027| 借地说说如何看本ID的文章，本ID不是股评，不会推荐什么股票，所以希望来本ID这里知道什么具体股票的，就不要浪费时间了。试想，真有本事的人，挣钱都忙不过来，怎么会当股评。本ID这里，股票只是其中一个小项目，只是希望来这里的人也学会怎么挣钱。所谓六艺，不会挣钱，在经济社会里还算人吗？看本ID的文章，要学会方法，当然，本ID有时候可能有意无意就会透露点东西，但你必须有分析能力，要吃透方法。就像10月24日告诉你认购权证介入的一个原则，26日武钢认购权证就大幅启动，2周从3毛多长到1块多，翻了快4倍，如果你真能吃透本ID所说的方法，这种机会是可以把握的。
00028| 
00029| <div style={{textAlign: 'center'}}>
00030| <img src={useBaseUrl('/img/stocks/009/580001.png')} /><br/><br/>
00031| </div>
00032| 
00033| 至于现实的股市，本ID在前面已经反复说了，只要是牛市，股票都要表现的，前几天大家可能都很烦银行股，因为大家都没有，但昨天开始大家就高兴了，因为银行股不动，其他股票开始动。别恨银行股，哪天它们真见顶了，市场也好不了，它们是红旗，各位只要看着红旗还在打，各根据地就可以继续轮动大干了。股票的运动是有规律的，好好学习，这一切都能在你的把握中。至于说本ID想炫耀自己，这种废话根本不值得反驳。本ID在投资市场曾干过事情牛的程度超过你们所有人的想象，本ID还用向你们炫耀？本ID现在只是把东西抖点出来，活跃一下博客的气氛，没有其他任何想法。
00034| 
00035| 
00036| ### 回复
00037| 
00038| <div class='blog-comment'>
00039| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 12:14:35<br/>
00040| [匿名] 冰火 <br/><br/>
00041| 
00042|  
00043| 2006-11-22 12:05:49 <br/>
00044| 沙发，我给楼主留言啦，楼主查看一下哦！谢谢了^_^ 
00045|  
00046| ==============<br/>
00047| 
00048| 什么留言？
00049| </div>
00050| 
00051| <div class='blog-comment'>
00052| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 12:16:41<br/>
00053| [匿名] 快 <br/><br/>
00054| 
00055|  
00056| 2006-11-22 12:18:40 <br/>
00057| 11月16日提到的北辰是否也可以理解，从3-4元布局到10元以上呢? 
00058|  
00059| ==============<br/>
00060| 
00061| 本ID不是股评，要自己学会看走势。
00062| </div>
00063| 
00064| <div class='blog-comment'>
00065| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 12:19:52<br/>
00066| [匿名] 快 <br/><br/>
00067| 
00068| 
00069| 2006-11-22 12:18:40 <br/>
00070| 11月16日提到的北辰是否也可以理解，从3-4元布局到10元以上呢? 
00071| 
00072| ==============<br/>
00073| 
00074| 本ID不是股评，要自己学会看走势。
00075| </div>
00076| 
00077| <div class='blog-comment'>
00078| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 12:25:08<br/>
00079| [匿名] nn <br/><br/>
00080| 
00081| 非常欣赏楼主的新思维和大智慧，但有一点不明白，楼主为何说15元多买N中工就是理性？现在我不是想问N中工值不值这个价，我是想知道假如我在那个位置买了，后面的情况大家也知道了，我的问题是在这个长达几个月的过程中应该如何处理才是最佳的操作手法? 
00082|  
00083| ==================<br/>
00084| 
00085| 开盘就买中工当然是理性的，因为第一只，而且开盘的位置也不太高。后面之所以出现如此走势，是中国特色的管理层所造成的，但开盘15元多买的，后面18、19元随便你出，由于情况发生了意外，当然就要选择退出，这还是上面的原则，买股票一定不能追高，这样一旦发生意外，退出也简单。
00086| </div>
00087| 
00088| <div class='blog-comment'>
00089| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 12:26:19<br/>
00090| [匿名] 冰火 <br/><br/>
00091| 
00092|  
00093| 2006-11-22 12:19:49 <br/>
00094| 在留言板上的留言。 
00095|  
00096| ===========<br/>
00097| 
00098| 没看到有你名字的
00099| </div>
00100| 
00101| <div class='blog-comment'>
00102| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 12:27:39<br/>
00103| 哦，对不起，没看仔细，原来你改名字了。
00104| </div>
00105| 
00106| <div class='blog-comment'>
00107| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 12:32:44<br/>
00108| 水热火深 <br/><br/>
00109| 
00110| 
00111| 2006-11-22 10:58:10<br/>
00112| 多谢大侠指教。我就是那个冰火。我大概明白你的意思了，假如Y是认沽行权价，X是认购行权价，那企业为了自己的利益会尽量保证行权当天的股价不低于Y，所以认购权证的最终价格会不低于Y-X，所以只要认购权证的价格跌到（Y-X）以下的区间内，都是比较安全的。是这个意思吗？ 
00113| 
00114| =============<br/>
00115| 
00116| 不一定要跌到那区间，基本就不会跌到那区间，在上面高点的位置就可以了，那是一个底线，基本不会跌破。所以你就有了一个几乎绝对安全的标准。像最近的武钢，几乎绝对安全线在0.21元，在0.35元见到底部。等于你用最多30%的风险去赌300%的利润，这样当然可以介入了。
00117| </div>
00118| 
00119| <div class='blog-comment'>
00120| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 12:35:59<br/>
00121| 馋中听禅 <br/><br/>
00122| 
00123| 2006-11-22 12:26:59 <br/>
00124| 已介入580003、580002，谢谢。
00125|  
00126| ===============<br/>
00127| 
00128| 你现在介入的位置都不算太好，有一定的风险，属于中途介入，一旦出现再次上涨，也就是出现二次上涨，就一定要找好出货的时机，对于权证，这个时机就是放巨量。
00129| </div>
00130| 
00131| <div class='blog-comment'>
00132| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 12:38:17<br/>
00133| [匿名] 快 <br/><br/>
00134| 
00135|  
00136| 2006-11-22 12:34:15 <br/>
00137| 我女儿这个月满两周岁，从现在开始布局，请教数女“设计一个程序”，在20年之后把她的驾御能力培养成你的几分之一呢? 
00138|  
00139| ============<br/>
00140| 
00141| 对不起，本ID没养过孩子，想起孩子就头疼。
00142| </div>
00143| 
00144| <div class='blog-comment'>
00145| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 12:47:46<br/>
00146| [匿名] 伤心太平洋 <br/><br/>
00147| 
00148| ===============<br/>
00149| 
00150| 主要是你介入的时机不对，或者介入的动机不对，介入时，首先要想好是短线还是中线介入，如果是中线，就要有至少两个月以后的操作期。介入的动机，对于投资特别重要，这点以后会说到。
00151| </div>
00152| 
00153| <div class='blog-comment'>
00154| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 12:50:05<br/>
00155| [匿名] 朝阳一小猪 <br/><br/>
00156| 
00157|  
00158| 2006-11-22 12:43:51 <br/>
00159| 强人啊强人，可是程序怎么设计法呢？不能指望我们大家都去学习股票分析程序设计啊，即便能学会，等我们学完了研究完了牛市也结束了，普通人只能一只只股票自己看啊，工作量巨大啊。
00160| 
00161| 好象有种些股票分析软件叫什么飞狐交易师的是可以用户自己设定一些指标值进行选股的的吧？想知道博主是怎么弄的啊，一定要不吝赐教哦！ 
00162|  
00163| ===================<br/>
00164| 
00165| 不是设计程序，是用想好一套系统的方法，不要企求有什么独门暗器。请你再好好读读，慢慢理解，会悟出点东西来的。
00166| </div>
00167| 
00168| <div class='blog-comment'>
00169| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 12:50:45<br/>
00170| 开盘了，先下，再见。
00171| </div>
00172| 
00173| <div class='blog-comment'>
00174| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 12:52:53<br/>
00175| [匿名] 飞龙 <br/><br/>
00176| 
00177|  
00178| 2006-11-22 12:49:47 <br/>
00179| 楼主应该不缺钱吧，为什么还要花大把时间炒股呢？ 
00180|  
00181| ===========<br/>
00182| 
00183| 炒股不花时间，只有牛市时候才需要看股票，本ID 2001年到2005年，4年连一眼股票都不看。现在就算看，一天也就4小时，这不是钱的问题，而是一个智力问题，股票对于本ID来说，就是一个智力游戏，休息的好方法。
00184| </div>
00185| 
00186| <div class='blog-comment'>
00187| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 12:53:22<br/>
00188| 开盘了，先下，再见。
00189| </div>
00190| 
00191| <div class='blog-comment'>
00192| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 14:27:22<br/>
00193| 友情提醒，大盘短线最大的风险是1972到1977的缺口，短线在所有板快都轮动一次后，短线的震荡在所难免。应有一定的心理准备。
00194| </div>
00195| 
00196| <div class='blog-comment'>
00197| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 14:35:16<br/>
00198| [匿名] 妖女的文章写的 <br/><br/>
00199| 
00200|  
00201| 2006-11-22 14:16:39 <br/>
00202| 有点狂，但是回复网友的问题态度还是不错的。我也有几个问题想请教：
00203| 对于你选股票的所谓的3个可以相乘起来的条件还有点不是很明白。第二点所谓的市场的比价系统，买卖系统不太明白，能不能说的更清楚点？是不是指市场当下的热点。比如前一阶段的炒银行股，大盘股，然后现在的炒二线蓝筹和非蓝筹，是不是这个意思？ 你说的第三个条件比较简单，但是作为我们一般的投资者又如何知道！散户的消息面太差了！ 
00204|  
00205| ================<br/>
00206| 
00207| 你的问题晚上回答，3点后有一个谈判，必须走了。再见。
00208| </div>
00209| 
00210| <div class='blog-comment'>
00211| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 16:50:33<br/>
00212| [匿名] 中银国际 <br/><br/>
00213| 
00214|  
00215| 2006-11-22 14:41:36 <br/>
00216| 哎呀，现在真的跳水啦，从最高位已经跳了30点啦，楼主真神人呀。 
00217|  
00218| ============<br/>
00219| 
00220| 震荡就是折腾，利用折腾，技术高的就可以玩轮动的游戏。大盘震荡，股票可不一定震荡，创新高的股票仍不会少。
00221| </div>
00222| 
00223| <div class='blog-comment'>
00224| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 17:02:16<br/>
00225| [匿名] 妖女的文章写的 <br/><br/>
00226| 
00227| 2006-11-22 14:16:39 <br/>
00228| 
00229| 对于你选股票的所谓的3个可以相乘起来的条件还有点不是很明白。<br/>
00230| =================<br/>
00231| 复习一下初中的概率
00232| 
00233| 第二点所谓的市场的比价系统，买卖系统不太明白，能不能说的更清楚点？是不是指市场当下的热点。比如前一阶段的炒银行股，大盘股，然后现在的炒二线蓝筹和非蓝筹，是不是这个意思？<br/>
00234| ===============<br/>
00235| 不是，市场个股之间有比价关系，这是市场的整体结构，要把握这点，必须对市场的总体结构有所把握。比价关系的变动是最重要的，这点以后会说到。
00236| 
00237| 
00238| 你说的第三个条件比较简单，但是作为我们一般的投资者又如何知道！散户的消息面太差了！ <br/>
00239| ==============<br/>
00240| 很多消息根本就不是什么秘密，关键你要有心。不是要你瞎听消息，而是要好好分析消息。是你在使消息，而不要被消息使。 
00241| </div>
00242| 
00243| <div class='blog-comment'>
00244| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 17:10:13<br/>
00245| [匿名] 飞龙 <br/><br/>
00246| 
00247|  
00248| 2006-11-22 16:15:58 <br/>
00249| 我炒股已有N年了，运气好赚了几百万，但总觉得不能一辈子炒股啊。现想办实业，不知做什么；给别人打工，也不可能；写写博客，又没有楼主的才情。受共产党教育多年，没有什么信仰，钱越多人越空虚，痛苦啊！请楼主指点迷津，多谢！ 
00250|  
00251| ==================<br/>
00252| 
00253| 先把房子、车子买好，把几十年生活费用、养孩子的费用等等留出来买国债，还有一些基本的保险。
00254| 
00255| 把上面所有问题都处理好了，如果还有闲钱，就继续炒股票。
00256| 
00257| 有空来本博客看看《论语》，看看“缠中说禅”。人生不悟道，才是真正的白活。炒股票也是可以悟道的，边炒边悟吧。
00258| 
00259| 实业就不要干了，炒股票的人干实业，基本很难成功。干实业太累，风险比股票大多了。股票的风险，一个人就可以控制，实业的风险，谁都控制不了。
00260| </div>
00261| 
00262| <div class='blog-comment'>
00263| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 17:11:12<br/>
00264| [匿名] Jim <br/><br/>
00265| 
00266|  
00267| 2006-11-22 16:37:35 <br/>
00268| 现在证券分析软件越来越高级，都有荐股功能吧？多下载几个不同公司设计的证券分析软件，分析某个股票时，如果10个有7个建议买进，就买进，反之亦然。 
00269|  
00270| =============<br/>
00271| 
00272| 这样和只有一个系统没什么区别，所有分析软件的原理都是一样的，等于一回事。
00273| </div>
00274| 
00275| <div class='blog-comment'>
00276| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 17:12:06<br/>
00277| 看了四小时的盘，谈了一小时的判，本ID要去找好吃的了。再见。
00278| </div>
00279| 
00280| <div class='blog-comment'>
00281| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 17:14:32<br/>
00282| [匿名] 倒霉呀！ <br/><br/>
00283| 
00284|  
00285| 2006-11-22 16:29:52 <br/>
00286| 从上周偶尔发现了这里，就再也止不住每天要来看看了。。呵呵。。真的很佩服很佩服楼主呀！<br/>
00287| 今年股市大牛，于是N年没有炒股的我一激动在5月份有色金属股涨到不能再涨的时候义无反顾介入了，结果在大家都说随便都能挣钱的大好时机，我竟然赔了40%，现在虽然大势趋好，但是我依然深套其中，呵呵。。<br/>
00288| 看了楼主的文章，感觉自己没有炒股的脑子呀！
00289|  
00290|  ===================<br/>
00291| 
00292| 临走还看到你的帖子，随手也回答了。当一个教训，以后一定不要追高介入任何股票，一定要在调整结束后将启动时介入，这是在市场中生存的最好办法。
00293| </div>
00294| 
00295| <div class='blog-comment'>
00296| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 17:15:38<br/>
00297| 明天继续孔二爷，再见。
00298| </div>
00299| 
00300| <div class='blog-comment'>
00301| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 18:27:27<br/>
00302| 还没去吃饭，网上转了一圈，去孔大叔那里惹了点事：<br/><br/>
00303| 
00304| 缠中说禅 <br/>
00305| 
00306| 2006-11-22 18:12:44 <br/>
00307| 风吹万树暮云低，人海孤行影自迷。<br/>
00308| ===============<br/>
00309| 尚可
00310| 
00311| 寒夜无眠非不困，晴天欲雨有何奇。<br/>
00312| ============<br/>
00313| 拙，“有”字音韵不佳，“又”吧，去声
00314| 
00315| 愿闻金鼓飞黄鹤，岂爱玉笼锁碧鸡。<br/>
00316| ===========<br/>
00317| 愿闻，太露
00318| 
00319| 温酒一杯且稍候，凤凰台上唱虹霓。<br/>
00320| ============<br/>
00321| 温酒一杯且稍候，拙。 
00322|  
00323| 
00324| 缠中说禅 <br/>
00325| 
00326| 2006-11-22 18:19:00 <br/>
00327| 本来想步韵一首，但看到孔大叔不按平水韵来，四支、八齐混着来，马上没兴趣了。 
00328|  
00329| 
00330| 孔大叔写诗，不说了。
00331| </div>
00332| 
00333| <div class='blog-comment'>
00334| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 18:28:54<br/>
00335| [匿名] 射男哥哥 <br/><br/>
00336| 
00337|  
00338| 2006-11-22 17:57:29 <br/>
00339| 检点数女股票高论：做股票就象做爱；选股票就象选面首。早出如男人早泻；高点如女人高潮。疲软股票如ED男人，调整期如男人不应期，大牛市不用安全套…… 古今中外，闻所未闻！尽管数女没养过孩子（26岁 亿元资产 女博士），如日后真有了一男半女，上面如此文字怎么让儿女过目呢？想一想哥哥我都后背发凉！人无远虑，必有近忧。人没有深远的审察、思虑、谋划，必然缠附祸患。 
00340|  
00341| ===============<br/>
00342| 
00343| 本ID叫缠中说禅，孩子是不会知道缠中说禅是谁的，等孩子知道时，估计新浪都倒闭了。
00344| </div>
00345| 
00346| <div class='blog-comment'>
00347| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 22:24:08<br/>
00348| [匿名] 不玩喽<br/>
00349| =============<br/>
00350| 没那么严重吧，大概你的帖子有敏感词。
00351| </div>
00352| 
00353| <div class='blog-comment'>
00354| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 22:26:33<br/>
00355| [匿名] 八卦 <br/><br/>
00356| 
00357|  
00358| 2006-11-22 22:16:36 <br/>
00359| 我刚才发的帖子怎么没了？没骂脏话啊？？？ 
00360|  
00361| ===========<br/>
00362| 
00363| 本ID是不删帖子的，这里的人都知道。是不是你的帖子带了链接，或者其他新浪不能接受的东西。
00364| 
00365| 上面不还有你的帖子吗？
00366| </div>
00367| 
00368| <div class='blog-comment'>
00369| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 22:33:31<br/>
00370| [匿名] 朗月无花 <br/><br/>
00371| 
00372|  
00373| 2006-11-22 18:47:32 <br/>
00374| 楼主一般都是刚发完帖子才评论，今天6点多了还评论，少见。 
00375|  
00376| ===============<br/>
00377| 
00378| 今天突然降温，家里温暖如春，就不爱出去了，边写孔二爷边在网上溜达。
00379| 
00380| 任务完成，明天中午上传。
00381| 
00382| 各位晚安。
00383| 
00384| </div>
00385| 
00386| <div class='blog-comment'>
00387| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 22:44:12<br/>
00388| [匿名] CC <br/><br/>
00389| 
00390|  
00391| 2006-11-22 22:34:07 <br/>
00392| 博主来了，能不能给解释一下刚才的问题，先谢，因为是新来你博客的，对你的观点还有些陌生，但对你讲的某些理念是认同的
00393| 
00394| 2006-11-22 18:54:52 <br/>
00395| 对你的名言有点不理解，为什么说做股票就象做爱呢，这之间有什么可比类推之处呢 
00396|  
00397| ==================<br/>
00398| 
00399| 刚看到你的帖子，看来还走不了了。
00400| 
00401| 连续几章不一直在比喻着吗？这种事情只可意会，不可言传。这里可没有变成黄色博客的打算，所以给点幽默感，多干多体会。
00402| </div>
00403| 
00404| <div class='blog-comment'>
00405| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/22 22:49:12<br/>
00406| 好了，晚了，下了，再见。
00407| </div>
00408| 
00409| <div class='blog-comment'>
00410| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/23 11:56:22<br/>
00411| [匿名] 青皮六<br/><br/>
00412| 
00413| ===========<br/>
00414| 
00415| 本ID不看通常所看的基本面，只看本ID认为是基本面的基本面，例如国航的李总是当兵出身的。
00416| </div>
00417| 
00418| <div class='blog-comment'>
00419| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/23 12:10:28<br/>
00420| 
00421| 昨天本ID在盘中友情提醒要对震荡要有心理准备，大盘经过昨天下午随后的跳水与今早的震荡，越来越接近真正的调整。
00422| 
00423| 注意，本ID说的调整只是短线的，好的个股甚至会借调整启动。
00424| 
00425| 大盘在进入调整前有极大可能先制造一个多头陷阱，大盘在1923-1925留下突破缺口，1972到1977留下中继缺口，如果是多头陷阱，一旦出现衰竭性缺口，就是警报拉响。
00426| </div>
00427| 
00428| <div class='blog-comment'>
00429| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/23 15:29:51<br/>
00430| 以后提问题请到新帖子，否则本ID不看老帖子，就不知道有人提问题了。
00431| </div>
00432| 
00433| <div class='blog-comment'>
00434| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/23 15:33:08<br/>
00435| [匿名] 信禅人 <br/><br/>
00436| 
00437|  
00438| 2006-11-23 12:42:09 <br/>
00439| 说得有水平，很有心。以后会经常到此走走。想请教：股市还能走多远？资源类的股票还能进吗？如原水（600649） 
00440|  
00441| ============<br/>
00442| 
00443| 没表现的都会表现的，这也不例外。原水刚上年线，回试年线不破就可介入。但短线注意大盘调整产生的影响，如果能逆大盘调整而启动，则力度会较大，否则跟着大盘走，就没什么意思了。
00444| </div>
00445| 
00446| <div class='blog-comment'>
00447| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/23 15:37:09<br/>
00448| [匿名] 一声叹息 <br/><br/>
00449| 
00450|  
00451| 2006-11-23 13:15:39 <br/>
00452| 已经介入600267，600868。<br/>
00453| 请博主鉴定，谢谢！ 
00454|  
00455| ============<br/>
00456| 
00457| 前者未上年线，以后最好不要介入这类股票。但既然介入了，就持有吧，反正没启动的最终都会启动，会轮到它的。后者在年线整理，耐心等待整理完成吧。
00458| </div>
00459| 
00460| <div class='blog-comment'>
00461| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/23 15:38:06<br/>
00462| 注意
00463| 
00464| 以后提问题请到每天的新帖子，本ID一般很少看老帖子的评论，错过了就不好了。
00465| </div>
00466| 
00467| <div class='blog-comment'>
00468| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/23 21:04:07<br/>
00469| [匿名] 小明2 <br/><br/>
00470| 
00471|  
00472| 2006-11-23 19:57:41 <br/>
00473| 怎么把我的帖子删掉了？<br/>
00474| 我只是问大盘的方向啊！ 
00475|  
00476| ============<br/>
00477| 
00478| 本ID从来不删帖子的，可能你的帖子有些什么问题，新浪给手起刀落了。
00479| </div>
00480| 
00481| <div class='blog-comment'>
00482| <span class='blog-comment-chan'>缠中说禅</span> 2006/11/23 21:05:49<br/>
00483| 请各位不要在老帖子里问问题，一旦有新帖子，请移步新帖子，否则本ID看不过来。谢谢。
00484| </div>

(End of file - total 484 lines)
</file>
```
```

```
Tool: read

**Input:**
```json
{
  "filePath": "/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/017.md"
}
```
**Output:**
```
<file>
00001| ---
00002| id: '017'
00003| title: ''
00004| hide_table_of_contents: true
00005| ---
00006| 
00007| import useBaseUrl from '@docusaurus/useBaseUrl';
00008| 
00009| # 教你炒股票17：走势终完美
00010| 
00011| > 2006/12/18 11:52:42
00012| 
00013| 任何级别的所有走势，都能分解成趋势与盘整两类，而趋势又分为上涨与下跌两类。以上结论，不是从天而降的，而是从无数图形的分析实践中总结出来的，正如《论语》所说“由诲女，知之乎！知之为，知之；不知为，不知；是知也。”（请看本ID相应系列的解释）这个从实际图形中总结出来的简单经验，却是一切有关技术分析理论的唯一坚实基础。这个基础，所有接触技术分析的人都知道，但可惜没有人能深究下去，然后就沉入技术指标、交易系统等苦海不能自拔。试想，基础都没搞清楚，又有什么可立起来？而基础稳固了，技术指标、交易系统等都是小儿科了。
00014| 
00015| 由上可得到“缠中说禅技术分析基本原理一”：任何级别的任何走势类型终要完成。后面一句用更简练的话，就是“走势终完美”。这个原理的重要性在于把实践中总结出来的、很难实用的、静态的“所有级别的走势都能分解成趋势与盘整”，转化成动态的、可以实用的“走势类型终要完成”，这就是论语所说的智慧：“所有级别的走势都能分解成趋势与盘整”是“不患”的，是无位次的，而“走势类型终要完成”的“走势终完美”以“所有级别的走势都能分解成趋势与盘整”的无位次而位次之，而“患”之。
00016| 
00017| 因为在实际操作中，面对是都是鲜活的、当下的，而正如《论语》所说的，“由知、德者，鲜矣！”，必须直面这种当下、鲜活，才能创造。而在任何一个走势的当下，无论前面是盘整还是趋势，都有一个两难的问题：究竟是继续延续还是改变。例如，原来是在一个趋势中，该趋势是否延续还是改变成相反的趋势或盘整，这样的问题在当下的层次上永远是“不患”的，无位次的。任何宣称自己能解决这个两难问题的，就如同在地球上宣称自己不受地球引力影响一样无效，这是任何面对技术图形的人都必须时刻牢记的。但这个两难的“不患“，在“所有级别的走势都能分解成趋势与盘整”的“不患”下，又成了其“患”，就因此可以位次（该问题的理解，可以参考本ID关于《论语》相关章节的解释）。正因为当下的走势是两难的，也就是在不完美到完美的动态过程中，这就构成了其“不患”而位次的基础。“走势终完美”，而走势“不患”地可以分解成趋势与盘整，换言之，“趋势终完美，盘整也终完美”。
00018| 
00019| “走势终完美”这句话有两个不可分割的方面：任何走势，无论是趋势还是盘整，在图形上最终都要完成。另一方面，一旦某种类型的走势完成以后，就会转化为其他类型的走势，这就是“不患”而有其位次。在技术分析里，不同的位次构成不同的走势类型，各种位次以无位次而位次。而如何在不同位次之间的灵活运动，是实际操作中最困难的部分，也是技术分析最核心的问题之一。
00020| 
00021| 为了深入研究这复杂问题，必须先引入缠中说禅走势中枢的概念：某级别走势类型中，被至少三个连续次级别走势类型所重叠的部分，称为缠中说禅走势中枢。换言之，缠中说禅走势中枢就是至少三个连续次级别走势类型重叠部分所构成。这里有一个递归的问题，就是这次级别不能无限下去，就像有些半吊子哲学胡诌什么“一分为二”，而“分”不是无限的，按照量子力学，物质之分是有极限的，同样，级别之次也不可能无限，在实际之中，对最后不能分解的级别，其缠中说禅走势中枢就不能用“至少三个连续次级别走势类型所重叠”定义，而定义为至少三个该级别单位K线重叠部分。一般来说，对实际操作，都把这最低的不可分解级别设定为1分钟或5分钟线，当然，也可以设定为1秒种线，但这都没有太大区别。
00022| 
00023| 有了上面的定义，就可以在任何一个级别的走势中找到“缠中说禅走势中枢”。有了该中枢，就可以给“盘整”、“趋势”给出一个最精确的定义：
00024| 
00025| 缠中说禅盘整：在任何级别的任何走势中，某完成的走势类型只包含一个缠中说禅走势中枢，就称为该级别的缠中说禅盘整。
00026| 
00027| 缠中说禅趋势：在任何级别的任何走势中，某完成的走势类型至少包含两个以上依次同向的缠中说禅走势中枢，就称为该级别的缠中说禅趋势。该方向向上就称为上涨，向下就称为下跌。
00028| 
00029| 那么，是否可能在某级别存在这样的走势，不包含任何缠中说禅走势中枢？这是不可能的。因为任何图形上的“向上+向下+向上”或“向下+向上+向下”都必然产生某一级别的缠中说禅走势中枢，没有缠中说禅走势中枢的走势图只意味着在整张走势图形上只存在两个可能，就是一次向下后永远向上，或者一次向上后永远向下。要出现这两种情况，该交易品种必然在一定时期交易后永远被取消交易，而这里探讨走势的一般情况，其前提就是该走势可以不断延续下去，不存在永远取消交易的情况，所以，相应有
00030| 
00031| “缠中说禅技术分析基本原理二”：任何级别任何完成的走势类型，必然包含一个以上的缠中说禅走势中枢。
00032| 
00033| 
00034| 由原理一、二以及缠中说禅走势中枢的定义，就可以严格证明：
00035| 
00036| “缠中说禅走势分解定理一”：任何级别的任何走势，都可以分解成同级别“盘整”、“下跌”与“上涨”三种走势类型的连接。
00037| 
00038| “缠中说禅走势分解定理二“：任何级别的任何走势类型，都至少由三段以上次级别走势类型构成。
00039| 
00040| 这些证明都很简单，就和初中几何的证明一样，有兴趣自己来一下。由上面的原理和定理，就可以严格地给出具体操作唯一可以依赖的两个坚实的基础。因为某种类型的走势完成以后就会转化为其他类型的走势，对于下跌的走势来说，一旦完成，只能转化为上涨与盘整，因此，一旦能把握下跌走势转化的关节点买入，就在市场中占据了一个最有利的位置，而这个买点，就是前面反复强调的“第一类买点”；而因为无论是趋势还是盘整在图形上最终都要完成，所以在第一类买点出现后第一次次级别回调制造的低点，是市场中第二有利的位置，为什么？因为上涨和盘整必然要在图形上完成，而上涨和盘整在图形上的要求，是必须包含三个以上的次级别运动，因此后面必须还至少有一个向上的次级别运动，这样的买点是绝对安全的，其安全性由走势的“不患”而保证，这，就是在前面反复强调的第二类买点。买点的情况说了，卖点的情况反之亦然。
00041| 
00042| 综上所述，就不难明白为什么本ID在前面反复强调这两类买卖点了。因为该两类买卖点是被最基础的分析所严格保证的，就如同几何中严格定理一样，只要找准了这两类买卖点，在市场的实际走势中是战无不胜的，是波涛汹涌的市场中最坚实的港湾。关于该两类买卖点与走势及上述原理、定理间密不可破的逻辑关系，必须切实理解体会，这是所有操作中最坚实、最不能混淆的基础。
00043| 
00044| 由上面的原理、定理，就可以继续证明前面已经说过的“缠中说禅买卖点定律一”：任何级别的第二类买卖点都由次级别相应走势的第一类买点构成。
00045| 
00046| 这样，就像前面曾说过的，任何由第一、二类买卖点构成的缠中说禅买卖点，都可以归结到不同级别的第一类买卖点。由此得到“缠中说禅趋势转折定律”：
00047| 
00048| 任何级别的上涨转折都是由某级别的第一类卖点构成的；任何的下跌转折都是由某级别的第一类买点构成的。
00049| 
00050| 注意，这某级别不一定是次级别，因为次级别里可以是第二类买卖点，而且还有这种情况，就是不同级别同时出现第一类买卖点，也就是出现不同级别的同步共振，所以这里只说是某级别。
00051| 
00052| 本ID以上对技术分析的理论构建，绝对前无古人，就像欧几里德之于几何一样。这是为纷繁的技术分析找到了一个坚实的理论基础，由这些原理、定理，可以继续引申出不同的定理，就像几何里面一样。这些定理，都是抛开一切偶然因数的，而实际的操作，必须建立在此之上，才会长期立于不败之地。
00053| 
00054| 这些问题以后还要逐步展开，这里先把两个前面已经让各位思考例子来分析一下，让各位对趋势、级别、走势中枢等概念有一个感性的认识，毕竟上面抽象的方法并不是每个人都能理解的：
00055| 
00056| 驰宏锌锗：为什么从2004年6月2日到2005年7月27日，构成标准的“下跌+盘整+下跌”的走势，而类似的图形在580991上不算，这唯一的原因就是因为后者在日线的下跌中并不构成日线级别的缠中说禅走势中枢，而在30分钟线上，这个中枢是明确的。所以580991只构成30分钟级别上的“下跌+盘整+下跌”。
00057| 
00058| 其后的上涨，对600497驰宏锌锗， 2005年7月27日到10月25日，明确地出现在日线上的上涨走势（为什么？因为在日线上明确地看到两个缠中说禅走势中枢）。而580991从2006年10月23日到12月13日，只构成日线上的盘整走势（为什么？因为在日线上明确地看到一个缠中说禅走势中枢）。
00059| 
00060| 两者力度上有如此区别的技术上的原因就是上面两个：一、“下跌+盘整+下跌”走势的出现级别不同，一个是日线，一个是30分钟的。二、其后的第一段走势，一个是日线上涨，一个是日线盘整。
00061| 
00062| <div style={{textAlign: 'left'}}>
00063| <img src={useBaseUrl('/img/stocks/017/600497_d1.png')} /><br/><br/>
00064| </div>
00065| 
00066| <div style={{textAlign: 'left'}}>
00067| <img src={useBaseUrl('/img/stocks/017/600497_d2.png')} /><br/><br/>
00068| </div>
00069| 
00070| <div style={{textAlign: 'left'}}>
00071| <img src={useBaseUrl('/img/stocks/017/580991_d.png')} /><br/><br/>
00072| </div>
00073| 
00074| <div style={{textAlign: 'left'}}>
00075| <img src={useBaseUrl('/img/stocks/017/580991_30f_1.png')} /><br/><br/>
00076| </div>
00077| 
00078| <div style={{textAlign: 'left'}}>
00079| <img src={useBaseUrl('/img/stocks/017/580991_30f_2.png')} /><br/><br/>
00080| </div>
00081| 
00082| <div style={{textAlign: 'left'}}>
00083| <img src={useBaseUrl('/img/stocks/017/580991_30f_3.png')} /><br/><br/>
00084| </div>
00085| 
00086| <div style={{textAlign: 'left'}}>
00087| <img src={useBaseUrl('/img/stocks/017/580991_d2.png')} /><br/><br/>
00088| </div>
00089| 
00090| 以上内容，足够各位消化几天了。后面还有很多内容，逐一写来。但请注意版权，发现抄袭的本ID要抓来狗头铡给铡了。最后布置几条思考题：
00091| 
00092| 1、 连接两相邻同级别缠中说禅走势中枢的一定是趋势吗？一定是次级别的趋势吗？<br/>
00093| 2、 背驰是两相邻同向趋势间，后者比前者的走势力度减弱所造成的，如果用均线或MACD等判断其力度，一定要在同级别的图上吗？同级别的MACD红绿柱子背驰一定反映某级别趋势间出现背驰吗？是相应级别的趋势出现背驰吗？<br/>
00094| 3、 盘整的高低点是如何造成的。（这个问题有点难度，提示，用缠中说禅走势中枢以及级别等进行分析。）
00095| 
00096| ### 回复
00097| 
00098| <div class='blog-comment'>
00099| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 11:56:31<br/>
00100| 好好消化，如何把抽象的理论变成自己的直觉，无论是谁，可不是一两天的事情。
00101| </div>
00102| 
00103| <div class='blog-comment'>
00104| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 12:05:33<br/>
00105| [匿名] ataoo0 <br/><br/>
00106| 
00107|  
00108| 2006-12-18 11:54:42 <br/>
00109| 可惜周五没受到楼主的托梦，，，还是希望楼主以后能多多梦到此类情景～～～～～～～～～～～～ <br/>
00110|  
00111| =========<br/>
00112| 
00113| 消息是没意义的，本ID那只是八卦一下。这几年的主题，本ID早说过了，就是收购中国。中国最大的特色是什么？人多，去年，本ID就一直和很多国外的基金接触，他们最大的目标就是中国的快速消费品市场，虽然本ID也很烦鬼佬，但他们绝对不是傻子。可惜，国人里的傻子太多了，而且傻子还话语权。
00114| </div>
00115| 
00116| <div class='blog-comment'>
00117| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 12:11:41<br/>
00118| 小明 <br/><br/>
00119| 
00120|  
00121| 2006-12-18 12:07:39 <br/>
00122| 双汇，青啤，还有谁？
00123| 
00124| 哦，请问缠mm对林园感觉如何？<br/>
00125| 有没有见过他？ 
00126|  
00127| ======<br/>
00128| 对不起，本ID只对市场本身有兴趣，市场里的所谓英雄狗熊，一点兴趣都没有。牛人，本ID见过太多，可惜，最后基本都死了。
00129| </div>
00130| 
00131| <div class='blog-comment'>
00132| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 12:24:16<br/>
00133| [匿名] nn <br/><br/>
00134| 
00135|  
00136| 2006-12-18 12:21:11 <br/>
00137| 先报到,后阅读,谢谢了!<br/>
00138| 另外,向楼主提个建议,为了方便大家检索你解的论语,建议楼主将每一讲的标题改为如下形式:论语祥解(41):孔子曰∶生而知之者，上也；学而知之者，次也；困而学之，又其次也。困而不学，民斯为下矣！<br/>
00139| 无论可否,先谢了!
00140|  
00141|  
00142| ==========<br/>
00143| 
00144| 题目不能怎么长吧，新浪不允许。最简单的就是复制到自己的电脑里，这是最好检索的。
00145| </div>
00146| 
00147| <div class='blog-comment'>
00148| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 12:48:50<br/>
00149| [匿名] lazycat588 <br/><br/>
00150| 
00151|  
00152| 2006-12-18 12:38:06 <br/>
00153| 可否转载您的文章？ 谢谢<br/>
00154| 当然会注明出处 
00155|  
00156| ===<br/>
00157| 
00158| 可以，但一定要顺便推广一下本博客。本博客怎么都应该比孔男人的火暴点吧。
00159| </div>
00160| 
00161| <div class='blog-comment'>
00162| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 12:51:20<br/>
00163| 各位慢慢消化，先下，再见。
00164| </div>
00165| 
00166| <div class='blog-comment'>
00167| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 15:15:02<br/>
00168| [匿名] 喝杯小酒 <br/><br/>
00169| 
00170|  
00171| 2006-12-18 14:38:04 <br/>
00172| 今儿哥哥批评缠妹几句<br/>
00173| 1、当前大牛市，不是谈细技术的时候，你的理论不适合当前，多教点选股大思路。<br/>
00174| 2、你的理论有些过时，单说指标这东西，用的人多了，就不准确了。<br/>
00175| 3、不许再说“消息准确”的话，那不算啥，高人应该高在别处。 
00176|  
00177| =========<br/>
00178| 
00179| 整个大牛市的图景，本ID1年半前就画好了，第一轮成分股，成分股就是那300只，还选什么选？
00180| 
00181| 现在说的不是指标，先把问题搞清楚。
00182| 
00183| 消息准确怎么了，能全国消息最准确的，代表了什么？代表了一种行业地位。
00184| </div>
00185| 
00186| <div class='blog-comment'>
00187| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 15:18:38<br/>
00188| [匿名] 中间体 <br/><br/>
00189| 
00190|  
00191| 2006-12-18 15:11:25 <br/>
00192| 缠中说禅走势中枢的概念：某级别类型走势中，被至少三个连续次级别类型走势所重叠的部分，称为缠中说禅走势中枢。
00193| 
00194| 次级别的走势怎样去重叠高级别??? 60分钟K线图去模拟日K线图吗?? 请举例
00195| 
00196| 弄懂中枢很关键啊 !! 
00197|  
00198| ==========<br/>
00199| 不是次级别重叠高级别，是次级别之间的重叠。
00200| </div>
00201| 
00202| <div class='blog-comment'>
00203| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 15:22:32<br/>
00204| [匿名] 想飞 <br/><br/>
00205| 
00206|  
00207| 2006-12-18 15:04:25 <br/>
00208| LZ，问好！<br/>
00209| “而580991从2006年10月23日到12月13日，只构成日线上的盘整走势（为什么？因为在日线上明确地看到一个缠中说禅走势中枢）。”<br/>
00210| 这句话中提到的那个缠中说禅走势中枢是指10/23~11/8，还是11/14~11/21，如果看30分钟图，应该是指前者对吗？ 
00211|  
00212| =======<br/>
00213| 
00214| 都不对，是11月8日到11月28日，是三个次级趋势构成 。
00215| </div>
00216| 
00217| <div class='blog-comment'>
00218| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 15:26:28<br/>
00219| 
00220| 再布置一个具体的股票
00221| 
00222| 请分析一下北辰12月7日以来走势的具体级别、走势类型。
00223| 
00224| <div style={{textAlign: 'left'}}>
00225| <img src={useBaseUrl('/img/stocks/017/601588_d.png')} /><br/><br/>
00226| </div>
00227| 
00228| <div style={{textAlign: 'left'}}>
00229| <img src={useBaseUrl('/img/stocks/017/601588_30f.png')} /><br/><br/>
00230| </div>
00231| 
00232| <div style={{textAlign: 'left'}}>
00233| <img src={useBaseUrl('/img/stocks/017/601588_5f.png')} /><br/><br/>
00234| </div>
00235| </div>
00236| 
00237| <div class='blog-comment'>
00238| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 15:27:52<br/>
00239| [匿名] 中间体 <br/><br/>
00240| 
00241|  
00242| 2006-12-18 15:23:32 <br/>
00243| 缠姐, 给举个例讲一下吧, 什么样叫重叠?? 
00244|  
00245| ========<br/>
00246| 
00247| 580991从11月8日到11月28日，三个次级趋势构成的日线中枢 。
00248| </div>
00249| 
00250| <div class='blog-comment'>
00251| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 15:47:11<br/>
00252| [匿名] 小小 <br/><br/>
00253| 
00254|  
00255| 2006-12-18 15:34:29 <br/>
00256| 请问禅姐,600519在10上位第二次缠绕后8.7日形成背弛,那第一个问题:10上位的第一次缠绕是7.4日还是7.24日?<br/>
00257| 第二, 10上位的第一次缠绕是那一天结束的?这两个问题是我最湖涂的请禅姐给说明,我一直坐在这里等你!
00258|  
00259|  
00260| ==========<br/>
00261| 
00262| 用均线或MACD看背驰都是辅助性的，都不是最重要的，最重要的是把今天的搞清楚，这是最重要的。关于背驰相关的问题，本ID后面会继续说的。先把逻辑关系搞清楚：
00263| 
00264| 走势--级别--趋势--前后趋势比较-背驰-用均线等辅助判断背驰
00265| 
00266| 所以先把前面搞清楚，别困在一些某节上，前面明白了，后面自然清楚。
00267| 
00268| 难道没有均线、没有MACD就判断不了背驰？显然不是。那只是辅助。
00269| </div>
00270| 
00271| <div class='blog-comment'>
00272| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 15:55:14<br/>
00273| 各位好好研究吧，真明白了，终身受用。如果你希望知道什么黑马之类的，这里没有，300只成分股，牛市结束后一看，都是黑马，牛市里有什么黑马，都是黑马，还用找吗？关键是你是否有持有的信心。牛市炒股票还用这么费心？前面本ID已经多次说过，牛市首先要灭的就是熊市心态，有时间先把基础搞好吧，本ID这里不帮任何人，你们个个是佛，本ID忙个什么帮？别憋屈自己了。
00274| </div>
00275| 
00276| <div class='blog-comment'>
00277| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 15:58:21<br/>
00278| [匿名] 中间体 <br/><br/>
00279| 
00280|  
00281| 2006-12-18 15:53:12 <br/>
00282| 缠中说禅 
00283| 
00284| 2006-12-18 15:27:52 <br/>
00285| [匿名] 中间体 <br/><br/>
00286| 
00287| 
00288| 2006-12-18 15:23:32 <br/>
00289| 缠姐, 给举个例讲一下吧, 什么样叫重叠?? 
00290| 
00291| ========<br/>
00292| 
00293| 580991从11月8日到11月28日，三个次级趋势构成的日线中枢 。 <br/>
00294| 
00295| \--------------------
00296| 
00297| 缠姐, 我知道今天一课很重要, 你能否具体讲一讲, 三个次级趋势如何构成的日线中枢 ?? 我用60分, 30分,15分钟图对比看不出什么名堂啊, 麻烦了,碰到如此笨的学生. 
00298|  
00299|  
00300| =======<br/>
00301| 这不最简单的事情吗？三段走势，不正好构成一个重叠吗？区间就在0。677与0。803之间，构成中枢。
00302| </div>
00303| 
00304| <div class='blog-comment'>
00305| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 16:12:28<br/>
00306| [匿名] 游客 <br/><br/>
00307| 
00308|  
00309| 2006-12-18 16:05:12 <br/>
00310| “中枢”的概念还是不清楚。烦请解惑：
00311| 
00312| 请教：“某级别类型走势中，被至少三个连续次级别类型走势所重叠的部分”比如是指周线、日线、小时线的K线重叠吗？ 
00313|  
00314| 
00315| ========<br/>
00316| 
00317| 不是几条K线的重叠，是至少三个连续次级别类型走势重叠部分所构成。
00318| </div>
00319| 
00320| <div class='blog-comment'>
00321| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 16:13:59<br/>
00322| [匿名] 中间体 <br/><br/>
00323| 
00324|  
00325| 2006-12-18 16:07:26 <br/>
00326| 这不最简单的事情吗？三段走势，不正好构成一个重叠吗？区间就在0。677与0。803之间，构成中枢。
00327| 
00328| 请讲明, 从哪到哪是一段, 哪三段??? 
00329|  
00330| ========<br/>
00331| 
00332| 这么简单的问题自己去思考，本ID回答你是害了你，你就不思考了。那几天，在图上就这下上下的三段，这还用本ID说吗？
00333| </div>
00334| 
00335| <div class='blog-comment'>
00336| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 16:14:59<br/>
00337| [匿名] 心禅 <br/><br/>
00338| 
00339|  
00340| 2006-12-18 16:03:56 <br/>
00341| “禅主”601588“北辰”作业：
00342| 
00343| 从其30分钟图看，12月7日-12月12日为下跌，12日-18日13：00为盘整期，今天下午上涨；一个“下跌+盘整+上涨”<br/>
00344| 禅主，我也判断它周一会结束盘整，可我按“下跌+盘整+下跌”原则考虑，判断它今天会再次下探，为什么会错？请指正 
00345|  
00346| =========<br/>
00347| 
00348| 谁告诉你股票一定要走出“下跌+盘整+下跌”的？基本概念要搞清楚。
00349| 
00350| <div style={{textAlign: 'left'}}>
00351| <img src={useBaseUrl('/img/stocks/017/601588_30f_answer.png')} /><br/><br/>
00352| </div>
00353| </div>
00354| 
00355| <div class='blog-comment'>
00356| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 16:16:54<br/>
00357| 
00358| 公告
00359| 
00360| 以后要本ID直接告诉答案的，本ID一律不回答，回答是害了各位，各位必须先思考，把自己的答案找出来，本ID来给各位评判，这样才有助于各位。
00361| </div>
00362| 
00363| <div class='blog-comment'>
00364| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 16:24:54<br/>
00365| [匿名] 一剑 <br/><br/>
00366| 
00367|  
00368| 2006-12-18 16:16:17 <br/>
00369| 缠姐：<br/>
00370| 和你探讨《货币战争和人民币策略》 一文，我认为目前中国经济高度依赖美国消费市场， 大量顺差间接享用美国经济虚拟化所带好处，所以在目前应该配合美圆贬值战略，以继续保持美国经济体系运转，所以第一买入点应该在未来而不是现在。 请赐教！ 
00371|  
00372| ========<br/>
00373| 2005年7月前，人民币和美圆直接挂钩，就成了双核，对世界其他体系进行盘剥，中国借机长大，如藤绕树一般。而现在，是美国对所有人的盘剥，中国现在刚进入破位之中，把一个好好的“上涨+盘整+上涨”弄成“上涨+盘整+下跌”，这时候还谈什么第一类买点？鼻子都给人牵着走了。
00374| 
00375| 另外，少用什么配合的说法，中国人凭什么要配合美国。中国对美国只有两种：一种叫利用，一种叫被利用。
00376| 
00377| 可惜现在是被利用了，一群大傻瓜！
00378| </div>
00379| 
00380| <div class='blog-comment'>
00381| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 16:27:44<br/>
00382| [匿名] 中间体 <br/><br/>
00383| 
00384|  
00385| 2006-12-18 16:18:34 <br/>
00386| 谢谢, 其实, 我们是没理解缠姐的表达, 这个'重叠'到底是什么?? 怎样就是重叠? 我们不理解啊.  <br/><br/>
00387|  
00388| 
00389| 
00390| 
00391| [匿名] 求知 <br/><br/>
00392| 
00393|  
00394| 2006-12-18 16:18:38 <br/>
00395| “中枢”的概念太重要了，也太抽象了，本人愚笨，还请结合例子细致一点解释。<br/>
00396| 先谢了！！！！！！！！！！！！！！ 
00397|  
00398| =========<br/>
00399| 
00400| 这不最简单的问题？A段经过8元到18元，B段经过18元到12元，C段经过12元到24元，你说这ABC三段的重叠部分在什么地方？
00401| 
00402| 如果这都回答不出来，本ID也没办法了，因为这幼儿园的小朋友都能回答。
00403| </div>
00404| 
00405| <div class='blog-comment'>
00406| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 16:34:32<br/>
00407| 
00408| 各位把下面这个定义好好读读：
00409| 
00410|   > 缠中说禅走势中枢的概念：某级别类型走势中，被至少三个连续次级别类型走势所重叠的部分，称为缠中说禅走势中枢。换言之，缠中说禅走势中枢就是至少三个连续次级别类型走势重叠部分所构成。
00411| 
00412| 关键是这几词：三个、连续、次级别、重叠。
00413| 
00414| 例子，580991
00415| 
00416| 在11月8日到11月28日，构成0。677到0。803的中枢。
00417| 
00418| 一看就明白，看图明白才是真明白。
00419| </div>
00420| 
00421| <div class='blog-comment'>
00422| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 16:36:15<br/>
00423| [匿名] 如 <br/><br/>
00424| 
00425|  
00426| 2006-12-18 16:30:03 <br/>
00427| 当下最紧要的一个请教问题,望不吝赐教.
00428| 
00429| 关于在上一课中,提到的,如何判断盘整后的图形,是上涨还是会下跌. 能否说明.?<br/>
00430| 目前股市,相当多的个股,正是上涨+盘整的走势,或者是上涨+下跌+盘整.........<br/>
00431| 而如何判明这盘整治之后的走势,还有,如何判断什么是有效突破,成了偶目前的当务之急, 请详细说明,不胜感激.. 
00432|  
00433| =======<br/>
00434| 
00435| 你看到ID文中的作业没有？
00436| 
00437| 3、 盘整的高低点是如何造成的。（这个问题有点难度，提示，用缠中说禅走势中枢以及级别等进行分析。）
00438| 
00439| 
00440| 把这个回答出来，就能解决你的问题。
00441| </div>
00442| 
00443| <div class='blog-comment'>
00444| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 16:41:19<br/>
00445| [匿名] 巴索林 <br/><br/>
00446| 
00447|  
00448| 2006-12-18 16:00:26 <br/>
00449| 一直在看缠mm的文章，觉得缠mm的思想既有广度又有深度，思维严谨，逻辑性强，而且文章诙谐、幽默。令我辈从中获益不少。对缠mm有教无类，诲人不倦的精神深感敬意和感谢。但心中有一疑惑，在此顺便问问缠mm，望解答。既然高手无论在牛市还是熊市都能在股市提款，为什么缠mm2001年~2005年却不看一眼股票呢？是否像你这样的高手也要回避熊市呢？那么职业股民在熊市中岂不要转行了？ 
00450|  
00451| ==========<br/>
00452| 
00453| 本ID又不等钱花，为什么要花精力在熊市里忙？有技术，熊市一样挣钱，这没错，但这种钱本ID早没兴趣了。
00454| 
00455| 人生有很多事情可以干，关键是要明白当下最值得干什么。有大牛市，本ID当然不会错过，那种破熊市里的破行情，值得本ID去浪费时间吗？
00456| </div>
00457| 
00458| <div class='blog-comment'>
00459| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 16:48:43<br/>
00460| 
00461| 本ID十分理解各位急着挣钱的心理，但这种心理本来就是市场参与者的大忌，连自己的心都控制不住，对自己的贪婪、欲望都不能控制，是不能在市场中长久成功的。
00462| 
00463| 心态平和点，焦躁没有智慧。
00464| </div>
00465| 
00466| <div class='blog-comment'>
00467| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 16:56:38<br/>
00468| [匿名] 一剑 <br/><br/>
00469| 
00470|  
00471| 2006-12-18 16:44:58 <br/>
00472| “2005年7月前，人民币和美圆直接挂钩，就成了双核，对世界其他体系进行盘剥，中国借机长大，如藤绕树一般。而现在，是美国对所有人的盘剥，中国现在刚进入破位之中，把一个好好的“上涨+盘整+上涨”弄成“上涨+盘整+下跌”，这时候还谈什么第一类买点？鼻子都给人牵着走了”
00473| 
00474| 
00475| ---------就好象两个壮女人去逛面首店，面首店只有一个快被榨干了的小面首，两个壮女人如何盘剥啊？ 只怕落个整个面首店崩盘， 所以现在只好让美国这个壮女人先盘剥，我们先听听声音，否则美国这个壮女人没有面首活不下去了，我们也无法从她身上吸油了，连个淫声都听不见了。。。。 
00476|  
00477| =======<br/>
00478| 
00479| 不对，而是一个大蛋糕，美国人习惯性占全份的，习惯性分蛋糕，而某些蠢人或别有用心者有意无意地顺着美国人去了。
00480| 
00481| 中国的事情其实一直很简单，不是蠢人太多，而是汉奸太多。
00482| </div>
00483| 
00484| <div class='blog-comment'>
00485| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 16:58:17<br/>
00486| [匿名] 小小 <br/><br/>
00487| 
00488|  
00489| 2006-12-18 16:52:25 <br/>
00490| 禅姐,600519在10上位第二次缠绕后8.7日形成背弛,那10上位的第二次缠绕是那一天开始那一天结束呀？ 
00491|  
00492| =======<br/>
00493| 你看不到本ID上面的回答吗？复制如下：
00494| 
00495| 用均线或MACD看背驰都是辅助性的，都不是最重要的，最重要的是把今天的搞清楚，这是最重要的。关于背驰相关的问题，本ID后面会继续说的。先把逻辑关系搞清楚：
00496| 
00497| 走势--级别--趋势--前后趋势比较-背驰-用均线等辅助判断背驰
00498| 
00499| 所以先把前面搞清楚，别困在一些某节上，前面明白了，后面自然清楚。
00500| 
00501| 难道没有均线、没有MACD就判断不了背驰？显然不是。那只是辅助。
00502| </div>
00503| 
00504| <div class='blog-comment'>
00505| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 17:06:54<br/>
00506| 
00507| 公告
00508| 
00509| 各位知道为什么智慧难得吗？就因为偷心不死，整天想着捷径，想着一夜暴富。你看看真正成功的人，有哪个是靠中彩票的？
00510| 
00511| 要在市场上成功，首先要把这偷心给废了，否则学什么都没用，一到场上就犯糊涂，然后就后悔、自责，然后又继续犯糊涂。
00512| 
00513| 道理是死的，用的是人，人没道理，什么道理都没用。
00514| 
00515| 没错，本ID可以告诉你消息，让你买所谓的黑马，但就算让你买了，你可能也守不住。你回头看看，有多少黑马是你曾经买过的，如果都留到现在，你还用找黑马吗？
00516| 
00517| 别说找不到黑马，而是好好想想，为什么黑马都避着自己。
00518| </div>
00519| 
00520| <div class='blog-comment'>
00521| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/18 17:09:28<br/>
00522| 
00523| 各位，请把那四个作业好好想想吧，如果真想学点什么。
00524| 
00525| 先下，再见。
00526| </div>

(End of file - total 526 lines)
</file>
```
```

```
Tool: read

**Input:**
```json
{
  "filePath": "/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/018.md"
}
```
**Output:**
```
<file>
00001| ---
00002| id: '018'
00003| title: ''
00004| hide_table_of_contents: true
00005| ---
00006| 
00007| import useBaseUrl from '@docusaurus/useBaseUrl';
00008| 
00009| # 教你炒股票18：不被面首的雏男是不完美的。
00010| 
00011| > 2006/12/26 15:05:58
00012| 
00013| 首先把前面一些最基本的概念、原理、定理列举如下：
00014| 
00015| 走势：打开走势图看到的就是走势。走势分不同级别。<br/>
00016| 走势类型：上涨、下跌、盘整。<br/>
00017| 趋势：上涨、下跌。
00018| 
00019| 缠中说禅走势中枢：某级别走势类型中，被至少三个连续次级别走势类型所重叠的部分。具体的计算以前三个连续次级别的重叠为准，严格的公式可以这样表示：次级别的连续三个走势类型A、B、C，分别的高、低点是a1\a2,b1\b2,c1\c2。则，中枢的区间就是（max（a2,b2,c2），min（a1,b1,c1））而实际上用目测就可以，不用这么复杂。注意，次级别的前三个走势类型都是完成的才构成该级别的缠中说禅走势中枢，完成的走势类型，在次级别图上是很明显的，根本就不用着再看次级别下面级别的图了。
00020| 
00021| <div style={{textAlign: 'left'}}>
00022| <img src={useBaseUrl('/img/stocks/018/zhongshu.png')} /><br/><br/>
00023| </div>
00024| 
00025| 缠中说禅盘整：在任何级别的任何走势中，某完成的走势类型只包含一个缠中说禅走势中枢，就称为该级别的缠中说禅盘整。
00026| 
00027| 缠中说禅趋势：在任何级别的任何走势中，某完成的走势类型至少包含两个以上依次同向的缠中说禅走势中枢，就称为该级别的缠中说禅趋势。该方向向上就称为上涨，向下就称为下跌。注意，趋势中的缠中说禅走势中枢之间必须绝对不存在重叠。
00028| 
00029| “缠中说禅技术分析基本原理一”：任何级别的任何走势类型终要完成。<br/>
00030| “缠中说禅技术分析基本原理二”：任何级别任何完成的走势类型，必然包含一个以上的缠中说禅走势中枢。<br/>
00031| “缠中说禅走势分解定理一”：任何级别的任何走势，都可以分解成同级别“盘整”、“下跌”与“上涨”三种走势类型的连接。<br/>
00032| “缠中说禅走势分解定理二“：任何级别的任何走势类型，都至少由三段以上次级别走势类型构成。
00033| 
00034| 原理一“任何级别的任何走势类型终要完成”，这最简单的话，却包含着技术分析最基本的东西，其哲学和灵魂都在此，否则就不可能被列为原理一了，这是最重要的。一个最简单的问题，如何判断一个走势类型完成了？这是技术分析里最核心的问题之一，例如，一旦判断知道了 “下跌”的结束，就知道随后必须要面对的是“盘整”与“上涨”，而后两种走势，对于多头来说，都必然产生利润，唯一区别，就是大小与快慢的问题。如果在市场中能找到一种百分百确定的赢利模式，那就是最伟大的成就了，至于大小、快慢，可以继续研究出新的标准来进行判断，而在逻辑上，这是后话了。
00035| 
00036| 这里最大的也是唯一的难点在于“走势类型的延伸”。例如一个盘整，三个重叠的连续次级别走势类型后，盘整就可以随时完成，也就是说，只要三个重叠的连续次级别走势类型走出来后，盘整随时结束都是完美的，但这可以不结束，可以不断延伸下去，不断围绕这缠中说禅中枢上上下下地延伸下去直到无穷都是可以的。这有点像一个雏男在某种标准达到后就具有立刻成为面首的条件，随时可以被面首，但却也可以一直坚持下去，一直自我封闭，一直不让消费，最后把自己给浪费掉了，直到最后变成一个烂苹果。
00037| 
00038| 同样，面对趋势，形成两个依次同向的缠中说禅走势中枢后，任何趋势都可以随时结束而完美，但也可以不断地延伸下去，形成更多的中枢。这种情况在实际操作中太常见了，如果这趋势是向上的，会不断上涨，看看600519之类的图，如果把复权算上，就可以看到一个标准的不断延伸的上涨。大盘2005年见底后的30分钟图上，同样可以看到这种情况。很多人抓不住牛股，经常在第一个中枢时就被震下马，最主要就是对此没有明确的认识。反之，对于下跌的延伸，是所有抄底者的噩梦。逃顶、抄底为何难？归根结底就是这“走势类型的延伸”闹的。
00039| 
00040| <div style={{textAlign: 'left'}}>
00041| <img src={useBaseUrl('/img/stocks/018/600519.png')} /><br/><br/>
00042| </div>
00043| 
00044| <div style={{textAlign: 'left'}}>
00045| <img src={useBaseUrl('/img/stocks/018/1A0001.png')} /><br/><br/>
00046| </div>
00047| 
00048| 如何判别“走势类型延伸”是否结束？这里，必须首先搞清楚，“走势类型延伸”的实质是什么？对于趋势来说，其“延伸”就在于同级别的同向“缠中说禅走势中枢”不断产生；而对于盘整来说，其“延伸”就在于不能产生新的“缠中说禅走势中枢”。由于“走势类型延伸”意味着当下的“走势类型”随时可以完成，因此相应的“类型”必然是确定的，因此“走势类型延伸”是否结束的判断关键就在于是否产生新的“缠中说禅走势中枢”。此外，由于趋势至少包含两个“缠中说禅走势中枢”，而盘整之有一个，因此趋势与盘整的判别关键也就在于是否产生新的“缠中说禅走势中枢”。由此可见，“缠中说禅走势中枢”的问题是技术分析中的核心问题，该问题一旦解决，很多判断上的大难题也将引刃而解。
00049| 
00050| “缠中说禅走势中枢定理一”：在趋势中，连接两个同级别“缠中说禅走势中枢”的必然是次级别以下级别的走势类型。
00051| 
00052| 用反证法，该定理的证明是很简单的，而这也回答了上一章中的作业一“连接两相邻同级别缠中说禅走势中枢的一定是趋势吗？一定是次级别的趋势吗？”首先，这不必然是趋势，任何走势类型都可能，最极端的就是跳空缺口后形成新的“缠中说禅走势中枢”；其次，也不一定是次级别的，只要是次级别以下，例如跳空缺口，就属于最低级别，如果图上是日线、周线，就不会是次级别了；最后，往往相连走势类型的级别越低，表示其力度越大，这也就是为什么缺口在分析中有比较强技术含义的理论依据所在。
00053| 
00054| 由定义知道，“缠中说禅走势中枢”的产生原因以及判断标准，也就是其“生”问题已经解决，那余下的就是其“住、坏、灭”的问题。也就是说，一个“缠中说禅走势中枢”是如何“维持”以及最终被“破坏”进而废弃的。先考虑其“维持”的问题。维持“缠中说禅走势中枢”的一个充分必要条件就是任何一个离开该中枢的走势类型都必须是次级别以下的并以次级别以下的走势类型返回，该问题很容易证明，因为无论是离开还是返回，只要是同级别的走势类型，就意味着形成新的“缠中说禅走势中枢”，这与原中枢的维持前提矛盾。该命题表述成如下定理：
00055| 
00056| “缠中说禅走势中枢定理二”：在盘整中，无论是离开还是返回“缠中说禅走势中枢”的走势类型必然是次级别以下的。
00057| 
00058| 由此，上一章作业三“盘整的高低点是如何造成的”就有了相应的答案：无论离开与返回的走势类型是何种级别的，在站最低级别上看，例如把1分钟图当成最低级别，那么最后连接离开与返回走势类型连接处的最低级别图，只能有两种可能：三根以上1分钟K线的来回重叠震荡后回头；二、1分钟K线无三根以上K线重叠的V型走势。对于第一种情况，这几根重叠K线最极端那根的极端位置，就构成盘整中的高低点，一般来说，这种情况比较少见；对于第二种情况，这个V型尖顶那根K线的极端位置就构成盘整中的高低点，这种情况十分常见。这也是为何真正的低点和高点总是盘中一闪而过的理论依据。本ID的理论能解释技术图表上任何细致的问题，这才是一种真正理论所应该具有的品质。这种的理论，不需要什么诺贝尔的奖励，那一百万美圆在市场上算得了什么？精通这样的理论，市场会给予你多得多的回报。
00059| 
00060| 有了上面两个“缠中说禅走势中枢”定理，不难证明定理三：
00061| 
00062| 某级别“缠中说禅走势中枢”的破坏，当且仅当一个次级别走势离开该“缠中说禅走势中枢”后，其后的次级别回抽走势不重新回到该“缠中说禅走势中枢”内。
00063| 
00064| 这定理三中的两个次级别走势的组合只有三种：趋势+盘整，趋势+反趋势，盘整+反趋势。其中的趋势分为上涨与下跌，分别代表从上方突破与下方跌破两种情况。而站在实用的角度，最用力的破坏，就是：趋势+盘整。例如在上涨中，如果一个次级别走势向上突破后以一个盘整走势进行整理回抽，那其后的上涨往往比较有力，特别这种突破是在底部区间。这种情况太常见了，其理论依据就在这里。
00065| 
00066| ### 回复
00067| 
00068| <div class='blog-comment'>
00069| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/26 15:09:24<br/>
00070| 对不起，有一个重要的谈判，要去中关村，必须马上走，有问题请放在这，晚上回来回答。
00071| </div>
00072| 
00073| <div class='blog-comment'>
00074| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/26 15:12:05<br/>
00075| 
00076| 大盘现在的走势十分正常，96年那次，发展涨了N倍了，很多股票都没涨，工行现在连一倍都没到，算得了什么？成分股就是牛市第一轮的最重要股票，多次说了，就不要埋怨了。
00077| 
00078| 下了，再见。
00079| </div>
00080| 
00081| <div class='blog-comment'>
00082| <span class='blog-comment-chan'>缠中说禅</span> 2006/12/26 21:28:26<br/>
00083| 
00084| 今天回来太晚了，各位好好自己研究一下，别没怎么认真思考就随便发问，这样是学不到东西的。
00085| 
00086| 晚安，再见。
00087| </div>

(End of file - total 87 lines)
</file>
```
```

---

## Assistant (Plan · minimax-m2.1-free · 6.9s)

_Thinking:_

很好，我现在开始看到缠论的核心内容了。让我继续阅读更多关键文章，特别是关于分型、笔、线段、买卖点、背驰等核心概念的文章。

```
Tool: read

**Input:**
```json
{
  "filePath": "/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/062.md"
}
```
**Output:**
```
<file>
00001| ---
00002| id: '062'
00003| title: ''
00004| hide_table_of_contents: true
00005| ---
00006| 
00007| import useBaseUrl from '@docusaurus/useBaseUrl';
00008| 
00009| # 教你炒股票62：分型、笔与线段
00010| 
00011| > 2007/6/30 9:49:51
00012| 
00013| 在宾馆里闲着等着10点开始的腐败，半个小时，找个面首来面首有点时间紧张，还不如给各位写个主贴，来个课程，耗费一下各位周末腐败的时间。
00014| 
00015| 瞧了一下，有位叫石猴的网友写了帖子来解释什么是线段，他的理解还行，但不够严密。其实，本ID的线段是可以最精确定义的，本ID的理论，本质上是一套几何理论，其有效性就如同几何一般，本ID理论当然有失败不严谨的时候，但这前提是几何的基础失败不严谨，不明白这一点，就不明白本ID的理论。这里，就把本来是后面的课程提前说说。
00016| 
00017| 下面的定义与图，都适合任何周期的K线图。先看图中的第1、2，图中的小线段代表的是K线，这里不分阳线阴线，只看K线高低点。
00018| 
00019| <img src={useBaseUrl('/img/stocks/062/xianduan.jpeg')} /> <br/><br/>
00020| 
00021| 像图1这种，第二K线高点是相邻三K线高点中最高的，而低点也是相邻三K线低点中最高的，本ID给一个定义叫顶分型；图2这种叫底分型，第二K线低点是相邻三K线低点中最低的，而高点也是相邻三K线高点中最低的。看不明白定义的，看图就明白了，这么直观都不明白，那去和孔男人为伍吧。
00022| 
00023| 顶分型的最高点叫该分型的顶，底分型的最低点叫该分型的底，由于顶分型的底和底分型的顶是没有意义的，所以顶分型的顶和底分型的底就可以简称为顶和低。也就是说，当我们以后说顶和底时，就分别是说顶分型的顶和底分型的底。
00024| 
00025| 两个相邻的顶和底之间构成一笔，所谓笔，就是顶和底之间的其他波动，都可以忽略不算，但注意，一定是相邻的顶和底，隔了几个就不是了。而所谓的线段，就是至少由三笔组成。但这里有一个细微的地方要分清楚，因为结合律是必须遵守的，像图3这种，顶和底之间必须共用一个K线，这就违反结合律了，所以这不算一笔，而图4，就光是顶和底了，中间没有其他K线，一般来说，也最好不算一笔，而图5，是一笔的最基本的图形，顶和底之间还有一根K线。在实际分析中，都必须要求顶和底之间都至少有一K线当成一笔的最基本要求。
00026| 
00027| 当然，实际图形里，有些复杂的关系会出现，就是相邻两K线可以出现如图6这种包含关系，也就是一K线的高低点全在另一K线的范围里，这种情况下，可以这样处理，在向上时，把两K线的最高点当高点，而两K线低点中的较高者当成低点，这样就把两K线合并成一新的K线；反之，当向下时，把两K线的最低点当低点，而两K线高点中的较低者当成高点，这样就把两K线合并成一新的K线。经过这样的处理，所有K线图都可以处理成没有包含关系的图形。
00028| 
00029| 而图7，就给出了经过以上处理，没有包含关系的图形中，三相邻K线之间可能组合的一个完全分类，其中的二、四，就是分别是顶分型和底分型，一可以叫上升K线，三可以叫下降K线。所以，上升的一笔，由结合律，就一定是底分型+上升K线+顶分型；下降的一笔，就是顶分型+下降K线+底分型。注意，这里的上升、下降K线，不一定都是3根，可以无数根，只要一直保持这定义就可以。当然，简单的，也可以是1、2根，这只要不违反结合律和定义就可以。
00030| 
00031| 至于图8，就是线段的最基本形态，而图9，就是线段破坏，也就是两线段组合的其中一种形态。有人可能要说，这怎么有点像波浪理论，这有什么奇怪的，本ID的理论可以严格地推论出波浪理论的所有结论，而且还可以指出他理论的所有不足，波浪理论和本ID的理论一点可比性都没有。不仅是波浪理论，所有关于股市的理论，只要是关系到图形的，本ID的理论都可以严格推论，因为本ID的理论是关于走势图形最基础的理论，谁都逃不掉。
00032| 
00033| 不能再废话了，下面车来了，腐败开始，大家也腐败去吧。

(End of file - total 33 lines)
</file>
```
```

```
Tool: read

**Input:**
```json
{
  "filePath": "/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/063.md"
}
```
**Output:**
```
<file>
00001| ---
00002| id: '063'
00003| title: ''
00004| hide_table_of_contents: true
00005| ---
00006| 
00007| # 教你炒股票63：替各位理理基本概念
00008| 
00009| > 2007/7/2 0:07:39
00010| 
00011| 在外面时间有点长，再好的宾馆也没家里好，有点想北京。明天就可以回北京了，3号还要去听一场音乐会。不过在北京也待不了几天，下周又要去一次深圳，唯一希望就是能赶上最后的荔枝，糯米糍、桂味什么的，在北京吃不到好的，不知道是否过了季节。闲着没事，就随手写一课程，希望对各位有帮助。
00012| 
00013| 一个对象的确立，特别是一个数学和几何对象的确立，首先要证明其存在性，如果你说的那东西根本就不存在的，那还说什么？例如中枢或走势类型这对象，如果不能证明其一定存在，而且是按级别存在的，那谈论就没意义了。所以，前面关于中枢的递归定义，就是解决这个问题的，是解决存在性问题。也就是说，中枢是可以递归式地定义出来的，而该定义是可操作性的，该定义实际上是如何找出中枢的一种方法，按照这种方法，就肯定能找出定义中的中枢。
00014| 
00015| 但是，光是存在性定义或定理没什么意义，所谓的可操作性，有时候只是理想化或者数学化的，例如，可以证明自然数的质数分解是唯一的，而且可以很理想化地去设计这种寻找，但实际上用最大的计算机也往往不可能完成，因此就需要变通的方法来方便实际操作。同样道理，对于中枢和走势类型，也就有了关于不同级别的图形的研究。否则，都从最原始的分笔成交去逐步定义、寻找，那这可操作的操作也没什么操作性了。
00016| 
00017| 进而，就有了不同级别显微镜的比喻。而实际上，一般能得到的图，最多也就是1分钟级别的，因此，可以从这个图入手。当然，也可以从5分钟，甚至更高入手，但这就等于把显微镜倍数弄小了，看到的东西自然没有1分钟的多且清楚。再次强调，什么级别的图和什么级别的中枢没有任何必然关系，走势类型以及中枢就如同显微镜下的观察物，是客观存在的，其存在性由上面所说最原始的递归定义保证，而级别的图，就如同显微镜，不同倍数的看这客观的图就看到不同的精细程度，如此而已。所以，不能把显微镜和显微镜观察的东西混在一起了。
00018| 
00019| 如果我们首先确立了显微镜的倍数，也就是说，例如我们把1分钟图作为最基本的图，那么就可以开始定义上一课程说的分型、笔、线段等等。有了线段，就可以定义1分钟的中枢，然后就是1分钟的走势类型，然后按照递归的方法，可以逐步定义5分钟、30分钟、日、周、月、季度、年的中枢和走势类型。而有的人总是不明白，例如总是在问，5分钟图怎么看，30分钟怎么看，其实，如果你选择5分钟或30分钟为最基本的图，那么和1分钟的看法一样，只不过你的显微镜倍数比较小，看起来比较粗糙而已。而如果你已经选择1分钟作为最基本的图，也就是选定了1分钟这个倍数的显微镜，那么看1分钟图就可以，所以，本ID也就不断在1分钟图上进行线段的记号来示范。
00020| 
00021| 那么，有人可能要问，如果用1分钟图这显微镜，5、30分钟等图还有用吗？当然也是有用的，例如走出一个1分钟的走势类型，已经完成了，就可以在5分钟图上相应记号上，这样的一个好处就是帮助记忆，否则当1分钟图上的线段成千上万时，肯定要抓狂的。而有了5、30、日等图，就把相应已经完成的走势类型记号上，实际上，在1分钟图上需要记住的，只是最近一个未完成的1分钟走势类型。当然，由于分解的多样性，实际上需要知道的要多点，这里只是站在一种分解的角度说的。另外一个好处就是看MACD辅助判断时，不用对太多的柱子面积进行相加，可以看大级别的MACD图，这样一目了然。日线的背驰，其实在1分钟图上也可以看出来，只不过是需要把所有相应对比段的MACD都加起来进行处理，这样当然是不切实际的，因此就可以看日线图的MACD，在理论上没有任何特别之处，只是为了方便，如果用1分钟的MACD把参数调到足够大，效果其实是一样的，而实际上不可能，一般软件上，MACD的参数有上限限制，所以实际上也限制了日线的背驰不能用1分钟的图解决。
00022| 
00023| 有人可能又要问，为什么5分钟图上不记号5分钟的走势类型？因为，在大级别图上记号次级别的走势类型有一个好处，就是能让你清晰地看到该级别的中枢和走势类型是如何形成的，这样会更直观。当然，如果在5分钟图上，你愿意记号30分钟甚至年线的走势类型也没什么，这是个人爱好问题。如果你有超强的记忆和分析力，甚至就在1分钟上记号就可以，如果你更牛一点，对图形过目不忘，像计算机一样自动就可以分类合并，那你在1分钟图上连记号都不用了。
00024| 
00025| 说点更实际的问题，一般人面对一只股票，不可能就先看1分钟图，大概都是先从日线，甚至周、月、季、年入手，这样等于先用倍数小的显微镜，甚至是肉眼先看一下，然后在转用倍数大的，进行精细的观察。因此，对于大级别的图，上一课中的分型、笔、线段等同样有用，不过，一般这个观察都是快速不精细的，所以大概精确就可以，而且，一般看图看多了，根本就不需要一步步按定义来，例如，打开日线图，1秒钟如果还看不明白一只股票大的走势，那就是慢的了。基本上说，如果图看多了，成了机械反应了，一看到可搞的图，就如同看到可搞的面首一样。一见钟情，科学研究说大概不需要1秒，股票如同面首，如果不能1秒之内一见钟情，估计这股票也和你没什么缘分，最多就是有缘无分空折腾了。
00026| 
00027| 别觉得本ID整天把股票和面首联系在一起有点不太地道，但人这身体都是从性而来，股票的道理和性的道理没什么区别当然也没什么可奇怪的，这道理在前面的课程里已经说过。如果，你能把你的性能量转化到股票上，有了那种一见钟情的直觉，那么就算是有点入门了。而前面的理论分析，最终还是要归到这种直觉上去。说得更直接一点，例如在419这种事情上，无论男女，其实决定是否419，都是在1秒内决定的，股票同样，是否和股票419，也一样。当然，有些419让后悔终生，有些让你怀念终生，这和股票是一个道理。而真正的419高手，就是一眼就要把一个人给看透，而且知道自己需要什么，该要什么，什么不该要，要了的要甩得开，如雁过长空，否则就不是419了。股票也一样，股票的走势如同面首在搔首弄姿，一眼要看穿其把戏。当然，股票比面首可爱的地方在于，面首的搔首弄姿只有一个方向，而股票有三种可能的状态，这也决定了，面首面首是有厌倦的时候，而股票股票则不一定。
00028| 
00029| 但在没有这看破一切的一眼前，就别把自己当情圣了，老老实实在家里抱孩子吧，花心萝卜是需要功力的。股票也一样，没有这超越的直觉，还是老老实实去分析，在大级别图粗略选定攻击目标后，就要选好显微镜，进行精细的跟踪分析，然后定位好符合自己操作级别的买点建仓，按照相应的操作级别进行操作，直到把这股票玩烂、直到厌倦或者又发现新的更好的可玩弄对象为止。而站在纯理论的角度，没有任何股票是特别有操作价值的，中枢震荡的股票不一定比相应级别单边上涨的股票产生的利润少。
00030| 
00031| 只有坏的操作者，没有坏的股票。股票只是废纸，本质上都是垃圾，如果技术、心态不到位，任何股票都可以让你倾家荡产。当然，对于小资金来说，一定要选择股性好的股票；而对于大资金来说，股性是可以改造的，就如同没有面首是不可以面首的，只是代价不同而已，股票也一样，任何股票的股性都可以被改造，只不过需要的能量不同而已。
00032| 
00033| 不写了，已经又一天开始了，本ID也要洗洗睡了，先下，今天收盘后解盘见，然后本ID晚宴后赶最后的班机回北京，归心似箭，周二，盘就可以在北京看了，再见。
00034| 
00035| 
00036| 

(End of file - total 36 lines)
</file>
```
```

```
Tool: read

**Input:**
```json
{
  "filePath": "/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/072.md"
}
```
**Output:**
```
<file>
00001| ---
00002| id: '072'
00003| title: ''
00004| hide_table_of_contents: true
00005| ---
00006| 
00007| # 教你炒股票72：本ID已有课程的再梳理
00008| 
00009| > 2007/8/21 22:37:20
00010| 
00011| 任何事情，都有缘起。本ID是个大杂家，本ID现实中最终的落脚处，是文化的总构建，所谓三教九流，彻底穷源地玩弄一把。虽然，经济上，本ID早就可以天天腐败什么活都不干了，但现在又没老到要在书斋里天天写书的地步，本ID觉得，那至少是40岁以后才能干的事情。因此，本ID在网上写东西，纯粹是顺着形势来，并没有什么计划。
00012| 
00013| 写关于股票的事情，对于本ID来说，不过是把本ID这十几年天天干的事情复述一下。正如在课程开头，本ID说的““教你炒股票”这样的题目，全中国不会有第二人比本ID更适合写的。” 当然，这种话招人恨的，不过却是事实。
00014| 
00015| 和股票相关的事情千奇百怪，本ID是什么都经历过，所以，开始写的时候，并没什么主题，只是漫谈。但对一般散户来说，听些掌故没什么实质意义，说消息面，肯定也没什么意义。如果你消息灵通到公布什么利好利空前都是第一时间知道，那么就没什么可说的。而对于散户来说，那种靠拿着原始股就可以翻几十几百几千倍的时代早过去了。靠研究公司基本面买股票，那种积累速度太慢，只适合大资金。其实，一切关于基本面的研究，最终都归于行业或总体经济的发展。最简单、最不伤脑筋的方法，本ID也说过，就是买指数基金、或者具体行业、板块的基金。对于散户来说，你对基本面的研究能力要超过一个好的基金团队的可能性是微乎其微的。至于指数基金，那就更不用说了，至少你肯定不会跑输指数。
00016| 
00017| 对于散户来说，最终能战胜市场、获得超越市场的回报的，只有在本ID所说的乘法原则下的技术面操作。技术面是三个独立系统里的一个，而另外两个，例如比价关系与基本面，可以配合决定你的介入种类。但当介入到一个品种后，技术面在操作上就起着决定性的意义。为什么？因为其他的面，变化的频率都没有技术面高，像基本面，其变化大致是有一定的稳定性的，不可能天天都是奇点、断裂点。比价关系也一样，一种比价确立后，就基本保持稳定了，不可能天天都变化。所以这种变化少的系统，不需要花太多精力去研究，而技术面显然不同。
00018| 
00019| 所以，最终本课程开始说技术面是顺理成章的。而技术方面，本ID的理论，肯定是关于技术方面最好的理论了，本ID本来是想在40岁退休后才写出来的，但大概是缘分到了，本ID也没刻意一定不写出来，所以就慢慢地写出来，而且现在还在写着。
00020| 
00021| 开始时，本ID并没有认真想写整套理论，因为当时好在网上骂男人玩，所以开始写技术的，都是用些损男人开心的招数，当时说的只是均线系统，那东西和本ID的理论没什么关系，只是闹着玩的。当然，如果真掌握了均线系统，也可以应付一定的情况了，例如，在日线单边走势中，最偷懒的方法就是看着一5日线就可以，而5周线就更是中线的关键，5月线是长线的关系。例如，为什么现在牛市的第一轮肯定没走完？很简单，你什么时候见过牛市的第一轮调整不跌破5月线的？这两年多，这5月线被有效跌破过吗？显然没有。而第一次跌破5月线后，下面的10月、30月线上来，自然构成新的调整底部，后面自然还有一波大的。
00022| 
00023| 后来开始写于本ID理论有关的东西，开始，只是想把一些有用的结论告诉各位，因此课程都不是按正式的理论框架写的。本ID的理论，本质上分两部分，一是形态学，二是动力学，当然三就是两者的结合。如果按正式的课程，那肯定要先讲形态学。但如果不说动力学，那至少背驰是没法讲了，然后中枢震荡也不可能用类背驰的方法去判别，第一类买卖点也无法说了。而所有买卖点，归根结底都是第一类买卖点，那这样，要把形态学和动力学都说完，才说第一类买卖点，估计所有看的人都会晕倒。
00024| 
00025| 所以，当时把于初学者有用的一些简单结论先说了，就是让各位有点实践的乐趣，当时000999刚好在6元，还很明确地说了，买这股票，就当本ID把你要给市场交的学费都给各位准备好了，就是让各位耐心学下去，拿着一个长线股票，至少比你到处乱跑要强点。这样安心学习，也是不错的。当然，有能力的，也就可以边学边实践，这没有任何需要统一规划的地方。
00026| 
00027| 站在纯理论的角度，形态学是最根本的。形态学，从本质上就是几何，这部分内容，是无须任何前提的。以前说的本ID理论成立的前提，其实并不是针对这部分的，主要是针对动力学部分。因此，就算一个庄家自己全买了，一个人天天自我交易，也永远逃不出形态学画的圈圈。而动力学方面的东西就不同了，必须有本ID要求的那两个前提：价格充分有效市场里的非完全绝对趋同交易。
00028| 
00029| 动力学，是属于物理范畴的，但站在更高的层次上看物理，物理的本质就是几何，当然，这是所有物理学家都不可能认同的，但如果用一些几何结构就可以把所有物理的常量给搞掂，那物理学家不认同也是白搭。同样道理，本ID理论里的动力学部分，本质上也是几何，只是这种几何比较特别，需要把价格充分有效市场里的非完全绝对趋同交易作为前提转化为某些几何结构，然后构造出理论的证明来。
00030| 
00031| 所以，本ID理论在整体上依然只是几何，只是需要有价格充分有效市场里的非完全绝对趋同交易的前提。而且，最终的理论，当然不会涉及那些基本上谁看都会晕的几何结构，而是谁看都能看明白的当下的走势。理论和理论的证明那是两回事情。费马猜想谁都看得懂，费马猜想的证明，能全看懂的人不会超过1千万分之一。
00032| 
00033| 当然，本ID的课程，基本的逻辑顺序还是一直坚持的，不过，如果是最终的课程，那么最开始的一章，肯定是形态学，和这课程的顺序大为不同。但现在，由于已经写成这样一种形态学和动力学混着说的状态，当然只能一直混着下去。
00034| 
00035| 所谓形态学、动力学，其实很好分辨，任何涉及背驰的，都是动力学的范围，背驰是动力学的基本点之一。另外，中枢、走势的能量结构之类的东西，也属于动力学。而形态学，就是中枢、走势类型、笔、线段之类的东西。
00036| 
00037| 其实，光用形态学，就足以形成一套有效的操作体系。只是在形态学中，由于没有背驰的概念，所以第一买卖点是抓不住了，但第二买卖点是肯定没问题的。单纯用形态学去操作，就是任何对最后一个中枢的回拉后第一个与回拉反向的不创新高或新低的中枢同级别离开，就是买卖段。
00038| 
00039| 就算按照这么简单的方法，也可以很容易判断现在在日线上的操作思路，例如，去年5月和今年5月后的调整，算是同级别的，那么，其后的卖点就是，万一回拉4335点之下，任何第一次向4335点上的与回拉级别相同的不创新高的反抽都是卖点。如果一直没有回拉回到4335点，又在上面形成新的同级别中枢，那么操作的标杆就进一步提到那个中枢上，如此类推。按照这种方法，那么从2005年中到现在，你都应该持股不动，为什么？因为没有卖点。当然，实际操作，要针对具体个股，说指数只是举例子。个股上，看000777在日线，6月20前后的一段，就可以看出类似的效果；但如果你是看周线图的，那么现在的卖段还没有出现，而且可以明确地看出，其6-7月份的调整，不过是突破历史高位后的回抽过程，站在更大的视野上，看到更大的方向，如此而已。
00040| 
00041| 当然，上面只是说如果只用形态学，也可以进行操作，但实际上，当然是动力学、形态学一起用更有效。所以，千万别认为以后就只用形态学了。不过这里有一个用处，就是那些对背驰、区间套没什么信心的，可以先多从形态学着手。而且，形态分析不好，也动力不起来。
00042| 
00043| 站在实际应用的角度，关于中枢的递归定义以及与从分型、笔、线段开始的最小级别定义之间的区别之类的东西，也是可以不管的，但这样，逻辑上就容易乱，所以，搞清楚没坏处。如果你实在特懒，那就从分型学起，这也可以。
00044| 
00045| 下面，本ID给出一个懒人线路图：
00046| 
00047| 分型-笔-线段-最小级别中枢-各级别中枢、走势类型
00048| 
00049| 上面几个东西，是形态学中最基本的，完全没有办法再简略了，所以无论多懒，如果真想学本ID的理论，那请先把这几样东西搞清楚。
00050| 
00051| 关于形态学，后面还有很多内容，最主要是关于各种与结合律相关的问题。当然还包括世界上所有有关股票的理论中关于形态部分的理论，根据本ID的形态学，例如什么K线理论，波浪理论之类的玩意，都可以从本ID的形态学中严格推出，而且，本ID还可以指出他们的缺陷以及原因。这个工作是必须干的，彻底穷源的其中一个方面，就是要包罗万象。
00052| 
00053| 注意，有时候课程是由浅入深，前面不严格的，后面引进新概念后，就可以严格定义了。例如，最开始时，说上涨、盘整，都是用高、低点之类的东西，因为当时没说中枢，所以不可能严格定义，后来说了中枢，就可以给出严格定义。
00054| 
00055| 再例如，64课里，由于没说特征序列的元素之类的概念，所以里面关于线段一些论述都如同用高、低点定义上涨、盘整一样，不太严格，到67课说了特征序列之类的东西后，定义就是严格的，所以在67课里，本ID说“本课，就是把前面“线段破坏的充要条件就是被另一个线段破坏”精确化了。因此，以后关于线段的划分，都以此精确的定义为基础。”
00056| 
00057| 为什么说原来的不精确，因为按照原来没有特征序列的定义，那么线段里都要继续存在类似小级别转大级别的情况，而有了特征序列后，就不再需要这种情况了，这样才能把线段给精确划分。
00058| 
00059| 由于本ID目前的讲课，一开始就没有按正常课程应该的顺序，所以，这种开始不精确后来再精确的情况才会发生。本ID愿意先不引进复杂的概念，先把大方向给说了，然后再说复杂的概念。这样有一个好处就是，如果理解能力差的，可以接受简单，不太精确的方式，这样也没什么问题，也可以用。例如，像特征序列的分型这样的概念，本ID就严重怀疑孔男人能理解的机会能超过10%。所以，如果不能理解精确的，就用不精确的，等有理解力，对市场再了解深了，再学精确的也可以。
00060| 
00061| 例如，如果你现在只能理解男上位、女上位，吻之类的东西，那也很好。关键是精通一样东西，精通就好，就怕半通不通。所以，以后有问题，一定要问，把所有想解决的问题都解决才行。当然，本ID无法回答所有问题，但有代表性的，一定会安排回答的。

(End of file - total 61 lines)
</file>
```
```

---

## Assistant (Plan · minimax-m2.1-free · 6.3s)

_Thinking:_

现在我已经收集了足够多的缠论核心内容。让我继续搜索一些关键概念的文章，比如背驰、买卖点、中枢震荡等。

```
Tool: grep

**Input:**
```json
{
  "pattern": "背驰|买卖点|中枢震荡",
  "include": "docs/stocks/*.md"
}
```
**Output:**
```
Found 100 matches
/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/zazen02.md:
  Line 11: 人的行为，就如同股票的中枢移动与震荡，有其规范，又有其突破规范的地方，而所谓的乐趣，则在于对规范突破的放荡中，就如同利润之于中枢的震荡。而有一个中枢，只要是人，只要活着就受困其中，“你首先是一个活人”这样一个中枢，哪天不受困其中，就死人一个了。换言之，人之所以有死，就在于“你首先是一个活人”中枢的被破坏。那么，那些上帝、灵魂的玩意，不过是把“你首先是一个活人”这中枢出现第三类买卖点后扩张成“你首先具有不死的灵魂”这类的中枢玩意，把肉体的活扩张成灵魂的活，肉体永生这中枢震荡不住了，就企图在灵魂永生的中枢里永远震荡下去，这就是所有宗教徒的YY。
  Line 29: 今天的走势依然没什么可说的，把下面的缺口补了后，就继续中枢震荡，关键是都在等周末的消息面，其实，不管周末有什么消息，这两天都消化了。因此，尾盘重新冲上4144点，收在其下面不远的地方，也就是很正常的。目前，拨乱反正行情第三目标已经达到，后面将为第四目标的创新高而努力，当然，前提是先把4144点的1/2线给站稳了。
  Line 49: 今天的走势依然没什么可说的，把下面的缺口补了后，就继续中枢震荡，关键是都在等周末的消息面，其实，不管周末有什么消息，这两天都消化了。因此，尾盘重新冲上4144点，收在其下面不远的地方，也就是很正常的。目前，拨乱反正行情第三目标已经达到，后面将为第四目标的创新高而努力，当然，前提是先把4144点的1/2线给站稳了。

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/zazen03.md:
  Line 15: 1、目前日线的背驰段解除没有？

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/zazen01.md:
  Line 36: 关于4000上下的震荡形成的中枢，要突破，向上要有第三类买点，否则，依然存在向下变盘的机会。在第三类买点出现，中枢完结前，震荡继续。用分时中枢概念看，昨天是一平衡市，今天也是，但今天中枢的位置向上移了，明天就面临三种选择，强的继续上移，中的围绕今天中枢震荡，弱的回试昨天中枢，从而让一般概念意义上的中枢形成级别扩展。根据明天开盘的走势，这一点不难分辨。
  Line 58: 关于4000上下的震荡形成的中枢，要突破，向上要有第三类买点，否则，依然存在向下变盘的机会。在第三类买点出现，中枢完结前，震荡继续。用分时中枢概念看，昨天是一平衡市，今天也是，但今天中枢的位置向上移了，明天就面临三种选择，强的继续上移，中的围绕今天中枢震荡，弱的回试昨天中枢，从而让一般概念意义上的中枢形成级别扩展。根据明天开盘的走势，这一点不难分辨。

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/zhongguancun.md:
  Line 19: 市场继续在这里折腾，这个5分钟的中枢震荡，将继续向更大级别延伸，因此，最终的突破方向，其级别意义就更大了，暂时，估计还需要一定的时间。

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/whoami.md:
  Line 209: 把买点的情况反过来就可以了，两段相邻的同级别上涨趋势发生背驰。

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/winestockwarn.md:
  Line 169: 又彻底背缠妹搞晕：这个背驰是指的MACD的均线不再随股价新高或新低，还是看MACD的拄体不再随股价新高或新低？两者一致当然最好，如不一致时，参考哪个？ 

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/whipsawing.md:
  Line 112: 在5分钟线上应该是已经背驰了，而且和上一次5分钟的背驰几乎是一摸一样的。 
  Line 117: 刚从0轴上来，不存在的背驰的问题。目前不是考虑5分钟的问题，而是60分钟的问题，对大盘最大杀伤力的，是60分钟可能的背驰。这是必须密切关注的。目前60分钟要不出现背驰，就要迅速拉起来，否则在这里折腾几天，那就有问题了。注意，60分钟一天才4根，所以还有几天可以看的。
  Line 135: 好好看看5分钟图，怎么没背驰了？
  Line 198: 看日线没必要去找1分钟的，一般日线上很明显地看出三段，而且，每段中日K线有至少三根以上重合，那基本都是30分钟的走势了。当看次级别的背驰等，才需要去看次级别的图。
  Line 211: 不一定，在快速拉升的最后，一个1分钟的背驰足以引发暴跌。所以，在不同的时期，对待不同的走势，关注的背驰级别也有所不同。这以后会具体说到。
  Line 239: lz麻烦你看看600210.刚刚出现一个3类卖点,现在又好像五分钟备驰,我看很象背驰,请lz看看是不是?谢谢. 
  Line 243: 3类卖点？背驰如果用MACD辅助，首先要回拉0轴。
  Line 257: 趋势内部的背驰/
  Line 272: 用MACD判断背驰首先要有黄白线对0轴的回拉，这个都没有，在该级别就不存在什么背驰，其他级别要相应去看了。
  Line 308: 临走回答一下，请先搞清楚背驰的条件，还有级别，没有具体的级别，光说背驰是没意义的。

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/xianghuoju.md:
  Line 11: 今天的走势没什么可说的，连续在这里提醒了N天了，中枢震荡就是逢高出，等下来出现底背驰再买，按此操作的，今天应该很爽才是。就算你不会这些，昨天告诉你4040点，今天1046的最后反抽，然后跌破5日线，这都看不明白，那就一定要连夜补课了。

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/yearlybottom.md:
  Line 13: 首先还是说580989，你看那中枢的力量是多么巨大，早上的远离，后面的回拉，一切如教科书一般，围绕这个原来的中枢进行震荡，这在昨天已经说了，后面震荡逐步减少，由于该中枢大致在0.6一线，依次向下的震荡空间是存在的。想想一个中枢震荡可以从0.4到0.95，这就是震荡的力量。
  Line 29: 现在的走势很简单，只要不有效破年线，就继续是原来的中枢震荡。中枢震荡怎么样，看看今天的580989。这就是教科书，看明白了，有什么震荡处理不了？

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/windrising.md:
  Line 134: mm,学了线断后，我想用线段的类中枢对线段中的笔背驰进行操作，可是好像不是很灵光。
  Line 158: 老大.请问三买后的向上段和离开中枢的向上段比较盘整背驰,有时候回落形成中枢,有时候只是稍稍回落又继续涨不形成中枢,有办法预判吗?谢谢

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/weeklinegapfilled.md:
  Line 17: 由于这次下跌只是1分钟级别的，对于原来的30分钟震荡并不能制造真正的破坏，所以，站在6124点下来的30分钟下跌角度，真正的背驰并没有出现。当然，盘整背驰也可以制造底点，然后再第三类买点地直接上去，但这需要后面的确认，在确认之前，震荡的格局是不会变的，也就是说，一旦上冲无力，唯一正确的选择，就是把今天抄底进入的退出。
  Line 19: 后面，最坏的情况，当然就是反弹后形成5分钟下跌的第一个中枢，然后继续跌破前两个底点的连线，最后去形成真正的30分钟背驰（当然，如果美国1987年那种极端情况，背驰是不会有的。）

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/weekbottomfractal.md:
  Line 15: 前面已经明确说过了，现在是5010点扩展出来的5分钟震荡，今天早上，一个完美的5149点下来的下跌段的背驰，然后就开始对5010点在中枢的震荡回抽，这都十分技术化。当然，这些走势的操作，需要比较高的技术把握，如果没这技术的，就算了。
  Line 17: 注意，只要这震荡不出现第三类买卖点，那么震荡继续。有技术的按照震荡的程式进行就可以，那程式是什么？课程里反复说过了。

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/weekslump.md:
  Line 21: 现在的情况十分简单，对于短线来说，就是现在依然是原来76-85那个5分钟中枢的中枢震荡，现在的问题只不过是，该5分钟的中枢的第三类买点是否出现。如果不出现，那就继续中枢震荡，当然，那时候，这5分钟就扩展成30分钟的中枢震荡了，那就更好玩了。
  Line 23: 至于超短线来说，昨天问题的答案在图里就有了，分不清楚的，请好好研究一下。目前，就是102-105的一个中枢震荡。注意，目前这个离开原来5分钟中枢的走势并没有完成，所以还谈不上回抽，那今天震荡的低点，刚好在78之上，也就看出，这中枢震荡并不是瞎掰的，这么远的距离，依然起着作用。
  Line 25: 个股，没什么可说的，就算是假突破，只要这大的中枢震荡存在，那么个股机会依然汹涌，假期前，又有一个持股持币的无聊问题，关键还是你的操作级别和该级别中的表现。对于完全不了解本ID理论的，就看5日或5周线，特别是5周线，这是中短线的关键。

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/warning.md:
  Line 11: 上周突破孔男人1/3线后，本ID这里成交屡创天量，比平时6、7千的浏览翻了近6、7倍，这轮行情过后，本ID这里指数上台阶，但也有太多新人加入，人心难免中枢震荡，为此废话几句。
  Line 35: 今天大盘没什么可说的，就是在昨天那5分钟中枢上晃荡，周五，由于对周末消息面的犹疑，尾盘只能横着。下周依然只要看这中枢震荡直到第三类买卖点出现。大的方面，还是突破4129的1/2线后的反抽确认活动，没什么特别的。下周很关键，因为涉及月线收盘，月线如果留下长上影，那下月一个弱走势盘整走势就很难避免。如果收光头阳线，那么后面继续强势的可能就很大了。
  Line 55: 今天大盘没什么可说的，就是在昨天那5分钟中枢上晃荡，周五，由于对周末消息面的犹疑，尾盘只能横着。下周依然只要看这中枢震荡直到第三类买卖点出现。大的方面，还是突破4129的1/2线后的反抽确认活动，没什么特别的。下周很关键，因为涉及月线收盘，月线如果留下长上影，那下月一个弱走势盘整走势就很难避免。如果收光头阳线，那么后面继续强势的可能就很大了。

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/vcera.md:
  Line 50: 今天走势十分正常，一个正常的中枢震荡，下午13点半附近的背弛如果还不能当下看出，那么就要抓紧学习了。具体的分析，将在课程61里。如果当下没能分析出来的，请先自己分析一下，然后对照明早的课程，这样才能提高。
  Line 54: 由于周一那缺口还在那里，因此成为行情发展的一个隐患，前面已经说过，只要震荡触及4192点附近的46，那么中枢就将扩展。今天的走势已经触及该点，所以后面将是一个大的中枢震荡。短线还是看在4224点的61，如果一个1分钟走势不能重新触及该点，就会形成一个5分钟的第三类卖点，那么震荡的区间就要往下扩展。如果能重新站稳4224点，那震荡依然是强势的。中线看，4144点的1/2线十分关键，如果该线站不稳，那么大盘的调整级别就加大，否则就问题不大。不会看的，短线还是看5日线，中线看5周线，不破就问题不大。
  Line 58: 个股方面，那16只里继续有几只新高了，其他在震荡后也会跟上的。昨天说那四种技术形态的个股，必须按照技术图形分别对待。特别是创新高的股票，必须注意有没有大级别背驰，有的，一定要小心，小心中了多头陷阱。如果没有背驰，或者盘整背驰最终转化为第三类买点，才可以介入。至于，其他形态的，看好技术图形就行。
  Line 75: 今天走势十分正常，一个正常的中枢震荡，下午13点半附近的背弛如果还不能当下看出，那么就要抓紧学习了。具体的分析，将在课程61里。如果当下没能分析出来的，请先自己分析一下，然后对照明早的课程，这样才能提高。
  Line 77: 由于周一那缺口还在那里，因此成为行情发展的一个隐患，前面已经说过，只要震荡触及4192点附近的46，那么中枢就将扩展。今天的走势已经触及该点，所以后面将是一个大的中枢震荡。短线还是看在4224点的61，如果一个1分钟走势不能重新触及该点，就会形成一个5分钟的第三类卖点，那么震荡的区间就要往下扩展。如果能重新站稳4224点，那震荡依然是强势的。中线看，4144点的1/2线十分关键，如果该线站不稳，那么大盘的调整级别就加大，否则就问题不大。不会看的，短线还是看5日线，中线看5周线，不破就问题不大。
  Line 79: 个股方面，那16只里继续有几只新高了，其他在震荡后也会跟上的。昨天说那四种技术形态的个股，必须按照技术图形分别对待。特别是创新高的股票，必须注意有没有大级别背驰，有的，一定要小心，小心中了多头陷阱。如果没有背驰，或者盘整背驰最终转化为第三类买点，才可以介入。至于，其他形态的，看好技术图形就行。
  Line 93: 你看看569的60分钟图，请说说10.78那天是什么？一个这么大级别的背驰，怎么可能1、2天就调整过来？本ID当天已经说得很清楚，剧本改了，要买要等待买点出现。
  Line 95: 再说一次，就算本ID没有专门提醒剧本改了，也应该看图作业，如果不明白，看看像569这样的背驰，一般是怎么调整的。569是本ID的股票，难道000999、000777、600635、600777、000778、600432、000915等等就不是？本ID对任何股票都只是按图作业。

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/waitingbuypoint.md:
  Line 13: 2762点下的三角反弹构成2924点下来的第一个中枢，然后是新一段的下跌，那么，后面的演化无非两种：两段力度对比（30或60分钟），后一段强于前一段，则还需要一个中枢后的下跌背驰才有机会完成2924点开始的下跌；反之，则2924点下来只是盘整走势，只需要一个中枢，其后将快速回到2679点之上。
  Line 17: 大的角度，目前7月3日开始的中枢震荡暂时还没出现第三类卖点，依然可以看成是该中枢震荡的延续，除非2924点开始的向下次级别走势类型完成后，其后的次级别反弹不能重回该中枢，才能确认中枢的彻底破坏。

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/useyourbrain.md:
  Line 37: 还有一只是600569，也是5月21日说的，22日就停牌，本ID也都是21、22两天买的，不过这股票有点背，本来要大涨的结果停牌碰上530大跌，所以本ID在复牌6月13日那天明确说：“今天，那关住的钢铁出来，这股票，这里很多人是停牌前一天9元多点买的，至少让各位少了被震的痛苦，逃过一次大跌，如果今天早上反应快的，还能有10%以上的收益。本来，如果没这次大跌，这股票肯定是要连续涨停的，现在只能先清洗一下，让需要用钱的先出来，这也是市场操作中经常要面对的事情，剧本，偶尔也要修改一下的。至于后面的走势，看好技术图形就不难发现了。”<span style={{color: '#FF0000', fontWeight: '500'}}>如果你在6月13日后还追高买入而不是等待买点再说，那本ID严重怀疑你是孔男人的嫡传弟子。</span>至于本ID自己，去看看60分钟图，这么大一个顶背驰，本ID会麻木不仁吗？对于有大卖点的股票，最大的仁慈就是砸死他，先卖后买，注意节奏，这样成本才能降低，否则成本怎么去变成0？至于600636，本ID也正在慢慢建仓中。
  Line 58: <span style={{fontWeight: 'normal'}}>由于要出差，先把这线段图贴出来，否则回来就积累一大堆K线，要分很多张图了。昨天说的很清楚了：</span>“明天还是这个4244点，站稳就走强，否则继续5分钟的中枢震荡，并且要小心出现第三类卖点。”今天的走势在4244点上精确地被再次压制，然后出现大幅度跳水，这些在今天走势的当下都很容易分析。81-82的盘整背驰、84点的第二类卖点，后面走出一个线段的标准下跌，以红箭头所指微型中枢前后出现背驰，然后有87的转折，但这个转折，由于86-87没有背驰，所以，只能是线段下级别的，因此，并不能现在就确定该线段就走完了，除非重新突破85的4131一点。<br/><br/>
  Line 60: 站在中枢的角度，75-84这个5分钟中枢下边在4188点，如果后面的走势不能重新站上去，就要提防形成5分钟第三卖点。而前面已经说过，现在的情况46-87已经构成一个30分钟的中枢，短线的问题只是这中枢的第三段是否完成。其后就是该中枢的一个中枢震荡，该中枢区间在[4067，4192]，该中枢要管大盘一段时间直到出现30分钟的第三类买卖点。
  Line 84: 由于要出差，先把这线段图贴出来，否则回来就积累一大堆K线，要分很多张图了。昨天说的很清楚了：“明天还是这个4244点，站稳就走强，否则继续5分钟的中枢震荡，并且要小心出现第三类卖点。”今天的走势在4244点上精确地被再次压制，然后出现大幅度跳水，这些在今天走势的当下都很容易分析。81-82的盘整背驰、84点的第二类卖点，后面走出一个线段的标准下跌，以红箭头所指微型中枢前后出现背驰，然后有87的转折，但这个转折，由于86-87没有背驰，所以，只能是线段下级别的，因此，并不能现在就确定该线段就走完了，除非重新突破85的4131一点。
  Line 86: 站在中枢的角度，76-84这个5分钟中枢下边在4188点，如果后面的走势不能重新站上去，就要提防形成5分钟第三卖点。而前面已经说过，现在的情况46-87已经构成一个30分钟的中枢，短线的问题只是这中枢的第三段是否完成。其后就是该中枢的一个中枢震荡，该中枢区间在[4067，4192]，该中枢要管大盘一段时间直到出现30分钟的第三类买卖点。

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/topfractal.md:
  Line 15: 昨天早上反抽不上5日线，顶分型确立。当然，顶分型确立，并不一定要拉出长阴线，但更不一定不拉出长阴线，10条短阴线与一条长阴线，只要不出现底分型，最终都只是指向一个向下笔的过程。而站在本ID理论的角度，只关心买卖点的结果，并不关心过程。
  Line 17: 一个顶分型跌破5日线，就是未病-欲病-已病模式中的最后一个已病了，既然已病了，就只能等大盘病好，病好的日线标志就是底分型。站在中枢震荡的角度，昨天说了，5010点那次的中枢震荡扩展成一个大的5分钟中枢震荡，今天的下跌，暂时没有把这个中枢震荡的第三类卖点给震出来，所以，只要不出现这个卖点，那么一切依然保持在基本的中枢震荡中，当然，如果出现了，那么大盘跌破上次低点的几率就极大了。
  Line 19: 站在中枢震荡的角度，第三类卖点是典型的已病了。第一等的高手，是未病就下手了，第二等的高手是欲病就下手，等到已病，那确实有点不太高明了。

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/totraitors1.md:
  Line 29: 那些面首以及面首都不如的，就不说他们了。大盘震荡的反复是不可避免的，而且站在纯技术上，就算站稳3000点上攻，也有极大可能进入日线的背驰段。但个股，特别是有题材的二、三线股票，将越来越摆脱指数的影响。联通是让大家观摩的，散户真没必要买，原来说过的14只股票，究竟整体走得怎样，大家也有目共睹了。不妨再列一次出来：
  Line 98: 于是，根据000761本钢5分钟图，以为：02301030-02150935 A段，之前有个中枢；接下去至02161500B段，构成一个较大的盘整中枢，同时MACD回抽0轴，今天开盘起走C段，上午10:45股价创新高，C段红柱小于A段，想必背驰，想起妹妹说过的有卖点一定要卖的，于是卖了，可收盘咋还创新高了呢？妹妹给看看俺的问题出在哪儿啦，那地方不叫背驰啊？<br/>
  Line 104: 要搞清楚，背弛必要有调整，但不必然有大调整，如果是盘整背弛，那往往转化成第三类买点。对于小级别的背弛是否产生大调整，必须是从大级别看起，这也是区间套方法所说的。例如5分钟的背弛，你必须先要看30分钟是否进如背驰段的可能，好象这，30分钟在主升段的，那5分钟的背弛往往就是一个盘中的小调整就完成了，这种背驰就没多大操作的意义了。否则1分钟背驰都每个弄一下，又不知道如何回补，那是很累的。一般这种背弛，盘中对冲一下就可以了。但那些符合区间套的背驰，就要充分注意了。
  Line 188: 缠师，盘整背驰中没看明白：其中提到的ABC三段，是指组成这段盘整走势中枢的三段重叠走势吗？ 
  Line 202: 请问000962五分钟好像要背驰，应该如何操作更好点。
  Line 209: 进入背弛段，要找精确的卖点的，就看1分钟以及以下的，这叫区间套方法，前面有一个课是专门说这个的。但对小级别的背驰，是否能引发大的调整，必须要看大级别是否进如背驰段。上面有关这个问题，刚回答了，请参考。
  Line 354: 或者，难道整个盘整走势本身就是个中枢，而不像趋势那样，有前面的连接段和后面的背驰段？ 
  Line 378: 老师的课程里很多地方说操作的级别要看资金量决定 但是我们对资金量的具体定义真是不明确 老师眼里的钱已经只是数字了 我们就不同 比如300万应该从哪个级别看起呢 另： 按您上面说的方法 600028从30分钟看已经进入背驰 但60分钟和日线看 还可以 就没有必要现在在卖点出来了 不只理解对吗 只到日线短了 再找卖点 对吗 
  Line 490: 盘整走势结束后如果接下来是上涨走势，一定有某级别离开盘整中枢低点的下跌背驰段吗？如果是盘整+下跌，又一定有离开盘整中枢高点的上升背驰段吗？<br/>
  Line 545: 1、北辰实业30分钟图06-12-07 10:00产生背驰，按楼主的理论，此次背驰所产生的走势至少应触及上一个中枢的最高点即6.15，为什么以后的走势至今还没有触及这一点？？？<br/>
  Line 552: 2、如何判断一个盘整的开始与结束？比如说一个上涨趋势完成后，对应的走势必然是盘整或下跌，那么当形成一个中枢的时候，我如何判断他是一个盘整还是一个下跌趋势的第一个中枢，是不是应该等等看？还有，趋势可以根据背驰来判断其结束，那么盘整用什么来判断其结束？<br/>

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/trustinthemoon.md:
  Line 25: 再次提醒，昨天说那两只股票，如果大盘有大问题，也会跟着调整的，但由于基本面上潜在大变化，所以市场如果大波动，将提供一个好的介入时机。本ID说的股票，从来都是中长线角度的，有足够的时间让你介入，关键是看好买卖点。
  Line 72: 还有一个,明明看起来是背驰了,买进却又再跌,为啥呢?<br/>
  Line 74: 请首先要确定你的明明是正确的，事实上，很多所谓明明的背驰，根本就不是。很多人，连中枢、走势类型、级别都没搞清楚，就分析背驰，这有可能准确吗？
  Line 108: 哪里有这么机械的，但如果月亮还带上一个背驰、分型之类的东西，那当然就有效了。

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/totraitors2.md:
  Line 67: 下跌时a+A+b+B+c因为b背驰了所以转化为a~+B。<br/>
  Line 71: 昨天下午的是1分钟级别的上涨，昨天收盘前是一个1分钟以下级别的顶背驰，今天早上1006附近是一个1分钟以下级别的底背驰，然后出现一个大的中枢，上下震荡，收盘勉强拉回这个中枢。明天，如果大盘在这中枢下出现第三类卖点，那大盘就会继续探下去。否则依然围绕这中枢震荡。
  Line 140: 第三类买点是在中枢上面出现的。震荡的处理很简单，就是看次级别的背驰弄对冲。当然，最好就是找有大级别第三类买点的强势股票，这样，大盘只要不一天内大幅下跌，一般都很安全。
  Line 152: 其实明白了本ID前面的课程，这都很简单。现在48附近有一个小中枢，能否上去形成一个大中枢就是能否短线走强的关键。没出现这个之前，基本不用关注。等在下面形成中枢后，如果是短线的，就找一个短线底背驰介入。从中线看，这个位置套不住人。
  Line 164: 昨天下午的是1分钟级别的上涨，昨天收盘前是一个1分钟以下级别的顶背驰，今天早上1006附近是一个1分钟以下级别的底背驰，然后出现一个大的中枢，上下震荡，收盘勉强拉回这个中枢。明天，如果大盘在这中枢下出现第三类卖点，那大盘就会继续探下去。否则依然围绕这中枢震荡。
  Line 167: “昨天下午的是1分钟级别的上涨，昨天收盘前是一个1分钟以下级别的顶背驰”
  Line 169: 老大这段为什么一分中上涨，会是1分以下级别的顶背驰呢？是不是说一分也盘整背驰了，一分以下也背驰了，这个级别同步背驰？<br/>
  Line 179: 背驰的级别和上涨的级别没有什么必然的对应关系，要有对应关系，就必须满足区间套关系。这个问题比较复杂，下面的课程会说到的。
  Line 239: 前一两天大盘走势看,分时图和1分钟图差不多,下跌第一个1分钟中枢可以认为是5分钟中枢吗?第2个是5分钟中枢也是1分钟中枢吗?分时图没有MACD看背驰,是看成交量吗?<br/>
  Line 315: 600550是否进入5分钟背驰段？ 
  Line 319: 你首先要搞清楚如何去判别，课程里都有具体的方法的。例如MACD的黄白线都没回拉0轴，就不存在该级别背驰的可能。该股票今天味盘低点是一个1分钟以下级别的背驰，但不是5分钟的。

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/toughyear.md:
  Line 23: 那么，现在的操作就极端简单了，一个短线的机会在这轮下跌的背弛点上，然后必须看反弹是否能回补今天缺口，只要不能，一定要走掉，因为必然会有再次的下探去构成更好的机会；反之，如果能回补，就看回补后构成的中枢的第三类买卖点情况。这样的操作安排，完全是绝对性的，没有任何含糊的地方，如果你看不懂，觉得很迷糊，就请虚心把课程好好学，里面都有最数学化的精确定义。

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/towarding4695.md:
  Line 15: 技术上，早上的回跌刚好形成5分钟中枢最后一次的一线段，这样，a+A的走势的a可以完美地进行线段盘整的分解，而A刚好是9个线段的最基本形式。当然，由于真正的第三类买点并没有出现，所以，大盘依然有重新回到该中枢震荡的可能。

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/strangecircle.md:
  Line 27: 二、水平还可以但看不懂中枢震荡的，就看5日线或5周线，一般来说，只要5周线不破，调整的级别就是有限的。
  Line 29: 三、懂得中枢震荡操作节奏的，就按中枢震荡的要求去操作，一般来说，原则是先卖后买，在这些位置，如果你的水平有点问题，卖错了就卖错了，权当把仓位减低。
  Line 33: 图形上，76开始的5分钟中枢异常明确了，在该中枢的第三买卖点出现前，中枢震荡将一直延续。
  Line 223: 那你就要看懂本ID的课程，说那么多，不就是告诉如何去找各种级别的买卖点？
  Line 235: 那你就要看懂本ID的课程，说那么多，不就是告诉如何去找各种级别的买卖点？
  Line 248: 所以买股票一定要分清楚买卖点，在长线买点介入，然后根据中线震荡把成本降低为0然后继续增加筹码，这样就不会有这种烦恼。
  Line 307: 1。是不是所有的买卖点的发现都有滞后性？而不是当时（当下）能确定的？---我的理解：买卖点出现在线段的端点，而线段端点的确定需要下一个线段的破坏，那么一旦确认破坏，买卖点肯定已经过去一段时间了。（不知这样理解对吗？）<br/>
  Line 308: 2.你一直讲你的理论不涉及预测，只关注当下。如果不涉及预测怎么能指导操作呢？比如，买点后必然上涨，卖点后必然下跌，不是预测吗？或者如第一个问题，买卖点只是事后的发现，才说得通呀。
  Line 327: 短线在中枢震荡中，当然就是先卖后买，这有什么问题？
  Line 350: 本ID多次说过了，想快，就学好第三类买点，那是最快的，操作上只要把握好两点：一、级别不能太小。二、一旦出现向上的盘整背驰一定要出来，不介入那些演化成大级别震荡的情况，只持有中枢上移的情况，一旦新中枢成立，马上走人。
  Line 352: 走人，第一卖点看背驰、错过了，第二卖点必须走。
  Line 369: 所以，对于散户，如果通道畅通的，最快的方法就是用第三类买点去操作，杀完一只继续一只，不断干下去，不参与任何的中枢震荡，只搞最强势的。
  Line 373: 当然，如果你没这技术，那就别玩高难度的，就玩简单的，把操作级别弄大点。中枢震荡玩不了，就看5日、5周线，持有到背驰卖点，然后坚决走人，等待新的买点。

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/stockshigh.md:
  Line 17: 技术上，指数就是继续去年末那5分钟中枢的震荡，在第三类买卖点出现之前，继续抖个不停。

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/stocksandmantra.md:
  Line 36: 例如在昨天下午，一个品种出现短线顶背驰又接近压力线，应该干什么？如果这品种恰好是大盘指数，应该干什么？注意，帖子可是中午就给出了，这是一个很好的现场例子，不管你如何了，但一定要记住这个例子。
  Line 40: 今天，除非下午大幅度起来形成包含关系，否则这顶分型就构成了，因此最关键就是5日线，不有效破就不形成笔，就会再冲一次34天线，否则将形成笔的调整，那就等笔对应的短线出现底背驰再说了。
  Line 44: 昨天下午正确操作，现在就不用左右为难，左右为难的操作都是因为节奏不对，因此，节奏是一个永远的主题，高手还是低手，最终考验的就是节奏，轮动只是节奏的一种方式，而最重要的节奏，还是买卖点，一切的节奏都必须以此为基础，当然轮动也不例外。

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/strikeback.md:
  Line 13: 具体的盘中事情，各位就没必要知道了，各位只需要知道结果，而结果是什么，已经永远刻在中国证券历史的K线图上。当然，如果要学技术，要当猎鲸者的，请好好去研究一下，从昨天凭空接坠石的两波反抽，到今天早上一开始的急拉，到后面的下跌，是如何构筑一个良好的技术反攻图形的，例如可以看看5分钟图，是如何用钱把这个底背驰给构造出来的。本ID也不能违反本ID的理论，就像牛顿也不能让苹果尽往天上飞。

/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/statement.md:
  Line 48: 好妹妹，快说说背驰吧，这个不同清楚，买卖点怎么也不明白 
  Line 57: 本ID要去弄弄头发，晚上要去腐败一下。明天继续说背驰。

(Results are truncated. Consider using a more specific path or pattern.)
```
```

```
Tool: read

**Input:**
```json
{
  "filePath": "/Users/jiangtao/workspace/study/chzhshch-blog/docs/stocks/043.md"
}
```
**Output:**
```
<file>
00001| ---
00002| id: '043'
00003| title: ''
00004| hide_table_of_contents: true
00005| ---
00006| 
00007| import useBaseUrl from '@docusaurus/useBaseUrl';
00008| 
00009| # 教你炒股票43：有关背驰的补习课
00010| 
00011| > 2007/4/6 15:31:28
00012| 
00013| 发现很多人对最基础的背驰问题还是不大清楚，周末，来一补习。关于如何判断背驰，背驰与盘整背驰的区别之类问题就不说了，这个太基础，连这都没搞清楚，那最好的办法就是重修，而不是补习。
00014| 
00015| 转折必然由背驰导致，但背驰导致的转折并不一定是同一级别的。在“教你炒股票29：转折的力度与级别”中有“缠中说禅背驰-转折定理：某级别趋势的背驰将导致该趋势最后一个中枢的级别扩展、该级别更大级别的盘整或该级别以上级别的反趋势。”这是一个十分重要的定理，这定理说明了什么？就是某级别的背驰必然导致该级别原走势类型的终止，进而开始该级别或以上级别的另外一个走势类型。
00016| 
00017| 由于不允许“上涨+上涨”、“下跌+下跌”的情况，所以，这定理对实际操作就很有意义了。例如，一个1分钟级别的顶背驰，就意味着必然导致一个至少1分钟级别的盘整或下跌走势类型，这就为背驰以后可能的走势以及级别给出了很明确的划定。有人经常问，为什么1分钟顶背驰后还涨，那有什么奇怪的，只要有一个1分钟的盘整，那就可以继续涨，这是1分钟顶背驰后可能的情况之一，当然，还有其他可能的情况，例如，最极端的，制造出一个年线级别的下跌，但不能说这个制造是由于1分钟顶背驰造成的，因为这是1分钟顶背驰后，形成的盘整或下跌逐步级别扩张，最后才慢慢形成的，如果随便看到一个1分钟顶背驰就说要形成年线级别大调整，那就是脑子水太多了。如果市场的转折与背驰都有这在级别上一一对应关系，那这市场也太没意思、太刻板了，而由于这种小级别背驰逐步积累后导致大级别转折的可能，才使得市场充满当下的生机。
00018| 
00019| 注意，这两种不同的转折方式的区分是十分关键的。所有的转折都与背驰相关，但加上背驰的级别与当下走势级别的关系，就有了这两种不同的转折方式。由于背驰的级别不可能大于当下走势的级别，例如一个30分钟级别的背驰，只可能存在于一个至少是30分钟级别的走势类型中，所以就有这两种不同转折方式的明确分类。
00020| 
00021| 一、背驰级别等于当下的走势级别
00022| 
00023| 例如，一个30分钟的走势类型，出现一个30分钟级别的背驰，那么这个背驰至少把走势拉向该30分钟走势最后一个中枢，当然就会跌破或升破相应的高点或低点。注意，这种情况包括进入背驰段的情况，例如，一个30分钟的走势类型，在30分钟级别进入背驰段，当然，这个背驰段并不一定就演化成背驰，因为，小级别的延伸足以使得大级别最终摆脱背驰，这与当下的走势判断相关。
00024| 
00025| 二、背驰级别小于于当下的走势级别
00026| 
00027| 这种情况下，是走势已经明显没有相应级别的背驰，例如，一个30分钟的走势类型，明确显示没有出现30分钟的背驰，也就是背驰段最终不成立，但却出现一个1分钟级别的背驰，用一个最简单的形式向上的a+A+b+B+c，A、B是30分钟中枢，在c中出现1分钟背驰，而c对b在30分钟级别并没有出现背驰，这时候并不必然保证c的1分钟转折的最终走势就一定不跌回B里，但即使这个回跌出现，其形式也和第一种情况不同。这第二种情况，必然要先形成一个比1分钟级别要大的中枢，然后向下突破，最终形成回跌到B中的走势。
00028| 
00029| 有人可能要问，第一种情况中如果是5分钟级别的回跌，也会形成一个比1分钟级别大的中枢，那和第二种情况有什么区别？这区别太大了，在第一种情况中，其回跌是必然的，而第二种情况，在形成一个比1分钟大的中枢后，并不必然回跌，可以往上突破，使得a+A+b+B+c继续延伸。这种小级别背驰最终转化成大级别转折的情况，最值得注意的，是出现在趋势走势的冲顶或赶底之中，这种情况一般都会引发大级别的转折，这种例子前面都说过，例如20070104的工行，20061207的北辰实业、20070122的水井坊等。
00030| 
00031| <img src={useBaseUrl('/img/stocks/043/601398_d.png')} /><br/><br/>
00032| <img src={useBaseUrl('/img/stocks/043/601588_d.png')} /><br/><br/>
00033| <img src={useBaseUrl('/img/stocks/043/600779_d.png')} /><br/><br/>
00034| 
00035| 以上两种情况，对走势的分解也是很有意义的，例如对一个30分钟的走势类型，其完结也同样有相应的两种情况，最普通的一种，例如出现一个30分钟的背驰，从而完成一个30分钟级别走势类型，在这种情况下，对该走势类型的分解就不存在任何含糊的地方，前后两个走势类型，就以该背驰点为分界；至于小级别背驰引发大级别转折的情况，这种情况比较复杂，但分解的原则是一致的，就是：
00036| 
00037| 缠中说禅走势类型分解原则：一个某级别的走势类型中，不可能出现比该级别更大的中枢，一旦出现，就证明这不是一个某级别的走势类型，而是更大级别走势类型的一部分或几个该级别走势类型的连接。
00038| 
00039| 这里，把上面第二种情况下的分解可能分析如下：
00040| 
00041| 不妨还是以上面向上30分钟级别的a+A+b+B+c为例子，在c中出现一个1分钟级别背驰，不妨假设后面演化出一个30分钟中枢C，如果C和B没有任何重叠，那就意味着原来的a+A+b+B+c并不是一个完成了的30分钟走势类型，该走势类型将延伸为a+A+b+B+c+C，相应的分解要等到该走势类型完成了才可以进行；如果C和B有重合，那么a+A+b+B+c+C=a+A+b+（B+c+C），其中（B+c+C）必然演化成一个日线中枢，那么a+A+b+B+c只是一个日线级别走势类型的一部分，如果一定要按30分钟级别来进行同级别分解，那么该分解点就是那1分钟的背驰点，a+A+b+B+c+C=（a+A+b+B+c）+C。
00042| 
00043| 有了以上的例子，就对如何用背驰对走势分解的基本原则有一个大概的了解了，熟悉了这些分解方法，市场的走势图就不会是天书了，而是如自己的掌纹一样清晰可辩。
00044| 
00045| ### 回复
00046| 
00047| <div class='blog-comment'>
00048| <span class='blog-comment-chan'>缠中说禅</span> 2007/4/6 15:32:12<br/>
00049| 
00050| 今天深圳已经实现对那条压力线的冲击，不过还没有突破站上去，某种程度上，这是汉奸最后的防线了，一旦突破站稳，那深圳的1万点就在本ID的强大炮火下了。
00051| 
00052| 昨天说了，汉奸现在也到处哭诉，在市场上没法成功，就在市场下努力，也亏汉奸干得出。希望下周汉奸能倾其所有，在这里大打一战，别搞到本ID都没兴趣搭理你们就没意思了。
00053| 
00054| 目前，二线股的行情已经有点不可阻挡了，由于10元上下的股票不断往上顶，就促使整个股价结构发生松动，15、20、30、甚至更高的二线股都被带动起来，由此也就知道本ID当时特别从10元上下二线股下手的深意。
00055| 
00056| 现在，本ID的星火已经有点燎原，也就不必要一定是什么10元上下的，只要盘整到位，业绩支持的二线股，都要启动，从而整个股价结构上一台阶，为下一轮三线股的再启动腾出空间。
00057| 
00058| 不过，任何时候都不应该追高，应该选择好买卖点，特别对于散户来说，否则，一个小的震荡就足以出问题。目前，在政策上存在微妙的地方，汉奸的哭诉能起多大作用，谁都说不准，那是另外一个战场的战争，这里就不方便说了。
00059| </div>
00060| 
00061| <div class='blog-comment'>
00062| <span class='blog-comment-chan'>缠中说禅</span> 2007/4/6 15:42:17<br/>
00063| [匿名] YY <br/><br/>
00064| 
00065|  
00066| 2007-04-06 15:40:08 <br/>
00067| 老大，能不能说点新鲜的东西啊 
00068| 
00069| 课程好久没更新了 
00070|  
00071| 
00072| --<br/>
00073| 
00074| 当然，但现在很多人跟不上，用一两节时间来补习一下，也是必要的。
00075| </div>
00076| 
00077| <div class='blog-comment'>
00078| <span class='blog-comment-chan'>缠中说禅</span> 2007/4/6 15:43:18<br/>
00079| [匿名] 平安保险 <br/><br/>
00080| 
00081|  
00082| 2007-04-06 15:40:40 <br/>
00083| 老师 是不是新股的周线还没有走出来 就不会那么快启动啊 这时候 看什么级别的 601318 这样的股票 短期是不是不值得参与 什么线都走不出来 要象大唐发电 四个月了 才会发作 盼复 
00084|  
00085| ==<br/>
00086| 
00087| 新股就看短线的图形。
00088| </div>
00089| 
00090| <div class='blog-comment'>
00091| <span class='blog-comment-chan'>缠中说禅</span> 2007/4/6 15:45:18<br/>
00092| [匿名] 缠心雕龙 <br/><br/>
00093| 
00094|  
00095| 2007-04-06 15:42:05 <br/>
00096| 博主好，39课中讲到的同级分解流程有点疑问：
00097| 
00098| 这种操作不管这么多，只理会一点，就是Ai与Ai+2之间是否盘整背驰，只要盘整背驰，就在i+2为偶数时卖出，为奇数时买入。如果没有，当i为偶，若Ai+3不跌破Ai高点，则继续持有到Ai+k+3跌破Ai+k高点后在不创新高或盘整顶背驰的Ai+k+4卖出，其中k为偶数。
00099| 
00100| --<br/>
00101| 请问，当Ai与Ai+2之间未盘背，若Ai+3不跌破Ai高点，而Ai+4对Ai+2盘背，Ai+4卖不卖？
00102| 
00103| 看原文应该是说不卖，则不卖的话，意味着即使发生Ai+4对Ai+2盘背，也不一定就卖出，还要看Ai+3是否跌破Ai高点。为何不在Ai+4先出来呢（可以避免Ai+5出现大跌）？
00104|  
00105| ==<br/>
00106| 为什么不卖？不是有这一句-或盘整顶背驰的Ai+k+4卖出
00107| </div>
00108| 
00109| <div class='blog-comment'>
00110| <span class='blog-comment-chan'>缠中说禅</span> 2007/4/6 15:49:55<br/>
00111| [匿名] 后知后觉 <br/><br/>
00112| 
00113|  
00114| 2007-04-06 15:44:23 <br/>
00115| 感谢禅主的教诲，赐我打开愚钝的钥匙！<br/>
00116| 如你所分析，的确现在都很谨慎。不过，低开后瞬间拉起，还是换了思路了。只是不知道是盘中主力拉起，还是场外进来的饿狼？<br/>
00117| 按照质地，分析价值，都感觉601318值得搞，只是没有老大这样的人去挑逗，它股性不是很活。下周平安出年报了，申银的分析报告我看了，挺细的，业绩应该在0。7～1。5，就看一些东西怎么计提估值了。<br/>
00118| 今日平安表现相对有些亢奋，好像有些“驿动”的渴望。按成本分析，现在就是第一天尾盘的价位。不知道老大是否有兴趣去在年报前后去干一票？<br/>
00119| 期待你的回答和分析！<br/>
00120| 谢了！ 
00121|  
00122| ==<br/>
00123| 平安没什么问题，现在最大的压力是有限售部分，但不构成实质影响。后面几个大家伙的业绩都很好，汉奸也少了一个借口
00124| </div>
00125| 
00126| <div class='blog-comment'>
00127| <span class='blog-comment-chan'>缠中说禅</span> 2007/4/6 15:53:58<br/>
00128| [匿名] 新浪网友 <br/><br/>
00129| 
00130|  
00131| 2007-04-06 15:45:33 <br/>
00132| 老师好. 大唐电信昨日发布业绩预告，早前预计扭亏为盈在昨日的预告中变成了预亏，令市场哗然，股价也因此跌停。传闻沸沸扬扬.<br/>
00133| 我是新股民 我现有（600198）15000股19.65买进 从来没有见过这样的 架势！现在不知道是去是留 请教该如何是好？ 谢谢 . 
00134|  
00135| =<br/>
00136| 
00137| 这没什么，如果有经验，今天可以补仓，弄两次短差成本就下来，这股票经过洗盘，还会上去的，不过需要点时间。
00138| </div>
00139| 
00140| <div class='blog-comment'>
00141| <span class='blog-comment-chan'>缠中说禅</span> 2007/4/6 15:57:04<br/>
00142| [匿名] 那一天 <br/><br/>
00143| 
00144|  
00145| 2007-04-06 15:45:37
00146| 
00147| 缠姐我是同学介绍来的,刚学到十八课
00148| 
00149| 您在十七课反复用到级别这两字, 能否给个对'级别'的准确解释!
00150| 
00151| 我对级别的理解有两种: <br/>
00152| 1) 周K线,次级日K线, 再次级60分K线, 等等. <br/>
00153| 2) 走势上,(举例) 周K线总体为向上,但里包含向下,整理, 向上<br/>
00154| 这包含在其中的就是次级别. 
00155| 
00156| 是否两种理解都对?? 
00157| 
00158| 我先谢您了!
00159| 
00160|  
00161| ==<br/>
00162| 课程里都有，请先把所有课程都看一遍。
00163| </div>
00164| 
00165| <div class='blog-comment'>
00166| <span class='blog-comment-chan'>缠中说禅</span> 2007/4/6 16:00:06<br/>
00167| [匿名] 兰兰 <br/><br/>
00168| 
00169|  
00170| 2007-04-06 15:56:08 <br/>
00171| 姐姐好!同学们好!好久没有和姐姐聊了!<br/>
00172| 向姐姐请教细节:<br/>
00173| 本为0后,挣股票做短差每次卖出时,只收回本金,对吗?如3000元本金,每次短差都是拿回3000元,股价涨到30元短差买点时只能买100股对吗? 
00174|  
00175| ==<br/>
00176| 一般，成本为0后，可以用先卖后买的方法，例如20卖1万，19就可以回补1万多股了，这样股数越来越多，前提是这股票还有中长线潜力。
00177| </div>
00178| 
00179| <div class='blog-comment'>
00180| <span class='blog-comment-chan'>缠中说禅</span> 2007/4/6 16:04:23<br/>
00181| [匿名] 瞎鼓捣 <br/><br/>
00182| 
00183|  
00184| 2007-04-06 15:58:50 <br/>
00185| 老大好
00186| 
00187| 原来备驰段也不一定发生备驰啊，这种情况多不多？具体怎么分辨？ 
00188|  
00189| ==<br/>
00190| 这很正常，如果用MACD来辅助看，拉回0轴后再上去，都可以先看成是进入背驰段，例如现在大盘的日线上，但最后是否黄白线创新高，在刚走的时候是不可能知道的，然后就要看小级别的结构，如果小级别的走势特别强，使得黄白线创出新高，那就不存在背驰的问题了。
00191| </div>
00192| 
00193| <div class='blog-comment'>
00194| <span class='blog-comment-chan'>缠中说禅</span> 2007/4/6 16:05:22<br/>
00195| [匿名] 中信海直 <br/><br/>
00196| 
00197|  
00198| 2007-04-06 16:00:50 <br/>
00199| 请问mm，为什么有的三段重叠算中枢，有的就不算，是不是只有均线交叉的情况下才算作中枢 
00200|  
00201| ==<br/>
00202| 和均线没关系，关键是要都是次级别的
00203| </div>
00204| 
00205| <div class='blog-comment'>
00206| <span class='blog-comment-chan'>缠中说禅</span> 2007/4/6 16:06:47<br/>
00207| [匿名] 新年好 <br/><br/>
00208| 
00209|  
00210| 2007-04-06 15:48:31 <br/>
00211| 请问缠姐，今天课中的两种情况，如果是第二种30分钟向上情况，如果是C和B没重合，是不是就不用参与，如果是C和B重合，是不是在那个1分钟的背驰点先出来？但是如果预先判断会不会重合呢？ 
00212|  
00213| ==<br/>
00214| 这负责，以后会说到，
00215| </div>
00216| 
00217| <div class='blog-comment'>
00218| <span class='blog-comment-chan'>缠中说禅</span> 2007/4/6 16:10:51<br/>
00219| 
00220| 对不起，周末要出去腐败，周五北京的交通很麻烦，本ID虽然不用自己开车，但走得晚，塞车也很难受，先下了。
00221| 
00222| 各位周末腐败快乐。
00223| 
00224| 再见。
00225| </div>

(End of file - total 225 lines)
</file>
```
```

---

## Assistant (Plan · minimax-m2.1-free · 6.2s)

_Thinking:_

现在我已经收集了足够的信息来梳理缠论的知识要点和学习路径。让我查看sidebars.js来了解网站的结构安排，然后整理出一个完整的梳理。

```
Tool: read

**Input:**
```json
{
  "filePath": "/Users/jiangtao/workspace/study/chzhshch-blog/sidebars.js"
}
```
**Output:**
```
<file>
00001| /**
00002|  * Creating a sidebar enables you to:
00003|  - create an ordered group of docs
00004|  - render a sidebar for each doc of that group
00005|  - provide next/previous navigation
00006| 
00007|  The sidebars can be generated from the filesystem, or explicitly defined here.
00008| 
00009|  Create as many sidebars as you want.
00010|  */
00011| 
00012| // @ts-check
00013| 
00014| const { sidebar: timelineSidebar } = require('./sidebars/timeline');
00015| // const { sidebar: byCategorySidebar } = require('./sidebars/byCategory');
00016| 
00017| const { sidebar: stocksExtendedSidebar } = require('./sidebars/stocksextended');
00018| const { sidebar: economicsSidebar } = require('./sidebars/economics');
00019| const { sidebar: essaysSidebar } = require('./sidebars/essays');
00020| const { sidebar: mathSidebar } = require('./sidebars/math');
00021| const { sidebar: musicSidebar } = require('./sidebars/music');
00022| const { sidebar: entertainmentSidebar } = require('./sidebars/entertainment');
00023| const { sidebar: confuciusSidebar } = require('./sidebars/confucius');
00024| const { sidebar: zenSidebar } = require('./sidebars/zen');
00025| const { sidebar: poemsSidebar } = require('./sidebars/poems');
00026| const { sidebar: fluidSidebar } = require('./sidebars/fluid');
00027| 
00028| const { sidebar: qiangguoSidebar } = require('./sidebars/qiangguo');
00029| const { sidebar: tangfenSidebar } = require('./sidebars/tangfen');
00030| const { sidebar: tianyaSidebar } = require('./sidebars/tianya');
00031| const { sidebar: y2002postsSidebar } = require('./sidebars/2002posts');
00032| const { sidebar: fundAnalysisSidebar } = require('./sidebars/fundanalysis');
00033| 
00034| const { sidebar: othersSidebar } = require('./sidebars/others');
00035| const { sidebar: identitySidebar } = require('./sidebars/identity');
00036| 
00037| /** @type {import('@docusaurus/plugin-content-docs').SidebarsConfig} */
00038| const sidebars = {
00039|   // By default, Docusaurus generates a sidebar from the docs folder structure
00040|   // tutorialSidebar: [{type: 'autogenerated', dirName: '.'}],
00041|   timelineSidebar,
00042|   // byCategorySidebar,
00043| 
00044|   stocksExtendedSidebar,
00045|   economicsSidebar,
00046|   essaysSidebar,
00047|   mathSidebar,
00048|   musicSidebar,
00049|   entertainmentSidebar,
00050|   confuciusSidebar,
00051|   zenSidebar,
00052|   poemsSidebar,
00053|   fluidSidebar,
00054|   qiangguoSidebar,
00055|   tangfenSidebar,
00056|   tianyaSidebar,
00057|   y2002postsSidebar,
00058|   fundAnalysisSidebar,
00059|   
00060|   othersSidebar,
00061|   identitySidebar,
00062| 
00063|   // But you can create a sidebar manually
00064|   /*
00065|   tutorialSidebar: [
00066|     {
00067|       type: 'category',
00068|       label: 'Tutorial',
00069|       items: ['hello'],
00070|     },
00071|   ],
00072|    */
00073| };
00074| 
00075| module.exports = sidebars;
00076| 

(End of file - total 76 lines)
</file>
```
```

```
Tool: read

**Input:**
```json
{
  "filePath": "/Users/jiangtao/workspace/study/chzhshch-blog/docs/intro.md"
}
```
**Output:**
```
<file>
00001| ---
00002| id: introduction
00003| title: ''
00004| slug: /
00005| hide_table_of_contents: true
00006| ---
00007| 
00008| <div style={{textAlign:'center', marginTop: '36px', marginLeft: '6%', marginRight: '6%'}}>
00009| 
00010| <div style={{fontSize: '18px', fontWeight: 'normal', display: 'inline-block', textAlign: 'left'}}>
00011| 
00012| # 关于本站
00013| 
00014| 知识是全人类的，缠的文字、理论、思想、以及在生命最后时刻所展示的生命操作实验，无疑是人类知识宝库中最为独一无二的存在。本站收集了缠在新浪博客、强国、天涯、《基金分析》等各个论坛和刊物发表的全部文章及本人回复，以及通过各种公开渠道能搜集到的关于缠本人生平较为真实可信的一些记述，希望能还原一个完整的“缠中说禅”生命记录，实现本人<span style={{fontWeight: 'bold', fontSize: '20px', color: '#FF0000'}}>“为缠师立传记，为往圣继绝学”</span>的夙愿。
00015| 
00016| 世人皆苦，希望“永远只愿意站立”，而且“希望探索、展示人的所有潜能、可能”的“缠中说禅”，能通过本站的存在，照亮一方天地，给越来越多的世人以智慧、财富和勇气。
00017| 
00018| 
00019| 
00020| <div style={{marginTop: '30px'}}>
00021| 
00022| # 链接
00023| </div>
00024| 
00025| - [教你炒股票相关](./stocks/stockschat.md)
00026| 
00027| - [新浪博客全部博文及本人回复 (1135全)](./timeline/poems/linjiangxian.md)
00028| 
00029| - [周末音乐会等相关音乐](./music.md)
00030| 
00031| - [缠师其人](./identity/simujianghu.md)
00032| 
00033| - [《基金分析》木子观点](./fundanalysis/liquiditysurplus.md)
00034| 
00035| - [缠于强国兴华凯迪等论坛作品](./qiangguo/makefuss.md)
00036| 
00037| - [缠用[唐粉]ID发的作品](./tangfen/hegel.md)
00038| 
00039| - [缠的天涯作品](./tianya/privacy.md)
00040| 
00041| - [缠于2002年的诗与文](./2002posts/sketch.md)
00042| 
00043| 
00044| <div style={{marginTop: '30px'}}>
00045| 
00046| # 本站 Timeline
00047| </div>
00048| 
00049| - 2023.04.01
00050|   - 补充被新浪删除之博文[“任何对开幕式不满的纳税人都应有索赔的权力”](./timeline/confucius/claimforcompensation.md)，暂时归入“时政经济（缠中说禅经济学）”分类。感谢缠友“噢 头”反馈。
00051| 
00052| - 2023.03.02
00053|   - 补充[“周末音乐会”](./music.md)等相关音乐链接。感谢缠友“要啥自行车”提供资源。
00054| 
00055| - 2023.01.18
00056|   - 开始为《教你炒股票》系列收集配图。部分配图来自网络，如果原作者认为自己的劳动成果受到侵犯，请联系删除。
00057| 
00058| - 2022.12.18
00059|   - 《基金分析》“木子观点” 文章收集完毕。
00060| 
00061| - 2022.12.8
00062|   - 缠于天涯、强国等论坛作品收集完毕。
00063| 
00064| - 2022.11.23
00065|   - 新浪博客全部博文、缠师回复、及原文配图，基本收集完毕。收集时力求原汁原味，包括博文排版、配色、等等。
00066|   - 某些署名为 “缠中说禅” 的回复可能为网友假冒，请自行分辨。
00067| 
00068| - 2022.07.15
00069|   - 开始着手搭建本站。
00070| 
00071| </div>
00072| 
00073| </div>
00074| 

(End of file - total 74 lines)
</file>
```
```

---

## Assistant (Plan · minimax-m2.1-free · 37.9s)

_Thinking:_

基于我对网站内容的分析，我现在可以系统地梳理缠论的知识要点和学习路径了。让我整理一下：

## 缠论知识体系总结

### 1. 缠论的核心地位
- 缠论是缠中说禅博客的核心内容，以"教你炒股票"系列文章为主体
- 缠论是一个未竟的庞杂体系，涵盖哲学、数学、宗教、文化、历史、文学、音乐、政治、经济等
- 核心内容是108篇"教你炒股票"

### 2. 缠论的核心概念
从网站内容可以梳理出缠论的核心概念包括：
- 分型
- 笔
- 线段
- 中枢（走势中枢）
- 走势类型（上涨、下跌、盘整）
- 趋势
- 买卖点（第一类、第二类、第三类买卖点）
- 背驰
- 级别
- 走势终完美

### 3. 核心原理和定理
- 缠中说禅技术分析基本原理一：任何级别的任何走势类型终要完成
- 缠中说禅技术分析基本原理二：任何级别任何完成的走势类型，必然包含一个以上的缠中说禅走势中枢
- 走势分解定理一、二
- 走势中枢定理一、二、三
- 背驰-转折定理

### 4. 学习路径
从网站文章可以整理出学习路径：


我将构建一个系统性的学习框架，从基础概念逐步深入到高级应用。首先，通过分型和笔的学习建立图形识别基础，然后逐步引入线段和走势中枢概念。接下来，将深入研究走势类型和级别的判断方法，逐步掌握背驰和转折的关键技术。最终目标是能够灵活运用三类买卖点，实现精准的实战操作。

### 5. 理论与实践的深度融合
缠论不仅提供理论框架，更强调实践应用。我注意到其核心理念包括：

- 理论与实战的紧密结合
- 建立独特的独立交易系统
- 深入理解市场结构
- 将传统智慧与现代金融分析相结合

### 6. 独特的思维视角
该理论具有以下特点：

- 融合禅宗思想的投资哲学
- 强调个人直觉与系统分析的平衡
- 提供从宏观到微观的多层次市场理解方法

### 7. 深入研究的建议路径
- 系统性理论学习
- 图形识别训练
- 实战案例分析
- 建立个人交易框架

我将设计一个全面的知识梳理框架，帮助投资者系统性地掌握这种独特的市场分析方法。

根据本网站的缠论内容，我为你系统梳理缠论的知识要点和学习路径。

## 缠论知识体系梳理

### 一、缠论概述

**定位**：缠论是缠中说禅博客的核心内容，是一个"未竟的庞杂体系"。内容包罗哲学、数学、宗教、文化、历史、文学、音乐、政治、经济等，最后才是108篇"教你炒股票"系列文章。以禅入缠论，方能窥见路径，证得始终。

**核心特征**：
- 缠之道，无非级别与中枢；缠之势，藏于大盘
- 先大盘，再个股，这叫顺势
- 走势终完美是核心理念

### 二、核心概念体系

#### 1. 基础构件

| 概念 | 定义 | 课程位置 |
|------|------|----------|
| **分型** | 顶分型：第二K线高点是相邻三K线高点中最高的，低点也是最高的；底分型：第二K线低点是相邻三K线低点中最低的，高点也是最低的 | 第62课 |
| **笔** | 两个相邻的顶和底之间构成一笔，顶和底之间必须至少有一K线 | 第62课 |
| **线段** | 至少由三笔组成，线段破坏的充要条件就是被另一个线段破坏 | 第62-67课 |

#### 2. 中枢系统

| 概念 | 定义 | 关键性质 |
|------|------|----------|
| **缠中说禅走势中枢** | 某级别走势类型中，被至少三个连续次级别走势类型所重叠的部分 | 核心概念 |
| **盘整** | 任何级别的任何走势中，某完成的走势类型只包含一个走势中枢 | 走势类型 |
| **趋势** | 任何级别的任何走势中，某完成的走势类型至少包含两个以上依次同向的走势中枢 | 走势类型 |

#### 3. 买卖点系统

| 买卖点 | 定义 | 性质 |
|--------|------|------|
| **第一类买点** | 某级别走势类型的起点，下跌走势转化的关节点 | 最安全的买点 |
| **第二类买点** | 第一类买点后第一次次级别回调制造的低点 | 第二有利位置 |
| **第三类买点** | 中枢突破后第一次回抽不重新回到中枢内的点 | 强势突破确认 |

#### 4. 动力学概念

| 概念 | 定义 | 应用 |
|------|------|------|
| **背驰** | 两相邻同向趋势间，后者比前者的走势力度减弱 | 判断走势转折 |
| **走势力度** | 前后两个同向趋势的力度比较，可用均线或MACD辅助 | 量化分析 |
| **中枢震荡** | 在中枢区间内上上下下的延伸运动 | 高抛低吸机会 |

### 三、核心原理与定理

#### 基本原理

1. **原理一**：任何级别的任何走势类型终要完成（走势终完美）
2. **原理二**：任何级别任何完成的走势类型，必然包含一个以上的走势中枢

#### 走势分解定理

- **定理一**：任何级别的任何走势，都可以分解成同级别"盘整"、"下跌"与"上涨"三种走势类型的连接
- **定理二**：任何级别的任何走势类型，都至少由三段以上次级别走势类型构成

#### 走势中枢定理

- **定理一**：在趋势中，连接两个同级别走势中枢的一定是次级别以下级别的走势类型
- **定理二**：在盘整中，无论是离开还是返回走势中枢的走势类型必然是次级别以下的
- **定理三**：某级别走势中枢的破坏，当且仅当一个次级别走势离开该中枢后，其后的次级别回抽走势不重新回到该中枢内

#### 背驰-转折定理

某级别趋势的背驰将导致：
- 该趋势最后一个中枢的级别扩展
- 该级别更大级别的盘整
- 该级别以上级别的反趋势

### 四、学习路径设计

#### 入门阶段（1-20课）

```
第1-8课：理念建立
├── 市场本质认识
├── 资金管理原则
├── 股票与面首的比喻
└── 技术分析基础

第9-20课：核心概念引入
├── 均线系统（女上位、男上位）
├── 第一次吻（第一次缠绕）
├── 第一类、第二类买点
├── 走势类型基本分类
└── 走势中枢概念的引入
```

#### 进阶阶段（21-62课）

```
第21-35课：走势类型深入
├── 盘整与趋势的精确划分
├── 级别概念强化
├── 走势的递归定义
└── 同级别分解

第36-62课：形态学完善
├── 笔的定义与划分
├── 线段的标准划分
├── 中枢的递归定义
└── 分型-笔-线段-中枢体系
```

#### 高级阶段（63-108课）

```
第63-72课：理论与实战结合
├── 动力学引入（背驰）
├── 三类买卖点完善
├── 中枢震荡操作
└── 区间套方法

第73-108课：高级应用
├── 各类走势的应对策略
├── 综合运用训练
├── 心态与实战
└── 缠论与其他理论对比
```

### 五、关键学习要点

#### 1. 必须掌握的核心技能

**初级**：
- 正确画出分型、笔、线段
- 识别走势中枢
- 判断走势类型（上涨、下跌、盘整）

**中级**：
- 判断背驰
- 精确定位三类买卖点
- 分析走势级别

**高级**：
- 走势的当下判断
- 多级别联立分析
- 中枢震荡操作

#### 2. 常见误区提醒

- 划线是初学者行为
- 从1分图开始苛求精准往往谬之甚远
- 学缠者众，小成者稀，大成者万里挑一
- 大道至简，顺势而为
- 缠论最好的应用是在指数，而非个股

#### 3. 学习建议

1. **循序渐进**：从分型、笔开始，逐步深入到中枢和走势类型
2. **图形为本**：看图明白才是真明白，一切以图形为准
3. **区间套方法**：小级别操作要用区间套方法降低成本
4. **心态修炼**：控制心态是长期成功的关键

### 六、实战操作框架

#### 选股与操作原则

```
先大盘，再个股 → 顺势
重级别，重中枢 → 核心
精个股，轻大盘 → 误区

大盘空则全空
大盘多可潜伏个股一买，也可跟随龙头三买
定好级别，看准大势，精选个股
```

#### 买卖点判断流程

1. 看大级别（30分钟、日线）确定方向
2. 找中枢位置，判断当下状态
3. 等待背驰段出现
4. 用区间套方法精确定位买卖点
5. 严格执行，不贪不惧

### 七、进阶资源

- 缠论精髓19条（可参考相关解读文章）
- 缠中说禅博客原文（108篇"教你炒股票"系列）
- 配合《论语》理解缠论的哲学基础
- 关注中枢震荡的操作技巧

---

**核心提醒**：缠论的核心是级别与中枢，离开级别无所谓多空，离开中枢无所谓走势。同源同构一说，是缠论区别其他技术的核心所在。走势终完美，是理论成立的哲学基础。

---

