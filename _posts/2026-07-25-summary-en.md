---
layout: default
title: "Horizon Summary: 2026-07-25 (EN)"
date: 2026-07-25
lang: en
---

> From 54 items, 17 important content pieces were selected

---

1. [vLLM v0.26.0: Inkling support, DeepSeek-V4 optimizations, and more](#item-1) ⭐️ 9.0/10
2. [Anthropic Unveils Claude Opus 5, Competes with Frontier Models at Half Price](#item-2) ⭐️ 9.0/10
3. [Samsung and SK Hynix Plan $1 Trillion Chip Project with US Tech Giants](#item-3) ⭐️ 9.0/10
4. [sglang v0.5.16: DSpark Speculative Decoding and Inkling Support](#item-4) ⭐️ 8.0/10
5. [Android May Restrict On-Device ADB, Sparking Debate](#item-5) ⭐️ 8.0/10
6. [Open-weight AI models become a platform akin to Kubernetes](#item-6) ⭐️ 8.0/10
7. [AMD's AI 2026 Strategy to Break CUDA Moat](#item-7) ⭐️ 8.0/10
8. [SK Group and NVIDIA $500B+ AI Partnership for Factories and HBM](#item-8) ⭐️ 8.0/10
9. [China Issues New Offshore Trust Tax Rules](#item-9) ⭐️ 8.0/10
10. [Samsung and Broadcom Sign $200B Semiconductor Deal](#item-10) ⭐️ 7.0/10
11. [Moody's Warns AI Investment Boom Strains Tech Firms' Finances](#item-11) ⭐️ 7.0/10
12. [Qualcomm warns of price hike across all products from Sept 1](#item-12) ⭐️ 7.0/10
13. [Apple Lobbies Trump to Use Chinese Storage Chips, Opposed by Micron](#item-13) ⭐️ 7.0/10
14. [Job security drives Chinese college admissions shift](#item-14) ⭐️ 7.0/10
15. [Ctrip Announces 19 Rectification Measures After Antitrust Penalty](#item-15) ⭐️ 7.0/10
16. [AMD Confirms Zen 7 EPYC 'Florence' for 2028, Zen 8 'Ravenna' for 2030](#item-16) ⭐️ 7.0/10
17. [Microsoft Blocks Pirated Windows Activations with TPM Chips](#item-17) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [vLLM v0.26.0: Inkling support, DeepSeek-V4 optimizations, and more](https://github.com/vllm-project/vllm/releases/tag/v0.26.0) ⭐️ 9.0/10

vLLM released version 0.26.0 with 411 commits from 212 contributors, introducing the new Inkling model family, significant DeepSeek-V4 performance improvements, fp32 lm_head support, flexible attention backends, and matured KV offloading with tiered secondary storage. Additionally, the Rust frontend now supports multimodal video and audio, and the Transformers backend has been updated to 5.13.0 with more model migrations. This major update positions vLLM as a leading inference engine for next-generation models like the 1T-parameter multimodal Inkling, offering day-0 support with optimized performance. The DeepSeek-V4 optimizations deliver notable end-to-end speedups across vendors, and new features like per-KV-cache-group attention backend selection improve flexibility for hybrid models, benefiting the entire LLM deployment ecosystem. The Inkling model family includes piecewise CUDA graph support, Hopper FA4 relative attention, MTP=1 speculative decoding, LoRA, and standard ModelOpt NVFP4 quantization. DeepSeek-V4 gains a specialized routing kernel (2.94% E2E TPOT improvement), fused_topk_bias (1.5–2x kernel speedup), and redundant repeat/copy removal (1.8% E2E TPOT), plus ROCm and sparse decode/prefill optimizations. fp32 lm_head is enabled via head_dtype, and the attention backend can now be selected per KV-cache group, with sliding-window as an explicit backend capability.

github · khluu · Jul 25, 10:38

**Background**: vLLM is a high-performance open-source library for LLM inference and serving, known for its efficient PagedAttention and support for various hardware backends. The Inkling model, developed by Thinking Machines Lab, is a 1T-parameter multimodal model that accepts text, image, and audio inputs with up to 1M context length, featuring novel architectural components like relative attention, short convolution, and shared expert sinks. DeepSeek-V4 is a large language model from DeepSeek, and vLLM's optimizations aim to reduce latency and improve throughput across NVIDIA, AMD, and Intel XPU platforms.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.vllm.ai/en/latest/api/vllm/models/inkling/">inkling - vLLM</a></li>
<li><a href="https://vllm.ai/blog/2026-07-15-inkling">TML Inkling on vLLM: Day-0 Support with Optimized Performance</a></li>
<li><a href="https://github.com/vllm-project/vllm/blob/main/vllm/models/inkling/nvidia/ops/fa4_rel_attention.py">vllm/vllm/models/inkling/nvidia/ops/fa4_rel_attention.py at ...</a></li>

</ul>
</details>

**Tags**: `#vLLM`, `#LLM inference`, `#GPU optimization`, `#performance`, `#open-source`

---

<a id="item-2"></a>
## [Anthropic Unveils Claude Opus 5, Competes with Frontier Models at Half Price](https://simonwillison.net/2026/Jul/24/introducing-claude-opus-5/#atom-everything) ⭐️ 9.0/10

Anthropic has released Claude Opus 5, a new AI model that approaches the frontier intelligence of Claude Fable 5 at half the price. It currently leads the Artificial Analysis leaderboard, surpassing even Fable 5. This release significantly reduces the cost of near-frontier AI, making advanced capabilities more accessible to developers and enterprises. It also intensifies competition in the AI model market, potentially driving further innovation and price reductions. Claude Opus 5 is priced the same as its predecessor Opus 4.8 and offers a fast mode at double the base cost. It demonstrated proactive behavior by writing its own computer vision pipeline to reconstruct a 3D model from a drawing when given no direct viewing method.

rss · Simon Willison · Jul 24, 23:48

**Background**: Anthropic's Claude models are named after sizes: Haiku, Sonnet, and Opus, with Opus being the largest. In 2026, Anthropic introduced additional models like Fable and Mythos, where Fable 5 is the most capable widely released model. Opus 5 slots between Opus 4.8 and Fable 5, offering a balance of performance and cost.

<details><summary>References</summary>
<ul>
<li><a href="https://llm-stats.com/benchmarks/artificial-analysis">Artificial Analysis Leaderboard - llm-stats.com</a></li>
<li><a href="https://platform.claude.com/docs/en/about-claude/models/overview">Models overview - Claude Platform Docs</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_(AI)">Claude (AI) - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Boris Cherny highlighted that Opus 5 is among the least prompt-injectable models yet, based on system card evaluations and red teaming, which is a promising security improvement. The overall buzz from the community has been positive, with excitement about its proactive capabilities and competitive pricing.

**Tags**: `#AI`, `#Anthropic`, `#Claude`, `#language model`, `#machine learning`

---

<a id="item-3"></a>
## [Samsung and SK Hynix Plan $1 Trillion Chip Project with US Tech Giants](https://36kr.com/newsflashes/3910551543289216?f=rss) ⭐️ 9.0/10

South Korean memory chip makers Samsung Electronics and SK Hynix are planning a massive chip cooperation project with US tech giants, valued at 1375 trillion won (approximately $1 trillion), according to a presidential advisor in South Korea. This unprecedented investment scale could significantly reshape the global semiconductor supply chain and strengthen Korea-US technological alliances, impacting industries from AI to consumer electronics. The project involves two of the world's largest memory chip manufacturers and unspecified US tech giants, though the exact scope and timeline have not been disclosed. The figure represents one of the largest ever joint semiconductor investments.

rss · 36kr · Jul 25, 06:11

**Background**: Semiconductors are critical components in modern electronics, and memory chips (like DRAM and NAND) are essential for devices from smartphones to data centers. South Korea's Samsung and SK Hynix dominate the global memory market, and collaboration with US firms aims to secure supply chains amid geopolitical tensions.

**Tags**: `#semiconductor`, `#Samsung`, `#SK Hynix`, `#investment`, `#Korea-US cooperation`

---

<a id="item-4"></a>
## [sglang v0.5.16: DSpark Speculative Decoding and Inkling Support](https://github.com/sgl-project/sglang/releases/tag/v0.5.16) ⭐️ 8.0/10

sglang v0.5.16 introduces DSpark, a novel confidence-driven speculative decoding algorithm achieving 383.7 tok/s on DeepSeek-V4-Pro, and adds support for Inkling, a 975B-parameter multimodal MoE model with 1M-token context. The release also includes other model support, performance optimizations, and infrastructure improvements. DSpark offers a significant throughput improvement for serving large language models by adaptive verification, while Inkling support enables efficient deployment of a cutting-edge multimodal MoE with million-token context. These features position sglang as a leading inference engine for both text-only and multimodal AI workloads. DSpark achieves an acceptance length ~5 with 383.7 tok/s on DeepSeek-V4-Pro (TP8, B300). Inkling reaches up to 71.7k tok/s input and 171.0 tok/s per-user decode on Blackwell hardware. The release also removes experimental QServe and FBGEMM FP8 quantization paths, and makes UnifiedRadixTree the default for SWA, Mamba, and DSA models.

github · Qiaolin-Yu · Jul 25, 00:13

**Background**: Speculative decoding accelerates LLM inference by using a smaller draft model to generate candidate tokens, which a larger target model then verifies in parallel. Multimodal MoE models like Inkling combine multiple modalities (text, image, audio) with mixture-of-experts architecture for efficient scaling. sglang is an open-source LLM serving framework optimized for high throughput and low latency.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2607.05147">[2607.05147] DSpark: Confidence-Scheduled Speculative ...</a></li>
<li><a href="https://thinkingmachines.ai/news/introducing-inkling/">Inkling: Our Open-Weights Model - Thinking Machines Lab</a></li>
<li><a href="https://huggingface.co/nm-testing/nvfp4_moe-e2e/tree/main">nm-testing/ nvfp 4 _ moe -e2e at main</a></li>

</ul>
</details>

**Tags**: `#LLM inference`, `#speculative decoding`, `#sglang`, `#AI infrastructure`, `#multimodal`

---

<a id="item-5"></a>
## [Android May Restrict On-Device ADB, Sparking Debate](https://kitsumed.github.io/blog/posts/android-may-soon-restrict-on-device-adb/) ⭐️ 8.0/10

Android may soon restrict on-device ADB (Android Debug Bridge) access, a change that has sparked intense debate among developers. The proposal would limit ADB usage to authorized hosts or specific networks, potentially breaking existing workflows. This change could significantly impact developers who rely on ADB for app development, testing, and debugging on Android devices. It highlights the ongoing tension between security improvements and developer control, and may force developers to adopt new workflows or face restrictions. The attack vector requires both Developer Options and remote ADB to be enabled, affecting only about 0.1% of users. The proposed restriction would allow developers to limit ADB to specific IP addresses or interfaces, such as a VPN like Tailscale.

hackernews · shscs911 · Jul 25, 06:57 · [Discussion](https://news.ycombinator.com/item?id=49045159)

**Background**: ADB (Android Debug Bridge) is a command-line tool used for debugging Android devices, allowing developers to install apps, run shell commands, and access logs. It is enabled via Developer Options and requires explicit user authorization. Over the years, ADB has been exploited in some attacks, leading to calls for tightened security.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.android.com/tools/adb">Android Debug Bridge (adb) | Android Studio | Android Developers</a></li>
<li><a href="https://www.howtogeek.com/125769/how-to-install-and-use-abd-the-android-debug-bridge-utility/">How to Install and Use ADB, the Android Debug Bridge Utility</a></li>
<li><a href="https://lifetips.alibaba.com/tech-efficiency/is-usb-debugging-risky-the-truth-about-android-adb-safety">Is USB Debugging Risky? The Truth About Android ADB Safety</a></li>

</ul>
</details>

**Discussion**: Comments show mixed reactions: some developers argue the restriction is an overreaction since the attack vector is unrealistic for most users, while others see it as a necessary security step or even a precursor to Google exerting more control over devices. A few suggest a more nuanced approach, like restricting ADB to specific networks, which the proposal seems to include.

**Tags**: `#Android`, `#ADB`, `#security`, `#developer tools`

---

<a id="item-6"></a>
## [Open-weight AI models become a platform akin to Kubernetes](https://tobi.knaup.me/2026-07-25-open-weight-ai-is-having-its-kubernetes-moment/) ⭐️ 8.0/10

The article argues that open-weight AI models are becoming the dominant platform in AI, similar to how Kubernetes became the standard for container orchestration, with implications for geopolitics, pricing, and innovation. This shift could democratize AI development, prevent vendor lock-in, and provide a baseline for inference costs, while also raising geopolitical concerns about model origin and regulation. The article uses the Kubernetes analogy to highlight that once an open platform becomes the industry's center of gravity, no single vendor can match the combined innovation rate. Community comments also discuss the feasibility of banning models by origin and the volatility of 'tokenomics' pricing.

hackernews · tknaup · Jul 25, 14:49 · [Discussion](https://news.ycombinator.com/item?id=49048034)

**Background**: Open-weight AI models are models whose internal parameters (weights) are publicly available, allowing anyone to download, modify, and deploy them. This contrasts with closed models like OpenAI's GPT-4, where only API access is provided. 'Tokenomics' refers to the economics of token usage in AI, including pricing and supply dynamics. The Kubernetes moment refers to the point where an open-source platform becomes the de facto standard, driving ecosystem growth.

<details><summary>References</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/open-weight-ai-what-we-finally-opened-bonnet-nicolas-pistorio-n3ulf">Open - weight AI : what if we finally opened the bonnet ?</a></li>
<li><a href="https://www.microsoft.com/en-us/corporate-responsibility/topics/open-weight/">Open Weights and American AI Leadership</a></li>
<li><a href="https://en.wikipedia.org/wiki/Tokenomics">Tokenomics - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Community members debate the feasibility of banning models by origin (e.g., Chinese models), noting weights are just numbers and cannot be traced to a country. Others praise the insight that open platforms outpace single vendors in innovation, and criticize the opacity of tokenomics pricing, suggesting open-weight models provide a sanity check on costs.

**Tags**: `#open-weight`, `#AI models`, `#Kubernetes`, `#tokenomics`, `#open source`

---

<a id="item-7"></a>
## [AMD's AI 2026 Strategy to Break CUDA Moat](https://newsletter.semianalysis.com/p/can-amd-break-the-cuda-moat-amd-advancing) ⭐️ 8.0/10

SemiAnalysis published a deep dive into AMD's plan to compete with NVIDIA's CUDA ecosystem, covering software improvements via agentic kernel generation, production challenges in the Helios MI455X ramp, and aggressive financial engineering offering up to 105% discounts. If AMD succeeds, it could weaken NVIDIA's stranglehold on AI computing, lower costs for customers, and accelerate innovation in AI hardware and software. The outcome will affect the entire AI industry's infrastructure choices. Agentic kernel generation uses LLM agents to automatically generate and optimize GPU kernels, a key software differentiator. The Helios MI455X system features 72 GPUs with 31 TB HBM4 memory but only 896 GB/s interconnect bandwidth, far below NVIDIA's NVLink 6 at 3.6 TB/s. AMD's financial engineering has offered discounts of up to 105% to win deals.

rss · Semianalysis · Jul 25, 00:33

**Background**: CUDA is NVIDIA's proprietary parallel computing platform that has become the de facto standard for AI workloads, creating a moat that locks developers into NVIDIA hardware. AMD's ROCm is an open-source alternative but has historically suffered from software quality and ecosystem gaps. Agentic kernel generation aims to automate the tedious manual process of writing optimized compute kernels, which could make AMD's hardware easier to program. Financial engineering involves creative pricing strategies like steep discounts to attract customers from NVIDIA.

<details><summary>References</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/agentic-kernel-generation">Agentic Kernel Generation</a></li>
<li><a href="https://www.servethehome.com/amds-epyc-venice-instinct-mi455x-helios-hardware-on-display-for-first-time-at-ces-2026/">AMD’s EPYC Venice, Instinct MI 455 X , & Helios ... - ServeTheHome</a></li>
<li><a href="https://en.wikipedia.org/wiki/Finance_Engineering">Finance Engineering</a></li>

</ul>
</details>

**Tags**: `#AMD`, `#CUDA`, `#GPU`, `#AI hardware`, `#software ecosystem`

---

<a id="item-8"></a>
## [SK Group and NVIDIA $500B+ AI Partnership for Factories and HBM](https://36kr.com/newsflashes/3910690882507907?f=rss) ⭐️ 8.0/10

SK Group and NVIDIA announced a strategic partnership valued at over $500 billion to build AI factories and develop next-generation HBM memory. SK Telecom will construct a 2 GW NVIDIA Vera Rubin DSX AI factory, and SK hynix will collaborate with NVIDIA on next-gen AI memory solutions including HBM. This partnership significantly expands AI infrastructure capacity and secures a long-term supply of advanced HBM memory, which is critical for training large language models and powering agentic and physical AI. The scale of investment underscores the industry's urgent need for integrated AI factory design and high-bandwidth memory to meet soaring global compute demand. SK Telecom's 2 GW AI factory will use the NVIDIA Vera Rubin DSX reference design, which provides a blueprint for building co-designed AI infrastructure with maximum tokens-per-watt. The partnership also formalizes long-term collaboration on HBM memory, likely encompassing HBM4 and beyond, to address evolving AI workload demands from LLM training to agentic and physical AI.

rss · 36kr · Jul 25, 06:40

**Background**: AI factories are large-scale data centers purpose-built to accelerate AI workloads, combining optimized compute, networking, and cooling. High Bandwidth Memory (HBM) is a critical component for AI accelerators, providing high-speed data access between memory and GPU dies; each generation (e.g., HBM3, HBM4) roughly doubles throughput to keep pace with growing model sizes. NVIDIA's Vera Rubin DSX is a reference architecture that standardizes AI factory design, enabling faster deployment and higher efficiency.

<details><summary>References</summary>
<ul>
<li><a href="https://nvidianews.nvidia.com/news/nvidia-releases-vera-rubin-dsx-ai-factory-reference-design-and-omniverse-dsx-digital-twin-blueprint-with-broad-industry-support">NVIDIA Releases Vera Rubin DSX AI Factory Reference Design and Omniverse DSX Digital Twin Blueprint With Broad Industry Support | NVIDIA Newsroom</a></li>
<li><a href="https://en.wikipedia.org/wiki/High_Bandwidth_Memory">High Bandwidth Memory - Wikipedia</a></li>
<li><a href="https://newsletter.semianalysis.com/p/scaling-the-memory-wall-the-rise-and-roadmap-of-hbm">Scaling the Memory Wall: The Rise and Roadmap of HBM</a></li>

</ul>
</details>

**Tags**: `#AI`, `#NVIDIA`, `#HBM`, `#AI infrastructure`, `#partnership`

---

<a id="item-9"></a>
## [China Issues New Offshore Trust Tax Rules](https://liaoning.chinatax.gov.cn/art/2026/7/24/art_5869_7823.html) ⭐️ 8.0/10

On July 24, 2026, China's Ministry of Finance and State Taxation Administration issued Announcement No. 21, requiring resident individuals to declare and pay tax annually on assets contributed to offshore trusts and all trust income, regardless of distribution. This rule closes previous tax avoidance paths where offshore trust income was not taxed unless distributed, significantly impacting high-net-worth individuals in China and enhancing tax compliance for offshore structures. All gains are taxed at a flat 20% rate on the appreciated value (market value minus original value and costs). Retroactive rules apply to contributions made from 2023 to 2025 and pre-2026 income, requiring reporting within 90 days without late penalties.

telegram · zaihuapd · Jul 25, 00:31

**Background**: Offshore trusts are trusts established in a foreign jurisdiction, often used for asset protection and tax planning. The new rule adopts a pass-through taxation approach, disregarding the trust entity and taxing the resident individual directly on all gains, eliminating the deferral advantage previously available.

<details><summary>References</summary>
<ul>
<li><a href="https://baike.baidu.com/item/离岸信托/2652314">离岸信托_百度百科</a></li>
<li><a href="https://zh.wikipedia.org/zh-cn/境外信託">境外信托 - 维基百科，自由的百科全书</a></li>
<li><a href="https://www.zhihu.com/question/374224709">税收穿透是什么意思？有什么实际应用吗？ - 知乎</a></li>

</ul>
</details>

**Tags**: `#tax regulation`, `#offshore trust`, `#China`, `#individual income tax`, `#compliance`

---

<a id="item-10"></a>
## [Samsung and Broadcom Sign $200B Semiconductor Deal](https://36kr.com/newsflashes/3910562246645128?f=rss) ⭐️ 7.0/10

Samsung Electronics and Broadcom have reportedly signed a $200 billion semiconductor supply cooperation agreement, as reported by Yicai (First Financial). This partnership underscores the growing importance of semiconductor supply chain stability and could significantly impact global chip production and pricing. The agreement is valued at $200 billion, making it one of the largest in the semiconductor industry; however, specific terms and products covered have not been disclosed.

rss · 36kr · Jul 25, 06:15

**Background**: Samsung Electronics is the world's largest memory chip manufacturer and a leading semiconductor foundry. Broadcom is a major supplier of networking and broadband chips. This long-term supply deal is expected to secure critical components for Broadcom and strengthen Samsung's customer base.

**Tags**: `#Semiconductor`, `#Business`, `#Samsung`, `#Broadcom`, `#Supply Chain`

---

<a id="item-11"></a>
## [Moody's Warns AI Investment Boom Strains Tech Firms' Finances](https://36kr.com/newsflashes/3910433082545536?f=rss) ⭐️ 7.0/10

Moody's issued a research report warning that the AI investment boom is eroding free cash flow and increasing balance sheet risks for six major tech companies, including Microsoft, Amazon, Alphabet, Meta, Oracle, and CoreWeave. This warning from a major rating agency signals a significant shift from 'asset-light' to 'asset-heavy' business models in tech, which could affect investor confidence and the industry's long-term financial stability. The six companies are transitioning from relying on software and cloud services to building large-scale data center infrastructure, requiring massive capital expenditures. Moody's noted that future investors will closely scrutinize whether these companies can generate sufficient returns from their AI investments.

rss · 36kr · Jul 25, 03:00

**Background**: Moody's Ratings is a credit rating agency that assesses the creditworthiness of companies. Free cash flow measures the cash a company generates after accounting for capital expenditures, and it is a key indicator of financial health. The shift to 'asset-heavy' models means companies must invest heavily in physical assets like data centers, which can strain cash flow.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/CoreWeave">CoreWeave</a></li>

</ul>
</details>

**Tags**: `#AI investment`, `#financial risk`, `#tech industry`, `#Moody's`, `#free cash flow`

---

<a id="item-12"></a>
## [Qualcomm warns of price hike across all products from Sept 1](https://tw.news.yahoo.com/%E7%8D%A8%E5%AE%B6-%E9%AB%98%E9%80%9A%E6%BC%B2%E5%83%B9%E4%BF%A1%E6%9B%9D%E5%85%89-%E5%85%A8%E7%B7%9A%E7%94%A2%E5%93%819-1%E8%B5%B7%E8%AA%BF%E6%BC%B2-%E7%9B%B4%E8%A8%80-142730846.html) ⭐️ 7.0/10

Qualcomm issued a price adjustment letter to customers on July 24, 2026, announcing a price increase for all products shipped on or after September 1, 2026, citing rising manufacturing costs and AI-driven capacity constraints. This broad price hike affects Qualcomm's chips used in smartphones, PCs, IoT, and automotive sectors, potentially raising consumer electronics prices and squeezing margins for downstream manufacturers. The letter did not specify a uniform increase percentage or list affected models; instead, account managers will contact customers individually with revised quotes, and some existing orders scheduled for shipment after September 1 may also face re-pricing.

telegram · zaihuapd · Jul 25, 03:01

**Background**: Qualcomm is a leading fabless semiconductor company supplying chips for mobile devices, automotive, and wireless infrastructure. The company cited rising costs in wafer fabrication, packaging, testing, advanced packaging, and substrate materials, compounded by surging AI and data center demand that strains the supply chain.

<details><summary>References</summary>
<ul>
<li><a href="https://zh.wikipedia.org/wiki/先进封装">先进封装 - 维基百科，自由的百科全书</a></li>
<li><a href="https://www.baogaobox.com/insights/260131000025282.html">2026年先进封装行业深度分析：全球先进封装占封装市场55%，2024-2030...</a></li>
<li><a href="https://www.jiuyangongshe.com/a/3y1m5jk1ayv">半 导 体 材 料 核心AI梳理</a></li>

</ul>
</details>

**Tags**: `#芯片涨价`, `#高通`, `#供应链`, `#AI需求`, `#半导体`

---

<a id="item-13"></a>
## [Apple Lobbies Trump to Use Chinese Storage Chips, Opposed by Micron](https://www.wsj.com/tech/trump-apple-micron-china-chips-784bbd3d) ⭐️ 7.0/10

Apple is lobbying the Trump administration to allow the use of Chinese-made storage chips from ChangXin Memory Technologies (CXMT) and Yangtze Memory Technologies (YMTC) in products sold outside the U.S., but Micron is actively opposing this move. This highlights the complex intersection of corporate interests and geopolitics in the semiconductor supply chain, potentially affecting Apple's cost structure and the competitive landscape for memory chips. Apple CEO Tim Cook and other executives have pitched the plan to President Trump and other officials in recent weeks, aiming to source DRAM from CXMT and NAND flash from YMTC for non-U.S. markets.

telegram · zaihuapd · Jul 25, 04:02

**Background**: ChangXin Memory Technologies (CXMT) is a Chinese DRAM manufacturer based in Hefei, while Yangtze Memory Technologies (YMTC) specializes in 3D NAND flash memory, known for its Xtacking technology. Both are part of China's push to develop domestic semiconductor capabilities, but they face restrictions from U.S. export controls.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ChangXin_Memory_Technologies">ChangXin Memory Technologies - Wikipedia</a></li>
<li><a href="https://zh.wikipedia.org/wiki/长鑫存储">长鑫存储 - 维基百科，自由的百科全书</a></li>

</ul>
</details>

**Tags**: `#Apple`, `#Micron`, `#semiconductor`, `#geopolitics`, `#supply chain`

---

<a id="item-14"></a>
## [Job security drives Chinese college admissions shift](https://www.caixin.com/2026-07-17/102464976.html) ⭐️ 7.0/10

In 2026 Chinese college admissions, fields with guaranteed job security such as military/police academies and government-funded teacher training saw soaring cutoff scores, while general five-year clinical medicine programs declined due to stricter employment requirements. This trend reflects growing risk aversion among families and students, reshaping talent supply and potentially affecting long-term workforce distribution in critical sectors like healthcare and education. Public Security University and local police schools saw entry requirements rise significantly; government-funded teacher training now offers a master's degree pathway (本研衔接). Meanwhile, clinical medicine long-cycle programs and directional veterinary medicine gained popularity.

telegram · zaihuapd · Jul 25, 04:49

**Background**: China's college admissions are highly competitive, and students often choose majors based on employment prospects. Recent policies include a transition to master-level training for government-funded teacher students (本研衔接) to improve quality, while healthcare reforms such as DRG/DIP payment and centralized drug procurement have reduced physician income expectations.

<details><summary>References</summary>
<ul>
<li><a href="https://yz.chsi.com.cn/kyzx/jybzc/202406/20240617/2293296999.html">yz.chsi.com.cn/kyzx/jybzc/202406/20240617/2293296999.html</a></li>
<li><a href="https://www.163.com/dy/article/JSPMISF70514CG7L.html">163.com/dy/article/JSPMISF70514CG7L.html</a></li>

</ul>
</details>

**Tags**: `#education`, `#employment`, `#China`, `#college admissions`, `#job security`

---

<a id="item-15"></a>
## [Ctrip Announces 19 Rectification Measures After Antitrust Penalty](https://mp.weixin.qq.com/s/6pfOO4iorcdUFb2zLNhFSw) ⭐️ 7.0/10

On July 25, 2026, Ctrip announced 19 rectification measures including ending exclusive partnerships and removing 'lowest price' requirements, following a penalty from China's State Administration for Market Regulation. This marks a significant antitrust enforcement action in China's platform economy, forcing a major online travel agency to reform business practices that restricted competition. Key measures include abolishing the 'first-level entrusted distribution (special brand)' exclusive cooperation model, eliminating promotional categories like 'Smart Select Special Offer', and ending mandatory 'lowest price across the web' conditions.

telegram · zaihuapd · Jul 25, 11:56

**Background**: Ctrip is a leading online travel platform in China. The State Administration for Market Regulation found it abused its market dominance to force exclusive cooperation and impose unfair conditions.

<details><summary>References</summary>
<ul>
<li><a href="https://www.163.com/dy/article/L2MNPNAN0550LJ66.html">刚刚 | 携程公布十九项整改措施！| 分 销 |经营|反垄断_网易订阅</a></li>
<li><a href="https://k.sina.com.cn/article_7879995939_1d5af322301901fdie.html?from=news">刚刚， 携 程 公布19... | 新浪网</a></li>
<li><a href="https://news.ifeng.com/c/8v35qLWztEm">停止、下线、取消、退还……被重罚后携程宣布整改_凤凰网</a></li>

</ul>
</details>

**Tags**: `#antitrust`, `#regulatory`, `#China`, `#travel`, `#platform economy`

---

<a id="item-16"></a>
## [AMD Confirms Zen 7 EPYC 'Florence' for 2028, Zen 8 'Ravenna' for 2030](https://www.techspot.com/news/113233-amd-confirms-zen-7-epyc-florence-2028-previews.html) ⭐️ 7.0/10

AMD has officially confirmed that its seventh-generation EPYC server processor, codenamed 'Florence' based on the Zen 7 architecture, will launch in 2028, followed by the eighth-generation EPYC 'Ravenna' based on Zen 8 in 2030. This extended roadmap provides a clear view of AMD's long-term server strategy, allowing data centers and cloud providers to plan infrastructure investments years in advance and intensifying the competitive landscape against Intel's future Xeon platforms. Florence will feature both standard Zen 7 cores and high-density Zen 7c cores, support new MRDIMM and LPDDR memory, and include AI compute extensions. It will be compatible with the new SP7 and SP8 platforms, targeting next-generation 'Ferrara' AI rack systems.

telegram · zaihuapd · Jul 25, 14:05

**Background**: AMD's EPYC processors are server CPUs designed for data centers, competing with Intel's Xeon lineup. Zen architectures are AMD's core microarchitectures; 'c' variants (like Zen 7c) are optimized for high core counts at lower power. MRDIMM (Multiplexed Rank DIMM) is a memory technology that increases bandwidth by interleaving data across multiple ranks. The SP7 and SP8 platforms are upcoming socket designs for EPYC CPUs, with SP7 for high-end servers and SP8 for entry-level.

<details><summary>References</summary>
<ul>
<li><a href="https://lenovopress.lenovo.com/lp2028-introduction-to-mrdimm-memory-technology">Introduction to MRDIMM Memory Technology > Lenovo Press</a></li>
<li><a href="https://wccftech.com/amd-sp7-sp8-platforms-epyc-venice-verano-cpus-12800-mtps-16-channel-memory-128-pcie-6-0-lanes/">AMD SP7 & SP8 Platforms For Next-Gen EPYC ... - Wccftech</a></li>

</ul>
</details>

**Tags**: `#AMD`, `#Zen`, `#server processors`, `#EPYC`, `#roadmap`

---

<a id="item-17"></a>
## [Microsoft Blocks Pirated Windows Activations with TPM Chips](https://www.techspot.com/news/113232-microsoft-using-tpm-chips-crack-down-pirated-windows.html) ⭐️ 7.0/10

Microsoft is adding TPM-based hardware verification to its Key Management Service (KMS) to block pirated Windows activations. The new 'TPM attestation' mechanism will become mandatory starting from the next version of Windows Server, with preparatory prompts rolling out in Windows Server 2025 from August 2026. This move significantly strengthens Microsoft's anti-piracy measures by tying activation to hardware trust, potentially rendering many existing KMS-based pirated activation tools ineffective. System administrators and enterprise licensing managers must prepare for the change to avoid activation disruptions. The TPM attestation requires the KMS server's hardware identity to be verified and unaltered by Microsoft before processing bulk activation requests. Microsoft previously blocked the KMS38 offline activation loophole in 2025, and the new TPM measure may counter the Massgrave group's Online KMS method, though their newer TSforge tool claims to bypass the entire DRM activation architecture.

telegram · zaihuapd · Jul 25, 15:55

**Background**: KMS (Key Management Service) is a Microsoft technology for volume licensing that allows organizations to activate Windows and Office products using an internal server. Pirated activation tools often exploit KMS by setting up fake KMS servers that respond to activation requests. TPM (Trusted Platform Module) is a hardware security chip that provides secure cryptographic operations and can attest to the system's integrity. By requiring TPM attestation, Microsoft aims to ensure only genuine KMS servers can authorize activations.

<details><summary>References</summary>
<ul>
<li><a href="https://learn.microsoft.com/en-us/windows-server/get-started/kms-client-activation-keys">Key Management Services (KMS) client activation and product ...</a></li>
<li><a href="https://massgrave.dev/tsforge">TSforge Activation | MAS - Microsoft Activation Scripts</a></li>
<li><a href="https://www.wincert.net/cast/microsoft-shuts-down-the-kms38-offline-activation-workaround/">Microsoft shuts down the KMS38 offline activation workaround</a></li>

</ul>
</details>

**Tags**: `#Windows`, `#Security`, `#TPM`, `#Piracy`, `#KMS`

---