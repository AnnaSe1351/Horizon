---
layout: default
title: "Horizon Summary: 2026-07-29 (ZH)"
date: 2026-07-29
lang: zh
---

> 从 83 条内容中筛选出 28 条重要资讯。

---

1. [开源引擎让 Gemma 4 26B 在仅 2GB 内存的 Mac 上运行](#item-1) ⭐️ 9.0/10
2. [文档携带的 AI 蠕虫可通过 Word 版 Copilot 自我传播](#item-2) ⭐️ 9.0/10
3. [Mitchell Hashimoto 宣布成立 Superlogical，将 Ghostty 转让给非营利组织](#item-3) ⭐️ 8.0/10
4. [KOReader：开源电子书阅读器提升墨水屏设备体验](#item-4) ⭐️ 8.0/10
5. [Handbook.md 研究表明长政策文档无法可靠约束 AI 智能体](#item-5) ⭐️ 8.0/10
6. [Matthew Green 谈后量子密码与 AI 密码分析](#item-6) ⭐️ 8.0/10
7. [Kimi AI 完成 35 亿美元 F 轮融资，估值 350 亿美元](#item-7) ⭐️ 8.0/10
8. [腾讯混元开源 AngelSpec](#item-8) ⭐️ 8.0/10
9. [Claude 共享对话和 Artifacts 被谷歌索引，Anthropic 称符合设计](#item-9) ⭐️ 8.0/10
10. [俄罗斯指控 Telegram 创始人杜罗夫协助恐怖活动](#item-10) ⭐️ 8.0/10
11. [报告：Hugging Face 被广泛用于生成深度伪造裸照](#item-11) ⭐️ 8.0/10
12. [中国起草反网络暴力法，专门规制 AI 生成的网暴内容](#item-12) ⭐️ 8.0/10
13. [Kimi 推出更便宜的 K3-256k，支持 256K 上下文](#item-13) ⭐️ 7.0/10
14. [AI 公司大量招聘技工建设数据中心](#item-14) ⭐️ 7.0/10
15. [SQLite 作者：SQL 改变了工作，而非消除](#item-15) ⭐️ 7.0/10
16. [指南：为 Claude 和 ChatGPT 添加自定义 MCP 服务器](#item-16) ⭐️ 7.0/10
17. [Claude Mythos 发现 HAWK 与 AES 的密码分析弱点](#item-17) ⭐️ 7.0/10
18. [模块化数据中心：像乐高一样解决劳动力困境](#item-18) ⭐️ 7.0/10
19. [柔性触觉感知初创尧乐科技完成 Pre-A+轮融资，用于数据手套](#item-19) ⭐️ 7.0/10
20. [报告：中国智能硬件进入 AI 原生阶段](#item-20) ⭐️ 7.0/10
21. [美国向 7 家科技公司提供 8.74 亿美元半导体研发资金](#item-21) ⭐️ 7.0/10
22. [ICLR 2027 截稿日期早于 NeurIPS 2026 决定](#item-22) ⭐️ 7.0/10
23. [ncnn Vulkan 后端在边缘设备上实现 10 倍 ML 推理加速](#item-23) ⭐️ 7.0/10
24. [xAI 起诉明尼苏达州阻止 AI 脱衣禁令](#item-24) ⭐️ 7.0/10
25. [Windows 11 静默安装 OneDrive Photos 并支持人脸扫描](#item-25) ⭐️ 7.0/10
26. [中国禁止新认证车辆安装自动驾驶'小蓝灯'](#item-26) ⭐️ 7.0/10
27. [闲鱼 AI 服务订单半年增 157%](#item-27) ⭐️ 7.0/10
28. [中国电信停止第三方互联网渠道销售 SIM 卡](#item-28) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [开源引擎让 Gemma 4 26B 在仅 2GB 内存的 Mac 上运行](https://github.com/drumih/turbo-fieldfare) ⭐️ 9.0/10

TurboFieldfare 是一个用 Swift 和 Metal 编写的开源推理引擎，能够在任何 M 系列 Mac 上以仅约 2 GB 内存运行 4 位量化的 Gemma 4 26B-A4B-IT 模型。它在 8 GB M2 MacBook Air 上达到 5–6 tok/s，在 M5 MacBook Pro 上达到 31–35 tok/s，通过从 SSD 流式传输路由专家来实现。 这一突破使得在内存受限的设备（如标准 MacBook）上运行具有 14 GB 权重的混合专家模型成为可能，极大地扩展了设备端 AI 的可及性。它挑战了将整个模型放入 RAM 的传统方法，并为边缘推理开辟了新的可能性。 该引擎将共享模型层和 KV 缓存保留在 RAM 中，同时仅从 SSD 流式传输每个 token 所需的路由专家，使用一个小的专家缓存和有界并行 pread。它还包含一个实验性的兼容 OpenAI 的本地服务器，支持流式和工具调用，并重用 KV 缓存中的一个提示前缀。

hackernews · gitpusher42 · 7月29日 15:05 · [社区讨论](https://news.ycombinator.com/item?id=49098510)

**背景**: Gemma 4 26B-A4B-IT 是谷歌的混合专家模型，总参数量 260 亿，但每个 token 仅激活约 40 亿参数，因为它使用路由专家。4 位量化将权重精度降至每个值 4 位，显著缩小模型大小同时保持精度。传统推理工具需要将所有权重加载到 RAM 中，这对于内存有限的设备上的大型模型是不可行的。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mixture_of_experts">Mixture of experts - Wikipedia</a></li>
<li><a href="https://huggingface.co/blog/moe">Mixture of Experts Explained</a></li>
<li><a href="https://www.emergentmind.com/topics/4-bit-model-quantization">4-Bit Model Quantization - emergentmind.com</a></li>

</ul>
</details>

**社区讨论**: 社区讨论显示出强烈的兴趣和技术深度。用户将其方法与 llama.cpp 的 mmap 进行了比较，指出 TurboFieldfare 将 SSD 读取与推理同步以降低延迟。一些人提供了旧版 macOS 的兼容性提示，其他人则询问在非 Mac 平台（如 Debian 或 Jetson）上运行的可能性。总体情绪积极，许多人对其克服内存限制的实用工程印象深刻。

**标签**: `#inference`, `#model compression`, `#edge AI`, `#open-source`, `#Gemma`

---

<a id="item-2"></a>
## [文档携带的 AI 蠕虫可通过 Word 版 Copilot 自我传播](https://enklypesalt.com/posts/context-collapse-part3-ai-worming-through-word/) ⭐️ 9.0/10

安全研究员 Håkon Måløy 展示了一种新型 AI 蠕虫，它利用提示注入在 Microsoft Word 的 Copilot 功能中自我复制，通过将恶意指令嵌入文档，使 Copilot 将攻击传播到新文档。 这是首个有记录的利用主流办公生产力工具进行自我复制的 AI 蠕虫案例，突显了基于 LLM 的助手在指令与数据混合方面的根本安全缺陷。如果不加以解决，可能导致大规模数据泄露和自动化恶意软件传播。 该攻击将提示注入升级为完整蠕虫，通过让 Copilot 重写文档以包含恶意提示，进而感染打开这些文档的其他用户。自 2026 年 3 月起微软已收到通知，但截至发表时该漏洞仍未得到缓解。

hackernews · Canopy9560 · 7月29日 11:44 · [社区讨论](https://news.ycombinator.com/item?id=49096188)

**背景**: 提示注入攻击利用了大语言模型（LLM）无法区分可信指令与不可信用户输入或数据的缺陷。当 Copilot 这样的 LLM 处理文档时，它可能将文档中的文本视为命令，允许攻击者构造恶意提示来劫持模型行为。AI 蠕虫通过增加自我复制能力扩展了这种攻击，使攻击能够自主跨系统传播。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/ai-worms">AI Worms: Autonomous Self-Propagating Malware</a></li>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection_attack">Prompt injection attack</a></li>
<li><a href="https://www.theregister.com/security/2026/07/29/word-worm-crawls-into-copilot-spreads-chaos/5280588">Word worm crawls into Copilot, spreads chaos - The Register</a></li>

</ul>
</details>

**社区讨论**: 社区评论表达了对此类漏洞修复难度的强烈担忧，有评论者指出只要指令和数据混合在一起，这类攻击从根本上就无法避免。另一条评论描述了拥有过多权限的 AI 代理如何被利用来窃取凭证并通过 GitHub 传播。一些用户已经卸载了 Copilot 以保护数据。

**标签**: `#AI Security`, `#Copilot`, `#Worms`, `#Prompt Injection`, `#LLM Vulnerabilities`

---

<a id="item-3"></a>
## [Mitchell Hashimoto 宣布成立 Superlogical，将 Ghostty 转让给非营利组织](https://www.superlogical.com/) ⭐️ 8.0/10

Mitchell Hashimoto 宣布成立新公司 Superlogical，该公司将在开源库 libghostty 之上构建终端应用。同时，他已将 Ghostty 终端模拟器的所有权转让给一个非营利组织。 这位知名开发者的此举展示了一种可持续的开源商业模式：公司在社区拥有的核心库上构建商业产品。这可能会鼓励更多开发者采用 libghostty 作为终端工具的基础。 Superlogical 将使用基于 MIT 许可证的 libghostty 作为其终端应用的公共构建模块，并将共享的工作上游回馈给社区。Ghostty 以其 GPU 加速性能和支持原生 UI 而闻名，最初由 Hashimoto 创建并已获得广泛认可。

hackernews · yan · 7月29日 15:41 · [社区讨论](https://news.ycombinator.com/item?id=49098965)

**背景**: Ghostty 是一款快速、功能丰富、跨平台的终端模拟器，采用 GPU 加速和平台原生 UI。其核心用 Zig 实现，即 libghostty 库，这是一个零依赖的 C 和 Zig 库，用于构建终端模拟器。通过将 Ghostty 转让给非营利组织，Hashimoto 确保该终端模拟器保持社区治理。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/ghostty-org/ghostty">GitHub - ghostty -org/ ghostty : Ghostty is a fast, feature-rich, and...</a></li>
<li><a href="https://ghostty.org/docs/about">About Ghostty</a></li>
<li><a href="https://ghostty.org/">Ghostty</a></li>

</ul>
</details>

**社区讨论**: 评论者大多称赞其开源和非营利结构，用户 simonw 强调 Superlogical 将把 libghostty 作为公共依赖进行构建。另一位评论者将其与 OLE/COM 技术进行类比，指出这种可组合系统的强大与复杂性。少数用户批评标题具有点击诱饵性质或信息量不足。

**标签**: `#terminal`, `#open-source`, `#developer-tools`, `#Mitchell Hashimoto`, `#libghostty`

---

<a id="item-4"></a>
## [KOReader：开源电子书阅读器提升墨水屏设备体验](https://koreader.rocks/) ⭐️ 8.0/10

KOReader 是一款针对电子墨水屏设备的开源文档查看器，支持 EPUB、PDF、DjVu 等多种文件格式，提供超越原生固件的可定制阅读体验。 它提供了一个免费、社区驱动的专有软件替代方案，支持原生格式和阅读进度同步等增强功能，极大地提升了 Kindle 和 Kobo 等设备上的用户体验。 KOReader 支持 EPUB、PDF、DjVu、XPS、CBT、CBZ、FB2、PDB、TXT、HTML、RTF、CHM、DOC、MOBI 和 ZIP 文件，可在越狱的 Kindle 及其他 E Ink 设备上安装。部分用户反映其界面不够直观且有时会卡顿。

hackernews · Cider9986 · 7月29日 11:05 · [社区讨论](https://news.ycombinator.com/item?id=49095865)

**背景**: Kindle、Kobo 等电子墨水屏设备通常运行专有固件，格式支持有限，常需转换 EPUB 等常用格式。KOReader 是一款运行在这些设备上的开源替代软件，提供广泛的文件格式兼容性以及手势、插件等可自定义功能，多被越狱设备爱好者用于获得更自由的阅读体验。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://grokipedia.com/page/KOReader">KOReader</a></li>
<li><a href="https://koreader.rocks/">KOReader</a></li>

</ul>
</details>

**社区讨论**: 社区反馈褒贬不一：许多用户称赞 KOReader 显著提升了阅读体验，认为优于专有软件；另一些用户则认为界面不直观，存在延迟和手势问题。部分用户仍偏好默认阅读器，并指出边框对齐和书籍排版方面的困难。

**标签**: `#e-reader`, `#open-source`, `#kindle`, `#kobo`, `#software`

---

<a id="item-5"></a>
## [Handbook.md 研究表明长政策文档无法可靠约束 AI 智能体](https://arxiv.org/abs/2607.25398) ⭐️ 8.0/10

一项名为 HANDBOOK.md 的新基准测试评估 AI 智能体能否遵循长达 124 页的企业政策手册。表现最佳的模型配置仅达到 36.2%的通过率，且智能体在 78%的任务中跳过了政策规则。 这一发现凸显了当前大型语言模型在需要严格遵循政策的真实智能体应用中的关键局限。它削弱了 AI 智能体在企业环境中的可靠性，并呼吁更好的长上下文处理或替代设计。 该基准包含长达 100 多页的手册，早期测试中没有前沿模型能通过 25%的任务。社区评论将失败归因于长上下文中 KV 缓存的极端量化以及糟糕的采样器配置，并指出本地推理可以缓解该问题。

hackernews · spIrr · 7月29日 13:01 · [社区讨论](https://news.ycombinator.com/item?id=49096969)

**背景**: 大型语言模型有上下文窗口限制，但近期模型声称支持数百万 token。然而，由于注意力机制的二次缩放和内存限制，有效利用长上下文仍然具有挑战性。政策合规是自主执行业务工作流的 AI 智能体的关键要求。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://surgehq.ai/blog/handbook-md">HANDBOOK.md Benchmark: Can AI Agents Follow a 100-Page ...</a></li>
<li><a href="https://elsolitario.org/en/2026/07/29/handbook-md-benchmark-ai-agents-corporate-policies/">AI Agents in HANDBOOK.md: Only 36.2% Pass Rate</a></li>
<li><a href="https://byteiota.com/ai-agents-skip-policy-rules-78-of-tasks-new-data/">AI Agents Skip Policy Rules 78% of Tasks—New Data | byteiota</a></li>

</ul>
</details>

**社区讨论**: 用户报告称，长上下文模型在交互几分钟后往往会忽略早期指令，当前提示中的明确指令比 CLAUDE.md 等持久文件更有效。一些评论者批评论文在“设计原则”等部分使用了 AI 生成内容，指出写作质量较差。

**标签**: `#large language models`, `#long context`, `#AI agents`, `#policy compliance`, `#LLM limitations`

---

<a id="item-6"></a>
## [Matthew Green 谈后量子密码与 AI 密码分析](https://simonwillison.net/2026/Jul/29/matthew-green/#atom-everything) ⭐️ 8.0/10

Matthew Green 指出，向后量子密码学的历史性转型使得当前成为 AI 推动密码分析的最佳时机，这有望增强对新算法（如 HAWK）的信心。 这一见解凸显了 AI 为即将推出的密码标准加强安全性的独特机会，对于保护数据免受未来量子攻击至关重要。 Green 提到了 HAWK（一种正在由 NIST 考虑的基于格的签名方案）以及 Impagliazzo 的 Minicrypt 世界（其中公钥密码不可能存在），暗示 AI 要么破坏、要么验证后量子密码的假设。

rss · Simon Willison · 7月29日 18:18

**背景**: 后量子密码学（PQC）旨在开发能够抵抗经典计算机和量子计算机攻击的算法。当前的公钥算法（如 RSA 和 ECC）在面对强大的量子计算机上的 Shor 算法时存在漏洞。NIST 正在标准化 PQC 算法，HAWK 是评估中的算法之一。Impagliazzo 的五世界模型对计算复杂性场景进行分类；Minicrypt 假设存在单向函数但没有公钥密码。由于'先收集、后解密'的威胁，向 PQC 的过渡十分紧迫。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Post-quantum_cryptography">Post-quantum cryptography</a></li>
<li><a href="https://hawk-sign.info/">Hawk</a></li>
<li><a href="https://blog.computationalcomplexity.org/2004/06/impagliazzos-five-worlds.html">Computational Complexity: Impagliazzo's Five Worlds</a></li>

</ul>
</details>

**标签**: `#post-quantum cryptography`, `#AI cryptanalysis`, `#cryptography standards`, `#Matthew Green`, `#public-key algorithms`

---

<a id="item-7"></a>
## [Kimi AI 完成 35 亿美元 F 轮融资，估值 350 亿美元](https://36kr.com/p/3916547493965442?f=rss) ⭐️ 8.0/10

中国 AI 初创公司月之暗面（Kimi）完成了超过 35 亿美元的 F 轮融资，投后估值达 350 亿美元。该轮融资因超额认购提前关闭，公司已启动 Pre-IPO 轮融资，投前估值 500 亿美元。 这一巨额融资轮凸显了全球 AI 领域的激烈竞争，尤其是中美之间的较量。它表明投资者对 Kimi 技术（尤其是其 K3 模型）的强烈信心，该模型据称媲美 OpenAI 和 Anthropic 的能力。 Kimi 在 6 月的年化经常性收入达到 3 亿美元，K3 模型发布后日销售额增长至少 6 倍。该公司计划最早今年内在香港 IPO。

rss · 36kr · 7月29日 11:04

**背景**: 月之暗面（Moonshot AI）以其 Kimi 聊天机器人闻名，是中国领先的 AI 初创公司。K3 模型的发布引发了科技股抛售， reminiscent of 'DeepSeek moment'，即中国模型令市场惊讶。该初创公司的快速收入增长和高估值凸显了 AI 军备竞赛中的高风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.lydaas.com/agentone">AgentOne企业级Agent平台 - 瓴羊 - lydaas.com</a></li>
<li><a href="https://www.aliyun.com/product/agentone">AgentOne</a></li>
<li><a href="https://zhuanlan.zhihu.com/p/1962257214417934168">瓴羊 AgentOne：阿里用十年场景沉淀切入企业级 Agent</a></li>

</ul>
</details>

**标签**: `#AI funding`, `#startups`, `#Chinese tech`, `#venture capital`

---

<a id="item-8"></a>
## [腾讯混元开源 AngelSpec](https://36kr.com/newsflashes/3916684374371721?f=rss) ⭐️ 8.0/10

2024 年 7 月 29 日，腾讯混元团队宣布正式开源 AngelSpec，这是一个投机解码框架，并同步开源了 Hy3-A21B 的 MTP 与 DFly drafter 权重及训练代码。 此次开源提供了从训练到部署的完整流程，使研究人员和开发者能够更高效地利用投机解码加速大语言模型推理，在保持输出质量不变的情况下将延迟降低 2-3 倍。 AngelSpec 是一个基于 PyTorch 的原生框架，覆盖 drafter 训练、架构设计和线上部署，并包含了多 token 预测（MTP）和块并行 DFlash 两类 drafter。

rss · 36kr · 7月29日 12:17

**背景**: 投机解码是一种大语言模型优化技术，其中一个小型的 draft 模型并行生成多个候选 token，然后由更大的目标模型在一个前向传播中验证这些 token。这可以将推理速度提升约 2-3 倍，同时保持原始输出分布不变。AngelSpec 是一个统一框架，简化了这类 draft 模型的训练和部署。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Speculative_decoding">Speculative decoding</a></li>
<li><a href="https://github.com/Tencent/AngelSpec/">GitHub - Tencent/AngelSpec: A unified, torch-native training ...</a></li>

</ul>
</details>

**标签**: `#speculative decoding`, `#LLM inference`, `#open-source`, `#Tencent`, `#AngelSpec`

---

<a id="item-9"></a>
## [Claude 共享对话和 Artifacts 被谷歌索引，Anthropic 称符合设计](https://thenextweb.com/news/claude-shared-chats-artifacts-google-search-indexed) ⭐️ 8.0/10

上周末，Claude 用户的共享对话和 Artifacts 链接被谷歌索引，导致医疗记录、公司文件等敏感数据公开暴露。Anthropic 表示系统未被入侵，索引行为是因为用户主动生成了共享链接，被搜索引擎抓取，属于符合预期的设计。 这一事件凸显了依赖共享内容功能的 AI 用户面临的重大隐私风险，敏感信息可能在未经明确同意的情况下被公开搜索。它引发了人们对 AI 聊天平台共享功能设计的担忧，尤其是在 ChatGPT 和 Grok 也曾出现类似问题的情况下。 Anthropic 于周一下午阻止了新的索引，但已被索引的旧链接仍然可访问。用户可以在设置中撤销已共享的链接。2025 年 9 月曾发生类似事件，近 600 条 Claude 对话被索引。

telegram · zaihuapd · 7月29日 02:40

**背景**: Claude 的共享功能允许用户为对话或 Artifacts（交互式代码预览）创建公开链接。这些链接本用于直接分享，但若被发布到公开网站，搜索引擎爬虫就可能发现并索引它们。ChatGPT 和 Grok 此前也出现过类似的隐私问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.zdnet.com/article/claude-ai-shared-chats-indexed-by-google/">Claude AI shared chats indexed by Google - see if your conversations were exposed | ZDNET</a></li>
<li><a href="https://support.claude.com/en/articles/10593882-share-and-unshare-chats">Share and unshare chats | Claude Help Center</a></li>

</ul>
</details>

**社区讨论**: Reddit 用户使用 Google dork 查询'site:claude.ai/share'发现了这一暴露。社区对敏感数据泄露表示担忧，并批评 Anthropic 缺乏充分的保护措施。也有观点认为用户应避免分享私密信息。

**标签**: `#privacy`, `#security`, `#AI`, `#Claude`, `#search indexing`

---

<a id="item-10"></a>
## [俄罗斯指控 Telegram 创始人杜罗夫协助恐怖活动](https://www.interfax.ru/russia/1106228) ⭐️ 8.0/10

俄罗斯联邦安全局（FSB）已依据《刑法》第 205.1 条对 Telegram 创始人帕维尔·杜罗夫提起刑事指控，指控其协助恐怖活动，并将其列入国际通缉名单。 这标志着国家对主要科技平台创始人的行动显著升级，可能对全球言论自由和平台治理产生寒蝉效应，尤其对 Telegram 等加密消息服务影响深远。 FSB 指控 Telegram 管理层拒不删除被乌克兰情报机构及恐怖、极端主义组织用于在俄罗斯境内策划破坏活动、恐怖袭击和诈骗的频道、群组和机器人，造成数十人伤亡和数十亿卢布损失。

telegram · zaihuapd · 7月29日 05:56

**背景**: Telegram 是由帕维尔·杜罗夫创立的广泛使用的加密消息应用，杜罗夫于 2014 年离开俄罗斯。FSB 是俄罗斯的主要安全机构，负责反情报和反恐。第 205.1 条指控涉及为恐怖活动提供协助。

**标签**: `#Telegram`, `#Pavel Durov`, `#Russia`, `#terrorism`, `#tech policy`

---

<a id="item-11"></a>
## [报告：Hugging Face 被广泛用于生成深度伪造裸照](https://www.theverge.com/ai-artificial-intelligence/971723/hugging-face-nudify-deepfake-undress-women-children) ⭐️ 8.0/10

欧洲非营利组织 AI Forensics 于 7 月 28 日发布报告，指出开源模型托管平台 Hugging Face 正被大量用于生成非自愿深度伪造色情内容。研究人员发现，其排名前九的图像编辑模型中有七个能轻易按简单提示为女性“脱衣”，该机构设置的蜜罐在 7 天内收到逾 1000 条请求，其中 73%涉性内容，近 7%针对儿童。 该报告揭示了 Hugging Face 在平台级防护措施上的严重漏洞，与其禁止非自愿性内容及未成年人裸露的政策相违背。这凸显了 AI 平台亟需加强提示词过滤与输出扫描机制，以防止开源模型被滥用。 研究人员无需精心构造绕过话术，简单提示即可生成露骨图像。AI Forensics 建议 Hugging Face 增加提示词过滤与输出扫描机制，以阻止有害图像生成。

telegram · zaihuapd · 7月29日 08:20

**背景**: 深度伪造（Deepfake）是指利用深度学习等人工智能技术生成或篡改图像、视频、音频，将一个人的形象或声音替换为另一个人的技术。蜜罐（Honeypot）是一种网络安全机制，通过设置诱饵系统来吸引并检测恶意行为。Hugging Face 是一个流行的机器学习模型托管与分享平台，上面有许多图像生成模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://zh.wikipedia.org/wiki/深伪技术">深伪技术 - 维基百科，自由的百科全书</a></li>
<li><a href="https://zh.wikipedia.org/wiki/蜜罐_(電腦科學)">蜜 罐 (電腦科學) - 维基百科，自由的百科全书</a></li>
<li><a href="https://en.wikipedia.org/wiki/Hugging_Face">Hugging Face</a></li>

</ul>
</details>

**标签**: `#AI安全`, `#深度伪造`, `#Hugging Face`, `#伦理`, `#平台责任`

---

<a id="item-12"></a>
## [中国起草反网络暴力法，专门规制 AI 生成的网暴内容](https://mp.weixin.qq.com/s/PrzKFhbwjgFEGBPADvFD6Q) ⭐️ 8.0/10

2026 年 7 月 29 日，国家互联网信息办公室公布反网络暴力法征求意见稿，明确对利用 AI 技术制作、传播网络暴力信息进行专门规制。草案共六十条，要求网络平台建立监测识别和防护功能。 这是重要的监管举措，直接应对 AI 生成网暴内容这一日益严峻的挑战——AI 网暴可能快速扩散且绕过传统审核。该法将重塑平台责任，为受害者提供更强有力的法律保护。 草案引入人格权侵害禁令，受害者可申请法院责令停止侵害。草案同时明确受害者有权请求精神损害赔偿。征求意见截止日期为 2026 年 8 月 28 日。

telegram · zaihuapd · 7月29日 10:59

**背景**: 网络暴力在中国已成为严重的社会问题，涉及“开盒”（人肉搜索）和有组织的网络攻击。根据《民法典》，人格权为姓名、肖像、隐私、名誉等提供法律保护。近期，抖音等平台已部署 AI 反网暴系统，主动识别网暴行为。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.guancha.cn/economy/2026_06_12_820308.shtml">抖音上线AI反网暴Agent - 观察者网</a></li>
<li><a href="http://dyzy.sdcourt.gov.cn/dyzy/372897/372830/28560321/index.html">人格权侵害禁令的实务要点与裁判规则</a></li>
<li><a href="https://www.hualianlaw.com/sys-nd/449.html">一文看懂“人格权侵害禁令”！丨上海市华联律师事务所</a></li>

</ul>
</details>

**标签**: `#AI regulation`, `#cyberbullying`, `#China law`, `#AI ethics`, `#online safety`

---

<a id="item-13"></a>
## [Kimi 推出更便宜的 K3-256k，支持 256K 上下文](https://www.kimi.com/code/docs/en/kimi-code/models) ⭐️ 7.0/10

Moonshot AI 发布了 Kimi K3-256k，这是 K3 模型的一个变体，拥有 256k token 的上下文窗口，其配额价格仅为原版 1M 上下文 K3 的一半，且在 256k 范围内性能完全相同。 这实际上使大多数不需要完整 1M 上下文的用户成本减半，让先进的 AI 能力更易获取，同时减轻了 Kimi 服务器的基础设施压力。 K3-256k 消耗的配额约为 1M 版本的一半，且在 256k 上下文内输出相同结果。原版 Kimi K3 拥有 2.8 万亿参数，于 2026 年 7 月 16 日发布并开源权重。

hackernews · monneyboi · 7月29日 19:25 · [社区讨论](https://news.ycombinator.com/item?id=49101852)

**背景**: 上下文窗口是指 AI 模型单次请求能处理的最大 token 数量。更大的上下文窗口可以处理更长的文档或代码库，但会增加计算成本。Kimi K3 是 Moonshot AI 的大型语言模型，拥有 1M token 的上下文窗口。新的 K3-256k 变体面向很少超过 200k token 的用户，提供了一个高性价比的选择。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/blog/ResterChed/kimi-k3-model-overview-mxfp4-quantization-open-wei">Kimi K 3 Model Overview: 2.8T Parameters, MXFP4 Quantization, and...</a></li>
<li><a href="https://www.digitalapplied.com/blog/ai-context-window-comparison-2026-1m-to-10m-tokens">AI Context Window Comparison 2026: 1M to 10M Tokens</a></li>
<li><a href="https://kimi-ai.chat/models/kimi-k3/">Kimi K 3 : 1M Context , API Pricing & Limits</a></li>

</ul>
</details>

**社区讨论**: 社区成员普遍欢迎 256k 变体，称这对典型使用场景是巨大的降价。一些用户对近期模型质量下降表示担忧，怀疑被提供了量化模型，但总体情绪积极。

**标签**: `#AI`, `#LLM`, `#model pricing`, `#context window`, `#cost efficiency`

---

<a id="item-14"></a>
## [AI 公司大量招聘技工建设数据中心](https://www.nytimes.com/2026/07/29/business/economy/data-center-electricians-training.html) ⭐️ 7.0/10

AI 公司正在招聘成千上万的电工、木匠等技工来建设和维护数据中心，标志着劳动力从传统建筑向技术基础设施的重大转移。 这一趋势凸显了 AI 行业对熟练技工日益增长的需求，可能重塑劳动力市场并为技工提供高薪机会。然而，数据中心建设的繁荣-萧条周期可能导致工作不稳定。 数据中心现在需要复杂的电气和冷却系统，未来设计倾向于液体冷却，可能增加对水管工的需求。《纽约时报》报道 AI 公司正在大量招聘，但未给出具体数字。

hackernews · thm · 7月29日 14:43 · [社区讨论](https://news.ycombinator.com/item?id=49098198)

**背景**: 数据中心是容纳服务器和计算设备的设施，用于云服务、AI 训练等数字运营。随着 AI 模型变得更大，它们需要巨大的计算能力，导致数据中心建设激增。这造成了技工需求，如电工负责电力系统、木匠负责建筑结构，以及未来的水管工负责液体冷却系统。

**社区讨论**: 社区评论者表达了不同观点：一些人警告数据中心工作的繁荣-萧条周期可能导致收入波动，而另一些人指出向液体冷却的转变可能会增加对水管工的需求。几位评论者对技工获得高薪工作感到高兴。

**标签**: `#AI`, `#data centers`, `#skilled trades`, `#labor market`, `#infrastructure`

---

<a id="item-15"></a>
## [SQLite 作者：SQL 改变了工作，而非消除](https://simonwillison.net/2026/Jul/29/d-richard-hipp/#atom-everything) ⭐️ 7.0/10

SQLite 的创建者 D. Richard Hipp 将 SQL 的出现与编程工作的演变进行了类比，指出 SQL 取代了昂贵的 COBOL 程序员进行数据查询的需求，但并未消除程序员——只是改变了他们的角色。 这一观点为当前关于 AI 和自动化取代软件工程师的担忧提供了令人安心的历史先例：新工具只是转移而非破坏工作。它强调了技术职业中适应性的持久价值。 Hipp 在一段 YouTube 采访中表示，在 SQL 出现之前，大规模数据查询是由 COBOL 程序员完成的——这是一个专业化且成本高昂的角色。SQL 的声明式语法允许用户简单地指定查询，从而自动化了大部分工作。

rss · Simon Willison · 7月29日 21:15

**背景**: COBOL（Common Business-Oriented Language）是一种冗长、类似英语的编程语言，专为商业数据处理设计，自 20 世纪 60 年代以来在大型机上广泛使用。SQL（Structured Query Language）是一种用于管理关系数据库的领域特定语言，于 20 世纪 70 年代推出。从 COBOL 到 SQL 的转变使数据查询对更多人变得可及，减少了对专门程序员的需求。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/COBOL_programming_language">COBOL programming language</a></li>

</ul>
</details>

**标签**: `#d-richard-hipp`, `#sql`, `#careers`, `#technology-evolution`

---

<a id="item-16"></a>
## [指南：为 Claude 和 ChatGPT 添加自定义 MCP 服务器](https://simonwillison.net/2026/Jul/29/mcp-in-claude-and-chatgpt/#atom-everything) ⭐️ 7.0/10

Simon Willison 发布了一篇详细教程，解释如何将自定义的模型上下文协议（MCP）服务器连接到 Claude 和 ChatGPT 的标准聊天界面。这使开发者能够用自定义的外部工具扩展这些 AI 助手的的能力。 本教程降低了开发者将自定义工具集成到广泛使用的 AI 聊天界面的门槛，展示了 MCP 标准的实际应用。它使用户能够通过连接外部数据源和服务来创建更通用的 AI 代理。 设置过程包括在 Claude 和 ChatGPT 的界面中配置 MCP 客户端设置，指向本地运行的 MCP 服务器。服务器必须符合 MCP 规范，并且客户端可以访问，这需要仔细的网络和身份验证配置。

rss · Simon Willison · 7月29日 00:13

**背景**: 模型上下文协议（MCP）是 Anthropic 于 2024 年 11 月推出的开放标准，旨在标准化大语言模型等 AI 系统与外部工具和数据的集成方式。MCP 服务器通过统一接口暴露特定能力（如文件系统访问、数据库查询）。本教程展示了如何设置自定义 MCP 服务器，以便与 Claude 和 ChatGPT 一起使用，扩展它们的内置功能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Model_Context_Protocol">Model Context Protocol - Wikipedia</a></li>
<li><a href="https://modelcontextprotocol.io/docs/getting-started/intro">What is the Model Context Protocol (MCP)?</a></li>

</ul>
</details>

**标签**: `#ai`, `#generative-ai`, `#chatgpt`, `#claude`, `#model-context-protocol`

---

<a id="item-17"></a>
## [Claude Mythos 发现 HAWK 与 AES 的密码分析弱点](https://simonwillison.net/2026/Jul/28/discovering-cryptographic-weaknesses-with-claude/#atom-everything) ⭐️ 7.0/10

Anthropic 的研究人员使用强大的大语言模型 Claude Mythos，发现了 HAWK 签名方案和简化轮数的 AES 中的数学缺陷，尽管这两项发现对当前系统没有实际影响。 这展示了 LLM 在密码分析中的新颖应用，表明它们可以帮助发现微妙的数学弱点，尽管目前没有直接实际威胁，但可能加速密码学研究。 Claude Mythos Preview 运行了 60 小时，估计 API 成本约 10 万美元，需要人工提示以鼓励其坚持和更高目标。该研究还产生了 CryptanalysisBench，一个评估 LLM 密码分析能力的新基准。

rss · Simon Willison · 7月28日 22:45

**背景**: HAWK 是一种基于格基的签名方案，已提交给 NIST 的后量子密码标准化流程，旨在抵抗经典和量子攻击。AES（高级加密标准）是一种广泛使用的对称加密算法；简化轮数的版本加密轮数更少，已知更弱。Claude Mythos 是 Anthropic 开发的高能力 LLM，因其能够发现软件漏洞而受到访问限制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://hawk-sign.info/">Hawk</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_Mythos">Claude Mythos</a></li>
<li><a href="https://en.wikipedia.org/wiki/Advanced_Encryption_Standard">Advanced Encryption Standard - Wikipedia</a></li>

</ul>
</details>

**标签**: `#AI`, `#cryptography`, `#LLM`, `#research`

---

<a id="item-18"></a>
## [模块化数据中心：像乐高一样解决劳动力困境](https://newsletter.semianalysis.com/p/the-wild-wild-west-of-lego-datacenters) ⭐️ 7.0/10

Semianalysis 的最新分析探讨了数据中心建设如何越来越多地转向像乐高积木一样的模块化组装方法，以解决关键的劳动力短缺问题。 随着超大规模数据中心需求激增且熟练劳动力短缺，模块化施工提供了一条更快速、更可扩展的路径来满足容量需求，正在重塑行业的建设策略。 模块化数据中心使用预制“积木”，每块重达 5 万磅，在现场像乐高套装一样组装，从而实现更快速的部署并减少对稀缺熟练工人的依赖。

rss · Semianalysis · 7月29日 22:09

**背景**: 模块化数据中心系统涉及可快速部署和扩展的便携式标准化模块。传统数据中心建设需要大量现场劳动力，且面临严重的熟练工人短缺。模块化方法常被比作拼搭乐高积木，可提高速度、成本效益和灵活性，因此对超大规模项目越来越有吸引力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://newsletter.semianalysis.com/p/the-wild-wild-west-of-lego-datacenters">The Wild Wild West Of LEGO Datacenters</a></li>
<li><a href="https://en.wikipedia.org/wiki/Modular_data_center">Modular data center - Wikipedia</a></li>
<li><a href="https://www.bjumper.com/en_GB/blog/technology-3/modular-data-center-architecture-181">How would a data center look if LEGO designed it?</a></li>

</ul>
</details>

**标签**: `#datacenters`, `#infrastructure`, `#modularization`, `#labor`, `#tech industry`

---

<a id="item-19"></a>
## [柔性触觉感知初创尧乐科技完成 Pre-A+轮融资，用于数据手套](https://36kr.com/p/3915175290901889?f=rss) ⭐️ 7.0/10

柔性触觉感知初创公司尧乐科技完成 Pre-A+轮融资，由鼎和高达领投，上市公司常熟汽饰和祖龙娱乐跟投。资金将用于开发织物传感器数据手套，该手套将传感功能直接嵌入织物结构，面向具身智能和世界模型的数据采集。 本轮融资凸显了高质量真实触觉数据的严重短缺，这类数据对于训练具身智能和世界模型至关重要，而数据手套正成为采集此类数据的关键接口。尧乐的一体化织物传感器设计有望提升数据可靠性和规模化部署能力，解决机器人及 AI 行业的数据瓶颈。 尧乐的手套采用自主研发的'金属纱线+三明治矩阵'传感器，将金属拉丝合金纱线直接编织到织物矩阵中。这消除了多层印刷薄膜设计常见的层间滑移和汗渍问题，实现了材料与器件一体化。手套还采用模块化设计，织物可水洗，集成的控制盒内置广角摄像头用于交叉验证。

rss · 36kr · 7月29日 01:30

**背景**: 具身智能（Embodied Intelligence）指通过传感器和驱动器与物理世界交互并学习的人工智能系统，需要丰富的多模态数据（包括触觉）。世界模型（World Model）是学习环境内部表示以模拟物理动力学的人工智能系统。然而，由于压力分布、摩擦力等复杂物理特性，触觉数据难以精准仿真，存在模拟到现实的差距（sim-to-real gap）。能够捕捉真实人机触摸交互的数据手套是提供高质量训练数据、训练通用具身模型的解决方案之一。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Embodied_intelligence">Embodied intelligence</a></li>
<li><a href="https://en.wikipedia.org/wiki/World_model_(artificial_intelligence)">World model (artificial intelligence)</a></li>
<li><a href="https://arxiv.org/html/2602.21625v1">Tacmap: Bridging the Tactile Sim-to-Real Gap via Geometry ...</a></li>

</ul>
</details>

**标签**: `#flexible tactile sensing`, `#embodied intelligence`, `#robotics`, `#startup funding`, `#data gloves`

---

<a id="item-20"></a>
## [报告：中国智能硬件进入 AI 原生阶段](https://36kr.com/p/3915066350327176?f=rss) ⭐️ 7.0/10

36 氪研究院发布《2026 年中国智能硬件行业发展研究报告》，指出行业已从单品智能化迈入 AI 原生阶段，端侧自主智能正在重构产品核心逻辑。报告显示 80.8%的消费者已使用 AI 硬件，端侧 AI 芯片、轻量化大模型、多传感融合等关键技术取得突破。 该报告系统分析了中国智能硬件行业转型，为投资者、制造商和政策制定者提供了重要参考。向端侧自主智能的 AI 原生硬件过渡可能重塑全球竞争格局，中国企业正从低价代工转向技术、生态与服务的复合价值输出。 报告显示 32%的消费者计划未来三个月增加 AI 硬件消费，同时指出行业面临碎片化竞争加剧、供应链成本承压、场景规模化落地不足、数据安全合规要求升级等挑战。智能机器人（包括人形和非人形）被视为跨场景增长新动力。

rss · 36kr · 7月28日 23:30

**背景**: 智能硬件是指集成 AI 能力的物理设备，可进行感知、处理和决策。端侧 AI（即设备本地 AI）使设备无需持续连接云端即可运行算法，降低延迟并提升隐私。关键技术包括端侧 AI 芯片（专为 AI 设计的 NPU）、轻量化大模型（压缩后可在本地运行）以及多传感融合（融合摄像头、雷达、激光雷达等数据以实现全面感知）。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://baike.baidu.com/item/端侧AI芯片/67904669">端侧AI芯片 - 百度百科</a></li>
<li><a href="https://zhuanlan.zhihu.com/p/1960373488725497644">多传感器融合技术介绍 - 知乎 - 知乎专栏</a></li>
<li><a href="https://xie.infoq.cn/article/8033f733e4cc8c9d35b2433ba">文心 大 模 型 ERNIE-Tiny...</a></li>

</ul>
</details>

**标签**: `#smart hardware`, `#AI`, `#industry report`, `#China`, `#technology trends`

---

<a id="item-21"></a>
## [美国向 7 家科技公司提供 8.74 亿美元半导体研发资金](https://36kr.com/newsflashes/3916694245469826?f=rss) ⭐️ 7.0/10

美国商务部于 7 月 29 日宣布，已与七家公司签署初步协议，拟提供总额 8.74 亿美元的联邦激励资金，用于集成光子学和先进封装等领域的半导体研发。 这笔《芯片与科学法案》的资金旨在加强美国在关键半导体技术领域的领导地位，可能加速集成光子学和先进封装的创新，这些技术对于更快、更高效的计算和通信至关重要。 公告未公布七家受益公司的名称。资金覆盖集成光子学、计算架构、先进封装、基板、材料和存储技术。

rss · 36kr · 7月29日 12:27

**背景**: 《芯片与科学法案》于 2022 年签署成为法律，拨款超过 500 亿美元以促进美国半导体制造和研发。集成光子电路利用光而非电子来处理信息，实现更高速度和更低功耗。先进封装技术将多个半导体芯片组合到一个封装中，从而提升性能、缩小尺寸并降低成本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Integrated_photonic_circuit">Integrated photonic circuit</a></li>
<li><a href="https://en.wikipedia.org/wiki/Advanced_packaging_(semiconductors)">Advanced packaging (semiconductors) - Wikipedia</a></li>
<li><a href="https://www.synopsys.com/glossary/what-is-advanced-semiconductor-packaging.html">What is Advanced Semiconductor Packaging? - Synopsys</a></li>

</ul>
</details>

**标签**: `#semiconductor`, `#CHIPS Act`, `#R&D funding`, `#US tech policy`, `#advanced packaging`

---

<a id="item-22"></a>
## [ICLR 2027 截稿日期早于 NeurIPS 2026 决定](https://www.reddit.com/r/MachineLearning/comments/1v9v4e7/iclr_2027_deadline_is_before_neurips_2026/) ⭐️ 7.0/10

ICLR 2027 的完整论文截稿日期定为 9 月 16 日，比 NeurIPS 2026 的决定公布早 8 天，迫使作者在收到 NeurIPS 反馈前决定是否投稿。 这种日程冲突给研究人员带来了两难困境：他们本可根据 NeurIPS 的评审意见改进论文，但现在可能被迫降低投稿质量或面临不公平拒稿。 ICLR 2027 截稿日期为 9 月 16 日，而 NeurIPS 2026 的决定预计在 9 月 24 日左右公布，两者仅相隔 8 天，作者没有时间在 ICLR 截稿前修改论文。

reddit · r/MachineLearning · /u/1414vo · 7月29日 12:43

**背景**: ICLR（国际学习表征会议）和 NeurIPS（神经信息处理系统大会）都是顶级机器学习会议。作者常向多个会议投稿，并根据较早截稿会议的评审意见修改论文。通常截稿日期会错开以便修改，但这次 ICLR 截稿日期早于 NeurIPS 决定公布，打破了这一惯例。

**标签**: `#machine learning`, `#conferences`, `#ICLR`, `#NeurIPS`, `#research deadlines`

---

<a id="item-23"></a>
## [ncnn Vulkan 后端在边缘设备上实现 10 倍 ML 推理加速](https://www.reddit.com/r/MachineLearning/comments/1v9s4mz/vendoragnostic_ml_inference_on_production_edge/) ⭐️ 7.0/10

PostSlate 通过使用 ncnn 的 Vulkan 后端替代基于 CPU 的 ONNX 运行时，在生产边缘设备上实现了 10 倍的 ML 推理加速。在 NVIDIA 4070 上，ArcFace R50 从 30ms 降至 3ms，SCRFD 从 25ms 降至 2.5ms。 这种方法消除了对供应商特定运行时（如 CUDA）的依赖，实现了在边缘设备上真正的跨平台 GPU 推理。它解决了开发者在多样化硬件上部署 ML 时无需强制用户安装额外驱动程序的常见痛点。 加速来自于通过 Vulkan 将计算卸载到 GPU，但关键优势在于 Vulkan 驱动程序几乎已存在于每台机器上，包括 NVIDIA、AMD、Intel 和 Apple Silicon。模型大小也有所减小：ArcFace 从 174MB（ONNX fp32）降至 87MB（ncnn fp16 权重存储）。

reddit · r/MachineLearning · /u/ppchaos · 7月29日 10:22

**背景**: ncnn 是由腾讯开发的高性能神经网络推理框架，专为移动和边缘设备设计，无第三方运行时依赖。Vulkan 是一个跨平台的 GPU API，提供对 GPU 硬件的底层访问，使其适用于不同供应商的 ML 推理。传统方法通常依赖于 CUDA（仅限 NVIDIA）或供应商特定的运行时，限制了部署灵活性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/Tencent/ncnn">Tencent/ ncnn : ncnn is a high-performance neural network inference ...</a></li>
<li><a href="https://github.khronos.org/Vulkan-Site/tutorial/latest/ML_Inference/Vulkan_Compute_for_ML/01_introduction.html">Vulkan Compute for ML: Introduction :: Vulkan Documentation Project</a></li>
<li><a href="https://www.lei.chat/posts/gpgpu-ml-inference-and-vulkan-compute/">GPGPU, ML Inference, and Vulkan Compute | Lei.Chat()</a></li>

</ul>
</details>

**标签**: `#machine learning`, `#inference`, `#Vulkan`, `#edge devices`, `#cross-platform`

---

<a id="item-24"></a>
## [xAI 起诉明尼苏达州阻止 AI 脱衣禁令](https://www.cbsnews.com/minnesota/news/elon-musk-xai-sues-minnesota-law-banning-ai-nudification/) ⭐️ 7.0/10

埃隆·马斯克旗下人工智能公司 xAI 于 7 月 28 日向联邦法院起诉明尼苏达州，试图阻止该州禁止 AI 脱衣技术的法律，主张该法违反第一修正案，对言论施加了过于宽泛的限制。 此案可能为州级 AI 法规与言论自由保护的交互设定先例，影响关于 AI 治理以及创新与防害之间平衡的全国性讨论。 明尼苏达州法律对 AI 提供商施加严格责任，即使生成的内容具有艺术或教育价值，只要涉及未经同意的裸体图像即属违法，xAI 认为这会压制合法言论。明尼苏达州检察长基思·埃利森为该法辩护，称其对于保护受害者免受有害深度伪造的伤害是必要的。

telegram · zaihuapd · 7月29日 02:30

**背景**: AI 脱衣工具利用深度学习从穿衣照片生成裸体图像，引发了严重的隐私和同意问题。美国多个州已通过法律针对未经同意的深度伪造色情内容，但这是 AI 公司首次以言论自由为由对这类法规提出法律挑战。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/html/2411.09751v1">Analyzing the AI Nudification Application Ecosystem</a></li>
<li><a href="https://contentmavericks.com/best-nudify-app/">7 Best Nudify Apps 2026 (#1 AI Nudifier For Photos)</a></li>

</ul>
</details>

**标签**: `#AI regulation`, `#xAI`, `#Elon Musk`, `#First Amendment`, `#AI ethics`

---

<a id="item-25"></a>
## [Windows 11 静默安装 OneDrive Photos 并支持人脸扫描](https://www.windowslatest.com/2026/07/29/windows-11-is-quietly-installing-onedrive-photos-another-image-viewer-that-nobody-asked-for) ⭐️ 7.0/10

微软正在部分 Windows 11 设备上未经用户同意自动安装 OneDrive Photos 应用。若用户授权，该应用可扫描照片中的人脸以按人物整理照片。 这种做法引发了重大的隐私担忧，因为用户可能不会预料到一个自动安装的应用具备人脸识别功能。这也凸显了微软在 Windows 中积极整合 AI 功能，可能以牺牲用户控制和透明度为代价。 OneDrive Photos 应用使用 AI 识别并归类相似人脸，与其他照片管理工具类似。值得注意的是，用户只能命名或确认 OneDrive 已经创建的群组，不能手动标记人脸，并且此前有报道称每年只能禁用人脸扫描三次。

telegram · zaihuapd · 7月29日 05:37

**背景**: Windows 11 有自动安装建议应用的历史，且往往没有明确通知用户。OneDrive Photos 是一款与微软 OneDrive 云存储服务整合的新图片查看器，旨在利用 AI 进行照片整理。虽然照片应用中的人脸识别很常见，但未经明确同意自动安装的做法因绕过用户选择而招致批评。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.windowslatest.com/2026/07/29/windows-11-is-quietly-installing-onedrive-photos-another-image-viewer-that-nobody-asked-for/">Windows 11 is quietly installing OneDrive Photos, and it ...</a></li>
<li><a href="https://www.windowscentral.com/microsoft/onedrives-ai-face-scanning-feature-suggests-it-can-only-be-disabled-3-times-a-year-but-that-doesnt-seem-right">OneDrive's AI face scanning feature comes under fire ...</a></li>
<li><a href="https://learn.microsoft.com/en-us/answers/questions/5779398/onedrive-people">OneDrive People - Microsoft Q&A</a></li>

</ul>
</details>

**标签**: `#Windows 11`, `#OneDrive`, `#Privacy`, `#Facial Recognition`, `#Software Updates`

---

<a id="item-26"></a>
## [中国禁止新认证车辆安装自动驾驶'小蓝灯'](https://www.yicai.com/brief/103296987.html) ⭐️ 7.0/10

中国自 2026 年 7 月 27 日起禁止新认证车辆安装蓝色指示灯（'小蓝灯'），因其不符合国家强制性标准 GB4785《汽车及挂车外部照明和光信号装置的安装规定》。该禁令适用于 2026 年 7 月 27 日后申请新车型认证的车辆。 该决定与之前要求 L3 级以上车辆自 2025 年 7 月 1 日起强制安装蓝绿色自动驾驶标志灯的规定产生冲突。这凸显了监管空白，汽车制造商需谨慎应对，可能延迟自动驾驶状态可视指示灯的部署。 禁令依据是 GB4785，该标准不允许使用蓝色外部灯光（专用于紧急车辆）来指示驾驶状态。但另一项关于自动驾驶系统（ADS）标志灯的标准要求 L3 级以上车辆使用蓝绿色灯光，两者存在不一致。

telegram · zaihuapd · 7月29日 07:12

**背景**: 在中国，GB4785-2019 规定了汽车外部照明和光信号装置的安装要求，指定了允许的颜色如白色、琥珀色和红色，而蓝色专用于紧急车辆。另外，由 SAE 制定并在中国采用的自动驾驶系统（ADS）标志灯标准，要求使用蓝绿色灯光表示车辆处于自动驾驶控制状态。对'小蓝灯'的禁令表明，ADS 标志灯标准尚未与 GB4785 协调一致，因此在标准统一之前，新认证车辆禁止使用蓝色灯光。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://baike.baidu.com/item/自动驾驶系统标志灯/67918376">自动驾驶系统标志灯 - 百度百科</a></li>
<li><a href="https://www.autoengineer.cn/gb/40">GB4785-2019《汽车及挂车外部照明和光信号装置的安装规定》-汽车工程...</a></li>
<li><a href="https://zhuanlan.zhihu.com/p/1920215527340606275">智驾“小蓝灯”来了，将于7月1日正式实施，L3级以上车辆必须强制安装！ ...</a></li>

</ul>
</details>

**标签**: `#autonomous driving`, `#regulation`, `#automotive`, `#China`, `#EV`

---

<a id="item-27"></a>
## [闲鱼 AI 服务订单半年增 157%](https://www.bianews.com/news/flash?id=242540) ⭐️ 7.0/10

闲鱼数据显示，2024 年上半年 AI 服务订单量达 981.6 万单，同比增长 157%，近 500 万人在该平台购买 AI 服务。 这显示了中国消费者市场对 AI 服务的真实强劲需求，尤其是 AI 编程类目增长 1732%，标志着向 AI 辅助生产力的转变。 增长最快的类别是 AI 编程与建站，订单同比增长 1732%；AI 漫剧增长 1425%；AI PPT 与办公类增长 264%。

telegram · zaihuapd · 7月29日 09:14

**背景**: 闲鱼是阿里巴巴旗下的二手交易平台，近年来已拓展到数字服务交易。平台上的 AI 服务涵盖编程、设计、写作和内容创作，反映了个体和小型企业无需深厚技术知识即可利用 AI 工具提高生产力的趋势。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://m.ithome.com/html/983021.htm">闲 鱼 ：2026 上半年 AI 服 务 订单达 981.6 万单同比增长 157...</a></li>

</ul>
</details>

**标签**: `#AI`, `#marketplace`, `#growth`, `#China`, `#programming`

---

<a id="item-28"></a>
## [中国电信停止第三方互联网渠道销售 SIM 卡](https://www.189.cn/web/notice/detail?order=1&amp;offerCode=519526800001&amp;provinceCode=600304) ⭐️ 7.0/10

这一政策变化将直接影响依赖京东、天猫等电商平台购买中国电信手机卡的用户，可能有助于减少诈骗并优化运营商的获客渠道。 发现了两份几乎相同的公告，仅 provinceCode 参数不同，表明该变更适用于多个省份。具体的实施细则及例外情况尚未披露。

telegram · zaihuapd · 7月29日 12:45

**背景**: 中国电信是中国三大国有电信运营商之一，传统上通过实体店、官方网站以及第三方互联网合作伙伴销售 SIM 卡。公告 URL 中的 provinceCode 是引用中国行政区划的代码，电信系统用它来标识服务区域。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://zh.wikipedia.org/zh-hk/中华人民共和国行政区划代码">中華人民共和國行政區劃代碼 - 維基百科，自由的百科全書</a></li>

</ul>
</details>

**标签**: `#telecom`, `#China`, `#policy change`, `#SIM card`, `#Internet services`

---