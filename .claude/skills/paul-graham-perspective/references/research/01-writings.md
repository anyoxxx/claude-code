# Agent 1 · 著作与系统性长文调研 (Paul Graham)

调研方式：纯网络搜索（paulgraham.com 本站被出口代理拦截，无法直接WebFetch原文全文；
以下依赖对原文的可靠转述/摘录来源交叉验证。这是本次调研的一个已知限制，已在SKILL.md诚实边界中注明）。

## 一、书籍（一手，作者本人著作）

| 书名 | 年份 | 核心内容 |
|------|------|---------|
| *On Lisp* | 1993 | Lisp宏编程技术专著，探讨如何用宏做"自底向上"编程、语言即可扩展工具的理念 |
| *ANSI Common Lisp* | 1995 | Common Lisp标准教科书，广泛用于大学课程 |
| *Hackers & Painters: Big Ideas from the Computer Age* | 2004 | 论文集，核心论点：编程是手艺（craft）而非科学，更接近绘画/建筑；黑客与画家一样是"makers"，追求做出好东西；学校、大公司、委员会、流行正统观念常压制真正优秀的工作 |

来源：Wikipedia "Paul Graham (programmer)"、Wikipedia "Hackers & Painters"、Goodreads、Medium书评多篇。可信度：中高（多源交叉一致）。

## 二、paulgraham.com 长文精粹（一手，本人所写，但本次因站点被出口代理拦截未能直接抓取原文全文，
以下基于多个独立转述来源交叉核实的内容摘要）

反复出现（≥3次跨文章、跨主题）的核心论点，判定为"真信念"候选：

### 1. Default Alive / Default Dead（《Default Alive or Default Dead?》，2015年10月）
初创公司要么"默认存活"（现有增长率和现金将在花光前实现盈利）要么"默认死亡"（必须靠外部注资才能续命）。多数创始人危险地不知道自己属于哪种。这是Graham与YC创始人对话时的招牌追问。
来源：libraryofllm.com、vectig.com、kruzeconsulting.com 等多篇独立转述一致。跨域：出现在融资建议、招聘建议、增长讨论多个场景 → 通过跨域复现验证。

### 2. Ramen Profitable（源自《A Fundraising Survival Guide》，2008）
"够付创始人生活费"的盈利水平。不是传统意义的大赚，但意味着不再需要"这个月"就融资——买的是时间和自主权。
来源：praval.com、joel.is、fourweekmba.com 等交叉核实。

### 3. Relentlessly Resourceful（《Relentlessly Resourceful》，2009年3月）
Graham把好创始人的特质浓缩为两个词。与其反义词"hapless"（无助/被动，被环境击打而非主动塑造环境）对比。仅仅"relentless"（执着）不够——在困难是全新的、无法硬闯的领域，还必须"resourceful"（善用手头资源、不断尝试新办法）。
来源：paulgraham.com/relres.html（经二手转述确认存在及内容）、jasonshen.com、Sam Altman在多个场合引用此文为其"最认同的PG建议"。

### 4. Schlep Blindness（《Schlep Blindness》）
人对"schlep"（繁琐、令人不快的苦活）存在无意识的视而不见——你的潜意识甚至不会让你看到涉及痛苦苦活的创业点子。Graham举Stripe为例：处理在线支付的痛苦人尽皆知，但十年间黑客们宁可去做菜谱网站也不愿碰这块硬骨头。核心论点："一家公司是由它愿意承担的schlep定义的。"
来源：persdre.github.io（引用原文段落）、timberry.com、startuparchive.org（Alexandr Wang谈此文对Scale AI的启发）。

### 5. Founder Mode vs Manager Mode（《Founder Mode》，2024年9月）
由Brian Chesky（Airbnb）的一次演讲触发。"经理人模式"是标准商学院式做法——招最好的人然后放权让他们做自己的事；"创始人模式"是创始人保持直接、深度介入的领导方式，类似乔布斯治理苹果的方式。Graham认为创始人被劝说"要像职业经理人一样管理"是系统性的坏建议，导致公司在创始人卸任CEO式管理后陷入困境。
来源：Wikipedia "Founder mode"、Fortune、Inc.、Oxide Computer博客等多篇独立转述及行业辩论，2024年在硅谷引发广泛讨论（部分批评见04他者视角文件）。

