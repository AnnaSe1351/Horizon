---
layout: default
title: "Horizon Summary: 2026-07-13 (EN)"
date: 2026-07-13
lang: en
---

> From 61 items, 18 important content pieces were selected

---

1. [Apple SpeechAnalyzer API Benchmarked Against Whisper](#item-1) ⭐️ 8.0/10
2. [Telegram's t.me Domain Suspended](#item-2) ⭐️ 8.0/10
3. [Samsung Health threatens data deletion if users refuse AI training](#item-3) ⭐️ 8.0/10
4. [LAPD ends Flock contract over privacy concerns](#item-4) ⭐️ 8.0/10
5. [Apple Overhauls Mac Chip Roadmap, Skips M6 Pro/Max/Ultra for AI Focus](#item-5) ⭐️ 8.0/10
6. [From Chain of Thought to Latent Reasoning](#item-6) ⭐️ 8.0/10
7. [GPUHedge reduces serverless GPU cold start latency from 117s to 30s](#item-7) ⭐️ 8.0/10
8. [Open-source tool filters arXiv papers daily by research interests](#item-8) ⭐️ 8.0/10
9. [J-space entropy evaluated as error predictor on Qwen3-4B](#item-9) ⭐️ 8.0/10
10. [Climate.gov data rescued by open data community](#item-10) ⭐️ 7.0/10
11. [Technical Deep Dive of Sega CD Silpheed's Visual Tricks](#item-11) ⭐️ 7.0/10
12. [DOOMQL: Doom-like game powered entirely by SQLite](#item-12) ⭐️ 7.0/10
13. [ByteDance Explores Autonomous Driving via Seed World Model Team](#item-13) ⭐️ 7.0/10
14. [Om AI unveils VLX, first edge-native streaming multimodal model](#item-14) ⭐️ 7.0/10
15. [Zero-Difference Cloud Control Raises Hundreds of Millions in C++ Round](#item-15) ⭐️ 7.0/10
16. [Intel invests €5B in Ireland for AI chip production](#item-16) ⭐️ 7.0/10
17. [StepFun Launches STEPX Brand, Agentic OS Step AOS, and Neo Phone](#item-17) ⭐️ 7.0/10
18. [Prompt-Engineering Paper on LLM Diversity Accepted to ICML Sparks Debate](#item-18) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Apple SpeechAnalyzer API Benchmarked Against Whisper](https://get-inscribe.com/blog/apple-speech-api-benchmark.html) ⭐️ 8.0/10

Apple's new SpeechAnalyzer API, introduced at WWDC 2025, has been benchmarked against OpenAI's Whisper, showing competitive speed and accuracy for on-device speech transcription. This could disrupt paid apps that merely wrap Whisper, as Apple may integrate a native recorder app, making transcription faster and more private on Apple devices. Benchmarks indicate SpeechAnalyzer is substantially faster than Whisper-Large-V2 for math lectures with only slightly lower accuracy, making it suitable for live transcription but not yet perfect for offline captions.

hackernews · get-inscribe · Jul 13, 16:06 · [Discussion](https://news.ycombinator.com/item?id=48894752)

**Background**: SpeechAnalyzer is Apple's on-device speech recognition framework introduced at WWDC 2025, replacing older APIs with a modular approach. Whisper is an open-source ASR model by OpenAI trained on 680,000 hours of data, widely used in third-party apps.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Whisper_(speech_recognition_system)">Whisper ( speech recognition system) - Wikipedia</a></li>
<li><a href="https://www.argmaxinc.com/blog/apple-and-argmax">Apple SpeechAnalyzer and Argmax WhisperKit - Argmax</a></li>

</ul>
</details>

**Discussion**: Commenters noted that Whisper is no longer state-of-the-art; models like Nemotron and Voxtral are better. Some predicted the end of paid Whisper wrappers, while a user integrated SpeechAnalyzer into Handy.computer.

**Tags**: `#Speech Recognition`, `#Apple`, `#Benchmarking`, `#Whisper`, `#API`

---

<a id="item-2"></a>
## [Telegram's t.me Domain Suspended](https://www.whois.com/whois/t.me) ⭐️ 8.0/10

Telegram's short URL domain t.me has been placed on serverHold status, effectively suspending its resolution, as shown by a WHOIS lookup. This suspension disrupts Telegram's link redirection service, potentially affecting millions of users who rely on t.me links to access channels and bots, and signals increased regulatory pressure on the platform. The serverHold status indicates that the .me registry (operated by the Government of Montenegro) took this action, not the registrar GoDaddy, which some commenters criticized. The status is often applied during legal disputes or investigations.

hackernews · Tiberium · Jul 13, 19:52 · [Discussion](https://news.ycombinator.com/item?id=48897878)

**Background**: t.me is a domain used by Telegram to create short, memorable links for its channels and bots, such as t.me/channelname. It is separate from the main Telegram domain telegram.org. A domain suspension can occur due to court orders, regulatory requests, or violation of registry policies, making the domain unresolvable and breaking all associated links.

<details><summary>References</summary>
<ul>
<li><a href="https://www.netify.ai/resources/domains/t.me">t . me - Domain Info - Telegram</a></li>

</ul>
</details>

**Discussion**: Commenters expressed surprise that Telegram relied on GoDaddy as a registrar, citing its lack of transparency. Others noted that the serverHold status was likely a registry-level action by the .me registry, possibly triggered by legal investigations in India, France, or Russia. One user mentioned implementing a redirect from t.me to telegram.me as a precaution.

**Tags**: `#telegram`, `#domain suspension`, `#legal`, `#governance`, `#internet`

---

<a id="item-3"></a>
## [Samsung Health threatens data deletion if users refuse AI training](https://neow.in/cWsyMTV3) ⭐️ 8.0/10

Samsung Health will delete users' health data if they decline to allow it to be used for AI training, according to a new policy. The company plans to collect sleep, medication, medical records, and cycle tracking data for AI training. This policy raises significant privacy and consent concerns, forcing users to choose between losing their health data or allowing it to be used for AI training. It could set a precedent for other health apps and wearable devices. The policy covers four categories: sleep, medications, medical records, and cycle tracking. Users who opt out will have their data deleted, potentially rendering many device features unusable.

hackernews · bundie · Jul 13, 20:01 · [Discussion](https://news.ycombinator.com/item?id=48897991)

**Background**: Samsung Health is a health-tracking app that collects data from Galaxy Watch and other devices. AI training uses this data to improve features and algorithms. The policy ties data retention to consent for AI training, a controversial approach.

**Discussion**: Commenters expressed outrage, with some calling it coercive and questioning whether Samsung would refund part of the device price if features become unusable. Others noted that the policy effectively forces users to either share sensitive data or lose it, while one commenter sarcastically saw a benefit in having data deleted to avoid misuse. There were also complaints about Samsung Health's poor usability and ads.

**Tags**: `#privacy`, `#data-deletion`, `#AI-training`, `#Samsung`, `#health-data`

---

<a id="item-4"></a>
## [LAPD ends Flock contract over privacy concerns](https://techcrunch.com/2026/07/13/lapd-lets-contract-with-surveillance-giant-flock-expire-citing-serious-concerns-over-civil-liberties-and-privacy/) ⭐️ 8.0/10

The Los Angeles Police Department (LAPD) has allowed its contract with surveillance company Flock Safety to expire, citing serious concerns over civil liberties and privacy. This decision highlights growing pushback against mass surveillance, but critics warn that Flock's business model allows data collection to continue through resale to other agencies, potentially undermining the LAPD's move. Flock Safety's cameras and poles remain in place after the contract expires, and the company can still sell data to other law enforcement agencies like CHP, LASD, or Palantir, making the surveillance system resilient to political pressure.

hackernews · forks · Jul 13, 15:11 · [Discussion](https://news.ycombinator.com/item?id=48893947)

**Background**: Flock Safety is a US-based company that provides automated license plate recognition (ALPR) cameras, video surveillance, and gunfire detection systems. Its systems are widely used by police departments and homeowners associations, raising privacy concerns because they can track vehicle movements and be shared across agencies without warrants.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Flock_Safety">Flock Safety - Wikipedia</a></li>
<li><a href="https://www.aclu.org/news/privacy-technology/tracking-alpr-cameras/flock-roundup">Flock’s Aggressive Expansions Go Far Beyond Simple Driver Surveillance | American Civil Liberties Union</a></li>
<li><a href="https://www.flocksafety.com/">Flock Safety</a></li>

</ul>
</details>

**Discussion**: Community comments point out that Flock's business model is designed to be resilient: even if one contract ends, cameras continue recording and data can be sold to other agencies, effectively tightening the surveillance net. Some also question the effectiveness of such systems in preventing crime, while others advocate for laws banning government purchase of data that could not be legally collected directly.

**Tags**: `#surveillance`, `#privacy`, `#civil liberties`, `#LAPD`, `#Flock`

---

<a id="item-5"></a>
## [Apple Overhauls Mac Chip Roadmap, Skips M6 Pro/Max/Ultra for AI Focus](https://36kr.com/newsflashes/3894068327759108?f=rss) ⭐️ 8.0/10

Apple is revising its Mac chip roadmap to prioritize AI performance, planning to skip the high-end M6 Pro, M6 Max, and M6 Ultra chips and instead deliver the M7 series directly in 2027, with the M7 Ultra aiming to rival Nvidia's Blackwell-class AI accelerators. This strategic shift indicates Apple's intent to make AI performance a central differentiator for its Mac lineup and potentially build its own AI server chips, challenging Nvidia's dominance in the AI accelerator market. Apple will skip the M6 Pro, Max, and Ultra variants after the base M6 launches this fall; the M7 Ultra is expected in 2028 and may serve as the foundation for Apple's next-generation AI server chips. Additionally, Apple is already researching M8 and beyond, with 2028 products using a 1.4nm process node.

rss · 36kr · Jul 13, 12:51

**Background**: Apple's Mac chips, starting with the M1 in 2020, have historically scaled performance through Pro, Max, and Ultra tiers. Nvidia's Blackwell architecture, introduced in 2024, is a major step in GPU AI acceleration, featuring 208 billion transistors on TSMC's 4NP process. The 1.4nm node (TSMC A14 or Intel's A14) is expected by 2028 and would significantly improve transistor density and efficiency.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Blackwell_(microarchitecture)">Blackwell (microarchitecture) - Wikipedia</a></li>
<li><a href="https://www.nvidia.com/en-us/data-center/technologies/blackwell-architecture/">The Engine Behind AI Factories | NVIDIA Blackwell Architecture</a></li>
<li><a href="https://semiwiki.com/wikis/industry-wikis/tsmc-a14-process-technology-wiki/">TSMC A14 Process Technology Wiki - SemiWiki</a></li>

</ul>
</details>

**Tags**: `#Apple`, `#AI chips`, `#Mac roadmap`, `#M7`, `#Nvidia`

---

<a id="item-6"></a>
## [From Chain of Thought to Latent Reasoning](https://www.reddit.com/r/MachineLearning/comments/1uviru5/chain_of_thought_is_a_scaling_trap_the_next_wave/) ⭐️ 8.0/10

A Reddit post argues that Chain of Thought (CoT) reasoning in LLMs suffers from faithfulness and cost issues, and proposes that the next wave is latent reasoning methods like Coconut, HRM, and RecursiveMAS. This discussion highlights a potential paradigm shift in LLM reasoning from verbose text-based traces to efficient latent-space computation, with significant implications for cost, speed, and interpretability in production systems. The post notes that latent reasoning methods like Coconut use continuous vectors instead of tokens, while HRM separates planning from execution and RecursiveMAS passes latent embeddings between agents, though they introduce a black-box visibility problem.

reddit · r/MachineLearning · /u/meowsterpieces · Jul 13, 17:50

**Background**: Chain of Thought (CoT) prompting makes LLMs generate intermediate reasoning steps in natural language, which improves performance but incurs extra token costs and can produce unfaithful traces. Latent reasoning methods aim to perform reasoning in the hidden state space, outputting language only at the end. Coconut (Chain of Continuous Thought) is one such method from Meta, HRM (Hierarchical Reasoning Model) is a recurrent architecture with deep computational depth, and RecursiveMAS scales latent collaboration among multiple agents.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/sapientinc/HRM">GitHub - sapientinc/HRM: Hierarchical Reasoning Model ...</a></li>
<li><a href="https://arxiv.org/abs/2604.25917">[2604.25917] Recursive Multi-Agent Systems - arXiv.org Images RecursiveMAS · GitHub Recursive Multi-Agent Systems - arXiv.org RecursiveMAS Playground — Recursive Multi-Agent Systems in ... How RecursiveMAS speeds up multi-agent inference by 2.4x and ...</a></li>

</ul>
</details>

**Tags**: `#Chain of Thought`, `#latent reasoning`, `#LLM reasoning`, `#faithfulness`, `#Coconut`

---

<a id="item-7"></a>
## [GPUHedge reduces serverless GPU cold start latency from 117s to 30s](https://www.reddit.com/r/MachineLearning/comments/1uvlb6h/gpuhedge_hedging_serverless_gpu_providers/) ⭐️ 8.0/10

GPUHedge is an open-source tool that uses hedging across multiple serverless GPU providers to reduce p95 cold start latency from 116.6 seconds to 29.4 seconds for a 17 GB AI model. Cold start latency is a critical pain point for serverless GPU inference, often causing requests to take over a minute; this solution demonstrates significant improvement and is open source, making it accessible for real-world deployment. The tool implements a speculative-execution approach: it starts a request on a primary provider, monitors lifecycle state, and conditionally launches a backup request; the first valid result wins, and the losing job is cancelled via the provider's native API.

reddit · r/MachineLearning · /u/Putrid_Construction3 · Jul 13, 19:20

**Background**: Serverless GPU inference allows running AI models without managing infrastructure, but providers suffer from cold starts—delays when loading a model onto a GPU after a period of inactivity. Hedging is a strategy where multiple redundant requests are sent to different providers, and the fastest response is used, reducing the impact of tail latency.

<details><summary>References</summary>
<ul>
<li><a href="https://gpuhosted.com/en/serverless-gpu-inference-guide/">Serverless GPU Inference Guide (2026): Scale to Zero</a></li>
<li><a href="https://en.wikipedia.org/wiki/Speculative_execution">Speculative execution - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#serverless`, `#GPU inference`, `#cold start`, `#hedging`, `#open-source`

---

<a id="item-8"></a>
## [Open-source tool filters arXiv papers daily by research interests](https://www.reddit.com/r/MachineLearning/comments/1uvcdf7/hundreds_of_papers_hit_arxiv_every_day_and_maybe/) ⭐️ 8.0/10

A new open-source tool called Research Radar fetches all new arXiv papers daily, scores their abstracts against a user's research interests, and produces a digest of the most relevant ones using a two-stage LLM pipeline. Researchers waste significant time skimming irrelevant papers; this tool automates filtering with customizable interest files and cost-efficient models, potentially saving hours per week and improving discovery of relevant work. The tool uses a two-pass scoring system: a cheap model scores all abstracts (1-10), then a strong model deep-reads the top scorers' full PDFs to generate summaries. It supports multiple backends including local models via Ollama/vLLM and cloud APIs like Claude.

reddit · r/MachineLearning · /u/usedtobreath · Jul 13, 13:59

**Background**: arXiv is a preprint repository hosting millions of papers across physics, mathematics, computer science, and more, with hundreds of new submissions daily. RSS feeds allow automated retrieval of new paper listings. Researchers often rely on manual browsing or popular newsletters, but these do not personalize to individual research topics.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ArXiv">arXiv - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/RSS_feed">RSS feed</a></li>

</ul>
</details>

**Tags**: `#arxiv`, `#paper filtering`, `#research tool`, `#open-source`, `#NLP`

---

<a id="item-9"></a>
## [J-space entropy evaluated as error predictor on Qwen3-4B](https://www.reddit.com/r/MachineLearning/comments/1uv5l75/evaluating_jspace_entropy_as_an_error_predictor/) ⭐️ 8.0/10

A study evaluated J-space entropy, derived from the Jacobian Lens, as an error predictor on Qwen3-4B across seven datasets totaling ~11,400 examples. This work clarifies the practical utility of internal entropy for LLM error detection, showing it complements output confidence on factual tasks but fails to detect internalized misconceptions, emphasizing task dependence. The evaluation used Qwen3-4B, with datasets including TriviaQA, PopQA, NQ-Open, TruthfulQA, HotpotQA, GSM8K, and CommonSenseQA; a threshold calibrated on TriviaQA failed on GSM8K due to higher baseline entropy for correct math reasoning, and multiple-choice formatting weakened the signal.

reddit · r/MachineLearning · /u/dasjomsyeet · Jul 13, 08:27

**Background**: The Jacobian Lens is an interpretability technique that reads out what an internal activation is disposed to make the model say by linearly projecting residual-stream vectors into the final-layer basis and decoding via the unembedding. J-space entropy refers to the entropy of the vocabulary distribution obtained from this lens at a given layer, hypothesized to indicate uncertainty or errors in the model's internal workspace.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/anthropics/jacobian-lens">GitHub - anthropics/jacobian-lens: Companion code for the ...</a></li>
<li><a href="https://explainx.ai/blog/what-is-j-lens-jacobian-lens-claude-interpretability-2026">What Is the J-Lens? Anthropic Jacobian Lens Guide - explainx.ai</a></li>
<li><a href="https://venturebeat.com/technology/anthropics-new-j-lens-reveals-a-silent-workspace-inside-claude-that-mirrors-a-leading-theory-of-consciousness">Anthropic's new "J-lens" reveals a silent workspace inside ...</a></li>

</ul>
</details>

**Tags**: `#machine learning`, `#interpretability`, `#LLM`, `#error detection`, `#Jacobian Lens`

---

<a id="item-10"></a>
## [Climate.gov data rescued by open data community](https://werd.io/climate-gov-was-destroyed-open-data-saved-it/) ⭐️ 7.0/10

After climate.gov was taken down, volunteers archived its data using open data tools and IPFS, ensuring public access to taxpayer-funded climate information. This event highlights the fragility of government data and the power of open data initiatives to protect public information from political or administrative changes. The archive was hosted on IPFS, a decentralized peer-to-peer file system, but the site relies on donations rather than sustained government funding.

hackernews · benwerd · Jul 13, 19:57 · [Discussion](https://news.ycombinator.com/item?id=48897945)

**Background**: IPFS is a distributed file system that uses content addressing to uniquely identify files, enabling decentralized storage and retrieval. It is designed to create a more resilient web by removing single points of failure. Government websites often serve static content that could benefit from such decentralized archiving.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/InterPlanetary_File_System">InterPlanetary File System - Wikipedia</a></li>
<li><a href="https://ipfs.tech/">IPFS: Building blocks for a better web | IPFS</a></li>

</ul>
</details>

**Discussion**: Commenters debated whether government data should automatically be public domain, and questioned the sustainability of donation-based preservation. Some proposed that government websites should adopt decentralized protocols like IPFS as a default for static content.

**Tags**: `#open-data`, `#climate-data`, `#government-transparency`, `#data-preservation`, `#IPFS`

---

<a id="item-11"></a>
## [Technical Deep Dive of Sega CD Silpheed's Visual Tricks](https://fabiensanglard.net/silpheed/index.html) ⭐️ 7.0/10

Fabien Sanglard published a detailed technical analysis of the Sega CD game Silpheed, explaining how it used Full Motion Video (FMV) and sprite scaling to create a convincing pseudo-3D experience. This deep dive reveals clever engineering solutions that pushed the limits of 16-bit hardware, offering valuable insights for retro game developers and enthusiasts interested in optimization techniques. The article details how Silpheed ran from a single CD track, using pre-rendered backgrounds and scaled sprites to simulate 3D movement, all while maintaining smooth gameplay on the Sega CD's limited hardware.

hackernews · ibobev · Jul 13, 14:52 · [Discussion](https://news.ycombinator.com/item?id=48893639)

**Background**: Full Motion Video (FMV) refers to pre-recorded video clips used in games, popular in the early 1990s due to CD-ROM storage. Sprite scaling is a technique where 2D sprites are resized to create a sense of depth or movement, commonly used in 16-bit console games to simulate 3D effects.

<details><summary>References</summary>
<ul>
<li><a href="https://en.namu.wiki/w/FMV">FMV - NamuWiki</a></li>
<li><a href="https://www.youtube.com/watch?v=Pcd6K0RZDdo">Jurassic Park - 16 Bit Sprite Scaling Dino Action! - YouTube</a></li>

</ul>
</details>

**Discussion**: Commenters expressed admiration for Silpheed's achievement, with one user noting it felt like controlling a movie. Another commenter corrected a detail about the Sega CD's sound setup, while others shared links to impressive demos on similar hardware.

**Tags**: `#retro gaming`, `#sega cd`, `#game development`, `#technical deep-dive`, `#FMV`

---

<a id="item-12"></a>
## [DOOMQL: Doom-like game powered entirely by SQLite](https://simonwillison.net/2026/Jul/13/doomql/#atom-everything) ⭐️ 7.0/10

Peter Gostev used GPT-5.6 Sol to build DOOMQL, a Doom-like first-person shooter where SQLite handles all game mechanics including movement, collision, enemies, combat, and rendering via a recursive CTE ray tracer, all running as a Python terminal script. DOOMQL demonstrates a highly unconventional yet creative use of SQLite as a complete game engine, challenging traditional game development paradigms and showcasing the potential of AI-assisted coding (GPT-5.6 Sol) for experimental projects. The game uses a single SQL query with recursive common table expressions (CTEs) to implement a full ray tracer for rendering. It is packaged as a Python script that can be run with `uv run`, and the underlying SQLite database can be explored interactively using Datasette with a custom HTML/JS app for a real-time minimap.

rss · Simon Willison · Jul 13, 22:34

**Background**: SQLite is a lightweight embedded relational database that supports recursive queries via CTEs. uv is a fast Python package and project manager written in Rust. GPT-5.6 Sol is OpenAI's most capable model for long-horizon cybersecurity tasks, released in July 2026. This project leverages these technologies to push the boundary of what can be done with a database.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/index/previewing-gpt-5-6-sol/">Previewing GPT - 5 . 6 Sol : a next-generation model | OpenAI</a></li>
<li><a href="https://docs.astral.sh/uv/guides/scripts/">Running scripts | uv - Astral</a></li>

</ul>
</details>

**Tags**: `#sqlite`, `#game-development`, `#python`, `#creative-coding`, `#doom`

---

<a id="item-13"></a>
## [ByteDance Explores Autonomous Driving via Seed World Model Team](https://36kr.com/p/3893815451417347?f=rss) ⭐️ 7.0/10

ByteDance is reportedly exploring autonomous driving, led by the Seed world model team under Zhou Chang, focusing on logistics scenarios. However, ByteDance officially denied any immediate plans for a smart driving business. ByteDance's entry could disrupt the autonomous driving landscape with its AI foundation model, computing power, and talent advantages. Autonomous driving is also a key gateway to embodied intelligence and physical AI. Seed is ByteDance's strategic-level foundation model research team established in 2023. Zhou Chang oversees multimodal models, world models, visual generation, and embodied AI. Volcengine already has an automotive business line partnered with Seres.

rss · 36kr · Jul 13, 08:34

**Background**: World models are AI systems that simulate physical dynamics like physics and object interactions, crucial for autonomous driving prediction and planning. Physical AI and embodied intelligence are emerging trends, with autonomous driving seen as one of the earliest commercial applications.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/World_model_(artificial_intelligence)">World model (artificial intelligence) - Wikipedia</a></li>
<li><a href="https://arxiv.org/abs/2501.11260">[2501.11260] A Survey of World Models for Autonomous Driving [2606.03159] NVIDIA OmniDreams: Real-Time Generative World ... Awesome World Models for Autonomous Driving - GitHub Images Top Stories World model (artificial intelligence) - Wikipedia The Waymo World Model: A New Frontier For Autonomous Driving ... Bowen12137/Awesome-World-Models - GitHub World models new driver for auto autonomy - Chinadaily.com.cn</a></li>

</ul>
</details>

**Tags**: `#ByteDance`, `#autonomous driving`, `#world model`, `#AI`, `#Seed`

---

<a id="item-14"></a>
## [Om AI unveils VLX, first edge-native streaming multimodal model](https://36kr.com/p/3893445208717826?f=rss) ⭐️ 7.0/10

Om AI has introduced VLX, the world's first edge-native streaming multi-modal model series for physical AI, which enables closed-loop perception, localization, and decision-making on edge devices. The model processes video continuously like a stream, rather than through discrete frame extraction, allowing autonomous real-time responses. This development is significant as it moves physical AI from cloud-based architectures to edge-native streaming, enabling low-latency, privacy-preserving autonomous systems. It could accelerate adoption in robotics, drones, wearable devices, and security cameras, bridging the gap between AI research and real-world deployment. The VLX model incorporates three interdependent capabilities: Flow (continuous perception), Seek (precise localization), and Go (action decision-making), all operating on the same video stream. Om AI claims the model has completed a commercial closed-loop with revenue in the hundreds of millions, and that it was trained on data from millions of real-world cameras, drones, and robots.

rss · 36kr · Jul 13, 02:39

**Background**: Physical AI refers to AI systems that interact with and understand the physical world, often requiring real-time processing on edge devices. Traditionally, video understanding uses offline frame extraction, but streaming multimodal models process continuous video without waiting for queries. Other approaches in physical AI include VLA (Vision-Language-Action models), world models, and JEPA (Joint Embedding Predictive Architecture), each with different emphases.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Vision–language–action_model">Vision–language–action model - Wikipedia</a></li>
<li><a href="https://www.turingpost.com/p/jepa">What is Joint Embedding Predictive Architecture (JEPA)?</a></li>
<li><a href="https://en.wikipedia.org/wiki/World_model_(artificial_intelligence)">World model (artificial intelligence)</a></li>

</ul>
</details>

**Tags**: `#physical AI`, `#multi-modal model`, `#edge computing`, `#robotics`, `#video understanding`

---

<a id="item-15"></a>
## [Zero-Difference Cloud Control Raises Hundreds of Millions in C++ Round](https://36kr.com/p/3885232033378308?f=rss) ⭐️ 7.0/10

Zero-Difference Cloud Control (Shenzhen) Co., Ltd., a humanoid robot joint component maker, has completed a C++ round of hundreds of millions of yuan led by Tongchuangweiye, with revenue doubling year-over-year in 2025. This funding highlights the shift in the humanoid robotics industry from concept to production, where supply chain bottlenecks for core components like joints are becoming critical. Zero-Difference Cloud Control's modular joint approach and revenue growth signal growing demand for reliable, mass-producible components. The company's eRob series joint modules reduce axial length by 44% and weight by over 20% compared to industry standards, using self-developed encoders and drivers. They aim to address the 'impossible triangle' of humanoid design: balancing flexibility, load capacity, and human-like size.

rss · 36kr · Jul 13, 02:37

**Background**: Humanoid robots require compact, high-torque joints to mimic human motion. Integrated joint modules combine motors, gearboxes, and sensors into a single unit. The industry currently faces a trade-off between dexterity, strength, and size, which Zero-Difference Cloud Control tackles through modular design and precision manufacturing.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Humanoid_robot">Humanoid robot - Wikipedia</a></li>
<li><a href="https://www.cubemars.com/categorys/robot-joint-module">Robot Joint Module – Precision & Flexible Motion for Robots</a></li>

</ul>
</details>

**Tags**: `#Humanoid Robotics`, `#Robotics Components`, `#Venture Capital`, `#Supply Chain`, `#Chinese Tech`

---

<a id="item-16"></a>
## [Intel invests €5B in Ireland for AI chip production](https://36kr.com/newsflashes/3894027379899655?f=rss) ⭐️ 7.0/10

Intel announced a €5 billion additional investment in its Leixlip, Ireland facility to expand advanced chip manufacturing for AI and HPC, focusing on the Intel 3 process node to boost production of Xeon 6 and next-generation Xeon server processors. This investment underscores Intel's commitment to regaining leadership in semiconductor manufacturing and supporting the growing demand for AI and high-performance computing chips. It also strengthens Intel's foundry services, making advanced nodes available to external customers. The €5 billion will upgrade existing wafer fab facilities, install advanced manufacturing equipment, and expand automated production systems. The Intel 3 node is the company's last FinFET process and a key part of its 'five nodes in four years' plan, offering variants like Intel 3-T, 3-E, and 3-PT.

rss · 36kr · Jul 13, 12:09

**Background**: Intel 3 is a semiconductor process node that provides multiple metal interconnect options and is the first advanced node Intel is opening for external foundry customers. Intel Xeon 6 is a server processor family designed for data centers. HPC (High-Performance Computing) refers to the use of supercomputers to solve complex computational problems. The investment is part of Intel's broader strategy to expand global manufacturing capacity.

<details><summary>References</summary>
<ul>
<li><a href="https://baike.baidu.com/item/Intel+3/67443398">Intel 3 - 百度百科</a></li>
<li><a href="https://news.qq.com/rain/a/20240620A0ANPD00">Intel 3 制程详解：性能相比Intel 4 提升18%！_腾讯新闻</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Intel`, `#chip manufacturing`, `#investment`, `#Ireland`

---

<a id="item-17"></a>
## [StepFun Launches STEPX Brand, Agentic OS Step AOS, and Neo Phone](https://36kr.com/newsflashes/3894017412726018?f=rss) ⭐️ 7.0/10

On July 13, 2026, StepFun officially launched the STEPX brand, the world's first large model-native AI terminal brand, along with the Step AOS agentic-native operating system and the STEPX Neo agentic smartphone. This marks a significant step in integrating LLMs directly into consumer hardware and operating systems, potentially reshaping how users interact with AI agents on personal devices. The STEPX Neo is described as the world's first agentic phone powered by the Step AOS, which uses an atomic capability engine to manage AI agents. Step AOS is built to natively support agentic workflows, distinguishing it from traditional mobile OSes.

rss · 36kr · Jul 13, 11:59

**Background**: An agentic operating system orchestrates AI agents, tools, and data, enabling autonomous task execution. A large model-native terminal embeds LLMs directly into the device's core, allowing seamless AI integration. StepFun (Jieyue Xingchen) is a Chinese AI company focusing on large models and agent technologies.

<details><summary>References</summary>
<ul>
<li><a href="https://www.gizmochina.com/2026/07/13/chinese-ai-company-launches-worlds-first-agentic-smartphone/">StepX Neo launches as world's first agentic smartphone with new Step ...</a></li>
<li><a href="https://www.make.com/en/blog/agentic-operating-system">What Is an Agentic Operating System? 2026 Guide | Make</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Operating System`, `#Agentic`, `#Large Language Model`, `#Terminal`

---

<a id="item-18"></a>
## [Prompt-Engineering Paper on LLM Diversity Accepted to ICML Sparks Debate](https://www.reddit.com/r/MachineLearning/comments/1uv1xb3/promptengineering_paper_accepted_to_icml_r/) ⭐️ 7.0/10

A paper titled 'Verbalized Sampling: How to Mitigate Mode Collapse and Unlock LLM Diversity' was accepted to ICML 2025, proposing a simple prompt-engineering technique to improve output diversity in large language models. This acceptance highlights an ongoing tension in the machine learning community about whether prompt-engineering work belongs at top-tier conferences like ICML, potentially reshaping what is considered rigorous ML research. The technique, called 'Verbalized Sampling,' reportedly recovers up to 66% of output diversity without retraining the model, yet lacks rigorous theoretical analysis. The paper's acceptance at ICML suggests a shift toward valuing empirical results even for seemingly simple methods.

reddit · r/MachineLearning · /u/Mean_Revolution1490 · Jul 13, 05:00

**Background**: Mode collapse is a failure mode in generative models where the output lacks diversity, often seen in GANs but also relevant to LLMs. Prompt engineering involves crafting input prompts to guide model behavior. The debate centers on whether such empirically-driven, theoretically-light work meets the bar for top ML conferences.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mode_collapse">Mode collapse - Wikipedia</a></li>
<li><a href="https://www.analyticsvidhya.com/blog/2025/10/verbalized-sampling/">RIP Prompt Engineering: The New Skill is Verbalized Sampling</a></li>
<li><a href="https://www.forbes.com/sites/lanceeliot/2025/11/01/prompt-engineering-newest-technique-is-verbalized-sampling-that-stirs-ai-to-be-free-thinking-and-improve-your-responses/">Prompt Engineering Newest Technique Is Verbalized Sampling ...</a></li>

</ul>
</details>

**Tags**: `#prompt-engineering`, `#ICML`, `#LLM diversity`, `#machine learning`, `#community debate`

---