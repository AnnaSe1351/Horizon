---
layout: default
title: "Horizon Summary: 2026-07-19 (EN)"
date: 2026-07-19
lang: en
---

> From 53 items, 19 important content pieces were selected

---

1. [SRE Replaces $120k Bowling System with $1,600 ESP32s](#item-1) ⭐️ 9.0/10
2. [Alibaba Announces Qwen 3.8: 2.4T Parameter Open-Weights LLM](#item-2) ⭐️ 9.0/10
3. [Claude Code now runs on Bun rewritten in Rust](#item-3) ⭐️ 8.0/10
4. [Minecraft Java Edition Adopts SDL3](#item-4) ⭐️ 8.0/10
5. [Moonshot AI Halts New Kimi K3 Subscriptions Amid Demand Surge](#item-5) ⭐️ 8.0/10
6. [Yimu Technology Raises Over ¥1B in Series E, Valuation Tops ¥10B](#item-6) ⭐️ 8.0/10
7. [GPT-2 token embeddings visualized in hyperbolic space](#item-7) ⭐️ 8.0/10
8. [Interactive map of GPT-2 token embeddings](#item-8) ⭐️ 8.0/10
9. [Honor Unveils Agentic OS Framework, Shifting to Intent-Centric Mobile OS](#item-9) ⭐️ 8.0/10
10. [Alibaba Open-Sources SAIL to Challenge Nvidia CUDA](#item-10) ⭐️ 8.0/10
11. [Selling 2,500 MIDI Recorders: Hardware Is Easier Than You Think](#item-11) ⭐️ 7.0/10
12. [AI Mania Leads to Irrational Corporate Decisions](#item-12) ⭐️ 7.0/10
13. [Zhongke Wenge Launches First Full-Chain AI Decision Suite at WAIC2026](#item-13) ⭐️ 7.0/10
14. [China's AI + Earthquake Disaster Reduction Plan](#item-14) ⭐️ 7.0/10
15. [Passing Swedish Medical Licensing Exam via Open-Weight LLMs with SFT and RLVR](#item-15) ⭐️ 7.0/10
16. [SenseTime Launches SenseNova U1 Pro Multimodal Agent Base](#item-16) ⭐️ 7.0/10
17. [Gboard developing sign-to-text feature using camera and AI](#item-17) ⭐️ 7.0/10
18. [US Politicians Optimize Online Profiles to Sway AI Chatbots](#item-18) ⭐️ 7.0/10
19. [Deep Space Matrix Unveils 'Star Ring Plan' with 210 Satellites](#item-19) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [SRE Replaces $120k Bowling System with $1,600 ESP32s](https://news.ycombinator.com/item?id=48968606) ⭐️ 9.0/10

An SRE built a prototype open-source scoring system called OpenLaneLink using ESP32 microcontrollers, replacing a $120k commercial system for about $1,600 total - roughly $200 per lane pair. This project demonstrates that modern embedded systems can dramatically reduce costs in niche industrial applications, challenging vendor lock-in and making bowling more affordable for small alleys. The system uses an ESPNow star-topology mesh with RS485 fallback, reporting to a Raspberry Pi running Redis and a state machine, allowing any React developer to build custom UIs and animations.

hackernews · section33 · Jul 19, 14:41

**Background**: The ESP32 is a low-cost, low-power microcontroller with built-in Wi-Fi and Bluetooth, widely used in IoT projects. Commercial bowling scoring systems are proprietary, often costing tens of thousands of dollars and locking operators into expensive service contracts.

<details><summary>References</summary>
<ul>
<li><a href="https://circuitdigest.medium.com/esp32-projects-with-circuit-diagram-and-code-full-tutorials-5c892a573998">Medium</a></li>
<li><a href="https://micropython.org/download/">MicroPython - Python for microcontrollers</a></li>

</ul>
</details>

**Discussion**: The Hacker News community praised the project as an archetypal example of hacker ingenuity, with users sharing similar retrofitting experiences and suggesting enhancements like LED chase lights and DMX control for laser shows.

**Tags**: `#embedded systems`, `#IoT`, `#ESP32`, `#cost reduction`, `#hardware hacking`

---

<a id="item-2"></a>
## [Alibaba Announces Qwen 3.8: 2.4T Parameter Open-Weights LLM](https://twitter.com/Alibaba_Qwen/status/2078759124914098291) ⭐️ 9.0/10

Alibaba announced Qwen 3.8, a 2.4 trillion parameter open-weights large language model, competing with Moonshot AI's Kimi K3. This signals intensified competition in open-weights LLMs, providing developers with more powerful local models and reducing reliance on proprietary APIs. Qwen 3.8 has 2.4 trillion parameters and is open-weights, meaning the model weights will be released publicly. It directly follows Moonshot AI's announcement of Kimi K3 with 2.8 trillion parameters.

hackernews · nh43215rgb · Jul 19, 08:44 · [Discussion](https://news.ycombinator.com/item?id=48966120)

**Background**: Large language models (LLMs) are AI models with billions or trillions of parameters that generate text. 'Open-weights' means the trained weights are publicly available, allowing local deployment and fine-tuning. Alibaba's Qwen series is a leading Chinese LLM family.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Kimi_K3">Kimi K3</a></li>
<li><a href="https://www.ai21.com/glossary/open-weights-model/">What is an Open - Weights Model ? | AI21</a></li>

</ul>
</details>

**Discussion**: The community is excited about open-weights competition, with users hoping for smaller versions for local use. Some users reported poor experience with Qwen 3.7 Pro, citing it as unusable for coding compared to Deepseek.

**Tags**: `#LLM`, `#open-weights`, `#Alibaba`, `#AI competition`, `#Qwen`

---

<a id="item-3"></a>
## [Claude Code now runs on Bun rewritten in Rust](https://simonwillison.net/2026/Jul/19/claude-code-in-bun-in-rust/#atom-everything) ⭐️ 8.0/10

Claude Code v2.1.181 and later now use the Rust port of Bun, achieving a 10% faster startup on Linux. The change was verified by examining binary strings showing Rust source files and an unreleased Bun v1.4.0. This demonstrates a significant architectural shift by Anthropic, bundling a custom JavaScript runtime for performance. It also sparks debate about engineering choices, project governance, and communication in open-source communities. Bun's Rust version is currently available as a canary release (bun upgrade --canary). The community discussion highlights concerns about the rewrite's communication process and the long-term viability of Bun as an independent open-source project.

rss · Simon Willison · Jul 19, 03:54 · [Discussion](https://news.ycombinator.com/item?id=48966569)

**Background**: Bun is a fast all-in-one JavaScript runtime, bundler, and package manager originally written in Zig. Claude Code is Anthropic's agentic coding tool that runs in the terminal. The rewrite of Bun from Zig to Rust was announced by Jarred Sumner, aiming to improve memory safety and reduce bugs.

<details><summary>References</summary>
<ul>
<li><a href="https://bun.sh/">Bun — A fast all-in-one JavaScript runtime</a></li>

</ul>
</details>

**Discussion**: Community comments are mixed: some criticize the reliance on a JavaScript runtime for a TUI tool and question the engineering quality. Others debate the communication around the rewrite, with one commenter noting the issue was the lack of mature governance. A few express concern that Bun is now silently becoming a different project.

**Tags**: `#bun`, `#rust`, `#claude-code`, `#performance`, `#runtime`

---

<a id="item-4"></a>
## [Minecraft Java Edition Adopts SDL3](https://www.minecraft.net/en-us/article/minecraft-26-3-snapshot-4) ⭐️ 8.0/10

Minecraft: Java Edition has switched from SDL2 to SDL3 for its cross-platform input and windowing handling in snapshot 26w03a, marking the first major game to adopt the newly stable SDL3 library. This move signals growing industry confidence in SDL3, which offers improved performance and modern API features; it also affects the modding community via LWJGL bindings, potentially streamlining cross-platform development for Minecraft and other Java-based games. The LWJGL bindings for SDL3 were contributed by a member of the GTNH modpack team, completing a full cycle from vanilla to modded and back to vanilla. Known issues include crashes in exclusive fullscreen mode on Windows with multiple monitors and on Wayland.

hackernews · ObviouslyFlamer · Jul 19, 11:48 · [Discussion](https://news.ycombinator.com/item?id=48967256)

**Background**: SDL (Simple DirectMedia Layer) is a cross-platform library that provides low-level access to audio, keyboard, mouse, and graphics hardware, widely used in game development. LWJGL (Lightweight Java Game Library) is the Java binding that allows Minecraft to use native APIs like OpenGL and SDL. SDL3 was released as stable in January 2025, with significant API changes from SDL2.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/SDL_library">SDL library</a></li>
<li><a href="https://www.lwjgl.org/?ref=jmaven.com">LWJGL - Lightweight Java Game Library</a></li>

</ul>
</details>

**Discussion**: Community comments highlight that the LWJGL bindings were written by a GTNH modpack team member, reinforcing the vanilla-modding feedback loop. Some users expressed concern about blocking bugs like Wayland and multi-monitor crashes, hoping fixes land before the stable release.

**Tags**: `#Minecraft`, `#SDL3`, `#game development`, `#LWJGL`, `#open-source`

---

<a id="item-5"></a>
## [Moonshot AI Halts New Kimi K3 Subscriptions Amid Demand Surge](https://twitter.com/kimi_moonshot/status/2078855608565207130) ⭐️ 8.0/10

Moonshot AI temporarily paused new subscriptions for its Kimi K3 model after demand exceeded capacity, prioritizing service quality for existing users. This move signals a rare customer-centric approach in the AI industry, where companies often prioritize growth over user experience, and highlights the immense demand for advanced reasoning models. Kimi K3 is a 2.8 trillion parameter model using hybrid linear attention (KDA) and supports up to 1 million context tokens; the suspension does not affect existing subscribers.

hackernews · serialx · Jul 19, 16:02 · [Discussion](https://news.ycombinator.com/item?id=48969291)

**Background**: Moonshot AI is a Beijing-based AI startup known for its Kimi chatbot series, with Kimi K3 being its flagship model released in July 2026. The model uses a novel hybrid attention architecture to improve efficiency on long-context tasks. The company is one of China's 'AI Tigers' and has gained significant attention for its open-source contributions.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Moonshot_AI">Moonshot AI</a></li>
<li><a href="https://en.wikipedia.org/wiki/Kimi_K3">Kimi K3</a></li>
<li><a href="https://platform.kimi.ai/docs/guide/kimi-k3-quickstart">Kimi K 3 - Kimi API Platform</a></li>

</ul>
</details>

**Discussion**: Community members praised Moonshot AI for prioritizing existing users over rapid growth, with some expressing personal satisfaction with Kimi K3's performance, comparing it favorably to Claude Opus. Others noted technical details such as the model's heavy use of RNN/linear attention layers, emphasizing its suitability for long-context tasks.

**Tags**: `#AI`, `#Kimi K3`, `#Moonshot AI`, `#subscription model`, `#demand management`

---

<a id="item-6"></a>
## [Yimu Technology Raises Over ¥1B in Series E, Valuation Tops ¥10B](https://36kr.com/newsflashes/3902093496813441?f=rss) ⭐️ 8.0/10

On July 18, Yimu Technology announced the completion of its Series E funding round of over 1 billion RMB, pushing its valuation above 10 billion RMB. The funds will be used to advance tactile sensing materials, chips, algorithms, and models for embodied intelligence, as well as scaling production. This significant funding round underscores strong market confidence in embodied AI and tactile sensing, a critical technology for robotics. Yimu's high valuation reflects the growing demand for advanced sensory capabilities in autonomous systems. The round was led by multiple top-tier RMB funds, leading USD funds, and prominent industry players. The company plans to focus on R&D of tactile sensing materials, chips, algorithms, and models, and also scale up production for high-quality delivery.

rss · 36kr · Jul 19, 05:15

**Background**: Embodied intelligence refers to AI systems that interact with the physical world through sensors and actuators, with cognition shaped by bodily interactions. Tactile sensing technology replicates human touch, enabling robots to perceive contact pressures and textures, which is crucial for dexterous manipulation and safe human-robot interaction.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Embodied_intelligence">Embodied intelligence</a></li>
<li><a href="https://pressureprofile.com/about/tactile-sensing">Tactile Sensors and Tactile Sensing Technology — PPS</a></li>

</ul>
</details>

**Tags**: `#embodied AI`, `#tactile sensing`, `#robotics`, `#funding`, `#Chinese tech`

---

<a id="item-7"></a>
## [GPT-2 token embeddings visualized in hyperbolic space](https://www.reddit.com/r/MachineLearning/comments/1v0pv45/follow_up_gpt2s_vocabulary_as_a_hyperbolic_tree/) ⭐️ 8.0/10

An interactive Poincaré ball visualization of 32,070 GPT-2 small token embeddings has been published, allowing users to explore the natural tree structure formed by token similarities without any training or optimization. This work highlights that hyperbolic geometry can more naturally represent hierarchical relationships in word embeddings than flat Euclidean space, potentially inspiring better embedding techniques for language models. The visualization uses only raw GPT-2 small token embeddings and employs a Möbius translation for navigation, with no optimization or training involved. The resulting forest structure contains one large tree of about 2,300 tokens and many smaller ones.

reddit · r/MachineLearning · /u/Limp-Contest-7309 · Jul 19, 12:54

**Background**: Hyperbolic geometry is a non-Euclidean geometry where space grows exponentially with distance, making it well-suited for embedding tree-like structures. The Poincaré ball model maps hyperbolic space onto a unit ball, preserving angles while distorting distances. Möbius transformations provide natural isometries of the hyperbolic ball, allowing smooth navigation.

**Tags**: `#GPT-2`, `#hyperbolic embeddings`, `#visualization`, `#token embeddings`, `#Poincaré ball`

---

<a id="item-8"></a>
## [Interactive map of GPT-2 token embeddings](https://www.reddit.com/r/MachineLearning/comments/1v09muj/interactive_map_of_gpt2s_token_embedding_space/) ⭐️ 8.0/10

A user-created interactive map visualizes 32,070 alphabetic tokens from GPT-2-small's embedding table using t-SNE and a minimum spanning tree, allowing exploration of nearest neighbor relationships by tapping or searching. This tool provides an intuitive way to interpret token embeddings, aiding in understanding how language models represent meaning and similarity, which is valuable for research, education, and debugging model behavior. The map uses t-SNE on a compressed representation of the embedding table, with edges forming a minimum spanning tree to show real nearest-kin relationships. It works on mobile and requires no forward pass or context.

reddit · r/MachineLearning · /u/Limp-Contest-7309 · Jul 18, 22:42

**Background**: Token embeddings are dense vector representations of subword units in a vocabulary, capturing semantic meaning in a high-dimensional space. t-SNE is a nonlinear dimensionality reduction technique that projects high-dimensional data into 2D or 3D for visualization while preserving local structure. A minimum spanning tree connects all points with the smallest total edge weight, highlighting the most important relationships.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Minimum_spanning_tree">Minimum spanning tree</a></li>
<li><a href="https://www.datacamp.com/tutorial/introduction-t-sne">Introduction to t - SNE : Nonlinear Dimensionality Reduction and Data...</a></li>

</ul>
</details>

**Tags**: `#GPT-2`, `#token embeddings`, `#t-SNE`, `#visualization`, `#interpretability`

---

<a id="item-9"></a>
## [Honor Unveils Agentic OS Framework, Shifting to Intent-Centric Mobile OS](https://wallstreetcn.com/articles/3777328) ⭐️ 8.0/10

At the 2026 World AI Conference, Honor unveiled its Agentic OS technical framework, which marks a shift from an app-centric to an intent-centric mobile operating system. The company also demonstrated the Robot Phone, capable of executing cross-app tasks through natural language commands. This framework redefines how users interact with smartphones by focusing on user intent rather than individual apps, potentially simplifying complex multi-step tasks. The collaboration with Alibaba's Qwen also underscores the industry trend of integrating large language models directly into operating systems. The Robot Phone, announced in October 2025 and showcased at CES 2026, features an AI super brain and a robotic camera arm, enabling embodied AI interaction. Honor collaborated with Alibaba's Qwen to develop on-device large model solutions tailored for smartphone scenarios.

telegram · zaihuapd · Jul 19, 02:06

**Background**: Traditional mobile operating systems are app-centric, requiring users to open specific applications to perform tasks. An intent-centric system, by contrast, allows users to simply state their goal, and the OS automatically understands the intent and orchestrates actions across multiple apps. Agentic OS refers to a framework where AI agents autonomously plan and execute tasks on behalf of the user, often integrating large language models for natural language understanding.

<details><summary>References</summary>
<ul>
<li><a href="https://www.lyzr.ai/blog/best-agentic-os-platforms/?trk=article-ssr-frontend-pulse_little-text-block">Best Agentic OS Platforms: Enterprise Buyer's Guide (2026)</a></li>
<li><a href="https://www.kindo.ai/blog/the-rise-of-intent-centric-systems">Intent - Centric Architecture: The 2026 Enterprise Model | Kindo</a></li>
<li><a href="https://www.honor.com/global/events/honor-robot-phone/">HONOR Robot Phone - HONOR Global</a></li>

</ul>
</details>

**Tags**: `#AI`, `#mobile OS`, `#intent-centric`, `#Agentic OS`, `#Honor`

---

<a id="item-10"></a>
## [Alibaba Open-Sources SAIL to Challenge Nvidia CUDA](https://www.scmp.com/tech/tech-war/article/3361048/alibaba-targets-nvidias-dominant-software-ecosystem-open-source-ai-stack) ⭐️ 8.0/10

On July 18, Alibaba's chip design unit T-Head announced the open-sourcing of SAIL, the software stack for its Zhenwu AI chips, at the World AI Conference in Shanghai. This move aims to lower migration costs for developers and directly challenge Nvidia's dominant CUDA ecosystem. By open-sourcing SAIL, Alibaba provides a viable alternative to Nvidia's CUDA, potentially reducing vendor lock-in and accelerating the adoption of domestic AI chips. This move could reshape the AI hardware ecosystem, especially in China where US export restrictions limit access to Nvidia products. Developers can adapt SAIL to mainstream AI frameworks within seven days, reusing existing code with minimal modifications. As of April, Alibaba had shipped 560,000 Zhenwu chips to over 400 enterprise customers across 20 industries.

telegram · zaihuapd · Jul 19, 07:34

**Background**: Nvidia's CUDA is a proprietary parallel computing platform that has become the de facto standard for AI computing, creating high switching costs for developers. SAIL (Software Abstraction & Integration Layer) is Alibaba's foundational software architecture for its Zhenwu AI chips, designed to simplify code portability. By open-sourcing SAIL, Alibaba aims to build an independent AI software ecosystem, similar to how Huawei and Moore Threads are promoting their own open-source stacks.

<details><summary>References</summary>
<ul>
<li><a href="https://www.scmp.com/tech/tech-war/article/3361048/alibaba-targets-nvidias-dominant-software-ecosystem-open-source-ai-stack">Alibaba targets Nvidia’s dominant software ecosystem with...</a></li>
<li><a href="https://azat.tv/en/alibaba-nvidia-ai-software-stack-sail/">Alibaba Open-Sources AI Software Stack to Challenge...</a></li>

</ul>
</details>

**Tags**: `#AI chips`, `#open source`, `#Alibaba`, `#Nvidia CUDA`, `#software stack`

---

<a id="item-11"></a>
## [Selling 2,500 MIDI Recorders: Hardware Is Easier Than You Think](https://chipweinberger.com/articles/20260719-hardware-is-not-so-hard) ⭐️ 7.0/10

Chip Weinberger shares lessons from selling 2,500 units of his JamCorder MIDI recorder, arguing that hardware development is more approachable than commonly believed. This challenges the prevailing notion that hardware is inherently harder than software, offering encouragement and practical insights for hardware entrepreneurs and makers. It also demonstrates that a simple, well-designed niche product can achieve significant sales without massive scale. The JamCorder is a straightforward device with a 25-component PCBA and an off-the-shelf clamshell enclosure, storing performances as standard MIDI files on a card to avoid app dependency. The author also implemented encryption to deter counterfeiting, sparking discussion on open-source versus closed hardware.

hackernews · chipweinberger · Jul 19, 10:34 · [Discussion](https://news.ycombinator.com/item?id=48966713)

**Background**: MIDI (Musical Instrument Digital Interface) is a digital communication protocol that allows electronic musical instruments and computers to exchange performance data like note pitches and velocities. Hardware development is often considered hard due to challenges in scaling, testing physical tolerances, and handling user variability, but Weinberger's experience shows that for simple, low-volume products, hardware can be as hard as you make it.

<details><summary>References</summary>
<ul>
<li><a href="https://www.loopcloud.com/cloud/blog/5260-What-is-MIDI-and-How-is-it-Used-in-Making-Music-">What is MIDI and How is it Used in Making Music?</a></li>
<li><a href="https://kernom.com/en-us/blogs/midi/midi-basis">Understanding MIDI Basis for your Stompboxes - KERNOM NEWS</a></li>
<li><a href="https://www.kvraudio.com/forum/viewtopic.php?t=274324">Hardware MIDI Recorder Suggestions - Hardware ... - KVR Audio</a></li>

</ul>
</details>

**Discussion**: Comments include a satisfied customer praising the product as perfect, a critique noting that hardware difficulty scales with complexity and that the JamCorder's simplicity is not representative of most products, and a question about balancing anti-counterfeit measures with open-source firmware. The discussion validates the topic's importance by providing contrasting perspectives on hardware development.

**Tags**: `#hardware`, `#product design`, `#entrepreneurship`, `#MIDI`, `#lessons learned`

---

<a id="item-12"></a>
## [AI Mania Leads to Irrational Corporate Decisions](https://simonwillison.net/2026/Jul/19/ai-mania/#atom-everything) ⭐️ 7.0/10

A critical analysis by Nik Suresh, shared on Simon Willison's blog, exposes how AI hype is causing executives to make irrational decisions, such as an executive who never used ChatGPT yet produced an AI-centered strategy for a $2B+ company. This highlights a systemic issue where AI mania encourages performative engineering and dishonesty, potentially wasting resources and undermining genuine innovation. The article includes an anecdote about an engineer at a company with a token leaderboard who used AI to rewrite a Go codebase in Zig just to appear productive, and a conversation revealing that executives avoid honesty about AI limitations due to fear of losing contracts.

rss · Simon Willison · Jul 19, 05:06

**Background**: Zig is a system programming language designed as an improvement to C, known for compile-time generics and manual memory management. Token leaderboards track AI token usage for cost and productivity comparisons, often used internally by companies to measure AI tool adoption. AI mania refers to the excessive hype and rushed adoption of AI technologies in business, often without understanding their practical limits.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Zig_(programming_language)">Zig (programming language)</a></li>
<li><a href="https://whoburnedmore.com/">Who Burned More? AI Token Leaderboard</a></li>

</ul>
</details>

**Tags**: `#AI hype`, `#corporate decision-making`, `#critical analysis`, `#software engineering`

---

<a id="item-13"></a>
## [Zhongke Wenge Launches First Full-Chain AI Decision Suite at WAIC2026](https://36kr.com/newsflashes/3902288636282757?f=rss) ⭐️ 7.0/10

At the 2026 World Artificial Intelligence Conference (WAIC2026), Zhongke Wenge released the industry's first complete AI decision-making product system, named 'Ji, Shu, He, Nao, Duan', covering the entire chain from data governance to agent execution. This system leverages the DOMA architecture as its technical foundation. This product suite aims to unify enterprise decision-making processes, potentially reducing decision cycles and enabling faster business insights. It could impact industries relying on complex, multi-step AI decision workflows by providing an end-to-end solution. The system integrates data governance, business modeling, model inference, and agent execution into a single closed loop. It reportedly supports decisions ranging from enterprise production and operations to scientific discovery.

rss · 36kr · Jul 19, 08:24

**Background**: AI decision intelligence involves using AI to support or automate decision-making in complex environments. Traditional approaches often require separate tools for data processing, modeling, and execution, leading to fragmented workflows. Zhongke Wenge's product attempts to provide a unified, end-to-end framework to address this inefficiency.

<details><summary>References</summary>
<ul>
<li><a href="https://stock.10jqka.com.cn/20260719/c678273021.shtml">中 科 闻 歌 WAIC 2026发布完整AI决策 产 品 体 系 | 同花顺财经</a></li>
<li><a href="https://www.163.com/dy/article/L25CR05105118O92.html">中 科 闻 歌 发布首个AI决策“全家桶”，企业决策卷入“10分钟时代”</a></li>

</ul>
</details>

**Tags**: `#AI`, `#decision intelligence`, `#product launch`, `#WAIC`

---

<a id="item-14"></a>
## [China's AI + Earthquake Disaster Reduction Plan](https://36kr.com/newsflashes/3902090005743493?f=rss) ⭐️ 7.0/10

On July 19, 2026, the China Earthquake Administration released the 'AI + Earthquake Disaster Reduction Action Plan (2026–2028)' at the World AI Conference, outlining nine key tasks including intelligent earthquake monitoring and AI-based early warning systems. This national-level plan signals China's strategic push to integrate AI into earthquake disaster reduction, aiming to strengthen the country's competitive edge in this domain and improve real-time monitoring and early warning capabilities. The plan focuses on building a 'data-model-platform-application' four-in-one AI technology system and aims to achieve effective AI support for earthquake disaster reduction operations by 2028.

rss · 36kr · Jul 19, 05:00

**Background**: Earthquake early warning and monitoring have traditionally relied on seismic networks and manual analysis. The integration of AI, such as deep learning for waveform recognition and rapid damage assessment, promises faster and more accurate responses. This plan formalizes China's commitment to leveraging AI for disaster resilience over the next three years.

<details><summary>References</summary>
<ul>
<li><a href="https://www.chinanews.com.cn/gn/2026/07-19/10662378.shtml">“人工 智 能 +防 震 减灾”行动方案发布-中新网</a></li>
<li><a href="https://tech.ifeng.com/c/8ut3mjO96rP">“人工 智 能 +防 震 减灾”行动方案发布_凤凰网</a></li>
<li><a href="http://www.earth-science.net/fileDQKX/journal/article/dqkxzx/2026/1/dqkxzx-51-1-1.pdf">Application of Artificial Intelligence Real⁃Time Earthquake Processing</a></li>

</ul>
</details>

**Tags**: `#人工智能`, `#防震减灾`, `#政策`, `#地震预警`

---

<a id="item-15"></a>
## [Passing Swedish Medical Licensing Exam via Open-Weight LLMs with SFT and RLVR](https://www.reddit.com/r/MachineLearning/comments/1v0pnoq/passing_the_swedish_medical_licensing_exam_by/) ⭐️ 7.0/10

A recent study demonstrates that open-weight large language models (LLMs) fine-tuned with supervised fine-tuning (SFT) and reinforcement learning from verified rewards (RLVR) can pass the Swedish Medical Licensing Exam, a non-English medical certification test. This extends the capability of open-weight LLMs to a new language and domain, showing potential for deploying medical AI in non-English settings. It also validates RLVR as an effective post-training method for factual domains. The study likely used open-weight models such as Llama or Mistral, and applied SFT on Swedish medical data followed by RLVR with verifiable reward signals from exam answers. The model achieved a passing score, but exact performance metrics and model sizes were not detailed in the summary.

reddit · r/MachineLearning · /u/AccomplishedCat4770 · Jul 19, 12:44

**Background**: Supervised fine-tuning (SFT) adapts a pre-trained LLM to specific tasks using labeled examples. Reinforcement learning from verified rewards (RLVR) is a newer technique where the model is rewarded only for outputs that can be formally verified as correct, avoiding the drift problem of learned reward models. Together, they allow LLMs to acquire domain-specific knowledge and reasoning skills.

<details><summary>References</summary>
<ul>
<li><a href="https://www.geeksforgeeks.org/artificial-intelligence/supervised-fine-tuning-sft-for-llms/">Supervised Fine - Tuning ( SFT ) for LLMs - GeeksforGeeks</a></li>
<li><a href="https://www.linkedin.com/pulse/reinforcement-learning-verifiable-reward-rlvr-new-paradigm-jatasra-xe3fc">Reinforcement Learning with Verifiable Reward ( RLVR ): A New...</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#medical AI`, `#fine-tuning`, `#reinforcement learning`, `#NLP`

---

<a id="item-16"></a>
## [SenseTime Launches SenseNova U1 Pro Multimodal Agent Base](https://mp.weixin.qq.com/s/hGo5TvUpxRodVtfnXDM7ew) ⭐️ 7.0/10

On July 18, 2025, SenseTime released the SenseNova U1 Pro, a next-generation multimodal agent base for long-term tasks, featuring 8K output, professional design aesthetics, and long-range agentic closed-loop thinking. This release marks a significant step for SenseTime in multimodal generation, offering system-level delivery capabilities for commercial creative scenarios and potentially enhancing productivity in fields like advertising and design. U1 Pro underwent three rapid iterations in the past two months. In June 2025, U1 users averaged 107 generated images per day, and the GitHub repository has over 8,500 stars. It demonstrates capabilities from image to video storyboard creation.

telegram · zaihuapd · Jul 19, 01:20

**Background**: A multi-modal agent base is an AI system that can perceive and act across multiple data types—text, images, audio, video—using vision-language models to understand and interact with graphical interfaces. Long-range agentic closed-loop thinking refers to AI that learns from outcomes, re-evaluates decisions, and adapts in real time over extended tasks. SenseTime's U1 Pro integrates these capabilities to deliver professional-grade outputs for business creation.

<details><summary>References</summary>
<ul>
<li><a href="https://aws.amazon.com/blogs/machine-learning/generative-ai-and-multi-modal-agents-in-aws-the-key-to-unlocking-new-value-in-financial-markets/">Generative AI and multi - modal agents in AWS: The key to unlocking...</a></li>
<li><a href="https://fp8.co/glossary/multi-modal-agents">Multi - Modal Agents — Definition & Explanation | fp8.co</a></li>
<li><a href="https://www.linkedin.com/pulse/how-agentic-ai-closed-loop-orchestration-transforming-william-fox-hz7oe">How Agentic AI And Closed - Loop Orchestration Are Transforming...</a></li>

</ul>
</details>

**Tags**: `#multimodal`, `#AI`, `#SenseTime`, `#image generation`, `#agentic`

---

<a id="item-17"></a>
## [Gboard developing sign-to-text feature using camera and AI](https://www.androidauthority.com/gboard-sign-to-text-3688910/) ⭐️ 7.0/10

An APK teardown of Gboard's latest beta (version 17.8.3) revealed a new 'Sign-to-Text' input option that uses the phone's camera to capture sign language gestures and convert them to text, processing gestures locally for privacy before sending to Google's cloud AI for recognition. This feature could significantly enhance accessibility for deaf and hard-of-hearing users by enabling real-time sign language input on mobile devices, potentially leveraging Google's SignGemma model announced last year. The feature was discovered via APK teardown and is not yet enabled in the beta, meaning it may never be released. Google has not disclosed which sign languages will be supported.

telegram · zaihuapd · Jul 19, 06:49

**Background**: SignGemma is an open AI model from Google DeepMind, part of the Gemma family, designed to translate sign language into text. It focuses on real-time communication and inclusive AI development. The Gboard sign-to-text feature appears to be the first major application of this model.

<details><summary>References</summary>
<ul>
<li><a href="https://www.linkedin.com/posts/genai-works_ai-googledeepmind-signgemma-activity-7333359467624824832-koAG">Google DeepMind launches SignGemma , an open AI model... | LinkedIn</a></li>
<li><a href="https://www.blockchain-council.org/ai/google-deepmind-announces-signgemma/">Google DeepMind Announces SignGemma - Blockchain Council</a></li>

</ul>
</details>

**Tags**: `#Gboard`, `#accessibility`, `#sign language`, `#AI`, `#DeepMind`

---

<a id="item-18"></a>
## [US Politicians Optimize Online Profiles to Sway AI Chatbots](https://www.nytimes.com/2026/07/19/us/politics/chatbots-political-campaigns.html) ⭐️ 7.0/10

US political campaigns are adjusting their websites and online content to influence how AI chatbots like ChatGPT describe candidates, giving rise to a new industry called 'answer engine optimization' (AEO). This practice could distort the information voters receive from AI systems, raising concerns about manipulation of political discourse and the integrity of democratic processes. A study found that new Wikipedia content can be ingested by chatbots within about 12 minutes, and over a third of AI answers in a Scottish election experiment contained errors.

telegram · zaihuapd · Jul 19, 13:19

**Background**: Answer engine optimization (AEO), also known as generative engine optimization (GEO), involves structuring digital content to improve visibility in AI-generated answers. As large language models are integrated into search, optimizing for direct answers rather than link lists becomes crucial. This practice aims to influence how LLMs retrieve and summarize information.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Answer_Engine_Optimization_(AEO)">Answer Engine Optimization (AEO)</a></li>

</ul>
</details>

**Tags**: `#AI伦理`, `#政治竞选`, `#信息操纵`, `#搜索引擎优化`, `#聊天机器人`

---

<a id="item-19"></a>
## [Deep Space Matrix Unveils 'Star Ring Plan' with 210 Satellites](https://mp.weixin.qq.com/s/TiC_sYBX7u3l3HZW-CsfLQ) ⭐️ 7.0/10

Deep Space Matrix announced the 'Star Ring Plan' at WAIC 2026, aiming to build a low-Earth orbit intelligent satellite constellation integrating computing, remote sensing, and relay capabilities. The first phase will deploy approximately 210 satellites, with eventual expansion to thousands or tens of thousands. This plan represents a significant move to establish a space-based AI computing infrastructure, potentially offering distributed computing power for AI workloads globally. It could reduce reliance on terrestrial data centers and enable low-latency AI processing for applications like autonomous systems and climate monitoring. The constellation will use cross-layer satellite computing interconnect to organize satellites on different orbits into a schedulable space computing network. The company emphasizes improving overall computing efficiency under constraints such as launch capacity and power consumption, rather than simply copying foreign routes.

telegram · zaihuapd · Jul 19, 14:05

**Background**: Space-based AI computing constellations, such as SpaceX's Starmind and China's Three-Body Computing Constellation, aim to deploy satellites with on-board computing capabilities to process data in orbit. This reduces the need to transmit large volumes of data to Earth, enabling real-time AI inference and data processing for Earth observation, communications, and other applications. Low-Earth orbit (LEO) satellites offer lower latency and higher bandwidth than geostationary satellites, making them suitable for distributed computing networks.

<details><summary>References</summary>
<ul>
<li><a href="https://news.google.com/stories/CAAqNggKIjBDQklTSGpvSmMzUnZjbmt0TXpZd1NoRUtEd2p6cC1Qd0RSSGQtNmx3NkV4U09DZ0FQAQ?hl=en-US&gl=US&ceid=US:en">Google News - China launches satellites for space - based ...</a></li>
<li><a href="https://www.cutter.com/article/orbit-data-centers-mapping-leaders-space-ai-computing">On-Orbit Data Centers: Mapping the Leaders in Space - Based AI ...</a></li>

</ul>
</details>

**Tags**: `#satellite AI`, `#space computing`, `#AI infrastructure`, `#low-earth orbit`, `#WAIC`

---