# AI 工具站 SEO 小册子：图解入门

> 4月10日修改  
> 8:13483 @18979

## AI 速览

本文讨论了 AI 工具站 SEO 的相关知识，涵盖从基础认知到实战操作以及高级实践等多方面内容，旨在帮助提升网站在搜索引擎上的表现。

> 我推崇把网站当成一本书 & 内容产品来做增长的策略，在写这本 SEO 小册子。  
> 因上努力，果上随缘，希望自己坚持写到底。

## Playbook 大纲

### 当前完成进度

- 零、前言
  - 序 1：Modern SEO as a System or Product
  - 感觉不需要序了
- 一、SEO 基石篇：认知打底，准备启动
  - 1.1 章节：SEO 的理想用户画像 ICP（Ideal Customer Profile）
  - 1.2 章节：什么是搜索用户的 Last-Click
  - 1.3 章节：SEO 不是技巧，是系统化竞争工程
  - 1.4 章节：寻找并了解你的 SEO 竞争对手
- 二、SEO 实战篇：站内基建
  - 2.1 章节：SEO 基建
  - （酝酿中）On-page SEO：页面骨架 & 规范
  - （酝酿中）URL Structure：网站内容架构
- 三、SEO 实战篇：SEO 内容创作
  - （酝酿中）关键词挖掘：专为 AI Tool Website 的方法
  - 3.2 章节：关键词搜索意图 → 页面内容定位 & 页面类型匹配
  - （酝酿中）工具页 SEO 内容规范
- 四、SEO 实战篇：外链建设
  - 4.x 章节：SEO 外链必知必会
  - 4.x 章节：外链 - Citations 目录站/导航站/评测站最快的 0→1 打法
- 五、其他 SEO 高级实践篇
  - 5.x 章节：pSEO（程序化 SEO）的双刃剑：失败案例和成功实践

### 作者信息

- 我暂时不卖课
- 爱好写点东西
- 我的小推特：<https://x.com/CoderJeffLee>
- 我的小即刻：<https://okjk.co/DjBa9>
- 我的小博客：<https://bysocket.com/>

## SEO 相关 Skill

- 开源项目：SEO 审计工具 `seo-audit-skill`

## SEO 相关杂文

自认为最佳到最杂

### 2026

- 《SEO = 内容系统 + 信任系统 + 结构系统（完整拆解）》
- 《SEO 搜索意图 → 页面内容 & 页面类型匹配》
- 《回顾去年 AI 出海 6 问 + SEO 实战 7 答》
- 《SEO 关键词要不要拆成多篇文章写？》
- 《为啥 SEO 不能做别人的品牌词？我排第二可以》

### 历年合集

- 《2025 出海分享合集：SEO / 增长 / Agent》
- 《子木 2024 出海分享合集》

## 零、前言

### 序 1：Modern SEO as a System or Product

现代 SEO 的本质目标没有改变 - 解决搜索用户需求并完成交付结果。

它仍隶属于搜索与检索体系中，只是进入了AI时代后，SEO本身的规则和信号都在不断演化。如今的Google搜索引擎已是一个智能化的系统工程，因此SEO工作也必须以“系统思维”去做，大家可以按照以下4个维度去执行

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//cc84ce70-6758-4fcb-a7fc-c9c68bea1444/markdown_0/imgs/img_in_image_box_418_1252_615_1359.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A17Z%2F-1%2F%2F893a38c7a18f5e4023b6713ec077e91094b9143122993bc0e9a967df642b5130)

### A. 产品层 (Search-Fit Product)

搜索关键词 → 功能与信息结果的设计。要让产品、功能、页面都源自搜索意图的反推，可以竞品等维度参考。

何为 Search-Fit Product?

意图匹配：信息型 → 教程；商业型 → 对比 / 替代；交易型 → 定价 / 落地；功能型 → 试用 / Demo 等等

就是这个业务能让用户“在此页面就能把事做完”

无论是表单提交，在线演示，下载模板，功能对比还是 FAO，只是不同页面的实现形式。

核心是让页面本身完成用户任务，不再跳出。

### B. 内容层 (Information Gain)

在 AI 时代，信息与工具都已不稀缺，真正稀缺的是“信息增量”。要通过合理分类与页面类型来提供比竞品更多、更准的信息。

- 内容类型：对比页 / 替代页 / 教程页 / 模板页

信息增量来源：案例、数据、截图、实验结论、实测差异

必须准确、可验证，拒绝“胡编内容”

例如：“去水印”这个关键词，如果页面能提供以下功能，这就是增量信息：

- 批量去水印功能
- 针对特定模型（如 Sora 2）的去水印功能

### C. 技术层

技术层是整个 SEO 的地基。

- 可抓取、可索引、可被智能模型理解：robots、sitemap（自动 lastmod）、canonical、hreflang、状态码等
- 性能标准（Core Web Vitals）：LCP、CLS、INP 分数保持在 70~80 以上；图片压缩与缓存、关键 CSS 内联等
- On-Page 优化：Title / Meta / H1 / H2 结构合理；图片 alt 完整；JSON-LD Schema 合规等

#### 页面模板结构可抽取

结论 / 步骤 / 对比 / FAQ 四件套

- 方便搜索引擎与 LLM 摘要理解页面

### D. 运营层

SEO 运营不是品牌公关，而是站内外运营：

外链生态：主题相关的引用、目录站、资源页、客座文、AI导航站、AI Newsletter等。建立主题权威与可发现性。

外链生态：主题相关的引用、目录站、资源页、客座文、AI 导航站、AI Newsletter 等。建立主题权威与可发现性。

- 索引与提交：GSC 手动提交 + API 自动提交；监控收录、内链、内容回补。

CTR 与 Last-Click：标题与摘要要匹配搜索意图，也要提高点击率。然后让进来的用户解决问题，成为的“最后一次点击”。

#### 度量指标 (Metrics)

流量层面：非品牌自然点击量

- 流量层面：Top20 / Top10 关键词对应页面的覆盖率

流量层面：有效索引率

转化层面：Money Pages（核心 SEO & 转化页）转化率

现代 SEO 是让搜索用户在你这里把事做完。我们通过产品匹配 + 信息增量 + 技术可见性 + 检索信号 来获得排名与转化。

它不依赖品牌曝光，而是专注于让搜索系统与用户同时验证你页面的双重真实价值。

本序章节完毕，谢谢大家，欢迎随时讨论。

## 一、 SEO 基石篇：认知打底

### 1.1 章节：SEO 的理想用户画像 ICP

SEO 的 ICP（Ideal Customer Profile），即就在搜索框输入与你业务高度相关词的客群。其重点在于先理清楚“谁在搜、为啥搜、搜完后需要找到什么”，再决定做什么页面以及下一步 CTA 转化如何设计。因此在正确的搜索用户面前展示正确的页面是第一步，也是最重要的一步。

### a. 谁在搜：AI 工具网站为例

AI 工具站常见的 3 类搜索决策用户如下

使用者：要找到马上能用的功能 / 模板等。搜索词 - 比如 AI 批量去背景、3D 视频特效 Prompt 等等

- 购买者：一般是技术负责人（DM 或 Dev），要评估对比 / 价格 / API 等。搜索词 - 比如 A vs B、A Alternatives、A Pricing / API 等等
- 学习者：要搞清楚是什么、怎么做等最佳实践。搜索词 - 比如 How-to xx、xx Guide 等等

确定 SEO 的 ICP，其画像包括行业 / 角色、要完成的目标、搜索主体验的关键行为等。理清楚这些才决定你做什么样的页面，大概 3 个维度：

