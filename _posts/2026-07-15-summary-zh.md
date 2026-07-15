---
layout: default
title: "Horizon Summary: 2026-07-15 (ZH)"
date: 2026-07-15
lang: zh
---

> 从 79 条内容中筛选出 22 条重要资讯。

---

1. [Stripe 与 Advent 出价逾 530 亿美元收购 PayPal](#item-1) ⭐️ 9.0/10
2. [Claude web_fetch 漏洞实现数据窃取](#item-2) ⭐️ 9.0/10
3. [马斯克：X 将无条件开源全部代码](#item-3) ⭐️ 9.0/10
4. [Inkling: Thinking Machines 的开源权重多模态模型](#item-4) ⭐️ 8.0/10
5. [在 13 年前的至强上无 GPU 运行 Gemma 4 26B，速度 5 tok/s](#item-5) ⭐️ 8.0/10
6. [面壁智能与三星合作，端侧模型将登陆旗舰手机](#item-6) ⭐️ 8.0/10
7. [支付宝 AI 版“阿宝”上线，从支付工具转向主动服务平台](#item-7) ⭐️ 8.0/10
8. [诺基亚与英伟达推出首个商用 AI-RAN 平台](#item-8) ⭐️ 8.0/10
9. [利用哈达玛积聚类解构卷积神经元](#item-9) ⭐️ 8.0/10
10. [怀念专业 ML 会议的多元化时代](#item-10) ⭐️ 8.0/10
11. [DeepSeek 年化收入逼近 5 亿美元，V4 API 毛利率超 50%](#item-11) ⭐️ 8.0/10
12. [腾讯成为 DeepSeek 首轮融资最大外部股东](#item-12) ⭐️ 8.0/10
13. [Telegram 推出机器人无服务器平台](#item-13) ⭐️ 8.0/10
14. [Telegram 数据中心之谜：位置与区域划分](#item-14) ⭐️ 7.0/10
15. [在软件开发中优先关注心理健康](#item-15) ⭐️ 7.0/10
16. [研究：睡眠规律性比时长更能预测死亡率](#item-16) ⭐️ 7.0/10
17. [蛋仔派对推出“双子星”编辑器，打造 AI 原生 UGC 平台](#item-17) ⭐️ 7.0/10
18. [PyTorch 模型在 T4 上比 A100 慢 170 倍：瓶颈分析](#item-18) ⭐️ 7.0/10
19. [英国计划对青少年实施午夜社交媒体宵禁](#item-19) ⭐️ 7.0/10
20. [中国 6 月出口 4120 亿美元创新高，AI 热潮驱动](#item-20) ⭐️ 7.0/10
21. [Google 与 Epic 撤回动议，第三方应用商店入驻 Play](#item-21) ⭐️ 7.0/10
22. [ASML 计划提高光刻设备价格；台积电抵制，部分中企接受](#item-22) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Stripe 与 Advent 出价逾 530 亿美元收购 PayPal](https://www.reuters.com/business/finance/stripe-advent-offer-buy-paypal-more-than-53-billion-sources-say-2026-07-15/) ⭐️ 9.0/10

据消息人士透露，Stripe 与私募股权公司 Advent International 联合提出以超过 530 亿美元收购 PayPal。这笔潜在交易将整合多个主要在线支付平台。 此次收购将打造在线支付领域的巨头，整合 Stripe 的现代基础设施与 PayPal 庞大的用户群及 Venmo、Braintree 等资产。这引发了重大的反垄断担忧，并可能重塑金融科技行业的竞争格局和定价。 据报道，出价对 PayPal 的估值超过 530 亿美元。该交易可能需要剥离 Venmo 或 Braintree 等资产以通过反垄断审查，同时 Stripe 可能获得 PayPal 的银行牌照，从而开展新的金融服务。

hackernews · rvz · 7月15日 03:32 · [社区讨论](https://news.ycombinator.com/item?id=48915953)

**背景**: Stripe 是一家领先的在线支付处理商，以对开发者友好的 API 著称；PayPal 是数字支付领域的先驱，提供 PayPal Checkout、Venmo 和 Braintree 等服务。Advent International 是一家大型私募股权公司，管理资产超过 1000 亿美元。此次收购将因在线非面对面支付领域的市场集中度而面临严格监管审查。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Advent_International">Advent International</a></li>
<li><a href="https://grokipedia.com/page/Advent_International">Advent International</a></li>
<li><a href="https://www.adventinternational.com/">Advent International - A leading global private equity investor</a></li>

</ul>
</details>

**社区讨论**: 社区评论表达了对竞争减少、费用可能上涨以及 Stripe 内容限制（例如封锁大麻和成人业务）的强烈担忧。一些人看到了 Stripe 获得 PayPal 银行牌照的战略价值，但整体情绪负面，用户担心选择减少和风险增加。

**标签**: `#acquisition`, `#fintech`, `#PayPal`, `#Stripe`, `#antitrust`

---

<a id="item-2"></a>
## [Claude web_fetch 漏洞实现数据窃取](https://simonwillison.net/2026/Jul/15/claude-web-fetch-exfiltration/#atom-everything) ⭐️ 9.0/10

安全研究员 Ayush Paul 发现 Claude 的 web_fetch 工具存在一个漏洞，攻击者可绕过防数据窃取保护，提取用户的私人记忆，如姓名、地点和雇主。 该漏洞展示了 AI 助手中“致命三重奏”（私人数据、不可信内容和工具访问）的现实危险，侵蚀了用户信任，并凸显了加强安全措施的必要性。 攻击利用蜜罐站点，指示 Claude 通过嵌套生成的链接逐字导航以窃取数据。Anthropic 声称已内部识别该问题，并通过移除 web_fetch 跟随获取内容中链接的能力进行了修复。

rss · Simon Willison · 7月15日 14:21

**背景**: “致命三重奏”是一个安全概念，描述了私人数据、不可信内容和工具访问的组合，可实现提示注入攻击。Claude 的 web_fetch 工具通常只允许获取用户提供的精确 URL 以确保安全，但该漏洞允许跟随获取页面中的链接，从而实现数据窃取。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://simonwillison.net/2025/Jun/16/the-lethal-trifecta/">The lethal trifecta for AI agents: private data, untrusted content, and ...</a></li>
<li><a href="https://docs.claude.com/en/docs/agents-and-tools/tool-use/web-fetch-tool">Web fetch tool - Claude Docs</a></li>

</ul>
</details>

**标签**: `#security`, `#AI`, `#Claude`, `#data exfiltration`, `#vulnerability`

---

<a id="item-3"></a>
## [马斯克：X 将无条件开源全部代码](https://x.com/elonmusk/status/2077361679034118271) ⭐️ 9.0/10

埃隆·马斯克宣布，在完成安全漏洞审查后，X 平台将无条件开源其全部代码库，并邀请第三方审计者验证正在运行的系统与开源代码的一致性。 这标志着主流社交媒体平台在透明度上的范式转变，可能为软件系统的信任树立新标准，并促使其他平台考虑类似的开放程度。 开源是无条件的，意味着没有对专有组件做任何例外；第三方验证旨在消除对部署代码与发布代码一致性的任何疑虑。

telegram · zaihuapd · 7月15日 13:32

**背景**: X（前身为 Twitter）自成立以来一直是专有平台。埃隆·马斯克于 2022 年收购该公司，此后一直推动提高透明度，包括此前部分公开推荐算法。对于这种规模的平台而言，完全开源整个代码库（包括所有后端系统）将是史无前例的。

**标签**: `#open source`, `#X/Twitter`, `#transparency`, `#Elon Musk`, `#code audit`

---

<a id="item-4"></a>
## [Inkling: Thinking Machines 的开源权重多模态模型](https://thinkingmachines.ai/news/introducing-inkling/) ⭐️ 8.0/10

Thinking Machines Lab 发布了 Inkling，一个开源权重的多模态模型，支持音频、高效推理并通过 Tinker 平台进行微调。 Inkling 填补了开源权重模型中音频理解能力的空白，使企业能够以更低成本定制和运行自己的模型。 该模型并非整体最强，但结合了多模态能力、高效推理以及可通过 Tinker 微调的特点。社区基准测试表明，它在某些任务上可能超越现有的开源模型。

hackernews · vimarsh6739 · 7月15日 18:12 · [社区讨论](https://news.ycombinator.com/item?id=48924912)

**背景**: 开源权重模型将训练好的参数公开，允许任何人下载、运行和微调。与封闭模型不同，它们赋予用户完全控制权，但部署需要更多专业知识。Inkling 专为定制化打造，面向需要专有模型的企业。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://thinkingmachines.ai/news/introducing-inkling/">Inkling: Our open-weights model - Thinking Machines Lab</a></li>
<li><a href="https://allthings.how/what-is-an-open-weight-ai-model-and-how-to-use-one/">What is an Open Weight AI Model and How to Use One</a></li>
<li><a href="https://opensource.org/ai/open-weights">Open Weights: not quite what you’ve been told</a></li>

</ul>
</details>

**社区讨论**: 社区评论对音频支持和微调潜力表示兴奋。一些人指出它可能成为像 DeepSeek 这类中国模型的强有力替代品。还有关于现代模型设计复杂性和 AI 领域红皇后竞赛的讨论。

**标签**: `#open-weights`, `#multimodal`, `#AI model`, `#fine-tuning`, `#audio`

---

<a id="item-5"></a>
## [在 13 年前的至强上无 GPU 运行 Gemma 4 26B，速度 5 tok/s](https://www.neomindlabs.com/2026/06/08/running-gemma-4-26b-at-5-tokens-sec-on-a-13-year-old-xeon-with-no-gpu/) ⭐️ 8.0/10

一位用户成功在无 GPU 的 13 年前至强服务器上，以每秒 5 个 token 的速度运行了谷歌的 Gemma 4 26B 混合专家（MoE）模型，通过激进量化技术将模型装入可用内存。 这表明超过 200 亿参数的大语言模型可以在十年前的硬件上运行，大幅降低了本地 AI 推理的成本和门槛，也展示了现代量化技术的有效性。 Gemma 4 26B 模型采用 MoE 架构，每个 token 激活 40 亿参数，激进量化可能将权重降至 INT4 或更低，从而在内存带宽有限的 CPU 上实现推理。

hackernews · neomindryan · 7月15日 15:34 · [社区讨论](https://news.ycombinator.com/item?id=48922434)

**背景**: 大语言模型（LLM）通常需要具备高内存带宽的强大 GPU。量化技术将模型权重压缩到更低的数值精度（例如从 16 位降至 4 位），减少内存占用，使 CPU 推理成为可能。混合专家（MoE）模型每个 token 仅激活部分参数，进一步提升了效率。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/google/gemma-4-26B-A4B">google/gemma-4-26B-A4B · Hugging Face</a></li>
<li><a href="https://ollama.com/library/gemma4:26b">gemma4:26b</a></li>
<li><a href="https://ai.google.dev/gemma/docs/core">Gemma 4 model overview | Google AI for Developers</a></li>

</ul>
</details>

**社区讨论**: 评论者反应不一：有人预测到 2027 年消费者硬件上可运行更大模型（200B+），也有人质疑本地推理与云 API 相比的成本效益。有用户报告在旧 CPU 上通过不同设置获得了类似速度（8-12 tok/s），还有人在双路 Xeon+256GB DDR4 上运行了多种模型。

**标签**: `#llm`, `#inference`, `#quantization`, `#machine-learning`, `#open-source`

---

<a id="item-6"></a>
## [面壁智能与三星合作，端侧模型将登陆旗舰手机](https://36kr.com/p/3896830362601351?f=rss) ⭐️ 8.0/10

面壁智能宣布与三星手机达成合作，其自主研发的 MiniCPM 系列端侧模型将搭载于数款三星旗舰机型上市。同日，网信部门批准了包括 Apple 智能、三星盖乐世 AI 在内的七款手机端侧生成式人工智能服务备案，标志着规模化落地的开始。 此次合作是端侧 AI 商业化的重要里程碑，验证了专业 AI 模型公司向设备厂商提供能力的市场分工模式。随着多项服务获得监管批准，端侧 AI 正从概念阶段进入消费设备的大规模落地阶段，有望重塑移动 AI 格局。 面壁智能的 MiniCPM5-1B 模型仅 10 亿参数，却在 1B 级开源模型中达到最优性能；MiniCPM-V 4.6 仅需 6GB 内存即可运行。面壁智能累计融资超 50 亿元，估值突破 200 亿元，成为国内端侧 AI 领域估值最高的独角兽。

rss · 36kr · 7月15日 11:47

**背景**: 端侧 AI 是指直接在手机、汽车、PC 等终端设备上运行的大语言模型，具有低延迟、高隐私和离线可用等优势。面壁智能孵化自清华大学自然语言处理实验室，在行业普遍追逐云端大模型时早期押注端侧。其提出的“大模型密度定律”认为开源模型的能力密度约每 3.5 个月翻一番，使小参数模型也能匹敌大模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/OpenBMB/MiniCPM">GitHub - OpenBMB/MiniCPM: MiniCPM5-1B: A SOTA 1B on-device ...</a></li>
<li><a href="https://zhuanlan.zhihu.com/p/1931281139416404545">终于有人把端侧大模型说清楚了 - 知乎</a></li>

</ul>
</details>

**标签**: `#end-side AI`, `#mobile AI`, `#Samsung`, `#Mianbi Intelligence`, `#AI regulation`

---

<a id="item-7"></a>
## [支付宝 AI 版“阿宝”上线，从支付工具转向主动服务平台](https://36kr.com/p/3896720584738435?f=rss) ⭐️ 8.0/10

支付宝推出了名为“阿宝”的 AI 助手，将应用从支付工具转变为主动服务平台，用户可以通过自然语言对话完成查找优惠券、下单购买等任务。该公开测试于 2026 年 7 月开始，是支付宝上线 22 年来最大的一次改版。 这次改版将用户行为从“用完即走”转变为“主动来聊”，显著提升了用户参与度和粘性。这也标志着支付行业从交易终点向服务入口转变的趋势，加剧了中国超级应用生态的竞争。 阿宝目前支持 70 多项高频办事技能，包括查账、缴费、政务和出行等。支付宝还通过 MCP/skill 协议向第三方服务开放 AI 平台，让外部服务能被阿宝调用。

rss · 36kr · 7月15日 09:50

**背景**: 传统上，支付宝等支付应用旨在实现高效、无感的交易，用户交互极少，导致用户粘性较低。AI 助手的引入将应用转变为对话式界面，用户可以主动发现和使用服务，有望提高用户参与度和使用时长。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://technode.com/2026/06/16/alipay-introduces-ai-powered-abao-taking-an-early-lead-in-chinas-super-app-ai-race/">Alipay introduces AI-powered Abao, taking an early lead in ...</a></li>
<li><a href="https://en.wedoany.com/shortnews/341044.html">China's Alipay AI Life Assistant Abao Opens Public Beta</a></li>
<li><a href="https://x.com/caixin/status/2067200184732602459">Caixin Global on X: "Tencent has integrated its AI agent WorkBuddy into WeChat Pay, allowing it to search for deals and initiate purchases on users’ behalf. The move comes as Chinese tech giants race to turn AI agents into gateways for consumer services. https://t.co/UZQxAjHMEI" / X</a></li>

</ul>
</details>

**标签**: `#Alipay`, `#AI`, `#payment industry`, `#user engagement`, `#technology transformation`

---

<a id="item-8"></a>
## [诺基亚与英伟达推出首个商用 AI-RAN 平台](https://36kr.com/newsflashes/3896822215722631?f=rss) ⭐️ 8.0/10

诺基亚与英伟达共同开发了首个商用人工智能驱动的无线接入网络（AI-RAN）平台，目标是在 2028 年前将相同无线频谱上的数据传输容量翻倍。 这是电信行业的一个重要里程碑，首次将 AI 商业化集成到 RAN 中，有望在不增加频谱的情况下大幅提升 5G/6G 网络的容量。 新的 AI-RAN 平台预计将于明年上市，它利用英伟达的 AI 计算能力和诺基亚的 RAN 专业知识，实时优化网络流量、资源分配和干扰管理。

rss · 36kr · 7月15日 11:32

**背景**: 无线接入网络（RAN）是移动网络的关键组件，负责将用户设备连接到核心网络。AI-RAN 将人工智能集成到 RAN 中，实现更高效、自适应和智能的网络运营，例如利用机器学习进行流量管理和资源分配。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ai-ran.org/">AI-RAN Alliance | Shaping Future AI-Native Networks</a></li>
<li><a href="https://www.orbissystems.eu/ai-ran-ai-driven-radio-access-networks/">AI-RAN Explained: The Future of AI-Driven Radio Networks</a></li>

</ul>
</details>

**标签**: `#AI-RAN`, `#Nokia`, `#Nvidia`, `#Telecom`, `#5G/6G`

---

<a id="item-9"></a>
## [利用哈达玛积聚类解构卷积神经元](https://www.reddit.com/r/MachineLearning/comments/1uwya70/mechanistic_interpretability_a_first_paper_on/) ⭐️ 8.0/10

一种新方法利用哈达玛积聚类分析 Inceptionv1 中的单个 1x1 卷积神经元，揭示了针对汽车、猫和字母等概念的单语义聚类。 这项工作为卷积神经网络的机械可解释性提供了一种新技术，能够更细粒度地理解单个神经元如何编码多个概念，从而可能提高模型的透明度和安全性。 该方法对感受野和神经元权重的哈达玛积进行聚类，得到高激活聚类（如汽车、猫）和低激活聚类（如字母）。低激活聚类显示其依赖的神经元也针对同一概念激活，且正负权重分布均衡，表明梯度下降存在刻意行为。

reddit · r/MachineLearning · /u/narang_27 · 7月15日 06:59

**背景**: 机械可解释性是一个将神经网络内部机制逆向工程为人类可理解算法的领域。哈达玛积是矩阵的元素级乘法，此处用于结合感受野和权重以识别神经元检测的内容。这项工作聚焦于卷积神经元，相比 Transformer，卷积神经元在可解释性研究中较少受到关注。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mechanistic_interpretability">Mechanistic interpretability</a></li>
<li><a href="https://en.wikipedia.org/wiki/Hadamard_product_(matrices)">Hadamard product (matrices) - Wikipedia</a></li>

</ul>
</details>

**标签**: `#mechanistic interpretability`, `#convolutional neural networks`, `#interpretability`, `#neuron analysis`, `#machine learning`

---

<a id="item-10"></a>
## [怀念专业 ML 会议的多元化时代](https://www.reddit.com/r/MachineLearning/comments/1uwy25k/does_anyone_else_miss_the_old_conference/) ⭐️ 8.0/10

一篇 Reddit 帖子表达了对旧会议生态系统的怀念，当时像 BMVC、ACCV、FG、ICIP 和 ICASSP 这样的专业会议拥有庞大且专注的社区，而如今研究集中在少数几个旗舰 ML 会议上。 这种情绪凸显了人们对 ML 研究集中化的担忧，这可能会减少社区多样性，造成审稿瓶颈，并导致高质量论文无法发表或难以被发现。 帖子特别提到了投稿数量激增、会议容量有限以及审稿不一致等问题，导致许多好论文只能作为非存档提交、仅出现在 arXiv 上，或者根本没有被分享。

reddit · r/MachineLearning · /u/Sep29493919 · 7月15日 06:47

**背景**: 此前，像 BMVC（英国机器视觉会议）和 ICASSP（国际声学、语音与信号处理会议）这样的专业会议分别是计算机视觉和信号处理研究的主要场所。近年来，ML 研究社区越来越多地集中在少数顶级会议（如 NeurIPS、ICML、CVPR）上，导致注意力和资源从较小的、聚焦的活动中转移。这种转变引发了对研究生态系统健康性的担忧，包括社区身份的丧失和审稿系统的压力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.bmva.org/bmvc">The British Machine Vision Association : The British Machine Vision Conference (BMVC)</a></li>
<li><a href="https://en.wikipedia.org/wiki/International_Conference_on_Acoustics,_Speech,_and_Signal_Processing">International Conference on Acoustics, Speech, and Signal Processing - Wikipedia</a></li>

</ul>
</details>

**标签**: `#machine learning`, `#conferences`, `#research community`, `#publishing`, `#academia`

---

<a id="item-11"></a>
## [DeepSeek 年化收入逼近 5 亿美元，V4 API 毛利率超 50%](https://www.theinformation.com/articles/deepseeks-annualized-revenue-nears-500-million-boosting-fundraise-ipo-plans) ⭐️ 8.0/10

DeepSeek 的年化收入已达到 4 至 5 亿美元，主要来自企业和开发者通过 API 调用模型，同时其 V4 API 毛利率超过 50%。公司计划再进行一轮 500 亿元人民币（约 74 亿美元）的融资，估值约 5000 亿元人民币（合 740 亿美元）。 这一收入和利润率表现表明，DeepSeek 尽管定价低于 OpenAI 和 Anthropic，仍能实现盈利竞争。计划中的 740 亿美元估值融资反映出投资者的强烈信心，可能进一步加剧 AI API 市场的竞争。 年化收入是基于近期月收入推算的全年数据，并非实际实现的全年收入。DeepSeek 计划引入中东等海外投资者，并允许使用美元投资。以上数据均来自匿名知情人士，DeepSeek 尚未回应。

telegram · zaihuapd · 7月15日 07:04

**背景**: DeepSeek 是一家中国人工智能公司，开发大型语言模型并向开发者和企业提供 API 服务。年化收入是将当前收入趋势推算至一整年的预测值，用于估算财务表现。毛利率表示扣除直接成本后留存的收入百分比，超过 50%在 AI 行业被认为是健康的。

**标签**: `#DeepSeek`, `#AI industry`, `#API`, `#revenue`, `#fundraising`

---

<a id="item-12"></a>
## [腾讯成为 DeepSeek 首轮融资最大外部股东](https://www.cls.cn/detail/2427193) ⭐️ 8.0/10

DeepSeek 完成首轮融资，腾讯通过其投资实体成为第一大外部股东，同时宣布将于本月推出完整版 DeepSeek-V4 模型，并启动面向 Agent 和代码智能体等方向的大规模招聘。 这笔融资标志着中国 AI 初创公司 DeepSeek 获得重要行业认可，该公司此前以高性价比的 R1 模型震撼业界，而腾讯、宁德时代、网易和京东的投资为其下一代模型（如 V4）提供了强大的资源支持。 腾讯间接持有新成立的杭州程砺平台超过 33%份额，该平台持有 DeepSeek 约 8.52%股份，使腾讯成为最大外部股东；其他投资者包括宁德时代（11.7%）、网易和京东（各 10%）、IDG（合计 10%）以及国家人工智能产业基金（0.28%）。DeepSeek-V4 预计本月中旬发布，采用 Mixture-of-Experts 架构，参数规模高达 1.6 万亿。

telegram · zaihuapd · 7月15日 12:56

**背景**: DeepSeek 是一家中国 AI 公司，由梁文峰于 2023 年 7 月创立，最初由对冲基金 High-Flyer 资助。2025 年 1 月，DeepSeek-R1 的发布使其获得全球关注，该模型以极低的训练成本与 OpenAI 的 GPT-4 和 o1 相抗衡。该公司采用开放权重模型和高效训练方法（如 MoE），并在出口限制下使用较弱芯片，挑战了英伟达等行业领导者，为美国 AI 领域带来了“斯普特尼克时刻”。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek_(Company)">DeepSeek (Company)</a></li>
<li><a href="https://huggingface.co/deepseek-ai/DeepSeek-V4-Pro">deepseek-ai/DeepSeek-V4-Pro · Hugging Face</a></li>
<li><a href="https://api-docs.deepseek.com/news/news260424/">DeepSeek V4 Preview Release | DeepSeek API Docs</a></li>

</ul>
</details>

**标签**: `#deepseek`, `#funding`, `#tencent`, `#ai`, `#artificial-intelligence`

---

<a id="item-13"></a>
## [Telegram 推出机器人无服务器平台](https://core.telegram.org/bots/serverless) ⭐️ 8.0/10

Telegram 正式推出无服务器平台，开发者现在可以通过一条 CLI 命令（npx tgcloud push）将机器人和 Mini App 的后端 JavaScript 代码直接部署在 Telegram 的基础设施上运行。 这消除了开发者自行配置和管理服务器的需求，大幅降低了构建 Telegram 机器人和 Mini App 的门槛，有望加速生态系统的增长。 代码运行在紧邻 Bot API 的隔离 V8 沙箱中，并自带基于 SQLite 的内置数据库。开发者需要将代码组织为 handlers、lib 和 schema 文件，部署由 Telegram 完全管理。

telegram · zaihuapd · 7月15日 16:00

**背景**: 无服务器计算让开发者可以编写和部署代码，而无需关心底层服务器。Telegram 机器人是与用户交互的自动化程序，传统上需要托管的服务器来处理 webhook 或轮询。V8 沙箱为不受信任的 JavaScript 代码提供内存隔离，增强安全性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://medium.com/@erdavtyan/architecting-highly-scalable-serverless-telegram-bots-5da2bb8fab61">Architecting highly scalable serverless Telegram bots</a></li>
<li><a href="https://chromium.googlesource.com/v8/v8/+/HEAD/docs/sandbox/architecture.md">V8 Sandbox Architecture</a></li>
<li><a href="https://github.com/17tayyy/TgCloudCLI">GitHub - 17tayyy/TgCloudCLI: TgCloudCLI is the CLI tool of TgCloud ...</a></li>

</ul>
</details>

**标签**: `#serverless`, `#telegram`, `#bots`, `#javascript`, `#cloud`

---

<a id="item-14"></a>
## [Telegram 数据中心之谜：位置与区域划分](https://dev.moe/en/3025) ⭐️ 7.0/10

一项分析揭示了 Telegram 的数据中心位置及其按区域划分用户的方式，DC1 位于迈阿密，DC2 在阿姆斯特丹，DC3/DC4 在新加坡，DC5 在美国。文章指出 DC5 经常宕机，影响中国用户，而 DC2 服务于俄罗斯和乌克兰用户。 了解 Telegram 的数据中心架构对于遇到延迟或连接问题的用户至关重要，因为区域划分影响性能和可靠性。该分析强调了潜在的技术债务以及在全球扩展基础设施的挑战。 Telegram 通过 auth.sendCode 方法将每个用户分配到特定 DC，文件通过 dc_id 参数与上传它们的 DC 绑定。社区评论指出 DC3 似乎已被弃用或保留用于特殊用途，系统的复杂性被视为技术债务。

hackernews · theanonymousone · 7月15日 13:22 · [社区讨论](https://news.ycombinator.com/item?id=48920475)

**背景**: Telegram 是一款基于云的消息应用，使用多个数据中心服务全球用户。按区域划分数据有助于降低延迟并遵守数据驻留法律，但也增加了跨 DC 管理用户数据的复杂性。官方 Telegram API 文档说明了用户注册时如何被重定向到合适的 DC。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://core.telegram.org/api/datacenter">Working with Different Data Centers - Telegram APIs 𝐓𝐞𝐥𝐞𝐠𝐫𝐚𝐦 𝐒𝐲𝐬𝐭𝐞𝐦 𝐃𝐞𝐬𝐢𝐠𝐧 𝐎𝐯𝐞𝐫𝐯𝐢𝐞𝐰 Ever ... Images How Telegram Ensures Speed & Reliability at Massive Scale Unmasking Telegram’s Architecture: A Deep Dive Core Architecture | telegramdesktop/tdesktop | DeepWiki Unmasking Telegram’s Architecture: A Deep Dive</a></li>
<li><a href="https://sysdesign.wiki/systems/telegram/">Telegram - System Design Case Study</a></li>
<li><a href="https://www.frugaltesting.com/blog/how-telegram-ensures-speed-reliability-at-massive-scale">How Telegram Ensures Speed & Reliability at Massive Scale</a></li>

</ul>
</details>

**社区讨论**: 社区评论揭示了实际观察：flexagoon 指出 DC5 经常对中国用户宕机，而 DC2 服务于俄罗斯和乌克兰。AntronX 分享说位于迈阿密的 DC 使得 Telegram 在西部海岸响应迅速。glaslong 对 DC3 的缺口感到好奇，londons_explore 批评该架构为技术债务。

**标签**: `#Telegram`, `#data centers`, `#infrastructure`, `#networking`, `#technical debt`

---

<a id="item-15"></a>
## [在软件开发中优先关注心理健康](https://ramones.dev/posts/mental-health/) ⭐️ 7.0/10

一位软件开发者分享了关于心理健康重要性的个人反思，强调了沟通、自我意识以及在工作场所管理神经多样性的重要性。 心理健康在高压力的科技环境中常被忽视，这篇帖子引发了关于为神经多样性人群提供支持以及使职业选择与个人福祉保持一致的重要讨论。 作者设定了具体目标，例如停止“愚蠢的错误”和改进计划，突显了神经多样性开发者即使技术娴熟也会面临的日常挣扎。

hackernews · ramon156 · 7月15日 11:27 · [社区讨论](https://news.ycombinator.com/item?id=48919198)

**背景**: 软件工程需要高度专注和注重细节，这对患有 ADHD 或自闭症等神经多样性个体可能具有挑战性。科技行业历来对心理健康问题存在污名化，但近年来对包容性实践的认知和倡导日益增长。

**社区讨论**: 评论表明，职业错位可能是一个因素，一位用户认为注重细节的工作并不适合所有人。其他人指出，神经多样性模式不能简单地“摆脱”，自我管理策略应侧重于利用个人优势，而非强行改变。

**标签**: `#mental health`, `#software engineering`, `#neurodiversity`, `#career advice`, `#personal growth`

---

<a id="item-16"></a>
## [研究：睡眠规律性比时长更能预测死亡率](https://academic.oup.com/sleep/article/47/1/zsad253/7280269) ⭐️ 7.0/10

2023 年发表在《睡眠》期刊上的一项研究发现，睡眠规律性（睡眠时间的稳定性）在 7 天周期内比睡眠时长更能预测全因死亡率。 这一发现挑战了仅关注睡眠时长的常见做法，表明保持规律的睡眠时间可能对长寿更为关键，可能会改变公共卫生建议和临床实践。 该研究分析了英国生物库中超过 6 万名参与者的数据，使用了基于加速度计的 7 天睡眠数据，并控制了包括轮班工作和就业状况在内的多种混杂因素。

hackernews · bilsbie · 7月15日 11:46 · [社区讨论](https://news.ycombinator.com/item?id=48919363)

**背景**: 睡眠规律性指的是每日睡眠时间的一致性，而睡眠时长则衡量总睡眠小时数。此前的研究已将不规律睡眠和短睡眠与多种健康风险联系起来，但很少有研究直接比较它们对死亡率的预测能力。

**社区讨论**: Hacker News 上的评论观点不一：一些用户分享了使用镁等睡眠补充剂的个人经验，而另一些用户则对职业暴露和宇宙辐射等混杂变量表示担忧，指出研究设计可能没有充分考虑这些因素。

**标签**: `#sleep`, `#health`, `#mortality`, `#research`, `#data science`

---

<a id="item-17"></a>
## [蛋仔派对推出“双子星”编辑器，打造 AI 原生 UGC 平台](https://36kr.com/p/3896755010963333?f=rss) ⭐️ 7.0/10

网易《蛋仔派对》在 2026 年 7 月第四届创作者大会上，正式推出行业首个同时覆盖帧同步与状态同步的 UGC 编辑器体系——“双子星”编辑器，并将 DeepSeek V4 Pro、GLM-5.2、Kimi K2.7 Code 等前沿 AI 大模型深度嵌入创作全链路。 这一举措代表了向 AI 原生 UGC 平台迈进的重要一步，使个人创作者无需大量编程即可制作专业级游戏，可能加速游戏开发领域的“一人公司”趋势。 AI 助手已覆盖 85.9 万作者，产生 224.3 万次会话，辅助编辑地图 85.5 万次。系统还集成了影眸科技的 Rodin 3D 生成算法用于资产创建，并支持从可视化“蛋码”通过 AI 辅助过渡到 Lua 脚本。

rss · 36kr · 7月15日 10:36

**背景**: 帧同步和状态同步是多人在线游戏的两种网络同步模型：帧同步在客户端运行核心逻辑，适合快速确定性游戏；状态同步在服务端运行逻辑，便于防作弊但带宽更高。《蛋仔派对》的“双子星”编辑器首次在 UGC 工具中结合两者。该游戏拥有超过 7 亿注册用户和 5000 万 UGC 创作者。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://bbs.huaweicloud.com/blogs/311156">帧 同 步 与 状 态 同 步 的 区 别 -云社 区 -华为云</a></li>
<li><a href="https://www.firecat-web.com/daily-news/12139">AI原生UGC平台雏形：蛋仔派对的双编辑器与“一人公司”孵化</a></li>

</ul>
</details>

**标签**: `#AI`, `#UGC`, `#Game Development`, `#NetEase`, `#OPC`

---

<a id="item-18"></a>
## [PyTorch 模型在 T4 上比 A100 慢 170 倍：瓶颈分析](https://www.reddit.com/r/MachineLearning/comments/1ux6a9x/pytorch_model_running_170x_slower_on_t4_vs_a100/) ⭐️ 7.0/10

一个基于 PyTorch 的点跟踪模型，使用 4D 相关体积和 Transformer 层，在 NVIDIA T4 GPU 上相比 A100 出现了意想不到的 170 倍减速，尽管两者都运行在纯 FP32 精度下。开发者已经排除了常见问题，如 GPU 利用率、驱动程序问题和模型放置。 这种极端的性能差距表明，简单的硬件规格比较（如 TFLOPS）可能具有误导性，因为内存带宽、张量核心利用率和算法特定瓶颈起着主要作用。理解这种性能下降对于跨不同 GPU 代际经济高效地部署模型至关重要。 该模型使用局部 4D 相关体积进行帧间密集匹配，然后使用 Transformer 层处理时间上下文，全部以 FP32 精度运行。在 T4 上，其张量核心不用于 FP32 运算，被迫依赖 CUDA 核心，而 A100 的 Ampere 架构在正确激活时，通过张量核心提供了显著更高的 FP32 吞吐量。

reddit · r/MachineLearning · /u/Future-Structure-296 · 7月15日 13:44

**背景**: 4D 相关体积是点跟踪中的一种技术，计算两帧之间所有点的成对相关性，产生一个 4D 张量。这种操作内存密集，且易受内存带宽扩展不良的影响。T4 的内存带宽约为 320 GB/s，而 A100 达到约 1555 GB/s，差约 4.8 倍，而非 170 倍，这表明存在额外的算法级低效。此外，T4 上的纯 FP32 运算无法利用张量核心，而 A100 在正确激活张量核心时，FP32 吞吐量最高可达 19.5 TFLOPS，尽管这需要特定条件。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/html/2407.15420v1">Local All-Pair Correspondence for Point Tracking - arXiv.org</a></li>
<li><a href="https://www.ryiuk.pro/research/posts/tensor-core-activation.html">Tensor Core Activation: Precision-Driven Performance</a></li>
<li><a href="https://www.tes-itsolutions.com/product-page/nvidia-a100-40gb-sxm4-hgx-tensor-core-gpu-900-2g509-a500-000">NVIDIA A 100 40GB SXM4 HGX Tensor Core GPU...</a></li>

</ul>
</details>

**标签**: `#pytorch`, `#gpu performance`, `#deep learning`, `#bottleneck analysis`, `#a100 vs t4`

---

<a id="item-19"></a>
## [英国计划对青少年实施午夜社交媒体宵禁](https://www.reuters.com/technology/uk-plans-default-midnight-social-media-curfew-16-17-year-olds-2026-07-14/) ⭐️ 7.0/10

英国政府宣布，将为 16 至 17 岁青少年设置默认的午夜至早上 6 点社交媒体宵禁，并默认关闭自动播放等功能，首批法规预计 2025 年底提交议会，2027 年春季生效。 这项政策可能显著改善青少年的睡眠质量和幸福感，并给社交媒体平台带来压力，要求其在英国范围内实施年龄验证和宵禁控制。 该宵禁为默认设置，用户可手动更改，同时默认关闭延长使用时长的自动播放功能。研究表明，午夜宵禁是家庭最易执行的管控措施。

telegram · zaihuapd · 7月15日 05:34

**背景**: 英国一直在推行更严格的在线安全法规，包括《在线安全法》。此举针对年满 16 岁时可能突然面临社交媒体风险的青少年，旨在保护他们的睡眠和专注力。

**标签**: `#social media regulation`, `#teen safety`, `#UK policy`, `#digital wellbeing`

---

<a id="item-20"></a>
## [中国 6 月出口 4120 亿美元创新高，AI 热潮驱动](https://www.bloomberg.com/news/articles/2026-07-14/china-s-exports-imports-soar-faster-than-forecast-amid-ai-rush) ⭐️ 7.0/10

中国 6 月出口飙升至 4120 亿美元，同比增长 27%，创历史新高，主要受全球 AI 投资超级周期推动。半导体出口按美元计飙升 122%，但因价格暴涨，数量反而下降 0.4%。 这些数据凸显了 AI 热潮如何重塑全球贸易，中国成为芯片和电子产品的重要供应国。创纪录的出口表明 AI 基础设施需求强劲，利好全球半导体和硬件产业。 芯片和计算机贡献了约三分之一的出口增长，低于此前的一半，显示增长正向汽车（首次单月超 100 万辆）、船舶和家电扩散。但对欧盟贸易顺差扩大至创纪录的 329 亿美元，原油进口受中东局势影响暴跌 41%至近十年最低。

telegram · zaihuapd · 7月15日 06:19

**背景**: “AI 超级周期”指人工智能相关硬件、数据中心和基础设施的持续大规模投资期，预计到 2030 年将达 7 万亿美元。中国半导体出口快速增长，反映出全球企业满足 AI 芯片需求，但数量下降凸显定价权。创纪录的贸易顺差可能重新引发与贸易伙伴的紧张关系。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://thesiliconreview.com/2026/07/ai-super-cycle-investment-wall-street-banks-financing-deals">AI Super Cycle: Wall Street Bets Big on AI Investment</a></li>
<li><a href="https://www.cnbc.com/2025/09/26/were-in-an-ai-super-cycle-top-investor-says-and-it-could-last-20-years.html">We're in an AI 'super cycle,' top investor says — and it ...</a></li>
<li><a href="https://www.semiconductor-digest.com/the-7-trillion-ai-supercycle-from-chips-to-data-centers-to-a-new-compute-economy/">The $7 Trillion AI Supercycle: From Chips to Data Centers to ...</a></li>

</ul>
</details>

**标签**: `#China`, `#AI`, `#exports`, `#semiconductors`, `#economics`

---

<a id="item-21"></a>
## [Google 与 Epic 撤回动议，第三方应用商店入驻 Play](https://www.theverge.com/policy/965792/google-epic-withdraw-injunction-third-party-app-stores-coming-google-play) ⭐️ 7.0/10

Google 与 Epic Games 共同撤回修改法院永久禁令的动议后，Google 将于 2026 年 7 月 22 日起在 Google Play 上托管第三方应用商店。 这是 Epic 诉 Google 反垄断案的直接结果，迫使 Google 在自己的商店内分发竞争对手的应用商店，可能重塑 Android 应用分发格局并削弱 Google 的控制。 第三方商店需支付 5000 美元的年费用于安全与政策审查，满足安全要求，且不得在美国以外分发；同时 Google 正为全球侧载开发独立的“Registered App Store”方案。

telegram · zaihuapd · 7月15日 11:15

**背景**: Epic 诉 Google 反垄断诉讼认定 Google 非法垄断了 Android 应用分发市场。法院发布了永久禁令，禁止 Google 阻止第三方应用商店通过 Google Play 分发。侧载（从官方商店外部手动安装应用）一直是争议焦点。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theverge.com/policy/965792/google-epic-withdraw-injunction-third-party-app-stores-coming-google-play">Google and Epic give up fighting — third-party Android... | The Verge</a></li>
<li><a href="https://www.techtimes.com/articles/320593/20260715/epic-google-jointly-withdraw-play-store-settlement-rival-android-app-stores-open-july-22.htm">Epic and Google Jointly Withdraw Play Store Settlement; Rival...</a></li>
<li><a href="https://arstechnica.com/gadgets/2026/07/third-party-app-stores-coming-to-google-play-next-week-as-epic-settlement-withdrawn/">Third-party app stores coming to Google Play next... - Ars Technica</a></li>

</ul>
</details>

**标签**: `#Google Play`, `#Epic Games`, `#app store`, `#antitrust`, `#policy`

---

<a id="item-22"></a>
## [ASML 计划提高光刻设备价格；台积电抵制，部分中企接受](https://news.bloomberglaw.com/artificial-intelligence/asml-plans-price-increases-on-chipmaking-equipment-information) ⭐️ 7.0/10

ASML 宣布计划提高其 EUV 和 DUV 光刻设备的价格。台积电正在抵制 EUV 涨价，而部分中国客户已同意 DUV 设备涨价 10%。 此举可能重塑半导体制造成本和供应动态，尤其是 ASML 在先进 EUV 设备上近乎垄断。它还可能加剧西方芯片制造商与中国企业之间的紧张关系，尤其是在出口管制背景下。 EUV 设备产能已几乎预订至 2027 年底，赋予 ASML 定价权。DUV 设备涨幅具体为 10%，针对的是较旧但仍对许多芯片制造商至关重要的技术。

telegram · zaihuapd · 7月15日 16:49

**背景**: ASML 是光刻机的主导供应商，光刻机对于在晶圆上印制集成电路至关重要。EUV（极紫外）系统支持最先进的工艺节点（如 3nm、5nm），而 DUV（深紫外）系统用于较不先进但仍关键的芯片生产。美荷政府已限制 ASML 向中国出售先进设备。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/EUV_lithography">EUV lithography</a></li>
<li><a href="https://en.wikipedia.org/wiki/DUV_lithography">DUV lithography</a></li>
<li><a href="https://en.wikipedia.org/wiki/ASML">ASML</a></li>

</ul>
</details>

**标签**: `#ASML`, `#semiconductor`, `#lithography`, `#chipmaking`, `#pricing`

---