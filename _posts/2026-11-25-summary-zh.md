---
layout: default
title: "Horizon 每日速递 - 2026-11-25"
date: 2026-11-25
lang: zh
updated: "09:00"
---

<h2 class="batch-heading">🕐 09:00 雷达更新</h2>

> 从 7 条内容中筛选出 1 条重要资讯。

---

**科技博客**
1. [十二个月内 LLM 能力的三个拐点](#b0900-item-tech-blog-1) ⭐️ 7.0/10

---

## 科技博客

<a id="b0900-item-tech-blog-1"></a>
### [十二个月内 LLM 能力的三个拐点](https://simonwillison.net/2026/Nov/24/llm-inflection-points/) ⭐️ 7.0/10

rss · Simon Willison · 11月24日 23:02

**「背景」** Simon Willison 在 2026 年 AI Engineer Code Summit 的演讲中提出，过去十二个月 LLM 与编码代理经历了三个显著能力拐点，并以此框架重新审视前沿模型的发展轨迹。

**「方案」** 第一个拐点在 2025 年 11 月：Claude Opus 4.5 与 GPT-5.1 系列使编码代理首次成为可靠的日常开发工具，作者不再需要频繁纠正输出。第二个拐点在 2026 年 6-7 月：Claude Fable 5 的发布引入了作者所称的「Fable 类模型」，其核心定义是——给定一个目标和必要工具，模型能以蛮力方式解决问题。作者举了两个实例：Fable 5 自主搭建 pyobjc 截图机制与 CORS 本地服务器来修复 Safari 显示 bug；Opus 5.5 与 Fable 5.2 通过五个 WebAudio 麦克风将神秘蜂鸣声源定位到约 40 厘米精度。第三个拐点在 9-10 月：前沿模型在 3D 建模与「理解趣味」方面出现质变，Opus 5.5 经 12 小时自主测试与平衡调整，将一款 RTS 游戏从无聊变为引人入胜，这是作者首次遇到似乎能理解「好玩」的模型。作者目前仍在判断 Fable 5.2 是否构成第四个拐点，其关键特征似乎是「只要你能想象并清晰描述一段软件，Fable 就能构建它」。整篇文章以第一手体验为主，未深入分析驱动这些跃迁的训练或架构机制。

**「启示」** 作者认为软件开发在过去一年已发生不可逆转的变革，前沿模型正从辅助工具演变为能自主定义问题、调用工具、迭代验证的通用问题解决者，而「趣味」与「审美」这类曾被视为人类专属的能力正被模型逐步习得。

**标签**: `#LLM capability assessment`, `#coding agents`, `#Fable class models`, `#AI engineering practice`, `#game design with LLMs`

---

---

<h2 class="batch-heading">🕐 07:00 雷达更新</h2>

> 从 24 条内容中筛选出 6 条重要资讯。

---

**科技新闻**
1. [微软因历史性故障宣布「Code Red」，内部备忘录显示与大规模裁员相关](#b0700-item-tech-news-1) ⭐️ 7.0/10
2. [Check Point 安全管理服务器遭活跃入侵活动利用 PRNG 漏洞](#b0700-item-tech-news-2) ⭐️ 7.0/10
3. [vCenter vmdir 曝 9.8 分鉴权绕过漏洞，已被零日利用](#b0700-item-tech-news-3) ⭐️ 7.0/10

**科技博客**
1. [从单个 USB-C 端口拆分 USB 3 与 USB 2 信号](#b0700-item-tech-blog-1) ⭐️ 6.0/10
2. [Cloudflare 基础设施透明度不足：TLS、IPv6 与通知缺陷](#b0700-item-tech-blog-2) ⭐️ 5.0/10
3. [爱好者级 3D 扫描技术初探：摄影测量与结构光对比](#b0700-item-tech-blog-3) ⭐️ 5.0/10

---

## 科技新闻

<a id="b0700-item-tech-news-1"></a>
### [微软因历史性故障宣布「Code Red」，内部备忘录显示与大规模裁员相关](https://www.reuters.com/business/microsoft-declares-code-red-after-historic-outage-internal-memos-show-2026-11-24/) ⭐️ 7.0/10

据路透社报道，微软在经历一次历史性服务中断后，内部宣布进入「Code Red」最高紧急状态。内部备忘录显示，此次故障与大规模人员缩减有关——公司裁撤或提供买断方案的对象约占 2022 年员工规模的 45%，目前仍有超过 25% 的在职员工正在决定是否接受买断。报道指出，在业务承诺未做实质性削减的情况下，如此快速的人员收缩可能削弱了基础设施可靠性与工程实践。

hackernews · thm · 11月24日 17:07 · [社区讨论](https://news.ycombinator.com/item?id=50631157)

**「背景」** 2026 年 11 月中旬，微软经历了一次持续约 24 小时的历史性全球服务中断，影响数百万用户，公司称原因为「与网络攻击或 AI/智能体无关的技术问题」（tool-1-1）。据路透社查阅的内部备忘录，微软随后启动了「Code Red」级别的内部危机响应机制，旨在全面改革其重大故障的预防与应对流程（tool-1-2）。此次事件发生之际，微软正经历大规模人员缩减，据社区分析，约 45% 的 2022 年时期员工已被裁或正在接受买断方案，而公司未对相应业务承诺做出实质性削减。

**「对依赖 Microsoft 365 的组织的影响」** 2026 年 11 月 12 日至 14 日的全球性故障导致 Outlook、Teams、Copilot 等 Microsoft 365 服务中断，波及全球公共和私营机构，ChatGPT 和 Claude 中的 Microsoft 365 连接器也受到影响。对于高度依赖 Microsoft 365 的企业和开发者而言，此次事件凸显了单一供应商依赖的风险，建议组织评估灾备方案并确认其变更发布流程是否包含渐进式灰度发布和特性开关等机制，以降低类似故障的连锁影响。

**「社区讨论」** Hacker News 评论中，多位读者将故障归因于裁员对工程能力的冲击：有人指出微软可能缺乏渐进式发布、功能开关等常规实践；有人建议引入 Netflix 式混沌工程或数字孪生建模来提升基础设施韧性。也有评论者提醒，将故障简单归咎于裁员过于草率，但「如此快速收缩而不损失什么」本身就不合常理。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://nypost.com/2026/11/13/business/microsoft-says-service-is-returning-to-normal-ai-not-to-blame-for-historic-outage/">Microsoft says service is returning to normal, AI not to blame for...</a></li>
<li><a href="https://www.youtube.com/watch?v=DYJL2q1hXrQ">&#x27; Code Red &#x27; Alert Issued by Microsoft , NWS, X and Multiple... - YouTube</a></li>
<li><a href="https://en.wikipedia.org/wiki/2026_Microsoft_outage">2026 Microsoft outage - Wikipedia</a></li>
<li><a href="https://dopestudio.co.uk/microsoft-365-outage-what-happened-and-how-it-hit-businesses-and-ai/">Microsoft 365 Outage Nov 2026 : Impact on Business &amp; AI</a></li>
<li><a href="https://www.cnbc.com/2026/11/12/microsoft-outage-outlook-aws-google.html">Microsoft works to restore Outlook and other 365 services</a></li>

</ul>
</details>

**标签**: `#infrastructure reliability`, `#Microsoft`, `#outage`, `#layoffs`, `#engineering practices`

---

<a id="b0700-item-tech-news-2"></a>
### [Check Point 安全管理服务器遭活跃入侵活动利用 PRNG 漏洞](https://www.greynoise.io/blog/check-point-security-management-servers-intrusion-campaign) ⭐️ 7.0/10

GreyNoise 披露了一起针对 Check Point 安全管理服务器的活跃入侵活动，攻击者利用 HFS（Host Firewall Service）会话 cookie 签名中 JavaScript Math.random\(\) 的可预测性来伪造管理员会话。具体而言，每次向 HFS loginSrp1 端点发起 POST 请求时，返回的签名 cookie 中「sid」值由 Node.js V8 引擎的 Math.random\(\) 生成；攻击者通过连续多次登录收集足够输出，重建 V8 PRNG 内部状态，从而恢复 cookie 签名密钥并伪造已签名的管理员会话 cookie。GreyNoise 报告还提及 CVE-2026-16232 可能是攻击者获取初始访问权限的入口，但尚未完全确认。该漏洞类别（可预测伪随机数生成器）在原理上并非新颖，但此次针对安全厂商自身产品的实战利用具有警示意义。

hackernews · louiereederson · 11月24日 16:32 · [社区讨论](https://news.ycombinator.com/item?id=50630594)

**「背景」** JavaScript 的 Math.random\(\) 并非密码学安全的伪随机数生成器，其内部状态可通过少量输出序列重建，这一弱点在原理上早已广为人知，但此次被实际用于伪造 Check Point HFS 管理会话 cookie。社区评论指出，攻击者可能通过 CVE-2026-16232 获得初始访问权限；GreyNoise 此前已披露代号 GT13 的入侵活动波及 17 个国家的 22 家组织，涉及 24 台 Check Point 服务器，并伴随数据窃取与防护绕过行为。

**「受影响组织应立即排查」** 运行 Check Point 安全管理服务器（HFS）的组织面临无需凭据即可伪造管理员会话的活跃攻击，攻击者通过多次登录收集 Math.random\(\) 输出即可重建 V8 PRNG 内部状态并恢复会话签名密钥。社区讨论中有人指出，多起 Check Point 客户被入侵的案例可能通过 CVE-2026-16232 获得初始访问，这意味着将 HFS 端点暴露于互联网的组织风险最高，应优先确认服务器是否可从外部访问并尽快修补相关漏洞。

**「社区讨论」** 社区讨论中最具实质性的问题是攻击者如何获得初始访问权限：有评论者指出 CVE-2026-16232 可能是初始利用向量，并追问受影响组织是否将 Check Point 安全管理服务器暴露于公网。另有评论者从设计层面质疑为何 Math.random\(\) 本身不默认提供更高安全性，而非要求数百个应用各自避免误用。部分评论者对 LLM 驱动的大规模自动化攻击进行了推测，但缺乏具体证据支撑。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://dzen.ru/a/awW7ysd-fTJLjyiF">Хакеры взломали серверы Check Point в 22 компаниях | Дзен</a></li>

</ul>
</details>

**标签**: `#security`, `#vulnerability`, `#check-point`, `#prng`, `#threat-intelligence`

---

<a id="b0700-item-tech-news-3"></a>
### [vCenter vmdir 曝 9.8 分鉴权绕过漏洞，已被零日利用](https://thehackernews.com/2026/11/vmware-vcenter-hit-by-another-critical.html) ⭐️ 7.0/10

Broadcom 为 VMware 产品线发布了 23 个漏洞补丁，其中核心漏洞为 vCenter 目录服务 vmdir 的鉴权绕过漏洞 CVE-2026-123903，CVSS 评分 9.8。该漏洞允许任何能够访问 vCenter 的攻击者绕过认证直接获取系统权限，且在补丁发布前数日已遭零日利用。目前公开信息未披露受影响的具体版本范围、利用方式细节或临时缓解措施，安全团队应优先排查 vCenter 实例并尽快应用补丁。

telegram · zaihuapd · 11月24日 14:50

**「背景」** vCenter 是 VMware 的虚拟化管理平台，广泛用于企业数据中心，负责集中管理 ESXi 主机和虚拟机。Broadcom 于 2023 年完成对 VMware 的收购后，VMware 安全补丁由 Broadcom 发布。标题中「再曝」表明 vCenter 此前已多次出现高危漏洞，此次 CVE-2026-123903 是该平台安全问题的又一次集中暴露。

**「运维与安全的紧迫行动」** 由于该漏洞在补丁发布前数日已被零日利用，任何可网络访问 vCenter 的攻击者均可通过一次失败的 LDAP SASL 绑定在连接上植入目标身份的访问令牌，随后以该身份执行明文 LDAP 操作而无需凭据（tool-2-1）。运行 vCenter 的企业安全团队和基础设施运维人员应立即部署 Broadcom 发布的补丁，并排查近期是否存在未授权的 LDAP 管理员账户创建或异常目录服务访问记录，以确认是否已遭入侵。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/dinosn/CVE-2026-123903">dinosn/ CVE - 2026 - 123903 : CVE - 2026 - 123903 : VMware vCenter vmdir ...</a></li>

</ul>
</details>

**标签**: `#vulnerability`, `#VMware`, `#authentication-bypass`, `#zero-day`, `#infrastructure-security`

---

## 科技博客

<a id="b0700-item-tech-blog-1"></a>
### [从单个 USB-C 端口拆分 USB 3 与 USB 2 信号](https://www.frankchiarulli.com/blog/splitting-usb-c/) ⭐️ 6.0/10

hackernews · fcjr · 11月24日 14:54 · [社区讨论](https://news.ycombinator.com/item?id=50629106)

**「背景」** USB-C 连接器以 24 个微型引脚同时承载 40–120 Gbps 数据与最高 240W 电力，其内部信号路由远比 USB-A 的 4 线设计复杂。Frank Chiarulli 在博客中探讨了一个对硬件/PCB 设计者而言非显然的设计模式：如何从单个 USB-C 端口同时引出 USB 3 和 USB 2 信号，使两个不同速度的设备共享同一物理接口。

**「方案」** 作者的核心思路是利用 USB-C 内部信号线的物理分离特性，将 USB 3 的 SuperSpeed 差分对与 USB 2 的 D+/D- 线分别路由到不同的下游设备，从而在一个端口上同时暴露两种速度的连接。社区讨论揭示了这一方案的优雅之处及其实际局限。评论者 jsmith45 指出，最大的工程难点在于电源管理：当主机需要切断某个 3.x 端口的供电时，必须通过设备树或 ACPI 表获知该 3.x 端口与哪个 2.x 端口配对，内部映射关系可能相当复杂。另一位评论者 Doohickey-d 补充了一个相关技巧——利用 USB-C 的可逆插拔特性，根据插头方向切换端口功能（例如一面访问 SD 卡、另一面输出实时视频），无需额外集线器即可实现类似的多设备暴露。评论者 xg15 则从协议演进角度评论，认为 USB 论坛的向后兼容策略是「不扩展协议，而是要求完整实现旧协议」，这一设计哲学贯穿了 USB 3 与 USB 2 共存的架构。

**「启示」** USB-C 端口在物理层具备同时承载多代 USB 信号的能力，但将其转化为可用的多设备方案时，电源管理、设备树映射等系统级约束往往比信号路由本身更具挑战性，这反映了 USB 生态中向后兼容设计哲学的深层代价。

**标签**: `#USB-C architecture`, `#hardware design`, `#signal routing`, `#embedded systems`, `#PCB design`

---

<a id="b0700-item-tech-blog-2"></a>
### [Cloudflare 基础设施透明度不足：TLS、IPv6 与通知缺陷](https://charlie.fish/posts/2026/11/what-cloudflare-doesnt-tell-you/) ⭐️ 5.0/10

hackernews · fishcharlie · 11月24日 19:03 · [社区讨论](https://news.ycombinator.com/item?id=50632883)

**「背景」** Cloudflare 作为全球规模最大的 CDN 与边缘安全平台之一，为大量网站提供 TLS 终止、DDoS 防护和 IPv4/IPv6 回源等能力。作者 Charlie Fish 认为，这种「中间层」角色在提供便利的同时，也遮蔽了底层基础设施的真实状态，使网站管理员难以感知回源连接中的安全隐患。

**「方案」** 作者从多个维度指出 Cloudflare 的不足：在 TLS 回源方面，Cloudflare 对源站连接的安全状态缺乏充分暴露，管理员难以判断整条路径的加密质量；在 IPv4/IPv6 处理上，Cloudflare 在回源时主动偏好 IPv4 而非 IPv6，作者认为这反映了协议演进上的滞后；在通知机制上，作者批评 Cloudflare 未向网站管理员充分告知上述问题。作者进一步提议，行业应考虑让 CDN 等中间网络在自身 TLS 信息之外，同时暴露回源 TLS 连接信息，以便用户和网络研究者理解整条路径的加密状态，并对不良安全实践形成问责。社区反应分化明显：Cloudflare 员工 jgrahamc 回应称公司已于 2022 年推出 SSL/TLS Recommender 工具帮助客户配置回源 TLS，暗示通知问题并非完全缺失；但 viraptor 认为 IPv4/IPv6 偏好「极其无关紧要」，因为用户可自行禁用 IPv4；huijzer 则指出多数用户根本不需要 DDoS 防护，且 Cloudflare 的可用性反而低于可靠 VPS 提供商。这些反驳表明，部分论点可能缺乏足够上下文或存在过度概括。

**「启示」** 作者的核心论点是：当基础设施被大规模中间层封装后，透明度缺失本身就是一种系统性风险，行业需要建立机制让终端用户能够穿透中间层感知真实连接状态。不过，社区反馈显示这一主张的适用范围和紧迫性存在争议，并非所有被列举的问题对多数用户都构成实际威胁。

**标签**: `#Cloudflare`, `#CDN infrastructure`, `#TLS/SSL`, `#networking`, `#critical analysis`

---

<a id="b0700-item-tech-blog-3"></a>
### [爱好者级 3D 扫描技术初探：摄影测量与结构光对比](https://hackaday.com/2026/11/24/getting-started-with-hobbyist-level-3d-scanning-technologies/) ⭐️ 5.0/10

rss · Hackaday · 11月24日 15:00

**「背景」** 3D 扫描技术已存在数十年，但爱好者级设备直到近年才变得可负担。作者 Maya Posch 以 2D 扫描仪演进史为类比，将当前阶段定位为类似 90 年代手持扫描仪——便宜设备能用但需大量技巧，而更贵的设备能显著降低挫败感。

**「方案」** 文章以一块 ESP32-S3 开发板为测试对象，分别用 Nikon D7200 搭配开源软件 Regard3D 进行摄影测量，以及 Creality Sermoon P1 进行结构光扫描。摄影测量方面，17 张照片的初次尝试因上下表面覆盖不足而失败；77 张照片的第二次尝试在 SMVS 算法下获得可用网格，但金属边缘仍有缺口，CVMS 算法则完全无法使用。结构光方面，作者经历了更彻底的失败：软件界面极不直观，旋转台反而让扫描仪混淆了目标，最终未获得任何有意义结果。作者将爱好者预算上限定在 1000 至 2000 美元区间，指出摄影测量在操作直觉性上明显优于结构光，但后者在精度上仍有潜力。评论区补充了实用经验：在转盘上贴标记点而非物体本身、使用消光喷雾处理反光表面、以及 AI 图像转 3D 模型等新方法。

**「启示」** 作为系列首篇，文章尚未给出明确结论，但初步证据表明摄影测量对爱好者更友好，而结构光扫描的软件体验仍是主要障碍；最终哪种技术胜出取决于具体精度需求和对象复杂度。

**标签**: `#3D scanning`, `#photogrammetry`, `#structured light`, `#hobbyist hardware`, `#reverse engineering`

---
