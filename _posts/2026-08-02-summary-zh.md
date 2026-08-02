---
layout: default
title: "Horizon Summary: 2026-08-02 (ZH)"
date: 2026-08-02
lang: zh
---

> 从 52 条内容中筛选出 13 条重要资讯。

---

1. [卡帕西的“骑自行车的鹈鹕”推文引发 AI 基准测试之争](#item-1) ⭐️ 8.0/10
2. [科技巨头联合签署公开信支持开放权重 AI](#item-2) ⭐️ 8.0/10
3. [ESL 词汇表自 1953 年以来的变化](#item-3) ⭐️ 7.0/10
4. [Bor：面向 Linux 桌面的开源实时策略管理工具](#item-4) ⭐️ 7.0/10
5. [Truth Social 推出每月 10 万美元 API，提供特朗普帖文快速访问](#item-5) ⭐️ 7.0/10
6. [谷歌地球因虚假灾难图像暂停 AI 图像生成功能](#item-6) ⭐️ 7.0/10
7. [中国 AI 模型包揽 OpenRouter 全球调用量前五](#item-7) ⭐️ 7.0/10
8. [LLM 的上下文退化：论文结论与实用应对习惯](#item-8) ⭐️ 7.0/10
9. [CausalVLBench：用于视觉语言模型视觉因果推理的新基准](#item-9) ⭐️ 7.0/10
10. [AI 芯片数量每 9 个月翻番，预计 2028 年达 2 亿颗](#item-10) ⭐️ 7.0/10
11. [苹果限制漏洞报告数量，设 30 天冷却期应对 AI 垃圾报告](#item-11) ⭐️ 7.0/10
12. [中国 AI 框架以近 90%准确率检测比特币洗钱](#item-12) ⭐️ 7.0/10
13. [深海热液喷口动物微塑料检出率高达 92%](#item-13) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [卡帕西的“骑自行车的鹈鹕”推文引发 AI 基准测试之争](https://twitter.com/karpathy/status/2083749667410727319) ⭐️ 8.0/10

安德烈·卡帕西（Andrej Karpathy）发推文讨论用“骑自行车的鹈鹕”作为 AI 基准测试，引发了关于这是否真正检验物理世界理解的辩论。这一基准最初由西蒙·威利森（Simon Willison）创建，要求模型生成一个骑自行车的鹈鹕的 SVG 图像。 这场辩论凸显了评估 AI 模型对物理世界理解这一日益增长的挑战，已超越简单的文本或图像任务。社区的回应方式可能会影响未来基准测试的设计，以及模型是被视为真正智能还是仅仅过度拟合流行提示词。 该基准是非正式的，依赖于单一提示词：“生成一个骑自行车的鹈鹕的 SVG”。一些社区成员认为，当前模型的结果粗糙，多年的 AI 内容接触降低了质量期望，而另一些人则视其为衡量进展的有用定性指标。

hackernews · delichon · 8月2日 04:05 · [社区讨论](https://news.ycombinator.com/item?id=49140998)

**背景**: “骑自行车的鹈鹕”基准测试由开发者西蒙·威利森于 2024 年底创建，用于测试大语言模型的代码生成和空间推理能力。它作为一个非正式基准而流行，因为要求模型理解鹈鹕与自行车在可视化代码输出中的关系。最近的分析，如迪伦·卡斯蒂略（Dylan Castillo）的“pelicanmaxxing”调查，探讨了 AI 实验室是否可能专门针对该基准训练模型，尽管数据表明鹈鹕在模型输出中并非异常常见。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://grokipedia.com/page/Pelican_on_a_bicycle_AI_benchmark">Pelican on a bicycle (AI benchmark)</a></li>
<li><a href="https://github.com/simonw/pelican-bicycle">GitHub - simonw/ pelican - bicycle : LLM benchmark : Generate an SVG...</a></li>
<li><a href="https://dylancastillo.co/posts/pelicanmaxxing.html">Are AI labs pelicanmaxxing? – Dylan Castillo</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了不同看法：有人担心该基准被视为“已用尽”，且 AI 接触降低了质量期望；另一些人则为其辩护，认为它是检验物理世界理解的有用定性基准。一位评论者指出，Anthropic 模型似乎专门针对 three.js 代码训练，使此类基准不太能反映通用能力；另一位则开玩笑说，要生成一个 AI 正在生成骑自行车的鹈鹕 SVG 的 SVG。

**标签**: `#AI`, `#benchmarking`, `#machine learning`, `#evaluation`, `#Karpathy`

---

<a id="item-2"></a>
## [科技巨头联合签署公开信支持开放权重 AI](https://simonwillison.net/2026/Aug/2/open-letters/#atom-everything) ⭐️ 8.0/10

西蒙·威利森总结了近期关于 AI 发展的多封公开信，重点介绍了微软于 7 月 24 日发布的《开放权重与美国 AI 领导力》公开信，该信由包括英伟达、亚马逊和 OpenAI 在内的 235 家 AI 相关公司联署。值得注意的是，Anthropic 未签署该信，并在三天后发布了自身相反的立场。 这封公开信反映了行业内围绕开放权重 AI 政策的重大分歧，可能影响美国政府是否限制此类模型的决策。其结果将塑造开源 AI 的未来以及 AI 提供商之间的竞争格局。 微软的公开信明确支持蒸馏技术，即利用其他模型输出训练模型的做法，并主张政策制定者不应将其与盗用混为一谈。Anthropic 的回应则由 CEO 达里奥·阿莫代伊主导，呼吁打击工业规模的蒸馏操作，同时声称该公司从未主张禁止开放权重模型。

rss · Simon Willison · 8月2日 04:16

**背景**: 开放权重模型公开发布 AI 模型训练后的数值参数（权重），允许任何人下载、运行和微调，但由于训练数据和代码可能仍属专有，因此并非完全开源。这封公开信显然旨在反对美国政府因安全顾虑而禁止或限制此类模型的倾向，尤其是在一项暂停 Claude Fable 5 访问的指令之后。支持者认为开放权重减少了单点故障并促进更广泛的审查，而批评者则担心被威权政府或恶意行为者滥用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.nytimes.com/2026/07/28/technology/open-weight-ai.html">What Is Open-Weights A.I.? - The New York Times</a></li>
<li><a href="https://hai.stanford.edu/ai-definitions/what-is-an-open-weight-model">What is an Open-Weight Model? - Stanford HAI</a></li>

</ul>
</details>

**标签**: `#AI policy`, `#open weights`, `#open source`, `#AI regulation`, `#industry`

---

<a id="item-3"></a>
## [ESL 词汇表自 1953 年以来的变化](https://pudding.cool/2026/07/essential-words/) ⭐️ 7.0/10

Pudding.cool 发布的一项交互式数据分析显示，1953 年至 2023 年间，英语学习者所学词汇发生了巨大变化，许多传统词汇被反映社会变迁的新词汇所取代。 这很重要，因为它表明语言教育如何反映更广泛的文化和社会趋势，影响全球数百万英语学习者所接收的优先事项和价值观。它也引发了关于选择教授哪些词汇时权衡取舍的讨论。 分析发现，'社会交际'层级的词汇量大小基本保持不变，但 1953 年列表中的近四分之一单词到 2023 年已消失，而 2023 年词汇中有 39%是新词。humble、loyalty、fellowship、polite 等词汇让位于 community、identity、organization、ethnic、gender、narrative 等词。

hackernews · c-oreills · 8月2日 15:41 · [社区讨论](https://news.ycombinator.com/item?id=49145590)

**背景**: 该分析可能比较了英语教学中使用的精选词表，例如数十年来对 ESL 课程具有影响力的 General Service List。这些词表旨在优先考虑对学习者最实用的词汇，但什么是'实用'会随着文化、技术和经济变化而改变。1953 年至 2023 年的研究期涵盖了战后、20 世纪末和数字时代词汇教学的不同重点。

**社区讨论**: 社区评论涵盖了为其他语言构建词汇表的实际反思，以及关于语言变化和不平等如何影响词汇选择的争论。一些用户批评文章的滚动交互令人沮丧，而另一些用户则深入探讨了其语言学和教学法含义，例如从关于亲密人际关系的词汇转向更抽象的社会类别词汇。

**标签**: `#English language learning`, `#vocabulary`, `#linguistics`, `#education`, `#data analysis`

---

<a id="item-4"></a>
## [Bor：面向 Linux 桌面的开源实时策略管理工具](https://getbor.dev/blog/2026-08-02-bor-v080-release/) ⭐️ 7.0/10

开源系统 Bor 0.8 已发布，用于集中式 Linux 桌面管理。它采用轻量级 Go 代理与中心服务器，通过 mTLS/gRPC 将 Firefox、Chrome、KDE、dconf、polkit 和软件包管理等策略实时推送到客户端，无需轮询；0.8 版新增了 Thunderbird、Microsoft Edge for Business 和 FirewallD 区域等策略类型。 Bor 填补了 Linux 工作站管理领域的长期空白，为 IT 团队和组织提供了一种现代、实时的替代方案，替代手动配置或传统配置管理工具。凭借对常见桌面环境的支持和不断扩展的策略覆盖，它可能使 Linux 成为企业和非营利组织更易管理的平台。 代理通过 mTLS/gRPC 与服务器通信，策略实时流式下发，无轮询机制。0.8 版新增 Thunderbird、Microsoft Edge for Business 和 FirewallD 区域策略；社区用户也提出了关于自定义脚本、用户映射（如与 Authentik 集成）、配置漂移处理以及为何选择 mTLS 而非 SSH 的问题。

hackernews · eniac111 · 8月2日 09:06 · [社区讨论](https://news.ycombinator.com/item?id=49142569)

**背景**: Bor 面向 Linux 桌面的集中式管理，通过安全的 gRPC 通道将配置策略流式下发到客户端。其策略覆盖桌面环境和系统服务，包括 dconf（GNOME 使用的底层配置系统）、polkit（用于细粒度访问控制的授权框架）以及 FirewallD 区域（定义网络接口的可信级别）。这种方案类似于移动设备管理（MDM），但针对的是 Linux 工作站，既适用于小规模部署，也适用于企业级机群。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Dconf">dconf - Wikipedia</a></li>
<li><a href="https://linuxconfig.org/introduction-to-polkit-navigating-authorization-frameworks-in-linux">Introduction to Polkit: Navigating Authorization Frameworks in Linux</a></li>
<li><a href="https://firewalld.org/documentation/zone/">Documentation - Zone | firewalld</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的讨论总体积极且务实，评论者询问了集成细节，例如如何执行自定义脚本以及如何将 Authentik 等外部身份提供者映射到 Linux 用户。多个问题深入探讨了架构——为何选择 mTLS 而非 SSH、没有轮询时如何应对配置漂移——还有人询问 Bor 与现有工具或 System76 的 Cosmic Sync 相比如何。此外，也有对文档质量的反馈，建议用 Mermaid 取代 ASCII 图表。

**标签**: `#linux-desktop`, `#policy-management`, `#open-source`, `#gRPC`, `#devops`

---

<a id="item-5"></a>
## [Truth Social 推出每月 10 万美元 API，提供特朗普帖文快速访问](https://36kr.com/newsflashes/3922088228957576?f=rss) ⭐️ 7.0/10

8 月 1 日，Truth Social 正式推出“Truth API”数据服务，以每月 10 万美元的价格向华尔街机构出售包括特朗普总统在内的顶级账户帖文的早期访问权限。该服务主要面向高频交易公司。 该 API 引发了关于内幕交易和利益冲突的严重担忧，因为特朗普的社交媒体帖文经常引发股票、债券和大宗商品市场波动。如果付费客户能比普通投资者更快反应，可能破坏市场公平性，并加剧对政治传播商业化方式的监管审视。 该服务每月收费 10 万美元，主要面向高频交易公司，提供所谓的“最快”实时访问最高级别账户帖文的渠道。批评者指出，尽管帖子理论上同时向公众发布，但更快的数据传输加上自动化交易系统，可能让付费订阅者比散户投资者更早采取行动。

rss · 36kr · 8月2日 08:15

**背景**: Truth Social 是特朗普媒体科技集团（TMTG）旗下的社交媒体平台，该公司于 7 月中旬宣布了 Truth API 计划。特朗普经常使用 Truth Social 发布关税、战争、央行领导层等政策声明，市场往往对这些帖文反应剧烈。例如，4 月特朗普发文称赞 Palantir Technologies 和英特尔后，相关股价立即出现波动。该 API 的商业模式本质上是向金融机构收取费用，以换取对这些影响市场言论的更快反应速度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.businessinsider.com/trump-truth-social-early-access-api-markets-2026-8">What smart people are saying about Trump Media charging for early access to the president's Truth Social posts</a></li>
<li><a href="https://thehill.com/policy/technology/5972998-trump-media-technology-group-launch-truth-api/">Trump Media & Technology Group to launch Truth API to sell to Wall Street</a></li>
<li><a href="https://time.com/article/2026/07/17/truth-social-api-wall-street-trump-media/">Trump Media to Sell Traders 'the Fastest' Access to Truth ...</a></li>

</ul>
</details>

**标签**: `#API`, `#finance`, `#social media`, `#ethics`, `#regulation`

---

<a id="item-6"></a>
## [谷歌地球因虚假灾难图像暂停 AI 图像生成功能](https://36kr.com/newsflashes/3922077104664199?f=rss) ⭐️ 7.0/10

谷歌在谷歌地球中上线的 AI 图像生成功能上线不到 48 小时即被暂停。该功能名为 Nano Banana，允许用户通过文本提示生成地点的逼真图像，但因涉及虚假灾难场景的违规行为而被撤回。 这一事件凸显了 AI 生成内容与真实卫星图像叠加以传播虚假信息的风险日益增长。它也展示了 AI 创新与地理空间工具中更强大安全防护需求之间的张力。 AI 生成的图像带有水印，且从未出现在公开的谷歌地球体验中，但用户将截图分享到了平台外部。谷歌表示正在加强护栏，之后才会恢复该功能。

rss · 36kr · 8月2日 07:51

**背景**: 谷歌地球的图像生成功能“Nano Banana”基于公司的 Gemini AI 模型，允许用户通过文本提示重新想象地点，例如将空地变成公园。此前关于地理空间虚假信息的研究表明，基于地理位置的虚假叙事可以在社交媒体上迅速传播，尤其是当它们模仿本地新闻或描绘灾难时。该功能原本面向创意和专业用途，但快速生成的逼真虚假灾难图像立即引发了强烈反应。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.google/products-and-platforms/products/earth/nano-banana-google-earth-image-generation/">Transform any place with Nano Banana in Google Earth</a></li>
<li><a href="https://www.businessinsider.com/google-earth-nano-banana-gemini-ai-satellite-image-generation-function-2026-7">Google Earth's new AI image generation function didn't survive a day after users deepfaked disasters</a></li>

</ul>
</details>

**标签**: `#AI安全`, `#谷歌地球`, `#虚假信息`, `#图像生成`, `#内容审核`

---

<a id="item-7"></a>
## [中国 AI 模型包揽 OpenRouter 全球调用量前五](https://36kr.com/newsflashes/3921989528432259?f=rss) ⭐️ 7.0/10

Chinese AI models claimed all top five spots in OpenRouter's weekly global AI model usage rankings, led by Xiaomi MiMo-V2.5 and DeepSeek, signaling rapid adoption of Chinese LLMs.

rss · 36kr · 8月2日 06:14

**标签**: `#AI`, `#LLM`, `#OpenRouter`, `#Chinese tech`, `#model adoption`

---

<a id="item-8"></a>
## [LLM 的上下文退化：论文结论与实用应对习惯](https://www.reddit.com/r/MachineLearning/comments/1vdsgcj/context_degradation_in_llms_what_the_papers/) ⭐️ 7.0/10

一位 Reddit 用户在 r/MachineLearning 板块发布了一份实用指南，总结了研究论文中关于大语言模型上下文退化的真实结论，并分享了作者为长时间分析任务中养成的应对习惯。该帖将基于研究的发现与保持模型在长对话中性能的实操策略结合起来。 这个问题很重要，因为上下文退化是一个有大量文献支持但常被忽视的问题，它会损害指令遵循能力和事实召回能力。该帖为从业者提供了具体的应对习惯，有助于提高真实工作流中 LLM 驱动分析的可靠性。 该指南以学术论文为基础，这些论文表明 LLM 并不会均匀处理所有上下文 token，随着输入长度增长，性能可能下降。常见的缓解措施包括上下文隔离、检索增强生成（RAG）和显式记忆管理，不过帖子中提到的具体习惯在摘要中没有详细说明。

reddit · r/MachineLearning · /u/usernamehere93 · 8月2日 20:20

**背景**: LLM 处理有限的上下文窗口，即它们一次能够处理的 token 数量，而研究人员观察到，当窗口长度接近上限时，模型对输入开头或中间部分 token 的任务性能常常会下降。这种现象有时被称为上下文退化（context degradation）、上下文腐烂（context rot）或上下文退化综合征（Context Degradation Syndrome），它会削弱指令遵循和对早期信息的准确召回。截断（truncation）、检索增强生成（RAG）和记忆缓冲（memory buffering）等技巧常被用来管理上下文长度并减轻这些影响。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/context-degradation-in-large-language-models">Context Degradation in LLMs</a></li>
<li><a href="https://www.trychroma.com/research/context-rot">Context Rot: How Increasing Input Tokens Impacts LLM Performance | Chroma</a></li>
<li><a href="https://www.morphllm.com/context-rot">Context Rot: Why LLMs Degrade as Context Grows (Complete Guide)</a></li>

</ul>
</details>

**标签**: `#LLM`, `#context degradation`, `#prompting`, `#practical AI`

---

<a id="item-9"></a>
## [CausalVLBench：用于视觉语言模型视觉因果推理的新基准](https://www.reddit.com/r/MachineLearning/comments/1vdd7ty/r_causalvlbench_benchmarking_visual_causal/) ⭐️ 7.0/10

新提出的 CausalVLBench 基准用于评估大型视觉语言模型（VLM）的视觉因果推理能力。它填补了这一特定能力缺乏专门评估工具的空白。 因果理解对于稳健的 AI 至关重要，而现有的 VLM 基准多关注感知和基础推理。CausalVLBench 使研究者能够测量和比较模型从视觉场景推断因果关系的能力，从而指导未来模型开发。 该基准可能包含需要反事实推理、干预推断以及图像或视频中时间因果推断的任务。提供的资料中没有具体的数据集构建方式、任务格式和模型性能结果。

reddit · r/MachineLearning · /u/moschles · 8月2日 09:07

**背景**: 大型视觉语言模型（VLM）结合了视觉和文本理解能力，可用于图像描述和视觉问答等任务。视觉因果推理更进一步，要求模型理解因果关系，例如移动或移除物体后会发生什么。基准测试是研究社区中系统评估和比较模型能力的重要工具。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/blog/vlms">Vision Language Models Explained</a></li>
<li><a href="https://scispace.com/pdf/causal-reasoning-meets-visual-representation-learning-a-3fro8z70.pdf">Causal Reasoning Meets Visual Representation</a></li>
<li><a href="https://openreview.net/pdf?id=XIaubzyOTN">Compositional Visual Causal Reasoning with Language Prompts</a></li>

</ul>
</details>

**标签**: `#benchmark`, `#vision-language models`, `#causal reasoning`, `#evaluation`, `#machine learning`

---

<a id="item-10"></a>
## [AI 芯片数量每 9 个月翻番，预计 2028 年达 2 亿颗](https://www.nytimes.com/interactive/2026/07/29/technology/ai-chips-data-center-boom.html) ⭐️ 7.0/10

据 Epoch AI 估算，全球 AI 芯片数量每 9 个月翻一番，预计到 2028 年底将达到约 2 亿颗。这将是当前约 2000 万颗芯片的 10 倍。 这一预测反映出前所未有的基础设施建设热潮，IDC 预计到 2029 年全球 AI 基础设施投资将突破 1 万亿美元，而去年为 3180 亿美元。然而，这也引发了电价上涨、环境争议以及支出是否超过实际盈利能力的担忧。 美国控制着全球约 80%的 AI 算力，据信仅谷歌一家的 AI 芯片数量就是中国所有公司总和的四倍。中国正通过自研半导体和 AI 基础设施加速追赶。

telegram · zaihuapd · 8月2日 01:01

**背景**: 这一增长由“规模定律”驱动，这是一项经验性发现，表明随着算力、数据和参数规模的增加，AI 模型性能会可预测地提升。Epoch AI 是一个研究 AI 发展轨迹的研究机构，提供了芯片数量估算，而 IDC 则是发布投资预测的市场研究公司。这些预测凸显出当前的 AI 热潮不仅关乎算法，更关乎物理基础设施——芯片、数据中心和电力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Neural_scaling_law">Neural scaling law - Wikipedia</a></li>
<li><a href="https://www.linkedin.com/company/epochai">Epoch AI | LinkedIn</a></li>

</ul>
</details>

**标签**: `#AI hardware`, `#data centers`, `#AI infrastructure`, `#industry trends`

---

<a id="item-11"></a>
## [苹果限制漏洞报告数量，设 30 天冷却期应对 AI 垃圾报告](https://www.ft.com/content/4532122d-90f2-4433-9df6-ca99d8a141d2?syn-25a6b1a6=1) ⭐️ 7.0/10

苹果证实已于今年 6 月开始限制研究人员可同时提交的漏洞报告数量，并设置 30 天冷却期，以应对大量由 AI 生成的低质量安全报告。意大利初创公司 Bynario 称，他们用 ChatGPT 在三周内于最新版 macOS 中发现 50 多个漏洞，包括可让攻击者完全控制电脑的提权漏洞链，但因提交上限而无法上报。 这一举措凸显了 AI 生成的噪音正给漏洞披露渠道带来压力，迫使厂商增设限制，而这些限制也可能阻碍合法研究人员的上报。同时，苹果也在防御侧采用 AI——本周的系统更新修复的漏洞数量约为平时的五倍，并借助了 Anthropic 和 OpenAI 的工具。 据称，30 天冷却期限制了研究人员同时提交的报告数量；苹果表示已联系 Bynario 并审核了其提交的内容。苹果还感谢 Anthropic 和 OpenAI 的工具协助发现漏洞，其最新 macOS 安全更新包含的修复数量约为常规版本的五倍。

telegram · zaihuapd · 8月2日 05:50

**背景**: 漏洞赏金计划允许安全研究人员报告漏洞以换取认可或奖励，苹果、微软、谷歌等大公司均运营自己的项目。近几个月来，Log4j、curl 等开源项目的维护者也反映被大量低质量的 AI 生成漏洞报告淹没，这些报告看起来专业但缺乏实质内容，促使相关项目采取“即时封禁 AI 生成提交”等应对政策。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bug_bounty_program">Bug bounty program</a></li>
<li><a href="https://aiproductivity.ai/news/log4j-ai-generated-security-report-spam/">Log4j Maintainers Drowning in AI - Generated Security Reports , 95...</a></li>
<li><a href="https://biggo.com/news/202506301402_AI_Security_Report_Spam_Hits_curl">AI - Generated Security Reports Flood curl Project... - BigGo News</a></li>

</ul>
</details>

**标签**: `#security`, `#AI`, `#Apple`, `#vulnerability research`, `#bug bounty`

---

<a id="item-12"></a>
## [中国 AI 框架以近 90%准确率检测比特币洗钱](https://www.scmp.com/news/china/science/article/3362493/chinese-police-ai-algorithm-tracks-bitcoin-money-laundering-90-accuracy) ⭐️ 7.0/10

中国人民公安大学的研究团队开发出一款结合记忆模块与大语言模型的 AI 框架，能以近 90%的准确率识别非法加密货币交易。该研究成果发表于 5 月刊的同行评审期刊《情报杂志》。 这标志着 AI 在金融犯罪侦测中的实际应用，为执法部门打击加密货币洗钱提供了一种可解释、可推广的工具。随着加密货币犯罪日益增多，此类 AI 驱动方法可能成为监管执法的重要手段。 该框架据称在检测匿名的跨境比特币交易中隐藏的洗钱行为时，准确率接近 90%。研究团队称它为监管部门提供了可解释的路径；最高人民检察院数据显示，2025 年全国检方共起诉 3,259 名涉及虚拟货币与地下银行洗钱案的嫌疑人。

telegram · zaihuapd · 8月2日 08:22

**背景**: 比特币交易记录在公开账本上，但用户以假名形式存在，因此追踪跨境转账背后的真实身份十分困难。循环神经网络和记忆网络等 AI 模型越来越多地被用于分析序列交易数据，而大型语言模型近期也被应用于区块链异常检测。将记忆模块与 LLM 结合，有助于捕捉简单启发式方法无法发现的长程交易模式。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://informationengineering.dinfo.unifi.it/phdinfo-seminar-francesco-marchetti-the-memory-in-deep-learning-from-recurrent-neural-network-to-memory-network/">PhDInfo Seminar: Francesco Marchetti, “The Memory in Deep learning...</a></li>
<li><a href="https://arxiv.org/html/2410.04039">BlockScan: Detecting Anomalies in Blockchain Transactions</a></li>
<li><a href="https://www.researchgate.net/publication/387104775_AD-LLM_Benchmarking_Large_Language_Models_for_Anomaly_Detection">AD-LLM: Benchmarking Large Language Models for Anomaly ...</a></li>

</ul>
</details>

**标签**: `#AI`, `#cryptocurrency`, `#money laundering`, `#LLM`, `#law enforcement`

---

<a id="item-13"></a>
## [深海热液喷口动物微塑料检出率高达 92%](https://www.yahoo.com/news/science/articles/most-isolated-environments-microplastics-finding-020000452.html) ⭐️ 7.0/10

韩国生物科学与生物技术研究院领衔的一项研究发表在《Water Research》上，研究在西南太平洋和印度洋约 2000 米深的深海热液喷口附近采集的 12 只动物中，有 11 只（92%）检出微塑料。这些动物包括蜗牛和贻贝，平均每只含有 3.42 片微塑料，主要为聚苯乙烯。 这一发现表明，塑料污染已侵入地球上最偏远、最极端的深海生态系统之一，影响了此前被认为不会接触地表污染物的生物。这凸显了从源头减少塑料排放的紧迫性，因为深海清理几乎无法实施，且对这些独特化能合成群落的影响可能长期存在。 该研究共检测了 4 个物种，其中滤食性贻贝体内微塑料分布均匀，而食草性蜗牛的微塑料则集中于消化器官。此外，印度洋样本中的微塑料浓度高于太平洋样本。

telegram · zaihuapd · 8月2日 11:00

**背景**: 深海热液喷口是海底的间歇泉，海水渗入地壳裂隙后被岩浆加热，再以富含矿物质的流体形式喷出，有时会形成高耸的烟囱状结构和“黑烟囱”羽流。这些极端生态系统通过化能合成作用，在无光照的条件下维持生命，即微生物将化学物质转化为能量。滤食是一种摄食策略，贻贝等生物从水中滤食浮游生物等悬浮颗粒，同时也会不自觉地摄入微塑料。这项研究进一步证明了微塑料污染已渗透到几乎所有的海洋环境，从表层海水到深海底。

<details><summary>参考链接</summary>
<ul>
<li><a href="http://www.extremescience.com.s3-website-us-west-2.amazonaws.com/deep-sea-vents.htm">Deep Sea Hydrothermal vents</a></li>
<li><a href="https://www.linkedin.com/posts/woods-hole-oceanographic-institution_deepseadiscovery-extremelife-activity-7298748542427287552-4DDe">What are hydrothermal vents ? | Woods Hole... | LinkedIn</a></li>
<li><a href="https://fiveable.me/key-terms/marine-biology/filter-feeding">Filter Feeding - ( Marine Biology ) - Vocab, Definition... | Fiveable</a></li>

</ul>
</details>

**标签**: `#microplastics`, `#deep-sea`, `#pollution`, `#marine biology`, `#environmental science`

---