- Content Type 页面内容类型：比如文章页、产品页、集合页等等

Content Format 页面内容格式：比如教程类、清单类、对比类等等

- Content Angle 页面内容角度：比如最新、免费、批量等等

有个小技巧，就是先看看 SERP（Search Engine Results Page）美区最前 10 个页面的类型 / 格式 / 角度，再决定你该做什么页和什么内容。比如：AI 工具网站为例，常见的页面

- 信息型 → 教程 / How-to
- 商业型 → 对比（A vs B）、替代（Alternatives）
- 交易型 → Pricing、Demo / Trial、下载、
- 导航型 → 品牌 / 功能入口页、集合页

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//cc84ce70-6758-4fcb-a7fc-c9c68bea1444/markdown_2/imgs/img_in_image_box_260_49_747_235.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A18Z%2F-1%2F%2Fbdf35c7da0ae084bd8acd4d0f1502654379cf1cacb535cd8d5abfd19d5d7fd53)

### b. 那如何刻画 SEO 的 ICP?

可以根据下面 6 个维度去刻画 SEO 的 ICP:

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//cc84ce70-6758-4fcb-a7fc-c9c68bea1444/markdown_2/imgs/img_in_image_box_260_314_352_424.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A18Z%2F-1%2F%2F879c63c0bc90f92445e73bf9b4dad2bc0891216ef7100d1619e5c24410dab027)

基本信息：角色 / 行业 / 地域

行为任务：这次搜索要把哪件事完成

意图阶段：Info / Commercial / Transactional / Navigational

关键词簇：主词、长尾、同义词、问题词等

证据偏好：更在意的维度，这是给页面内容角度的方向参考。比如其重视价格、隐私等等

转化路径：Demo → 注册 → 试用 → 付款

#### 其中有两个小技巧

如何刻画，不只是SEO Research的结论，也得结合产品运营的用户访谈等多个方式，一起去确定用户画像

有了用户画像，也就有了关键词簇，这样下一步通过 SEM 关键词投放验证 MVP 的转化和商业化情况。这样即使效果不佳，也是个好结果。然后继续假设验证新的 MVP

因此，SEO 的 ICP 不是“抽象人设”，而是有明确任务的搜索者：识别他是谁（角色）、为啥搜（意图）、要在网页把什么事做完，再对齐 SERP 来决定页面类型 / 格式 / 角度。这样产出的页面，既满足人，也满足搜索引擎的底层逻辑。

但搜索行为 20% 存在比较模糊，可能有很多种含义。所以做 SEO 运营的人，需要有同理心和共情力，关键是理解你需要的受众，通过掌握 SEO 的理想用户画像为目标，去执行 SEO 方法，更有效的接触和留住这些用户。

本章节完毕，谢谢大家，欢迎随时讨论。

### 1.2 章节：什么是搜索用户的 Last-Click

❤️：这一章节内容，感谢老猫@杭州、《The Art of SEO》

大家都用过搜索引擎。只要有搜索框，就有SEO。只要你在搜索框里输入过任何东西，你一定是带着目的来的。不管是小红书的搜索框、微信“搜一搜”，还是谷歌或百度。

有搜索框就会有搜索结果。现在搜索结果里，会多出一部分 AI 信息，比如谷歌的 AI Overview、微信“搜一搜”的 AI 元宝快速回答。

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//cc84ce70-6758-4fcb-a7fc-c9c68bea1444/markdown_2/imgs/img_in_image_box_290_935_456_1131.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A18Z%2F-1%2F%2F737be68a4b6da44d8ee18850ce347d601de0d89a8002a3088402f5087eef6701)

#### 如何做好谷歌 SEO 外链

做好谷歌SEO 外链需要综合考虑多个因素，以下是一些关键要点和方法：

权威性：优先选择商权重，行业相关的网站，如行业媒体，专业博客等，可通过Aveo Semrush等工具评估网站权重（如Domain Authority）。

相关性：确保外链网站与自身业务或内容主题高度相关，例如太阳能板供应商应选择新能源领域网站。

2. 优化外链质量与布局

避免低质量外错：避免论坛、采集站、PBN等垃圾外错，这类外错可能被谷歌算法过滤，甚至影响网站信誉。

- 福文本 ·

A国家·快速运营%

如上图，用户可能会去看 AI Overview，就已经解决问题（当然还有很早期不需要点击就能被直接解决的，比如在谷歌上搜“今天的天气”）。但更多的其他搜索用户，不同的搜索词还是会点开下面自然排名第一名网站。只要点进某个网站去解决问题，就产生了点击。

这个点击，也是我们做网站 SEO 的目的。在网站的 SEO 目标上，我们需要搜索用户点击进入我们的网站，是第一步。

有了点击，Last-Click 的策略才有意义。那什么是 Last-Click 呢？

#### Last-Click

从用户角度，用户在搜索结果里点击了你的网站，不再去点其它网站；也不会很快关掉你的网站、重新输入别的搜索词去看新的结果。

从谷歌搜索引擎角度，说明你的页面真正解决了该搜索词对应的用户搜索意图，你的站点有价值。

这就像一本教你做家常菜的书：今天想做清蒸鲈鱼，你在这本书里已经得到完整解法，就不会再去翻别的书，或者再搜“鲈鱼最佳做法”，找其他书。这里的书约等于你的网站！

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//cc84ce70-6758-4fcb-a7fc-c9c68bea1444/markdown_3/imgs/img_in_image_box_327_32_705_190.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A20Z%2F-1%2F%2Fcc089c911ca7cf1349c32478d325ab39184d4fae2ad07a61ca50ea68184cc6da)

#### 第一个问题：谷歌怎么知道你的网站是不是 Last-Click?

有一些明确的信号，比如页面浏览深度、平均停留时长等行为指标。再加上谷歌“全家桶”的侧面数据（例如Chrome浏览器等，数据样本非常丰富），足以帮助谷歌智能搜索模型判断页面是否有效解决搜索意图。所以把网站做到位，让谷歌“知道”你的站对应很多搜索词都是Last-Click，是非常关键。这其实回到了产品第一的本质

#### 第二个问题：怎么把网站做到位，做到 Last-Click 级别？

可以试着把网站当成一本书、当成一个产品去做。

- 如果是博客类型，就是内容型产品 / 教程型产品；
- 如果是功能类型，就是工具型网站。

记得用户搜索词往往意图模糊。比如搜 "AI tattoo": Text to tattoo

可能是想用文字描述生成纹身图

- 也可能已经有纹身贴图，想要试穿（try-on）到手臂或其他部位

这意味着你的工具网站要尽可能全面地解决这一系列需求，才能做到位，也就是成为真正的“酒香”。

我们常说“酒香不怕巷子深”，但在SEO这边不是的。你的“酒香”大概率确保最后一个点击落在你这儿，这样来的用户才能试用、产生留存，最终转化为付费/订阅。但不一定能排名到第一名！

#### 第三个问题：我把工具、内容和体验都做好了，就一定能拿自然第一名吗？

不一定。这个我们会在后面的实战章节展开。除了内容与体验，还有很多核心因素——外链尤为重要，其次还有内链优化、On-Page SEO 等等。

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//cc84ce70-6758-4fcb-a7fc-c9c68bea1444/markdown_3/imgs/img_in_image_box_262_708_749_955.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A20Z%2F-1%2F%2F8d2e29f4dd634c706ec1851ac9aa6a85ce5c6374d03441aefb9ebcca2f396d02)

