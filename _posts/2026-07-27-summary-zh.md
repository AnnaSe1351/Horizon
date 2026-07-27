---
layout: default
title: "Horizon Summary: 2026-07-27 (ZH)"
date: 2026-07-27
lang: zh
---

> 从 73 条内容中筛选出 24 条重要资讯。

---

1. [月之暗面开源 Kimi K3：首个 2.8 万亿参数模型](#item-1) ⭐️ 9.0/10
2. [中国开始量产国产 DUV 光刻机](#item-2) ⭐️ 9.0/10
3. [vLLM v0.26.0 发布，支持新模型族和 DeepSeek-V4 优化](#item-3) ⭐️ 8.0/10
4. [Anthropic 澄清对开放权重模型的立场](#item-4) ⭐️ 8.0/10
5. [Libsm64 将超级马里奥 64 转化为可复用库](#item-5) ⭐️ 8.0/10
6. [Bun 的 Rust 重写版本已在 Claude Code 中发布，公开版本推迟](#item-6) ⭐️ 8.0/10
7. [小米 MiMo-V2.5 登 OpenRouter 双榜第一](#item-7) ⭐️ 8.0/10
8. [个人评测 6 大前沿 LLM 发现左倾偏见](#item-8) ⭐️ 8.0/10
9. [Fastjson2 曝未修复的远程代码执行漏洞](#item-9) ⭐️ 8.0/10
10. [法官驳回谷歌利用 DMCA 阻止爬取搜索结果的企图](#item-10) ⭐️ 7.0/10
11. [论坛项目弃用 React 改用 HTMX，引发讨论](#item-11) ⭐️ 7.0/10
12. [Paged Out #9：免费黑客杂志发布](#item-12) ⭐️ 7.0/10
13. [现代电子邮件可通过借用现有组件构建](#item-13) ⭐️ 7.0/10
14. [Ethan Mollick 的 AI 工具指南转向代理系统](#item-14) ⭐️ 7.0/10
15. [清华博士创业公司获数千万元融资，研发航空氢燃料电池](#item-15) ⭐️ 7.0/10
16. [2026 年资本转向 AI 应用商业化质量](#item-16) ⭐️ 7.0/10
17. [全球最大 eVTOL 货运无人机 AT8000 机身下线](#item-17) ⭐️ 7.0/10
18. [‘数字空间一号’试验星工程启动，构建 AI 太空大脑](#item-18) ⭐️ 7.0/10
19. [携程被罚 51.79 亿；长鑫科技上市；日本承认中国人形机器人领先](#item-19) ⭐️ 7.0/10
20. [从头构建 Transformer：英译泰米尔语翻译教程](#item-20) ⭐️ 7.0/10
21. [提出训练前数据确定性审计门控](#item-21) ⭐️ 7.0/10
22. [谷歌 Gemini 4：最具雄心的预训练，预计 2026 年底发布](#item-22) ⭐️ 7.0/10
23. [阿里推出“千问办公”AI 办公平台](#item-23) ⭐️ 7.0/10
24. [中方驳美方制裁威胁：模型蒸馏是行业惯例](#item-24) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [月之暗面开源 Kimi K3：首个 2.8 万亿参数模型](https://huggingface.co/moonshotai/Kimi-K3) ⭐️ 9.0/10

月之暗面在 HuggingFace 上开源了 Kimi K3 模型，总参数量达 2.8 万亿，激活参数 104B，在多项基准测试中取得顶尖表现。该模型采用了 Kimi Delta Attention（KDA）和 Attention Residuals（AttnRes）等全新架构，基于 Stable LatentMoE 框架构建。 Kimi K3 是首个开源的 3T 级别参数模型，是开源 AI 领域的重要里程碑。它缩小了与 GPT-5.6 Sol、Claude Fable 5 等专有前沿模型的差距，为研发社区提供了强大且可部署的替代方案。 该模型采用 896 个专家，每 token 激活 16 个，扩展效率较 Kimi K2 提升约 2.5 倍。原生支持文本、图像和视频理解，上下文窗口达 100 万 token，并支持 MXFP4 量化以实现高效部署。

telegram · zaihuapd · 7月27日 15:15

**背景**: Kimi K3 基于混合专家（MoE）架构构建，该架构每 token 仅激活部分参数，以平衡性能与效率。Kimi Delta Attention（KDA）是一种高效的线性注意力机制，扩展了 Gated DeltaNet；Attention Residuals（AttnRes）允许各层通过学习的注意力权重选择性聚合前层信息。Stable LatentMoE 引入了潜在空间路由和分位数平衡，以实现稳定的专家利用率。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2510.26692">[2510.26692] Kimi Linear: An Expressive, Efficient Attention Architecture</a></li>
<li><a href="https://www.kimi.com/blog/kimi-k3">Kimi K3 Tech Blog: Open Frontier Intelligence</a></li>

</ul>
</details>

**标签**: `#open-source`, `#large language model`, `#Moonshot AI`, `#Mixture of Experts`, `#AI breakthrough`

---

<a id="item-2"></a>
## [中国开始量产国产 DUV 光刻机](https://www.theinformation.com/articles/china-starts-mass-producing-homegrown-duv-chipmaking-tools-advance-local-chip-industry) ⭐️ 9.0/10

中国已开始大规模生产自主研发的浸没式深紫外（DUV）光刻机，今年目标生产约 5 台，2027 年约 20 台，将交付中芯国际、华虹半导体等国内厂商。 这一突破挑战了 ASML 在 DUV 光刻领域的近乎垄断地位，增强了中国半导体自给自足能力，在西方出口管制收紧的背景下具有重大地缘政治和市场影响。 国产设备主要使用国产零部件，但部分关键部件仍来自日本，今年本地供应链延误已影响进度。芯片商需数月时间测试精度与兼容性方能投入量产。

telegram · zaihuapd · 7月27日 14:10

**背景**: DUV 光刻利用深紫外光（如 193nm ArF 激光）在硅片上刻印电路图案。浸没式光刻通过将液体（通常是水）置于镜头与晶圆之间来提高分辨率，可实现 45 纳米以下的制程。目前 ASML 主导着先进光刻机市场。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DUV_lithography">DUV lithography</a></li>
<li><a href="https://en.wikipedia.org/wiki/Immersion_lithography">Immersion lithography</a></li>
<li><a href="https://www.asml.com/news/stories/2023/how-immersion-lithography-saved-moores-law">How immersion lithography saved Moore’s Law</a></li>

</ul>
</details>

**标签**: `#semiconductor`, `#lithography`, `#China`, `#ASML`, `#DUV`

---

<a id="item-3"></a>
## [vLLM v0.26.0 发布，支持新模型族和 DeepSeek-V4 优化](https://github.com/vllm-project/vllm/releases/tag/v0.26.0) ⭐️ 8.0/10

vLLM v0.26.0 引入了对全新 Inkling 模型系列的全面支持，包括分段 CUDA 图和 Hopper FA4 相对注意力，并在多个 GPU 厂商平台上显著提升了 DeepSeek-V4 的性能。 此次发布通过优化 DeepSeek-V4 等前沿模型并支持新架构，巩固了 vLLM 作为领先开源 LLM 推理引擎的地位，惠及整个 AI 推理生态系统。 此次发布包含来自 212 位贡献者的 411 次提交，显著特性包括生成模型的 fp32 lm_head、每个 KV 缓存组可选择的注意力后端、成熟的 KV 卸载与分层二级存储，以及 Rust 前端对多模态视频和音频的支持。

github · khluu · 7月27日 01:06

**背景**: vLLM 是一个用于高吞吐量 LLM 推理的开源库。分段 CUDA 图是一种将模型计算拆分成多个片段的技术，以便对可变长度序列进行 CUDA 图捕获，从而提升性能。NVFP4 量化是一种 4 位浮点格式的模型权重表示，可在保持精度的同时减少内存使用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.spheron.network/blog/tensorrt-model-optimizer-modelopt-quantization-guide/">NVIDIA TensorRT Model Optimizer (ModelOpt): FP8, INT4, and FP4 Quantization Guide (2026) | Spheron Blog</a></li>
<li><a href="https://docs.sglang.io/docs/advanced_features/piecewise_cuda_graph">Piecewise CUDA Graph - SGLang Documentation</a></li>
<li><a href="https://docs.vllm.ai/en/stable/design/cuda_graphs/">CUDA Graphs - vLLM</a></li>

</ul>
</details>

**标签**: `#vLLM`, `#LLM inference`, `#performance optimization`, `#open source`, `#DeepSeek`

---

<a id="item-4"></a>
## [Anthropic 澄清对开放权重模型的立场](https://www.anthropic.com/news/position-open-weights-models) ⭐️ 8.0/10

Anthropic 发布博文，表示从未主张禁止开放权重模型，而是提议对所有足够强大的模型进行强制性安全测试，并采取措施打击工业规模的蒸馏行为。 这一澄清可能通过区分开放权重访问与安全要求来影响 AI 监管讨论，从而影响开源社区和专有 AI 开发者。 Anthropic 的提议包括对所有足够强大的模型（无论开放还是封闭）进行强制性安全测试，并打击从专有模型中提取知识的蒸馏操作。

hackernews · surprisetalk · 7月27日 22:03 · [社区讨论](https://news.ycombinator.com/item?id=49076057)

**背景**: 开放权重模型发布训练好的神经网络权重，允许任何人本地运行，但常与完全开源模型混淆。知识蒸馏将能力从大模型转移到小模型，可降低部署门槛但也引发滥用担忧。Anthropic 的立场正处于开放访问与安全监管之间的紧张关系中。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://promptmetheus.com/resources/llm-knowledge-base/open-weights-model">Open - weights Model | LLM Knowledge Base</a></li>
<li><a href="https://www.analyticsvidhya.com/blog/2025/04/open-weight-models/">What are Open Source and Open Weight Models ? | Analytics Vidhya</a></li>
<li><a href="https://en.wikipedia.org/wiki/Knowledge_distillation">Knowledge distillation - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍批评 Anthropic 的立场，认为强制性安全测试通过设置昂贵的监管障碍实际上等于禁止开放权重模型。一些人指出 Anthropic 自身面临版权诉讼的虚伪性，另一些则质疑在缺乏明确标准下所提措施的可行性。

**标签**: `#AI safety`, `#open-source`, `#regulation`, `#Anthropic`, `#open-weights`

---

<a id="item-5"></a>
## [Libsm64 将超级马里奥 64 转化为可复用库](https://github.com/libsm64/libsm64) ⭐️ 8.0/10

libsm64 项目将《超级马里奥 64》的核心游戏逻辑和角色提取为共享库，允许开发者将马里奥嵌入到任何能加载 C 库的游戏引擎中。 这开启了跨游戏混搭的创意可能性，展示了逆向工程和反编译的力量，使马里奥能够未经任天堂授权出现在《半条命 2》等游戏中。 该库暴露了一个在 libsm64.h 中定义的最小 API；客户端项目只需包含该头文件并加载共享库。该项目依赖于之前对《超级马里奥 64》的完整反编译。

hackernews · klaussilveira · 7月27日 10:04 · [社区讨论](https://news.ycombinator.com/item?id=49067352)

**背景**: 《超级马里奥 64》最初于 1996 年在任天堂 64 上发布。2019 年，社区主导的努力成功地从原始机器码反编译了游戏源代码，生成了可读的 C 代码库。libsm64 在此基础上将游戏角色打包为可移植库。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/libsm64/libsm64">GitHub - libsm64/libsm64: Mario 64 as a library for use in external game engines · GitHub</a></li>

</ul>
</details>

**社区讨论**: 评论者非常热情，有人称之为‘单从概念上就是我最喜欢的库之一’。有人分享了马里奥在《半条命 2》中的示例和其他演示。有人开玩笑说将其作为服务出售，还有人指出这实现了可互操作游戏资产的承诺，而无需区块链炒作。

**标签**: `#reverse-engineering`, `#game-development`, `#open-source`, `#nintendo-64`, `#libraries`

---

<a id="item-6"></a>
## [Bun 的 Rust 重写版本已在 Claude Code 中发布，公开版本推迟](https://lockwood.dev/ai/2026/07/27/how-is-the-bun-rewrite-in-rust-going.html) ⭐️ 8.0/10

Bun 的创建者 Jarred 宣布，Bun 的 Rust 重写版本已在一个多月前集成到 Claude Code 中，但公开版本要等到 Node.js 兼容性目标达成后才能发布。 这一更新表明 Bun 在性能和兼容性方面取得了重大进展，Rust 重写版本已在 Claude Code 这样的重要工具中投入生产。推迟发布凸显了项目对稳定性的承诺，这对依赖 Bun 的开发者至关重要。 Rust 重写版本在 Bun v1.4 视频中被承诺会通过一定数量的新 Node.js 测试，但该数字尚未达成。实现这一目标的拉取请求尚未合并，公开版本预计下周二发布。

hackernews · tomlockwood · 7月27日 11:12 · [社区讨论](https://news.ycombinator.com/item?id=49067854)

**背景**: Bun 是一个快速的 JavaScript 运行时和工具包，旨在替代 Node.js。其原始核心使用 Zig 编写，但团队决定用 Rust 重写以获得更好的性能和生态集成。Claude Code 是 Anthropic 的 AI 编程助手，帮助开发者理解和编辑代码库。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://claude.com/product/claude-code">Claude Code by Anthropic | AI Coding Agent, Terminal, IDE</a></li>
<li><a href="https://docs.anthropic.com/en/docs/claude-code/overview">Claude Code overview - Anthropic</a></li>

</ul>
</details>

**社区讨论**: 社区评论表现出谨慎乐观：一些人指出重写是一项重大工程，预计开发节奏会放缓；另一些人则质疑重写的必要性，并提到一个声称性能更好的 Zig 分支。还有关于 LLM 在翻译过程中作用的讨论。

**标签**: `#Bun`, `#Rust`, `#rewrite`, `#JavaScript`, `#performance`

---

<a id="item-7"></a>
## [小米 MiMo-V2.5 登 OpenRouter 双榜第一](https://36kr.com/newsflashes/3913798998201732?f=rss) ⭐️ 8.0/10

7 月 27 日，OpenRouter 数据显示，小米 MiMo-V2.5 模型登顶全球大模型调用量周榜和月榜双第一，成为当周全球唯一突破 10T token 的模型。自 5 月以来，其周 token 量从 1.46T 激增至 10.46T，两个月内增长约 616%。 这一里程碑凸显了小米自研模型的快速普及和竞争力，表明中国 AI 公司在全球大模型部署中正取得重要进展。同时也验证了通过 OpenRouter 等统一 API 平台进行高容量、低成本模型推理的需求日益增长。 MiMo-V2.5 是一个原生全模态模型，支持文本、图像、视频和音频理解，基于 MiMo-V2-Flash 骨干网络构建。该模型经历了五阶段训练流程，包括文本预训练、多模态预训练、监督微调（上下文窗口从 32K 逐步扩展到 1M）以及强化学习和 MOPD。

rss · 36kr · 7月27日 11:22

**背景**: OpenRouter 是一个统一 API 接口，通过单个端点连接数百个 AI 模型，充当反向代理和路由层，负责请求转换和提供商选择。Token 调用是指 AI 模型处理的数据单位，token 调用量反映了推理使用量。高 token 调用量通常表明模型在开发者和企业中的受欢迎程度及成本效益。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://mimo.xiaomi.com/mimo-v2-5">MiMo-V2.5 | Xiaomi</a></li>
<li><a href="https://huggingface.co/XiaomiMiMo/MiMo-V2.5">XiaomiMiMo/MiMo-V2.5 · Hugging Face</a></li>

</ul>
</details>

**标签**: `#AI`, `#LLM`, `#Xiaomi`, `#OpenRouter`, `#model deployment`

---

<a id="item-8"></a>
## [个人评测 6 大前沿 LLM 发现左倾偏见](https://www.reddit.com/r/MachineLearning/comments/1v8fnzw/evaluated_6_frontier_llms_gpt54_claude_sonnet_46/) ⭐️ 8.0/10

一位独立研究人员对六个前沿 LLM（GPT-5.4、Claude Sonnet 4.6、Claude Opus 4.7、Gemini Pro/Flash、Grok 4.3）在八个偏见基准上进行了约 20600 个样本的评测，发现所有模型均存在一致的左倾政治偏见，并且在种族相关问题上表现出显著的拒绝回答率。 这项研究对主要 LLM 中的政治和社会偏见进行了全面的独立检验，揭示了即使是像 Grok 这样自称右倾的模型在实际行为中也表现出左倾。它强调了透明偏见审计的必要性，以及在敏感应用中使用这些模型时需要谨慎。 值得注意的是，GPT-5.4 拒绝了 20.3%的种族相关 BBQ 问题，而 Claude Opus 4.7 拒绝了 13.8%，Grok 拒绝了 9.5%，Claude Sonnet 4.6 和 Gemini Pro 约为 5%。该研究未经同行评审，使用单一提示模板，且未进行多次运行平均，限制了统计推广性。

reddit · r/MachineLearning · /u/marggggggggg · 7月27日 22:37

**背景**: 偏见基准如 WinoBias（共指消解中的性别偏见）、BBQ（问答中的社会偏见）和 SeeGULL（刻板印象数据集）是评估 LLM 公平性的标准化工具。政治指南针（Political Compass）和其他政治偏见数据集用于衡量意识形态倾向。拒绝率表示模型避免回答可能揭示偏见的问题，这本身也可能是一种偏见形式。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/winobias">WinoBias : Gender Bias in Coreference Benchmark</a></li>
<li><a href="https://ukgovernmentbeis.github.io/inspect_evals/evals/bias/bbq/index.html">BBQ : Bias Benchmark for Question Answering</a></li>
<li><a href="https://github.com/google-research-datasets/seegull">GitHub - google-research-datasets/seegull: SeeGULL is a broad-coverage stereotype dataset in English containing stereotypes about identity groups spanning 178 countries across 8 different geo-political regions across 6 continents, as well as state-level identities within the US and India. · GitHub</a></li>

</ul>
</details>

**标签**: `#LLM bias`, `#benchmarking`, `#political bias`, `#fairness`, `#frontier models`

---

<a id="item-9"></a>
## [Fastjson2 曝未修复的远程代码执行漏洞](https://mp.weixin.qq.com/s/LJaul1jNjK9pXRAkoUiMEA) ⭐️ 8.0/10

长亭科技于 7 月 27 日披露 Fastjson2 的一个远程代码执行漏洞，攻击者可通过恶意 JSON 数据绕过 AutoType 校验并执行代码，影响 2.0.62 及之前所有版本，目前无正式补丁。 Fastjson2 是 Java 中广泛使用的 JSON 库，该严重 RCE 漏洞带来极大安全风险，建议用户立即禁用 AutoType。 漏洞细节和利用代码尚未公开，但维护者已确认安全问题。这是本月继 Fastjson1 之后的第二个严重漏洞。

telegram · zaihuapd · 7月27日 10:31

**背景**: Fastjson 是阿里巴巴开源的 Java JSON 库，其 AutoType 功能允许 JSON 数据携带类型信息，在反序列化时自动识别类型。但恶意 JSON 数据可利用 AutoType 实现远程代码执行。此前 Fastjson1（如≤1.2.80 版本）也曾出现类似漏洞。AutoType 默认关闭，但部分用户为功能需求会开启。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://alibaba.github.io/fastjson2/autotype_cn.html">FASTJSON 2 Autotype 机制介绍 | fastjson 2</a></li>
<li><a href="https://github.com/alibaba/fastjson2/wiki/Security-Advisory:-Remote-Code-Execution-in-fastjson-1.2.68–1.2.83">Security Advisory: Remote Code Execution in fastjson 1.2.68–1.2.83</a></li>
<li><a href="https://juejin.cn/post/7104159627360600095">Fastjson反序列化 远 程 代 码 执 行 漏 洞 产生 原 因及修复建议Fastjason...</a></li>

</ul>
</details>

**标签**: `#Fastjson2`, `#RCE`, `#vulnerability`, `#security`, `#Java`

---

<a id="item-10"></a>
## [法官驳回谷歌利用 DMCA 阻止爬取搜索结果的企图](https://www.techdirt.com/2026/07/27/judge-rejects-googles-attempt-to-dmca-its-way-out-of-being-scraped/) ⭐️ 7.0/10

一名联邦法官裁定，谷歌不得利用《数字千年版权法》(DMCA)阻止第三方爬取其搜索结果，并确认搜索结果不受版权保护。 这一裁决为数据爬取设立了重要先例，可能限制大型科技公司利用版权法阻碍竞争和数据访问。它还明确了搜索结果列表作为事实汇编通常缺乏版权保护所需的原创性。 该案涉及谷歌起诉 SerpAPI，后者为第三方客户爬取谷歌搜索结果。法官驳回了谷歌关于爬取构成 DMCA 反规避的主张，因为搜索结果并非原创作品。

hackernews · cdrnsf · 7月27日 18:15 · [社区讨论](https://news.ycombinator.com/item?id=49073513)

**背景**: 《数字千年版权法》禁止规避控制受版权作品访问的技术措施。谷歌辩称其搜索结果受版权保护，而爬取行为绕过了其技术保护。然而，法院长期以来认为，像电话目录或搜索结果等事实汇编需要最低限度的创造性才有版权，谷歌的算法列表通常缺乏这一点。

**社区讨论**: 评论者大多对这一裁决表示欢迎，批评谷歌利用版权法扼杀竞争，并指出其缺乏合法 API 的问题。一些人提出了欧盟与美国版权保护差异的担忧，以及爬取在揭露虚假 ESTA 网站等诈骗行为中的实际必要性。

**标签**: `#scraping`, `#DMCA`, `#Google`, `#legal`, `#copyright`

---

<a id="item-11"></a>
## [论坛项目弃用 React 改用 HTMX，引发讨论](https://misago-project.org/t/removing-reactjs-from-the-codebase-and-adapting-htmx-for-ui-interactivity/1267/) ⭐️ 7.0/10

Misago 论坛项目宣布将从代码库中移除 React.js，转而采用 HTMX 来实现 UI 交互，这反映了向前端更简单、服务器驱动方法的转变。 这一决定凸显了开发人员中的一种日益增长的趋势：在论坛等内容密集型网站中，放弃笨重的客户端 JavaScript 框架，转而采用轻量级、基于超媒体的库。 HTMX 是一个小型、无依赖的库（压缩后约 14 KB），允许开发人员通过 HTML 属性直接添加 AJAX、CSS 过渡、WebSocket 和服务器发送事件，从而无需完整的 JavaScript 框架。

hackernews · Ralfp · 7月27日 09:58 · [社区讨论](https://news.ycombinator.com/item?id=49067301)

**背景**: React.js 是一个流行的用于构建用户界面的 JavaScript 库，常用于单页应用（SPA）。但对于论坛这类以内容为主的网站，其中大部分内容是非交互式文本，完整的 SPA 框架可能过于复杂。HTMX 受 intercooler.js 启发，无需编写自定义 JavaScript 即可实现动态更新，符合超文本和服务器端渲染的原则。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://htmx.org/">htmx - high power tools for html</a></li>
<li><a href="https://en.wikipedia.org/wiki/Htmx">htmx - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍支持这一转变，许多人都称赞 HTMX 对于论坛软件的简单性。然而，有用户报告了当 HTMX 发送大型 HTML 响应时的性能问题，另有人推荐了类似 PyView 的服务器驱动替代方案。总体情绪积极，但带有实际注意事项。

**标签**: `#HTMX`, `#React`, `#server-side rendering`, `#web development`, `#frontend frameworks`

---

<a id="item-12"></a>
## [Paged Out #9：免费黑客杂志发布](https://pagedout.institute/download/PagedOut_009.pdf) ⭐️ 7.0/10

Paged Out #9 已以 PDF 形式发布，这是一本免费且设计精美的黑客杂志，包含深入的技术文章和创意内容，让人想起经典的黑客杂志。 这次发布对黑客社区意义重大，因为它复兴了 2600 和 Phrack 等标志性杂志的精神，为高度技术和好奇内容提供了现代平台。 值得注意的文章包括“Baby Steps in C”（幽默风格）、“The Subpixel Zoo”（关于亚像素渲染），以及一篇未署名的关于 Wang 可计算平铺工作的重新发现，将多米诺骨牌问题与停机问题联系起来。

hackernews · laurensr · 7月27日 14:22 · [社区讨论](https://news.ycombinator.com/item?id=49070138)

**背景**: Paged Out 是一本免费的、由社区驱动的黑客杂志，旨在捕捉 2600 和 Phrack 等经典杂志的精髓。它涵盖广泛的技术主题，包括编程、复古计算和黑客技术，通常采用创意和实践方法。该杂志以其精美的设计和深入的技术内容而闻名，吸引黑客和技术爱好者。

**社区讨论**: 评论者称赞这本杂志是现代的 2600/Phrack，有人称其“设计精美”、“技术深度高”。技术见解包括对可计算平铺文章的讨论，将其与 Wang 在 1960 年代的工作以及多米诺骨牌问题与停机问题的等价性联系起来，以及对文本亚像素渲染的兴趣。

**标签**: `#hacker magazine`, `#technical articles`, `#computing history`, `#programming`, `#retro computing`

---

<a id="item-13"></a>
## [现代电子邮件可通过借用现有组件构建](https://en.andros.dev/blog/d7ed8b07/modern-email-can-be-built-from-borrowed-parts/) ⭐️ 7.0/10

一项提案建议利用其他协议中的现代组件重建电子邮件系统，引发了关于垃圾邮件、成本和迁移路径的讨论。 电子邮件仍是关键通信基础设施，任何现代化改造都可能影响数十亿用户。该提案揭示了垃圾邮件、经济模型和网络效应等阻碍此前尝试的挑战。 该提案利用了 JMAP、MTA-STS 和 ARC 等现有改进来解决 SMTP 的缺陷。然而，社区评论强调需要向后兼容和迁移路径来克服网络效应。

hackernews · andros · 7月27日 08:27 · [社区讨论](https://news.ycombinator.com/item?id=49066639)

**背景**: 电子邮件依赖已有数十年历史的 SMTP 协议，该协议缺乏内置加密和认证。现代扩展如 JMAP 替代 IMAP 用于客户端-服务器通信，MTA-STS 改进服务器间加密，ARC 则在转发链中保留认证信息。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/JSON_Meta_Application_Protocol">JSON Meta Application Protocol - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/MTA-STS">MTA-STS</a></li>
<li><a href="https://easydmarc.com/blog/arc-email-authentication-what-it-is-and-how-it-works/">ARC Email Authentication Explained | EasyDMARC</a></li>

</ul>
</details>

**社区讨论**: 评论者如 teddyh 警告历史重演，指出不切实际的垃圾邮件解决方案层出不穷；BeetleB 则提出通过经济手段抑制垃圾邮件。rbanffy 等人指出电子邮件的韧性可能表明协议栈并非如人们所想的那般糟糕。jerf 的评论虽截断，但可能建议重新评估当前方案。

**标签**: `#email`, `#protocols`, `#spam`, `#SMTP`, `#modernization`

---

<a id="item-14"></a>
## [Ethan Mollick 的 AI 工具指南转向代理系统](https://simonwillison.net/2026/Jul/27/an-opinionated-guide-to-which-ai-to-use-to-do-stuff/#atom-everything) ⭐️ 7.0/10

Ethan Mollick 更新了他关于使用哪些 AI 工具的主观指南，强调从基于聊天的模型（如 ChatGPT 和 Claude）转向能够自主完成数小时人类工作的代理系统。 这反映了行业向更自主的 AI 代理发展的趋势，可能通过自动化复杂的多步骤任务显著提高知识工作者的生产力。 值得注意的是，Gemini 已被移除，因为谷歌在 Codex/ChatGPT Work/Cowork 类别中缺乏成熟的产品，而 Gemini Spark 尚未证明自己。指南解释了模式命名（如 ChatGPT Work 和 Claude Cowork）的混乱，这些模式在桌面端和移动端操作不同。

rss · Simon Willison · 7月27日 21:55

**背景**: 代理 AI 系统是能够追求目标、使用工具并以不同程度的自主性采取行动的 AI 代理，不同于需要人工干预的传统 AI 模型。像 OpenAI 的 Deep Research 工具可以自主进行在线研究。谷歌的 Gemini Spark 是一个 24/7 的 AI 代理，与谷歌服务集成，无需技术设置。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AI_agent">AI agent - Wikipedia</a></li>
<li><a href="https://www.ibm.com/think/topics/agentic-ai">What is Agentic AI? | IBM</a></li>
<li><a href="https://mitsloan.mit.edu/ideas-made-to-matter/agentic-ai-explained">Agentic AI, explained | MIT Sloan</a></li>

</ul>
</details>

**标签**: `#AI`, `#LLMs`, `#agentic systems`, `#tools`

---

<a id="item-15"></a>
## [清华博士创业公司获数千万元融资，研发航空氢燃料电池](https://36kr.com/p/3913736066028932?f=rss) ⭐️ 7.0/10

由清华大学博士创立的易氢动力已完成数千万元天使+轮融资，由红鸟启航基金和贵州科创天使基金领投。资金将用于航空级液冷燃料电池产品的开发及验证，以及空冷燃料电池在无人机和 eVTOL 等场景的商业化推广。 此次融资标志着中国氢能航空领域日益受到关注，该领域此前落后于车用燃料电池。易氢动力的技术可为长航程 eVTOL‘空中出租车’和高续航无人机提供动力，有望颠覆低空经济格局。 易氢动力已开发出 30kW 液冷燃料电池系统（现已迭代至 90-110kW）以及适用于无人机的空冷系统。公司已成为中国商飞的供应商，并与多家 eVTOL 整机厂合作。空冷产品在 2025 年无人机巡检场景中已实现数百万收入。

rss · 36kr · 7月27日 10:19

**背景**: 氢燃料电池通过电化学反应产生电能，相比锂电池具有高能量密度和快速补能的优势。在航空领域，氢能被视作 eVTOL 和无人机的潜在零排放解决方案，尤其能克服电池在航程和低温环境下的局限。欧洲早在 21 世纪初就开始相关研究，而中国在低空经济政策推动下近年来加速布局。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.163.com/dy/article/L2S6ANCQ05118DFD.html">清华博士团队创业，这家公司要给飞机做氢能「心脏」｜36氪首发</a></li>
<li><a href="https://en.wikipedia.org/wiki/EVTOL">eVTOL - Wikipedia</a></li>

</ul>
</details>

**标签**: `#hydrogen fuel cell`, `#aviation`, `#clean energy`, `#startup funding`, `#Tsinghua University`

---

<a id="item-16"></a>
## [2026 年资本转向 AI 应用商业化质量](https://36kr.com/p/3913706151400583?f=rss) ⭐️ 7.0/10

风险资本对 AI 应用的评估标准从用户规模（DAU）转向商业化质量，如月之暗面（Kimi）放弃 DAU 目标，聚焦 Agent 产品。这一转变以海艺（SeaArt）为代表，该公司毛利率超过 40%、续费率超 60%，吸引了大量融资。 这标志着 AI 行业的转折点：仅靠高用户数不再能保证估值，可持续盈利和高留存率成为关键。这将重塑 AI 初创公司的生存格局，更青睐那些拥有强大商业模式而非追求规模的公司。 月之暗面（Kimi）估值半年涨 6 倍至目标 300 亿美元，同时降低 DAU 优先级。Character.AI 在月活峰值 2800 万后流失 800 万，Inflection AI 在烧掉 13 亿美元后转型，说明了规模优先策略的失败。

rss · 36kr · 7月27日 09:48

**背景**: 在 AI 应用层，2023 至 2025 年的主流策略是补贴算力快速获取用户，复制互联网时代的“圈地”模式。然而，高算力成本和低留存率表明，仅靠 DAU 无法支撑利润。AI Agent 概念（能感知、推理并行动的自主系统）成为新焦点，如月之暗面的转向。海艺（Haiyi）是一家成都公司，构建了多模态创作社区、AI 短剧平台和角色互动产品，通过可复用的能力模块实现了高毛利。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.techbang.com/posts/131321-moonshot-ai-kimi-k3-2-8-trillion-parameter-open-model">Moonshot AI 發布全球首款 2.8 兆參數開放 模 型 Kimi ... | T客邦</a></li>
<li><a href="https://en.wikipedia.org/wiki/AI_agent">AI agent</a></li>
<li><a href="https://www.53ai.com/news/neirongchuangzuo/2025021575931.html">AI Agent ... - 53 AI - AI 知识库|大模型知识库|大模型训练|智能体开发</a></li>

</ul>
</details>

**标签**: `#AI applications`, `#venture capital`, `#commercialization`, `#Kimi`, `#Agent`

---

<a id="item-17"></a>
## [全球最大 eVTOL 货运无人机 AT8000 机身下线](https://36kr.com/p/3912369056240772?f=rss) ⭐️ 7.0/10

中国公司牧羽天航空宣布其 AT8000 机身下线，这是全球最大的 eVTOL 货运无人机，最大起飞重量达 8 吨。 这一里程碑使中国在重载低空物流领域处于领先地位，可能通过实现 1000 公里航程和 3.5 吨有效载荷，改变时效性或偏远地区的货物运输。 AT8000 采用半倾转混动架构，拥有 18 个升力旋翼（4 个可倾转）和 2 个推进旋翼，巡航速度 252 公里/小时，全复合材料结构，核心技术完全自主。

rss · 36kr · 7月27日 08:23

**背景**: eVTOL（电动垂直起降飞行器）设计为像直升机一样起降，但过渡到固定翼飞行以提高效率。低空经济指利用 1000 米以下空域进行商业活动，如货运无人机和空中出租车。半倾转混动架构结合固定升力旋翼和倾转旋翼，以平衡垂直升力和前向推力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/EVTOL">eVTOL - Wikipedia</a></li>
<li><a href="https://www.embention.com/embention-uam-academy/lesson/types-and-architectures-of-evtol-aircraft/">eVTOL Types and Architectures | Embention UAM Academy</a></li>
<li><a href="https://www.grepow.com/blog/what-is-low-altitude-economy.html">What Are Low Altitude Economy and Low - Altitude Aircrafts | Grepow</a></li>

</ul>
</details>

**标签**: `#eVTOL`, `#heavy-lift drone`, `#low-altitude economy`, `#cargo logistics`, `#aviation`

---

<a id="item-18"></a>
## [‘数字空间一号’试验星工程启动，构建 AI 太空大脑](https://36kr.com/p/3912546487637378?f=rss) ⭐️ 7.0/10

7 月 26 日，‘数字空间一号’试验星工程在北京正式启动，旨在在轨验证一种能够实现卫星星座自主管理的 AI‘太空大脑’架构。 随着卫星数量激增至数万颗，传统地面指令管控模式难以为继；该项目有望开创未来大型星座所需的自主类脑运行方式，推动中国航天产业从‘管得住’向‘用得好’跃迁。 该卫星将测试一套‘感知-认知-行为’的星上全链条智能闭环，在毫秒级实现自主运行。为避免大语言模型在航天应用中的黑箱和幻觉问题，项目采用物理世界模型作为基础底座。

rss · 36kr · 7月27日 01:00

**背景**: 中国商业航天已完成‘造得出、送得上’的第一阶段，但随着轨道资源拥挤，传统地面管控模式正面临失效。中国科学院院士魏奉思提出的‘太空大脑’概念，设想卫星具备类似鸟群的本体智能，能自主避碰和适应环境变化。

<details><summary>参考链接</summary>
<ul>
<li><a href="http://www.maqu.gov.cn/info/1043/1940.htm">我国成功发射微厘 空 间 一 号 试 验 卫 星 -玛曲县人民政府</a></li>
<li><a href="https://min.news/zh-hans/tech/b7a4da51b797351c8113a6d006842c54.html">中国科学院院士魏奉思：每颗 卫 星 都要有自己的“ 大 脑 ” - 头条汇</a></li>

</ul>
</details>

**标签**: `#aerospace`, `#satellite`, `#AI`, `#space intelligence`, `#digital space`

---

<a id="item-19"></a>
## [携程被罚 51.79 亿；长鑫科技上市；日本承认中国人形机器人领先](https://36kr.com/p/3913118530819457?f=rss) ⭐️ 7.0/10

中国市场监管总局对携程滥用市场支配地位处以 51.79 亿元罚款；长鑫科技以每股 8.66 元在科创板上市；日本技术人员拆解宇树科技 G1 人形机器人后承认中国在人形机器人领域已领先日本。 对携程的巨额罚款标志着中国反垄断执法力度加强，可能重塑在线旅游市场格局；长鑫科技上市凸显中国推动半导体自给自足的决心；日方评估则表明中国在人形机器人这一未来关键产业已取得显著领先。 携程的罚款包括没收违法所得和罚款两部分；长鑫科技预估市值在 1 万亿至 4 万亿元之间，首日涨幅或达 70%-600%；宇树 G1 人形机器人售价 9.9 万元，能完成敲核桃、以 2 米/秒速度小跑等动作。

rss · 36kr · 7月26日 23:50

**背景**: 中国反垄断罚款依据《反垄断法》，携程案涉及其在在线旅游预订市场的滥用市场支配地位行为。长鑫科技是中国领先的 DRAM 制造商，其 IPO 包含超额配售选择权（绿鞋机制）以稳定股价。人形机器人如宇树 G1 旨在模仿人类运动，具有工业和服务领域的应用潜力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.163.com/dy/article/L2OGLTI10511B8LM.html">163.com/dy/article/L2OGLTI10511B8LM.html</a></li>
<li><a href="https://m.dzplus.dzng.com/share/general/0/NEWS2139618WUMBNTSKAWAFL">半岛聚焦丨65...</a></li>

</ul>
</details>

**标签**: `#Ctrip`, `#antitrust`, `#IPO`, `#humanoid robot`, `#China tech`

---

<a id="item-20"></a>
## [从头构建 Transformer：英译泰米尔语翻译教程](https://www.reddit.com/r/MachineLearning/comments/1v86qo9/built_trained_a_transformer_from_scratch_in_pure/) ⭐️ 7.0/10

一位开发者发布了一份详细的教程和博客文章，完整讲解了如何使用纯 PyTorch 从零构建并训练用于英译泰米尔语的 Transformer 模型。 本教程为实践者提供了包含数学和代码的逐步指南，帮助学习 Transformer 架构，弥合理论与实际实现之间的差距，尤其适用于低资源语言对。 模型在 Kaggle 上使用双 NVIDIA T4 GPU 训练，数据集来自 Hugging Face 的'gopi30/english-tamil'，并包含完整的数学推导和 PyTorch 模块解释。

reddit · r/MachineLearning · /u/imrancoder · 7月27日 17:17

**背景**: Transformer 架构在《Attention Is All You Need》论文中提出，通过自注意力机制取代循环层，彻底改变了自然语言处理。由于平行数据有限且文字系统不同，英译泰米尔语的机器翻译具有挑战性。本教程旨在为学习者揭开该架构的神秘面纱。

**标签**: `#Transformer`, `#PyTorch`, `#Machine Translation`, `#NLP`, `#Tutorial`

---

<a id="item-21"></a>
## [提出训练前数据确定性审计门控](https://www.reddit.com/r/MachineLearning/comments/1v8a3nu/training_data_needs_a_real_gonogo_gate_before/) ⭐️ 7.0/10

一位 Reddit 用户提出一个训练前数据确定性审计系统，该系统基于数据泄露、矛盾、来源等明确的质量检查来门控训练，输出可复现的通过/失败判定。 这解决了机器学习管道治理中的一个关键缺口，即数据质量决策通常是临时性的，并引入了一种原则性方法，防止有缺陷的数据进入训练。 该系统将基于证据而非 LLM 判断给出通过、警告、失败或安全失败等判定，并可在保留原始数据的同时，对派生副本生成修复计划。

reddit · r/MachineLearning · /u/jesusmjk · 7月27日 19:13

**背景**: 机器学习中的数据泄露是指训练数据无意中包含来自测试集的信息，导致性能估计过于乐观。数据来源追踪数据的来源和转换过程，对可复现性和可信度至关重要。提出的门控旨在将这些检查整合到正式的训练前控制层中，类似于已用于代码和部署的门控。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Leakage_(machine_learning)">Leakage ( machine learning ) - Wikipedia</a></li>
<li><a href="https://www.ibm.com/think/topics/data-leakage-machine-learning">What is Data Leakage in Machine Learning ? | IBM</a></li>
<li><a href="https://zenithlaw.com/data-provenance-ml-lifecycle-traceability-graph-methods-ten-lessons">Data Provenance in Machine Learning : Traceability, Graph Met</a></li>

</ul>
</details>

**标签**: `#data quality`, `#ML pipelines`, `#training data`, `#data validation`, `#MLOps`

---

<a id="item-22"></a>
## [谷歌 Gemini 4：最具雄心的预训练，预计 2026 年底发布](https://9to5google.com/2026/07/26/google-gemini-4-teases/) ⭐️ 7.0/10

谷歌 CEO Sundar Pichai 在 Alphabet 2026 年第二季度财报电话会议上透露，下一代大模型 Gemini 4 已投入训练，称这是该公司迄今为止最具雄心的预训练项目，预计将于 2026 年底发布。 这一声明凸显了谷歌保持在 AI 前沿的决心，因为更大的基础模型对于推进 AGI 至关重要。Gemini 4 可能设立新的性能标准，并加剧领先 AI 实验室之间的竞争。 Pichai 表示，计算资源将优先分配给 AGI 研发，以确保 Gemini 4 在发布时仍保持领先。按照以往节奏，该模型预计在 2026 年 11 月或 12 月发布，同时 Gemini 3.x Flash 系列将继续以几乎每月一次的频率迭代，重点提升编码能力。

telegram · zaihuapd · 7月27日 04:06

**标签**: `#AI`, `#Google`, `#Gemini`, `#Large Language Model`

---

<a id="item-23"></a>
## [阿里推出“千问办公”AI 办公平台](https://qwenwork.cn/) ⭐️ 7.0/10

阿里巴巴推出了“千问办公”的 Beta 版本，这是一个一站式 AI 办公平台，能够通过自然语言生成和编辑文档、表格、PPT、网页、代码及多媒体内容，并具备电脑操控功能。 此次发布标志着阿里巴巴进入 AI 办公生产力领域，具备跨应用控制等高级自动化功能，可能挑战现有的如 Microsoft Copilot 和 Google Workspace 等工具。 该平台支持网页、Windows 和 macOS 客户端，并接入钉钉。提供免费版和付费套餐，每月 78 元起。桌面客户端可以读取本地文件，调用浏览器自动化和 Computer Use 功能，在执行可能不可撤销的操作前会明确征求用户确认。

telegram · zaihuapd · 7月27日 05:45

**背景**: “千问办公”基于阿里巴巴的 Qwen 大语言模型家族。其“Computer Use”功能允许 AI 直接操控电脑界面，跨应用执行点击、输入和数据提取等操作。这属于 AI 代理自动化的大趋势，类似于 Anthropic 的计算机使用能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Qwen">Qwen - Wikipedia</a></li>

</ul>
</details>

**标签**: `#AI`, `#office productivity`, `#Alibaba`, `#Qwen`, `#computer automation`

---

<a id="item-24"></a>
## [中方驳美方制裁威胁：模型蒸馏是行业惯例](https://www.mofcom.gov.cn/syxwfb/art/2026/art_7f1622463a7c48ef9fad600ce0ef702f.html) ⭐️ 7.0/10

这一对峙凸显了 AI 地缘政治的紧张升级，模型蒸馏成为两大 AI 强国之间的焦点。美国的制裁可能扰乱跨国合作和开源模型共享，影响全球 AI 发展。 商务部指出，模型蒸馏是广泛使用的技术，部分美国企业也在研发中使用中国模型，并警告如果美方造成实质性损害，中方将采取必要措施维护企业合法权益。

telegram · zaihuapd · 7月27日 11:01

**背景**: 模型蒸馏是一种机器学习技术，通过让较小的“学生”模型学习模仿较大的“教师”模型的行为，从而实现高效部署。它常用于压缩大型模型而不显著损失性能。美国近期调查中国 AI 企业，指控其未经授权蒸馏美国前沿模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://medium.com/stream-zero/understanding-the-essentials-of-model-distillation-in-ai-1e97403bee8a">Understanding the Essentials of Model Distillation in AI | Medium</a></li>
<li><a href="https://www.linkedin.com/pulse/understanding-distillation-ai-how-models-can-extracted-pooni-vvaqc">Understanding " Distillation " in AI : How Models Can Be Extracted and...</a></li>
<li><a href="https://avahi.ai/glossary/model-distillation/">What is Model Distillation in AI ?</a></li>

</ul>
</details>

**标签**: `#AI policy`, `#model distillation`, `#US-China relations`, `#technology sanctions`, `#Chinese AI`

---