---
layout: default
title: "Horizon Summary: 2026-07-25 (ZH)"
date: 2026-07-25
lang: zh
---

> 从 54 条内容中筛选出 17 条重要资讯。

---

1. [vLLM v0.26.0 发布：支持 Inkling 模型，优化 DeepSeek-V4 等](#item-1) ⭐️ 9.0/10
2. [Anthropic 发布 Claude Opus 5，以半价对标前沿模型](#item-2) ⭐️ 9.0/10
3. [三星与 SK 海力士拟携手美国科技巨头推进万亿美元芯片项目](#item-3) ⭐️ 9.0/10
4. [sglang v0.5.16 发布：支持 DSpark 推测解码和 Inkling 多模态模型](#item-4) ⭐️ 8.0/10
5. [Android 可能限制设备端 ADB，引发争议](#item-5) ⭐️ 8.0/10
6. [开放权重 AI 模型正在成为类似 Kubernetes 的平台](#item-6) ⭐️ 8.0/10
7. [AMD 2026 年 AI 战略挑战 CUDA 护城河](#item-7) ⭐️ 8.0/10
8. [SK 集团与英伟达达成超 5000 亿美元 AI 工厂与 HBM 合作](#item-8) ⭐️ 8.0/10
9. [中国发布离岸信托个税新规](#item-9) ⭐️ 8.0/10
10. [三星与博通签署 2000 亿美元半导体合作协议](#item-10) ⭐️ 7.0/10
11. [穆迪警告 AI 投资热潮冲击科技公司财务](#item-11) ⭐️ 7.0/10
12. [高通全线产品 9 月 1 日起涨价](#item-12) ⭐️ 7.0/10
13. [苹果游说特朗普用中国存储芯片，遭美光反对](#item-13) ⭐️ 7.0/10
14. [就业确定性主导高考志愿转向](#item-14) ⭐️ 7.0/10
15. [携程公布 19 项整改措施应对反垄断处罚](#item-15) ⭐️ 7.0/10
16. [AMD 确认 2028 年推出 Zen 7 EPYC 'Florence'，2030 年推出 Zen 8 'Ravenna'](#item-16) ⭐️ 7.0/10
17. [微软利用 TPM 芯片封堵盗版 Windows 激活](#item-17) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [vLLM v0.26.0 发布：支持 Inkling 模型，优化 DeepSeek-V4 等](https://github.com/vllm-project/vllm/releases/tag/v0.26.0) ⭐️ 9.0/10

vLLM 发布了 0.26.0 版本，包含来自 212 位贡献者的 411 次提交，引入了新的 Inkling 模型家族、显著的 DeepSeek-V4 性能改进、fp32 lm_head 支持、灵活的注意力后端，以及成熟的 KV 卸载和分层二级存储。此外，Rust 前端现在支持多模态视频和音频，Transformers 后端已更新至 5.13.0 并迁移了更多模型。 这一重大更新使 vLLM 成为支持新一代模型（如 1T 参数多模态 Inkling）的领先推理引擎，提供日零支持并优化性能。DeepSeek-V4 的优化在多家供应商上实现了显著的端到端加速，而每 KV 缓存组注意力后端选择等新功能提高了混合模型的灵活性，惠及整个大语言模型部署生态系统。 Inkling 模型家族包括分段式 CUDA 图支持、Hopper FA4 相对注意力、MTP=1 投机解码、LoRA 和标准 ModelOpt NVFP4 量化。DeepSeek-V4 获得了专门的路由内核（端到端 TPOT 提升 2.94%）、fused_topk_bias（内核加速 1.5–2 倍）以及冗余重复/复制移除（端到端 TPOT 提升 1.8%），此外还有 ROCm 和稀疏解码/预填充优化。fp32 lm_head 通过 head_dtype 启用，现在可按 KV 缓存组选择注意力后端，滑动窗口成为显式的后端能力。

github · khluu · 7月25日 10:38

**背景**: vLLM 是一个高性能的开源大语言模型推理和服务库，以其高效的 PagedAttention 和对多种硬件后端的支持而闻名。Inkling 模型由 Thinking Machines Lab 开发，是一个 1T 参数的多模态模型，接受文本、图像和音频输入，上下文长度可达 100 万，具有相对注意力、短卷积和共享专家汇等新颖架构组件。DeepSeek-V4 是 DeepSeek 的大型语言模型，vLLM 的优化旨在跨 NVIDIA、AMD 和 Intel XPU 平台降低延迟并提高吞吐量。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.vllm.ai/en/latest/api/vllm/models/inkling/">inkling - vLLM</a></li>
<li><a href="https://vllm.ai/blog/2026-07-15-inkling">TML Inkling on vLLM: Day-0 Support with Optimized Performance</a></li>
<li><a href="https://github.com/vllm-project/vllm/blob/main/vllm/models/inkling/nvidia/ops/fa4_rel_attention.py">vllm/vllm/models/inkling/nvidia/ops/fa4_rel_attention.py at ...</a></li>

</ul>
</details>

**标签**: `#vLLM`, `#LLM inference`, `#GPU optimization`, `#performance`, `#open-source`

---

<a id="item-2"></a>
## [Anthropic 发布 Claude Opus 5，以半价对标前沿模型](https://simonwillison.net/2026/Jul/24/introducing-claude-opus-5/#atom-everything) ⭐️ 9.0/10

Anthropic 发布了 Claude Opus 5，这是一个接近 Claude Fable 5 前沿智能水平但价格减半的新 AI 模型。它目前在 Artificial Analysis 排行榜上领先，甚至超过了 Fable 5。 此次发布大幅降低了接近前沿 AI 的成本，使开发者和企业更容易获得高级能力。同时加剧了 AI 模型市场的竞争，可能推动进一步创新和降价。 Claude Opus 5 的定价与其前代 Opus 4.8 相同，并提供快速模式（费用为基本模型的两倍）。它展现了主动行为：在无法直接查看图纸的情况下，自行编写计算机视觉管线从原始像素中提取几何信息并重建 3D 模型。

rss · Simon Willison · 7月24日 23:48

**背景**: Anthropic 的 Claude 模型按规模命名：Haiku、Sonnet 和 Opus，其中 Opus 是最大的。2026 年，Anthropic 推出了 Fable 和 Mythos 等额外模型，Fable 5 是能力最强且广泛发布的模型。Opus 5 介于 Opus 4.8 和 Fable 5 之间，在性能和成本之间取得了平衡。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://llm-stats.com/benchmarks/artificial-analysis">Artificial Analysis Leaderboard - llm-stats.com</a></li>
<li><a href="https://platform.claude.com/docs/en/about-claude/models/overview">Models overview - Claude Platform Docs</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_(AI)">Claude (AI) - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: Boris Cherny 指出，根据系统卡评估和红队测试，Opus 5 是目前最难被提示注入的模型之一，这是一项有前途的安全改进。社区整体反响积极，对其主动能力和有竞争力的定价感到兴奋。

**标签**: `#AI`, `#Anthropic`, `#Claude`, `#language model`, `#machine learning`

---

<a id="item-3"></a>
## [三星与 SK 海力士拟携手美国科技巨头推进万亿美元芯片项目](https://36kr.com/newsflashes/3910551543289216?f=rss) ⭐️ 9.0/10

据韩国总统顾问消息，三星电子和 SK 海力士将与美国科技巨头推进一项规模达 1375 万亿韩元（约合 1 万亿美元）的芯片合作项目。 这一史无前例的投资规模可能重塑全球半导体供应链，并巩固韩美技术联盟，对从人工智能到消费电子等产业产生深远影响。 该项目涉及全球两大内存芯片制造商以及未指明的美国科技巨头，但具体范围和时间表尚未公布。这一金额是半导体领域有史以来最大的联合投资之一。

rss · 36kr · 7月25日 06:11

**背景**: 半导体是现代电子产品的关键组件，内存芯片（如 DRAM 和 NAND）对智能手机到数据中心等设备至关重要。韩国的三星和 SK 海力士主导全球内存市场，与美国公司的合作旨在在地缘政治紧张时期确保供应链安全。

**标签**: `#semiconductor`, `#Samsung`, `#SK Hynix`, `#investment`, `#Korea-US cooperation`

---

<a id="item-4"></a>
## [sglang v0.5.16 发布：支持 DSpark 推测解码和 Inkling 多模态模型](https://github.com/sgl-project/sglang/releases/tag/v0.5.16) ⭐️ 8.0/10

sglang v0.5.16 引入了 DSpark，一种新颖的基于置信度的推测解码算法，在 DeepSeek-V4-Pro 上达到 383.7 tok/s 的吞吐量，并增加了对 Inkling（一个 975B 参数、1M token 上下文的多模态 MoE 模型）的支持。该版本还包括其他模型支持、性能优化和基础设施改进。 DSpark 通过自适应验证为大型语言模型服务提供了显著的吞吐量提升，而对 Inkling 的支持则使得高效部署具有百万 token 上下文的先进多模态 MoE 成为可能。这些特性使 sglang 成为面向纯文本和多模态 AI 工作负载的领先推理引擎。 DSpark 在 DeepSeek-V4-Pro（TP8，B300）上达到约 5 的接受长度，吞吐量 383.7 tok/s。Inkling 在 Blackwell 硬件上输入吞吐量高达 71.7k tok/s，每用户解码 171.0 tok/s。该版本还移除了实验性的 QServe 和 FBGEMM FP8 量化路径，并将 UnifiedRadixTree 设为 SWA、Mamba 和 DSA 模型的默认实现。

github · Qiaolin-Yu · 7月25日 00:13

**背景**: 推测解码通过使用较小的草稿模型生成候选 token，再由较大的目标模型并行验证，从而加速 LLM 推理。像 Inkling 这样的多模态 MoE 模型结合了多种模态（文本、图像、音频）和专家混合架构以实现高效扩展。sglang 是一个开源 LLM 服务框架，针对高吞吐量和低延迟进行了优化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2607.05147">[2607.05147] DSpark: Confidence-Scheduled Speculative ...</a></li>
<li><a href="https://thinkingmachines.ai/news/introducing-inkling/">Inkling: Our Open-Weights Model - Thinking Machines Lab</a></li>
<li><a href="https://huggingface.co/nm-testing/nvfp4_moe-e2e/tree/main">nm-testing/ nvfp 4 _ moe -e2e at main</a></li>

</ul>
</details>

**标签**: `#LLM inference`, `#speculative decoding`, `#sglang`, `#AI infrastructure`, `#multimodal`

---

<a id="item-5"></a>
## [Android 可能限制设备端 ADB，引发争议](https://kitsumed.github.io/blog/posts/android-may-soon-restrict-on-device-adb/) ⭐️ 8.0/10

Android 可能很快限制设备端 ADB（Android 调试桥）的访问权限，这一变化引发了开发者的激烈讨论。该提议将限制 ADB 仅用于授权主机或特定网络，可能破坏现有工作流程。 这一变化可能严重影响依赖 ADB 进行应用开发、测试和调试的开发者。它凸显了安全改进与开发者控制之间的持续紧张关系，可能迫使开发者采用新的工作流程或面临限制。 攻击向量需要同时启用开发者选项和远程 ADB，仅影响约 0.1%的用户。提议的限制允许开发者将 ADB 限制到特定 IP 地址或接口，例如 Tailscale 等 VPN。

hackernews · shscs911 · 7月25日 06:57 · [社区讨论](https://news.ycombinator.com/item?id=49045159)

**背景**: ADB（Android 调试桥）是一个用于调试 Android 设备的命令行工具，允许开发者安装应用、运行 shell 命令和访问日志。它通过开发者选项启用，并需要用户明确授权。多年来，ADB 在某些攻击中被利用，导致了加强安全性的呼声。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://developer.android.com/tools/adb">Android Debug Bridge (adb) | Android Studio | Android Developers</a></li>
<li><a href="https://www.howtogeek.com/125769/how-to-install-and-use-abd-the-android-debug-bridge-utility/">How to Install and Use ADB, the Android Debug Bridge Utility</a></li>
<li><a href="https://lifetips.alibaba.com/tech-efficiency/is-usb-debugging-risky-the-truth-about-android-adb-safety">Is USB Debugging Risky? The Truth About Android ADB Safety</a></li>

</ul>
</details>

**社区讨论**: 评论显示反应不一：一些开发者认为这种限制反应过度，因为攻击向量对大多数用户来说不现实；而另一些人则认为这是必要的安全措施，甚至是谷歌加强对设备控制的前奏。少数人建议采取更细致的方案，比如将 ADB 限制到特定网络，而提议似乎包含了这一点。

**标签**: `#Android`, `#ADB`, `#security`, `#developer tools`

---

<a id="item-6"></a>
## [开放权重 AI 模型正在成为类似 Kubernetes 的平台](https://tobi.knaup.me/2026-07-25-open-weight-ai-is-having-its-kubernetes-moment/) ⭐️ 8.0/10

文章认为，开放权重 AI 模型正在成为 AI 领域的主导平台，类似于 Kubernetes 成为容器编排的标准，对地缘政治、定价和创新产生影响。 这一转变可能使 AI 开发民主化，防止供应商锁定，并为推理成本提供基准，同时也引发了对模型来源和监管的地缘政治担忧。 文章借用 Kubernetes 的类比强调，一旦开放平台成为行业重心，任何单一供应商都无法匹敌联合创新速度。社区评论还讨论了按来源禁止模型的可行性以及“tokenomics”定价的波动性。

hackernews · tknaup · 7月25日 14:49 · [社区讨论](https://news.ycombinator.com/item?id=49048034)

**背景**: 开放权重 AI 模型是其内部参数（权重）公开可用的模型，允许任何人下载、修改和部署。这不同于 OpenAI 的 GPT-4 等封闭模型，后者只提供 API 访问。“Tokenomics”指的是 AI 中 token 使用的经济学，包括定价和供应动态。Kubernetes 时刻指的是开源平台成为事实标准的转折点，推动生态系统发展。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/open-weight-ai-what-we-finally-opened-bonnet-nicolas-pistorio-n3ulf">Open - weight AI : what if we finally opened the bonnet ?</a></li>
<li><a href="https://www.microsoft.com/en-us/corporate-responsibility/topics/open-weight/">Open Weights and American AI Leadership</a></li>
<li><a href="https://en.wikipedia.org/wiki/Tokenomics">Tokenomics - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区成员争论按来源（例如中国模型）禁止模型的可行性，指出权重只是数字，无法追踪到国家。其他人赞扬开放平台在创新上超越单一供应商的见解，并批评 tokenomics 定价的不透明性，认为开放权重模型为成本提供了合理基准。

**标签**: `#open-weight`, `#AI models`, `#Kubernetes`, `#tokenomics`, `#open source`

---

<a id="item-7"></a>
## [AMD 2026 年 AI 战略挑战 CUDA 护城河](https://newsletter.semianalysis.com/p/can-amd-break-the-cuda-moat-amd-advancing) ⭐️ 8.0/10

SemiAnalysis 发表深度分析，探讨 AMD 如何通过自主核生成改进软件、应对 Helios MI455X 的量产挑战，并利用金融工程提供高达 105% 的折扣来与 NVIDIA 的 CUDA 生态系统竞争。 若 AMD 成功，可能削弱 NVIDIA 在 AI 计算领域的垄断地位，降低客户成本，并加速 AI 硬件与软件的创新。其结果将影响整个 AI 行业的基础设施选择。 自主核生成利用 LLM 智能体自动生成和优化 GPU 内核，这是关键的软件差异化优势。Helios MI455X 系统配备 72 块 GPU 和 31 TB HBM4 内存，但互连带宽仅为 896 GB/s，远低于 NVIDIA NVLink 6 的 3.6 TB/s。AMD 的金融工程已提供高达 105% 的折扣以赢得订单。

rss · Semianalysis · 7月25日 00:33

**背景**: CUDA 是 NVIDIA 的专有并行计算平台，已成为 AI 工作负载的事实标准，形成了锁定开发者的护城河。AMD 的 ROCm 是开源替代方案，但历史上存在软件质量和生态差距。自主核生成旨在自动化编写优化计算内核的繁琐手工过程，可能让 AMD 硬件更易编程。金融工程涉及激进的定价策略，例如大幅折扣以吸引 NVIDIA 客户。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/agentic-kernel-generation">Agentic Kernel Generation</a></li>
<li><a href="https://www.servethehome.com/amds-epyc-venice-instinct-mi455x-helios-hardware-on-display-for-first-time-at-ces-2026/">AMD’s EPYC Venice, Instinct MI 455 X , & Helios ... - ServeTheHome</a></li>
<li><a href="https://en.wikipedia.org/wiki/Finance_Engineering">Finance Engineering</a></li>

</ul>
</details>

**标签**: `#AMD`, `#CUDA`, `#GPU`, `#AI hardware`, `#software ecosystem`

---

<a id="item-8"></a>
## [SK 集团与英伟达达成超 5000 亿美元 AI 工厂与 HBM 合作](https://36kr.com/newsflashes/3910690882507907?f=rss) ⭐️ 8.0/10

SK 集团与英伟达宣布一项价值超过 5000 亿美元的战略合作，旨在建设 AI 工厂并开发下一代 HBM 内存。SK 电信将建设 2 吉瓦的 NVIDIA Vera Rubin DSX AI 工厂，SK 海力士将与英伟达共同开发包括 HBM 在内的下一代 AI 内存解决方案。 此次合作大幅扩展了 AI 基础设施容量，并确保了先进 HBM 内存的长期供应，这对于训练大型语言模型以及驱动代理 AI 和物理 AI 至关重要。投资规模突显了行业对集成 AI 工厂设计和高带宽内存的迫切需求，以满足全球飙升的计算需求。 SK 电信的 2 吉瓦 AI 工厂将采用 NVIDIA Vera Rubin DSX 参考设计，该设计提供了构建协同设计 AI 基础设施的蓝图，以实现每瓦特最大令牌数。该合作还正式确立了在 HBM 内存（可能包括 HBM4 及更先进的技术）上的长期协作，以满足从 LLM 训练到代理 AI 和物理 AI 等不断变化的工作负载需求。

rss · 36kr · 7月25日 06:40

**背景**: AI 工厂是专为加速 AI 工作负载而建造的大型数据中心，集成了优化的计算、网络和冷却。高带宽内存（HBM）是 AI 加速器的关键组件，在内存和 GPU 芯片之间提供高速数据访问；每一代（例如 HBM3、HBM4）的吞吐量大致翻倍，以跟上不断增长的模型规模。NVIDIA 的 Vera Rubin DSX 是一种参考架构，致力于标准化 AI 工厂设计，从而实现更快的部署和更高的效率。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://nvidianews.nvidia.com/news/nvidia-releases-vera-rubin-dsx-ai-factory-reference-design-and-omniverse-dsx-digital-twin-blueprint-with-broad-industry-support">NVIDIA Releases Vera Rubin DSX AI Factory Reference Design and Omniverse DSX Digital Twin Blueprint With Broad Industry Support | NVIDIA Newsroom</a></li>
<li><a href="https://en.wikipedia.org/wiki/High_Bandwidth_Memory">High Bandwidth Memory - Wikipedia</a></li>
<li><a href="https://newsletter.semianalysis.com/p/scaling-the-memory-wall-the-rise-and-roadmap-of-hbm">Scaling the Memory Wall: The Rise and Roadmap of HBM</a></li>

</ul>
</details>

**标签**: `#AI`, `#NVIDIA`, `#HBM`, `#AI infrastructure`, `#partnership`

---

<a id="item-9"></a>
## [中国发布离岸信托个税新规](https://liaoning.chinatax.gov.cn/art/2026/7/24/art_5869_7823.html) ⭐️ 8.0/10

2026 年 7 月 24 日，财政部和税务总局发布第 21 号公告，要求居民个人每年申报并缴纳离岸信托的财产装入和所有收益的税款，无论是否实际分配。 此项规定封堵了以往离岸信托收益不分配就不征税的避税路径，对中国高净值人群产生重大影响，并加强了离岸架构的税务合规。 所有收益按增值额（市场价值减去原值和成本）统一适用 20%税率。追溯规则适用于 2023 年至 2025 年间的装入和 2026 年前的收益，须在 90 日内申报补缴且不加收滞纳金。

telegram · zaihuapd · 7月25日 00:31

**背景**: 离岸信托是指在离岸属地设立的信托，常被用于资产保护和税务规划。新规采用穿透式征税原则，无视信托实体，直接对居民个人的所有增值征税，消除了以往递延纳税的优势。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://baike.baidu.com/item/离岸信托/2652314">离岸信托_百度百科</a></li>
<li><a href="https://zh.wikipedia.org/zh-cn/境外信託">境外信托 - 维基百科，自由的百科全书</a></li>
<li><a href="https://www.zhihu.com/question/374224709">税收穿透是什么意思？有什么实际应用吗？ - 知乎</a></li>

</ul>
</details>

**标签**: `#tax regulation`, `#offshore trust`, `#China`, `#individual income tax`, `#compliance`

---

<a id="item-10"></a>
## [三星与博通签署 2000 亿美元半导体合作协议](https://36kr.com/newsflashes/3910562246645128?f=rss) ⭐️ 7.0/10

据报道，三星电子与博通签署了一份价值 2000 亿美元的半导体供应合作协议，该消息由第一财经发布。 此次合作凸显了半导体供应链稳定性的日益重要性，并可能对全球芯片生产和定价产生重大影响。 该协议价值 2000 亿美元，是半导体行业规模最大的协议之一；然而，具体条款及涵盖的产品尚未披露。

rss · 36kr · 7月25日 06:15

**背景**: 三星电子是全球最大的存储器芯片制造商及领先的半导体代工厂，而博通是网络和宽带芯片的主要供应商。这项长期供应协议预计将确保博通的关键组件供应，并巩固三星的客户基础。

**标签**: `#Semiconductor`, `#Business`, `#Samsung`, `#Broadcom`, `#Supply Chain`

---

<a id="item-11"></a>
## [穆迪警告 AI 投资热潮冲击科技公司财务](https://36kr.com/newsflashes/3910433082545536?f=rss) ⭐️ 7.0/10

穆迪发布研究报告警告称，AI 投资热潮正在侵蚀包括微软、亚马逊、Alphabet、Meta、甲骨文和 CoreWeave 在内的六家主要科技公司的自由现金流，并推高其资产负债表风险。 这一来自主要评级机构的警告标志着科技行业从'轻资产'模式向'重资产'模式的重大转变，可能影响投资者信心和行业长期财务稳定性。 这六家公司正从依赖软件和云服务转向大规模建设数据中心基础设施，需要巨额资本支出。穆迪指出，未来投资者将密切关注这些公司能否从 AI 投资中获得足够回报。

rss · 36kr · 7月25日 03:00

**背景**: 穆迪评级是一家评估公司信用的信用评级机构。自由现金流衡量公司扣除资本支出后产生的现金，是财务健康的关键指标。向'重资产'模式转变意味着公司必须大力投资于数据中心等物理资产，这可能会给现金流带来压力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/CoreWeave">CoreWeave</a></li>

</ul>
</details>

**标签**: `#AI investment`, `#financial risk`, `#tech industry`, `#Moody's`, `#free cash flow`

---

<a id="item-12"></a>
## [高通全线产品 9 月 1 日起涨价](https://tw.news.yahoo.com/%E7%8D%A8%E5%AE%B6-%E9%AB%98%E9%80%9A%E6%BC%B2%E5%83%B9%E4%BF%A1%E6%9B%9D%E5%85%89-%E5%85%A8%E7%B7%9A%E7%94%A2%E5%93%819-1%E8%B5%B7%E8%AA%BF%E6%BC%B2-%E7%9B%B4%E8%A8%80-142730846.html) ⭐️ 7.0/10

高通于 2026 年 7 月 24 日向客户发出价格调整通知信，宣布自 2026 年 9 月 1 日起对全线产品调涨价格，原因是制造成本上升和 AI 需求带来的产能压力。 此次全线涨价波及手机、PC、物联网和汽车等领域采用高通芯片的产品，可能导致消费电子终端价格上涨，并挤压下游制造商的利润空间。 信中未公布统一涨幅和具体产品型号，客户经理将逐一联系客户提供新报价，部分已下单但排期在 9 月后出货的订单也可能被重新报价。

telegram · zaihuapd · 7月25日 03:01

**背景**: 高通是一家领先的无晶圆半导体公司，为移动设备、汽车和无线基础设施提供芯片。该公司指出，晶圆制造、封装测试、先进封装和基板材料成本持续上升，加上 AI 和数据中心需求激增导致供应链产能紧张。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://zh.wikipedia.org/wiki/先进封装">先进封装 - 维基百科，自由的百科全书</a></li>
<li><a href="https://www.baogaobox.com/insights/260131000025282.html">2026年先进封装行业深度分析：全球先进封装占封装市场55%，2024-2030...</a></li>
<li><a href="https://www.jiuyangongshe.com/a/3y1m5jk1ayv">半 导 体 材 料 核心AI梳理</a></li>

</ul>
</details>

**标签**: `#芯片涨价`, `#高通`, `#供应链`, `#AI需求`, `#半导体`

---

<a id="item-13"></a>
## [苹果游说特朗普用中国存储芯片，遭美光反对](https://www.wsj.com/tech/trump-apple-micron-china-chips-784bbd3d) ⭐️ 7.0/10

苹果正在游说特朗普政府，允许其在销往美国以外的产品中使用中国长鑫存储（CXMT）和长江存储（YMTC）生产的存储芯片，但美光科技正在积极阻挠这一举措。 这凸显了半导体供应链中企业利益与地缘政治的复杂交织，可能影响苹果的成本结构以及存储芯片的竞争格局。 近几周，苹果 CEO 库克及其他高管已向总统特朗普等官员推销该计划，旨在为非美国市场采购长鑫存储的 DRAM 和长江存储的 NAND 闪存。

telegram · zaihuapd · 7月25日 04:02

**背景**: 长鑫存储（CXMT）是一家总部位于合肥的中国 DRAM 制造商，而长江存储（YMTC）专注于 3D NAND 闪存，以其 Xtacking 技术闻名。两者都是中国发展本土半导体能力的一部分，但面临美国出口限制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ChangXin_Memory_Technologies">ChangXin Memory Technologies - Wikipedia</a></li>
<li><a href="https://zh.wikipedia.org/wiki/长鑫存储">长鑫存储 - 维基百科，自由的百科全书</a></li>

</ul>
</details>

**标签**: `#Apple`, `#Micron`, `#semiconductor`, `#geopolitics`, `#supply chain`

---

<a id="item-14"></a>
## [就业确定性主导高考志愿转向](https://www.caixin.com/2026-07-17/102464976.html) ⭐️ 7.0/10

2026 年中国高考录取中，军警院校、公费师范等就业有保障的专业投档线大幅攀升，而普通五年制临床医学因就业门槛提高而遇冷。 这一趋势反映出家庭和学生的风险规避情绪加剧，将重塑人才供给，并可能影响医疗、教育等关键领域的长期人力分布。 公安大学及地方警校招录门槛显著提升；公费师范生政策新增本研衔接培养通道。同时，临床医学长学制及定向兽医专业逆势走强。

telegram · zaihuapd · 7月25日 04:49

**背景**: 中国高考竞争激烈，学生常根据就业前景选择专业。近期政策包括公费师范生本研衔接培养以提升质量，而医疗改革如 DRG/DIP 支付和药品耗材集采降低了医生收入预期。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://yz.chsi.com.cn/kyzx/jybzc/202406/20240617/2293296999.html">yz.chsi.com.cn/kyzx/jybzc/202406/20240617/2293296999.html</a></li>
<li><a href="https://www.163.com/dy/article/JSPMISF70514CG7L.html">163.com/dy/article/JSPMISF70514CG7L.html</a></li>

</ul>
</details>

**标签**: `#education`, `#employment`, `#China`, `#college admissions`, `#job security`

---

<a id="item-15"></a>
## [携程公布 19 项整改措施应对反垄断处罚](https://mp.weixin.qq.com/s/6pfOO4iorcdUFb2zLNhFSw) ⭐️ 7.0/10

2026 年 7 月 25 日，携程在被国家市场监督管理总局处罚后，公布了 19 项整改措施，包括终止独家合作和取消'全网最低价'要求。 这标志着中国平台经济领域重要的反垄断执法行动，迫使一家大型在线旅游平台改革限制竞争的商业实践。 关键措施包括废除'一级委托分销（特牌）'独家合作模式，取消'智选特惠'等促销类别，以及终止强制性'全网最低价'要求。

telegram · zaihuapd · 7月25日 11:56

**背景**: 携程是中国领先的在线旅游平台。国家市场监督管理总局认定其滥用市场支配地位，强制要求独家合作并施加不公平条件。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.163.com/dy/article/L2MNPNAN0550LJ66.html">刚刚 | 携程公布十九项整改措施！| 分 销 |经营|反垄断_网易订阅</a></li>
<li><a href="https://k.sina.com.cn/article_7879995939_1d5af322301901fdie.html?from=news">刚刚， 携 程 公布19... | 新浪网</a></li>
<li><a href="https://news.ifeng.com/c/8v35qLWztEm">停止、下线、取消、退还……被重罚后携程宣布整改_凤凰网</a></li>

</ul>
</details>

**标签**: `#antitrust`, `#regulatory`, `#China`, `#travel`, `#platform economy`

---

<a id="item-16"></a>
## [AMD 确认 2028 年推出 Zen 7 EPYC 'Florence'，2030 年推出 Zen 8 'Ravenna'](https://www.techspot.com/news/113233-amd-confirms-zen-7-epyc-florence-2028-previews.html) ⭐️ 7.0/10

AMD 正式确认，基于 Zen 7 架构的第七代 EPYC 服务器处理器“Florence”将于 2028 年推出，随后基于 Zen 8 的第八代 EPYC “Ravenna” 计划在 2030 年登场。 这条长期路线图清晰展示了 AMD 的服务器战略布局，帮助数据中心和云服务商提前进行基础设施投资规划，同时也加剧了与 Intel 未来至强平台的竞争。 Florence 将配备标准 Zen 7 核心和面向高密度计算的 Zen 7c 核心，支持新型 MRDIMM 和 LPDDR 内存，并包含 AI 计算扩展。它将兼容新的 SP7 和 SP8 平台，用于下一代“Ferrara”AI 机架系统。

telegram · zaihuapd · 7月25日 14:05

**背景**: AMD 的 EPYC 处理器是面向数据中心的服务器 CPU，与 Intel 的至强系列竞争。Zen 架构是 AMD 的核心微架构；'c' 版本（如 Zen 7c）针对高核心数和低功耗进行了优化。MRDIMM（多路复用列 DIMM）是一种通过跨多个列交织数据来提高带宽的内存技术。SP7 和 SP8 平台是即将推出的 EPYC CPU 插槽设计，其中 SP7 用于高端服务器，SP8 用于入门级。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://lenovopress.lenovo.com/lp2028-introduction-to-mrdimm-memory-technology">Introduction to MRDIMM Memory Technology > Lenovo Press</a></li>
<li><a href="https://wccftech.com/amd-sp7-sp8-platforms-epyc-venice-verano-cpus-12800-mtps-16-channel-memory-128-pcie-6-0-lanes/">AMD SP7 & SP8 Platforms For Next-Gen EPYC ... - Wccftech</a></li>

</ul>
</details>

**标签**: `#AMD`, `#Zen`, `#server processors`, `#EPYC`, `#roadmap`

---

<a id="item-17"></a>
## [微软利用 TPM 芯片封堵盗版 Windows 激活](https://www.techspot.com/news/113232-microsoft-using-tpm-chips-crack-down-pirated-windows.html) ⭐️ 7.0/10

微软正在为其密钥管理服务（KMS）增加基于 TPM 芯片的硬件验证，以阻止盗版 Windows 激活。新的“TPM 证明”机制将从下一版 Windows Server 起成为强制要求，并自 2026 年 8 月起在 Windows Server 2025 中推送准备提示。 此举通过将激活与硬件信任绑定，显著加强了微软的反盗版措施，可能使许多现有的基于 KMS 的盗版激活工具失效。系统管理员和企业授权管理者需为这一变化做好准备，以避免激活中断。 TPM 证明要求 KMS 服务器的硬件身份先经微软认证且未被篡改，之后才允许处理批量激活请求。微软此前已在 2025 年封堵了 KMS38 离线激活漏洞，新 TPM 措施可能对抗 Massgrave 组织的 Online KMS 方法，尽管他们新推出的 TSforge 工具声称可绕过整个 DRM 激活架构。

telegram · zaihuapd · 7月25日 15:55

**背景**: KMS（密钥管理服务）是微软用于批量授权的技术，允许组织使用内部服务器激活 Windows 和 Office 产品。盗版激活工具常通过设置伪造的 KMS 服务器来响应激活请求进行利用。TPM（可信平台模块）是一种硬件安全芯片，提供安全的加密操作并能证明系统的完整性。通过要求 TPM 证明，微软旨在确保只有正版 KMS 服务器才能授权激活。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://learn.microsoft.com/en-us/windows-server/get-started/kms-client-activation-keys">Key Management Services (KMS) client activation and product ...</a></li>
<li><a href="https://massgrave.dev/tsforge">TSforge Activation | MAS - Microsoft Activation Scripts</a></li>
<li><a href="https://www.wincert.net/cast/microsoft-shuts-down-the-kms38-offline-activation-workaround/">Microsoft shuts down the KMS38 offline activation workaround</a></li>

</ul>
</details>

**标签**: `#Windows`, `#Security`, `#TPM`, `#Piracy`, `#KMS`

---