本章节完毕，谢谢大家，欢迎随时讨论。

### 1.3 章节：SEO 不是技巧，是系统化竞争工程

❤️：这一章节内容，感谢 Joker 当时分享的关键词搜索意图，非常赞！

#### 一、你眼中的谷歌 SEO

很多人理解的谷歌 SEO 很简单：

- 有排名 = 有流量

排名靠前 = 自然流量

所以：SEO = 排名

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//cc84ce70-6758-4fcb-a7fc-c9c68bea1444/markdown_3/imgs/img_in_image_box_257_1289_508_1425.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A20Z%2F-1%2F%2Ff9fef6aa3546429546c7ac38c1d4dba805aed74914bea4fbb857c5ab01dc4472)

从结果层面看没错，但从系统层面看，可以换一个更直观的模型这样理解：

谷歌搜索引擎 = 书架系统

- 你的网站 = 一本书
- 你的网站页面 = 书的章节

SEO 排名 = 你的书 / 章节在书架上的位置

SEO 的本质即是“写文章”，但也是让你的书和章节在书架系统里获得更靠前的位置。

#### 拆开就是

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//cc84ce70-6758-4fcb-a7fc-c9c68bea1444/markdown_4/imgs/img_in_image_box_264_124_502_221.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A21Z%2F-1%2F%2Fdac36f7dc3549a13fdf1fd2025d319896b29c8b81739244ab26f75cf1b854087)

SEO排名= $ \left(\text{页面内容}+\text{页面基建}\right)+\text{外链} $

站内

页面基建（Technical SEO + UX）

页面内容（结构 + 搜索意图 + 信息质量）

外链（信任投票系统）

这是一个完整的 SEO 竞争框架，不是单点优化问题

2. 1 页面基建 (SEO 的地基系统)

谷歌是网页搜索引擎，本质是爬虫 + 页面理解系统。

如果你的网页：

- 打不开 / 加载慢
- 结构混乱 / 适配差
- 稳定性差

相当于你的书质量很差，翻都翻不动！那连“上书架”的资格都没有，更谈不上排名。

这就是 Technical SEO 的本质意义：不是优化排名，而是保证可索引、可理解、可使用。

核心维度包括：

- 页面性能

前端加载

多语言

后端响应

。lang

CDN

。hreflang

服务稳定性

- 语义结构

结构化数据

- 结构系统

schema 自动化

URL 结构

其他

目录层级

- robots.txt

内链结构

- sitemap.xml

设备体验

响应式适配

404 / 重定向处理

这些东西的特点只有一个：

- 基本是一次性工程
- 是“系统地基”，不是内容产出型工作

网站大改版才会重新 Check & 修复，不是日常 SEO 动作。

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//cc84ce70-6758-4fcb-a7fc-c9c68bea1444/markdown_4/imgs/img_in_image_box_397_976_639_1095.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A21Z%2F-1%2F%2F5cd9187de51f697b7ff1dfc3b2aea3c2bc34a772b535bff5ea02b594d92b41c3)

2. 2 页面内容 (SEO 的核心竞争力)

#### a、页面形式 (Content Type)

页面首先要解决的是：装内容的容器是什么形态

比如：

- 落地页

博客页

工具页

资源下载页

Prompt 页

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//cc84ce70-6758-4fcb-a7fc-c9c68bea1444/markdown_4/imgs/img_in_image_box_527_1233_773_1370.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A21Z%2F-1%2F%2F99bd9d652b6c9b0c838b88bce975a36a64a63169f39966d17bda77ee9b2edaed)

这个不是你决定的，是谷歌 SERP 决定的：SERP 前排是什么页面形态，你就做什么形态这是 Google 的内容结构喜好的逻辑，不是创作者偏好。

#### b、搜索词决定竞争难度

排名难度大 - 词：创业、视频生成

排名难度中 - 词：AI 创业、AI 视频生成

蓝海词：独立开发者 AI 创业、AI 音乐视频生成

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//8086160b-d8f0-44dd-abc6-e7553163d793/markdown_0/imgs/img_in_image_box_556_41_749_179.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A47Z%2F-1%2F%2F94db833fe952fe7cf04cf2ac27538d3ac2f9b932e9a0256111f58ee7d42dc895)

新站逻辑，推荐农村包围城市策略：蓝海词→中等词→大词

不是战略选择，是竞争游戏的优先级选择逻辑。

#### c、搜索意图决定优先级

搜索意图决定的不是能不能做，而是：

- 做不做

先做哪个

- 做成什么形态
- 投入资源值不值

信息类、交易类、商业类，本质是用户价值密度不同。

零点击时代，本质变化就是：

信息型价值密度下降

决策型、交易型价值密度上升

所以关键词优先级不是按搜索量排，是按转化意图强度排。

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//8086160b-d8f0-44dd-abc6-e7553163d793/markdown_0/imgs/img_in_image_box_537_520_772_659.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A47Z%2F-1%2F%2F90d9cdebba34ec5ddaaa968a85f3dd9514d5a87b93888df6d658150ed226cf79)

#### d、关键词研究决定站点结构

第一阶段的关键词 research 不是写内容，而是定结构：

决定：

- /tools
- /blogs
- /resources
- /docs
- /models
- /api

这不是 SEO 技术问题，是页面信息架构问题。SEO 本质不是页面工程，是内容系统工程。

#### e. SEO 内容创作的核心目标

不是“写文章”，而是：同时满足两个系统

- 搜索引擎理解

用户搜索价值

所有内容必须同时满足：

Google 能理解

用户能通过内容解决真实问题

这也是为什么要做：

- 页面结构化（H1 H2 H3）
- 模块化（功能 模板 FAQ How to Use）
- 意图匹配（页面类型匹配搜索意图）

信息密度控制（不是堆字数）

#### f、内链本质

内链不是 SEO 技巧，是权重引导系统。比如一个网站 1 万个页面：Google 不可能认为 1 万个页面同等重要

内链的本质是告诉 Google:

- 哪些是核心章节

哪些是次级章节

哪些是支撑内容

这就像一本书：

目录结构

- 核心章节

重点章节

- 辅助章节

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//8086160b-d8f0-44dd-abc6-e7553163d793/markdown_1/imgs/img_in_image_box_533_34_773_176.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A49Z%2F-1%2F%2F5e07c772cd122cd0d24e7e3ea665d9b32adab5b0a082098fed898a3261defaa5)

## 三、外链（站外信任系统）

SEO 排名结构 =

站内：内容 + 基建

站外：外链

外链本质是信任投票系统。

外链的作用：

1. 排名提升：提升关键词页面在 SERP 中的权重竞争力
2. 引荐流量：导入真实用户，不是爬虫信号
3. 发现与收录：外链 = 给爬虫修路。比如新站新页，有外链比只交 sitemap 更快收录

外链简单可以分两类：

首页外链：提升整站权重基数、影响全站的各个页面的排名

页面外链：提升单页竞争力、用于打核心关键词页

外链必须是自然增长模型。如果一个新站：

- 短时间大量新增高质量外链

来源结构异常集中

## 自然 vs 风控触发

- 增长曲线异常陡峭

结果只有一个：

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//8086160b-d8f0-44dd-abc6-e7553163d793/markdown_1/imgs/img_in_image_box_534_608_767_716.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A49Z%2F-1%2F%2F191885b876535f3d0238311c54d10a34c9c3aa94bfd3822cf2c88a7987394cde)

不是提升，是风控触发。

## 四、总结一句话

