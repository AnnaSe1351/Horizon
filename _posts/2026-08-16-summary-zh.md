---
layout: default
title: "Horizon Summary: 2026-08-16 (ZH)"
date: 2026-08-16
lang: zh
---

> 从 36 条内容中筛选出 9 条重要资讯。

---

1. [Anthropic 发布 Claude 系统提示词，推进 AI 透明度](#item-1) ⭐️ 8.0/10
2. [Cloudflare 在切换域名服务器后静默注入 Web Analytics 脚本](#item-2) ⭐️ 8.0/10
3. [Qwen 3.8 27B 表现出色，但默认过度思考](#item-3) ⭐️ 8.0/10
4. [SSOG-Attention：用可分离高斯实现次二次复杂度注意力](#item-4) ⭐️ 8.0/10
5. [重新审视 ECA-Net：中心假设并不可靠](#item-5) ⭐️ 8.0/10
6. [Anthropic 第二季营收超 115 亿美元，同比增 14 倍](#item-6) ⭐️ 8.0/10
7. [AI 信用额度灰市交易：安全与合规风险凸显](#item-7) ⭐️ 7.0/10
8. [Amodei：公众对 AI 的不信任是制度信任危机，而非营销问题](#item-8) ⭐️ 7.0/10
9. [SafePal 披露数据泄露，约 3.98 万客户受影响](#item-9) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Anthropic 发布 Claude 系统提示词，推进 AI 透明度](https://platform.claude.com/docs/en/release-notes/system-prompts) ⭐️ 8.0/10

Anthropic 在其平台文档中公开了用于引导 Claude 的实际系统提示词，让公众首次得以一窥塑造 Claude 生产行为的提示词内容。 这一透明度举措让开发者和研究人员得以了解主要 AI 实验室如何在生产中引导其模型，可能为行业开放性树立标杆。同时，它为提示词工程实践以及真实 LLM 系统中嵌入的安全指令提供了宝贵见解。 公开的提示词包含危机处理、检查用户是否上传图片以及其他安全相关行为的指令。Simon Willison 还构建了这些提示词的 git 历史记录，方便对比 Opus 4.8 和 Opus 5 等模型版本之间的差异。

hackernews · tosh · 8月16日 12:48 · [社区讨论](https://news.ycombinator.com/item?id=49319556)

**背景**: 系统提示词是给 LLM 的预定义指令，用于引导其行为，通常优先于用户输入。AI 部署者用它来确保不同场景下响应的一致性，但提示词内容也可能引入偏见。Anthropic 公开 Claude 的系统提示词，是 AI 开发中关于透明度和问责制更广泛讨论的一部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://promptengineering.org/system-prompts-in-large-language-models/">System Prompts in Large Language Models</a></li>
<li><a href="https://arxiv.org/abs/2505.21091">[2505.21091] Position is Power: System Prompts as a Mechanism of Bias in Large Language Models (LLMs)</a></li>
<li><a href="https://arxiv.org/html/2505.21091v2">Position is Power: System Prompts as a Mechanism of Bias in Large Language Models (LLMs)</a></li>

</ul>
</details>

**社区讨论**: 社区反应总体积极，Simon Willison 分享了提示词变更的 git 历史，以突出不同版本之间的差异。部分评论者对论坛针对 AI 批评性文章的审核表示担忧，而另一些人则质疑通过系统提示词强制“常识”是否有效，并指出系统提示词只是塑造复杂行为系统中的一个层面。

**标签**: `#AI`, `#Claude`, `#system prompts`, `#LLM`, `#transparency`

---

<a id="item-2"></a>
## [Cloudflare 在切换域名服务器后静默注入 Web Analytics 脚本](https://news.ycombinator.com/item?id=49322107) ⭐️ 8.0/10

一名 Hacker News 用户报告称，为了在自定义子域名上提供 R2 存储桶服务而把域名服务器切换到 Cloudflare 后，Cloudflare 静默向其纯 HTML、无 JavaScript 的站点 textlog.cc 注入了 Web Analytics 的 beacon 脚本。用户必须登录 Cloudflare Analytics 控制台，先添加站点再关闭脚本；用户认为这种方式具有侵入性，不应默认开启。 考虑到 Cloudflare 作为约五分之一网站的反向代理，自动注入分析代码对期待站点中不出现第三方脚本的站长和访客都有广泛影响。这也引发关于默认设置的策略问题：会修改站点内容的功能应当让用户主动选择开启，而不是静默加入后让用户手动关闭。 注入的脚本从 static.cloudflareinsights.com/beacon.min.js 加载，并带有 data-cf-beacon 属性，其中包含 token 和构建版本号（如 2024.11.0）。有评论者指出，只有当 Cloudflare 终止 HTTPS（即代理流量）时才能完成注入，因此该问题影响的是开启代理的域名，而不是纯 DNS-only 的配置。

hackernews · stagas · 8月16日 17:49

**背景**: Cloudflare Web Analytics 是 Cloudflare 提供的免费、注重隐私的分析服务，无需 cookie 即可统计访客，支持手动接入或由 Cloudflare 边缘自动注入。Cloudflare 本质上是反向代理：当域名的 DNS 记录开启代理（橙色云）时，HTTP 响应会经过 Cloudflare 边缘节点，边缘节点可以在 HTML 到达浏览器前改写内容，这就是 beacon 脚本出现在纯静态页面中的原因。想避免该行为的用户可以在控制台中关闭 Web Analytics，或通过 Content-Security-Policy 拦截该脚本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=49322107">Tell HN: Cloudflare silently injects its analytics when you switch nameservers | Hacker News</a></li>
<li><a href="https://community.cloudflare.com/t/web-analytics-data-ingestion-options/497952">Web Analytics data ingestion options - Usage & Design - Cloudflare ...</a></li>
<li><a href="https://community.cloudflare.com/t/how-to-disable-the-web-analytics-from-my-domains/286189">How to disable the Web Analytics from my domains - Analytics - Cloudflare Community</a></li>

</ul>
</details>

**社区讨论**: 评论区确认了该行为并提供了缓解方案：有用户建议用 Content-Security-Policy meta 标签限制 script-src 为自身或指定来源，从而拦截被注入的 beacon 脚本。另一位评论者指出，只有在 Cloudflare 终止 HTTPS/代理流量时才会发生注入，也有评论者将这种注入比作恶意代码，并质疑其是否涉及法律问题。

**标签**: `#Cloudflare`, `#Privacy`, `#Web Analytics`, `#DNS`, `#JavaScript`

---

<a id="item-3"></a>
## [Qwen 3.8 27B 表现出色，但默认过度思考](https://simonwillison.net/2026/Aug/16/qwen-38-27b/) ⭐️ 8.0/10

Qwen 发布了采用 Apache-2.0 许可的 Qwen 3.8 27B，这是一款具备视觉能力的语言模型，其官方基准数据显示它超越了 Qwen 3.6 27B 和闭源的 Qwen 3.7-Plus。开发者 Simon Willison 在 M5 Max MacBook Pro 和 NVIDIA DGX Spark 上进行了测试，发现模型默认使用 xhigh 推理强度，导致严重的过度思考。 27B 参数的开权重模型非常适合在配置合理的笔记本上运行，因此强大的视觉语言能力使它成为本地 AI 用户的有力选择。然而，默认的过度思考行为会让它在消费级硬件上几乎不可用，凸显了基准性能提升与实际使用体验之间的张力。 该模型默认的 reasoning_effort 为 xhigh，此外还有 medium 和 low 选项。在 Simon Willison 的测试中，生成一幅鹈鹕骑自行车的 SVG 花了 21 分钟，消耗了 22,276 个推理 token 来产出 3,223 个输出 token，他不得不将 LM Studio 的上下文限制从 8,192 提高到 262,144。

rss · Simon Willison · 8月16日 22:00

**背景**: Qwen 是阿里巴巴推出的大语言模型系列，Qwen 3.8 27B 是一个视觉语言模型（VLM），能够同时理解和生成图像与文本信息。“开权重（open weights）”意味着模型权重是公开的，但与真正的开源 AI 不同，训练数据和完整流程通常不包含在内。推理强度（reasoning effort）是一个控制模型在回答前进行多少思维链计算的参数，xhigh 会产生非常长的内部思考过程。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Vision-language_model_(VLM)">Vision-language model (VLM)</a></li>
<li><a href="https://opensource.org/ai/open-weights">Open Weights: not quite what you’ve been told – Open Source Initiative</a></li>

</ul>
</details>

**标签**: `#LLM`, `#Qwen`, `#open-source`, `#AI`, `#machine-learning`

---

<a id="item-4"></a>
## [SSOG-Attention：用可分离高斯实现次二次复杂度注意力](https://www.reddit.com/r/MachineLearning/comments/1vpt6ay/ssogattention_sum_of_separable_gaussians_as_a/) ⭐️ 8.0/10

这篇文章介绍了 SSOG-Attention，一种新的注意力机制，利用可分离高斯之和将复杂度从 O(N²·d)降至 O(N·√N·d)。实验表明，它在 CIFAR-100 上优于标准缩放点积注意力，并在 ImageNet-1k 上以更快的收敛速度达到相当的性能。 这之所以重要，因为次二次复杂度注意力是让 transformer 扩展到更长序列的关键目标，而 SSOG 为 SDPA 提供了一种实用且高效的替代方案。如果得到广泛验证，它可能影响受二次内存和计算成本限制的大型语言模型和视觉 transformer。 SSOG 为每个头学习少量高斯原子，并根据查询 token 对其进行几何引导，将其分解为可分离的高斯之和。报告中的复杂度为 O(N·√N·d)，并且该方法在更大规模下更快、更节省内存，同时提供相当或更好的准确率。

reddit · r/MachineLearning · /u/4rtemi5 · 8月16日 10:06

**背景**: 缩放点积注意力（SDPA）计算所有查询和键 token 之间的两两相似度，导致随序列长度二次增长的 O(N²·d)复杂度。次二次复杂度注意力方法试图通过稀疏模式、低秩近似或基于核的公式来克服这一问题。可分离高斯允许将多维高斯核写成低维核的乘积，从而实现更高的计算效率。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.pytorch.org/tutorials/intermediate/scaled_dot_product_attention_tutorial.html">(Beta) Implementing High-Performance Transformers with Scaled Dot ...</a></li>
<li><a href="https://louiswang524.github.io/blog/ssa-subquadratic-sparse-attention/">From Quadratic to Linear: A Survey of Subquadratic Sparse Attention ...</a></li>
<li><a href="https://dl.acm.org/doi/10.1016/j.eswa.2023.121352">Large Separable Kernel Attention: : Rethinking the Large Kernel Attention design in CNN: Expert Systems with Applications: An International Journal: Vol 236, No C</a></li>

</ul>
</details>

**标签**: `#attention`, `#efficient-transformers`, `#sub-quadratic-attention`, `#gaussian`, `#machine-learning`

---

<a id="item-5"></a>
## [重新审视 ECA-Net：中心假设并不可靠](https://www.reddit.com/r/MachineLearning/comments/1vptaw9/revisiting_the_efficient_channel_attention_paper/) ⭐️ 8.0/10

一篇对 ECA-Net 论文的批判性再分析指出，其通过一维卷积实现通道注意力的概念论证存在缺陷，尽管 ECA 在实验上确实优于 SE。在国际象棋残局表上的实验显示，k=1 的 ECA 表现与 k=3 几乎相当，这与论文声称跨通道交互是关键的观点相矛盾。 这一分析挑战了被广泛引用的注意力机制，可能促使研究者重新思考通道注意力模块的理论基础。同时，它也凸显了使用已解决的博弈残局表（如国际象棋）作为架构设计无偏基准的价值。 作者在 6 子国际象棋残局表（一个已解决的游戏，共有 3.7 万亿个局面）上比较了多种通道门控模块。结果显示：ECA k=3 的准确率为 96.68%，ECA k=1 为 96.61%，SE8 为 96.17%，恒等映射为 96.04%，表明无交互的 k=1 几乎与 k=3 一样有效。

reddit · r/MachineLearning · /u/arkuto · 8月16日 10:13

**背景**: ECA-Net（高效通道注意力）是 2019 年提出的一种轻量级通道注意力模块，它直接对通道均值做一维卷积，避免了 Squeeze-and-Excitation（SE）模块中的降维操作。通道注意力机制通过选择性地加权特征通道来提升模型性能。作者将“沿通道维度做卷积”类比为“对表格数据使用卷积”，而表格数据本身没有空间或时间上的拓扑结构。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/1910.03151">[1910.03151] ECA-Net: Efficient Channel Attention for Deep Convolutional Neural Networks</a></li>
<li><a href="https://github.com/bangguwu/ecanet">GitHub - BangguWu/ECANet: Code for ECA-Net: Efficient Channel Attention for Deep Convolutional Neural Networks · GitHub</a></li>
<li><a href="https://www.researchgate.net/figure/Block-diagram-of-the-Squeeze-and-Excitation-SE-attention-block-according-to-Hu-et-al_fig2_360214840">Block diagram of the Squeeze - and - Excitation ( SE ) attention block</a></li>

</ul>
</details>

**标签**: `#efficient-channel-attention`, `#deep-learning`, `#paper-analysis`, `#attention-mechanisms`

---

<a id="item-6"></a>
## [Anthropic 第二季营收超 115 亿美元，同比增 14 倍](https://www.cnbc.com/2026/08/15/anthropic-revenue-jumps-to-over-11point5-billion-in-q2-report.html) ⭐️ 8.0/10

Anthropic 公布的初步第二季度营收超过 115 亿美元，同比增长逾 14 倍。随着公司筹备最早可能于今年秋季启动的大型 IPO，其调整后营业利润也转为正值。 爆炸式的营收增长验证了先进 AI 模型的强劲商业需求，对领先的 AI 初创公司之一而言是一个重大业务里程碑。调整后营业利润转正以及可能的 IPO，表明 AI 基础设施热潮正在转化为可持续盈利和公开市场的成熟。 这些数字是初步数据，仍可能调整，且显示出较 2026 年第一季度的 47.3 亿美元和去年同期的 7.87 亿美元的急剧加速增长。公司第二季度调整后营业利润转正，早于可能于今年秋季启动的大型 IPO。

telegram · zaihuapd · 8月16日 07:26

**背景**: Anthropic 是一家领先的人工智能公司，以开发 Claude 系列大语言模型而闻名，并高度重视 AI 安全。其营收增长反映了企业对生成式 AI 工具和云端推理服务采用的激增。成功上市将使 Anthropic 成为少数几家上市的 AI 模型开发商之一，为 AI 行业提供关键的估值基准。

**标签**: `#Anthropic`, `#revenue`, `#AI industry`, `#IPO`, `#business`

---

<a id="item-7"></a>
## [AI 信用额度灰市交易：安全与合规风险凸显](https://vectoral.com/blog/who-are-the-token-brokers) ⭐️ 7.0/10

一个灰色市场正在兴起，第三方“令牌经纪人”转售未使用的人工智能 API 信用额度，这通常违反平台服务条款。Vectoral 的分析指出，经纪人通过转售注册奖励或 B2B 合作伙伴福利获得的信用额度来牟利。 这一现象影响 OpenAI、Google 等 AI 平台，加剧欺诈、账户盗用和政策违规问题，并破坏促销信用体系的完整性。用户若信任不受监管的第三方经纪人，也可能面临账户被黑和私人数据泄露的风险。 经纪人通常以大幅折扣转售信用额度，但买家无法验证实际访问的是哪个模型。平台可以通过追踪中继账户的 IP 地址来发现滥用行为，但这类做法依然存在，与机票酒店忠诚度计划中延续数十年的滥用模式相似。

hackernews · mlenhard · 8月16日 14:44 · [社区讨论](https://news.ycombinator.com/item?id=49320611)

**背景**: AI 令牌是模型处理的数据单位，API 信用额度是令牌的预付费配额。平台常为新账户提供免费信用额度，形成可转售的未用额度供给。这种灰市类似于“令牌套利”，在注册、支付、使用和退款流程中钻空子以获取利润，而非进行合法消费。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/token-arbitrage-economy-why-ai-platforms-facing-sophisticated-igkec">The Token Arbitrage Economy: Why AI Platforms Are Facing...</a></li>
<li><a href="https://blogs.nvidia.com/blog/ai-tokens-explained/">What Are AI Tokens ? The Language and Currency... | NVIDIA Blog</a></li>

</ul>
</details>

**社区讨论**: 评论者对信任没有声誉的第三方经纪人表示怀疑，指出这等于招致黑客攻击或将私人数据发送给陌生邮箱。还有人指出模型蒸馏是个有趣的角度，并认为这种滥用模式在忠诚度计划中已存在数十年。另有人批评该研究过于浅显，并指向 linux.do 和 nodeseek.com 上庞大的令牌转售社区。

**标签**: `#AI`, `#grey market`, `#security`, `#platform abuse`, `#token brokers`

---

<a id="item-8"></a>
## [Amodei：公众对 AI 的不信任是制度信任危机，而非营销问题](https://simonwillison.net/2026/Aug/16/dario-amodei/) ⭐️ 7.0/10

Anthropic CEO Dario Amodei 于 2026 年 8 月 16 日发推文，认为公众对 AI 的不信任主要源于对制度更广泛的信任危机，而非 AI 领袖的风险警告。他反对采用华丽营销活动的做法，并表示只有通过切实的成就（例如真正治愈癌症）才能恢复信任。 这一表态回应了 AI 伦理领域中一个关键争论，即 AI 领袖自身的悲观警告是否会加剧公众恐惧。Amodei 的视角将焦点从传播信息转移到实际交付成果，可能影响 AI 公司如何接受问责以及如何与公众沟通。 Amodei 承认，包括 Anthropic 在内的 AI 公司最准确的批评是未能兑现惠及世界的重大承诺。他指出，信任危机比 AI 早了几十年，并坚称“真正治愈癌症”远比任何正面包装的营销活动更有效。

rss · Simon Willison · 8月16日 15:05

**背景**: Anthropic 是一家专注于 AI 安全领域的领先 AI 公司，Dario Amodei 一直是 AI 风险讨论中的重要声音。近年来，一些评论人士认为，AI 高管频繁公开警告灾难性风险，加剧了公众对技术的不信任和抵制。Amodei 的推文回应了这些说法，指出这种不信任是系统性和长期性的，而非由特定言论造成。

**标签**: `#AI`, `#public trust`, `#AI ethics`, `#Anthropic`, `#Dario Amodei`

---

<a id="item-9"></a>
## [SafePal 披露数据泄露，约 3.98 万客户受影响](https://www.reuters.com/legal/litigation/crypto-wallet-provider-safepal-discloses-data-breach-affecting-nearly-40000-2026-08-16/) ⭐️ 7.0/10

SafePal 于 8 月 16 日披露，其订单追踪系统发生数据泄露，约 39,798 名客户的订单信息被未授权访问。受影响的资料包括姓名、地址和购买数据，泄露时间为 2025 年 3 月 2 日至 2026 年 4 月 11 日。 该事件之所以重要，是因为被泄露的订单信息可能被用于对加密货币用户进行定向钓鱼和冒充攻击，尽管资金本身是安全的。SafePal 在全球拥有超过 2500 万用户，此次泄露表明钱包基础设施之外的客户数据仍可能给整个加密生态带来安全风险。 SafePal 表示，泄露未涉及助记词、私钥、钱包密码及银行账户等信息。公司已修复该漏洞，并下架了 30 多个与此次泄露相关的欺诈网站和钓鱼链接。

telegram · zaihuapd · 8月16日 17:06

**背景**: SafePal 是一家成立于 2018 年的加密货币钱包提供商，提供 S1、S1 Pro 和 X1 等硬件钱包，并支持比特币、BNB 等主流加密货币。在加密货币钱包中，资金由私钥或种子助记词（如 BIP39 助记词）保护；只要这些信息未泄露，攻击者就无法直接盗取资产。此次泄露仅涉及订单追踪数据，而非钱包凭证，但被窃取的个人信息仍可能被用于社工攻击。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://grokipedia.com/page/SafePal">SafePal</a></li>
<li><a href="https://www.safepal.com/">SafePal Crypto Hardware Wallet (Official) | The best wallet to protect...</a></li>
<li><a href="https://iancoleman.io/bip39/">BIP 39 - Mnemonic Code</a></li>

</ul>
</details>

**标签**: `#data breach`, `#security`, `#cryptocurrency`, `#SafePal`, `#privacy`

---