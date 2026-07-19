---
layout: default
title: "Horizon Summary: 2026-07-19 (ZH)"
date: 2026-07-19
lang: zh
---

> 从 53 条内容中筛选出 19 条重要资讯。

---

1. [SRE 用 1600 美元 ESP32 替代 12 万美元保龄球计分系统](#item-1) ⭐️ 9.0/10
2. [阿里发布千问 3.8：2.4 万亿参数开源权重大模型](#item-2) ⭐️ 9.0/10
3. [Claude Code 现已使用用 Rust 重写的 Bun](#item-3) ⭐️ 8.0/10
4. [Minecraft Java 版采用 SDL3](#item-4) ⭐️ 8.0/10
5. [Moonshot AI 因需求激增暂停 Kimi K3 新订阅](#item-5) ⭐️ 8.0/10
6. [一目科技 E 轮融资超 10 亿元，估值突破 100 亿元](#item-6) ⭐️ 8.0/10
7. [GPT-2 词元嵌入的双曲空间可视化](#item-7) ⭐️ 8.0/10
8. [GPT-2 词元嵌入交互地图](#item-8) ⭐️ 8.0/10
9. [荣耀发布 Agentic OS 技术框架，转向意图驱动操作系统](#item-9) ⭐️ 8.0/10
10. [阿里开源 SAIL 挑战英伟达 CUDA](#item-10) ⭐️ 8.0/10
11. [卖出 2500 台 MIDI 录音机：硬件没那么难](#item-11) ⭐️ 7.0/10
12. [人工智能狂热导致企业非理性决策](#item-12) ⭐️ 7.0/10
13. [中科闻歌在 WAIC2026 发布首个全链 AI 决策套件](#item-13) ⭐️ 7.0/10
14. [中国发布 AI+防震减灾行动方案](#item-14) ⭐️ 7.0/10
15. [开源权重 LLMs 经 SFT 和 RLVR 后通过瑞典医考](#item-15) ⭐️ 7.0/10
16. [商汤发布 SenseNova U1 Pro 多模态智能体基座](#item-16) ⭐️ 7.0/10
17. [Gboard 正在开发通过摄像头识别手语转文字的功能](#item-17) ⭐️ 7.0/10
18. [美国政客优化网络形象以影响 AI 聊天机器人](#item-18) ⭐️ 7.0/10
19. [深空矩阵发布“星环计划”，首阶段 210 颗卫星](#item-19) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [SRE 用 1600 美元 ESP32 替代 12 万美元保龄球计分系统](https://news.ycombinator.com/item?id=48968606) ⭐️ 9.0/10

一位 SRE 用 ESP32 微控制器构建了一个名为 OpenLaneLink 的开源计分系统原型，以约 1600 美元的总成本替代了 12 万美元的商业系统——大约每对球道 200 美元。 该项目表明现代嵌入式系统可以大幅降低小众工业应用的成本，挑战供应商锁定，使保龄球运动对小场馆更加经济实惠。 该系统使用 ESPNow 星形拓扑网格并带有 RS485 回退，数据传输到运行 Redis 和状态机的树莓派，允许任何 React 开发者构建自定义界面和动画。

hackernews · section33 · 7月19日 14:41

**背景**: ESP32 是一种低成本、低功耗的微控制器，内置 Wi-Fi 和蓝牙，广泛用于物联网项目。商业保龄球计分系统是专有的，通常耗资数万美元，并将运营商锁定在昂贵的服务合同中。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://circuitdigest.medium.com/esp32-projects-with-circuit-diagram-and-code-full-tutorials-5c892a573998">Medium</a></li>
<li><a href="https://micropython.org/download/">MicroPython - Python for microcontrollers</a></li>

</ul>
</details>

**社区讨论**: Hacker News 社区称赞该项目是黑客创造力的典型例子，用户分享了类似的改造经验，并提出了增强建议，如 LED 追光灯和用于激光秀的 DMX 控制。

**标签**: `#embedded systems`, `#IoT`, `#ESP32`, `#cost reduction`, `#hardware hacking`

---

<a id="item-2"></a>
## [阿里发布千问 3.8：2.4 万亿参数开源权重大模型](https://twitter.com/Alibaba_Qwen/status/2078759124914098291) ⭐️ 9.0/10

阿里宣布发布千问 3.8，一个 2.4 万亿参数的开源权重大语言模型，与月之暗面的 Kimi K3 竞争。 这标志着开源权重大模型领域的竞争加剧，为开发者提供更强大的本地模型，减少对专有 API 的依赖。 千问 3.8 拥有 2.4 万亿参数且开源权重，即模型权重将公开发布。它紧随月之暗面宣布的 2.8 万亿参数 Kimi K3 之后。

hackernews · nh43215rgb · 7月19日 08:44 · [社区讨论](https://news.ycombinator.com/item?id=48966120)

**背景**: 大语言模型（LLM）是具有数十亿或数万亿参数的 AI 模型，用于生成文本。“开源权重”意味着训练好的权重是公开可用的，允许本地部署和微调。阿里的千问系列是领先的中文大模型家族。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Kimi_K3">Kimi K3</a></li>
<li><a href="https://www.ai21.com/glossary/open-weights-model/">What is an Open - Weights Model ? | AI21</a></li>

</ul>
</details>

**社区讨论**: 社区对开源权重竞争感到兴奋，用户希望有更小的版本供本地使用。部分用户报告千问 3.7 Pro 体验不佳，认为在编码方面不如 Deepseek。

**标签**: `#LLM`, `#open-weights`, `#Alibaba`, `#AI competition`, `#Qwen`

---

<a id="item-3"></a>
## [Claude Code 现已使用用 Rust 重写的 Bun](https://simonwillison.net/2026/Jul/19/claude-code-in-bun-in-rust/#atom-everything) ⭐️ 8.0/10

Claude Code v2.1.181 及更高版本现在使用 Rust 移植的 Bun，在 Linux 上启动速度提高了 10%。通过检查二进制文件中的字符串，发现了 Rust 源文件和一个未发布的 Bun v1.4.0 版本，从而验证了这一变化。 这展示了 Anthropic 进行了一次重大的架构调整，为了性能而捆绑了自定义的 JavaScript 运行时。这也引发了关于工程选择、开源项目治理及社区沟通的热议。 Bun 的 Rust 版本目前以 canary 版本发布（bun upgrade --canary）。社区讨论中对重写的沟通流程以及 Bun 作为独立开源项目的长期可行性表示担忧。

rss · Simon Willison · 7月19日 03:54 · [社区讨论](https://news.ycombinator.com/item?id=48966569)

**背景**: Bun 是一个快速的、一体化的 JavaScript 运行时、打包器和包管理器，最初用 Zig 编写。Claude Code 是 Anthropic 的代理式编码工具，在终端中运行。Jarred Sumner 宣布将 Bun 从 Zig 重写为 Rust，旨在提高内存安全性并减少 bug。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://bun.sh/">Bun — A fast all-in-one JavaScript runtime</a></li>

</ul>
</details>

**社区讨论**: 社区评论褒贬不一：有人批评在 TUI 工具中依赖 JavaScript 运行时，并质疑工程质量；另一些人则争论重写过程中的沟通问题，一位评论者指出问题在于缺乏成熟的治理；少数人担心 Bun 正在悄然变成一个不同的项目。

**标签**: `#bun`, `#rust`, `#claude-code`, `#performance`, `#runtime`

---

<a id="item-4"></a>
## [Minecraft Java 版采用 SDL3](https://www.minecraft.net/en-us/article/minecraft-26-3-snapshot-4) ⭐️ 8.0/10

Minecraft: Java Edition 在快照 26w03a 中从 SDL2 切换至 SDL3，用于跨平台输入和窗口管理，成为首个采用新稳定版 SDL3 库的主流游戏。 此举表明业界对 SDL3 的信心增强，该库提供更好的性能和现代 API 特性；同时通过 LWJGL 绑定影响模组社区，可能简化 Minecraft 及其他 Java 游戏的跨平台开发。 SDL3 的 LWJGL 绑定由 GTNH 整合包团队成员贡献，完成了从原版到模组再回到原版的完整循环。已知问题包括在 Windows 多显示器环境下和 Wayland 上进入独占全屏模式时可能崩溃。

hackernews · ObviouslyFlamer · 7月19日 11:48 · [社区讨论](https://news.ycombinator.com/item?id=48967256)

**背景**: SDL（Simple DirectMedia Layer）是一个跨平台库，提供对音频、键盘、鼠标和图形硬件的底层访问，广泛应用于游戏开发。LWJGL（Lightweight Java Game Library）是 Java 绑定库，使 Minecraft 能够使用 OpenGL 和 SDL 等原生 API。SDL3 于 2025 年 1 月发布稳定版，与 SDL2 相比有重大 API 变更。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/SDL_library">SDL library</a></li>
<li><a href="https://www.lwjgl.org/?ref=jmaven.com">LWJGL - Lightweight Java Game Library</a></li>

</ul>
</details>

**社区讨论**: 社区评论强调 LWJGL 绑定由 GTNH 整合包团队成员编写，强化了原版与模组之间的反馈循环。一些用户对 Wayland 和多显示器崩溃等阻塞性 bug 表示担忧，希望能在稳定版发布前修复。

**标签**: `#Minecraft`, `#SDL3`, `#game development`, `#LWJGL`, `#open-source`

---

<a id="item-5"></a>
## [Moonshot AI 因需求激增暂停 Kimi K3 新订阅](https://twitter.com/kimi_moonshot/status/2078855608565207130) ⭐️ 8.0/10

Moonshot AI 因 Kimi K3 模型需求超出当前服务能力，暂时停止新用户订阅，优先保障现有用户的服务质量。 此举在 AI 行业中罕见地体现了以客户为中心的理念，表明公司优先考虑用户体验而非盲目扩张，同时凸显了市场对先进推理模型的巨大需求。 Kimi K3 是一个拥有 2.8 万亿参数、采用混合线性注意力机制（KDA）的模型，支持高达 100 万上下文令牌；此次暂停仅针对新订阅，现有用户不受影响。

hackernews · serialx · 7月19日 16:02 · [社区讨论](https://news.ycombinator.com/item?id=48969291)

**背景**: Moonshot AI 是一家总部位于北京的人工智能初创公司，以其 Kimi 聊天机器人系列而闻名，Kimi K3 是其旗舰模型，于 2026 年 7 月发布。该模型采用新颖的混合注意力架构，提高了长上下文任务的效率。该公司是中国“AI 六小虎”之一，其开源贡献备受关注。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Moonshot_AI">Moonshot AI</a></li>
<li><a href="https://en.wikipedia.org/wiki/Kimi_K3">Kimi K3</a></li>
<li><a href="https://platform.kimi.ai/docs/guide/kimi-k3-quickstart">Kimi K 3 - Kimi API Platform</a></li>

</ul>
</details>

**社区讨论**: 社区成员称赞 Moonshot AI 优先考虑现有用户而非快速扩张的做法，一些人分享了对 Kimi K3 性能的满意体验，认为其可与 Claude Opus 媲美。还有用户提到该模型大量使用 RNN/线性注意力层的技术细节，强调其适合长上下文任务。

**标签**: `#AI`, `#Kimi K3`, `#Moonshot AI`, `#subscription model`, `#demand management`

---

<a id="item-6"></a>
## [一目科技 E 轮融资超 10 亿元，估值突破 100 亿元](https://36kr.com/newsflashes/3902093496813441?f=rss) ⭐️ 8.0/10

7 月 18 日，一目科技宣布完成超 10 亿元 E 轮融资，估值突破 100 亿元。所融资金将用于具身智能触觉感知材料、芯片、算法和模型的研发，以及规模化量产。 本轮大额融资凸显了市场对具身智能和触觉感知技术的强烈信心，该技术对机器人领域至关重要。一目科技的高估值反映了自主系统对先进感知能力日益增长的需求。 本轮融资由多家一线人民币基金、头部美元基金和知名产业方联合参与。公司计划重点研发触觉感知材料、芯片、算法和模型，并扩大产线以实现高质量交付。

rss · 36kr · 7月19日 05:15

**背景**: 具身智能是指通过传感器和执行器与物理世界交互的人工智能系统，其认知受身体互动塑造。触觉感知技术复制人类触觉，使机器人能够感知接触压力和纹理，对于灵巧操作和安全的人机交互至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Embodied_intelligence">Embodied intelligence</a></li>
<li><a href="https://pressureprofile.com/about/tactile-sensing">Tactile Sensors and Tactile Sensing Technology — PPS</a></li>

</ul>
</details>

**标签**: `#embodied AI`, `#tactile sensing`, `#robotics`, `#funding`, `#Chinese tech`

---

<a id="item-7"></a>
## [GPT-2 词元嵌入的双曲空间可视化](https://www.reddit.com/r/MachineLearning/comments/1v0pv45/follow_up_gpt2s_vocabulary_as_a_hyperbolic_tree/) ⭐️ 8.0/10

一篇交互式庞加莱球可视化展示了 GPT-2 small 的 32,070 个词元嵌入，用户无需训练或优化即可探索由词元相似性形成的自然树状结构。 这项工作表明双曲几何比平坦的欧几里得空间更能自然地表示词嵌入中的层次关系，可能启发语言模型更好的嵌入技术。 该可视化仅使用 GPT-2 small 的原始词元嵌入，并采用莫比乌斯平移进行导航，无需任何优化或训练。生成的森林结构包含一棵约 2,300 个词元的大树和许多较小的树。

reddit · r/MachineLearning · /u/Limp-Contest-7309 · 7月19日 12:54

**背景**: 双曲几何是一种非欧几何，其中空间随距离指数增长，非常适合嵌入树状结构。庞加莱球模型将双曲空间映射到单位球上，在保持角度的同时扭曲距离。莫比乌斯变换提供了双曲球的自然等距变换，支持平滑导航。

**标签**: `#GPT-2`, `#hyperbolic embeddings`, `#visualization`, `#token embeddings`, `#Poincaré ball`

---

<a id="item-8"></a>
## [GPT-2 词元嵌入交互地图](https://www.reddit.com/r/MachineLearning/comments/1v09muj/interactive_map_of_gpt2s_token_embedding_space/) ⭐️ 8.0/10

一位用户创建了交互式地图，利用 t-SNE 和最小生成树可视化 GPT-2-small 的嵌入表中的 32070 个字母词元，通过点击或搜索即可探索最近邻关系。 该工具提供了一种直观的方式来解释词元嵌入，有助于理解语言模型如何表示意义和相似性，对研究、教学和调试模型行为具有重要价值。 该地图在嵌入表的压缩表示上使用 t-SNE，边构成最小生成树以显示真实的最近邻关系。它支持移动端，无需前向传播或上下文。

reddit · r/MachineLearning · /u/Limp-Contest-7309 · 7月18日 22:42

**背景**: 词元嵌入是词汇中子词单元的稠密向量表示，在高维空间中捕捉语义。t-SNE 是一种非线性降维技术，将高维数据投影到二维或三维以进行可视化，同时保留局部结构。最小生成树以最小总边权重连接所有点，突出了最重要的关系。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Minimum_spanning_tree">Minimum spanning tree</a></li>
<li><a href="https://www.datacamp.com/tutorial/introduction-t-sne">Introduction to t - SNE : Nonlinear Dimensionality Reduction and Data...</a></li>

</ul>
</details>

**标签**: `#GPT-2`, `#token embeddings`, `#t-SNE`, `#visualization`, `#interpretability`

---

<a id="item-9"></a>
## [荣耀发布 Agentic OS 技术框架，转向意图驱动操作系统](https://wallstreetcn.com/articles/3777328) ⭐️ 8.0/10

在 2026 年世界人工智能大会上，荣耀发布了 Agentic OS 技术框架，标志着手机操作系统从以应用为中心转向以用户意图为中心。同时展示了 Robot Phone，能够通过自然语言发起并自动执行跨应用任务。 该框架通过聚焦用户意图而非单个应用，重新定义了智能手机交互方式，有望简化复杂的多步骤任务。与阿里巴巴千问的合作也凸显了将大语言模型直接集成到操作系统中的行业趋势。 Robot Phone 于 2025 年 10 月发布，并在 2026 年 CES 上展示，配备 AI 超级大脑和机械摄像头臂，支持具身 AI 交互。荣耀与阿里巴巴千问合作，开发针对手机场景的终端大模型解决方案。

telegram · zaihuapd · 7月19日 02:06

**背景**: 传统手机操作系统以应用为中心，用户需要打开特定应用来完成任务。而意图驱动系统则允许用户直接表达目标，操作系统自动理解意图并跨应用编排操作。Agentic OS 是一种 AI 代理自主规划并执行任务的框架，通常集成大语言模型以实现自然语言理解。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.lyzr.ai/blog/best-agentic-os-platforms/?trk=article-ssr-frontend-pulse_little-text-block">Best Agentic OS Platforms: Enterprise Buyer's Guide (2026)</a></li>
<li><a href="https://www.kindo.ai/blog/the-rise-of-intent-centric-systems">Intent - Centric Architecture: The 2026 Enterprise Model | Kindo</a></li>
<li><a href="https://www.honor.com/global/events/honor-robot-phone/">HONOR Robot Phone - HONOR Global</a></li>

</ul>
</details>

**标签**: `#AI`, `#mobile OS`, `#intent-centric`, `#Agentic OS`, `#Honor`

---

<a id="item-10"></a>
## [阿里开源 SAIL 挑战英伟达 CUDA](https://www.scmp.com/tech/tech-war/article/3361048/alibaba-targets-nvidias-dominant-software-ecosystem-open-source-ai-stack) ⭐️ 8.0/10

7 月 18 日，阿里巴巴芯片设计部门平头哥在上海世界人工智能大会上宣布，将其真武 AI 芯片的软件栈 SAIL 开源。此举旨在降低开发者的迁移成本，直接挑战英伟达 CUDA 生态的主导地位。 通过开源 SAIL，阿里巴巴提供了一个可行的替代方案来对抗英伟达的 CUDA，可能减少供应商锁定并加速国产 AI 芯片的采用。此举可能重塑 AI 硬件生态系统，特别是在受美国出口限制而难以获取英伟达产品的中国。 开发者可在 7 天内将 SAIL 适配到主流 AI 框架，并以较少改动复用现有代码。截至 4 月，阿里已向 20 个行业的 400 多家企业客户出货 56 万片真武芯片。

telegram · zaihuapd · 7月19日 07:34

**背景**: 英伟达的 CUDA 是一个专有的并行计算平台，已成为 AI 计算的事实标准，为开发者带来了高昂的切换成本。SAIL（软件抽象与集成层）是阿里巴巴为其真武 AI 芯片设计的底层软件架构，旨在简化代码的可移植性。通过开源 SAIL，阿里巴巴希望构建一个独立的 AI 软件生态，类似华为和摩尔线程也在推动各自的开放软件栈。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.scmp.com/tech/tech-war/article/3361048/alibaba-targets-nvidias-dominant-software-ecosystem-open-source-ai-stack">Alibaba targets Nvidia’s dominant software ecosystem with...</a></li>
<li><a href="https://azat.tv/en/alibaba-nvidia-ai-software-stack-sail/">Alibaba Open-Sources AI Software Stack to Challenge...</a></li>

</ul>
</details>

**标签**: `#AI chips`, `#open source`, `#Alibaba`, `#Nvidia CUDA`, `#software stack`

---

<a id="item-11"></a>
## [卖出 2500 台 MIDI 录音机：硬件没那么难](https://chipweinberger.com/articles/20260719-hardware-is-not-so-hard) ⭐️ 7.0/10

Chip Weinberger 分享了销售 2500 台 JamCorder MIDI 录音机的经验，认为硬件开发比通常认为的更容易上手。 这挑战了硬件天生比软件更难的主流观念，为硬件创业者和创客提供了鼓励和实用见解。同时证明，一个设计精良的简单小众产品也能在没有大规模生产的情况下取得可观的销量。 JamCorder 是一款简单的设备，采用 25 个元件的 PCBA 和现成的翻盖外壳，将演奏内容以标准 MIDI 文件存储在存储卡上，无需依赖专用应用程序。作者还启用了加密以防止仿冒，引发了关于开源与封闭硬件的讨论。

hackernews · chipweinberger · 7月19日 10:34 · [社区讨论](https://news.ycombinator.com/item?id=48966713)

**背景**: MIDI（乐器数字接口）是一种数字通信协议，允许电子乐器和计算机交换诸如音符音高和力度等演奏数据。硬件开发常被认为困难，原因在于规模化生产、物理公差测试以及应对用户使用差异等方面的挑战，但 Weinberger 的经验表明，对于简单、小批量的产品，硬件的难度取决于你如何设计。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.loopcloud.com/cloud/blog/5260-What-is-MIDI-and-How-is-it-Used-in-Making-Music-">What is MIDI and How is it Used in Making Music?</a></li>
<li><a href="https://kernom.com/en-us/blogs/midi/midi-basis">Understanding MIDI Basis for your Stompboxes - KERNOM NEWS</a></li>
<li><a href="https://www.kvraudio.com/forum/viewtopic.php?t=274324">Hardware MIDI Recorder Suggestions - Hardware ... - KVR Audio</a></li>

</ul>
</details>

**社区讨论**: 评论包括一位满意的顾客称赞该产品完美无缺；有批评者指出硬件难度随复杂性增加，JamCorder 的简易性并不能代表大多数产品；还有用户询问如何在防伪措施与开源固件之间取得平衡。这些讨论从不同角度探讨了硬件开发，印证了这一话题的重要性。

**标签**: `#hardware`, `#product design`, `#entrepreneurship`, `#MIDI`, `#lessons learned`

---

<a id="item-12"></a>
## [人工智能狂热导致企业非理性决策](https://simonwillison.net/2026/Jul/19/ai-mania/#atom-everything) ⭐️ 7.0/10

Nik Suresh 在 Simon Willison 博客上发表了一篇批判性分析，揭露 AI 热潮如何导致高管做出非理性决策，例如一位从未使用过 ChatGPT 的高管却为一家营收超 20 亿美元的公司制定了以 AI 为中心的战略。 这突显了一个系统性问题：AI 狂热助长了表演式工程和不诚实行为，可能浪费资源并破坏真正的创新。 文章提到一个关于拥有 token 排行榜的公司工程师的轶事，他利用 AI 将 Go 代码库重写为 Zig 语言，只是为了显得高产；还透露高管们因害怕失去合同而避免坦诚 AI 的局限性。

rss · Simon Willison · 7月19日 05:06

**背景**: Zig 是一种系统编程语言，旨在改进 C 语言，以编译时泛型和手动内存管理著称。Token 排行榜用于跟踪 AI token 使用量，以进行成本和生产力比较，常被公司内部用于衡量 AI 工具的采用情况。AI 狂热指的是在商业中过度炒作和匆忙采用 AI 技术，通常却不了解其实际局限性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Zig_(programming_language)">Zig (programming language)</a></li>
<li><a href="https://whoburnedmore.com/">Who Burned More? AI Token Leaderboard</a></li>

</ul>
</details>

**标签**: `#AI hype`, `#corporate decision-making`, `#critical analysis`, `#software engineering`

---

<a id="item-13"></a>
## [中科闻歌在 WAIC2026 发布首个全链 AI 决策套件](https://36kr.com/newsflashes/3902288636282757?f=rss) ⭐️ 7.0/10

在 2026 世界人工智能大会（WAIC2026）上，中科闻歌发布了业界首个完整的 AI 决策产品体系，名为“基、枢、核、脑、端”，覆盖从数据治理到智能体执行的全链路。该系统以 DOMA 架构为技术底座。 该产品套件旨在统一企业决策流程，可能缩短决策周期并实现更快速的业务洞察。它通过提供端到端解决方案，可能影响依赖复杂多步骤 AI 决策工作流的行业。 该系统将数据治理、业务建模、模型推理和智能体执行集成到一个闭环中。据称它支持从企业生产经营到科学发现等不同层级的决策。

rss · 36kr · 7月19日 08:24

**背景**: AI 决策智能指的是在复杂环境中使用 AI 支持或自动化决策。传统方法通常需要分离的数据处理、建模和执行工具，导致工作流碎片化。中科闻歌的产品试图提供统一的端到端框架来解决这一效率问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://stock.10jqka.com.cn/20260719/c678273021.shtml">中 科 闻 歌 WAIC 2026发布完整AI决策 产 品 体 系 | 同花顺财经</a></li>
<li><a href="https://www.163.com/dy/article/L25CR05105118O92.html">中 科 闻 歌 发布首个AI决策“全家桶”，企业决策卷入“10分钟时代”</a></li>

</ul>
</details>

**标签**: `#AI`, `#decision intelligence`, `#product launch`, `#WAIC`

---

<a id="item-14"></a>
## [中国发布 AI+防震减灾行动方案](https://36kr.com/newsflashes/3902090005743493?f=rss) ⭐️ 7.0/10

2026 年 7 月 19 日，中国地震局在世界人工智能大会上发布《“人工智能+防震减灾”行动方案（2026—2028 年）》，规划了地震智能监测处理、智能化地震预警等九大任务。 这一国家层面的计划标志着中国战略性推动 AI 与防震减灾融合，旨在巩固在该领域的竞争优势，提升实时监测和预警能力。 方案聚焦构建“数据—模型—平台—应用”四位一体的人工智能技术体系，并计划到 2028 年实现 AI 对防震减灾业务的有效支撑。

rss · 36kr · 7月19日 05:00

**背景**: 传统地震预警和监测依赖地震台网和人工分析。AI 的引入——如利用深度学习进行波形识别和快速震害评估——有望实现更快更准的响应。该方案正式确立了未来三年中国将 AI 用于防灾减灾的承诺。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.chinanews.com.cn/gn/2026/07-19/10662378.shtml">“人工 智 能 +防 震 减灾”行动方案发布-中新网</a></li>
<li><a href="https://tech.ifeng.com/c/8ut3mjO96rP">“人工 智 能 +防 震 减灾”行动方案发布_凤凰网</a></li>
<li><a href="http://www.earth-science.net/fileDQKX/journal/article/dqkxzx/2026/1/dqkxzx-51-1-1.pdf">Application of Artificial Intelligence Real⁃Time Earthquake Processing</a></li>

</ul>
</details>

**标签**: `#人工智能`, `#防震减灾`, `#政策`, `#地震预警`

---

<a id="item-15"></a>
## [开源权重 LLMs 经 SFT 和 RLVR 后通过瑞典医考](https://www.reddit.com/r/MachineLearning/comments/1v0pnoq/passing_the_swedish_medical_licensing_exam_by/) ⭐️ 7.0/10

一项最新研究表明，通过监督微调（SFT）和基于验证奖励的强化学习（RLVR）微调后的开源权重大语言模型（LLM），能够通过瑞典医师执照考试这一非英语医学认证测试。 这扩展了开源权重 LLM 的能力至新的语言和领域，展示了在非英语环境中部署医疗 AI 的潜力，同时验证了 RLVR 作为事实性领域有效后训练方法的有效性。 该研究可能使用了 Llama 或 Mistral 等开源权重模型，在瑞典医疗数据上进行 SFT，随后使用来自考试答案的可验证奖励信号进行 RLVR。模型达到了及格分数，但具体性能指标和模型大小在摘要中未详细说明。

reddit · r/MachineLearning · /u/AccomplishedCat4770 · 7月19日 12:44

**背景**: 监督微调（SFT）通过使用标注示例将预训练 LLM 适配到特定任务。基于验证奖励的强化学习（RLVR）是一种较新技术，模型仅在输出可被正式验证为正确时才获得奖励，从而避免了学习型奖励模型的漂移问题。两者结合使 LLM 能够获得领域特定知识和推理能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.geeksforgeeks.org/artificial-intelligence/supervised-fine-tuning-sft-for-llms/">Supervised Fine - Tuning ( SFT ) for LLMs - GeeksforGeeks</a></li>
<li><a href="https://www.linkedin.com/pulse/reinforcement-learning-verifiable-reward-rlvr-new-paradigm-jatasra-xe3fc">Reinforcement Learning with Verifiable Reward ( RLVR ): A New...</a></li>

</ul>
</details>

**标签**: `#LLM`, `#medical AI`, `#fine-tuning`, `#reinforcement learning`, `#NLP`

---

<a id="item-16"></a>
## [商汤发布 SenseNova U1 Pro 多模态智能体基座](https://mp.weixin.qq.com/s/hGo5TvUpxRodVtfnXDM7ew) ⭐️ 7.0/10

2025 年 7 月 18 日，商汤科技发布了新一代多模态智能体基座 SenseNova U1 Pro，具备 8K 超清输出、专业设计美感以及长程 Agentic 闭环思维等核心能力。 此次发布标志着商汤在多模态生成领域的重要进步，为商业创意场景提供系统级交付能力，有望提升广告、设计等领域的生产效率。 U1 Pro 在过去两个月内经历了三次快速迭代。2025 年 6 月，U1 用户人均日生图量达 107 张，GitHub 星标数超 8500。它展示了从图像到视频分镜创作的跨模态能力。

telegram · zaihuapd · 7月19日 01:20

**背景**: 多模态智能体基座是一种能够跨文本、图像、音频、视频等多种数据类型进行感知和行动的 AI 系统，利用视觉语言模型理解并交互图形界面。长程 Agentic 闭环思维指 AI 从结果中学习、重新评估决策并实时适应，以处理长期任务。商汤 U1 Pro 整合这些能力，为商业创作提供专业级输出。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://aws.amazon.com/blogs/machine-learning/generative-ai-and-multi-modal-agents-in-aws-the-key-to-unlocking-new-value-in-financial-markets/">Generative AI and multi - modal agents in AWS: The key to unlocking...</a></li>
<li><a href="https://fp8.co/glossary/multi-modal-agents">Multi - Modal Agents — Definition & Explanation | fp8.co</a></li>
<li><a href="https://www.linkedin.com/pulse/how-agentic-ai-closed-loop-orchestration-transforming-william-fox-hz7oe">How Agentic AI And Closed - Loop Orchestration Are Transforming...</a></li>

</ul>
</details>

**标签**: `#multimodal`, `#AI`, `#SenseTime`, `#image generation`, `#agentic`

---

<a id="item-17"></a>
## [Gboard 正在开发通过摄像头识别手语转文字的功能](https://www.androidauthority.com/gboard-sign-to-text-3688910/) ⭐️ 7.0/10

该功能通过利用去年公布的 SignGemma 模型，可能为听障用户提供在移动设备上实时输入手语的能力，大幅提升无障碍体验。 该功能通过 APK 拆解发现，尚未在测试版中实际启用，因此存在最终不发布的可能性。Google 也未公布将支持哪些手语种类。

telegram · zaihuapd · 7月19日 06:49

**背景**: SignGemma 是 Google DeepMind 推出的开源 AI 模型，属于 Gemma 系列，专门用于将手语翻译为文字，旨在促进实时沟通和包容性 AI 发展。Gboard 的手语转文字功能似乎是该模型的首个重要应用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.linkedin.com/posts/genai-works_ai-googledeepmind-signgemma-activity-7333359467624824832-koAG">Google DeepMind launches SignGemma , an open AI model... | LinkedIn</a></li>
<li><a href="https://www.blockchain-council.org/ai/google-deepmind-announces-signgemma/">Google DeepMind Announces SignGemma - Blockchain Council</a></li>

</ul>
</details>

**标签**: `#Gboard`, `#accessibility`, `#sign language`, `#AI`, `#DeepMind`

---

<a id="item-18"></a>
## [美国政客优化网络形象以影响 AI 聊天机器人](https://www.nytimes.com/2026/07/19/us/politics/chatbots-political-campaigns.html) ⭐️ 7.0/10

美国竞选团队正调整网站和在线内容，以影响 ChatGPT 等 AI 聊天机器人对候选人的描述，催生了称为“答案引擎优化”（AEO）的新行业。 这种做法可能扭曲选民从 AI 系统获取的信息，引发对政治言论操纵和民主进程完整性的担忧。 一项研究发现，维基百科新内容约 12 分钟即可被聊天机器人抓取，而苏格兰选举实验中超过三分之一的 AI 回答存在错误。

telegram · zaihuapd · 7月19日 13:19

**背景**: 答案引擎优化（AEO），也称为生成引擎优化（GEO），涉及结构化数字内容以提高在 AI 生成答案中的可见性。随着大型语言模型被集成到搜索中，优化直接答案而非链接列表变得至关重要。这种做法旨在影响 LLM 如何检索和总结信息。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Answer_Engine_Optimization_(AEO)">Answer Engine Optimization (AEO)</a></li>

</ul>
</details>

**标签**: `#AI伦理`, `#政治竞选`, `#信息操纵`, `#搜索引擎优化`, `#聊天机器人`

---

<a id="item-19"></a>
## [深空矩阵发布“星环计划”，首阶段 210 颗卫星](https://mp.weixin.qq.com/s/TiC_sYBX7u3l3HZW-CsfLQ) ⭐️ 7.0/10

深空矩阵在 WAIC 2026 发布“星环计划”，拟建设集算力、遥感、中继于一体的低轨智能卫星星座，首阶段部署约 210 颗卫星，最终拓展至数千乃至数万颗。 该计划是构建天基 AI 算力基础设施的重要举措，可能为全球 AI 工作负载提供分布式计算能力，减少对地面数据中心的依赖，并实现自主系统、气候监测等应用的低延迟 AI 处理。 该星座将通过跨层卫星算力互联协同，将不同轨道卫星组织成可调度的空间计算网络。公司强调在运力、功耗等约束下提升整体算力效率，而非简单复制海外路线。

telegram · zaihuapd · 7月19日 14:05

**背景**: 天基 AI 计算星座，如 SpaceX 的 Starmind 和中国的三体计算星座，旨在部署具有星上计算能力的卫星，在轨道上处理数据。这减少了对大量数据传回地球的需求，使地球观测、通信等应用能够实现实时 AI 推理和数据处理。低地球轨道卫星相比地球同步轨道卫星具有更低延迟和更高带宽，适合分布式计算网络。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.google.com/stories/CAAqNggKIjBDQklTSGpvSmMzUnZjbmt0TXpZd1NoRUtEd2p6cC1Qd0RSSGQtNmx3NkV4U09DZ0FQAQ?hl=en-US&gl=US&ceid=US:en">Google News - China launches satellites for space - based ...</a></li>
<li><a href="https://www.cutter.com/article/orbit-data-centers-mapping-leaders-space-ai-computing">On-Orbit Data Centers: Mapping the Leaders in Space - Based AI ...</a></li>

</ul>
</details>

**标签**: `#satellite AI`, `#space computing`, `#AI infrastructure`, `#low-earth orbit`, `#WAIC`

---