SEO 不是优化页面，SEO 是页面内容参与一个竞争系统

这个系统由三部分组成：

- 技术系统（页面能不能被理解）
- 内容系统（用户和 Google 是否认可）

信任系统（外部世界是否投票给你）

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//8086160b-d8f0-44dd-abc6-e7553163d793/markdown_1/imgs/img_in_image_box_556_831_747_945.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A49Z%2F-1%2F%2Fc994f808479df423e197d86fa82d5ef26c803a2608f3472bf48ef43d3925ad6e)

SEO = 系统工程不是单点优化

不是运营技巧，是系统工程。

不是写文章，是构建内容产品。

不是做 SEO 项目，是做一个能在搜索系统里长期竞争的内容型产品体系。

如果要压缩成一句话作为方法论总结：

谷歌 SEO 不是排名技术，而是内容系统 + 信任系统 + 结构系统的长期竞争工程。

本章节完毕，谢谢大家，欢迎随时讨论。

### 1.4 章节：寻找并了解你的 SEO 竞争对手

❤️：这一章节内容，感谢《创业清单》某一章节内容对我的启发

在规划和启动 SEO 时，对 SEO 做得不错的竞争网站有明确、详细的洞察是非常重要的。

一方面，你以为你很懂客户，但你可能不懂搜索用户在搜索什么，以及其背后的搜索意图。比如用户可能搜“最好的AI写作工具”，也可能搜“如何用AI提升写作效率”，这两种搜索背后的需求和决策阶段是不同的。这里，洞察竞品能给你多一个搜索维度去了解你的客户。

另一方面，每个新站都应当做 SEO 竞争性分析，最起码能了解 SEO 流量渠道能不能做？现阶段该不该做？如果竞品都是 DR 70+ 的老站，你一个新站短期内很难竞争；但如果有不少新站在快速起量，说明这个赛道还有机会。

这里分享下寻找并了解你的 SEO 竞争对手的方法。

## 一、 如何找到 SEO 竞争对手

在这个 AI 创业浪潮和长尾时代，基本上 SEO 维度保证你也有未知的 SEO 竞争对手。所以从 SEO 流量维度去看 SEO 竞争对手，不能只看头部那几家。

很多时候，真正跟你抢流量的不是行业老大，而是那些你没听说过、但 SEO 做得很猛的新站。

## 如何找到 & 源源不断找到 SEO 竞争对手？

这里我推荐：类似 Marketing Research 的思路，它不是一次性的任务。这个 SEO Marketing Research 大家可以每月做一次报告，持续提高大家对新的创业公司 & 未知的竞争对手的了解。

## 1、 如何找？

如何找到对标竞品，SEO 做得好的？

通过你们网站对应的业务词根，在谷歌上搜索。

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//8086160b-d8f0-44dd-abc6-e7553163d793/markdown_2/imgs/img_in_chart_box_259_269_368_356.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A50Z%2F-1%2F%2Fe12666527dd1d09d463301a922c21f305efba259b01d169ce2d8ef16a0fd4e52)

免费插件：

<https://chromewebstore.google.com/detail/hhfkpjffbhledfpkhhcoidplcebgdgbk>

然后通过插件去看，筛选条件是：

月访问量大于 100K，且 SEO Search 占比 40% 以上的网站

这说明这个站的流量主要来自 SEO，值得深入研究。

## 2、 怎么看？

我们的目标：找到一些 [SEO 流量不错] × [尤其是新站，代表最近起量] × [对标站]

肯定有对标站，我认为世界之大，肯定有对应的 SEO 玩家和其网站。不要觉得自己的产品太独特没有竞品，换个角度想，满足类似需求、服务类似客群的都可以算作 SEO 竞品。

## 3、 如何找更多？

如何多找？扩词去找。如何扩词：

第一步，确定业务最核心的几个词根。

比如写作方向，ai writing tool、ai writing assistant，或者竞品品牌词 Grammarly .....

第二步，把这些词根扩展成几类搜索词（因为对标站 - SEO 玩家也会写这些文章）：

核心词：就是那些词根本身

best 类词：比如 best ai note taking apps 等

alternatives 类词：比如 Grammarly alternatives、Otter alternatives、Notion AI alternatives 等

- use case 或功能类词：比如 linkedin post generator、ai meeting notes for recruiters

上面讲了方法，其实还要定义什么是 SEO 竞争对手。我认为除了直接的对手，还要包括跟你满足相同基本需求或客群一致的都行。因为要避免大家定义竞品过于狭隘。

比如找到这种，尤其这种2026年的新站。如果SEO占比大，太爽了；尤其关注域名创建时间最新的、增速比较快、以及SEO流量占比大的站点。

起量时间：2026年1月-2月

Search 占比: 74%

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//8086160b-d8f0-44dd-abc6-e7553163d793/markdown_2/imgs/img_in_chart_box_256_938_349_1009.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A50Z%2F-1%2F%2Fe533348d0a154d8a441abdf4a7aeac0d0b93214c56ce1714599ed8caa8a92cf1)

- AI song generator
- 和其他竞品词

还有对应国家都是 T1 国家等

**1 Top Hormone**

| Dopamine | Taurol | Dopamine | 20%   |
| -------- | ------ | -------- | ----- |
| c-oxo-a  | 20     | 20       | 80.18 |
| c-oxo-b  | 20     | 10       | 80.19 |
| c-oxo-a  | 800    | 400      | 80.18 |
| c-oxo-b  | 100    | 100      | 80.17 |
| c-oxo-a  | 200    | 100      | 80.19 |

**1 Top Region**

| Region         | Average |
| -------------- | ------- |
| Urban Region   | 10000   |
| City           | 8,000   |
| Urban/Tropical | 7200    |
| Urban          | 4,100   |

## 二、 如何评估竞争对手

每次评估是为了定新的目标和策略，或者校对自己现有的目标，但 SEO 目标，肯定不是拍脑袋定绝对值。

大概评估的是两个维度：

- 竞争对手的 SEO Top Pages：重点是非品牌词对应带来 SEO 流量的页面，以及其对应的 SEO 内容策略

竞争对手在 SEO 排名上升期：其对应的外链建设策略

有很多方法和工具去评估，下面是我经常用的方法：

1. Ahrefs (或 SEMRush)

## [内容策略评估]

通过 Ahrefs - Top Pages:

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//8086160b-d8f0-44dd-abc6-e7553163d793/markdown_3/imgs/img_in_image_box_255_36_513_223.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A51Z%2F-1%2F%2F27896402515885793d2fed73af0d89026fa5eee1216ae758c4b2f440358a7be2)

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//8086160b-d8f0-44dd-abc6-e7553163d793/markdown_3/imgs/img_in_chart_box_255_36_513_102.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A52Z%2F-1%2F%2F9a2ba0375df4fbcae3d110eaa5128cd4c9eddf8a889e809816f011f3c5e4d166)

去年11月开始

整体 SEO 页面排名靠前

其品牌词 - 首页占比流量才 5.5%

- 通过 URL Slug 和关键词去判断：

他们的内容策略主要是通过模型、功能等落地页

部分是做传统的 Blog

第一步，看整体增长趋势。先看 Organic pages 和 Organic traffic，找出其 SEO 页面增长最快的是哪几个月。这能帮你定位他们的 SEO 爆发期。

第二步，分析非品牌词页面。再去看他们对应的非品牌词页面以及该页面对应的核心关键词。其实一般URL slug就是其核心关键词，可以初步判断其搜索意图。总结出其SEO内容的关键词挖掘方向和内容创作策略：是做工具页面、还是常规的博客文章页面等等。

