---
layout: default
title: "Horizon Summary: 2026-08-18 (ZH)"
date: 2026-08-18
lang: zh
---

> 从 52 条内容中筛选出 14 条重要资讯。

---

1. [Mojo 编程语言以 Apache 2.0 协议正式开源](#item-1) ⭐️ 9.0/10
2. [Qwen 3.8 27B 以 52 分追平 GPT-5.6 Luna](#item-2) ⭐️ 9.0/10
3. [TurboVec：用 Rust 实现谷歌 TurboQuant 向量搜索](#item-3) ⭐️ 8.0/10
4. [Linux 7.3 内核在显存耗尽时提升性能](#item-4) ⭐️ 8.0/10
5. [配摄像头 AirPods 现身 macOS Tahoe 26.7 RC 视频展示视觉智能](#item-5) ⭐️ 8.0/10
6. [冰岛超市关于管理顾问的讽刺警告](#item-6) ⭐️ 7.0/10
7. [亚马逊广告驱动的搜索对消费者征收隐性“税”](#item-7) ⭐️ 7.0/10
8. [把铁路网变成平板扫描仪：线阵扫描创意项目](#item-8) ⭐️ 7.0/10
9. [用弹簧针和临时工具救活变砖的 AMD Framework 13 笔记本](#item-9) ⭐️ 7.0/10
10. [数据中心废热可使凤凰城气温升高达 4°C。](#item-10) ⭐️ 7.0/10
11. [macOS 26.7 代码曝光苹果智能在华审查机制](#item-11) ⭐️ 7.0/10
12. [中国要求政府机构提前卸载定制版 Windows 10](#item-12) ⭐️ 7.0/10
13. [OpenAI 与 CodeAI 推出青少年 AI 教育与 ChatGPT 青少年版](#item-13) ⭐️ 7.0/10
14. [国产 AI 芯片预计 2026 年占据中国市场近 90%](#item-14) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Mojo 编程语言以 Apache 2.0 协议正式开源](https://simonwillison.net/2026/Aug/18/mojo-is-now-open-source/) ⭐️ 9.0/10

2026 年 8 月，Modular 以 Apache 2.0 许可证开源了 Mojo 编译器和工具链，兑现了 2023 年 5 月作出的承诺。此前一周，Mojo 1.0 刚刚发布。 这是 AI 基础设施领域的一个重要里程碑，因为 Mojo 兼具类似 Python 的语法和高性能系统编程能力，并原生支持 GPU。开源将促进更广泛的采用和社区贡献，并可能加速 AI 开发工具的演进。 Mojo 最初计划成为 Python 的超集，但这一目标在 2025 年 8 月前后被调整，目前它是一种独立的语言。它基于 MLIR 编译器框架，可面向 CPU、GPU、TPU 及更多加速器生成代码。

rss · Simon Willison · 8月18日 21:39

**背景**: Mojo 是 Modular 公司开发的一种系统编程语言，其语法借鉴 Python，同时引入静态类型和借用检查器等系统级特性。它面向 AI 和异构计算领域的高性能场景。此次开源紧随 1.0 版本发布，兑现了对开发者社区的长期承诺。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mojo_(programming_language)">Mojo (programming language)</a></li>
<li><a href="https://mojolang.org/">Mojo</a></li>

</ul>
</details>

**标签**: `#Mojo`, `#open source`, `#programming language`, `#AI`, `#compiler`

---

<a id="item-2"></a>
## [Qwen 3.8 27B 以 52 分追平 GPT-5.6 Luna](https://simonwillison.net/2026/Aug/17/qwen-38-27b-scores-52/) ⭐️ 9.0/10

Qwen 3.8 27B 在 Artificial Analysis 智能指数上获得 52 分，与 GPT-5.6 Luna（最高）持平，仅比 GLM-5.2（最高）和 DeepSeek V4 Pro 0813（最高）低一分。对于一个 270 亿参数的开源权重模型来说，这是一个里程碑式的结果。 一个 270 亿参数的模型能够与 7530 亿到 1.7 万亿参数规模的模型匹敌，预示着模型效率与可及性可能迎来范式转变。这可能让前沿水平的智能在单张 GPU 上即可部署，极大降低 AI 应用的成本和延迟。 Artificial Analysis 智能指数 v4.1.1 汇总了大约十项评测（包括 GDPval-AA、Terminal-Bench v2.1、SciCode、GPQA Diamond 和 Humanity's Last Exam），得出 1 到 100 分的综合得分。Qwen 3.8 27B 是一个 270 亿参数规模的稠密模型，具备原生视觉-语言能力；在 4-bit 量化下，未计入 KV cache 时仅需约 14-16GB 显存即可运行。

rss · Simon Willison · 8月17日 23:58

**背景**: Artificial Analysis 智能指数是一个独立基准，将编程、科学推理、智能体工具使用和通用知识等能力综合为一个“智能”评分，各大实验室在新品发布公告中广泛引用该分数。Qwen 3.8 27B 是阿里巴巴 Qwen 团队最新发布的开源权重模型，定位为原生视觉-语言模型，支持灵活思考控制，可可靠地完成复杂多步骤任务。其较小的体量与 API-only 旗舰模型（如 Qwen 3.8-Max）或集群级系统（如 Kimi K3）形成鲜明对比。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://artificialanalysis.ai/">AI Model & API Providers Analysis | Artificial Analysis</a></li>
<li><a href="https://huggingface.co/Qwen/Qwen3.8-27B">Qwen/Qwen3.8-27B · Hugging Face</a></li>
<li><a href="https://www.yottalabs.ai/post/qwen-3-8-27b-specs-hardware-requirements-how-to-run-2026">Qwen 3.8 27B: Specs, Hardware Requirements, and How to Run It (2026) | Yotta Labs</a></li>

</ul>
</details>

**标签**: `#AI`, `#LLMs`, `#Qwen`, `#benchmarks`, `#efficiency`

---

<a id="item-3"></a>
## [TurboVec：用 Rust 实现谷歌 TurboQuant 向量搜索](https://github.com/RyanCodrai/turbovec) ⭐️ 8.0/10

TurboVec 是一个新的 Rust 库，在 GitHub 上以 'turbovec' 名称发布，重新实现了谷歌的 TurboQuant 高效向量搜索技术。该项目旨在让 Rust 开发者也能使用这种节省内存的量化方法。 向量搜索是 AI 应用的核心，而 TurboQuant 号称能实现接近零的索引时间和大幅降低的内存占用。Rust 实现可以让这些优势更容易被性能敏感型系统采用，并扩展现有 C++/Python 之外的生态。 TurboQuant 的原理是在索引前对高维向量进行旋转和压缩，而 TurboVec 项目仍处于早期阶段，这一点从 README 和社区反馈中可以看出。评论者还指出，Qdrant 已经在数月前开始集成 TurboQuant，说明该技术正被广泛采用。

hackernews · fittingopposite · 8月18日 18:07 · [社区讨论](https://news.ycombinator.com/item?id=49349898)

**背景**: TurboQuant 是谷歌提出的一种技术，能够以极低内存、接近零的预处理时间和最先进的准确率来构建和查询大规模向量索引，从而让语义搜索更高效。向量搜索依赖嵌入（embedding），而量化方法（如二进制量化）可将存储最多缩小 32 倍；TurboQuant 则通过归一化和随机旋转进一步优化。TurboVec 是这类技术被引入 Rust 以构建更快、更安全系统的趋势之一。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://research.google/blog/turboquant-redefining-ai-efficiency-with-extreme-compression/">TurboQuant : Redefining AI efficiency with extreme compression</a></li>
<li><a href="https://almcorp.com/blog/google-turboquant-vector-search-explained/">Google TurboQuant Vector Search : What It Is and How It Works</a></li>

</ul>
</details>

**社区讨论**: HN 评论者总体上很热情：有人指出 1000 万篇文档只占 4GB，可以显著加快倒排索引构建和调试过程，还有人期待 SQLite 绑定。但也有人提醒，FAISS 已不再是业界最先进方案，并附上了 ANN benchmark 链接；还有人表示 Qdrant 早已集成 TurboQuant，并建议阅读 TurboQuant 的公开评审以获得更全面的看法。

**标签**: `#vector-search`, `#Rust`, `#quantization`, `#TurboQuant`, `#ANN`

---

<a id="item-4"></a>
## [Linux 7.3 内核在显存耗尽时提升性能](https://pixelcluster.dev/VRAM-Overcommit/) ⭐️ 8.0/10

Linux 7.3 引入了改进显存耗尽时视频内存管理性能的初始内核代码。这一针对显存超卖场景的改动将随 Linux 7.3 内核发布，预计可减少帧时间卡顿。 显存耗尽在游戏和 GPU 加速负载中是很常见的痛点，因此更好的超卖性能直接提升用户体验。这也凸显了 Linux 内核开发持续带来以性能为核心的更新，而许多用户对此充满期待。 这项工作由 Vock 主导，他还在推进对 Linux GPU 驱动视频内存管理的进一步改进。文章指出，实际的驱逐性能很大程度上取决于 GPU 如何使用被驱逐的内存，而虚拟内存碎片化也是一个相关的考虑因素。

hackernews · flaburgan · 8月18日 07:51 · [社区讨论](https://news.ycombinator.com/item?id=49342719)

**背景**: 内存超卖是计算中的一个概念，即分配给进程的内存超过物理可用内存，依赖的是并非所有内存会同时被使用这一事实。显存超卖也是类似机制，让 GPU 内存超过物理显存，将数据换出到系统内存。Linux 内核通过启发式算法以及 vm.overcommit_memory 等超卖设置来管理这一行为。Linux 7.3 的改进重点在于让显存耗尽时的体验更加流畅。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Memory_overcommitment">Memory overcommitment - Wikipedia</a></li>
<li><a href="https://www.phoronix.com/news/Linux-7.3-Improving-vRAM-Mgmt">Linux 7.3 To Land Initial Code Improving vRAM Management ...</a></li>
<li><a href="https://pixelcluster.dev/VRAM-Overcommit/">VRAM Management Part 2: Beyond the Limits... | pixelcluster's GPU blog</a></li>

</ul>
</details>

**社区讨论**: 评论者总体态度热情：有人表示在 7.2 的诸多性能改进后已经等不及 7.3 了，还有人希望系统内存满时也能有类似修复。一位 Nvidia 用户评论说 Nvidia GPU 似乎完全不支持分页，并询问内核是否可以对虚拟内存进行就地碎片整理以提升性能。

**标签**: `#linux`, `#kernel`, `#vram`, `#performance`, `#memory-management`

---

<a id="item-5"></a>
## [配摄像头 AirPods 现身 macOS Tahoe 26.7 RC 视频展示视觉智能](https://www.macrumors.com/2026/08/17/camera-equipped-airpods-macos-26-7/) ⭐️ 8.0/10

苹果正在开发代号为 B790 的配备摄像头 AirPods，macOS Tahoe 26.7 候选发布版中的视频揭示了这一点。视频演示了视觉智能功能，摄像头可识别书名，Siri 能回答佩戴者周围环境的问题，该产品最快可能于 9 月发布。 这标志着苹果向可穿戴设备集成视觉智能迈出了重要一步，可实现免提、情境感知的辅助功能。它可能重塑 AirPods 产品线，并加剧 AI 驱动可穿戴设备市场的竞争。 macOS Tahoe 26.7 候选发布版中的视频显示，AirPods 摄像头通过视觉智能识别书名并保存信息。彭博社的马克·古尔曼此前曾报道该产品可能于今年发布，B790 代号紧随 AirPods Pro 3 的 B788，表明这是一个合理的后续版本。

telegram · zaihuapd · 8月18日 02:00

**背景**: macOS Tahoe 是苹果 macOS 的第二十二个重大版本，于 2025 年 WWDC 上公布，并于 2025 年 9 月 15 日发布。视觉智能是苹果基于 AI 的功能，让摄像头能够识别物体、文字和地标，已在较新的 iPhone 上提供。配备摄像头的 AirPods 将把这一功能带到可穿戴设备形态，让用户能通过 Siri 自然地查询周围环境。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.macrumors.com/2026/08/17/camera-equipped-airpods-macos-26-7/">Apple's Camera-Equipped AirPods Confirmed: See... - MacRumors</a></li>
<li><a href="https://9to5mac.com/2026/08/17/airpods-with-camera-get-their-clearest-leak-yet/">AirPods with cameras get their clearest leak yet - 9to5Mac</a></li>
<li><a href="https://www.apple.com/newsroom/2025/06/macos-tahoe-26-makes-the-mac-more-capable-productive-and-intelligent-than-ever/">macOS Tahoe 26 makes the Mac more capable, productive, and ...</a></li>

</ul>
</details>

**标签**: `#Apple`, `#AirPods`, `#macOS`, `#视觉智能`, `#硬件`

---

<a id="item-6"></a>
## [冰岛超市关于管理顾问的讽刺警告](https://about.iceland.co.uk/our-story/the-dark-ages/beware-management-consultants/) ⭐️ 7.0/10

英国连锁超市 Iceland Foods 在其官网发布了一篇题为《提防管理顾问》（Beware Management Consultants）的讽刺文章，嘲笑大型管理咨询公司带来的陷阱与荒诞。该文是其“黑暗时代”（The Dark Ages）历史回顾系列的一部分。 这篇讽刺文章与对咨询行业激励机制的普遍批评产生共鸣——大型咨询公司的收益来自推动变革，而非实现持久成果。它为企业界提供了一个少见的发声角度，加入关于管理咨询价值的持续争论，尤其引起那些承受咨询后果的工程师和员工的共鸣。 这篇文章发布在 Iceland Foods 官网“我们的故事”（Our Story）的“黑暗时代”（The Dark Ages）栏目下，属于一种戏谑式的企业历史叙述。评论者提到，这家公司曾与冰岛国家发生过商标争议，进一步体现了其特立独行的企业文化。

hackernews · KolmogorovComp · 8月18日 19:29 · [社区讨论](https://news.ycombinator.com/item?id=49351324)

**背景**: Iceland Foods 是一家以冷冻食品闻名的英国连锁超市，成立于 1970 年，长期由特立独行的创始人 Malcolm Walker 领导。“黑暗时代”系列似乎是该公司以自嘲、幽默的方式回顾过往商业失误。管理顾问经常被批评为兜售通用建议并让客户产生依赖，这篇讽刺文章似乎正是在表达这种观点。

**社区讨论**: 评论者觉得这家公司的特立独行很有趣，将它比作 Dr. Bronner 肥皂上密密麻麻的标签文字和 SQLite 的道德准则。也有人进一步讨论咨询行业的激励问题，认为管理层对变革的痴迷常常忽视竞争现实；还有评论者自嘲地反思自己内部的治理工作是否同样如此。

**标签**: `#management`, `#consulting`, `#corporate-culture`, `#satire`, `#business`

---

<a id="item-7"></a>
## [亚马逊广告驱动的搜索对消费者征收隐性“税”](https://seths.blog/2026/08/the-amazon-tax/) ⭐️ 7.0/10

Seth Godin 的博文批评亚马逊的搜索结果是一种由广告驱动的“助推机制”，认为平台实际上通过引导消费者购买亚马逊想卖的产品、而非最匹配的产品，对消费者征收了一种隐性“税”。这篇文章引发广泛讨论，获得 474 条评论和 7.0/10 的评分。 亚马逊是占主导地位的电商平台，因此搜索质量下降会影响数百万买家和卖家。这一批评凸显了更广泛的担忧：平台经济如何将广告收入置于用户体验之上。 评论者报告称，大约四分之三的搜索结果可能是赞助广告，平台看起来是在引导购买意图，而非帮助定位特定商品。文章认为，广告的唯一目的是让消费者选择并非评论最好或价格最优的产品。

hackernews · herbertl · 8月18日 13:22 · [社区讨论](https://news.ycombinator.com/item?id=49345263)

**背景**: “亚马逊税”是一个隐喻，指当搜索结果为了广告主而非消费者的明确意图进行优化时，消费者所付出的隐性成本。随着时间推移，亚马逊的搜索已经从“定位我要找的确切商品”变成“给我一份充满赞助商品的语义搜索结果列表”。这种批评与关于平台设计和消费者行为的更广泛讨论相关，即广告日益塑造用户看到的选择。

**社区讨论**: 评论者大多认同这一批评，多人表示亚马逊的搜索几乎无法使用，且很大一部分结果是赞助广告。一些用户表示因质量下降而将购买转向其他平台，也有人指出这种行为只是广告的普遍运作方式。

**标签**: `#ecommerce`, `#platform-design`, `#search`, `#amazon`, `#consumer-behavior`

---

<a id="item-8"></a>
## [把铁路网变成平板扫描仪：线阵扫描创意项目](https://philo.gay/linecam/) ⭐️ 7.0/10

这是一个创意计算项目，把行驶中的火车当作平板扫描仪，通过车窗捕捉线阵扫描图像，再拼接成铁路沿线景观的“扫描图”。该项目在网站上展示了这一技术及其中间结果。 该项目展示了如何将日常移动和普通硬件重新用于艺术成像，在摄影、时间与空间之间建立联系。它的启发性在于提供了一种低成本、易上手的方式，让人们在专业工作室之外也能探索狭缝扫描技术。 该技术依赖于线阵扫描成像：一条狭缝每次只捕捉一行图像，而火车的移动提供了第二个扫描维度。项目作者自己也提到，进行中的“扫描图”本身就是对时间和空间的有趣拉伸，即便不是最终的创作目标。

hackernews · otherayden · 8月18日 12:43 · [社区讨论](https://news.ycombinator.com/item?id=49344825)

**背景**: 线阵扫描相机通过单一传感器元件，在一个方向上扫描，同时借助被摄物体或相机的移动来完成第二个方向的成像。狭缝扫描摄影是一种相关的艺术技法，通过在相机和被摄物之间加入一条狭缝，将运动和时间记录在同一张图像中。该项目把这些原理应用到火车上，把铁路网变成了一台巨大的扫描装置。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Line-scan_camera">Line-scan camera - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Slit-scan_photography">Slit-scan photography</a></li>
<li><a href="https://www.lomography.com/magazine/283280-making-a-slit-scan-camera">Making a Slit Scan Camera · Lomography</a></li>

</ul>
</details>

**社区讨论**: 评论区对该项目反响热烈，并补充了实用和历史背景。有人回忆起 2008 年曾用 iSight 摄像头做过类似装置，也有人分享了自己手工拼接的狭缝扫描动画，还有人推荐了 slitscan.space 上的交互式狭缝扫描小工具。总体态度积极，既称赞了这篇记录，也提出了进一步实验的建议，例如在车窗上贴镜子来测量列车速度。

**标签**: `#creative-computing`, `#imaging`, `#slit-scan`, `#photography`, `#railway`

---

<a id="item-9"></a>
## [用弹簧针和临时工具救活变砖的 AMD Framework 13 笔记本](https://quantum5.ca/2026/08/16/fixing-bricked-amd-7040-series-framework-13-laptop-with-20-tools/) ⭐️ 7.0/10

一篇详细文章记录了如何在一台 AMD 7040 系列 Framework 13 笔记本因 BIOS 更新失败而变砖后将其救活。由于该型号没有 Framework 提供的标准 BIOS 恢复选项，修复工作依靠临时工具和弹簧针完成。 这一事件暴露了维修权运动中的一个盲点：即使是可以由用户维修的笔记本，也可能缺乏易用的固件恢复途径。它也引发了关于厂商是否应对官方更新导致设备变砖负责的争论，即使设备已过保修期。 作者不得不使用弹簧针直接接触 SPI 闪存芯片，因为 Framework 为了降低成本而未焊接 JSPI 调试连接器。这一过程很好地说明了嵌入式调试工具如何替代缺失的恢复基础设施。

hackernews · jp_sc · 8月18日 13:18 · [社区讨论](https://news.ycombinator.com/item?id=49345220)

**背景**: Framework Computer 是一家倡导维修权的笔记本厂商，其产品采用模块化、易拆解设计。弹簧针是一种弹簧加载的电气触点，常用于 PCB 测试治具和编程夹具。BIOS 恢复通常依赖厂商提供的机制，如 USB 恢复文件或专用排针；当这些选项缺失时，用户只能自行想办法。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Pogo_pin">Pogo pin</a></li>
<li><a href="https://en.wikipedia.org/wiki/Framework_Laptop">Framework Laptop</a></li>
<li><a href="https://www.intel.com/content/dam/support/us/en/documents/boardsandkits/BIOS-Recovery-Update-Instructions.pdf">BIOS Recovery Update Instructions</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了不满，并围绕法律责任展开争论；有人主张，官方 BIOS 更新存在缺陷导致设备变砖，即使过保也应可在小额索赔法庭维权。还有人指出 ThinkPad 和 Pixel 设备也有类似问题，并提到 Framework 的 JSPI 连接器其实存在但没有焊接；部分评论者表示这一经历让他们后悔购买了 Framework 笔记本。

**标签**: `#hardware`, `#BIOS`, `#repair`, `#Framework`, `#embedded`

---

<a id="item-10"></a>
## [数据中心废热可使凤凰城气温升高达 4°C。](https://asmedigitalcollection.asme.org/sustainablebuildings/article/7/2/024501/1233035/Data-Center-Waste-Heat-as-an-Emerging-Urban) ⭐️ 7.0/10

《ASME 可持续建筑杂志》上的一项新研究发现，凤凰城一个数据中心园区的废热可使附近气温升高达 4°C，下风向约 500 米范围内平均升温约 0.8°C。 这些发现凸显了数据中心对当地气候的可测量影响，而随着人工智能和云计算推动此类设施快速扩张，这一影响可能进一步加剧。市政部门和运营商可能需要考虑废热缓解和再利用策略，以避免加剧城市热岛效应。 该研究测量了凤凰城一个数据中心园区周围的气温，发现下风向约 500 米范围内典型升温为 0.8°C，最大影响为 4°C。研究将废热视为一种新兴的城市问题，而非全球气候驱动因素。

hackernews · cwwc · 8月18日 17:24 · [社区讨论](https://news.ycombinator.com/item?id=49349147)

**背景**: 数据中心消耗大量电力，而这些能量最终几乎全部转化为必须散发的热量，通常通过冷却系统排出热空气。当数据中心位于城市区域时，这种废热会加剧城市热岛效应——即城市比周边农村地区更热的趋势。凤凰城气候炎热干燥，是此类温度升高的特别敏感地点。研究人员正越来越多地研究废热回收技术，以将这种副产品转化为有用能源。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Urban_heat_island_effect">Urban heat island effect</a></li>
<li><a href="https://www.eesi.org/articles/view/thermal-energy-networks-turn-data-center-waste-heat-into-a-hot-commodity">Thermal Energy Networks Turn Data Center Waste Heat into a Hot Commodity | Article | EESI</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍对标题的表述持怀疑态度，指出平均测量升温为 0.8°C，远小于 4°C 的最大值。一位评论者质疑数据中心热量是否值得关注，相比之下 AI 带来的风险更大；另一位则认为该问题可能因政治目的被夸大；还有评论者指出化石燃料基础设施受到的关注反而更少。

**标签**: `#data centers`, `#waste heat`, `#urban heat island`, `#energy infrastructure`, `#climate`

---

<a id="item-11"></a>
## [macOS 26.7 代码曝光苹果智能在华审查机制](https://www.macrumors.com/2026/08/17/macos-26-7-unreleased-apple-devices/) ⭐️ 7.0/10

MacRumors 报道称，未发布的 macOS 26.7 版本中的代码曝光了 Apple Intelligence“写作工具”在中国大陆的内容安全处理机制。代码显示，使用前需进行强制的内容安全更新，部分文本无法被编辑并可能需发送给其他服务，多次触发安全警报后“写作工具”会被暂时限制。 这一发现意义重大，因为它是首批具体证据，表明苹果的 AI 写作功能将针对中国大陆内置过滤和处罚机制，引发隐私与审查方面的担忧。它同时表明苹果可以通过云控远程下发安全规则，这可能会影响用户和开发者对该功能的信任。 被发现的字符串包括“需要进行内容安全更新”“无法编辑此文本”（提示将文本发送给 %1$@/%2$@）以及“因多次触发安全警报，‘写作工具’暂时受限”。安全审查规则似乎可通过云控远程下发；不过，这些发现基于未发布代码，尚未得到苹果证实。

telegram · zaihuapd · 8月18日 02:16

**背景**: Apple Intelligence 是苹果的个人智能系统，由新一代 Apple 基础模型驱动，可在 iPhone、iPad、Mac 等设备上提供文本改写、校对、摘要等“写作工具”功能。“写作工具”是 Apple Intelligence 首批落地能力之一，随 iOS 18.1 等系统更新推出。在中国大陆，人工智能功能需要符合本地内容安全监管要求；苹果官方曾表示，当 Apple Intelligence 功能在中国大陆可用时，受支持的设备可以在该地区激活使用。MacRumors 发现的代码似乎正是描述这一合规机制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://support.apple.com/en-us/121115">How to get Apple Intelligence - Apple Support</a></li>
<li><a href="https://developer.apple.com/apple-intelligence/">Apple Intelligence - Apple Developer</a></li>

</ul>
</details>

**标签**: `#Apple`, `#Apple Intelligence`, `#Censorship`, `#China`, `#macOS`

---

<a id="item-12"></a>
## [中国要求政府机构提前卸载定制版 Windows 10](https://www.bloomberg.com/news/articles/2026-08-18/china-axing-microsoft-windows-from-state-agencies-ahead-of-plan) ⭐️ 7.0/10

中国国家安全部已要求部分政府相关机构卸载定制版 Windows 10 政府版，将原定 2027 年 2 月的停用时间提前数月。微软表示，未发现影响该产品的安全事件，该产品仍在定期获得安全更新。 这反映了中国对数据安全的担忧加剧，以及政府 IT 领域减少对美国技术依赖的趋势。这可能加速国产操作系统的采用，并影响微软在中国公共部门的业务。 定制版名为 Windows 10 神州网信政府版（CMGE），由微软与神州网信合作开发，旨在实现“政府数据不出境”，并移除了 OneDrive 等功能。指令源于数据安全担忧，但未披露具体漏洞；微软表示未发现影响该产品的安全事件。

telegram · zaihuapd · 8月18日 06:22

**背景**: Windows 10 政府版于 2017 年推出，旨在满足中国法律对政府数据不出境的要求。该版本由神州网信负责管理和服务，支持本地激活、补丁、更新和升级，并移除了 OneDrive 等面向消费者的功能。此次提前停用是敏感政府环境中以国产软件替代外国软件的更广泛行动的一部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.mydrivers.com/1/533/533778.htm">中国定制政府版Windows 10是这样：数据不出境</a></li>
<li><a href="https://lihkg.com/thread/4146263/page/1">內地傳提前停用定制版Windows 10系統 轉用國產作業系統 | LIHKG 討論...</a></li>

</ul>
</details>

**标签**: `#Windows 10`, `#China`, `#Government IT`, `#Cybersecurity`, `#Microsoft`

---

<a id="item-13"></a>
## [OpenAI 与 CodeAI 推出青少年 AI 教育与 ChatGPT 青少年版](https://openai.com/index/chatgpt-for-teens/) ⭐️ 7.0/10

2026 年 8 月 18 日，OpenAI 宣布与 CodeAI（前身为 Code.org）合作，帮助学生和教师负责任地使用 AI，并同步上线了“ChatGPT 青少年版”。合作内容包括联合咨询委员会、AI 素养课程、学生挑战赛、职业项目，以及一门免费的高中 AI 基础课程。 这将面向全球数百万学生普及 AI 素养教育，并通过内置安全措施回应了青少年使用 AI 的担忧。它标志着行业正将 AI 教育纳入学校课程，并让 AI 工具对未成年人更安全。 “ChatGPT 青少年版”包含适龄保护、平衡使用工具和可选的家长控制；青少年账户还可以关闭拟人语音回复。该合作还将在未来一年支持 CodeAI 开发一门免费的高中 AI 基础课程。

telegram · zaihuapd · 8月18日 12:06

**背景**: CodeAI 原名为 Code.org，于 2026 年 6 月更名，以突出 AI 教育而不只是计算机科学。“ChatGPT 青少年版”使用同样的核心 ChatGPT 模型，但加入了支持学习的功能，如作业提醒和测验，并减少过于拟人化的交互体验。此次合作延续了 OpenAI 将 AI 素养带进 K-12 教育并解决安全问题的努力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://code.org/en-US/codeai">Code.org is now CodeAI</a></li>
<li><a href="https://help.openai.com/en/articles/20001421-chatgpt-for-teens">ChatGPT for Teens | OpenAI Help Center</a></li>
<li><a href="https://www.bbc.com/news/articles/czxqz91n5n8o">OpenAI launches ChatGPT for Teens with new safety features</a></li>

</ul>
</details>

**标签**: `#OpenAI`, `#AI Education`, `#ChatGPT`, `#Teen Safety`, `#CodeAI`

---

<a id="item-14"></a>
## [国产 AI 芯片预计 2026 年占据中国市场近 90%](https://www.tomshardware.com/tech-industry/artificial-intelligence/chinas-homegrown-ai-accelerators-to-supply-90-percent-of-the-countrys-domestic-market-analysts-suggest-cambricon-and-huawei-expected-to-be-the-biggest-winners-in-the-shift-away-from-nvidia-and-amd) ⭐️ 7.0/10

TrendForce 预测，到 2026 年中国本土 AI 加速器将供应国内近 90%的市场，而前一年约为 45%。寒武纪和华为预计将成为主要受益者，逐步取代英伟达。 这标志着全球 AI 芯片格局的一次重大转变，因为美国出口管制加速了中国推动自主可控的步伐。英伟达在中国的主导地位预计将大幅削弱，从而重塑 AI 硬件供应链。 2025 年，英伟达出货 220 万颗，占据 55%市场份额；华为出货 81.2 万颗，占 20.3%。要在 2026 年实现近 90%的国产供应，中国需将高端 AI 芯片产量提升 2.2 倍至约 196 万颗，产能能否跟上成为疑问。

telegram · zaihuapd · 8月18日 13:03

**背景**: 在美国对英伟达和 AMD 先进芯片实施出口限制的背景下，中国的 AI 芯片产业快速发展。寒武纪是一家总部位于北京、部分国有控股的 AI 处理器与 GPGPU 设计公司；华为的昇腾系列则在加速卡性能上直接对标英伟达。TrendForce 等分析机构指出，中芯国际的良率偏低以及 HBM 供应受限等产能瓶颈，可能对这些雄心勃勃的目标构成威胁。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Cambricon_Technologies">Cambricon Technologies - Wikipedia</a></li>
<li><a href="https://www.trendforce.com/news/2025/12/15/insights-cambricon-remains-chinas-top-ai-chip-startup-rumored-2026-triple-output-faces-smic-limits/">[Insights] Cambricon Remains China’s Top AI Chip Startup; Rumored 2026 Triple Output Faces SMIC Limits</a></li>
<li><a href="https://www.tomshardware.com/tech-industry/semiconductors/cambricon-targets-500000-ai-chips-in-2026-as-china-accelerates-domestic-hardware-push">Cambricon targets 500,000 AI chips in 2026 as China accelerates domestic hardware push — low yields and limited HBM supply could threaten chip ambitions | Tom's Hardware</a></li>

</ul>
</details>

**标签**: `#AI hardware`, `#China`, `#semiconductors`, `#market analysis`

---