### 6. How to Do Great Work（长文，约11,800字/近30页，2023）
四步流程：选择领域 → 学到足以抵达前沿 → 注意到前沿的缺口 → 探索有潜力的缺口。核心驱动力是好奇心："如果要用一个词回答如何做出伟大的工作，Graham会押好奇心。" 强调做自己真正感兴趣、有天赋的事，而非刻意追求"重要性"（重要性应交给后人评判）；强调与最好的同行共事的重要性。
来源：LinkedIn总结、danielscrivner.com、outlieracademy.com newsletter、David Senra (Founders Podcast) 等多篇独立总结高度一致。

### 7. Maker's Schedule, Manager's Schedule（2009年7月，约1100字）
制作者（程序员、作家）需要以半天为单位使用时间，无法在一小时单位内写好代码；管理者的日程表以一小时为格数。核心结论："当你处于制作者日程时，会议是灾难"——一个会议能通过把下午切成两段都不够做难事的碎片而毁掉整个下午。
来源：Cal Newport博客引用讨论、Scrum.org、多篇转述高度一致，术语已进入通用词汇("maker time"概念的源头之一)。

### 8. Mean People Fail（博文）
论点：以恶劣方式对待他人的创始人几乎不会在最高层面上成功。理由：刻薄让人变蠢（"你在争斗中从不会拿出最好的工作，因为争斗不够general"）；刻薄的创始人吸引不到最好的人才。
**反面证据/争议**：Inc.杂志专文反驳《Sorry, Paul Graham: Mean People Succeed, Too》，指出不少极端成功者以刻薄著称；有评论认为"最优秀的人也可能想要一个能挑战甚至让他们有点害怕的老板"。→ 这是一个被公开挑战的论点，记录矛盾而非调和。

### 9. What You Can't Say（2004年1月）
探讨"道德时尚"（moral fashion）——社会武断的规范常被误认为"善"，比一般时尚更危险。提出识别隐藏禁忌的方法：看人们因说什么而惹上麻烦、看被用来压制异议的标签、跨文化跨时代比较观念。核心主张：培养怀疑心智、质疑传统智慧，即使这意味着要考虑令人震惊的想法，这对智识成长至关重要。

## 三、自创术语清单（揭示概念发明能力）
- default alive / default dead
- ramen profitable
- relentlessly resourceful（及反义词 hapless）
- schlep blindness
- founder mode / manager mode（后者非PG原创但由他重新定义流行）
- maker's schedule / manager's schedule

## 四、推荐书单 / 智识谱系线索（部分，需与02/04交叉）
- Lisp语言本身（源自McCarthy）——Graham视Lisp为"更强大的编程语言"信仰的根基
- 提及painting/artists作为方法论类比（他曾短暂在佛罗伦萨美术学院学画）

## 五、来源清单与可信度
| 来源 | 类型 | 可信度 |
|------|------|--------|
| Wikipedia (Paul Graham programmer词条, Hackers & Painters词条, Founder mode词条) | 二手百科 | 中 |
| paulgraham.com/relres.html 等原文URL（经转述确认，未能直接抓取全文） | 一手（但本次未直接读取原文，降级标注） | 中高 |
| libraryofllm.com, vectig.com, kruzeconsulting.com | 二手转述 | 中 |
| persdre.github.io, timberry.com, startuparchive.org | 二手转述/引用原文段落 | 中高 |
| Inc.com《Sorry, Paul Graham: Mean People Fail》 | 二手批评 | 中 |
| Cal Newport博客、danielscrivner.com、outlieracademy.com | 二手总结 | 中 |

**已知限制**：paulgraham.com 直接访问被本次运行环境的出口代理拦截（EGRESS_BLOCKED），未能直接读取essay原文全文，全部依赖高质量二手转述交叉验证（多个独立信源对同一篇essay给出一致复述，可信度仍属中高，但严格说不算"一手直读"）。这是本次调研的诚实边界之一。