这里补充一个点：如果非品牌词页面排名第一，可以深度地按照SEO用户角度，搜索这个词，点击进入其网页，体验&注册&转化。这样你的评估会有更深的体验，即让你成为竞争对手的一个新客户，完整体验SEO渠道在竞争对手那里的整体产品转化流程。

## 外链策略评估

通过 Ahrefs - Overview - Backlink profile，去看他们外链增长曲线。这里注意两个点：

AI 工具行业，一般看 DR 50 以下，重点是 DR 30 到 50 区间内他们的外链建设策略。因为当他们 DR 很高、SEO 排名已经很靠前的时候，会有很多自然水外链（别人主动引用），你无法具体参考并借鉴。

重点看其 SEO Organic Top pages 增长最快的哪几个月，到底对应外链是如何建设的。时间点的对应很重要，能看出因果关系。

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//8086160b-d8f0-44dd-abc6-e7553163d793/markdown_3/imgs/img_in_image_box_256_547_409_643.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A52Z%2F-1%2F%2Fdb67b1d354d9b59a7cdf662bea446f014f00c5ba21022d5b805e4d9fea105e8f)

比如这个站，明显看出其2月份SEO起量，然后1~2月外链建设明显加速。

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//8086160b-d8f0-44dd-abc6-e7553163d793/markdown_3/imgs/img_in_image_box_255_651_408_765.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A52Z%2F-1%2F%2Faff1b6cad648ae4747c435ebc3c9ab344da8fce55b882f204e470fff895e1de6)

然后具体看外链 - Referring domains，按 First seen 倒序排列，先看 Dofollow、Best links：总共 491 的 Domain 外链，其中 209 domains 的 Dofollow Best links

一个一个看，看多了就有经验，可见：

前期主要是 AI 导航站外链建设

- 然后同步开展 Guest Post 客座博客外链建设

自然你可以用 Ahrefs 自动追踪其 SEO 变化，尤其是他们非品牌词页面 SEO 整体起量的时候，关注他们上线了什么新的 SEO 页面等等，更值得去细细评估其 SEO 内容策略和外链建设策略。

## 2、 与竞争对手现在和过去的 SEO 员工交流

通过交流、招聘等方式都行，但是注意交流点，大家交流策略就行。根据策略的交流，洞察他们整个站 SEO 起量的阶段和对应的方式方法。

还有一个技巧：洞察竞争对手的招聘JD。JD里面可能能看出他们在做什么策略。比如招聘小语种SEO内容运营说明小语种对他们是一个SEO起量策略，同时也说明某个小语种国家这个产品的转化率不错，值得投入资源。

最后，通过上面几种方法，定下阶段性的 SEO 目标。我认为看多了竞品就会减少确定性偏差，不然容易落入偏差倾向而不自知。

## 三、 如何定 SEO 目标？

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//8086160b-d8f0-44dd-abc6-e7553163d793/markdown_3/imgs/img_in_image_box_397_1104_641_1240.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A52Z%2F-1%2F%2F2a11e6301ba70f20a8e7e3ec8092bd78383feada51bb9dd1232293a546ea97d0)

新站 SEO 的目标，不是直接定“我要多少流量”，而是先对标同类网站近三个月的内容和外链增长曲线，再倒推出自己在流量、页面数、外链数上的阶段性追赶目标。

根据上面的方法，要先找几个对标站，看它们近三个月的页面增长曲线和外链增长曲线，再反推出自己现阶段合理的追赶目标。基于对标，核心就定两类指标：

一类是流量与非品牌词占比

- 另一类是 Top Pages 数、Referring Domains 数等

更实战一点说，就是先算出对标站的 SEO 增长效率，再做环比拆解：我现在差多少页面、差多少外链、差多少非品牌词覆盖，然后把目标落成 3 个月内要补多少页面、外链涨到什么水平、自然流量做到多少。

这样定出来的 SEO 目标才不是空口号，而是有对标、有路径、有节奏的增长计划。

小结：SEO 竞争分析不是一次性任务，而是持续的市场洞察。找对标站、看增长曲线、拆解策略，再反推自己的目标和路径。记住你的竞争对手不只是行业老大，更多是那些你不知道，但正在快速起效的新站

本章节完毕，谢谢大家，欢迎随时讨论。

## 二、 SEO 实战篇：站内基建

### 2.1 章节：SEO 基建

：章节内容，感谢阿彪师傅@Pollo.ai。下面内容包括：SEO 基建What/Why/When/How&Checklist

### a. What | 什么是网站的 SEO 基建？

网站整个 SEO 基建，就相当于一本空白的电子书基础设施。这里可以把网站当成“搜索引擎与用户同时读懂的房子”，那么 SEO 基建就是整个房子的地基与水电，包括 Technical SEO、robots.txt、sitemap.xml、状态码/重定向、分页规范、结构化数据、性能等

更好的理解和做好网站的 SEO 基建，要知道其目的：一方面给谷歌搜索模型或机器看懂（抓取 / 理解 / 索引），另一方面更要给用户好的体验（速度 / 可读 / 可转化）

### b. Why | 为什么要先做基建？

前提大家都知道 SEO 有沙盒期，新站得 3 - 6 个月见效，但只要新网站未来打算做 SEO，就应该从一开始把 SEO 基建先搭好。基本上 AI 工具网站都是需要做 SEO 的，比如 ai xx tool 都可以是首页的关键词。回到为什么呢？因为到中期再重构，这些基建问题会迅速积累成技术债，代价很大。如果等到中期再补，会牵一发而动全身（路由、模板、数据结构都要重构），其成本更高。

搜索机器×搜索用户 vs 权重：极端例子，如果新做了一个3D超炫网站，用户体验100分，但对搜索引擎可见性和可理解性只有60分；与其如此，不如让用户体验80分、搜索引擎80分，整体收益ROI更高。

另外，前期好的基建会带来好的网页抓取预算与稳定增长：url 结构清晰、性能合格、提交规范，抓取与收录也可预期，后期 pSEO（Programmatic SEO）才能规模化。

### b. When & How | 怎么落地？

什么时候开始做？上面也讲过，只要SEO是有效的增长渠道，那么越早越好。比如立项的时候，粗粒度的规划好路由。比如下图zoominfo的案例：

| A           | B       | C                                 | D                                |
| ----------- | ------- | --------------------------------- | -------------------------------- |
| Traffic (K) | Pages   | Path                              | 备注                             |
| 11330.6     | 0604584 | www.zoominfo.com                  |                                  |
| 10149.8     | 4744881 | www.zoominfo.com/ic               | company 的文件夹                 |
| 570.3       | 618458  | www.zoominfo.com/ic               | company employee 的文件夹        |
| 295.7       | 1071958 | www.zoominfo.com/ic               | 员工 profile 文件夹              |
| 39.4        | 29958   | www.zoominfo.com/companies-search | 各行各业各地的公司 directory     |
| 27.9        | 1480    | www.zoominfo.com/top-info         | Top List 系列各行各业各地的公司  |
| 6.6         | 38149   | www.zoominfo.com/people           | 同名同姓的人名列表页面           |
| 4.3         | 7847    | www.zoominfo.com/people-search    | 各行各岗位，各国家&州的人名 list |

1. 人员维度：A-Z，行业，职位，国家，州 https://www.zoominfo.com/people-search/https://www.zoominfo.com/people_directory/professional_profile/A-0-0
2. Browse directory: https://www.zoominfo.com/s/search
3. Company search: 行业，国家，州 https://www.zoominfo.com/companies-search/
4. Top List 系列: https://www.zoominfo.com/top-lists

