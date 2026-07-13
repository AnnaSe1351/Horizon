---
layout: default
title: "Horizon Summary: 2026-07-13 (ZH)"
date: 2026-07-13
lang: zh
---

> 从 61 条内容中筛选出 18 条重要资讯。

---

1. [苹果 SpeechAnalyzer API 与 Whisper 基准测试对比](#item-1) ⭐️ 8.0/10
2. [Telegram 的 t.me 域名被暂停](#item-2) ⭐️ 8.0/10
3. [三星健康应用威胁若拒绝 AI 训练将删除数据](#item-3) ⭐️ 8.0/10
4. [洛杉矶警局因隐私担忧终止与 Flock 合同](#item-4) ⭐️ 8.0/10
5. [苹果调整 Mac 芯片路线图，跳过 M6 高端直接研发 M7](#item-5) ⭐️ 8.0/10
6. [从思维链到潜在推理](#item-6) ⭐️ 8.0/10
7. [GPUHedge 将无服务器 GPU 冷启动延迟从 117 秒降至 30 秒](#item-7) ⭐️ 8.0/10
8. [开源工具每日按研究兴趣过滤 arXiv 论文](#item-8) ⭐️ 8.0/10
9. [在 Qwen3-4B 上评估 J-space 熵作为错误预测器](#item-9) ⭐️ 8.0/10
10. [开源社区拯救了气候.gov 数据](#item-10) ⭐️ 7.0/10
11. [SEGA CD 版《Silpheed》视觉技巧技术深度解析](#item-11) ⭐️ 7.0/10
12. [DOOMQL：完全由 SQLite 驱动的类 Doom 游戏](#item-12) ⭐️ 7.0/10
13. [字节跳动通过 Seed 世界模型团队探索自动驾驶](#item-13) ⭐️ 7.0/10
14. [Om AI 发布全球首个端侧原生流式多模态模型 VLX](#item-14) ⭐️ 7.0/10
15. [零差云控完成数亿元 C++轮融资](#item-15) ⭐️ 7.0/10
16. [英特尔追加 50 亿欧元投资爱尔兰扩大 AI 芯片产能](#item-16) ⭐️ 7.0/10
17. [阶跃星辰发布 STEPX 品牌、智能体系统 Step AOS 及 Neo 手机](#item-17) ⭐️ 7.0/10
18. [关于 LLM 多样性的提示工程论文被 ICML 接收引发争议](#item-18) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [苹果 SpeechAnalyzer API 与 Whisper 基准测试对比](https://get-inscribe.com/blog/apple-speech-api-benchmark.html) ⭐️ 8.0/10

苹果在 WWDC 2025 上推出的全新 SpeechAnalyzer API 已与 OpenAI 的 Whisper 进行基准测试，结果显示其在设备端语音转录的速度和准确性上具有竞争力。 这可能会冲击那些仅仅封装 Whisper 的付费应用，因为苹果可能会集成原生录音应用，在苹果设备上实现更快速、更私密的转录。 基准测试表明，在数学讲座场景下，SpeechAnalyzer 比 Whisper-Large-V2 快很多，但准确性略低，适合实时转录，但尚未完美适用于离线字幕。

hackernews · get-inscribe · 7月13日 16:06 · [社区讨论](https://news.ycombinator.com/item?id=48894752)

**背景**: SpeechAnalyzer 是苹果在 WWDC 2025 上推出的设备端语音识别框架，采用模块化方式取代旧 API。Whisper 是 OpenAI 基于 68 万小时数据训练的开源 ASR 模型，被广泛用于第三方应用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Whisper_(speech_recognition_system)">Whisper ( speech recognition system) - Wikipedia</a></li>
<li><a href="https://www.argmaxinc.com/blog/apple-and-argmax">Apple SpeechAnalyzer and Argmax WhisperKit - Argmax</a></li>

</ul>
</details>

**社区讨论**: 评论者指出 Whisper 已不再是最先进的模型，像 Nemotron 和 Voxtral 等更好。有人预测付费 Whisper 封装应用将消亡，还有用户将 SpeechAnalyzer 集成到了 Handy.computer 中。

**标签**: `#Speech Recognition`, `#Apple`, `#Benchmarking`, `#Whisper`, `#API`

---

<a id="item-2"></a>
## [Telegram 的 t.me 域名被暂停](https://www.whois.com/whois/t.me) ⭐️ 8.0/10

Telegram 的短链接域名 t.me 已被设置为 serverHold 状态，实际上暂停了解析，WHOIS 查询显示了这一情况。 此次暂停中断了 Telegram 的链接重定向服务，可能影响数百万依赖 t.me 链接访问频道和机器人的用户，并表明该平台面临更大的监管压力。 serverHold 状态表明是 .me 域名注册局（由黑山政府运营）采取了此行动，而非注册商 GoDaddy（一些评论者批评了后者）。该状态通常在法律纠纷或调查期间应用。

hackernews · Tiberium · 7月13日 19:52 · [社区讨论](https://news.ycombinator.com/item?id=48897878)

**背景**: t.me 是 Telegram 用于为其频道和机器人创建简短、易记链接的域名，例如 t.me/channelname。它与主要域名 telegram.org 不同。域名暂停可能因法院命令、监管请求或违反注册局政策而发生，导致域名无法解析并破坏所有关联链接。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.netify.ai/resources/domains/t.me">t . me - Domain Info - Telegram</a></li>

</ul>
</details>

**社区讨论**: 评论者对 Telegram 依赖 GoDaddy 作为注册商表示惊讶，并指其缺乏透明度。其他人指出 serverHold 状态很可能是 .me 注册局级别的行动，可能由印度、法国或俄罗斯的法律调查触发。一位用户提到已将重定向从 t.me 改为 telegram.me 作为预防措施。

**标签**: `#telegram`, `#domain suspension`, `#legal`, `#governance`, `#internet`

---

<a id="item-3"></a>
## [三星健康应用威胁若拒绝 AI 训练将删除数据](https://neow.in/cWsyMTV3) ⭐️ 8.0/10

根据一项新政策，三星健康将删除拒绝将其健康数据用于 AI 训练的用户的数据。该公司计划收集睡眠、用药、医疗记录和周期追踪数据用于 AI 训练。 这一政策引发了严重的隐私和同意问题，迫使用户在删除健康数据和允许用于 AI 训练之间做出选择。它可能为其他健康应用和可穿戴设备开创先例。 该政策涵盖四类数据：睡眠、用药、医疗记录和周期追踪。选择退出的用户将面临数据删除，可能导致许多设备功能无法使用。

hackernews · bundie · 7月13日 20:01 · [社区讨论](https://news.ycombinator.com/item?id=48897991)

**背景**: 三星健康是一款健康追踪应用，收集来自 Galaxy Watch 等设备的数据。AI 训练利用这些数据改进功能和算法。该政策将数据保留与 AI 训练同意挂钩，是一种有争议的做法。

**社区讨论**: 评论者表达了愤怒，有人称其具有胁迫性，并质疑如果功能无法使用，三星是否会退还部分设备费用。其他人指出，该政策实际上迫使用户要么分享敏感数据，要么失去数据。一位评论者讽刺地认为删除数据可以避免滥用反而有好处。还有人对三星健康应用糟糕的可用性和广告表示不满。

**标签**: `#privacy`, `#data-deletion`, `#AI-training`, `#Samsung`, `#health-data`

---

<a id="item-4"></a>
## [洛杉矶警局因隐私担忧终止与 Flock 合同](https://techcrunch.com/2026/07/13/lapd-lets-contract-with-surveillance-giant-flock-expire-citing-serious-concerns-over-civil-liberties-and-privacy/) ⭐️ 8.0/10

洛杉矶警察局（LAPD）已允许与监控公司 Flock Safety 的合同到期，理由是严重担心公民自由和隐私问题。 这一决定凸显了对大规模监控的日益抵制，但批评者警告称，Flock 的商业模式允许通过向其他机构转售数据来继续收集数据，可能削弱 LAPD 的行动。 Flock Safety 的摄像头和杆子在合同到期后仍保留，该公司仍可向其他执法机构（如 CHP、LASD 或 Palantir）出售数据，使监控系统对政治压力有弹性。

hackernews · forks · 7月13日 15:11 · [社区讨论](https://news.ycombinator.com/item?id=48893947)

**背景**: Flock Safety 是一家美国公司，提供自动车牌识别（ALPR）摄像头、视频监控和枪声检测系统。其系统被警察局和房主协会广泛使用，引发了隐私担忧，因为它们可以追踪车辆移动并在没有搜查令的情况下跨机构共享。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Flock_Safety">Flock Safety - Wikipedia</a></li>
<li><a href="https://www.aclu.org/news/privacy-technology/tracking-alpr-cameras/flock-roundup">Flock’s Aggressive Expansions Go Far Beyond Simple Driver Surveillance | American Civil Liberties Union</a></li>
<li><a href="https://www.flocksafety.com/">Flock Safety</a></li>

</ul>
</details>

**社区讨论**: 社区评论指出，Flock 的商业模式设计得很有弹性：即使一个合同终止，摄像头仍继续录制，数据可以出售给其他机构，实际上收紧了监控网。一些人质疑此类系统在预防犯罪方面的有效性，而另一些人则主张制定法律，禁止政府购买无法直接合法收集的数据。

**标签**: `#surveillance`, `#privacy`, `#civil liberties`, `#LAPD`, `#Flock`

---

<a id="item-5"></a>
## [苹果调整 Mac 芯片路线图，跳过 M6 高端直接研发 M7](https://36kr.com/newsflashes/3894068327759108?f=rss) ⭐️ 8.0/10

苹果正在调整其 Mac 芯片路线图以优先考虑 AI 性能，计划跳过高端 M6 Pro、M6 Max 和 M6 Ultra 芯片，直接于 2027 年推出 M7 系列，其中 M7 Ultra 的目标是匹敌英伟达 Blackwell 级别的 AI 加速器。 这一战略转变表明苹果有意将 AI 性能作为其 Mac 产品线的核心差异化因素，并可能打造自己的 AI 服务器芯片，挑战英伟达在 AI 加速器市场的主导地位。 苹果将在今年秋季推出基础版 M6 后跳过 M6 Pro、Max 和 Ultra 版本；M7 Ultra 预计于 2028 年推出，并可能成为苹果下一代 AI 服务器芯片的基础。此外，苹果已在研发 M8 及后续芯片，2028 年的产品将采用 1.4 纳米制程。

rss · 36kr · 7月13日 12:51

**背景**: 苹果的 Mac 芯片自 2020 年的 M1 起，历来通过 Pro、Max 和 Ultra 层级来扩展性能。英伟达的 Blackwell 架构于 2024 年推出，是 GPU AI 加速的一大进步，采用台积电 4NP 工艺，集成 2080 亿个晶体管。1.4 纳米节点（台积电 A14 或英特尔 A14）预计于 2028 年实现，将大幅提升晶体管密度和能效。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Blackwell_(microarchitecture)">Blackwell (microarchitecture) - Wikipedia</a></li>
<li><a href="https://www.nvidia.com/en-us/data-center/technologies/blackwell-architecture/">The Engine Behind AI Factories | NVIDIA Blackwell Architecture</a></li>
<li><a href="https://semiwiki.com/wikis/industry-wikis/tsmc-a14-process-technology-wiki/">TSMC A14 Process Technology Wiki - SemiWiki</a></li>

</ul>
</details>

**标签**: `#Apple`, `#AI chips`, `#Mac roadmap`, `#M7`, `#Nvidia`

---

<a id="item-6"></a>
## [从思维链到潜在推理](https://www.reddit.com/r/MachineLearning/comments/1uviru5/chain_of_thought_is_a_scaling_trap_the_next_wave/) ⭐️ 8.0/10

一个 Reddit 帖子指出，LLM 中的思维链（CoT）推理存在忠实度和成本问题，并提出下一个浪潮是 Coconut、HRM 和 RecursiveMAS 等潜在推理方法。 这一讨论凸显了 LLM 推理可能从冗长的文本痕迹转向高效的潜在空间计算的范式转变，对生产系统的成本、速度和可解释性具有重要影响。 帖子指出，像 Coconut 这样的潜在推理方法使用连续向量而非 token，HRM 将规划与执行分离，RecursiveMAS 在 agent 之间传递潜在嵌入，但这些方法引入了黑盒可视性问题。

reddit · r/MachineLearning · /u/meowsterpieces · 7月13日 17:50

**背景**: 思维链（Chain of Thought, CoT）提示让 LLM 生成自然语言的中间推理步骤，虽能提升性能，但会增加 token 成本并可能产生不忠实的痕迹。潜在推理方法旨在隐状态空间中进行推理，仅在最后输出语言。Coconut（连续思维链）是 Meta 提出的一种方法，HRM（分层推理模型）是一种具有深度计算深度的循环架构，RecursiveMAS 则扩展了多智能体间的潜在协作。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/sapientinc/HRM">GitHub - sapientinc/HRM: Hierarchical Reasoning Model ...</a></li>
<li><a href="https://arxiv.org/abs/2604.25917">[2604.25917] Recursive Multi-Agent Systems - arXiv.org Images RecursiveMAS · GitHub Recursive Multi-Agent Systems - arXiv.org RecursiveMAS Playground — Recursive Multi-Agent Systems in ... How RecursiveMAS speeds up multi-agent inference by 2.4x and ...</a></li>

</ul>
</details>

**标签**: `#Chain of Thought`, `#latent reasoning`, `#LLM reasoning`, `#faithfulness`, `#Coconut`

---

<a id="item-7"></a>
## [GPUHedge 将无服务器 GPU 冷启动延迟从 117 秒降至 30 秒](https://www.reddit.com/r/MachineLearning/comments/1uvlb6h/gpuhedge_hedging_serverless_gpu_providers/) ⭐️ 8.0/10

GPUHedge 是一个开源工具，通过在多个无服务器 GPU 提供商之间进行对冲，将 17 GB AI 模型冷启动的 p95 延迟从 116.6 秒降低到 29.4 秒。 冷启动延迟是无服务器 GPU 推理的关键痛点，通常导致请求耗时超过一分钟；该解决方案展示了显著的改进，并且是开源的，便于实际部署。 该工具实现了投机执行方法：它在主要提供商上启动请求，监控生命周期状态，并有条件地启动备用请求；第一个有效结果胜出，失败的作业通过提供商的本地 API 取消。

reddit · r/MachineLearning · /u/Putrid_Construction3 · 7月13日 19:20

**背景**: 无服务器 GPU 推理允许在不管理基础设施的情况下运行 AI 模型，但提供商存在冷启动问题——即模型在闲置后加载到 GPU 时的延迟。对冲是一种策略，向不同提供商发送多个冗余请求，并使用最快的响应，从而减少尾部延迟的影响。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://gpuhosted.com/en/serverless-gpu-inference-guide/">Serverless GPU Inference Guide (2026): Scale to Zero</a></li>
<li><a href="https://en.wikipedia.org/wiki/Speculative_execution">Speculative execution - Wikipedia</a></li>

</ul>
</details>

**标签**: `#serverless`, `#GPU inference`, `#cold start`, `#hedging`, `#open-source`

---

<a id="item-8"></a>
## [开源工具每日按研究兴趣过滤 arXiv 论文](https://www.reddit.com/r/MachineLearning/comments/1uvcdf7/hundreds_of_papers_hit_arxiv_every_day_and_maybe/) ⭐️ 8.0/10

一款名为 Research Radar 的新型开源工具每天获取所有新的 arXiv 论文，根据用户的研究兴趣对摘要进行评分，并通过两阶段 LLM 管道生成最相关论文的摘要。 研究人员在浏览无关论文上浪费大量时间；该工具通过可定制的兴趣文件和成本高效的模型自动过滤，每周可能节省数小时并提高相关工作的发现效率。 该工具使用两阶段评分系统：廉价模型对所有摘要进行评分（1-10 分），然后强模型对高分论文的完整 PDF 进行深度阅读并生成摘要。它支持多种后端，包括通过 Ollama/vLLM 的本地模型以及 Claude 等云 API。

reddit · r/MachineLearning · /u/usedtobreath · 7月13日 13:59

**背景**: arXiv 是一个预印本仓库，托管着物理学、数学、计算机科学等领域的数百万篇论文，每天有数百篇新提交。RSS 订阅可实现自动获取新论文列表。研究人员通常依赖手动浏览或流行通讯，但这些方法不能根据个人研究主题进行个性化定制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ArXiv">arXiv - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/RSS_feed">RSS feed</a></li>

</ul>
</details>

**标签**: `#arxiv`, `#paper filtering`, `#research tool`, `#open-source`, `#NLP`

---

<a id="item-9"></a>
## [在 Qwen3-4B 上评估 J-space 熵作为错误预测器](https://www.reddit.com/r/MachineLearning/comments/1uv5l75/evaluating_jspace_entropy_as_an_error_predictor/) ⭐️ 8.0/10

一项研究在 Qwen3-4B 上评估了源自 Jacobian Lens 的 J-space 熵作为错误预测器的效果，涉及七个数据集共约 11,400 个样本。 这项工作阐明了内部熵在 LLM 错误检测中的实际效用，表明它在事实性任务上可以补充输出置信度，但无法检测内化的错误观念，强调了任务依赖性。 评估使用了 Qwen3-4B，数据集包括 TriviaQA、PopQA、NQ-Open、TruthfulQA、HotpotQA、GSM8K 和 CommonSenseQA；在 TriviaQA 上校准的阈值在 GSM8K 上失败，因为正确的数学推理具有更高的基线熵，而且多项选择格式削弱了信号。

reddit · r/MachineLearning · /u/dasjomsyeet · 7月13日 08:27

**背景**: Jacobian Lens 是一种可解释性技术，通过将残差流向量线性投影到最终层基空间并经由模型的解嵌入解码，来读出内部激活倾向于让模型说出的内容。J-space 熵指的是在特定层从该透镜获得的词汇分布的熵，被假设为指示模型内部工作空间中的不确定性或错误。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/anthropics/jacobian-lens">GitHub - anthropics/jacobian-lens: Companion code for the ...</a></li>
<li><a href="https://explainx.ai/blog/what-is-j-lens-jacobian-lens-claude-interpretability-2026">What Is the J-Lens? Anthropic Jacobian Lens Guide - explainx.ai</a></li>
<li><a href="https://venturebeat.com/technology/anthropics-new-j-lens-reveals-a-silent-workspace-inside-claude-that-mirrors-a-leading-theory-of-consciousness">Anthropic's new "J-lens" reveals a silent workspace inside ...</a></li>

</ul>
</details>

**标签**: `#machine learning`, `#interpretability`, `#LLM`, `#error detection`, `#Jacobian Lens`

---

<a id="item-10"></a>
## [开源社区拯救了气候.gov 数据](https://werd.io/climate-gov-was-destroyed-open-data-saved-it/) ⭐️ 7.0/10

气候.gov 被关闭后，志愿者使用开放数据工具和 IPFS（星际文件系统）对其数据进行了存档，确保了公众对纳税人资助的气候信息的访问。 这一事件凸显了政府数据的脆弱性以及开放数据倡议在保护公共信息免受政治或行政变动影响方面的力量。 档案托管在 IPFS（一种去中心化的点对点文件系统）上，但该网站依赖捐款而非持续的政府资助。

hackernews · benwerd · 7月13日 19:57 · [社区讨论](https://news.ycombinator.com/item?id=48897945)

**背景**: IPFS 是一种使用内容寻址来唯一标识文件的分布式文件系统，实现去中心化的存储和检索。它旨在通过消除单点故障来创建更有弹性的网络。政府网站通常提供静态内容，可以从这种去中心化存档中受益。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/InterPlanetary_File_System">InterPlanetary File System - Wikipedia</a></li>
<li><a href="https://ipfs.tech/">IPFS: Building blocks for a better web | IPFS</a></li>

</ul>
</details>

**社区讨论**: 评论者讨论了政府数据是否应自动属于公共领域，并质疑基于捐款的保存的可持续性。有人提议政府网站应默认采用去中心化协议如 IPFS 来存储静态内容。

**标签**: `#open-data`, `#climate-data`, `#government-transparency`, `#data-preservation`, `#IPFS`

---

<a id="item-11"></a>
## [SEGA CD 版《Silpheed》视觉技巧技术深度解析](https://fabiensanglard.net/silpheed/index.html) ⭐️ 7.0/10

这篇深度分析揭示了突破 16 位硬件限制的巧妙工程解决方案，为对优化技术感兴趣的复古游戏开发者与爱好者提供了宝贵见解。 文章详细描述了《Silpheed》如何通过单个 CD 音轨运行，利用预渲染背景和缩放精灵模拟 3D 运动，同时在 SEGA CD 有限的硬件上保持流畅的游戏体验。

hackernews · ibobev · 7月13日 14:52 · [社区讨论](https://news.ycombinator.com/item?id=48893639)

**背景**: 全动态视频（FMV）指游戏中使用的预录视频片段，因 CD-ROM 存储而在 1990 年代初流行。精灵缩放是一种通过调整 2D 精灵大小来营造深度或运动感的技术，常用于 16 位主机游戏模拟 3D 效果。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.namu.wiki/w/FMV">FMV - NamuWiki</a></li>
<li><a href="https://www.youtube.com/watch?v=Pcd6K0RZDdo">Jurassic Park - 16 Bit Sprite Scaling Dino Action! - YouTube</a></li>

</ul>
</details>

**社区讨论**: 评论者对《Silpheed》的成就表示赞赏，有用户称其感觉像在控制一部电影。另一位评论者纠正了关于 SEGA CD 声音设置的细节，其他人则分享了类似硬件上令人印象深刻的演示链接。

**标签**: `#retro gaming`, `#sega cd`, `#game development`, `#technical deep-dive`, `#FMV`

---

<a id="item-12"></a>
## [DOOMQL：完全由 SQLite 驱动的类 Doom 游戏](https://simonwillison.net/2026/Jul/13/doomql/#atom-everything) ⭐️ 7.0/10

Peter Gostev 借助 GPT-5.6 Sol 构建了 DOOMQL，这是一款类 Doom 的第一人称射击游戏，其中 SQLite 负责所有游戏机制，包括移动、碰撞、敌人、战斗以及通过递归 CTE 光线追踪器进行的渲染，全部作为 Python 终端脚本运行。 DOOMQL 展示了将 SQLite 作为完整游戏引擎的极富创意且非传统的用法，挑战了传统游戏开发范式，并展示了 AI 辅助编程（GPT-5.6 Sol）在实验性项目中的潜力。 该游戏使用单个包含递归公用表表达式（CTE）的 SQL 查询来实现完整的射线追踪渲染。它被打包为一个可通过 `uv run` 运行的 Python 脚本，其底层的 SQLite 数据库可以使用 Datasette 进行交互式探索，并附带一个自定义 HTML/JS 应用以提供实时小地图。

rss · Simon Willison · 7月13日 22:34

**背景**: SQLite 是一个轻量级的嵌入式关系数据库，支持通过 CTE 进行递归查询。uv 是一个用 Rust 编写的高效 Python 包和项目管理器。GPT-5.6 Sol 是 OpenAI 于 2026 年 7 月发布的最强模型，专门用于长周期网络安全任务。该项目利用这些技术，突破了数据库应用的传统边界。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/previewing-gpt-5-6-sol/">Previewing GPT - 5 . 6 Sol : a next-generation model | OpenAI</a></li>
<li><a href="https://docs.astral.sh/uv/guides/scripts/">Running scripts | uv - Astral</a></li>

</ul>
</details>

**标签**: `#sqlite`, `#game-development`, `#python`, `#creative-coding`, `#doom`

---

<a id="item-13"></a>
## [字节跳动通过 Seed 世界模型团队探索自动驾驶](https://36kr.com/p/3893815451417347?f=rss) ⭐️ 7.0/10

据报道，字节跳动正探索自动驾驶领域，由 Seed 旗下周畅负责的世界模型团队主导，聚焦无人物流场景。但字节官方回应称没有做智能驾驶业务的计划。 字节的入局可能凭借其 AI 大模型、算力和人才优势颠覆自动驾驶行业格局。同时，自动驾驶被视为通往具身智能和物理 AI 的关键入口。 Seed 是字节 2023 年成立的一级战略部门。周畅管理多模态大模型、世界模型、视觉生成和具身智能等领域。火山引擎旗下已有汽车行业线，并与赛力斯合作。

rss · 36kr · 7月13日 08:34

**背景**: 世界模型是能够模拟物理动态（如物理规律、物体交互）的 AI 系统，对自动驾驶的预测与规划至关重要。物理 AI 和具身智能是当前趋势，自动驾驶被认为是其最早落地的商业场景之一。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/World_model_(artificial_intelligence)">World model (artificial intelligence) - Wikipedia</a></li>
<li><a href="https://arxiv.org/abs/2501.11260">[2501.11260] A Survey of World Models for Autonomous Driving [2606.03159] NVIDIA OmniDreams: Real-Time Generative World ... Awesome World Models for Autonomous Driving - GitHub Images Top Stories World model (artificial intelligence) - Wikipedia The Waymo World Model: A New Frontier For Autonomous Driving ... Bowen12137/Awesome-World-Models - GitHub World models new driver for auto autonomy - Chinadaily.com.cn</a></li>

</ul>
</details>

**标签**: `#ByteDance`, `#autonomous driving`, `#world model`, `#AI`, `#Seed`

---

<a id="item-14"></a>
## [Om AI 发布全球首个端侧原生流式多模态模型 VLX](https://36kr.com/p/3893445208717826?f=rss) ⭐️ 7.0/10

Om AI 发布了 VLX 系列，这是全球首个面向物理 AI 的端侧原生流式多模态模型，能够在端侧设备上实现持续的感知、定位和决策闭环。该模型以流式方式连续处理视频，而非离散的帧提取，从而实现自主实时响应。 这一进展意义重大，因为它将物理 AI 从云端架构转向端侧原生流式，实现了低延迟、隐私保护的自主系统。这可能加速在机器人、无人机、可穿戴设备和安防摄像头等领域的应用，弥合 AI 研究与实际部署之间的差距。 VLX 模型融合了三个相互依赖的能力层：Flow（持续感知）、Seek（精准定位）和 Go（行动决策），都在同一视频流上运行。Om AI 声称该模型已完成商业闭环，营收达数亿元，并在数百万个真实摄像头、无人机和机器人的数据上进行了训练。

rss · 36kr · 7月13日 02:39

**背景**: 物理 AI 指与物理世界交互并理解物理世界的 AI 系统，通常需要在端侧设备上进行实时处理。传统视频理解采用离线抽帧方式，而流式多模态模型无需等待查询即可连续处理视频。物理 AI 的其他方法包括 VLA（视觉-语言-动作模型）、世界模型和 JEPA（联合嵌入预测架构），各有侧重。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Vision–language–action_model">Vision–language–action model - Wikipedia</a></li>
<li><a href="https://www.turingpost.com/p/jepa">What is Joint Embedding Predictive Architecture (JEPA)?</a></li>
<li><a href="https://en.wikipedia.org/wiki/World_model_(artificial_intelligence)">World model (artificial intelligence)</a></li>

</ul>
</details>

**标签**: `#physical AI`, `#multi-modal model`, `#edge computing`, `#robotics`, `#video understanding`

---

<a id="item-15"></a>
## [零差云控完成数亿元 C++轮融资](https://36kr.com/p/3885232033378308?f=rss) ⭐️ 7.0/10

零差云控（深圳）科技股份有限公司，一家专注于人形机器人关节部件的公司，完成了由同创伟业领投的数亿元 C++轮融资，2025 年营收同比增长超过 100%。 这笔融资凸显了人形机器人行业从概念到生产的转变，关节等核心零部件的供应链瓶颈正变得至关重要。零差云控的模块化关节方案和营收增长表明，市场对可靠、可批量生产的零部件需求日益增长。 该公司的 eRob 系列关节模组相比行业标准，轴向长度减少 44%，重量降低超过 20%，采用自研编码器和驱动器。其目标是对抗人形设计的“不可能三角”：在灵活性、负载能力和类人尺寸之间取得平衡。

rss · 36kr · 7月13日 02:37

**背景**: 人形机器人需要紧凑、高扭矩的关节来模拟人类运动。集成关节模组将电机、减速机和传感器集成在一个单元中。行业目前面临灵巧性、力量与尺寸之间的权衡，零差云控通过模块化设计和精密制造来应对这一挑战。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Humanoid_robot">Humanoid robot - Wikipedia</a></li>
<li><a href="https://www.cubemars.com/categorys/robot-joint-module">Robot Joint Module – Precision & Flexible Motion for Robots</a></li>

</ul>
</details>

**标签**: `#Humanoid Robotics`, `#Robotics Components`, `#Venture Capital`, `#Supply Chain`, `#Chinese Tech`

---

<a id="item-16"></a>
## [英特尔追加 50 亿欧元投资爱尔兰扩大 AI 芯片产能](https://36kr.com/newsflashes/3894027379899655?f=rss) ⭐️ 7.0/10

英特尔宣布向爱尔兰莱克斯利普园区追加投资 50 亿欧元，用于扩大先进芯片制造能力，聚焦 Intel 3 制程节点，提升 Xeon 6 及下一代 Xeon 服务器处理器的产量，以满足 AI 和 HPC 需求。 此次投资凸显了英特尔重夺半导体制造领导地位的决心，并支撑 AI 和高性能计算芯片日益增长的需求。同时，它强化了英特尔的代工服务，使先进制节点对外部客户开放。 这 50 亿欧元将用于升级现有晶圆厂设施、安装先进制造设备并扩建自动化生产系统。Intel 3 是英特尔最后一代 FinFET 工艺节点，也是其“四年五个制程节点”计划的关键一环，提供 Intel 3-T、3-E、3-PT 等多个变体。

rss · 36kr · 7月13日 12:09

**背景**: Intel 3 是英特尔的一种半导体制程节点，提供多种金属布线层选项，也是首个对外开放代工的先进制程节点。Intel Xeon 6 是面向数据中心的服务器处理器家族。HPC（高性能计算）指利用超级计算机解决复杂计算问题。此次投资是英特尔扩大全球制造产能战略的一部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://baike.baidu.com/item/Intel+3/67443398">Intel 3 - 百度百科</a></li>
<li><a href="https://news.qq.com/rain/a/20240620A0ANPD00">Intel 3 制程详解：性能相比Intel 4 提升18%！_腾讯新闻</a></li>

</ul>
</details>

**标签**: `#AI`, `#Intel`, `#chip manufacturing`, `#investment`, `#Ireland`

---

<a id="item-17"></a>
## [阶跃星辰发布 STEPX 品牌、智能体系统 Step AOS 及 Neo 手机](https://36kr.com/newsflashes/3894017412726018?f=rss) ⭐️ 7.0/10

2026 年 7 月 13 日，阶跃星辰正式发布全球首个大模型原生 AI 终端品牌 STEPX，同步推出智能体原生操作系统 Step AOS 和智能体手机 STEPX Neo。 这标志着将大语言模型直接集成到消费硬件和操作系统中的重要一步，可能重塑用户与个人设备上 AI 智能体的交互方式。 STEPX Neo 被称为全球首款智能体手机，搭载 Step AOS 系统，该系统采用原子能力引擎来管理 AI 智能体。Step AOS 旨在原生支持智能体工作流，与传统移动操作系统不同。

rss · 36kr · 7月13日 11:59

**背景**: 智能体操作系统（agentic OS）协调 AI 智能体、工具和数据，实现自主任务执行。大模型原生终端将大语言模型直接嵌入设备核心，实现无缝 AI 集成。阶跃星辰是一家专注于大模型和智能体技术的中国 AI 公司。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.gizmochina.com/2026/07/13/chinese-ai-company-launches-worlds-first-agentic-smartphone/">StepX Neo launches as world's first agentic smartphone with new Step ...</a></li>
<li><a href="https://www.make.com/en/blog/agentic-operating-system">What Is an Agentic Operating System? 2026 Guide | Make</a></li>

</ul>
</details>

**标签**: `#AI`, `#Operating System`, `#Agentic`, `#Large Language Model`, `#Terminal`

---

<a id="item-18"></a>
## [关于 LLM 多样性的提示工程论文被 ICML 接收引发争议](https://www.reddit.com/r/MachineLearning/comments/1uv1xb3/promptengineering_paper_accepted_to_icml_r/) ⭐️ 7.0/10

一篇题为《Verbalized Sampling：如何缓解模式崩溃并释放 LLM 多样性》的论文被 ICML 2025 接收，提出一种简单的提示工程技术，以提高大型语言模型输出的多样性。 该论文被接收凸显了机器学习社区中关于提示工程工作是否应属于 ICML 等顶级会议的持续争论，可能重塑人们眼中严谨的 ML 研究的范畴。 这项名为'Verbalized Sampling'的技术据称可在不重新训练模型的情况下恢复高达 66%的输出多样性，但缺乏严格的理论分析。该论文被 ICML 接收表明，即使对于看似简单的方法，学术界也开始重视实证结果。

reddit · r/MachineLearning · /u/Mean_Revolution1490 · 7月13日 05:00

**背景**: 模式崩溃是生成模型中的一种故障模式，表现为输出缺乏多样性，常见于 GANs，但也与 LLMs 相关。提示工程涉及精心设计输入提示以引导模型行为。争论的焦点在于，这类实证驱动、理论较薄弱的工作是否达到顶级机器学习会议的标准。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mode_collapse">Mode collapse - Wikipedia</a></li>
<li><a href="https://www.analyticsvidhya.com/blog/2025/10/verbalized-sampling/">RIP Prompt Engineering: The New Skill is Verbalized Sampling</a></li>
<li><a href="https://www.forbes.com/sites/lanceeliot/2025/11/01/prompt-engineering-newest-technique-is-verbalized-sampling-that-stirs-ai-to-be-free-thinking-and-improve-your-responses/">Prompt Engineering Newest Technique Is Verbalized Sampling ...</a></li>

</ul>
</details>

**标签**: `#prompt-engineering`, `#ICML`, `#LLM diversity`, `#machine learning`, `#community debate`

---