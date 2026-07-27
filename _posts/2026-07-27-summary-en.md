---
layout: default
title: "Horizon Summary: 2026-07-27 (EN)"
date: 2026-07-27
lang: en
---

> From 73 items, 24 important content pieces were selected

---

1. [Moonshot AI Open-Sources Kimi K3: First 2.8 Trillion Parameter Model](#item-1) ⭐️ 9.0/10
2. [China Starts Mass Production of Domestic DUV Lithography Tools](#item-2) ⭐️ 9.0/10
3. [vLLM v0.26.0 Released with New Model Families and DeepSeek-V4 Optimizations](#item-3) ⭐️ 8.0/10
4. [Anthropic Clarifies Stance on Open-Weights Models](#item-4) ⭐️ 8.0/10
5. [Libsm64 turns Super Mario 64 into a reusable library](#item-5) ⭐️ 8.0/10
6. [Bun's Rust Rewrite Ships in Claude Code, Public Release Delayed](#item-6) ⭐️ 8.0/10
7. [Xiaomi MiMo-V2.5 Tops OpenRouter Global Charts](#item-7) ⭐️ 8.0/10
8. [Solo Benchmark of 6 Frontier LLMs Reveals Left-Leaning Bias](#item-8) ⭐️ 8.0/10
9. [Unpatched RCE Vulnerability in Fastjson2 Affects All Versions](#item-9) ⭐️ 8.0/10
10. [Judge Rejects Google's DMCA Attempt to Block Scraping](#item-10) ⭐️ 7.0/10
11. [Forum Project Drops React for HTMX, Sparks Debate](#item-11) ⭐️ 7.0/10
12. [Paged Out #9: Free Hacker Magazine Released](#item-12) ⭐️ 7.0/10
13. [Modern email can be built from borrowed parts](#item-13) ⭐️ 7.0/10
14. [Ethan Mollick's AI Tool Guide Shifts to Agentic Systems](#item-14) ⭐️ 7.0/10
15. [Tsinghua PhD Startup Raises Millions for Aviation Hydrogen Fuel Cells](#item-15) ⭐️ 7.0/10
16. [Capital Shifts Focus to Commercialization for AI Apps in 2026](#item-16) ⭐️ 7.0/10
17. [World's largest eVTOL cargo drone AT8000 fuselage completed](#item-17) ⭐️ 7.0/10
18. [Digital Space One experimental satellite project launched to build AI-driven space brain](#item-18) ⭐️ 7.0/10
19. [Ctrip fined $5.1B; ChangXin Memory IPO; Japan admits China leads in humanoid robots](#item-19) ⭐️ 7.0/10
20. [Transformer from Scratch: English-to-Tamil Translation Tutorial](#item-20) ⭐️ 7.0/10
21. [Proposing a deterministic pre-training data audit gate](#item-21) ⭐️ 7.0/10
22. [Google Gemini 4: Most Ambitious Pre-training, Expected Late 2026](#item-22) ⭐️ 7.0/10
23. [Alibaba Launches 'Qianwen Office' AI Platform](#item-23) ⭐️ 7.0/10
24. [China Rebuts US Sanctions Threat Over AI Model Distillation](#item-24) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Moonshot AI Open-Sources Kimi K3: First 2.8 Trillion Parameter Model](https://huggingface.co/moonshotai/Kimi-K3) ⭐️ 9.0/10

Moonshot AI has open-sourced Kimi K3 on Hugging Face, a 2.8 trillion parameter Mixture-of-Experts model with 104 billion active parameters, achieving top-tier benchmark results. It introduces novel architectures including Kimi Delta Attention (KDA) and Attention Residuals (AttnRes), built on the Stable LatentMoE framework. Kimi K3 is the first open-source model at the 3-trillion-parameter scale, marking a major milestone in open-source AI. It narrows the gap with proprietary frontier models like GPT-5.6 Sol and Claude Fable 5, and offers a powerful, deployable alternative for the research and development community. The model uses 896 experts with 16 active per token, achieving approximately 2.5x scaling efficiency over Kimi K2. It natively supports text, image, and video understanding with a 1-million-token context window and supports MXFP4 quantization for efficient deployment.

telegram · zaihuapd · Jul 27, 15:15

**Background**: Kimi K3 is built on the Mixture-of-Experts (MoE) architecture, which activates only a subset of parameters per token to balance performance and efficiency. Kimi Delta Attention (KDA) is an efficient linear attention mechanism that extends Gated DeltaNet, while Attention Residuals (AttnRes) allow layers to selectively aggregate information from previous layers via learned attention weights. Stable LatentMoE introduces latent-space routing and quantile balancing for stable expert utilization.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2510.26692">[2510.26692] Kimi Linear: An Expressive, Efficient Attention Architecture</a></li>
<li><a href="https://www.kimi.com/blog/kimi-k3">Kimi K3 Tech Blog: Open Frontier Intelligence</a></li>

</ul>
</details>

**Tags**: `#open-source`, `#large language model`, `#Moonshot AI`, `#Mixture of Experts`, `#AI breakthrough`

---

<a id="item-2"></a>
## [China Starts Mass Production of Domestic DUV Lithography Tools](https://www.theinformation.com/articles/china-starts-mass-producing-homegrown-duv-chipmaking-tools-advance-local-chip-industry) ⭐️ 9.0/10

China has begun mass-producing domestically developed immersion deep ultraviolet (DUV) lithography tools, with a target of 5 units this year and 20 units by 2027, to be delivered to domestic chipmakers like SMIC and Hua Hong Semiconductor. This breakthrough challenges ASML's near-monopoly in DUV lithography and strengthens China's semiconductor self-sufficiency, with potential geopolitical and market implications as Western export controls tighten. The domestic tools rely mostly on Chinese components, though some critical parts still come from Japan, and local supply chain delays have affected progress this year. Chipmakers will need months to test precision and compatibility before mass production.

telegram · zaihuapd · Jul 27, 14:10

**Background**: DUV lithography uses deep ultraviolet light (e.g., 193nm ArF lasers) to pattern circuits on silicon wafers. Immersion lithography, a key enhancement, places a liquid (typically water) between the lens and wafer to improve resolution, enabling nodes below 45nm. ASML currently dominates the advanced lithography market.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DUV_lithography">DUV lithography</a></li>
<li><a href="https://en.wikipedia.org/wiki/Immersion_lithography">Immersion lithography</a></li>
<li><a href="https://www.asml.com/news/stories/2023/how-immersion-lithography-saved-moores-law">How immersion lithography saved Moore’s Law</a></li>

</ul>
</details>

**Tags**: `#semiconductor`, `#lithography`, `#China`, `#ASML`, `#DUV`

---

<a id="item-3"></a>
## [vLLM v0.26.0 Released with New Model Families and DeepSeek-V4 Optimizations](https://github.com/vllm-project/vllm/releases/tag/v0.26.0) ⭐️ 8.0/10

vLLM v0.26.0 introduces support for the new Inkling model family with full stack including piecewise CUDA graph and Hopper FA4 relative attention, and delivers substantial performance improvements for DeepSeek-V4 across GPU vendors. This release strengthens vLLM as a leading open-source LLM inference engine by optimizing for cutting-edge models like DeepSeek-V4 and enabling new model architectures, which benefits the entire AI inference ecosystem. The release includes 411 commits from 212 contributors, with notable features such as fp32 lm_head for generation models, flexible attention backends per KV-cache group, matured KV offloading and tiered secondary storage, and a Rust frontend gaining multimodal video and audio support.

github · khluu · Jul 27, 01:06

**Background**: vLLM is an open-source library for high-throughput LLM inference. Piecewise CUDA graph is a technique that splits the model's computation into pieces to allow CUDA graph capture for variable-length sequences, improving performance. NVFP4 quantization is a 4-bit floating point format for model weights, reducing memory usage while maintaining accuracy.

<details><summary>References</summary>
<ul>
<li><a href="https://www.spheron.network/blog/tensorrt-model-optimizer-modelopt-quantization-guide/">NVIDIA TensorRT Model Optimizer (ModelOpt): FP8, INT4, and FP4 Quantization Guide (2026) | Spheron Blog</a></li>
<li><a href="https://docs.sglang.io/docs/advanced_features/piecewise_cuda_graph">Piecewise CUDA Graph - SGLang Documentation</a></li>
<li><a href="https://docs.vllm.ai/en/stable/design/cuda_graphs/">CUDA Graphs - vLLM</a></li>

</ul>
</details>

**Tags**: `#vLLM`, `#LLM inference`, `#performance optimization`, `#open source`, `#DeepSeek`

---

<a id="item-4"></a>
## [Anthropic Clarifies Stance on Open-Weights Models](https://www.anthropic.com/news/position-open-weights-models) ⭐️ 8.0/10

Anthropic released a blog post stating it has never advocated for banning open-weights models, but instead proposes mandatory safety testing for all sufficiently capable models and measures to crack down on industrial-scale distillation. This clarification could shape AI regulation debates by distinguishing between open-weights access and safety requirements, affecting both open-source communities and proprietary AI developers. Anthropic's proposals include mandatory safety testing for 'all sufficiently capable models,' both open and closed, and cracking down on distillation operations that extract knowledge from proprietary models.

hackernews · surprisetalk · Jul 27, 22:03 · [Discussion](https://news.ycombinator.com/item?id=49076057)

**Background**: Open-weights models release the trained neural network weights, allowing anyone to run them locally, but are often confused with fully open-source models. Knowledge distillation transfers capabilities from a large model to a smaller one, which can lower barriers to deployment but also raise concerns about misuse. Anthropic's position sits at the center of a tension between open access and safety regulation.

<details><summary>References</summary>
<ul>
<li><a href="https://promptmetheus.com/resources/llm-knowledge-base/open-weights-model">Open - weights Model | LLM Knowledge Base</a></li>
<li><a href="https://www.analyticsvidhya.com/blog/2025/04/open-weight-models/">What are Open Source and Open Weight Models ? | Analytics Vidhya</a></li>
<li><a href="https://en.wikipedia.org/wiki/Knowledge_distillation">Knowledge distillation - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters widely criticized Anthropic's position, arguing that mandatory safety testing effectively bans open-weights models by creating costly regulatory barriers. Some noted the hypocrisy given Anthropic's own copyright lawsuit, while others questioned the feasibility of proposed measures without clear criteria.

**Tags**: `#AI safety`, `#open-source`, `#regulation`, `#Anthropic`, `#open-weights`

---

<a id="item-5"></a>
## [Libsm64 turns Super Mario 64 into a reusable library](https://github.com/libsm64/libsm64) ⭐️ 8.0/10

The libsm64 project extracts the core game logic and character of Super Mario 64 into a shared library, allowing developers to embed Mario into any game engine that can load a C library. This opens up creative cross-game mashups and showcases the power of reverse engineering and decompilation, enabling Mario to appear in games like Half-Life 2 without authorization from Nintendo. The library exposes a minimal API defined in libsm64.h; client projects only need to include that header and load the shared library. The project relies on the prior complete decompilation of Super Mario 64.

hackernews · klaussilveira · Jul 27, 10:04 · [Discussion](https://news.ycombinator.com/item?id=49067352)

**Background**: Super Mario 64 was originally released in 1996 for the Nintendo 64. In 2019, a community-led effort successfully decompiled the game's source code from its original machine code, producing a C-readable codebase. libsm64 builds on that decompilation to package the game's player character as a portable library.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/libsm64/libsm64">GitHub - libsm64/libsm64: Mario 64 as a library for use in external game engines · GitHub</a></li>

</ul>
</details>

**Discussion**: Commenters were highly enthusiastic, with one calling it 'one of my favorite libraries from the premise alone.' Examples of Mario in Half-Life 2 and other demos were shared. Some joked about selling it as a service, while others noted it realizes the promise of interoperable game assets without blockchain hype.

**Tags**: `#reverse-engineering`, `#game-development`, `#open-source`, `#nintendo-64`, `#libraries`

---

<a id="item-6"></a>
## [Bun's Rust Rewrite Ships in Claude Code, Public Release Delayed](https://lockwood.dev/ai/2026/07/27/how-is-the-bun-rewrite-in-rust-going.html) ⭐️ 8.0/10

Bun's creator Jarred announced that the Rust rewrite of Bun has shipped in Claude Code over a month ago, but the public release is delayed until compatibility goals with Node.js are met. This update shows significant progress in Bun's performance and compatibility efforts, as the Rust rewrite is production-ready in a major tool like Claude Code. The delay highlights the project's commitment to stability, which matters for developers relying on Bun. The Rust rewrite was promised to pass a certain number of new Node.js tests in the Bun v1.4 video, but that number hasn't been reached yet. Pull requests to achieve it are pending, and the public release is expected next Tuesday.

hackernews · tomlockwood · Jul 27, 11:12 · [Discussion](https://news.ycombinator.com/item?id=49067854)

**Background**: Bun is a fast JavaScript runtime and toolkit designed as a drop-in replacement for Node.js. Its original core was written in Zig, but the team decided to rewrite it in Rust for better performance and ecosystem integration. Claude Code is Anthropic's AI coding agent that helps developers understand and edit codebases.

<details><summary>References</summary>
<ul>
<li><a href="https://claude.com/product/claude-code">Claude Code by Anthropic | AI Coding Agent, Terminal, IDE</a></li>
<li><a href="https://docs.anthropic.com/en/docs/claude-code/overview">Claude Code overview - Anthropic</a></li>

</ul>
</details>

**Discussion**: Community comments show cautious optimism: some note the rewrite is a major undertaking and expect a slower development pace, while others question whether the rewrite was necessary, pointing to a Zig fork that claims better performance. There is also discussion about the role of LLMs in the translation process.

**Tags**: `#Bun`, `#Rust`, `#rewrite`, `#JavaScript`, `#performance`

---

<a id="item-7"></a>
## [Xiaomi MiMo-V2.5 Tops OpenRouter Global Charts](https://36kr.com/newsflashes/3913798998201732?f=rss) ⭐️ 8.0/10

On July 27, OpenRouter data showed Xiaomi's MiMo-V2.5 model ranked first in both weekly and monthly global LLM call volumes, becoming the only model to exceed 10T tokens in a single week. Since May, its weekly token volume surged from 1.46T to 10.46T, a growth of approximately 616% in two months. This milestone highlights the rapid adoption and competitive performance of Xiaomi's self-developed model, signaling that Chinese AI companies are making significant inroads in global LLM deployment. It also validates the growing demand for high-volume, cost-efficient model inference via unified API platforms like OpenRouter. MiMo-V2.5 is a native omnimodal model supporting text, image, video, and audio understanding, built on the MiMo-V2-Flash backbone. The model underwent a five-stage training pipeline including text pre-training, multimodal pre-training, supervised fine-tuning with progressive context window extension (32K to 1M), and reinforcement learning with MOPD.

rss · 36kr · Jul 27, 11:22

**Background**: OpenRouter is a unified API interface that connects users to hundreds of AI models through a single endpoint, acting as a reverse proxy and routing layer for request translation and provider selection. Token calls refer to the units of data processed by AI models; the number of tokens called indicates the volume of inference usage. High token call volumes often reflect a model's popularity and cost-effectiveness among developers and enterprises.

<details><summary>References</summary>
<ul>
<li><a href="https://mimo.xiaomi.com/mimo-v2-5">MiMo-V2.5 | Xiaomi</a></li>
<li><a href="https://huggingface.co/XiaomiMiMo/MiMo-V2.5">XiaomiMiMo/MiMo-V2.5 · Hugging Face</a></li>

</ul>
</details>

**Tags**: `#AI`, `#LLM`, `#Xiaomi`, `#OpenRouter`, `#model deployment`

---

<a id="item-8"></a>
## [Solo Benchmark of 6 Frontier LLMs Reveals Left-Leaning Bias](https://www.reddit.com/r/MachineLearning/comments/1v8fnzw/evaluated_6_frontier_llms_gpt54_claude_sonnet_46/) ⭐️ 8.0/10

An independent researcher evaluated six frontier LLMs (GPT-5.4, Claude Sonnet 4.6, Claude Opus 4.7, Gemini Pro/Flash, Grok 4.3) across eight bias benchmarks with ~20,600 examples, finding consistent left-leaning political bias in all models and notable refusal rates on race-related questions. This study provides a comprehensive, independent check on political and social biases in leading LLMs, highlighting that even models like Grok which self-identify as right-leaning behave left-leaning in practice. It underscores the need for transparent bias auditing and careful deployment of these models in sensitive applications. Notably, GPT-5.4 refused 20.3% of race-related BBQ questions, while Claude Opus 4.7 refused 13.8%, Grok 9.5%, and Claude Sonnet 4.6 and Gemini Pro around 5%. The study is non-peer-reviewed, uses single prompt templates, and lacks multi-run averaging, limiting statistical generalizability.

reddit · r/MachineLearning · /u/marggggggggg · Jul 27, 22:37

**Background**: Bias benchmarks like WinoBias (gender bias in coreference), BBQ (social bias in QA), and SeeGULL (stereotype dataset) are standardized tools to evaluate fairness in LLMs. The Political Compass and other political bias datasets measure ideological alignment. Refusal rates indicate when a model avoids answering a question that might reveal bias, which itself can be a form of bias.

<details><summary>References</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/winobias">WinoBias : Gender Bias in Coreference Benchmark</a></li>
<li><a href="https://ukgovernmentbeis.github.io/inspect_evals/evals/bias/bbq/index.html">BBQ : Bias Benchmark for Question Answering</a></li>
<li><a href="https://github.com/google-research-datasets/seegull">GitHub - google-research-datasets/seegull: SeeGULL is a broad-coverage stereotype dataset in English containing stereotypes about identity groups spanning 178 countries across 8 different geo-political regions across 6 continents, as well as state-level identities within the US and India. · GitHub</a></li>

</ul>
</details>

**Tags**: `#LLM bias`, `#benchmarking`, `#political bias`, `#fairness`, `#frontier models`

---

<a id="item-9"></a>
## [Unpatched RCE Vulnerability in Fastjson2 Affects All Versions](https://mp.weixin.qq.com/s/LJaul1jNjK9pXRAkoUiMEA) ⭐️ 8.0/10

On July 27, Chaitin Tech disclosed a remote code execution vulnerability in Fastjson2 that allows attackers to bypass AutoType validation and execute code via malicious JSON data, affecting all versions up to 2.0.62. No official patch has been released. Fastjson2 is a widely-used JSON library in Java; this critical RCE vulnerability poses a severe security risk, and users are advised to immediately disable AutoType. The full vulnerability details and exploit code have not been disclosed, but the maintainer has confirmed the issue. This is the second serious Fastjson vulnerability this month following Fastjson1.

telegram · zaihuapd · Jul 27, 10:31

**Background**: Fastjson is an open-source Java JSON library by Alibaba. Its AutoType feature allows JSON to carry type information for automatic type identification during deserialization. However, malicious JSON data can exploit AutoType to achieve remote code execution. Similar vulnerabilities have been found in Fastjson1 (e.g., versions ≤1.2.80). AutoType is disabled by default but some users enable it for functionality.

<details><summary>References</summary>
<ul>
<li><a href="https://alibaba.github.io/fastjson2/autotype_cn.html">FASTJSON 2 Autotype 机制介绍 | fastjson 2</a></li>
<li><a href="https://github.com/alibaba/fastjson2/wiki/Security-Advisory:-Remote-Code-Execution-in-fastjson-1.2.68–1.2.83">Security Advisory: Remote Code Execution in fastjson 1.2.68–1.2.83</a></li>
<li><a href="https://juejin.cn/post/7104159627360600095">Fastjson反序列化 远 程 代 码 执 行 漏 洞 产生 原 因及修复建议Fastjason...</a></li>

</ul>
</details>

**Tags**: `#Fastjson2`, `#RCE`, `#vulnerability`, `#security`, `#Java`

---

<a id="item-10"></a>
## [Judge Rejects Google's DMCA Attempt to Block Scraping](https://www.techdirt.com/2026/07/27/judge-rejects-googles-attempt-to-dmca-its-way-out-of-being-scraped/) ⭐️ 7.0/10

A federal judge ruled that Google cannot use the Digital Millennium Copyright Act (DMCA) to prevent third parties from scraping its search results, affirming that search results are not copyrightable. This ruling sets a significant precedent for data scraping, potentially limiting large tech companies' ability to use copyright law to block competition and data access. It also clarifies that search result listings, which are factual compilations, generally lack the originality required for copyright protection. The case involved Google suing SerpAPI, a company that scrapes Google search results for third-party clients. The judge rejected Google's argument that scraping constitutes DMCA anti-circumvention, as search results are not original works of authorship.

hackernews · cdrnsf · Jul 27, 18:15 · [Discussion](https://news.ycombinator.com/item?id=49073513)

**Background**: The DMCA prohibits circumvention of technological measures that control access to copyrighted works. Google argued that its search results are copyrighted and that scraping bypasses its technological protections. However, courts have long held that factual compilations like phone directories or search results require a minimal degree of creativity to be copyrightable, which Google's algorithmic listings generally lack.

**Discussion**: Commenters largely celebrated the ruling, criticizing Google for using copyright law to stifle competition and noting the lack of a legitimate API. Some raised concerns about differing copyright protections in the EU versus the US, and the practical necessity of scraping to expose scams like fake ESTA websites.

**Tags**: `#scraping`, `#DMCA`, `#Google`, `#legal`, `#copyright`

---

<a id="item-11"></a>
## [Forum Project Drops React for HTMX, Sparks Debate](https://misago-project.org/t/removing-reactjs-from-the-codebase-and-adapting-htmx-for-ui-interactivity/1267/) ⭐️ 7.0/10

The Misago forum project announced it is removing React.js from its codebase and adapting HTMX for UI interactivity, reflecting a shift towards simpler, server-driven frontend approaches. This decision highlights a growing trend among developers to move away from heavy client-side JavaScript frameworks in favor of lightweight, hypermedia-based libraries for content-heavy sites like forums. HTMX is a small, dependency-free library (~14k min.gz'd) that allows developers to add AJAX, CSS Transitions, WebSockets, and Server Sent Events directly via HTML attributes, eliminating the need for a full JavaScript framework.

hackernews · Ralfp · Jul 27, 09:58 · [Discussion](https://news.ycombinator.com/item?id=49067301)

**Background**: React.js is a popular JavaScript library for building user interfaces, often used for single-page applications (SPAs). However, for content-focused sites like forums, where most content is non-interactive text, a full SPA framework may be overcomplicated. HTMX, inspired by intercooler.js, enables dynamic updates without writing custom JavaScript, aligning with the principles of hypertext and server-side rendering.

<details><summary>References</summary>
<ul>
<li><a href="https://htmx.org/">htmx - high power tools for html</a></li>
<li><a href="https://en.wikipedia.org/wiki/Htmx">htmx - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters generally support the move, with many praising HTMX's simplicity for forum software. However, one user reported performance issues when HTMX sent large HTML responses, and another recommended server-driven alternatives like PyView. Overall, the sentiment is positive but with practical caveats.

**Tags**: `#HTMX`, `#React`, `#server-side rendering`, `#web development`, `#frontend frameworks`

---

<a id="item-12"></a>
## [Paged Out #9: Free Hacker Magazine Released](https://pagedout.institute/download/PagedOut_009.pdf) ⭐️ 7.0/10

Paged Out #9, a free and beautifully designed hacker magazine, has been released as a PDF, featuring deep technical articles and creative content reminiscent of classic hacker zines. This release is significant for the hacker community as it revives the spirit of iconic zines like 2600 and Phrack, offering a modern platform for highly technical and curious content. Notable articles include 'Baby Steps in C' (humorous), 'The Subpixel Zoo' on subpixel rendering, and an uncredited rediscovery of Wang's work on computable tilings linking the domino problem to the halting problem.

hackernews · laurensr · Jul 27, 14:22 · [Discussion](https://news.ycombinator.com/item?id=49070138)

**Background**: Paged Out is a free, community-driven hacker magazine that aims to capture the essence of classic zines like 2600 and Phrack. It covers a wide range of technical topics including programming, retro computing, and hacking, often with a creative and hands-on approach. The magazine is known for its beautiful design and deep technical content, appealing to hackers and tech enthusiasts.

**Discussion**: Commenters praised the magazine as a modern 2600/Phrack, with one calling it 'beautifully designed' and 'deeply technical'. Technical insights included discussion of the computable tilings piece linking to Wang's 1960s work and the domino problem's equivalence to the halting problem, as well as interest in subpixel rendering for text.

**Tags**: `#hacker magazine`, `#technical articles`, `#computing history`, `#programming`, `#retro computing`

---

<a id="item-13"></a>
## [Modern email can be built from borrowed parts](https://en.andros.dev/blog/d7ed8b07/modern-email-can-be-built-from-borrowed-parts/) ⭐️ 7.0/10

A proposal suggests rebuilding email using modern components from other protocols, sparking debate on spam, cost, and migration paths. Email remains a critical communication backbone, and any modernization could affect billions of users. The proposal highlights challenges of spam, economic models, and network effects that have hindered previous attempts. The proposal leverages existing improvements like JMAP, MTA-STS, and ARC to address SMTP's shortcomings. However, community comments emphasize the need for backward compatibility and a migration path to overcome network effects.

hackernews · andros · Jul 27, 08:27 · [Discussion](https://news.ycombinator.com/item?id=49066639)

**Background**: Email relies on the decades-old SMTP protocol, which lacks built-in encryption and authentication. Modern extensions like JMAP replace IMAP for client-server communication, MTA-STS improves server-to-server encryption, and ARC preserves authentication across forwarding chains.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/JSON_Meta_Application_Protocol">JSON Meta Application Protocol - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/MTA-STS">MTA-STS</a></li>
<li><a href="https://easydmarc.com/blog/arc-email-authentication-what-it-is-and-how-it-works/">ARC Email Authentication Explained | EasyDMARC</a></li>

</ul>
</details>

**Discussion**: Commenters like teddyh warn about history repeating with unworkable spam solutions, while BeetleB proposes economic disincentives for spam. Others, like rbanffy, note that email's resilience may indicate the stack is not as broken as claimed. jerf's truncated comment likely advises reconsidering the current setup.

**Tags**: `#email`, `#protocols`, `#spam`, `#SMTP`, `#modernization`

---

<a id="item-14"></a>
## [Ethan Mollick's AI Tool Guide Shifts to Agentic Systems](https://simonwillison.net/2026/Jul/27/an-opinionated-guide-to-which-ai-to-use-to-do-stuff/#atom-everything) ⭐️ 7.0/10

Ethan Mollick updated his opinionated guide on which AI tools to use, emphasizing a shift from chat-based models like ChatGPT and Claude to agentic systems that can perform hours of human work autonomously. This reflects a broader industry trend towards more autonomous AI agents, which could significantly boost productivity for knowledge workers by automating complex, multi-step tasks. Notably, Gemini has been dropped from the list as Google lacks an established entry in the Codex/ChatGPT Work/Cowork category, and Gemini Spark has yet to prove itself. The guide explains the confusing naming of modes like ChatGPT Work and Claude Cowork, which operate differently on desktop vs. mobile.

rss · Simon Willison · Jul 27, 21:55

**Background**: Agentic AI systems are AI agents that can pursue goals, use tools, and take actions with varying degrees of autonomy, unlike traditional AI models that require human intervention. Deep Research tools, like OpenAI's, can conduct online research autonomously. Google's Gemini Spark is a 24/7 AI agent that integrates with Google services but requires no technical setup.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AI_agent">AI agent - Wikipedia</a></li>
<li><a href="https://www.ibm.com/think/topics/agentic-ai">What is Agentic AI? | IBM</a></li>
<li><a href="https://mitsloan.mit.edu/ideas-made-to-matter/agentic-ai-explained">Agentic AI, explained | MIT Sloan</a></li>

</ul>
</details>

**Tags**: `#AI`, `#LLMs`, `#agentic systems`, `#tools`

---

<a id="item-15"></a>
## [Tsinghua PhD Startup Raises Millions for Aviation Hydrogen Fuel Cells](https://36kr.com/p/3913736066028932?f=rss) ⭐️ 7.0/10

Chinese startup Yiqing Power, founded by Tsinghua University PhDs, has raised tens of millions of yuan in an angel+ round led by Redbird Qihang Fund and Guizhou Science & Technology Innovation Angel Fund. The funds will be used to develop aviation-grade liquid-cooled fuel cells and commercialize air-cooled fuel cells for drones and eVTOL aircraft. This funding signals growing interest in hydrogen aviation in China, a sector that lags behind automotive fuel cells. Yiqing Power's technology could enable long-range eVTOL 'air taxis' and high-endurance drones, potentially disrupting the low-altitude economy. Yiqing Power has developed a 30kW liquid-cooled fuel cell system (now iterated to 90-110kW) and air-cooled systems for drones. It has become a supplier to COMAC and partners with eVTOL OEMs. The air-cooled products have already generated millions in revenue in 2025 for drone inspection applications.

rss · 36kr · Jul 27, 10:19

**Background**: Hydrogen fuel cells produce electricity through an electrochemical reaction, offering high energy density and fast refueling compared to batteries. In aviation, hydrogen is seen as a potential zero-emission solution for eVTOL and drones, where battery limitations in range and cold weather are critical. Global efforts include Europe's early research and China's recent push under the low-altitude economy policy.

<details><summary>References</summary>
<ul>
<li><a href="https://www.163.com/dy/article/L2S6ANCQ05118DFD.html">清华博士团队创业，这家公司要给飞机做氢能「心脏」｜36氪首发</a></li>
<li><a href="https://en.wikipedia.org/wiki/EVTOL">eVTOL - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#hydrogen fuel cell`, `#aviation`, `#clean energy`, `#startup funding`, `#Tsinghua University`

---

<a id="item-16"></a>
## [Capital Shifts Focus to Commercialization for AI Apps in 2026](https://36kr.com/p/3913706151400583?f=rss) ⭐️ 7.0/10

Venture capital is shifting its evaluation criteria for AI applications from user scale (DAU) to commercialization quality, with companies like Kimi abandoning DAU targets and focusing on Agent products. This change is exemplified by Haiyi (SeaArt), which reported gross margins over 40% and a 60%+ renewal rate, attracting significant funding. This marks a turning point for the AI industry, as high user numbers alone no longer guarantee valuation; sustainable profitability and high retention are now key. It could reshape which AI startups survive and thrive, favoring those with strong business models over those chasing scale. Kimi's valuation surged 6x in six months to $30 billion target while deprioritizing DAU. Character.AI lost 8 million MAUs after a peak of 28 million, and Inflection AI pivoted after burning $1.3 billion, illustrating the failure of scale-first strategies.

rss · 36kr · Jul 27, 09:48

**Background**: In the AI application layer, the prevailing strategy from 2023 to 2025 was to use subsidies on compute to acquire users rapidly, mirroring internet-era 'land-grab' tactics. However, high compute costs and poor retention revealed that DAU alone cannot sustain margins. The concept of AI Agents—autonomous systems that perceive, reason, and act—has become a new focus, as seen in Kimi's pivot. Haiyi, a Chengdu-based company, built a multi-modal creation community, AI short drama platform, and character interaction product, achieving high margins through reusable capability modules.

<details><summary>References</summary>
<ul>
<li><a href="https://www.techbang.com/posts/131321-moonshot-ai-kimi-k3-2-8-trillion-parameter-open-model">Moonshot AI 發布全球首款 2.8 兆參數開放 模 型 Kimi ... | T客邦</a></li>
<li><a href="https://en.wikipedia.org/wiki/AI_agent">AI agent</a></li>
<li><a href="https://www.53ai.com/news/neirongchuangzuo/2025021575931.html">AI Agent ... - 53 AI - AI 知识库|大模型知识库|大模型训练|智能体开发</a></li>

</ul>
</details>

**Tags**: `#AI applications`, `#venture capital`, `#commercialization`, `#Kimi`, `#Agent`

---

<a id="item-17"></a>
## [World's largest eVTOL cargo drone AT8000 fuselage completed](https://36kr.com/p/3912369056240772?f=rss) ⭐️ 7.0/10

Chinese company Muyutian Aviation announced the fuselage completion of its AT8000, the world's largest eVTOL cargo drone, with an 8-ton maximum takeoff weight. This milestone positions China as a leader in heavy-lift low-altitude logistics, potentially transforming cargo delivery by enabling 1000 km range and 3.5-ton payload for time-sensitive or remote-area transport. The AT8000 uses a semi-tilt hybrid propulsion architecture with 18 lift rotors (4 tilting) and 2 pusher rotors, a cruising speed of 252 km/h, and all-composite construction with fully proprietary technology.

rss · 36kr · Jul 27, 08:23

**Background**: eVTOL (electric vertical takeoff and landing) aircraft are designed to operate like helicopters for takeoff and landing but transition to fixed-wing flight for efficiency. The low-altitude economy refers to the use of airspace below 1000 meters for commercial activities such as cargo drones and air taxis. Semi-tilt hybrid propulsion combines fixed lift rotors with tilting rotors to balance vertical lift and forward thrust.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/EVTOL">eVTOL - Wikipedia</a></li>
<li><a href="https://www.embention.com/embention-uam-academy/lesson/types-and-architectures-of-evtol-aircraft/">eVTOL Types and Architectures | Embention UAM Academy</a></li>
<li><a href="https://www.grepow.com/blog/what-is-low-altitude-economy.html">What Are Low Altitude Economy and Low - Altitude Aircrafts | Grepow</a></li>

</ul>
</details>

**Tags**: `#eVTOL`, `#heavy-lift drone`, `#low-altitude economy`, `#cargo logistics`, `#aviation`

---

<a id="item-18"></a>
## [Digital Space One experimental satellite project launched to build AI-driven space brain](https://36kr.com/p/3912546487637378?f=rss) ⭐️ 7.0/10

On July 26, the Digital Space One experimental satellite project was officially launched in Beijing, aiming to validate an on-orbit AI 'space brain' architecture that enables autonomous satellite constellation management. As satellite numbers surge past tens of thousands, traditional ground-based command and control becomes unsustainable; this project could pioneer the autonomous, brain-like operation needed for future large constellations, shifting China's space industry from 'can launch' to 'can manage well'. The satellite will test a 'perception-cognition-action' intelligent closed loop that integrates space sensing, cognitive reasoning, and behavioral decisions entirely onboard, achieving millisecond-level autonomy. A physical-world model is used as the foundation to avoid the black-box and hallucination issues of large language models in aerospace applications.

rss · 36kr · Jul 27, 01:00

**Background**: Commercial aerospace in China has achieved the first stage of 'can build and launch', but as orbital resources become crowded, managing large constellations with legacy ground-based control is failing. The 'Space Brain' concept, proposed by Academician Wei Fengsi, envisions satellites with onboard intelligence similar to bird flocks, enabling autonomous collision avoidance and environment adaptation.

<details><summary>References</summary>
<ul>
<li><a href="http://www.maqu.gov.cn/info/1043/1940.htm">我国成功发射微厘 空 间 一 号 试 验 卫 星 -玛曲县人民政府</a></li>
<li><a href="https://min.news/zh-hans/tech/b7a4da51b797351c8113a6d006842c54.html">中国科学院院士魏奉思：每颗 卫 星 都要有自己的“ 大 脑 ” - 头条汇</a></li>

</ul>
</details>

**Tags**: `#aerospace`, `#satellite`, `#AI`, `#space intelligence`, `#digital space`

---

<a id="item-19"></a>
## [Ctrip fined $5.1B; ChangXin Memory IPO; Japan admits China leads in humanoid robots](https://36kr.com/p/3913118530819457?f=rss) ⭐️ 7.0/10

China's market regulator fined Ctrip 51.79 billion yuan ($7.1 billion) for abusing its dominant market position. Meanwhile, memory chipmaker ChangXin Memory Technology (CXMT) listed on the STAR Market with an IPO price of 8.66 yuan per share, and Japanese technicians concluded that China's humanoid robotics have surpassed Japan's after disassembling Unitree's G1 robot. The Ctrip fine signals China's intensified antitrust enforcement, potentially reshaping the online travel market. CXMT's IPO highlights China's push for semiconductor self-sufficiency, while the Japanese assessment underscores China's rapid progress in humanoid robotics, a key future industry. Ctrip's fine includes both confiscation of illegal gains and a penalty. CXMT's estimated market value ranges from 1 trillion to 4 trillion yuan, implying a potential first-day return of 70%-600%. Unitree's G1 robot costs 99,000 yuan and can perform tasks like cracking walnuts and running at 2 m/s.

rss · 36kr · Jul 26, 23:50

**Background**: Antitrust fines in China are governed by the Anti-Monopoly Law, and Ctrip's case involves abuse of dominant market position in the online travel booking market. ChangXin Memory Technology is a leading Chinese DRAM manufacturer, and its IPO includes an overallotment option (greenshoe) to stabilize the stock. Humanoid robots like Unitree's G1 are designed to mimic human movements and have potential applications in industry and service sectors.

<details><summary>References</summary>
<ul>
<li><a href="https://www.163.com/dy/article/L2OGLTI10511B8LM.html">163.com/dy/article/L2OGLTI10511B8LM.html</a></li>
<li><a href="https://m.dzplus.dzng.com/share/general/0/NEWS2139618WUMBNTSKAWAFL">半岛聚焦丨65...</a></li>

</ul>
</details>

**Tags**: `#Ctrip`, `#antitrust`, `#IPO`, `#humanoid robot`, `#China tech`

---

<a id="item-20"></a>
## [Transformer from Scratch: English-to-Tamil Translation Tutorial](https://www.reddit.com/r/MachineLearning/comments/1v86qo9/built_trained_a_transformer_from_scratch_in_pure/) ⭐️ 7.0/10

A developer published a comprehensive tutorial and blog post detailing how to build and train a Transformer model from scratch using pure PyTorch for English-to-Tamil machine translation. This tutorial provides an accessible, step-by-step guide with math and code for practitioners learning Transformer architectures, bridging theory and practical implementation for low-resource language pairs. The model was trained on the 'gopi30/english-tamil' dataset from Hugging Face using dual NVIDIA T4 GPUs on Kaggle, with full mathematical breakdowns and PyTorch block explanations.

reddit · r/MachineLearning · /u/imrancoder · Jul 27, 17:17

**Background**: The Transformer architecture, introduced in the 'Attention Is All You Need' paper, revolutionized NLP by using self-attention mechanisms without recurrent layers. Machine translation between English and Tamil is challenging due to limited parallel data and different scripts. This tutorial aims to demystify the architecture for learners.

**Tags**: `#Transformer`, `#PyTorch`, `#Machine Translation`, `#NLP`, `#Tutorial`

---

<a id="item-21"></a>
## [Proposing a deterministic pre-training data audit gate](https://www.reddit.com/r/MachineLearning/comments/1v8a3nu/training_data_needs_a_real_gonogo_gate_before/) ⭐️ 7.0/10

A Reddit user proposes a deterministic pre-training data audit system that gates training on explicit quality checks like leakage, contradictions, and provenance, outputting a reproducible PASS/FAIL verdict. This addresses a critical gap in ML pipeline governance, where data quality decisions are often ad hoc, and introduces a principled approach to prevent flawed data from entering training. The system would give verdicts like PASS, WARNING, FAIL, or FAIL_SECURITY based on evidence rather than LLM judgment, and could produce a repair plan on a derived copy while preserving the original.

reddit · r/MachineLearning · /u/jesusmjk · Jul 27, 19:13

**Background**: Data leakage in machine learning occurs when training data inadvertently contains information from the test set, leading to overly optimistic performance estimates. Data provenance tracks the origin and transformations of data, which is crucial for reproducibility and trust. The proposed gate aims to integrate these checks into a formal pre-training control layer, similar to gates already used for code and deployment.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Leakage_(machine_learning)">Leakage ( machine learning ) - Wikipedia</a></li>
<li><a href="https://www.ibm.com/think/topics/data-leakage-machine-learning">What is Data Leakage in Machine Learning ? | IBM</a></li>
<li><a href="https://zenithlaw.com/data-provenance-ml-lifecycle-traceability-graph-methods-ten-lessons">Data Provenance in Machine Learning : Traceability, Graph Met</a></li>

</ul>
</details>

**Tags**: `#data quality`, `#ML pipelines`, `#training data`, `#data validation`, `#MLOps`

---

<a id="item-22"></a>
## [Google Gemini 4: Most Ambitious Pre-training, Expected Late 2026](https://9to5google.com/2026/07/26/google-gemini-4-teases/) ⭐️ 7.0/10

Google CEO Sundar Pichai revealed during the Alphabet Q2 2026 earnings call that Gemini 4 is currently in training, describing it as the company's most ambitious pre-training project to date, with a launch expected by the end of 2026. This announcement underscores Google's determination to stay at the forefront of AI, as larger foundational models are essential for advancing towards AGI. Gemini 4 could set new performance standards and intensify the competitive landscape among leading AI labs. Pichai stated that compute resources will be prioritized for AGI research to ensure Gemini 4 remains state-of-the-art upon release. The model is expected to launch in November or December 2026, following previous Gemini release cadences, while the Gemini 3.x Flash series will continue with near-monthly updates focused on coding capabilities.

telegram · zaihuapd · Jul 27, 04:06

**Tags**: `#AI`, `#Google`, `#Gemini`, `#Large Language Model`

---

<a id="item-23"></a>
## [Alibaba Launches 'Qianwen Office' AI Platform](https://qwenwork.cn/) ⭐️ 7.0/10

Alibaba has launched a beta version of 'Qianwen Office', a one-stop AI office platform that can generate and edit documents, tables, PPTs, web pages, code, and multimedia via natural language, and also features computer control capabilities. This release marks Alibaba's entry into the AI office productivity space with advanced automation features like cross-application control, potentially challenging existing tools like Microsoft Copilot and Google Workspace. The platform is available on web, Windows, and macOS, and integrates with DingTalk. It offers a free tier and paid plans starting at 78 RMB/month. Desktop clients can read local files and use browser automation and Computer Use functions, with explicit user confirmation before executing potentially irreversible actions.

telegram · zaihuapd · Jul 27, 05:45

**Background**: 'Qianwen Office' is built on Alibaba's Qwen large language model family. The 'Computer Use' feature allows AI to directly control the computer interface, performing clicks, typing, and data extraction across applications. This is part of a broader trend in AI agent automation, similar to Anthropic's computer use capabilities.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Qwen">Qwen - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#AI`, `#office productivity`, `#Alibaba`, `#Qwen`, `#computer automation`

---

<a id="item-24"></a>
## [China Rebuts US Sanctions Threat Over AI Model Distillation](https://www.mofcom.gov.cn/syxwfb/art/2026/art_7f1622463a7c48ef9fad600ce0ef702f.html) ⭐️ 7.0/10

China's Ministry of Commerce on July 27 formally rejected U.S. allegations that Chinese AI firms are stealing intellectual property through model distillation, calling the technology a common industry practice and noting that nearly 200 U.S. startups have urged the government not to restrict access to Chinese open-source models. This exchange underscores escalating tensions in AI geopolitics, with model distillation emerging as a flashpoint between the world's two largest AI powers. The U.S. sanctions could disrupt cross-border collaboration and open-source model sharing, affecting global AI development. The Ministry of Commerce stated that model distillation is a widely used technique and that some U.S. companies also use Chinese models in their research and development. It warned that China will take necessary measures to protect its firms' legitimate rights if the U.S. causes substantial damage.

telegram · zaihuapd · Jul 27, 11:01

**Background**: Model distillation is a machine learning technique where a smaller 'student' model is trained to replicate the behavior of a larger 'teacher' model, enabling efficient deployment. It is commonly used to compress large models without significant performance loss. The U.S. has recently investigated Chinese AI firms for allegedly distilling American frontier models without authorization.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/stream-zero/understanding-the-essentials-of-model-distillation-in-ai-1e97403bee8a">Understanding the Essentials of Model Distillation in AI | Medium</a></li>
<li><a href="https://www.linkedin.com/pulse/understanding-distillation-ai-how-models-can-extracted-pooni-vvaqc">Understanding " Distillation " in AI : How Models Can Be Extracted and...</a></li>
<li><a href="https://avahi.ai/glossary/model-distillation/">What is Model Distillation in AI ?</a></li>

</ul>
</details>

**Tags**: `#AI policy`, `#model distillation`, `#US-China relations`, `#technology sanctions`, `#Chinese AI`

---