From 阿彪师傅 @ Pollo.ai 分享配图

## 怎么落地呢？其实谷歌 SEO 有官方检测工具

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//8086160b-d8f0-44dd-abc6-e7553163d793/markdown_4/imgs/img_in_image_box_256_1005_674_1352.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A53Z%2F-1%2F%2Fb4bdab267b9feec053c8005e43aad5c323dd3d583e4592beebcb3beca4f834f7)

## SEO 基建 Checklist

信息架构 / 路由：URL 规范，状态码 200/301/404/410

- 抓取 / 索引：robots.txt, sitemap.xml, lastmod, canonical, hreflang, 参数 / 分页, Ping
- 结构化：Schema（FAQPage / HowTo / SoftwareApplication / Product），Rich Results 等
- 性能 / CWV: LCP<2.5s, CLS<0.1, INP<200ms, SSR/SSG, CDN, WebP/AVIF, 懒加载, 缓存
- On-Page SEO: Title, Description, H1/H2, 内链（上行/横向/下行）, 图片 alt
- 观测 / 流程：G5C，GA4，抓取 / 错误日志

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//2a17c44d-f6cd-4e93-a15a-ed971f9c0450/markdown_0/imgs/img_in_image_box_258_56_511_242.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A15Z%2F-1%2F%2F2891a6458a9d704b2a496e5cc18a475cc43c3331646c8206bfefecade1929f77)

#### Cursor 操作示意图

复制下方 SEO Optimization for One Page 的 Permpt，然后

- 替换输入主关键词

替换指定对应页面

```text
Act as a senior SEO engineer. Your task is to fully optimize the page {{PAGE_URL}} for the target keyword {{PRIMARY_KEYWORD}}.
Conduct a comprehensive audit and provide implementation across four SEO infrastructure layers:
1. Technical SEO
- Validate robots.txt, sitemap.xml segmentation (with lastmod), canonical tags, hreflang.
- Ensure correct status codes, redirect rules, pagination/parameter handling, canonical loop checks.
- Confirm inclusion in sitemap, crawlability, and verify crawl logs (Googlebot activity).
2. Core Web Vitals (Performance & Usability)
- Target: LCP < 2.5s, CLS < 0.1, INP < 200ms, TTFB < 800ms.
- Optimize images (WebP/AVIF, lazy load), preload fonts, inline critical CSS, defer non-critical JS, enable HTTP/3 and CDN caching.
3. On-Page SEO (Ranking Signals)
- Optimize title (45–60 chars), meta description (120–155 chars, keyword + CTA), single H1, structured H2/H3 hierarchy.
- Internal linking: 1 Hub, 2 Cluster, 3 Leaf with keyword-rich anchors.
- Add alt text, scannable paragraphs, freshness signals (last updated), enriched content blocks (steps, comparison, FAQ).
4. Structured Data (Schema)
- Add JSON-LD: SoftwareApplication (if tool), FAQPage/HowTo, BreadcrumbList, Article.
- Validate with Google Rich Results Test & GSC coverage.
Deliverables
- Provide precise code differs or implementation steps.
- Generate JSON-LD block with the correct injection point.
- Output SEO audit report in Markdown with: Current Issues, Fix Implementation, Expected Impact.
- Confirm page passes all 4 gates: Technical, CWV, On-Page, Schema.
Only propose SEO-safe, compliant improvements. Do not alter brand, pricing, or core design.
```

小结下，只要确定中期会做 SEO 渠道，就从第一天把基建搭好。它是“机器可理解 × 人类可转化”的交集权衡，是后续 pSEO 放量、国际化扩展、外链带动与增长飞轮的前置条件。

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//2a17c44d-f6cd-4e93-a15a-ed971f9c0450/markdown_0/imgs/img_in_image_box_258_1024_752_1272.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A15Z%2F-1%2F%2F8c0fc86b906b84ec53c985f3cf6c2f8f4ed8fe4343f3f27d4aafc14c88d784de)

本章节完毕，谢谢大家，欢迎随时讨论。

## 三、 SEO 实战篇：SEO 内容创作

### 3.2 章节：搜索意图 → 页面内容 & 页面类型匹配

❤️：章节内容，感谢 Joker 上次的分享，让我回声久久

搜索意图，就是用户在搜索框里敲下那串词（搜索关键词）背后真正想干嘛：ta到底想找什么、解决什么问题等等。

但在不单单这一关，除了—关是用户想干嘛，另一关是 Google 需要用什么内容形态来满足他

#### 所以把搜索意图理解为

- 搜索意图 = 用户想完成的任务
- 同时也是 Google 判断“该用什么页面类型来满足这个任务”

SEO 本质不是匹配关键词，而是匹配关键词对应的 用户任务 + Google 页面形态

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//2a17c44d-f6cd-4e93-a15a-ed971f9c0450/markdown_1/imgs/img_in_image_box_409_164_631_290.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A15Z%2F-1%2F%2F00da31f4dccd2f4b6bad23fc18181aa29d80a552e51ea3f57b7cefd5dc523453)

### a. 四大类搜索意图

要知道搜索意图到底有什么用？先了解一般将搜索意图分成四大类

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//2a17c44d-f6cd-4e93-a15a-ed971f9c0450/markdown_1/imgs/img_in_image_box_256_373_396_453.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A16Z%2F-1%2F%2F33d6061854019c90bace975ab19f4ea0b489f05e9cc8eec4824cbdc734391250)

- 信息意图（Informational）：用户在学知识、找信息做判断，给教程或详细文章

导航意图（Navigational）：用户想找特定的网站或品牌（如 canva login），应提供品牌登录页面

交易意图（Transactional）：用户想用工具或买东西，直接给工具或购买链接

- 商业意图（Commercial）：用户在做用工具或购买决策，给测评列表或对比

比如 al kissing generator 关键词，明显属于 交易意图（Transactional）。有什么用呢？好像也有点

通过词根，然后按搜索意图去挖掘对应的长尾关键词。Ahrefs 或 SEMRush 都提供这个筛选项

根据四大类搜索意图，能判断出对应的关键词优先级

比如现在零点击时代，少做 informational 类的文章

比如多做交易意图和商业意图的词：比如 ai music video generator、best ai music video generator

注意：一个核心关键词可能同时匹配多个搜索意图。比如 best ai music video generator，可能代表用户可能想用这个工具（交易意图），也可能代表用户在线测评对比，然后再选择使用哪个工具（商业意图），如下图

### 商业意图

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//2a17c44d-f6cd-4e93-a15a-ed971f9c0450/markdown_1/imgs/img_in_image_box_255_719_778_930.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A16Z%2F-1%2F%2F40c6af3f4b6f3ce85dd3adc2c8ecadc9bd87a6f318dd38621ef066f374002ac0)

第 3 和 7 交易意图，其他还是商业意图

BEST AI MUSIC VIDEO GENERATOR

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//2a17c44d-f6cd-4e93-a15a-ed971f9c0450/markdown_1/imgs/img_in_image_box_371_995_665_1133.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A16Z%2F-1%2F%2F52e164f36a4d4c00df45e9417d5554dc6defb61ad229d20632d98d67b45994d3)

### b. 搜索意图的作用

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//2a17c44d-f6cd-4e93-a15a-ed971f9c0450/markdown_1/imgs/img_in_image_box_370_1205_666_1374.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A16Z%2F-1%2F%2Fff68f1d36fa8ae6cbecca234d128da2e856f539ca7d59cf0a2fd52b30745f994)

