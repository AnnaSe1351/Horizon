---
layout: default
title: "Horizon Summary: 2026-07-17 (EN)"
date: 2026-07-17
lang: en
---

> From 83 items, 20 important content pieces were selected

---

1. [First atmosphere detected on rocky exoplanet in habitable zone](#item-1) ⭐️ 9.0/10
2. [Firefox Runs Inside Chrome via WebAssembly Compilation](#item-2) ⭐️ 9.0/10
3. [AWS Billing Glitch Shows $1.7 Billion for $5 User](#item-3) ⭐️ 8.0/10
4. [Kimi K3 and Pelican Benchmark Reveal Tokenization Flaws](#item-4) ⭐️ 8.0/10
5. [Open source AI models surge past proprietary in token usage](#item-5) ⭐️ 8.0/10
6. [China Unicom & Huawei Launch World's Largest 5G-A Uplink Network](#item-6) ⭐️ 8.0/10
7. [Ex-NIO and Huawei AI Leaders Raise Millions for Embodied World Model Startup](#item-7) ⭐️ 8.0/10
8. [Hunan Yuneng Invests 24B Yuan in Battery Materials Project](#item-8) ⭐️ 8.0/10
9. [Moonshot AI Releases Kimi K3: 2.8T Open-Source Model Tops Frontend Code Arena](#item-9) ⭐️ 8.0/10
10. [Truth Social to sell fast access to Trump's posts to Wall Street](#item-10) ⭐️ 8.0/10
11. [Huawei Unveils Ascend 950 SuperNode, Claims 6.7x NVIDIA Performance](#item-11) ⭐️ 8.0/10
12. [US Lawmakers Propose Banning Chinese Memory Chips in Allied Supply Chains](#item-12) ⭐️ 8.0/10
13. [OpenAI CFO Proposes 'Useful Intelligence per Dollar' as AI ROI Metric](#item-13) ⭐️ 8.0/10
14. [Three Non-Solution Responses to Problems](#item-14) ⭐️ 7.0/10
15. [Choosing a Lisp Dialect: Guide and Community Insights](#item-15) ⭐️ 7.0/10
16. [EEG Reveals Brain Encodes Two Speech Streams Simultaneously](#item-16) ⭐️ 7.0/10
17. [MoSense Raises Angel Funding for Full-Body Tactile Skin](#item-17) ⭐️ 7.0/10
18. [Prism Bug Leaks User Paper in Compilation Error](#item-18) ⭐️ 7.0/10
19. [EU AI Act OpenRAG: Legal Corpus with BGE-M3 Embeddings](#item-19) ⭐️ 7.0/10
20. [Blogger sentenced 20 months for faking Xiaomi SU7 crash test](#item-20) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [First atmosphere detected on rocky exoplanet in habitable zone](https://www.bbc.com/news/articles/cy4kdd1e0ejo) ⭐️ 9.0/10

Astronomers using the James Webb Space Telescope (JWST) have detected an atmosphere on LHS 1140b, a rocky exoplanet about 48 light-years away in the habitable zone of a red dwarf star. This marks the first confirmed atmosphere on a potentially Earth-like world in a habitable zone. This discovery is a milestone in exoplanet science, as it demonstrates that rocky planets in the habitable zone of red dwarfs can retain atmospheres despite intense stellar radiation. It opens new avenues for studying planetary habitability and searching for biosignatures. The detection was made using transit spectroscopy during JWST observations of LHS 1140b passing behind its star, which ruled out a mini-Neptune interpretation and confirmed a nitrogen-rich atmosphere with helium. The planet's close orbit around a red dwarf raises questions about atmospheric retention, but JWST's data are robust.

hackernews · neversaydie · Jul 17, 14:06 · [Discussion](https://news.ycombinator.com/item?id=48947560)

**Background**: Transit spectroscopy is a technique where starlight passing through a planet's atmosphere is analyzed to reveal its chemical composition. The habitable zone of a red dwarf star is much closer to the star than in Sun-like systems, and red dwarfs are known for their flare activity, which could strip atmospheres. This detection shows that some rocky worlds in such zones can indeed hold onto their atmospheres.

<details><summary>References</summary>
<ul>
<li><a href="https://hycean.group.cam.ac.uk/observations/transit-spectroscopy/">Transit Spectroscopy - Hycean Worlds - University of Cambridge</a></li>
<li><a href="https://en.wikipedia.org/wiki/Habitability_of_red_dwarf_systems">Habitability of red dwarf systems - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The top comment initially expressed skepticism about atmospheric retention on a rocky planet around a red dwarf, but later updated that JWST ruled out a mini-Neptune, reinforcing the finding. Other comments discussed building solar lens telescopes for future observations and speculated on propulsion systems to reach LHS 1140b within centuries.

**Tags**: `#exoplanets`, `#atmosphere`, `#JWST`, `#astronomy`

---

<a id="item-2"></a>
## [Firefox Runs Inside Chrome via WebAssembly Compilation](https://simonwillison.net/2026/Jul/16/firefox-in-webassembly/#atom-everything) ⭐️ 9.0/10

Puter has successfully compiled the entire Firefox browser into WebAssembly, allowing it to run inside another browser like Chrome. The project used AI-assisted programming with Claude and Fable models, costing an estimated $25,000 in tokens. This demonstrates that complex, performance-critical applications like full browsers can be ported to WebAssembly, expanding the platform's capabilities beyond simple games and utilities. It also showcases the potential of AI-assisted development to tackle large-scale engineering challenges. Firefox's Gecko engine was chosen for its strong single-process support. All network traffic is proxied through Puter's servers using the Wisp protocol over WebSockets, because browser-based WebAssembly cannot open raw network connections.

rss · Simon Willison · Jul 16, 23:34

**Background**: WebAssembly (WASM) is a low-level binary instruction format that runs in modern web browsers at near-native speed. It allows languages like C++ to be compiled to run in the browser, enabling complex applications previously limited to native environments. Compiling a full browser into WASM is a monumental task due to the sheer size and complexity of browser engines. Puter's project demonstrates that with sufficient engineering effort and AI assistance, even such large-scale ports are feasible.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/MercuryWorkshop/wisp-protocol">GitHub - MercuryWorkshop/wisp-protocol: Wisp is a low ...</a></li>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>

</ul>
</details>

**Tags**: `#WebAssembly`, `#Firefox`, `#browser`, `#WASM`, `#emulation`

---

<a id="item-3"></a>
## [AWS Billing Glitch Shows $1.7 Billion for $5 User](https://news.ycombinator.com/item?id=48945241) ⭐️ 8.0/10

An AWS billing system unit error caused some customers to see estimated bills as high as $1.7 billion, while typical usage was under $5. This incident underscores critical flaws in AWS billing infrastructure, eroding trust in cloud cost management and affecting millions of users who rely on accurate billing alerts. The error stemmed from a unit mismatch where a service emitted metering values in bytes instead of gigabytes, causing a 10^9 multiplier error. AWS acknowledged the issue and fixed it within hours.

hackernews · nprateem · Jul 17, 09:42

**Background**: AWS billing uses a complex system where services emit metering data (e.g., bytes transferred) and pricing plans convert these into costs. A unit conversion error can cause extreme bill inflation. This is not the first such error; similar issues have occurred historically.

**Discussion**: Community comments included firsthand accounts from an ex-AWS engineer explaining the unit error, and many users reporting emotional distress from alarm emails showing huge bills. Some criticized AWS's billing reliability and transparency.

**Tags**: `#AWS`, `#billing`, `#cloud computing`, `#infrastructure`, `#reliability`

---

<a id="item-4"></a>
## [Kimi K3 and Pelican Benchmark Reveal Tokenization Flaws](https://simonwillison.net/2026/Jul/16/kimi-k3/) ⭐️ 8.0/10

Moonshot AI released Kimi K3, a 2.8-trillion-parameter open-source model, while Simon Willison's pelican benchmark exposed tokenization quirks and a possible hidden system prompt in Kimi K3, sparking community debate on LLM evaluation reliability. This discussion highlights critical issues in LLM benchmarking, such as tokenization inconsistency and hidden prompts, which can skew performance comparisons and undermine the validity of popular benchmarks. The pelican benchmark is an informal test where models generate an SVG of a pelican riding a bicycle; Kimi K3's tokenizer counted 95 tokens for this prompt, while others counted 10, suggesting an 85-token hidden system prompt. The model also refused to leak its system prompt.

hackernews · droidjj · Jul 17, 14:21 · [Discussion](https://news.ycombinator.com/item?id=48947717)

**Background**: The pelican benchmark, created by developer Simon Willison in late 2024, is a simple test of LLMs' ability to generate correct SVG code. Kimi K3, released in July 2026 by Moonshot AI, has 2.8 trillion parameters and uses hybrid attention mechanisms. Hidden system prompts are instructions injected by the model provider that are not visible to users but influence model behavior.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Kimi_K3">Kimi K3</a></li>
<li><a href="https://platform.kimi.ai/docs/guide/kimi-k3-quickstart">Kimi K3 - Kimi API Platform</a></li>
<li><a href="https://grokipedia.com/page/Pelican_on_a_bicycle_AI_benchmark">Pelican on a bicycle (AI benchmark)</a></li>

</ul>
</details>

**Discussion**: Comments from btown proposed a new 'SWE-bench-adversarial-pelican-gen' benchmark to test agentic tool calling. OsrsNeedsf2P expressed skepticism that pelicans on bikes are not in the training set, noting that similar content appears on blogs and GitHub. devttyeu detailed the token count discrepancy, suggesting an 85-token hidden system prompt for reasoning effort.

**Tags**: `#LLM`, `#benchmarking`, `#tokenization`, `#Kimi K3`, `#AI evaluation`

---

<a id="item-5"></a>
## [Open source AI models surge past proprietary in token usage](https://stateofopensource.ai/) ⭐️ 8.0/10

An analysis based on OpenRouter token data reveals that open source AI models now account for 63% of tokens processed, up from 40% four months ago, representing a nearly 5x growth in daily token volume. This rapid shift from closed to open models could disrupt the business models of companies like OpenAI and Anthropic, which rely on proprietary models, and may accelerate the adoption of smaller, device-local AI. The data comes from OpenRouter, a platform that provides a unified API for accessing over 400 LLMs and processes millions of users; skeptics note that the analysis was clearly AI-generated, which may undermine its credibility.

hackernews · rellem · Jul 17, 14:31 · [Discussion](https://news.ycombinator.com/item?id=48947825)

**Background**: OpenRouter is a marketplace that aggregates many large language models (LLMs) via a single API. Tokens are the basic units that LLMs use to process text; token usage volume is a proxy for model adoption and revenue. The analysis uses OpenRouter's public token data to track market share between open and closed models.

<details><summary>References</summary>
<ul>
<li><a href="https://openrouter.ai/">OpenRouter</a></li>
<li><a href="https://openrouter.ai/about">About - The Unified Interface For LLMs | OpenRouter</a></li>
<li><a href="https://www.codecademy.com/article/what-is-openrouter">What is OpenRouter? A Guide with Practical Examples</a></li>

</ul>
</details>

**Discussion**: Community comments are mixed: some celebrate the data showing open models' growth, while others criticize the presentation as clearly AI-written and hard to parse. One user built a real-time dashboard for the token data. There is speculation that open models will render proprietary model companies obsolete.

**Tags**: `#open source`, `#AI`, `#LLMs`, `#market analysis`, `#generative AI`

---

<a id="item-6"></a>
## [China Unicom & Huawei Launch World's Largest 5G-A Uplink Network](https://36kr.com/p/3899398088509319?f=rss) ⭐️ 8.0/10

China Unicom Beijing and Huawei have deployed the world's largest commercial 5G-Advanced (5G-A) uplink network across Beijing, with over 10,000 base stations providing 100MHz uplink continuous coverage. Field tests show an average uplink speed of 397 Mbps, a peak of 1 Gbps, and only 0.1% of edge points below 20 Mbps. This launch marks a major milestone in 5G-A commercialization, demonstrating that high uplink capacity can support emerging Mobile AI applications like AI glasses, smartphones, and cameras. It signals a shift from download-centric networks to uplink-centric connectivity essential for real-time AI processing in the cloud. The network uses a 3.5GHz + 2.1GHz SUL (Supplementary Uplink) solution from Huawei to boost uplink coverage and capacity. Over a 34km test route, the uplink 100MHz activation ratio reached 83%, and 72% of test points achieved uplink speeds above 300 Mbps.

rss · 36kr · Jul 17, 07:13

**Background**: 5G-Advanced (5G-A) is an evolutionary step between 5G and 6G, defined in 3GPP Releases 18 and 19. It introduces enhanced uplink, AI integration, and spectrum flexibility to support new use cases like immersive video and industrial IoT. The 'big uplink' capability is particularly important for applications that generate large amounts of data at the edge and require real-time cloud processing.

<details><summary>References</summary>
<ul>
<li><a href="https://www.edntaiwan.com/20250930nt01-5g-advanced-to-6g-whats-next-for-wireless-networks/">5 G - Advanced 為6G鋪路：無線網路的下一步？ - 電子技術設計</a></li>
<li><a href="https://vocus.cc/article/694c6b38fd8978000134e571">5 G 演進與 5 G - Advanced / 邁向 6G 是 甚麼</a></li>

</ul>
</details>

**Tags**: `#5G-Advanced`, `#Network`, `#China Unicom`, `#Huawei`, `#Uplink`

---

<a id="item-7"></a>
## [Ex-NIO and Huawei AI Leaders Raise Millions for Embodied World Model Startup](https://36kr.com/p/3899081603483525?f=rss) ⭐️ 8.0/10

Rikaikaiwu (Beijing Coronal Robotics Co., Ltd.), a startup founded by former autonomous driving leaders from NIO and Huawei, has raised several hundred million RMB in seed funding for its embodied world model LaMPA. The company aims to build a foundational model that understands physical worlds, predicts changes, and drives robots across diverse scenarios. This funding highlights the growing importance of world models for embodied AI, as robots need to understand physical dynamics beyond imitation learning. The strong founding team and focus on industrial deployment could accelerate the adoption of generalist robots in manufacturing. LaMPA introduces a triple representation system (environment, ego, experience) based on Yann LeCun's JEPA theory, using a block diffusion architecture for efficient scaling. The company also developed a world reward model to automate reinforcement learning feedback, reducing deployment cycles in new industrial scenarios.

rss · 36kr · Jul 17, 01:52

**Background**: World models are AI systems that simulate physical dynamics, causality, and interactions, enabling robots to predict outcomes and plan actions. Yann LeCun's Joint Embedding Predictive Architecture (JEPA) proposes learning abstract representations in latent space rather than pixel-level generation, a key inspiration for LaMPA. The startup targets server manufacturing as its first high-precision assembly scenario, partnering with Yuantu Future.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/World_model_(artificial_intelligence)">World model (artificial intelligence) - Wikipedia</a></li>
<li><a href="https://ai.meta.com/blog/yann-lecun-ai-model-i-jepa/">I-JEPA: The first AI model based on Yann LeCun’s vision for more human-like AI</a></li>

</ul>
</details>

**Tags**: `#embodied AI`, `#world model`, `#autonomous driving`, `#robotics`, `#startup funding`

---

<a id="item-8"></a>
## [Hunan Yuneng Invests 24B Yuan in Battery Materials Project](https://36kr.com/newsflashes/3899699021465223?f=rss) ⭐️ 8.0/10

Hunan Yuneng announced a planned investment of about 24 billion yuan to build an integrated mining-processing-recycling new energy battery materials industrial project in Weng'an County, Guizhou Province. The project includes 800,000 tons of lithium iron phosphate (LFP), 1 million tons of iron phosphate, and upstream raw material processing and lithium battery recycling facilities. This massive investment signals a major consolidation in the battery supply chain, strengthening Hunan Yuneng's position as a leading LFP cathode material supplier. It also highlights the industry's shift toward vertically integrated production models to secure raw materials and reduce costs amid growing demand for energy storage and electric vehicles. The project has a planned construction period of 5 years, with an initial investment of 50-80 billion yuan within the first 18 months after formal construction starts. The subsequent investment pace will be adjusted based on market demand.

rss · 36kr · Jul 17, 12:18

**Background**: Lithium iron phosphate (LiFePO4, LFP) is a cathode material for lithium-ion batteries known for its high safety, long cycle life, and low cost, widely used in electric vehicles and energy storage systems. The term 'mining-processing一体化' (kuang hua yi ti) refers to an integrated industrial chain covering mining of raw materials (e.g., phosphorus, iron, lithium), processing into battery materials, and recycling of spent batteries.

<details><summary>References</summary>
<ul>
<li><a href="https://www.yicai.com/news/103280574.html">湖南裕能：拟建设 矿 化 一 体 新能源电池材料循环产业 项 目 总投资约240...</a></li>
<li><a href="https://m.gelonghui.com/p/5629770">公告精选︱湖南裕能：拟240...</a></li>
<li><a href="https://baike.baidu.com/item/磷酸铁锂/10485541">磷酸铁锂_百度百科</a></li>

</ul>
</details>

**Tags**: `#battery`, `#supply chain`, `#energy storage`, `#investment`, `#manufacturing`

---

<a id="item-9"></a>
## [Moonshot AI Releases Kimi K3: 2.8T Open-Source Model Tops Frontend Code Arena](https://www.kimi.com/blog/kimi-k3) ⭐️ 8.0/10

Moonshot AI released Kimi K3, the world's first open-source model with 2.8 trillion parameters, built on Kimi Delta Attention and Attention Residuals. It achieved the top score of 1679 in the Frontend Code Arena, surpassing Claude Fable 5. Kimi K3 demonstrates that open-source models can compete with the best closed models in specific domains like frontend coding, potentially accelerating AI adoption in software development. However, its overall performance still trails top closed models, and full weights will not be open until 2026, limiting immediate community impact. Kimi K3 is a sparse Mixture-of-Experts (MoE) model with 2.8T total parameters, using a novel hybrid linear attention mechanism (Kimi Delta Attention) and Attention Residuals for better information flow. It features a 1M-token context window, native vision understanding, and is available on Kimi.com and API with pricing at $0.30 per million input tokens (cache hit), $3.00 (cache miss), and $15.00 for output tokens.

telegram · zaihuapd · Jul 17, 00:02

**Background**: Large language models with trillions of parameters require massive computational resources and typically use Transformer architectures with standard attention, which has O(n²) complexity. Kimi Delta Attention (KDA) is a linear attention variant that refines Gated DeltaNet with a diagonalized gate for more efficient finite-state RNN memory, reducing complexity to O(n). Attention Residuals (AttnRes) replace standard residual connections with learned attention over previous layer outputs, enabling adaptive information aggregation across layers. The Frontend Code Arena is a real-world coding benchmark using Elo-style voting where developers compare model outputs.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2510.26692">[2510.26692] Kimi Linear: An Expressive, Efficient Attention ... GitHub - MoonshotAI/Kimi-Linear Kimi K3 - Kimi API Platform Kimi Linear: An Expressive, Efficient Attention Architecture Moonshot AI Releases Kimi K3: A 2.8 Trillion Parameter Open ... GitHub - hwilner/kimi-delta-attention: Educational ... Kimi K3 (Moonshot AI) - Cloudflare Docs</a></li>
<li><a href="https://github.com/MoonshotAI/Kimi-Linear">GitHub - MoonshotAI/Kimi-Linear</a></li>
<li><a href="https://platform.kimi.ai/docs/guide/kimi-k3-quickstart">Kimi K3 - Kimi API Platform</a></li>

</ul>
</details>

**Tags**: `#Kimi K3`, `#LLM`, `#open-source`, `#large language model`, `#AI`

---

<a id="item-10"></a>
## [Truth Social to sell fast access to Trump's posts to Wall Street](https://www.cnn.com/2026/07/16/business/truth-social-data-wall-street) ⭐️ 8.0/10

Trump Media & Technology Group announced on July 16, 2026, that it will launch Truth API, a data feed providing millisecond-speed access to posts from the top 10 accounts on Truth Social, starting August 1, 2026, aimed at institutional investors for algorithmic trading. This move monetizes Trump's political influence by selling privileged data access, potentially enabling market manipulation and raising ethical concerns about the blurring lines between the presidency and private business. Truth API will specifically target high-frequency algorithmic traders, offering them a competitive edge by delivering Trump's posts faster than public access. TMTG has not disclosed pricing, and CNN previously reported that Trump used Truth Social to promote stocks he had just purchased.

telegram · zaihuapd · Jul 17, 01:02

**Background**: An API (Application Programming Interface) allows software systems to exchange data automatically. In financial markets, algorithmic trading uses computer programs to execute trades based on predefined criteria, and social media sentiment analysis has become a popular data source. Truth Social has become President Trump's primary channel for policy announcements, and his posts have previously caused significant market volatility.

<details><summary>References</summary>
<ul>
<li><a href="https://www.globenewswire.com/news-release/2026/07/16/3328489/0/en/trump-media-and-technology-group-launches-truth-api-a-new-licensed-data-service-for-financial-services-partners-that-provides-the-fastest-access-to-truth-social-s-most-influential-.html">Trump Media and Technology Group Launches Truth API, a New Licensed Data Service for Financial Services Partners That Provides the Fastest Access to Truth Social’s Most Influential Accounts</a></li>
<li><a href="https://thehill.com/policy/technology/5972998-trump-media-technology-group-launch-truth-api/">Trump Media & Technology Group to launch Truth API to sell to Wall Street</a></li>

</ul>
</details>

**Tags**: `#social media`, `#API`, `#finance`, `#algorithmic trading`, `#regulation`

---

<a id="item-11"></a>
## [Huawei Unveils Ascend 950 SuperNode, Claims 6.7x NVIDIA Performance](https://www.ithome.com/0/978/019.htm) ⭐️ 8.0/10

At WAIC 2026, Huawei publicly demonstrated the Ascend 950 SuperNode (Atlas 950 SuperPoD) for the first time. According to a BOC International securities report, the system delivers 6.7x the total compute power of NVIDIA's NVL144 system, offering 1 EFLOPS FP8 and 2 EFLOPS FP4 across 1024 cards with 256 TB unified memory. This announcement challenges NVIDIA's dominance in AI hardware by offering a significant performance advantage on paper. If validated, the Ascend 950 could accelerate AI model training in China and reduce reliance on NVIDIA GPUs. The system uses Huawei's self-developed Lingqu (UnifiedBus) interconnect protocol and SuperNode architecture to achieve a 1024-card scale-up. Additionally, Huawei showcased the Atlas 850E air-cooled SuperNode, which can be deployed in standard air-cooled data centers without liquid cooling retrofitting.

telegram · zaihuapd · Jul 17, 10:27

**Background**: The Lingqu protocol is a five-layer unified interconnect stack developed by Huawei to replace PCIe, NVLink, and RDMA, supporting up to 8192 cards without traffic reduction. SuperNode architecture integrates dozens or hundreds of AI chips into a single high-speed interconnected unit to meet the demands of large model training. The performance claim comes from a Chinese securities report and has not been independently verified.

<details><summary>References</summary>
<ul>
<li><a href="https://locsic.com/zh/thinking/lingqu-unifiedbus-protocol-analysis/">灵衢协议深度分析：中国算力突围的互联赌注 — Locsic</a></li>
<li><a href="https://aijishu.com/a/1060000000520368">aijishu.com/a/1060000000520368</a></li>

</ul>
</details>

**Tags**: `#Huawei`, `#AI hardware`, `#Ascend`, `#SuperNode`, `#NVIDIA`

---

<a id="item-12"></a>
## [US Lawmakers Propose Banning Chinese Memory Chips in Allied Supply Chains](https://www.tomshardware.com/pc-components/dram/lawmakers-want-us-government-to-ban-memory-chips-from-china-even-in-allied-supply-chains-citing-unacceptable-risk-to-national-economic-and-supply-chain-security) ⭐️ 8.0/10

US House China Committee Chairman John Moolenaar and Representative George Whitesides sent a letter to Commerce Secretary Howard Lutnick, urging a ban on US companies purchasing Chinese memory chips, adding CXMT to the Entity List, and imposing additional restrictions on YMTC. This escalation in US-China semiconductor tensions could reshape global memory supply chains, impacting major US tech firms like Apple and deepening technological decoupling between the two countries. The lawmakers argued that Chinese memory makers have close ties to the Chinese military, making every purchase a potential funding source for the PLA's dual-use technologies. They also urged coordination with Japan, South Korea, and the EU to prevent Chinese manufacturers from embedding in allied supply chains amid potential shortages.

telegram · zaihuapd · Jul 17, 14:00

**Background**: ChangXin Memory Technologies (CXMT) is a leading Chinese DRAM manufacturer, while Yangtze Memory Technologies (YMTC) specializes in NAND flash memory. The Entity List is a US export control tool that restricts listed entities from accessing US technology without a license. The US has previously imposed sanctions on several Chinese semiconductor companies, and this proposal targets the memory chip segment, critical for AI infrastructure and consumer electronics.

<details><summary>References</summary>
<ul>
<li><a href="https://zh.wikipedia.org/wiki/长鑫存储">长鑫存储 - 维基百科，自由的百科全书</a></li>
<li><a href="https://zh.wikipedia.org/zh-hans/實體清單">实体清单 - 维基百科，自由的百科全书</a></li>

</ul>
</details>

**Tags**: `#semiconductors`, `#supply chain security`, `#US-China tech competition`, `#memory chips`, `#AI infrastructure`

---

<a id="item-13"></a>
## [OpenAI CFO Proposes 'Useful Intelligence per Dollar' as AI ROI Metric](https://openai.com/index/a-scorecard-for-the-ai-age) ⭐️ 8.0/10

OpenAI CFO Sarah Friar proposed a new metric called 'useful intelligence per dollar' to measure AI return on investment, focusing on task completion cost and reliability instead of token cost. This framework could shift how enterprises evaluate AI investments, moving beyond traditional adoption metrics to emphasize actual value delivered per dollar spent. The framework includes four dimensions: useful work completed, total cost per successful task, reliability of AI output, and whether more value is generated per dollar as usage scales. OpenAI also noted that a more powerful model, like GPT-5.6's Sol, can reduce output tokens by 54% on coding tasks compared to another leading model.

telegram · zaihuapd · Jul 17, 15:00

**Background**: Traditionally, enterprise AI ROI was measured by adoption metrics like user numbers or license renewals, but these don't capture the cost-effectiveness of completing actual tasks. Token cost alone is misleading because a more expensive model that gets it right first time can be cheaper overall per task. This new metric aims to provide a more holistic view of AI value.

**Tags**: `#AI ROI`, `#metric`, `#OpenAI`, `#enterprise AI`, `#cost efficiency`

---

<a id="item-14"></a>
## [Three Non-Solution Responses to Problems](https://improvesomething.today/responses-to-problems/) ⭐️ 7.0/10

The article identifies three common non-solution responses to problems: ignoring, preserving, and redefining them, presenting a framework for understanding counterproductive behaviors in individuals and organizations. Recognizing these patterns helps people and organizations avoid wasting resources and improve genuine problem-solving. The high community engagement (172 score, 101 comments) indicates broad relevance, especially in government and consulting contexts. The three responses are: (1) ignoring or downplaying the problem, (2) preserving the problem to maintain power or budgets, and (3) redefining the problem to shift focus away from the root cause. The article is from improvesomething.today and scored 7.0/10.

hackernews · surprisetalk · Jul 17, 14:00 · [Discussion](https://news.ycombinator.com/item?id=48947490)

**Background**: In problem-solving, people often avoid genuine solutions due to cognitive biases, organizational incentives, or fear of change. The article discusses ignoring (focusing on more pressing issues), preserving (maintaining the status quo for personal gain), and redefining (changing the framing to avoid solving). These patterns are common in bureaucracy and consulting, where incentives may not align with solving problems.

**Discussion**: Commenters provided real-world examples: government agencies preserving problems to justify budgets, experts maintaining problems to retain positions, and consultants recommending changes without implementation. Some argued ignoring is sometimes optimal, while others criticized the preservation of problems for political or financial gain. The discussion largely agreed with the article's framework and offered nuanced perspectives.

**Tags**: `#problem-solving`, `#psychology`, `#organizational behavior`, `#systems thinking`

---

<a id="item-15"></a>
## [Choosing a Lisp Dialect: Guide and Community Insights](https://scotto.me/blog/2026-07-17-which-lisp/) ⭐️ 7.0/10

A blog post provides a guide to choosing a Lisp dialect, and the accompanying community discussion explores trade-offs between Scheme, Common Lisp, and Clojure. This is valuable for Lisp enthusiasts and programmers seeking a functional language, as it surfaces real-world experiences and opinions on each dialect's strengths and weaknesses. The post contrasts Scheme's minimalism, Common Lisp's extensibility and power, and Clojure's modern features like immutable data structures and JVM integration.

hackernews · silcoon · Jul 17, 13:56 · [Discussion](https://news.ycombinator.com/item?id=48947455)

**Background**: Lisp is one of the oldest high-level programming languages, with major dialects including Scheme (known for simplicity), Common Lisp (comprehensive and multi-paradigm), and Clojure (functional, hosted on JVM/CLR/JavaScript). These dialects differ in syntax, standard library, and philosophy, leading to ongoing debates about which is 'best'.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Lisp_(programming_language)">Lisp (programming language) - Wikipedia</a></li>
<li><a href="https://stackoverflow.com/questions/11223403/what-are-the-differences-between-clojure-scheme-racket-and-common-lisp">What are the differences between Clojure, Scheme/Racket and ...</a></li>
<li><a href="https://clojure.org/reference/lisps">Clojure - Differences with other Lisps</a></li>

</ul>
</details>

**Discussion**: Comments reflect a mix of personal experience and wishful thinking: some praise Scheme for its elegance, others want a fusion of SBCL performance, Clojure syntax, and DrRacket friendliness. A few emphasize Common Lisp's extensibility, while one commenter argues Lisp is less special than perceived.

**Tags**: `#Lisp`, `#Scheme`, `#Common Lisp`, `#Programming Languages`, `#Clojure`

---

<a id="item-16"></a>
## [EEG Reveals Brain Encodes Two Speech Streams Simultaneously](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.3003876) ⭐️ 7.0/10

A new study published in PLOS Biology uses EEG to demonstrate that the human brain can simultaneously encode two distinct speech streams, providing neural evidence for multitasking in auditory processing. This finding challenges traditional views of limited attentional capacity and opens avenues for understanding how the brain manages competing auditory inputs, with implications for hearing aids, speech recognition, and cognitive neuroscience. The study used EEG to measure neural tracking of two simultaneous speech streams, finding that the brain encodes both streams even when attention is focused on one, suggesting parallel processing.

hackernews · giuliomagnifico · Jul 17, 05:51 · [Discussion](https://news.ycombinator.com/item?id=48943745)

**Background**: EEG (electroencephalography) records electrical activity of the brain via electrodes on the scalp. The brain's ability to follow speech rhythms can be measured by how well EEG signals synchronize with the speech envelope. Previous research focused on single-stream encoding, but this study shows dual-stream encoding is possible.

**Discussion**: Commenters shared personal anecdotes, with references to Richard Feynman's experiments on simultaneous counting and reading, and reports from pilots and partygoers who naturally process multiple speech streams. Some linked the finding to mindfulness and attention practices, suggesting a broader relevance to consciousness.

**Tags**: `#neuroscience`, `#EEG`, `#brain`, `#multitasking`, `#speech processing`

---

<a id="item-17"></a>
## [MoSense Raises Angel Funding for Full-Body Tactile Skin](https://36kr.com/p/3899128277452681?f=rss) ⭐️ 7.0/10

MoSense, a startup founded by HKUST PhDs, closed a multi-million yuan angel round led by Sequoia China, Hillhouse Venture, and Zhiyuan Robot to develop MoSkin, a full-body multimodal tactile skin using electromagnetic metamaterials for robot perception. Full-body tactile sensing is a critical bottleneck for humanoid robots moving from demos to real-world tasks like manufacturing and home service. MoSense's solution could bridge the Sim-to-Real gap by providing continuous force-field perception, enabling safer and more adaptive robot interactions. MoSkin covers the robot's hands, limbs, torso, and soles, integrating force, temperature, slip, vibration, and material sensing. The company is also developing a world-action-tactile prediction model based on a multimodal latent-space fusion gating mechanism to refine low-frequency decision-making with high-frequency tactile feedback.

rss · 36kr · Jul 17, 02:39

**Background**: Tactile sensing for robots has traditionally been limited to fingertips or grippers, leaving most of the body without touch feedback. This restricts complex physical interactions and contributes to the Sim-to-Real gap, where policies trained in simulation fail in the real world due to missing tactile data. Electromagnetic metamaterials allow MoSkin to convert the robot's rigid boundary into a continuous six-dimensional force field, enabling large-area, conformal deployment.

<details><summary>References</summary>
<ul>
<li><a href="https://www.sciencedirect.com/science/article/pii/S305091302500110X">Advances in magnetic materials and sensors for tactile ...</a></li>
<li><a href="https://www.sciencedirect.com/science/article/pii/S0264127524000017">Vision-based tactile intelligence with soft robotic metamaterial</a></li>
<li><a href="https://onlinelibrary.wiley.com/doi/full/10.1002/smll.202511475">Flexible Tactile Sensors: Materials, Mechanisms, Structures ...</a></li>

</ul>
</details>

**Tags**: `#robotics`, `#tactile sensing`, `#startup funding`, `#humanoid robots`, `#sensor technology`

---

<a id="item-18"></a>
## [Prism Bug Leaks User Paper in Compilation Error](https://www.reddit.com/r/MachineLearning/comments/1uz75qt/prism_accidentally_leaked_d/) ⭐️ 7.0/10

A bug in Prism's compilation process caused another user's academic paper to be returned to a different user, leading to a prompt takedown within 10 minutes of the first report. This incident raises serious privacy concerns for researchers using AI-powered LaTeX platforms, as sensitive unpublished work could be exposed to unauthorized parties. The bug was first reported on Prism's Discord and a Twitter post, triggering a rapid response where the website was taken down within 10 minutes. The exact scope of exposure and whether other users' data was affected remains unclear.

reddit · r/MachineLearning · /u/Few-Monitor5103 · Jul 17, 17:59

**Background**: Prism is a free, AI-first LaTeX editor and scientific workspace developed by OpenAI, integrating ChatGPT and Codex to assist with writing and collaboration. It allows researchers to compile LaTeX documents in the cloud. A compilation bug that returns another user's document indicates a potential misrouting of data or caching issue.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/prism/">Prism | A free, LaTeX Editor and AI -native workspace for... | OpenAI</a></li>
<li><a href="https://openai-dotcom-git-main-openai.vercel.app/index/introducing-prism/">Introducing Prism | OpenAI</a></li>

</ul>
</details>

**Tags**: `#security`, `#privacy`, `#machine learning`, `#data leak`

---

<a id="item-19"></a>
## [EU AI Act OpenRAG: Legal Corpus with BGE-M3 Embeddings](https://www.reddit.com/r/MachineLearning/comments/1uytlac/eu_ai_act_openrag_933_legally_structured_chunks/) ⭐️ 7.0/10

The EU AI Act OpenRAG corpus was released, containing 933 legally structured chunks and normalized 1024-dimensional BGE-M3 embeddings stored in a single SQLite file, achieving significant improvements in recall and QA accuracy over sliding window baselines. This resource provides a high-quality, specialized dataset for legal NLP and retrieval-augmented generation (RAG) systems, enabling more accurate retrieval and question answering on the EU AI Act, a landmark regulation. The corpus was evaluated using the AI Act Evaluation Benchmark: scenario article recall@20 reached 0.541 (structural) vs 0.449 (baseline), and QA article hit@10 reached 0.927 vs 0.898. The dataset includes exact EUR-Lex links, Article 113 application-date metadata, and deliberate NULLs for ambiguous cases.

reddit · r/MachineLearning · /u/Automatic-Forever-63 · Jul 17, 08:18

**Background**: Retrieval-Augmented Generation (RAG) combines large language models (LLMs) with external knowledge bases to improve output accuracy. BGE-M3 is a versatile embedding model supporting dense, sparse, and multi-vector retrieval. EUR-Lex is the official online database of European Union law. This corpus leverages legal structure (articles, recitals, definitions) for chunking, unlike typical sliding window methods.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/BAAI/bge-m3">BAAI/bge-m3 · Hugging Face</a></li>
<li><a href="https://en.wikipedia.org/wiki/Retrieval-augmented_generation">Retrieval-augmented generation - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/EUR-Lex">EUR-Lex</a></li>

</ul>
</details>

**Tags**: `#EU AI Act`, `#RAG`, `#legal NLP`, `#embeddings`, `#SQLite`

---

<a id="item-20"></a>
## [Blogger sentenced 20 months for faking Xiaomi SU7 crash test](https://weibo.com/1893892941/5321659255097490) ⭐️ 7.0/10

On July 17, 2025, a Beijing court sentenced auto blogger Gao to 1 year and 8 months in prison and fined him 100,000 yuan for fabricating a crash test of the Xiaomi SU7, damaging the company's reputation. This case marks a landmark enforcement of China's new online evaluation regulations, signaling stricter legal consequences for spreading false information about products, especially in the automotive industry. The blogger's video, which garnered over 3 million views, falsely claimed the SU7's low-voltage battery cable was broken in the crash and the eCall system failed, when in fact the cable was intentionally removed before the test and the battery was damaged by a forklift.

telegram · zaihuapd · Jul 17, 07:21

**Background**: The Xiaomi SU7 is an electric sedan that uses a 12V low-voltage battery for auxiliary systems and an eCall emergency call system that automatically contacts emergency services after a crash. China's new online evaluation regulations require honesty in product reviews and testing.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Xiaomi_SU7">Xiaomi SU7 - Wikipedia</a></li>
<li><a href="https://umbrex.com/resources/umbrex-explainers/automotive-mobility-explainers/ecall-compliance/">What is eCall compliance? | Umbrex Explainers</a></li>

</ul>
</details>

**Tags**: `#自媒体`, `#法律案例`, `#虚假信息`, `#汽车评测`, `#网络规范`

---