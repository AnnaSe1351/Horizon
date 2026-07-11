---
layout: default
title: "Horizon Summary: 2026-07-11 (EN)"
date: 2026-07-11
lang: en
---

> From 64 items, 17 important content pieces were selected

---

1. [SpaceX Proposes 100,000 More Starlink Satellites for 100x Bandwidth](#item-1) ⭐️ 9.0/10
2. [World's First Live Pig Gallbladder Surgery by Humanoid Robot](#item-2) ⭐️ 9.0/10
3. [6 U-Boot flaws allow code execution before boot](#item-3) ⭐️ 9.0/10
4. [SGLang v0.5.15 release boosts LLM inference performance](#item-4) ⭐️ 8.0/10
5. [Apple Sues OpenAI Over Trade Secret Theft](#item-5) ⭐️ 8.0/10
6. [Zhipu CEO Tang Jie's Internal Letter: Beyond Market Value to AGI](#item-6) ⭐️ 8.0/10
7. [Circle Receives OCC Approval to Establish Trust Bank](#item-7) ⭐️ 8.0/10
8. [VultronRetriever Models Achieve #1 on MTEB Leaderboard](#item-8) ⭐️ 8.0/10
9. [Relativity governs chemical bonds in heavy elements, study confirms](#item-9) ⭐️ 7.0/10
10. [Residential Proxies and Scraping: LWN Analysis and Community Debate](#item-10) ⭐️ 7.0/10
11. [Soviet control rooms: vintage design meets modern observability](#item-11) ⭐️ 7.0/10
12. [AR glasses require continuous recording, cloud processing, says Patel](#item-12) ⭐️ 7.0/10
13. [SK Hynix Nasdaq Debut, CXMT IPO, ChatGPT Work Agent](#item-13) ⭐️ 7.0/10
14. [SK Hynix CEO Warns of Worst Memory Shortage by 2027](#item-14) ⭐️ 7.0/10
15. [GPT-5.6 Codex Boosts Context Window to 353K Tokens](#item-15) ⭐️ 7.0/10
16. [Zhipu Founder Launches 'Touch High' AGI Plan](#item-16) ⭐️ 7.0/10
17. [Google opposes EU site blocking, US anti-piracy bills advance](#item-17) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [SpaceX Proposes 100,000 More Starlink Satellites for 100x Bandwidth](https://www.zdnet.com/home-and-office/networking/spacex-wants-to-launch-100000-more-starlink-satellites/) ⭐️ 9.0/10

SpaceX has submitted a proposal to the US Federal Communications Commission (FCC) to launch up to 100,000 additional Starlink satellites, aiming to increase total system bandwidth by 100 times. If approved, this would be the largest satellite constellation ever proposed, potentially revolutionizing global internet access by providing high-speed, low-latency connectivity to underserved regions. However, it also raises serious concerns about space debris, light pollution, and the privatization of low Earth orbit. The proposal is a draft supplement to SpaceX's earlier application for Gen2 Starlink, which currently has authorization for about 30,000 satellites but has launched over 7,000. The new plan would bring the total to over 130,000 satellites, requiring advanced orbital management and debris mitigation measures.

hackernews · CrankyBear · Jul 10, 17:51 · [Discussion](https://news.ycombinator.com/item?id=48863064)

**Background**: Starlink is a satellite internet constellation operated by SpaceX, currently with thousands of active satellites in low Earth orbit, providing broadband to remote and rural areas. A mega-constellation is a large group of satellites working together, but it also contributes to space debris and light pollution. SpaceX's proposal faces scrutiny from regulators, astronomers, and environmental groups.

<details><summary>References</summary>
<ul>
<li><a href="https://leosatnetwork.com/definitions/mega-constellation">What is Mega - constellation ? | Satellite & Space... | LeoSatNetwork</a></li>
<li><a href="https://en.wikipedia.org/wiki/Space_debris_mitigation">Space debris mitigation</a></li>
<li><a href="https://orbitaldebris.jsc.nasa.gov/mitigation/">Debris Mitigation - ARES | Orbital Debris Program Office</a></li>

</ul>
</details>

**Discussion**: Community members expressed mixed emotions: some lament the loss of a natural night sky and the commercialization of space, while others highlight the practical benefits of reliable internet in underserved areas. One commenter noted the transformative potential for newly middle-class populations in developing countries, and a user shared a positive experience in a rural area where Starlink replaced poor previous service.

**Tags**: `#SpaceX`, `#Starlink`, `#satellite internet`, `#broadband`, `#space infrastructure`

---

<a id="item-2"></a>
## [World's First Live Pig Gallbladder Surgery by Humanoid Robot](https://arstechnica.com/ai/2026/07/humanoid-robots-controlled-by-surgeons-did-world-first-operation-on-live-pigs/) ⭐️ 9.0/10

Surgeons remotely operated a Unitree G1 humanoid robot to perform two minimally invasive gallbladder removal surgeries on live pigs, marking the first use of a general-purpose humanoid robot for live animal surgery. The results were published in Nature. This low-cost approach (G1 base price ~$13,500) could democratize access to robotic surgery, especially in rural, battlefield, or space settings where expensive specialized robots like da Vinci are impractical. It also shows humanoid robots' potential beyond factories into complex medical tasks. The Unitree G1 is 1.5 m tall, weighs 27 kg, and has 23 degrees of freedom. Its price, including a dexterous hand, is about $67,000, vastly cheaper than da Vinci systems (0.5–2.5 million USD). The robot was teleoperated by surgeons for the procedure.

telegram · zaihuapd · Jul 11, 02:29

**Background**: Teleoperated robotic surgery enables surgeons to perform precise procedures from a distance using robotic arms controlled via a console. While systems like da Vinci have been the standard, they are expensive and bulky. Humanoid robots like the G1 offer a general-purpose, affordable alternative that can be deployed in diverse environments.

<details><summary>References</summary>
<ul>
<li><a href="https://www.unitree.com/g1/">Humanoid robot G1_Humanoid Robot Functions ... - Unitree G1</a></li>
<li><a href="https://www.azorobotics.com/Article.aspx?ArticleID=732">Teleoperated Robotic Surgery : An Overview</a></li>

</ul>
</details>

**Tags**: `#humanoid robots`, `#medical robotics`, `#remote surgery`, `#robotic surgery`, `#teleoperation`

---

<a id="item-3"></a>
## [6 U-Boot flaws allow code execution before boot](https://www.bleepingcomputer.com/news/security/new-u-boot-flaws-could-enable-stealthy-firmware-attacks/) ⭐️ 9.0/10

Security firm Binarly disclosed six vulnerabilities in U-Boot's FIT image signature verification, two of which can lead to arbitrary code execution and four to device crashes, affecting U-Boot versions since 2013.07. These vulnerabilities enable attackers to execute malicious code before the operating system boots, potentially disabling firmware security features or implanting persistent malware, impacting a wide range of embedded devices. The flaws reside in the signature verification of FIT images, can be exploited remotely on systems with remote firmware update capabilities like BMCs, and while patches have been accepted by upstream, they require integration by hardware vendors for distribution.

telegram · zaihuapd · Jul 11, 08:32

**Background**: U-Boot is a widely used bootloader for embedded systems, responsible for loading the operating system. FIT (Flattened Image Tree) is a format that packages the kernel, device tree, and other binaries with cryptographic signatures for secure boot. BMC (Baseboard Management Controller) is a specialized processor on server motherboards that enables remote monitoring and firmware updates.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.u-boot.org/en/latest/usage/fit/signature.html">U-Boot FIT Signature Verification — Das U-Boot unknown version documentation</a></li>
<li><a href="https://thehackernews.com/2022/11/over-dozen-new-bmc-firmware-flaws.html">Over a Dozen New BMC Firmware Flaws Expose OT and IoT Devices...</a></li>

</ul>
</details>

**Tags**: `#security`, `#U-Boot`, `#firmware`, `#vulnerability`, `#embedded systems`

---

<a id="item-4"></a>
## [SGLang v0.5.15 release boosts LLM inference performance](https://github.com/sgl-project/sglang/releases/tag/v0.5.15) ⭐️ 8.0/10

SGLang v0.5.15 introduces Spec V2 with zero-overhead scheduling via CUDA-graphable DSA draft-extend, and IndexShare MTP which reuses indexer top-k across draft steps, reducing draft-step costs up to 1.9x. It also tunes GLM-5.2 NVFP4 on Blackwell hardware, achieving over 500 tokens per second per user on 8x B300. These optimizations significantly improve the efficiency and throughput of large language model serving, particularly for production deployments on NVIDIA Blackwell GPUs. The Spec V2 and IndexShare MTP innovations reduce latency and computational overhead, enabling faster and more cost-effective inference for high-demand applications. Spec V2 achieves +11% end-to-end TPS by dropping host-to-device and device-to-host syncs and fusing metadata operations. IndexShare MTP reduces draft-step costs up to 1.9x at long context. GLM-5.2 NVFP4 on 8x B300 reaches 500+ tok/s/user, and on 4x GB300 reaches 450 tok/s/user at batch size 1.

github · Fridge003 · Jul 10, 22:58

**Background**: SGLang is an open-source inference engine for large language models, known for its efficient serving capabilities. NVFP4 is a 4-bit floating point quantization format optimized for NVIDIA Blackwell GPUs, offering high throughput with reduced memory usage. Speculative decoding accelerates inference by using a smaller draft model to predict multiple tokens, which the main model then verifies. Multi-Token Prediction (MTP) is a technique where the model predicts multiple future tokens simultaneously, improving efficiency.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/nvidia/GLM-5.2-NVFP4">nvidia/GLM-5.2-NVFP4 · Hugging Face</a></li>
<li><a href="https://cohere.com/blog/hardware-aware-dynamic-speculative-decoding">Hardware-Aware, Dynamic Speculative Decoding (DSD) | Cohere</a></li>
<li><a href="https://arxiv.org/abs/2502.09419">[2502.09419] On multi-token prediction for efficient LLM ... Multi-Token Prediction (MTP) — Megatron Bridge Multi-Token Prediction (MTP) | Sebastian Raschka, PhD On multi-token prediction for efficient LLM inference - arXiv.org Multi-Token Prediction (MTP) — Megatron Core MTP (Multi-Token Prediction) - vLLM</a></li>

</ul>
</details>

**Tags**: `#LLM serving`, `#GPU optimization`, `#speculative decoding`, `#inference performance`

---

<a id="item-5"></a>
## [Apple Sues OpenAI Over Trade Secret Theft](https://9to5mac.com/2026/07/10/apple-sues-openai-trade-secret-theft/) ⭐️ 8.0/10

Apple has filed a lawsuit against OpenAI, accusing the company and several former employees of systematically stealing trade secrets, including confidential hardware information, and coaching new hires on how to avoid detection when leaving Apple. This lawsuit could have major repercussions for OpenAI, potentially crippling its hardware operations and setting a legal precedent for intellectual property protection in the AI industry. It underscores the growing tension between tech giants over AI talent and technology. According to the complaint, OpenAI recruits emailed themselves confidential information when leaving Apple, and used Apple hardware data to approach Apple suppliers. Apple alleges a pattern of deliberate trade secret misappropriation.

hackernews · stock_toaster · Jul 10, 20:47 · [Discussion](https://news.ycombinator.com/item?id=48865019)

**Background**: Trade secret theft lawsuits are common in the tech industry, but this case is particularly significant due to the deep pockets and high stakes involved. Apple has a long history of aggressively protecting its intellectual property, and OpenAI is a leading AI company whose business model relies on large-scale data and hardware.

**Discussion**: Commenters largely criticize OpenAI, calling it a company built on copyright violation and predicting severe consequences for its hardware operations. Some advise businesses using OpenAI models to be cautious about their own IP, while others see the lawsuit as open-and-shut given Apple's resources.

**Tags**: `#Apple`, `#OpenAI`, `#trade secrets`, `#lawsuit`, `#AI ethics`

---

<a id="item-6"></a>
## [Zhipu CEO Tang Jie's Internal Letter: Beyond Market Value to AGI](https://36kr.com/newsflashes/3891162734689031?f=rss) ⭐️ 8.0/10

On July 11, 2026, Zhipu founder and CEO Tang Jie released an internal letter titled 'The Great Wave Has Come,' announcing the company will not pursue short-term application monetization but will focus on long-term AGI goals: long-horizon task capability, autonomous agent systems, self-evolution, and extreme safety governance. This strategic shift from a top Chinese AI company signals a commitment to foundational AGI research at a time when many peers race to commercialize, potentially resetting industry priorities. Zhipu's market value has already entered the 'trillion Hong Kong dollar club,' adding weight to its long-term vision. Zhipu's market value surged 10x in six months to over HK$1 trillion by June 2026, surpassing Baidu and Xiaomi. The company attributed its growth to a bet on coding (Coding) and reasoning (Reasoning) capabilities starting in 2025, leading to the open-source GLM-5.2 model that rivals GPT-5.5 and Claude Opus 4.8.

rss · 36kr · Jul 11, 11:35

**Background**: Zhipu AI, founded in 2019 as a spinout from Tsinghua University, develops the General Language Model (GLM) series. The company's open-weight models, including ChatGLM, have gained international attention. The internal letter outlines three technical mountains to climb for AGI: long-horizon tasks, autonomous agents, and self-evolution, drawing on progress from models like GLM-5.2 and industry trends.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GLM_(AI)">GLM (AI) - Wikipedia</a></li>
<li><a href="https://www.businessinsider.com/what-is-glm-5-2-chinese-ai-coding-model-2026-6">What is GLM-5.2? Another open-source Chinese AI model has Silicon Valley's attention.</a></li>

</ul>
</details>

**Tags**: `#AGI`, `#战略`, `#智谱`, `#AI发展`, `#内部信`

---

<a id="item-7"></a>
## [Circle Receives OCC Approval to Establish Trust Bank](https://36kr.com/newsflashes/3890740672838404?f=rss) ⭐️ 8.0/10

Circle announced that the U.S. Office of the Comptroller of the Currency (OCC) approved its application to establish a trust bank, named Circle National Trust Bank, on Friday. This milestone allows Circle to directly manage reserve assets backing its USDC stablecoin, reducing reliance on third-party banks and enhancing trust in the stablecoin ecosystem. Circle National Trust Bank will hold cash and U.S. Treasury assets backing USDC, but the license does not permit commercial banking activities such as taking deposits or making loans.

rss · 36kr · Jul 11, 05:10

**Background**: A trust bank acts as a fiduciary managing assets on behalf of clients. Previously, Circle relied on third-party banks and custodians to hold USDC reserves. The OCC is the primary regulator for national banks in the U.S.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Trust_bank">Trust bank</a></li>

</ul>
</details>

**Tags**: `#stablecoin`, `#regulation`, `#Circle`, `#USDC`, `#blockchain`

---

<a id="item-8"></a>
## [VultronRetriever Models Achieve #1 on MTEB Leaderboard](https://www.reddit.com/r/MachineLearning/comments/1utmxq8/vultronretriever_family_of_models_released_on/) ⭐️ 8.0/10

The VultronRetriever family of models, including Prime-8B, Core-4.5B, and Flash-0.8B, has been released on Hugging Face, each ranking first in its class on the MTEB leaderboard, with VultronRetrieverPrime-8B as the global #1. The models were demonstrated running fully offline on an iPhone during the Raise Summit Paris. This release sets a new state-of-the-art for retrieval models, offering substantial improvements in speed, memory efficiency, and offline edge performance, which is critical for deploying AI on mobile and resource-constrained devices. VultronRetrieverPrime-8B has up to 16x smaller index storage footprint and 12x higher throughput compared to previous 9B-class leaders, while the Flash-0.8B model indexes up to 60 images per minute fully offline. The models leverage the Hydra architecture for late interaction retrieval and generation at half the memory of comparable models.

reddit · r/MachineLearning · /u/madkimchi · Jul 11, 15:22

**Background**: The MTEB (Massive Text Embedding Benchmark) is a standard public leaderboard for evaluating embedding models on tasks like retrieval, classification, and clustering. Late interaction retrieval, introduced by models like ColBERT, separates query and document processing until the final stages, enabling efficient and precise similarity computation. Hydra is a novel architecture that unifies document retrieval and generation within a single vision-language model, using bidirectional attention for retrieval and causal attention for generation.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/spaces/mteb/leaderboard">MTEB Leaderboard - a Hugging Face Space by mteb</a></li>
<li><a href="https://arxiv.org/html/2603.28554">Hydra: Unifying Document Retrieval and Generation in a Single Vision-Language Model</a></li>
<li><a href="https://jina.ai/news/what-is-colbert-and-late-interaction-and-why-they-matter-in-search/">What is ColBERT and Late Interaction and Why They Matter in Search?</a></li>

</ul>
</details>

**Tags**: `#retrieval`, `#MTEB`, `#edge AI`, `#model release`, `#NLP`

---

<a id="item-9"></a>
## [Relativity governs chemical bonds in heavy elements, study confirms](https://www.brown.edu/news/2026-07-09/chemical-bonds-relativity) ⭐️ 7.0/10

New research published in Science provides experimental confirmation that relativistic effects, including spin-orbit coupling, govern chemical bonding in heavy elements. This study validates long-standing theoretical predictions and deepens our understanding of chemical behavior in heavy elements like gold and mercury, with implications for materials science and quantum chemistry. The research uses advanced spectroscopic techniques to directly observe spin-orbit coupling's influence on chemical bonds. It underscores that non-relativistic quantum chemistry models are insufficient for accurately describing heavy elements.

hackernews · hhs · Jul 10, 22:30 · [Discussion](https://news.ycombinator.com/item?id=48866134)

**Background**: Relativistic effects become significant when electrons move at speeds close to the speed of light, which occurs in heavy elements due to high nuclear charge. Spin-orbit coupling is a relativistic interaction between an electron's spin and its orbital motion, affecting energy levels and bonding. This field is known as relativistic quantum chemistry.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Spin-orbit_coupling">Spin-orbit coupling</a></li>
<li><a href="https://en.wikipedia.org/wiki/Relativistic_quantum_chemistry">Relativistic quantum chemistry</a></li>

</ul>
</details>

**Discussion**: Commenters note that relativistic effects on heavy elements were already known, but this study provides direct experimental confirmation. Some appreciate the validation of Einstein's theories, while others debate the novelty of the findings. Overall, the community engagement is high with 148 comments.

**Tags**: `#physics`, `#chemistry`, `#relativity`, `#heavy elements`, `#quantum mechanics`

---

<a id="item-10"></a>
## [Residential Proxies and Scraping: LWN Analysis and Community Debate](https://lwn.net/SubscriberLink/1080822/990a8a5e2d379085/) ⭐️ 7.0/10

The LWN article discusses the challenge of blocking sophisticated web scrapers that use residential proxy networks, and considers proof-of-work solutions like Anubis, while noting their limitations. This matters because residential proxies enable large-scale scraping that drains server resources and threatens the open web, while solutions like proof-of-work may be bypassed by botnets and could harm legitimate users. The debate highlights the tension between protecting content and maintaining accessibility. Residential proxies route traffic through IPs assigned to real home devices, making bot detection difficult. Proof-of-work solutions like Anubis can be circumvented by botnets that use millions of devices to compute challenges, and they also introduce delays for legitimate visitors.

hackernews · chmaynard · Jul 10, 19:38 · [Discussion](https://news.ycombinator.com/item?id=48864252)

**Background**: Residential proxies are proxy servers that use IP addresses from real ISP-assigned residential devices, making them appear as legitimate users. They are commonly sold for web scraping, SEO, and multi-accounting. Proof-of-work (PoW) is a computational challenge that requires solving a puzzle before accessing a site, designed to deter automated scraping. Anubis is an open-source PoW tool used by some websites to combat aggressive AI scraping.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Anubis_(software)">Anubis (software) - Wikipedia</a></li>
<li><a href="https://grokipedia.com/page/Residential_proxy">Residential proxy</a></li>

</ul>
</details>

**Discussion**: Community comments express skepticism about proof-of-work effectiveness, advocate for a better common crawl as a solution, note the ease of installing proxies via apps, and argue that the issue is scraping intensity. Some also mention the need for archiving due to page deletion.

**Tags**: `#web scraping`, `#residential proxies`, `#security`, `#bot detection`, `#common crawl`

---

<a id="item-11"></a>
## [Soviet control rooms: vintage design meets modern observability](https://designyoutrust.com/2018/01/vintage-beauty-soviet-control-rooms/) ⭐️ 7.0/10

An article showcases the aesthetic and functional design of Soviet-era control rooms, sparking a discussion comparing them to modern software observability. The discussion bridges historical industrial design with current software engineering concepts, highlighting lessons for system observability that are still relevant today. Commenters note that similar control rooms existed in non-Soviet countries and praise the use of physical model-based displays and shadowless lighting for operator clarity.

hackernews · mvdtnz · Jul 11, 05:19 · [Discussion](https://news.ycombinator.com/item?id=48868996)

**Background**: Control rooms in the pre-digital era used large panels with lights, dials, and mimic diagrams to show system status. Observability in software refers to the ability to infer system state from outputs, often through metrics, logs, and traces.

<details><summary>References</summary>
<ul>
<li><a href="https://www.geeksforgeeks.org/electrical-engineering/controllability-and-observability-in-control-system/">Controllability and Observability in Control System - GeeksforGeeks</a></li>

</ul>
</details>

**Discussion**: Commenters generally appreciate the design, with some arguing it is not unique to the Soviet Union. One highlights that physical modeling supported causal reasoning, contrasting with modern software's time-series focus. Another shares a related article on seafoam green control rooms.

**Tags**: `#control rooms`, `#Soviet`, `#design`, `#history`, `#observability`

---

<a id="item-12"></a>
## [AR glasses require continuous recording, cloud processing, says Patel](https://simonwillison.net/2026/Jul/10/nilay-patel/#atom-everything) ⭐️ 7.0/10

Nilay Patel argued that augmented reality glasses are technically impossible without continuously recording cameras and cloud processing, leading to inevitable privacy invasion, and questioned whether such products should be pursued. This argument challenges the core direction of AR development, highlighting a fundamental privacy trade-off that could hinder consumer adoption or require significant societal debate. Patel claims no chip small enough to fit in glasses stems is both powerful and power-efficient for real-time processing, necessitating cloud offloading, while on-device alternatives result in bulky headsets like the Apple Vision Pro.

rss · Simon Willison · Jul 10, 17:05

**Background**: Augmented reality glasses aim to overlay digital information onto the real world, requiring cameras to understand the environment. On-device processing keeps data local and reduces latency but is limited by power and size constraints, while cloud processing offers more power but introduces privacy and latency issues. Recent advancements in on-device AI chips, like the AR1+ Gen 1, can handle simple tasks locally, but complex real-time AR remains challenging.

<details><summary>References</summary>
<ul>
<li><a href="https://www.evenrealities.com/blog/how-ai-glasses-work">How Do AI Glasses Work? The Complete Technology Guide 2025</a></li>
<li><a href="https://dymesty.com/blogs/articles/smart-glasses-processor-chip-guide">Smart Glasses Processor Guide: Chips, NPU & On-Device AI Explained – Dymesty AI Glasses</a></li>

</ul>
</details>

**Tags**: `#augmented reality`, `#privacy`, `#tech ethics`, `#cloud computing`, `#surveillance`

---

<a id="item-13"></a>
## [SK Hynix Nasdaq Debut, CXMT IPO, ChatGPT Work Agent](https://36kr.com/p/3890553690192384?f=rss) ⭐️ 7.0/10

SK Hynix made its Nasdaq debut on July 10, 2026, closing up nearly 13% from its IPO price of $149. Chinese memory chip maker CXMT (ChangXin Memory Technologies) revealed its underwriter lineup for its upcoming IPO. OpenAI launched ChatGPT Work, an AI agent powered by GPT-5.6 that can autonomously complete complex, multi-hour tasks across applications. SK Hynix's Nasdaq listing provides the world's second-largest memory chip maker with a new funding channel for AI infrastructure growth, attracting global investors. CXMT's IPO is a milestone for China's semiconductor self-sufficiency, as it is the leading domestic DRAM manufacturer. ChatGPT Work marks a significant advance in practical AI agents, capable of executing long-running, multi-step workflows autonomously. SK Hynix issued 177.9 million American Depositary Receipts (ADRs) at $149 each, raising about $26.5 billion; each ADR represents one-tenth of a common share on the Korea Exchange. CXMT's underwriter syndicate includes six major Chinese securities firms, notably China International Capital Corporation (CICC) and CITIC Securities, with several also being shareholders. ChatGPT Work is built on GPT-5.6, integrated into the ChatGPT desktop app with Codex, and can browse websites, run code, and generate slideshows and spreadsheets over hours of sustained effort.

rss · 36kr · Jul 11, 01:24

**Background**: AI agents are intelligent systems that can use tools and take actions autonomously to achieve goals, often with varying degrees of autonomy. ChatGPT, originally launched by OpenAI in 2022, is a generative AI chatbot that uses large language models (LLMs). American Depositary Receipts (ADRs) are negotiable certificates that represent shares in a foreign company and trade on U.S. stock exchanges. CXMT is a leading Chinese DRAM manufacturer whose IPO is seen as part of China's push to reduce reliance on foreign memory chips.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ChatGPT_agent">ChatGPT agent</a></li>
<li><a href="https://en.wikipedia.org/wiki/AI_agent">AI agent</a></li>
<li><a href="https://openai.com/index/introducing-chatgpt-agent/">Introducing ChatGPT agent: bridging research and action | OpenAI</a></li>

</ul>
</details>

**Tags**: `#semiconductor`, `#AI`, `#IPO`, `#memory`, `#tech news`

---

<a id="item-14"></a>
## [SK Hynix CEO Warns of Worst Memory Shortage by 2027](https://www.reuters.com/world/asia-pacific/sk-hynix-ceo-sees-worst-ever-memory-supply-shortage-2027-says-demand-outstrip-2026-07-10/) ⭐️ 7.0/10

SK Hynix CEO Kwak Noh-Jung warned that the global memory industry will face its worst-ever supply shortage by 2027, with customer demand expected to outstrip supply even after aggressive expansion. This prediction signals a major supply constraint for key technologies such as AI and cloud computing, potentially driving up prices and affecting the broader semiconductor supply chain. SK Hynix's 2025 operating profit reached a record 47 trillion won ($31 billion), and the CEO mentioned that the company is considering overseas fab locations in the US, Japan, and Southeast Asia, prioritizing cost advantages.

telegram · zaihuapd · Jul 11, 00:45

**Background**: The memory industry is cyclical, with periods of oversupply and shortage driven by demand for DRAM and NAND flash used in data centers, PCs, and mobile devices. SK Hynix is a leading memory manufacturer alongside Samsung and Micron.

**Tags**: `#memory shortage`, `#SK Hynix`, `#semiconductor industry`, `#supply chain`, `#hardware`

---

<a id="item-15"></a>
## [GPT-5.6 Codex Boosts Context Window to 353K Tokens](https://www.reddit.com/r/codex/comments/1us14aj/gpt_56_has_larger_ctx_window/) ⭐️ 7.0/10

GPT-5.6 Codex's effective context window has increased from about 258K to roughly 353K tokens. Requests exceeding 272K tokens now incur double input pricing (2x) and 1.5x output pricing. This extension allows developers to handle larger codebases or documents without truncation, but the higher pricing for long contexts may impact cost-sensitive users. The pricing change encourages more efficient use of the context window. The GPT-5.6 series includes three models (Sol, Terra, Luna) with tiered pricing. For Sol, short-context input is $5 per million tokens and output $30; long-context input doubles to $10 and output to $45. The effective window is 353K, though the API spec advertises up to 1M tokens.

telegram · zaihuapd · Jul 11, 13:34

**Background**: GPT-5.6 is OpenAI's latest large language model iteration. The context window determines how much text the model can consider at once. Codex is an AI coding assistant that uses GPT models. The effective context window is often smaller than the maximum due to system overhead and compression. Pricing increases for longer contexts help manage computational costs.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/openai/codex/issues/31860">[Critical][Codex App] GPT-5.6 Sol is catalog-capped at 372K ...</a></li>
<li><a href="https://github.com/openai/codex/discussions/21298">Codex automatic context compression always fails ! · openai codex ...</a></li>

</ul>
</details>

**Discussion**: The community suggests reverting the effective window to around 258K to leverage Codex's automatic compression earlier and avoid the higher pricing tier. Some users report that automatic compression has been unreliable in previous versions.

**Tags**: `#GPT-5`, `#Codex`, `#context window`, `#pricing`, `#AI model`

---

<a id="item-16"></a>
## [Zhipu Founder Launches 'Touch High' AGI Plan](https://mp.weixin.qq.com/s/3CQSkf_kBnXiCDgS4L-Cgg) ⭐️ 7.0/10

Zhipu founder Tang Jie announced the 'Touch High' plan, outlining four peaks to AGI: long-term tasks, autonomous agents, self-training, and extreme safety governance, with a massive investment in mechanistic interpretability. This signals a major Chinese AI lab prioritizing AGI over short-term profit, with a strong focus on safety and interpretability, potentially influencing the global AGI race and open-source community. The plan includes heavy investment in mechanistic interpretability to open the black box, while Zhipu's GLM-5.2 model already approaches frontier capabilities; however, it remains a strategic roadmap rather than a breakthrough.

telegram · zaihuapd · Jul 11, 13:59

**Background**: Mechanistic interpretability reverse-engineers neural networks to understand their internal mechanisms, crucial for AI safety. Zhipu is known for its open-source GLM models. The 'Touch High' plan reflects a long-term commitment to AGI research.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mechanistic_interpretability">Mechanistic interpretability - Wikipedia</a></li>
<li><a href="https://arxiv.org/abs/2404.14082">[2404.14082] Mechanistic Interpretability for AI Safety -- A ... AI Interpretability & Explainability: The Complete Guide (2026) What Is Mechanistic Interpretability and Why It Matters Inside AI’s Black Box: How Mechanistic Interpretability ... Understanding Mechanistic Interpretability in AI Models [2501.16496] Open Problems in Mechanistic Interpretability</a></li>

</ul>
</details>

**Tags**: `#AGI`, `#Zhipu`, `#AI safety`, `#open-source`, `#GLM`

---

<a id="item-17"></a>
## [Google opposes EU site blocking, US anti-piracy bills advance](https://torrentfreak.com/google-opposes-site-blocking-in-europe-as-u-s-piracy-blocking-plans-gain-momentum/) ⭐️ 7.0/10

Google submitted a filing to the European Commission opposing expanded site-blocking measures, calling DNS, IP, and VPN blocking ineffective and disproportionate, while the U.S. Congress pushes forward anti-piracy legislation that includes site-blocking proposals. This contrast highlights a potential double standard in Google's stance on content regulation, and the U.S. legislative momentum could lead to significant changes in internet governance and online piracy enforcement. Google cited Italy's anti-piracy system mistakenly blocking Google Drive subdomains and Cloudflare IP addresses that host 42 million domains, and advocated for better legal alternatives over site blocking.

telegram · zaihuapd · Jul 11, 15:10

**Background**: Site blocking often involves DNS resolver blocking, IP address blocking, or VPN blocking to prevent access to pirated content. However, these techniques carry a high risk of overblocking—accidentally blocking legitimate services—as seen in the Italian case. The U.S. previously saw major backlash against similar proposals, such as SOPA/PIPA, over free speech concerns.

<details><summary>References</summary>
<ul>
<li><a href="https://torrentfreak.com/spain-piracy-crisis-cloudflare-says-laliga-knew-danger-blocked-ip-address-anyway-250211/">Piracy Crisis: Cloudflare Says LaLiga Knew Dangers, Blocked ...</a></li>
<li><a href="https://legalblogs.wolterskluwer.com/copyright-blog/fighting-online-piracy-in-2025-expanding-copyright-enforcement-to-new-intermediaries/">Fighting online piracy in 2025: expanding copyright ...</a></li>

</ul>
</details>

**Tags**: `#internet governance`, `#anti-piracy`, `#site blocking`, `#tech policy`, `#Google`

---