我感觉还是有点宽泛，那搜索意图到底有什么用？我先下个结论：

搜索意图，第一能有效地帮助大家判断关键词先做哪个后做哪个

Google 眼里的用户的搜索意图：决定你用什么页面样式来写

判断在谷歌眼里，用户喜欢的页面形式。什么页面形式多就做什么页面

不同意图 = 必须不同页面，不可混做

用户角度的搜索意图：决定你写什么

做出与之用户搜索相符的内容，基于行业产品和客群知识，去创作更多信息增量

常见的内容 3C 要素：内容类型（博客 or 落地页等等）、内容格式（表格、感言、列表等模块）、内容角度

其中也得关注 Google 眼里的用户喜欢的内容角度，你也得有。即排名前面的页面在用什么内容共同点说服用户点击

比如上图 best ai music video generator，有 4 篇文章测评 / 榜单 形式、1 个 Reddit 论坛 UGC 讨论形式和 2 个工具落地页形式。因此我就会选择做文章页面，里面内容角度我肯定会提到：Why 模块、Research 井罗列出 Top 工具的介绍、截图和优劣势等等

### c. 小结

SEO 不是一词一页，而是一种搜索意图—页；页面的使命是精准满足这一种需求。

如果把 SEO 当成内容产品来做，搜索意图就是这款产品的需求文档。

它先决定你要做哪种产品形态：比如工具页 / 榜单页 / UGC 论坛

然后它再指导你这页该交付什么内容组件：比如步骤要不要、对比表要不要、评测方法和数据样本要不要FAQ要不要.

同一个关键词，意图不同，就是不同产品，不能混在一页里硬写。

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//2a17c44d-f6cd-4e93-a15a-ed971f9c0450/markdown_2/imgs/img_in_image_box_395_421_640_580.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A17Z%2F-1%2F%2Ff839225ce3f943807c08a56568a1347a9bb68901db82975a91505adadff07211)

所以：

- 阶段性，做好某类词对应的页面形式模版（很容易被忽视），对应的页型选好和结构定好

持续：在对应的关键词列表后面可以补充搜索意图、Google SERP 形态、必须内容模块三个字段

持续：按关键词优先级，根据搜索意图作用，创作好对应的内容。但好坏的内容有着明显的分水岭

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//2a17c44d-f6cd-4e93-a15a-ed971f9c0450/markdown_2/imgs/img_in_image_box_379_693_663_840.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A17Z%2F-1%2F%2F0c159637ff3b3773580c929508e799c293921898b91a4e43783741044529d07f)

SEO 赢的不是谁更会写，而是谁更懂用户要完成什么任务，以及 Google 准备让哪种页面去完成它。

本章节完毕，谢谢大家，欢迎随时讨论。

（酝酿中）关键词挖掘：专为 AI Tool Website 的方法

（酝酿中）搜索意图 → 页面类型匹配

（酝酿中）工具页 SEO 内容规范

## 四、 SEO 实战篇：外链建设

### 4.x 章节：SEO 外链必知必会

本章节讲讲如何判断什么是“好外链”？AI站阶段性如何做好外链？

#### a. 什么是外链？

什么是外链呢？外链（Backlink）=外部网站指向你页面的链接。一般站点自然增长的外链中，首页对应的外链数量占比最大

再聊聊外链大家都知道的作用：

1. 排名提升：帮助网站在 Google 搜索中，核心关键词页面的排名提升
2. 引荐流量（Referral Traffic）：优质外链能带来精准用户访问，为站点导入真实潜在客户
3. 发现与收录：外链给谷歌爬虫“修路”，新站/新页面有几条靠道外链，通常比只交 sitemap 更快被收录。

但要注意：外链要自然增长，才是搜索引擎认可的。极端案例：如果一个新站一天突然新增成千上万条“非自然&高质量外链”，不仅不会提升，反而极可能被判定为作弊，面临整站被Kill的风险

### b. 如何判断什么是“好外链”？

可以把网站比作一本书。比如你写了一本《AI电商创业》指南，里面有几个章节：

章节 A：《AI 电商创意灵感》= 一个核心排名页面

章节 B：《AI 电商创业团队搭建》= 另一个核心排名页面

这时马云在自己的博客上推荐了你的书，并附上了这本书的几个核心章节链接——这就是一个顶级高质量外链。

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//2a17c44d-f6cd-4e93-a15a-ed971f9c0450/markdown_3/imgs/img_in_image_box_337_220_675_368.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A19Z%2F-1%2F%2F9bf63249fd92fcde09c40d1b6cedea986667485c0b2a6cf0c9c39d26d8767b13)

高质量外链有 3 个核心标准：

相关性：推荐站点的主题与你一致（马云和电商的关系）

权威性：推荐站点本书在行业内有影响力（代表马云在电商行业权重高）

- 流量精准度：他的读者恰好是你的潜在客户（能带来转化）

如果标准点要排序话，我认为：精准流量 > 权威度 = 相关性。因为真正能带来点击与转化的外链，才是最有价值的外链。

案例: heygen 的一个 Best Backlink

流量精准度：流量大、这个报告被精准所需业内人疯传

Heygen 的 a16z 外接案例

权威性：a16z站点是AI工具方向的权威和具备影响力

- 相关性：讲的 AI Avatar，heygen 亮点功能就是 AI 数字人

同样，外链不是越多越好，单一类型的外链越多，不如外链类型的丰富完整越强

本章节完毕，谢谢大家，欢迎随时讨论。

### 4.x 章节：外链-目录站/导航站/评测站

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//2a17c44d-f6cd-4e93-a15a-ed971f9c0450/markdown_3/imgs/img_in_image_box_413_894_622_1103.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A19Z%2F-1%2F%2Fe1412dafe370336c083985dd87573e9370205d872e0df19afeb8a96b10a835a6)

在做 AI 工具站出海的圈子里，创始人做新品牌网站出来后，就会讨论：“该不该打榜 ProductHunt？该不该付费提交 AI 导航站 TAAFT，有用吗？怎么提交？”等等。比如最大的 ai tool directory 导航站 TAAFT，提交一次最高 350 刀套餐。那本章节给大家分享下目录站 / 导航站 / 评测站等如何提交。

#### a. 识别 AI 导航站的双重价值

AI 导航站的价值有两个：一方面是带来外链 referral 推荐流量，另一方面是为网站首页和全站带来 SEO 外链权重。尤其新站的话，提升其对谷歌搜索引擎的可见性与收录速度。展开讲：

DR 50+ 的导航站外链，也算高质量外链类型之一，能够有效的传递权重。比如 taaft 对应的 ai-xxx-generator 列表页面，你排在第一，而且是 Dofollow 外链。尤其对于新站来说，提高页面抓取 & 收录率，还有 PH monthly #1 是一个新站的背书，提高搜索引擎的信任度

另外这些精选的位置，也是目标用户群的直接关注的页面，带来的外链推荐流量也是精准的用户

#### b. AI 导航站外链的提交策略

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//2a17c44d-f6cd-4e93-a15a-ed971f9c0450/markdown_3/imgs/img_in_image_box_256_1370_495_1446.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A19Z%2F-1%2F%2F951e06af5da29b3a984af22f0a6cbf0a051b2d00a6f3bdc0511159f5859224a4)

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//2a17c44d-f6cd-4e93-a15a-ed971f9c0450/markdown_3/imgs/img_in_image_box_539_1372_776_1442.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A19Z%2F-1%2F%2F8f17c6fda4864d5ce5ff2135325095962cd1810aece790d0d368419c13dd6c29)

