---
layout: default
title: "Horizon 每日速递 - 2026-11-22"
date: 2026-11-22
lang: zh
updated: "15:00"
---

<h2 class="batch-heading">🕐 15:00 雷达更新</h2>

> 从 4 条内容中筛选出 1 条重要资讯。

---

**科技博客**
1. [300 美元以内的 18 自由度腱驱动机械手](#b1500-item-tech-blog-1) ⭐️ 5.0/10

---

## 科技博客

<a id="b1500-item-tech-blog-1"></a>
### [300 美元以内的 18 自由度腱驱动机械手](https://hackaday.com/2026/11/21/building-a-robotic-hand-on-a-budget/) ⭐️ 5.0/10

rss · Hackaday · 11月22日 06:00

**「背景」** 灵巧操作是机器人领域长期未解的难题，具备精细运动能力的硬件往往价格高昂。Mahdi 用不到 300 美元的零件成本构建了一只 18 自由度的腱驱动机械手，试图在极低预算下逼近这一目标。

**「方案」** 该设计本质上是一个完整的前臂：3D 打印骨架，伺服电机集中布置在前臂，通过肌腱驱动各关节。几项关键工程决策值得注意：用细钢丝绳替代合成纤维缆线，通过压接而非打结来固定肌腱，消除了小尺寸下打结的可靠性问题；每根肌腱穿入 PTFE 管以降低摩擦；肌腱路径经过关节旋转中心，使关节弯曲时路径长度保持不变。每根手指可侧向运动并独立屈伸两个关节。前臂底座可旋转，但伺服电机电流过大，小滑环无法承受，大滑环又超出预算；作者改用扁平排线盘绕方案，配合打印的线缆导向件防止弯折，既比滑环便宜得多，也更紧凑。文章指出，此前已有多个项目采用类似的腱驱动思路，更逼真的版本会用人工肌肉替代伺服电机，甚至 3D 打印肌腱和韧带，但本文未提供定量性能数据、耐久性测试或深入的取舍分析。

**「启示」** 该项目证明在极低预算下，通过压接、PTFE 管、旋转中心路由和排线替代滑环等巧妙的机械约束，可以构建出结构复杂的腱驱动系统，为低成本灵巧机构设计提供了可迁移的工程思路，但缺乏量化验证使其结论仍停留在概念验证层面。

**标签**: `#robotics`, `#mechanism-design`, `#low-cost-hardware`, `#tendon-actuation`, `#maker-project`

---

---

<h2 class="batch-heading">🕐 07:00 雷达更新</h2>

> 从 11 条内容中筛选出 2 条重要资讯。

---

**科技新闻**
1. [Claude 与 Alpöge 在 Lean 中完成与黎曼猜想相关的形式化证明](#b0700-item-tech-news-1) ⭐️ 8.0/10

**科技博客**
1. [大型代码库中避免致命失误比追求精巧更重要](#b0700-item-tech-blog-1) ⭐️ 5.0/10

---

## 科技新闻

<a id="b0700-item-tech-news-1"></a>
### [Claude 与 Alpöge 在 Lean 中完成与黎曼猜想相关的形式化证明](https://leanprover-community.github.io/blog/posts/riemann-hypothesis/) ⭐️ 8.0/10

Lean 证明器社区博客发布了一项由 Claude AI 与数学家 Levent Alpöge 合作完成的形式化工作，据称涉及广义黎曼猜想（GRH）或黎曼猜想（RH）的证明。该过程中 Claude 被用于在 Lean 中形式化大量现代数学内容，Alpöge 作为人类专家引导方向。然而，该博客未提供完整证明文本，社区对这一结果是否构成经过独立验证的数学证明存在显著分歧：此前曾有一个伪造的 Collatz 猜想反例通过某款独立检查器，引发对证明检查器独立性的质疑；但支持者指出目前已有多种不同语言、不同实现且各自具备一致性证明的检查器（如 con-leche 和 con-ron），利用漏洞通过所有检查器的可能性已极低。无论数学结论本身是否最终成立，Claude 在 Lean 中形式化大规模现代数学这一工程本身已具有独立意义。

hackernews · g-b-r · 11月21日 14:36 · [社区讨论](https://news.ycombinator.com/item?id=50589618)

**「背景」** 黎曼猜想是数论中关于素数分布的核心未解决问题，自 1859 年提出以来已有 167 年历史。2026 年 11 月 20 日，Anthropic 数学家 Levent Alpöge 宣布他与 Claude AI 共同找到了该猜想（或其广义形式 GRH）的证明，并发布了用 Lean 证明助手语言编写的形式化代码供数学界验证。

**「对形式化验证社区的影响」** 对形式化验证社区而言，此次事件迫使人们重新审视证明检查器的独立性：社区讨论中指出，此前一个伪造的 Collatz 猜想反例曾通过其中一个独立检查器，这引发了对多个检查器是否真正独立的质疑。对数学家而言，该结果是否构成 GRH 或 RH 的完整证明仍有待确认，但 Claude 在 Lean 中形式化大量现代数学这一过程本身，已对 AI 辅助形式化数学的可行性边界产生了具体影响。

**「社区讨论」** 讨论的核心分歧在于证明检查器的独立性是否足以保证结论可靠。有评论者指出此前一个伪造的 Collatz 猜想反例曾通过某款独立检查器，质疑所谓「独立」检查器之间的实际独立性；另一评论者反驳称，当前已有多种不同实现且各自具备一致性证明的检查器，要同时绕过所有内核的一致性证明和 RH 证明本身，概率已微乎其微。此外，多位评论者强调 Levent Alpöge 在引导 Claude 完成这一过程中的关键作用，认为不应将功劳完全归于 AI 系统。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.clarin.com/us-news/who-is-levent-alpoge-the-anthropic-mathematician-who-claims-solved-the-riemann-hypothesis-with-claude_0_2WdGvYKBVM.html">Who is Levent Alpöge ? The Anthropic mathematician who claims he...</a></li>
<li><a href="https://www.theguardian.com/technology/2026/nov/21/anthropic-riemann-hypothesis-solved-claude-ai">Anthropic mathematician claims he used Claude to... | The Guardian</a></li>

</ul>
</details>

**标签**: `#formal-verification`, `#AI-mathematics`, `#Lean-prover`, `#theorem-proving`, `#AI-assisted-research`

---

## 科技博客

<a id="b0700-item-tech-blog-1"></a>
### [大型代码库中避免致命失误比追求精巧更重要](https://seangoedecke.com/to-code-well-avoid-blunders/) ⭐️ 5.0/10

rss · Sean Goedecke · 11月22日 00:00

**「背景」** 许多工程师将编程类比为需要发现精妙战术组合的棋类运动，但 Sean Goedecke 指出，在大型商业代码库中，编程更接近一种「不犯错即获胜」的博弈：一次失误就能将优雅的代码库拖入泥潭，这与篮球中落后 99 分仍可能翻盘的情形截然不同。

**「方案」** 作者将致命失误归纳为几类典型模式：引入并行系统完成同一任务、为关键数据建立第二真相源、将安全的同步操作改为脆弱的异步操作、增加新的微妙故障点、以及复杂化关键接口。其核心论点是：不一致性会破坏团队对代码的默认信任，迫使工程师在每次修改时都去排查意外；而不必要的需求则具有双重危险性——它们具有「粘性」（实现者拥有判断其必要性的上下文，后来者只能假设其必要），且会与其他特性产生组合爆炸式的交互，这正是大型代码库难以维护的根源。作者建议开发者在动手前将任务裁剪到最小需求集，并找到最自然地融入现有代码库的位置；当脑海中浮现「我可以用某个巧妙模式实现」的念头时，这恰恰是注意力偏离主线的危险信号。他同时指出，当前 AI 编码代理在一致性方面与人类水平相当，但在避免不必要需求方面远逊于人类。

**「启示」** 在大型团队协作中，编程的核心能力不是发现新抽象，而是对细节的专注和对一致性的守护——避免失误本身就是最大的技术贡献，而「聪明」有时反而是劣势。

**标签**: `#software engineering practice`, `#codebase maintainability`, `#simplicity and consistency`, `#large team engineering`, `#engineering philosophy`

---
