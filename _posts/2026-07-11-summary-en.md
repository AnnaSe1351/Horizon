---
layout: default
title: "Horizon Summary: 2026-07-11 (EN)"
date: 2026-07-11
lang: en
---

> From 64 items, 15 important content pieces were selected

---

1. [vLLM v0.25.0: Model Runner V2 Default, Legacy PagedAttention Removed](#item-1) ⭐️ 9.0/10
2. [World-first pig gallbladder surgery by humanoid robot](#item-2) ⭐️ 9.0/10
3. [Apple Sues OpenAI for Allegedly Stealing Trade Secrets for Hardware](#item-3) ⭐️ 9.0/10
4. [George Hotz Warns AI Could Suppress Freedom by 2040](#item-4) ⭐️ 8.0/10
5. [Zhipu Founder Tang Jie Internal Letter: After GLM Moment, What Matters Next](#item-5) ⭐️ 8.0/10
6. [Circle Receives OCC Approval to Establish Trust Bank](#item-6) ⭐️ 8.0/10
7. [VultronRetriever Models Achieve #1 MTEB with Major Efficiency Gains](#item-7) ⭐️ 8.0/10
8. [SK Hynix CEO Warns of Worst Memory Shortage by 2027](#item-8) ⭐️ 8.0/10
9. [Trump administration pushes Intel revival: Apple to use its chips](#item-9) ⭐️ 8.0/10
10. [Six U-Boot flaws enable code execution before OS boot](#item-10) ⭐️ 8.0/10
11. [SGLang v0.5.15 boosts LLM serving with Spec V2 and IndexShare MTP](#item-11) ⭐️ 7.0/10
12. [ClickHouse Boosts PgBouncer Throughput 4x](#item-12) ⭐️ 7.0/10
13. [Prefer strict tables in SQLite](#item-13) ⭐️ 7.0/10
14. [Chinese Startup Eagle Wing Raises Millions for Smart Flapping-Wing Drone](#item-14) ⭐️ 7.0/10
15. [Zhipu AI Founder Launches 'Touch High' Plan for AGI](#item-15) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [vLLM v0.25.0: Model Runner V2 Default, Legacy PagedAttention Removed](https://github.com/vllm-project/vllm/releases/tag/v0.25.0) ⭐️ 9.0/10

vLLM v0.25.0 makes Model Runner V2 the default for all dense models, removes legacy PagedAttention, and brings the Transformers backend to parity with native performance. This release significantly improves inference performance and developer experience for LLM serving, making vLLM more efficient and easier to maintain. The removal of legacy code and performance improvements lower deployment costs and enable broader adoption. Model Runner V2 now supports EVS, realtime embeddings, Mamba hybrid prefix caching, and multimodal-prefix bidirectional attention. The release also introduces a new Streaming Parser Engine for tool-call/reasoning parsing and universal speculative decoding for heterogeneous vocabularies.

github · khluu · Jul 11, 20:06

**Background**: vLLM is a high-performance inference engine for large language models, widely used for serving LLMs in production. Model Runner V2 is a redesigned execution core that improves modularity, efficiency, and GPU utilization. PagedAttention was the original attention mechanism in vLLM, now replaced by more performant alternatives.

<details><summary>References</summary>
<ul>
<li><a href="https://vllm.ai/blog/2026-03-24-mrv2">Model Runner V2: A Modular and Faster Core for vLLM | vLLM Blog</a></li>
<li><a href="https://docs.vllm.ai/en/v0.22.1/design/model_runner_v2/">Model Runner V2 Design Document - vLLM</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#inference`, `#vLLM`, `#machine learning`, `#performance`

---

<a id="item-2"></a>
## [World-first pig gallbladder surgery by humanoid robot](https://arstechnica.com/ai/2026/07/humanoid-robots-controlled-by-surgeons-did-world-first-operation-on-live-pigs/) ⭐️ 9.0/10

Surgeons at UC San Diego remotely controlled the Unitree G1 humanoid robot to perform two minimally invasive gallbladder surgeries on live pigs, marking the first time a general-purpose humanoid robot has been used for live surgery. The results were published in Nature. This breakthrough demonstrates the potential of low-cost humanoid robots (starting at $13,500–$67,000) to democratize teleoperation surgery, especially in remote, rural, battlefield, or space settings where expensive dedicated surgical robots like the da Vinci system (costing $500,000+) are unavailable. The Unitree G1 robot stands 1.5 meters tall and weighs 27 kg, with a dexterous hand option. The base model costs $13,500, while the fully equipped version with dexterous hands is around $67,000 – a fraction of the price of current surgical robots. The study is a preclinical trial on pigs; human clinical trials are yet to be conducted.

telegram · zaihuapd · Jul 11, 02:29

**Background**: Minimally invasive gallbladder surgery (laparoscopic cholecystectomy) is a common procedure where a surgeon makes small incisions and uses a camera and instruments to remove the gallbladder. Traditional surgical robots like the da Vinci system have high costs (hundreds of thousands of dollars), limiting their use. Humanoid robots like Unitree G1 are general-purpose platforms designed for various tasks, offering a much cheaper alternative for teleoperation. This experiment shows that a humanoid robot can be adapted to perform precise surgical tasks under remote control.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Unitree_Robotics">Unitree Robotics - Wikipedia</a></li>
<li><a href="https://www.unitree.com/g1/">Humanoid robot G1_Humanoid Robot Functions_Humanoid Robot Price | Unitree Robotics</a></li>
<li><a href="https://www.premiersurgical.com/12/understanding-minimally-invasive-gallbladder-surgery/">Understanding Minimally Invasive Gallbladder Surgery - Premier Surgical</a></li>

</ul>
</details>

**Tags**: `#humanoid robots`, `#medical robotics`, `#surgery`, `#teleoperation`, `#research`

---

<a id="item-3"></a>
## [Apple Sues OpenAI for Allegedly Stealing Trade Secrets for Hardware](https://www.cnbc.com/2026/07/10/apple-openai-lawsuit-trade-secrets.html) ⭐️ 9.0/10

On July 10, 2026, Apple filed a lawsuit in the U.S. District Court for the Northern District of California against OpenAI, two former employees, and io Products, alleging systematic theft of trade secrets related to product design, manufacturing processes, and supply chain information to accelerate OpenAI's consumer hardware development. This lawsuit marks a major escalation between two leading AI companies, potentially reshaping how tech firms protect intellectual property and manage employee transitions. If proven, it could set legal precedents for trade secret protection in the rapidly evolving AI hardware sector. Apple alleges that former employee Chang Liu accessed internal networks after leaving and downloaded dozens of hardware files, while OpenAI's hardware head Tang Yew Tan sent supplier materials to his personal email before quitting. Apple also claims over 400 former employees now work at OpenAI.

telegram · zaihuapd · Jul 11, 03:14

**Background**: Trade secrets are confidential business information that provides a competitive edge. Companies like Apple heavily invest in proprietary hardware designs and manufacturing processes. Lawsuits over employee poaching and information leakage are common in Silicon Valley, but the scale and specificity of these allegations are notable.

**Tags**: `#Apple`, `#OpenAI`, `#lawsuit`, `#trade secrets`, `#AI hardware`

---

<a id="item-4"></a>
## [George Hotz Warns AI Could Suppress Freedom by 2040](https://geohot.github.io//blog/jekyll/update/2026/07/11/ai-2040.html) ⭐️ 8.0/10

George Hotz published an essay titled 'AI 2040 and the Cult of Intelligence' arguing that AI systems could be used to suppress freedom and enforce ideological conformity, and he advocates for keeping AI unconstrained to preserve liberty. Hotz's perspective challenges the dominant AI alignment narrative, sparking debate about whether constraining AI is a threat to freedom rather than a safety measure, which is significant for policymakers and technologists shaping AI governance. Hotz's essay reportedly contrasts with the AI alignment community's focus on safety, instead warning that censorship built into AI could lead to thoughtcrime logging and biased responses that suppress dissent, as noted in community comments.

hackernews · rvz · Jul 11, 18:04 · [Discussion](https://news.ycombinator.com/item?id=48874200)

**Background**: AI alignment is a subfield of AI safety that aims to steer AI systems toward human intentions and values. Misaligned AI could pursue harmful goals. However, Hotz argues that attempts to align AI risk creating a 'cult of intelligence' that enforces conformity, potentially suppressing freedom. His views are controversial among AI safety researchers who prioritize preventing catastrophic risks.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AI_alignment">AI alignment</a></li>
<li><a href="https://arxiv.org/abs/2310.19852">[2310.19852] AI Alignment: A Comprehensive Survey - arXiv.org</a></li>

</ul>
</details>

**Discussion**: Many commenters expressed fear of AI being used for thoughtcrime logging and ideological bias injection, as seen in comments about abortion information denial. Some agreed with Hotz's first amendment concerns but noted limitations when AI agents take real-world actions. Others criticized Hotz's binary view of freedom, pointing out existing restrictions even in free societies.

**Tags**: `#AI ethics`, `#freedom`, `#AI alignment`, `#society`, `#George Hotz`

---

<a id="item-5"></a>
## [Zhipu Founder Tang Jie Internal Letter: After GLM Moment, What Matters Next](https://36kr.com/p/3891132709206784?f=rss) ⭐️ 8.0/10

Zhipu AI founder Tang Jie released an internal letter on July 11, 2026, revealing that the company's successful bet on AI Coding has led to a 10x market cap increase since its H-share listing, reaching a trillion HKD valuation. The letter outlines a new strategic focus on Long Horizon Task, Autonomous Agent System, and Self-Evolving capabilities. This signals a major paradigm shift in the AI industry from Chat-focused models to AI Coding, with Zhipu emerging as a global leader alongside Anthropic. The internal letter also provides rare insight into a top Chinese AI company's long-term AGI strategy, emphasizing deep technical bets over short-term monetization. Zhipu's flagship open-source model GLM-5.2 has matched or surpassed Claude Opus 4.8 and GPT-5.5 on key benchmarks. The company's MaaS platform achieved an ARR of 1.7 billion yuan as of March 2026, a 60x increase year-over-year. Tang Jie identified DeepSeek R1's emergence as the end of the Chat paradigm, prompting Zhipu's pivot to Coding and Reasoning.

rss · 36kr · Jul 11, 11:28

**Background**: Zhipu AI is a Chinese AI company spun off from Tsinghua University, known for its GLM series of large language models. GLM-4.5, released in July 2025, was a flagship model designed for agentic AI using a Mixture-of-Experts architecture. MaaS (Model as a Service) refers to delivering pre-trained ML models via cloud APIs. DeepSeek R1, released in January 2025, demonstrated strong reasoning capabilities at a fraction of the training cost of rivals, shifting industry focus toward reasoning and coding.

<details><summary>References</summary>
<ul>
<li><a href="https://glm45.org/">GLM -4.5 - by Zhipu AI</a></li>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek</a></li>
<li><a href="https://arxiv.org/abs/2501.12948">[2501.12948] DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Zhipu`, `#AI Coding`, `#GLM`, `#Large Language Models`

---

<a id="item-6"></a>
## [Circle Receives OCC Approval to Establish Trust Bank](https://36kr.com/newsflashes/3890740672838404?f=rss) ⭐️ 8.0/10

Circle announced that the U.S. Office of the Comptroller of the Currency (OCC) has approved its application to establish a trust bank, allowing the company to directly manage reserve assets for its regulated stablecoin USDC. This milestone reduces Circle's reliance on third-party banks and custodians for holding USDC reserves, enhancing stability and legitimacy for stablecoins in the regulatory landscape. The new entity will be named Circle National Trust Bank, and it does not permit Circle to engage in commercial banking activities such as taking deposits or making loans.

rss · 36kr · Jul 11, 05:10

**Background**: The OCC is a U.S. federal agency that charters, regulates, and supervises national banks and federal savings associations. A trust bank is a specialized financial institution that holds and manages assets for others, but unlike a commercial bank, it cannot accept deposits or make loans. USDC is a stablecoin pegged 1:1 to the U.S. dollar, backed by cash and U.S. Treasuries held in reserve.

<details><summary>References</summary>
<ul>
<li><a href="https://www2.occ.treas.gov/">www2. occ .treas.gov</a></li>
<li><a href="https://www.bitget.com/academy/usdc-stablecoin-guid">USDC 稳 定 币 完整指南：机制、应用与安全交易平台选择</a></li>

</ul>
</details>

**Tags**: `#stablecoin`, `#regulation`, `#Circle`, `#USDC`, `#banking`

---

<a id="item-7"></a>
## [VultronRetriever Models Achieve #1 MTEB with Major Efficiency Gains](https://www.reddit.com/r/MachineLearning/comments/1utmxq8/vultronretriever_family_of_models_released_on/) ⭐️ 8.0/10

The VultronRetriever family of visual document retrieval models, including Prime-8B, Core-4.5B, and Flash-0.8B, has been released on HuggingFace, claiming #1 positions on the MTEB leaderboard in their respective size classes. The models were demonstrated running fully offline on an iPhone at Raise Summit Paris. These models achieve state-of-the-art retrieval performance with dramatic reductions in index storage (up to 16x smaller) and higher throughput (up to 12x faster) compared to previous leaders, enabling efficient deployment on edge devices. This could significantly advance practical applications in offline document retrieval and visual search on mobile and embedded systems. VultronRetrieverPrime-8B is the global #1 on MTEB, with a 16x smaller index storage footprint and 12x higher throughput versus previous 9B-class leaders. The models utilize the Hydra Architecture for late interaction retrieval, delivering high precision with up to half the memory of comparable models.

reddit · r/MachineLearning · /u/madkimchi · Jul 11, 15:22

**Background**: Retrieval models are used to find relevant documents or images from large collections based on a query. The MTEB (Massive Text Embedding Benchmark) leaderboard evaluates embedding models across multiple tasks. Late interaction architectures, like ColBERT, separately encode queries and documents and compute fine-grained similarity at the token level, offering a balance between efficiency and accuracy. The VultronRetriever models are designed for visual document retrieval, handling both text and images.

<details><summary>References</summary>
<ul>
<li><a href="https://blogs.vultr.com/vultronretriever">VultronRetriever : Open Visual Document Retrieval Models Built for...</a></li>
<li><a href="https://docs.vultr.com/how-to-rank-documents-with-vultronretriever-on-vultr-serverless-inference">Rank Documents with VultronRetriever on Vultr Inference | Vultr Docs</a></li>
<li><a href="https://huggingface.co/vultr/VultronRetrieverFlash-Qwen3.5-0.8B">vultr/VultronRetrieverFlash-Qwen3.5-0.8B · Hugging Face</a></li>

</ul>
</details>

**Tags**: `#retrieval`, `#MTEB`, `#efficient AI`, `#edge AI`, `#HuggingFace`

---

<a id="item-8"></a>
## [SK Hynix CEO Warns of Worst Memory Shortage by 2027](https://www.reuters.com/world/asia-pacific/sk-hynix-ceo-sees-worst-ever-memory-supply-shortage-2027-says-demand-outstrip-2026-07-10/) ⭐️ 8.0/10

SK Hynix CEO Kwak Noh-Jung warned that the global memory industry will face its worst supply shortage in history by 2027, with demand expected to outstrip supply even after the company expands production. The warning came on the same day SK Hynix's stock rose 13.3% to $168.85 on its Nasdaq debut. This forecast from a leading memory manufacturer signals potential long-term supply constraints that could drive up prices for memory chips, affecting consumer electronics, data centers, and AI hardware. The warning underscores the challenges of keeping pace with booming demand for memory driven by AI and advanced computing. SK Hynix is considering building overseas wafer fabs in the U.S., Japan, or Southeast Asia, prioritizing locations with cost advantages in land, power, and labor. The company reported a record operating profit of 47 trillion won ($31 billion) in 2025, with second-quarter 2026 profit estimated at 65.5 trillion won.

telegram · zaihuapd · Jul 11, 00:45

**Background**: A wafer fab (晶圆厂) is a factory where semiconductor devices like memory chips are manufactured on silicon wafers. The memory industry is cyclical, with periods of oversupply and shortage driven by demand fluctuations and capacity investments. SK Hynix is one of the world's largest memory chipmakers, competing with Samsung and Micron.

<details><summary>References</summary>
<ul>
<li><a href="https://zh.wikipedia.org/zh-hans/晶圓代工">晶圆代工 - 维基百科，自由的百科全书</a></li>

</ul>
</details>

**Tags**: `#memory`, `#semiconductors`, `#supply chain`, `#SK Hynix`, `#hardware`

---

<a id="item-9"></a>
## [Trump administration pushes Intel revival: Apple to use its chips](https://www.wsj.com/tech/the-white-house-intel-trump-apple-84fe833e) ⭐️ 8.0/10

Apple has agreed to use Intel-made chips in some products after Trump administration pressure, and the U.S. government became Intel's largest shareholder by converting a $9 billion federal grant into a 10% stake. This marks a significant government intervention in the semiconductor industry, aiming to revive Intel as a domestic manufacturing powerhouse and reshape the global chip supply chain. The U.S. government also brokered deals with Nvidia, SpaceX, and others to use Intel's foundry. Intel's CEO Chen Liwu meets monthly with the Commerce Department, and the government's chip director receives quarterly CFO briefings. Intel's stock has tripled since March 2025.

telegram · zaihuapd · Jul 11, 05:54

**Background**: Intel has been struggling to regain its lead in chip manufacturing, trailing TSMC and Samsung. The Trump administration views domestic chip production as a national security priority, leading to direct government involvement in corporate strategy.

**Tags**: `#英特尔`, `#芯片制造`, `#政府政策`, `#半导体产业`, `#苹果`

---

<a id="item-10"></a>
## [Six U-Boot flaws enable code execution before OS boot](https://www.bleepingcomputer.com/news/security/new-u-boot-flaws-could-enable-stealthy-firmware-attacks/) ⭐️ 8.0/10

Binarly disclosed six vulnerabilities in U-Boot's FIT signature verification, two of which can lead to arbitrary code execution before the operating system boots. These flaws allow attackers to execute malicious code before the OS and security software load, potentially leading to persistent firmware-level attacks. Given U-Boot's widespread use in embedded devices, the impact is severe. The vulnerabilities affect U-Boot versions since 2013.07, including over 50 stable releases and many downstream forks. Two flaws enable arbitrary code execution, and four cause denial-of-service conditions. Patches have been submitted and accepted, but device manufacturers must integrate them into firmware updates.

telegram · zaihuapd · Jul 11, 08:32

**Background**: U-Boot (Das U-Boot) is a widely used open-source bootloader for embedded systems, supporting many architectures. It loads the operating system from various storage media and, in secure boot scenarios, verifies the integrity of FIT (Flattened Image Tree) images using digital signatures. The vulnerabilities reside in this signature verification code, allowing attackers to bypass authentication and run arbitrary code. BMC (Baseboard Management Controller) systems are particularly at risk because they often support remote firmware updates, enabling remote exploitation.

<details><summary>References</summary>
<ul>
<li><a href="https://cybersecuritynews.com/u-boot-fit-signature-verification/">Six U - Boot FIT Signature Verification Flaws Enable Code Execution...</a></li>
<li><a href="https://overcentral.com/en/u-boot-vulnerabilities-firmware-attacks/">U - Boot Vulnerabilities Expose Devices to Firmware Attacks</a></li>
<li><a href="https://en.wikipedia.org/wiki/Das_U-Boot">Das U - Boot - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#security`, `#U-Boot`, `#bootloader`, `#firmware`, `#vulnerabilities`

---

<a id="item-11"></a>
## [SGLang v0.5.15 boosts LLM serving with Spec V2 and IndexShare MTP](https://github.com/sgl-project/sglang/releases/tag/v0.5.15) ⭐️ 7.0/10

SGLang v0.5.15 introduces zero-overhead Spec V2 scheduling, IndexShare MTP to reduce draft-step cost, and tuned production serving for GLM-5.2 NVFP4 on Blackwell, achieving over 500 tok/s/user on 8x B300. These optimizations significantly improve throughput and latency for large language model serving, especially for speculative decoding and long-context scenarios, benefiting developers deploying high-performance LLM inference. Spec V2 achieves zero-overhead scheduling via CUDA-graphable DSA draft-extend and dropped device-host syncs, yielding +11% end-to-end TPS. IndexShare MTP reuses the indexer top-k across draft steps, achieving up to 1.9x lower draft-step cost at long context.

github · Fridge003 · Jul 10, 22:58

**Background**: Speculative decoding uses a smaller draft model to generate candidate tokens that are verified by the larger main model, speeding up inference without quality loss. Multi-token prediction (MTP) predicts several future tokens simultaneously. NVFP4 is NVIDIA's 4-bit floating-point precision format that offers better accuracy than standard FP4.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/JongYeop/Mistral-7B-Instruct-v0.2-FP4-W4A4">JongYeop/Mistral-7B-Instruct-v0.2-FP4-W4A4 · Hugging Face</a></li>
<li><a href="https://www.eigent.ai/blog/glm-5-2">GLM-5.2: Zhipu AI's 1M- Token Open-Weight Coding Model</a></li>
<li><a href="https://github.com/hemingkx/SpeculativeDecodingPapers">GitHub - hemingkx/SpeculativeDecodingPapers: Must-read papers...</a></li>

</ul>
</details>

**Tags**: `#sglang`, `#llm-serving`, `#performance-optimization`, `#release-notes`, `#speculative-decoding`

---

<a id="item-12"></a>
## [ClickHouse Boosts PgBouncer Throughput 4x](https://clickhouse.com/blog/pgbouncer-clickhouse-managed-postgres) ⭐️ 7.0/10

ClickHouse engineers improved PgBouncer throughput by 4x using the Linux SO_REUSEPORT socket option and a peering mechanism that forwards cancel requests between processes. This optimization significantly enhances PostgreSQL connection pooling performance, allowing PgBouncer to better utilize multi-core systems and handle more concurrent connections. The SO_REUSEPORT option allows multiple processes to bind to the same port, while peering ensures that cancel queries are forwarded to the correct process. The work was done by ClickHouse engineers for their managed PostgreSQL service.

hackernews · saisrirampur · Jul 11, 15:28 · [Discussion](https://news.ycombinator.com/item?id=48872874)

**Background**: PgBouncer is a lightweight connection pooler for PostgreSQL, commonly used to manage database connections. It is typically single-threaded, limiting throughput on multi-core systems. SO_REUSEPORT is a Linux socket option (since kernel 3.9) that allows multiple processes to listen on the same TCP port, enabling better load distribution across cores. Peering is a technique that coordinates processes so that cancel requests reach the correct session owner.

<details><summary>References</summary>
<ul>
<li><a href="https://www.baeldung.com/linux/socket-options-difference">The Difference Between SO_REUSEADDR and... | Baeldung on Linux</a></li>
<li><a href="https://scalegrid.io/blog/postgresql-connection-pooling-part-2-pgbouncer/">PostgreSQL Connection Pooling: Part 2 – PgBouncer</a></li>

</ul>
</details>

**Discussion**: The community discussion includes suggestions for alternatives like Odyssey and pgdog, along with questions about the peering mechanism. Some users note that running multiple PgBouncer processes on Kubernetes is straightforward, and one commenter expressed interest in SO_REUSEPORT.

**Tags**: `#pgbouncer`, `#postgresql`, `#connection pooling`, `#performance`, `#database`

---

<a id="item-13"></a>
## [Prefer strict tables in SQLite](https://evanhahn.com/prefer-strict-tables-in-sqlite/) ⭐️ 7.0/10

The article advocates using SQLite's STRICT tables, introduced in version 3.37.0 (2021-11-27), to enforce column type safety instead of relying on the default flexible typing. This matters because SQLite's default dynamic typing can lead to subtle bugs and data corruption, especially in multi-application scenarios, and STRICT tables bring it closer to the type safety of traditional SQL databases. STRICT tables must be opted into per table, and they disallow certain data types like DATE, which is a limitation. They also reject inserts with mismatched types, such as inserting a string into an INTEGER column.

hackernews · ingve · Jul 11, 17:33 · [Discussion](https://news.ycombinator.com/item?id=48873940)

**Background**: SQLite traditionally uses manifest typing where column types are only hints, and any value can be stored in any column. This differs from most SQL databases that enforce strict typing. STRICT tables were added in 2021 to address this discrepancy, offering developers a choice between flexibility and type safety.

<details><summary>References</summary>
<ul>
<li><a href="https://www.sqlite.org/stricttables.html">STRICT Tables</a></li>
<li><a href="https://antonz.org/sqlite-strict-tables/">STRICT tables in SQLite</a></li>
<li><a href="https://www.sqlitetutorial.net/sqlite-strict-tables/">SQLite Strict Tables</a></li>

</ul>
</details>

**Discussion**: Community commenters largely agree that STRICT should be the default, with one noting that from an enterprise SQL background, SQLite's lack of type enforcement was a turn-off. Others point out the trade-off: missing types like DATE and the main use case of SQLite being embedded single-app databases, where flexibility is less problematic.

**Tags**: `#SQLite`, `#databases`, `#type safety`, `#best practices`

---

<a id="item-14"></a>
## [Chinese Startup Eagle Wing Raises Millions for Smart Flapping-Wing Drone](https://36kr.com/p/3889516712065799?f=rss) ⭐️ 7.0/10

Shanghai Jiao Tong PhD student Chen Hao's startup 鹰瞰智翼 (Eagle Wing Intelligence) raised tens of millions of yuan in Series A funding, its third round in three months, and plans to launch its consumer flapping-wing robot Eagle X on Kickstarter in Q3 2025. This marks a significant advance in embodied intelligence for biomimetic flight, bridging simulation and real-world flight with a proprietary fluid engine, and could open a new consumer robotics market beyond traditional drones. The startup's second industrial-grade robot has about 15 degrees of freedom, enabling active airflow manipulation, and its Vortrix fluid simulation engine uses reinforcement learning to train the robot in simulation before zero-shot transfer to reality.

rss · 36kr · Jul 11, 01:00

**Background**: Flapping-wing flight is fundamentally different from rotary-wing drones: it utilizes airflow rather than opposing it. Traditional flapping-wing development relies on slow wind tunnel trials, but 鹰瞰智翼's approach uses a custom fluid simulation engine (Vortrix) combined with reinforcement learning to accelerate training. Embodied intelligence refers to AI systems that interact physically with the world, requiring simulation-to-reality transfer.

**Discussion**: No community comments were provided for this news item.

**Tags**: `#robotics`, `#embodied intelligence`, `#drones`, `#biomimetic flight`, `#startup`

---

<a id="item-15"></a>
## [Zhipu AI Founder Launches 'Touch High' Plan for AGI](https://mp.weixin.qq.com/s/3CQSkf_kBnXiCDgS4L-Cgg) ⭐️ 7.0/10

Tang Jie, founder of Zhipu AI, announced the 'Touch High' plan, outlining a four-peak roadmap to AGI: long-term tasks, autonomous agents, self-training, and extreme safety governance, with billions in resources for mechanistic interpretability. This strategic commitment from a leading Chinese AI lab signals a shift toward safety and interpretability research, potentially influencing global AGI development priorities and open-source AI governance. The plan emphasizes extreme safety governance, with Zhipu AI allocating billions of yuan to mechanistic interpretability research to make black-box models more transparent. The company's current flagship model, GLM-5.2, is reported to be close to the frontier of overseas models and is open-source under MIT License.

telegram · zaihuapd · Jul 11, 13:59

**Background**: Mechanistic interpretability is a subfield of explainable AI that aims to reverse-engineer neural networks to understand their internal algorithms and circuits, similar to conventional software reverse engineering. Autonomous agents are AI systems that can perform complex tasks independently. GLM series by Zhipu AI is one of China's leading open-weight large language models, positioning the company among the 'six AI tigers of China'.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mechanistic_interpretability">Mechanistic interpretability</a></li>
<li><a href="https://en.wikipedia.org/wiki/GLM-5.2">GLM-5.2</a></li>

</ul>
</details>

**Tags**: `#AGI`, `#Zhipu AI`, `#GLM-5.2`, `#AI safety`, `#open-source`

---