如上图，TAAFT 网站的做法为例，它同样将链接指向首页，但在提交给 TAAFT 和另一个不同的 AI 导航站时，可以使用了不同的标题及对应内容。为啥这么做呢？先来个大白话

“就是把你的产品，放在不同”人流很大的商场”里，

每个商场的招牌与个一样的笑点，

吸引不同想法的人，

但最后全都把人带回你自己的店。

整体提交策略，大家可以参考下面 3 个核心步骤：

## 1、 遵循“二八原则”，聚焦头部站点

新站优先提交 Top 20 的导航站和目录站就够了。判断标准：

- 第一标准：Similarweb 的月访问量 > 10 万
- 其次标准：Ahrefs 的 Domain Authority (DA) > 50

与其提交 100 个低质量导航站，不如把 20 个头部站点的物料做到极致。因为这样做，一方面能减轻工作量，另一方面，可以把提交给头部站点的物料准备得更好、更完整和丰富，从而获得更佳效果。

## 2、 精细化准备提交物料（标题、描述、配图）

标题：固定品牌词 + 灵活主关键词

描述文案：融入 1-2 个核心主关键词

上面比如做一个音乐生成的站，其中2.0版本发布的Rap生成功能很强！那使用了不同的标题及对应内容话，这样做能有效地进行“寄生SEO”，会带来不错的流量与排名。尤其是对于新站，首要的是提升可见性。当你的新站还没有任何外链时，提交对应核心主关键词可以更长尾一点，因为这样竞争相对小一点，更容易排名。

具体到细节，我们提交的 Title 中，品牌词一般是固定的。但是，品牌词或产品、首页对应的主关键词可以进行微调。如果主关键词微调了，那对应的描述也需要相应微调。因此，在物料准备阶段，围绕一句话价值主张，对应的 Title、文本描述乃至配图都可以进行调整。

这里提一下：新增的页面收录不单单是自己在 GSC（Google Search Console）后台或通过 API 提交。这里提交的 AI 导航站是 Top 的，它每天都会被谷歌搜索引擎抓取。爬虫会顺着导航站（它每小时、每天都在抓取）抓取到你的新站首页和其他内链页面。

## 3、 监控付费提交与外链效果

头部站点付费提交可获得更快审核和更好展示位置。同时，你也需要监控每个头部导航站的提交情况。因为提交收录毕竟需要收费，TAAFT 也支持 CPC 计价，你就需要全链路地监控从该站点带来的外链流量。

最后大家关注是 SEO 文案 + 视频/图片等物料。好的宣传视频、封面图以及文案，都可能被编辑（类似于 TAAFT 的小编）看到并精选。提交后，如果你发现在某个 AI 导航站被推荐了，或者拿到了比较好的排名，你可以在自己的官网中反向露出这个推荐模块。对于 SEO 来说，这是一个很好的“信任见证”。

本章节完毕，谢谢大家，欢迎随时讨论。

## 五、 其他 SEO 高级实践篇

### 5.x 章节：pSEO（程序化SEO）的双刃剑

更多资料：

20251217-程序化 SEO 是把双刃剑-子木.pdf - 对应讲稿：

<https://mp.weixin.qq.com/s/1wKZPEHptDZpagDIuF_eFg>

Zoominfo 等站规划，彪哥 @Pollo.ai - 2023

### a. 程序化 SEO 是什么

首先一定不是内容农场，这些都是投机 & 不长期。

pSEO（程序化 SEO）= 模板（可抽取的页面结构，也可 AI 模板）× 结构化内容数据（可比较、可更新）× 自动化（批量 & 定时生成 + 自动提交索引）

目的是规模化产出“对搜索用户有用”&对搜索引擎友好的页面，而不是换词、换城市的空壳。比如论坛“精华帖集合页”就是早期pSEO的雏形-把分散信息结构化、聚合化、可持续更新。

### b. 失败 = 经验

AI 时代下，造成很多误用了 AI 多模态能力，然后批量生成页面跟谷歌 SEO 对抗，尝到了一定甜头，但后面被 kill 了

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//2a17c44d-f6cd-4e93-a15a-ed971f9c0450/markdown_4/imgs/img_in_image_box_259_1218_423_1289.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A20Z%2F-1%2F%2F18bfe975ffd16ec546fb4a4ca5d153a346e4e6d0adc8d04ec92470bb163619d6)

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//2a17c44d-f6cd-4e93-a15a-ed971f9c0450/markdown_4/imgs/img_in_image_box_429_1217_573_1319.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A20Z%2F-1%2F%2F45c3511bb4e5cc6748eb5dc469c04da545df3c7df284000de6e45a3b05193ca7)

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//2a17c44d-f6cd-4e93-a15a-ed971f9c0450/markdown_4/imgs/img_in_image_box_583_1217_779_1324.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A21Z%2F-1%2F%2Fe08005edb0ba44d55a4d929ee372ba61f546e152247144bb01b4a696a6333c0d)

我的练手站

上面的几个站大家可以看出：动辄上千万曝光却只有几万点击、CTR极低，基本能判定是海量模板也在堆量，但本质不在“是否用AI”

短短几个月能把体量拉满，几乎只可能是AI批量生成。问题不止在量，而在内容维度缺失：页面同质、信息增量低、无法给出可抽取的结论/表格/步骤/证据，用户扫一眼就跳过。

谷歌算法更新近期也很快，就是在打击规模化低质量内容，并把权重转向信息增量、原创证据、可用性与新鲜度的网站。

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//2a17c44d-f6cd-4e93-a15a-ed971f9c0450/markdown_4/imgs/img_in_image_box_376_1499_661_1543.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A21Z%2F-1%2F%2Fd09cd4885384620521c3ac9ac70937f38525ae425b587e8baf116b4d3039cecc)

## 谷歌 SEO 算法更新路径

### c. 程序化 SEO 的成功实践

pSEO 是用 AI 能力 + 工程能力 把「可抽取的信息增量」规模化。

其关键：信息的增量（内容如何生成）+ 工程化（字段、模板、更新策略）+ 科学验证的流程化（样本、小批量、监控）

## 如何做？维度 → 字段级别的公式拆解

功能 × 场景 × 行业 × 语言 × 版本 → 无限长尾组合

→ 可组合的维度先抽成字段（Function / Use-case 等）

→ 用模板装配（对比表 / 步骤 / FAQ / Schema 等）

→ 用自动化发布与维护（定时生成、lastmod 更新、Google Search Console API 提交、质量巡检等）

![Image](https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-15//5cd81b9c-d6f8-489b-8445-8c310d14897e/markdown_0/imgs/img_in_chart_box_383_348_675_553.jpg?authorization=bce-auth-v1%2FALTAKzReLNvew3ySINYJ0fuAMN%2F2026-04-15T06%3A22%3A09Z%2F-1%2F%2Fec1433ebd7c4417f3637d15dec0f5a5bce33df0d70df41c658b72233e5c92cc2)

## 举一些成功的例子：

pSEO 现阶段用 AI + 工程把“信息增量”的页面规模化，做对用户有用且对搜索友好的页面，而不是换词堆页。

先打磨 10 个能被选进答案的硬内容页面，满足有效收录率后。然后看看其内容拆分模块，按「功能 × 场景 × 行业 × 语言 × 版本」字段化组合滚动扩量，同时避商标词等。
