---
layout: default
title: "Horizon Summary: 2026-07-29 (EN)"
date: 2026-07-29
lang: en
---

> From 83 items, 28 important content pieces were selected

---

1. [Open-source engine runs Gemma 4 26B on Mac with only 2 GB RAM](#item-1) ⭐️ 9.0/10
2. [Document-borne AI worms self-propagate through Copilot for Word](#item-2) ⭐️ 9.0/10
3. [Mitchell Hashimoto Announces Superlogical, Transfers Ghostty to Non-Profit](#item-3) ⭐️ 8.0/10
4. [KOReader: Open-Source E-Reader Enhances E-Ink Devices](#item-4) ⭐️ 8.0/10
5. [Handbook.md Study: Long Policy Docs Fail to Govern AI Agents](#item-5) ⭐️ 8.0/10
6. [Matthew Green on Post-Quantum Crypto and AI Cryptanalysis](#item-6) ⭐️ 8.0/10
7. [Kimi AI completes $3.5B Series F at $35B valuation](#item-7) ⭐️ 8.0/10
8. [Tencent Hunyuan Open-Sources AngelSpec](#item-8) ⭐️ 8.0/10
9. [Claude shared chats and Artifacts indexed by Google, Anthropic says by design](#item-9) ⭐️ 8.0/10
10. [Russia charges Telegram founder Durov with aiding terrorism](#item-10) ⭐️ 8.0/10
11. [Report: Hugging Face widely used to generate deepfake nude images](#item-11) ⭐️ 8.0/10
12. [China Drafts Anti-Cyberbullying Law Targeting AI-Generated Abuse](#item-12) ⭐️ 8.0/10
13. [Kimi Launches Cheaper K3-256k with 256K Context](#item-13) ⭐️ 7.0/10
14. [AI Firms Hire Thousands of Tradespeople for Data Centers](#item-14) ⭐️ 7.0/10
15. [SQLite Creator: SQL Changed Jobs, Not Eliminated Them](#item-15) ⭐️ 7.0/10
16. [Guide: Custom MCP server for Claude and ChatGPT](#item-16) ⭐️ 7.0/10
17. [Claude Mythos Finds Cryptanalytic Weaknesses in HAWK and AES](#item-17) ⭐️ 7.0/10
18. [Modular Data Centers: LEGO-Like Solution to Labor Woes](#item-18) ⭐️ 7.0/10
19. [Fabric Tactile Sensing Startup YaoLe Tech Raises Pre-A+ for Data Gloves](#item-19) ⭐️ 7.0/10
20. [China Smart Hardware Enters AI-Native Phase, Report Says](#item-20) ⭐️ 7.0/10
21. [US awards $874M to 7 tech firms for semiconductor R&D](#item-21) ⭐️ 7.0/10
22. [ICLR 2027 deadline precedes NeurIPS 2026 decisions](#item-22) ⭐️ 7.0/10
23. [ncnn Vulkan Backend Enables 10x ML Inference Speedup on Edge](#item-23) ⭐️ 7.0/10
24. [xAI sues Minnesota to block AI nudification ban](#item-24) ⭐️ 7.0/10
25. [Windows 11 silently installs OneDrive Photos with face scanning](#item-25) ⭐️ 7.0/10
26. [China Bans 'Little Blue Lights' for Autonomous Driving Indicators on New Vehicles](#item-26) ⭐️ 7.0/10
27. [Xianyu's AI Service Orders Surge 157% in H1 2024](#item-27) ⭐️ 7.0/10
28. [China Telecom Halts Third-Party Online SIM Card Sales](#item-28) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Open-source engine runs Gemma 4 26B on Mac with only 2 GB RAM](https://github.com/drumih/turbo-fieldfare) ⭐️ 9.0/10

TurboFieldfare is an open-source inference engine written in Swift and Metal that runs the 4-bit quantized Gemma 4 26B-A4B-IT model on any M-series Mac using only about 2 GB of RAM. It achieves 5–6 tok/s on an 8 GB M2 MacBook Air and 31–35 tok/s on an M5 MacBook Pro by streaming routed experts from SSD. This breakthrough enables running large Mixture-of-Experts models with 14 GB of weights on memory-constrained devices like standard MacBooks, dramatically expanding the accessibility of on-device AI. It challenges the conventional approach of fitting entire models into RAM and opens new possibilities for edge inference. The engine keeps the shared model layers and KV cache in RAM while streaming only the routed experts needed for each token from SSD, using a small expert cache and bounded parallel pread. It also includes an experimental OpenAI-compatible local server with streaming and tool call support, and reuses one prompt prefix from the KV cache.

hackernews · gitpusher42 · Jul 29, 15:05 · [Discussion](https://news.ycombinator.com/item?id=49098510)

**Background**: Gemma 4 26B-A4B-IT is a Mixture-of-Experts (MoE) model from Google with 26 billion total parameters but only about 4 billion active per token, as it uses routed experts. 4-bit quantization reduces the weight precision to 4 bits per value, shrinking model size significantly while preserving accuracy. Traditional inference tools require loading all weights into RAM, which is infeasible for large models on memory-limited devices.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mixture_of_experts">Mixture of experts - Wikipedia</a></li>
<li><a href="https://huggingface.co/blog/moe">Mixture of Experts Explained</a></li>
<li><a href="https://www.emergentmind.com/topics/4-bit-model-quantization">4-Bit Model Quantization - emergentmind.com</a></li>

</ul>
</details>

**Discussion**: The community discussion shows strong interest and technical depth. Users compared the approach to llama.cpp's mmap, noting that TurboFieldfare synchronizes SSD reads with inference for lower latency. Some provided compatibility tips for older macOS versions, and others asked about running on non-Mac platforms like Debian or Jetson. Overall sentiment is positive, with many impressed by the practical engineering overcoming memory limitations.

**Tags**: `#inference`, `#model compression`, `#edge AI`, `#open-source`, `#Gemma`

---

<a id="item-2"></a>
## [Document-borne AI worms self-propagate through Copilot for Word](https://enklypesalt.com/posts/context-collapse-part3-ai-worming-through-word/) ⭐️ 9.0/10

Security researcher Håkon Måløy demonstrated a new class of AI worm that uses prompt injection to self-replicate within Microsoft Word's Copilot feature, embedding malicious instructions in documents that cause Copilot to propagate the attack to new documents. This marks the first documented case of a self-replicating AI worm exploiting a mainstream office productivity tool, highlighting a fundamental security flaw in LLM-based assistants that mix instructions with data. It could lead to widespread data breaches and automated malware propagation if not addressed. The attack upgrades prompt injection to a full worm by making Copilot rewrite documents to include the malicious prompt, which then infects other users who open those documents. Microsoft has been notified since March 2026 but the vulnerability remains unmitigated as of publication.

hackernews · Canopy9560 · Jul 29, 11:44 · [Discussion](https://news.ycombinator.com/item?id=49096188)

**Background**: Prompt injection attacks exploit the inability of large language models (LLMs) to distinguish between trusted instructions and untrusted user input or data. When an LLM such as Copilot processes a document, it may treat text in the document as commands, allowing attackers to craft malicious prompts that hijack the model's behavior. AI worms extend this by adding self-replication capabilities, enabling the attack to spread autonomously across systems.

<details><summary>References</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/ai-worms">AI Worms: Autonomous Self-Propagating Malware</a></li>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection_attack">Prompt injection attack</a></li>
<li><a href="https://www.theregister.com/security/2026/07/29/word-worm-crawls-into-copilot-spreads-chaos/5280588">Word worm crawls into Copilot, spreads chaos - The Register</a></li>

</ul>
</details>

**Discussion**: Community comments express strong concern about the difficulty of fixing this class of vulnerability, with one commenter noting that as long as instructions and data are mixed, such attacks are fundamentally unavoidable. Another comment describes how AI agents with excessive access could be exploited to steal credentials and propagate through GitHub. Some users have already uninstalled Copilot to protect their data.

**Tags**: `#AI Security`, `#Copilot`, `#Worms`, `#Prompt Injection`, `#LLM Vulnerabilities`

---

<a id="item-3"></a>
## [Mitchell Hashimoto Announces Superlogical, Transfers Ghostty to Non-Profit](https://www.superlogical.com/) ⭐️ 8.0/10

Mitchell Hashimoto has announced Superlogical, a new company that will build terminal applications on top of the open-source libghostty library. He has also transferred ownership of the Ghostty terminal emulator to a non-profit organization. This move by a prominent developer signals a sustainable open-source business model where a company builds commercial products on a community-owned core. It could encourage more developers to adopt libghostty as a foundation for terminal tools. Superlogical will use libghostty as the MIT-licensed public building block for its terminal applications, upstreaming shared work back to the community. Ghostty, known for its GPU-accelerated performance and native UI, was originally created by Hashimoto and has gained significant popularity.

hackernews · yan · Jul 29, 15:41 · [Discussion](https://news.ycombinator.com/item?id=49098965)

**Background**: Ghostty is a fast, feature-rich, cross-platform terminal emulator that uses GPU acceleration and platform-native UI. Its core is implemented in Zig as the libghostty library, which is a zero-dependency C and Zig library for building terminal emulators. By transferring Ghostty to a non-profit, Hashimoto ensures the terminal emulator remains community-governed.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/ghostty-org/ghostty">GitHub - ghostty -org/ ghostty : Ghostty is a fast, feature-rich, and...</a></li>
<li><a href="https://ghostty.org/docs/about">About Ghostty</a></li>
<li><a href="https://ghostty.org/">Ghostty</a></li>

</ul>
</details>

**Discussion**: Commenters largely praised the open-source and non-profit structure, with user simonw highlighting that Superlogical will build on libghostty as a public dependency. Another commenter drew parallels to OLE/COM technologies, noting both the power and complexity of such composable systems. A few users criticized the title for being clickbaity or uninformative.

**Tags**: `#terminal`, `#open-source`, `#developer-tools`, `#Mitchell Hashimoto`, `#libghostty`

---

<a id="item-4"></a>
## [KOReader: Open-Source E-Reader Enhances E-Ink Devices](https://koreader.rocks/) ⭐️ 8.0/10

KOReader is an open-source document viewer for E Ink devices that supports a wide range of file formats including EPUB, PDF, DjVu, and more, offering a customizable reading experience beyond stock firmware. It provides a free, community-driven alternative to proprietary e-reader software, enabling native format support and enhanced features like reading progress syncing, which significantly improves the user experience on devices like Kindle and Kobo. KOReader supports EPUB, PDF, DjVu, XPS, CBT, CBZ, FB2, PDB, TXT, HTML, RTF, CHM, DOC, MOBI, and ZIP files, and can be installed on jailbroken Kindles and other E Ink devices. Some users have reported a non-intuitive UI and occasional lag.

hackernews · Cider9986 · Jul 29, 11:05 · [Discussion](https://news.ycombinator.com/item?id=49095865)

**Background**: E Ink devices like Kindle and Kobo typically run proprietary firmware with limited format support, often requiring conversion for common formats like EPUB. KOReader is an open-source alternative that runs on these devices, offering extensive file format compatibility and customizable features such as gestures and plugins. It is often used by enthusiasts who jailbreak their devices to gain more control over their reading experience.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/KOReader">KOReader</a></li>
<li><a href="https://koreader.rocks/">KOReader</a></li>

</ul>
</details>

**Discussion**: Community feedback is mixed: many users praise KOReader for significantly improving the reading experience and being superior to proprietary software, while others find the UI non-intuitive and note lag and gesture issues. Some prefer the default viewer and highlight difficulties with bezel alignment and book formatting.

**Tags**: `#e-reader`, `#open-source`, `#kindle`, `#kobo`, `#software`

---

<a id="item-5"></a>
## [Handbook.md Study: Long Policy Docs Fail to Govern AI Agents](https://arxiv.org/abs/2607.25398) ⭐️ 8.0/10

A new benchmark called HANDBOOK.md tests whether AI agents can follow corporate handbooks up to 124 pages long. The best-performing model configuration achieves only a 36.2% pass rate, and agents skip policy rules in 78% of tasks. This finding highlights a critical limitation of current large language models in real-world agentic applications, where strict policy adherence is essential. It undermines the reliability of AI agents in enterprise settings and calls for better long-context handling or alternative designs. The benchmark includes handbooks with up to 100+ pages, and no frontier model cleared 25% of tasks in early tests. Community comments attribute failures to extreme quantization of KV cache in long contexts and poor sampler configurations, with some noting that local inference can alleviate the problem.

hackernews · spIrr · Jul 29, 13:01 · [Discussion](https://news.ycombinator.com/item?id=49096969)

**Background**: Large language models (LLMs) have limited context windows, but recent models claim support for millions of tokens. However, effective use of such long contexts remains challenging due to attention mechanisms' quadratic scaling and memory constraints. Policy compliance is a key requirement for AI agents that autonomously execute tasks in business workflows.

<details><summary>References</summary>
<ul>
<li><a href="https://surgehq.ai/blog/handbook-md">HANDBOOK.md Benchmark: Can AI Agents Follow a 100-Page ...</a></li>
<li><a href="https://elsolitario.org/en/2026/07/29/handbook-md-benchmark-ai-agents-corporate-policies/">AI Agents in HANDBOOK.md: Only 36.2% Pass Rate</a></li>
<li><a href="https://byteiota.com/ai-agents-skip-policy-rules-78-of-tasks-new-data/">AI Agents Skip Policy Rules 78% of Tasks—New Data | byteiota</a></li>

</ul>
</details>

**Discussion**: Users report that long context models often ignore early instructions after a few minutes of interaction, and that explicit instructions in the current prompt work better than persistent files like CLAUDE.md. Some commenters criticize the paper for using AI-generated content in sections like 'Design Principles', noting poor writing quality.

**Tags**: `#large language models`, `#long context`, `#AI agents`, `#policy compliance`, `#LLM limitations`

---

<a id="item-6"></a>
## [Matthew Green on Post-Quantum Crypto and AI Cryptanalysis](https://simonwillison.net/2026/Jul/29/matthew-green/#atom-everything) ⭐️ 8.0/10

Matthew Green argued that the historic transition to post-quantum cryptography makes now the ideal time for AI to advance cryptanalysis, potentially strengthening confidence in new algorithms like HAWK. This insight highlights a unique opportunity for AI to bolster the security of upcoming cryptographic standards, which is critical for protecting data against future quantum attacks. Green references HAWK, a lattice-based signature scheme being considered by NIST, and mentions Impagliazzo's Minicrypt world where public-key cryptography is impossible, suggesting AI could either undermine or validate post-quantum assumptions.

rss · Simon Willison · Jul 29, 18:18

**Background**: Post-quantum cryptography (PQC) aims to develop algorithms secure against both classical and quantum computers. Current public-key algorithms like RSA and ECC are vulnerable to Shor's algorithm on a powerful quantum computer. NIST is standardizing PQC algorithms, with HAWK among those being evaluated. Impagliazzo's five worlds classify computational complexity scenarios; Minicrypt assumes one-way functions exist but no public-key cryptography. The transition to PQC is urgent due to 'harvest now, decrypt later' threats.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Post-quantum_cryptography">Post-quantum cryptography</a></li>
<li><a href="https://hawk-sign.info/">Hawk</a></li>
<li><a href="https://blog.computationalcomplexity.org/2004/06/impagliazzos-five-worlds.html">Computational Complexity: Impagliazzo's Five Worlds</a></li>

</ul>
</details>

**Tags**: `#post-quantum cryptography`, `#AI cryptanalysis`, `#cryptography standards`, `#Matthew Green`, `#public-key algorithms`

---

<a id="item-7"></a>
## [Kimi AI completes $3.5B Series F at $35B valuation](https://36kr.com/p/3916547493965442?f=rss) ⭐️ 8.0/10

Chinese AI startup Moonshot AI (Kimi) raised over $3.5 billion in Series F funding, bringing its post-money valuation to $35 billion. The round was closed early due to oversubscription, and the company has started a pre-IPO round at a $50 billion pre-money valuation. This massive funding round underscores the intense global competition in AI, particularly between the US and China. It signals strong investor confidence in Kimi's technology, especially its K3 model, which reportedly rivals OpenAI and Anthropic's capabilities. Kimi's annualized recurring revenue reached $300 million in June, and daily sales grew at least 6x after the K3 model launch. The company plans to IPO in Hong Kong as early as this year.

rss · 36kr · Jul 29, 11:04

**Background**: Moonshot AI, known for its Kimi chatbot, is a leading Chinese AI startup. The K3 model's release caused a sell-off in tech stocks, reminiscent of the 'DeepSeek moment' where a Chinese model surprised the market. The startup's rapid revenue growth and valuation highlight the high stakes in the AI arms race.

<details><summary>References</summary>
<ul>
<li><a href="https://www.lydaas.com/agentone">AgentOne企业级Agent平台 - 瓴羊 - lydaas.com</a></li>
<li><a href="https://www.aliyun.com/product/agentone">AgentOne</a></li>
<li><a href="https://zhuanlan.zhihu.com/p/1962257214417934168">瓴羊 AgentOne：阿里用十年场景沉淀切入企业级 Agent</a></li>

</ul>
</details>

**Tags**: `#AI funding`, `#startups`, `#Chinese tech`, `#venture capital`

---

<a id="item-8"></a>
## [Tencent Hunyuan Open-Sources AngelSpec](https://36kr.com/newsflashes/3916684374371721?f=rss) ⭐️ 8.0/10

On July 29, 2024, Tencent Hunyuan announced the open-source release of AngelSpec, a speculative decoding framework that includes drafter weights and training code for the Hy3-A21B model. This release provides the full pipeline from training to deployment, enabling researchers and developers to more efficiently accelerate large language model inference using speculative decoding, which can reduce latency by 2-3x without altering output quality. AngelSpec is a torch-native framework covering drafter training, architecture design, and online deployment, and it includes both multi-token prediction (MTP) and block-parallel DFlash drafter types.

rss · 36kr · Jul 29, 12:17

**Background**: Speculative decoding is an optimization technique for large language models where a smaller draft model generates multiple candidate tokens in parallel, and a larger target model verifies them in a single forward pass. This speeds up inference by roughly 2-3 times while preserving the original output distribution. AngelSpec is a unified framework that simplifies the training and deployment of such draft models.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Speculative_decoding">Speculative decoding</a></li>
<li><a href="https://github.com/Tencent/AngelSpec/">GitHub - Tencent/AngelSpec: A unified, torch-native training ...</a></li>

</ul>
</details>

**Tags**: `#speculative decoding`, `#LLM inference`, `#open-source`, `#Tencent`, `#AngelSpec`

---

<a id="item-9"></a>
## [Claude shared chats and Artifacts indexed by Google, Anthropic says by design](https://thenextweb.com/news/claude-shared-chats-artifacts-google-search-indexed) ⭐️ 8.0/10

Over the weekend, Claude users' shared conversation and Artifact links were indexed by Google, exposing sensitive data such as medical records and company files. Anthropic stated that the system was not breached and that indexing occurred because users voluntarily created shareable links that were crawled by search engines, which is by design. This incident highlights significant privacy risks for AI users who rely on shared content features, as sensitive information can become publicly searchable without explicit consent. It raises concerns about the design of sharing functionality in AI chat platforms, especially as similar issues have occurred with ChatGPT and Grok. Anthropic blocked new indexing by Monday afternoon, but previously indexed links remain accessible. Users can revoke shared links in their settings. A similar incident in September 2025 saw nearly 600 Claude conversations indexed.

telegram · zaihuapd · Jul 29, 02:40

**Background**: Claude's sharing feature allows users to create public links to conversations or Artifacts (interactive code previews). These links are intended for direct sharing, but if posted on public websites, search engine crawlers can discover and index them. Similar privacy issues have previously affected ChatGPT and Grok.

<details><summary>References</summary>
<ul>
<li><a href="https://www.zdnet.com/article/claude-ai-shared-chats-indexed-by-google/">Claude AI shared chats indexed by Google - see if your conversations were exposed | ZDNET</a></li>
<li><a href="https://support.claude.com/en/articles/10593882-share-and-unshare-chats">Share and unshare chats | Claude Help Center</a></li>

</ul>
</details>

**Discussion**: Reddit users discovered the exposure using a Google dork query 'site:claude.ai/share'. The community expressed concern over sensitive data leaks and criticized Anthropic for lacking adequate safeguards. Some argued that users should avoid sharing private information.

**Tags**: `#privacy`, `#security`, `#AI`, `#Claude`, `#search indexing`

---

<a id="item-10"></a>
## [Russia charges Telegram founder Durov with aiding terrorism](https://www.interfax.ru/russia/1106228) ⭐️ 8.0/10

Russia's Federal Security Service (FSB) has initiated a criminal case against Telegram founder Pavel Durov under Article 205.1 of the Criminal Code, charging him with aiding terrorism and placing him on an international wanted list. This marks a significant escalation in state action against a major tech platform founder, with potential chilling effects on free speech and platform governance globally, especially for encrypted messaging services like Telegram. The FSB alleges that Telegram's management refused to delete channels, groups, and bots used by Ukrainian intelligence and terrorist organizations to coordinate sabotage, attacks, and fraud in Russia, causing dozens of casualties and billions of rubles in damages.

telegram · zaihuapd · Jul 29, 05:56

**Background**: Telegram is a widely used encrypted messaging app founded by Pavel Durov, who left Russia in 2014. The FSB is the primary security agency in Russia, responsible for counterintelligence and counterterrorism. The charge under Article 205.1 pertains to providing assistance to terrorist activities.

**Tags**: `#Telegram`, `#Pavel Durov`, `#Russia`, `#terrorism`, `#tech policy`

---

<a id="item-11"></a>
## [Report: Hugging Face widely used to generate deepfake nude images](https://www.theverge.com/ai-artificial-intelligence/971723/hugging-face-nudify-deepfake-undress-women-children) ⭐️ 8.0/10

A report from European nonprofit AI Forensics released on July 28 reveals that Hugging Face, an open-source model hosting platform, is being extensively used to generate non-consensual deepfake pornographic content. Researchers found that 7 of the top 9 image editing models on the platform can easily undress women with simple prompts, and a honeypot set up by the organization received over 1,000 requests in 7 days, 73% of which were sexual and nearly 7% targeted children. This report highlights significant gaps in Hugging Face's platform-level safeguards against harmful content, contradicting its own policies against non-consensual sexual content and child nudity. It underscores the urgent need for AI platforms to implement stronger content filtering and output scanning mechanisms to prevent abuse of open-source models. The researchers did not need to craft elaborate jailbreak prompts; simple instructions were sufficient to generate explicit images. AI Forensics recommended that Hugging Face add prompt filtering and output scanning to block harmful image generation.

telegram · zaihuapd · Jul 29, 08:20

**Background**: Deepfake refers to AI-generated synthetic media where a person's image or voice is replaced with someone else's, often using deep learning. Honeypot is a security mechanism that sets up a decoy system to attract and detect malicious activity. Hugging Face is a popular platform for hosting and sharing machine learning models, including image generation models.

<details><summary>References</summary>
<ul>
<li><a href="https://zh.wikipedia.org/wiki/深伪技术">深伪技术 - 维基百科，自由的百科全书</a></li>
<li><a href="https://zh.wikipedia.org/wiki/蜜罐_(電腦科學)">蜜 罐 (電腦科學) - 维基百科，自由的百科全书</a></li>
<li><a href="https://en.wikipedia.org/wiki/Hugging_Face">Hugging Face</a></li>

</ul>
</details>

**Tags**: `#AI安全`, `#深度伪造`, `#Hugging Face`, `#伦理`, `#平台责任`

---

<a id="item-12"></a>
## [China Drafts Anti-Cyberbullying Law Targeting AI-Generated Abuse](https://mp.weixin.qq.com/s/PrzKFhbwjgFEGBPADvFD6Q) ⭐️ 8.0/10

On July 29, 2026, China's Cyberspace Administration of China released a draft anti-cyberbullying law that explicitly regulates the use of AI technology to create and spread cyberbullying content. The 60-article draft also requires online platforms to establish monitoring and protective mechanisms. This is a major regulatory step as it directly addresses the growing challenge of AI-generated cyberbullying, which can scale rapidly and evade traditional moderation. The law could reshape platform responsibility and provide stronger legal protections for victims in China. The draft introduces personality rights protection injunctions, allowing victims to seek court orders to stop ongoing violations. It also clarifies that victims can claim mental damage compensation. The consultation period runs until August 28, 2026.

telegram · zaihuapd · Jul 29, 10:59

**Background**: Cyberbullying in China has become a serious social problem, with cases involving 'doxxing' and coordinated online attacks. Under China's Civil Code, personality rights provide legal protection for name, image, privacy, and reputation. Recently, platforms like Douyin have deployed AI-based detection systems to proactively identify cyberbullying behavior.

<details><summary>References</summary>
<ul>
<li><a href="https://www.guancha.cn/economy/2026_06_12_820308.shtml">抖音上线AI反网暴Agent - 观察者网</a></li>
<li><a href="http://dyzy.sdcourt.gov.cn/dyzy/372897/372830/28560321/index.html">人格权侵害禁令的实务要点与裁判规则</a></li>
<li><a href="https://www.hualianlaw.com/sys-nd/449.html">一文看懂“人格权侵害禁令”！丨上海市华联律师事务所</a></li>

</ul>
</details>

**Tags**: `#AI regulation`, `#cyberbullying`, `#China law`, `#AI ethics`, `#online safety`

---

<a id="item-13"></a>
## [Kimi Launches Cheaper K3-256k with 256K Context](https://www.kimi.com/code/docs/en/kimi-code/models) ⭐️ 7.0/10

Moonshot AI released Kimi K3-256k, a variant of the K3 model with a 256k-token context window, priced at half the quota of the original 1M-context K3 while delivering identical performance within the 256k range. This effectively halves costs for most users who do not need the full 1M context, making advanced AI capabilities more accessible and reducing infrastructure pressure on Kimi's servers. The K3-256k consumes about half the quota of the 1M version, and within 256k context it delivers the same results. The original Kimi K3 has 2.8 trillion parameters and was released with open-source weights on July 16, 2026.

hackernews · monneyboi · Jul 29, 19:25 · [Discussion](https://news.ycombinator.com/item?id=49101852)

**Background**: Context window refers to the maximum number of tokens an AI model can process in a single request. Larger context windows allow handling longer documents or codebases but increase computational cost. Kimi K3 is a large language model from Moonshot AI with a 1M-token context window. The new K3-256k variant targets users who rarely exceed 200k tokens, offering a cost-effective alternative.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/blog/ResterChed/kimi-k3-model-overview-mxfp4-quantization-open-wei">Kimi K 3 Model Overview: 2.8T Parameters, MXFP4 Quantization, and...</a></li>
<li><a href="https://www.digitalapplied.com/blog/ai-context-window-comparison-2026-1m-to-10m-tokens">AI Context Window Comparison 2026: 1M to 10M Tokens</a></li>
<li><a href="https://kimi-ai.chat/models/kimi-k3/">Kimi K 3 : 1M Context , API Pricing & Limits</a></li>

</ul>
</details>

**Discussion**: Community members largely welcomed the 256k variant, calling it a massive price reduction for typical usage. Some users expressed concerns about recent model quality degradation, suspecting quantized models are being served, but the overall sentiment is positive.

**Tags**: `#AI`, `#LLM`, `#model pricing`, `#context window`, `#cost efficiency`

---

<a id="item-14"></a>
## [AI Firms Hire Thousands of Tradespeople for Data Centers](https://www.nytimes.com/2026/07/29/business/economy/data-center-electricians-training.html) ⭐️ 7.0/10

AI companies are recruiting thousands of electricians, carpenters, and other tradespeople to build and maintain data centers, marking a significant labor shift from traditional construction to tech infrastructure. This trend highlights the growing demand for skilled trades in the AI industry, potentially reshaping the labor market and offering high-paying opportunities for tradespeople. However, the boom-bust nature of data center construction could lead to job instability. Data centers now require complex electrical and cooling systems, with future designs leaning toward liquid cooling, which may increase demand for plumbers. The New York Times reports that AI companies are hiring by the thousands, though specific numbers are not given.

hackernews · thm · Jul 29, 14:43 · [Discussion](https://news.ycombinator.com/item?id=49098198)

**Background**: Data centers are facilities that house servers and computing equipment for cloud services, AI training, and other digital operations. As AI models grow larger, they require massive computing power, leading to a surge in data center construction. This creates demand for tradespeople such as electricians for power systems, carpenters for building structures, and soon plumbers for liquid cooling systems.

**Discussion**: Community commenters express mixed views: some warn about the boom-bust nature of data center work leading to income volatility, while others point out the shift toward liquid cooling may increase demand for plumbers. Several commenters are happy for tradespeople getting well-paid work.

**Tags**: `#AI`, `#data centers`, `#skilled trades`, `#labor market`, `#infrastructure`

---

<a id="item-15"></a>
## [SQLite Creator: SQL Changed Jobs, Not Eliminated Them](https://simonwillison.net/2026/Jul/29/d-richard-hipp/#atom-everything) ⭐️ 7.0/10

D. Richard Hipp, creator of SQLite, drew an analogy between the advent of SQL and the evolution of programming jobs, stating that SQL replaced the need for expensive COBOL programmers for data querying but did not eliminate programmers—it simply changed their roles. This perspective offers a reassuring historical precedent for current fears about AI and automation replacing software engineers: new tools shift rather than destroy jobs. It underscores the enduring value of adaptability in technology careers. Hipp was speaking in a YouTube interview, noting that before SQL, generating large-scale data queries was done by COBOL programmers—a specialized and costly role. SQL's declarative syntax allowed users to specify queries simply, automating much of that work.

rss · Simon Willison · Jul 29, 21:15

**Background**: COBOL (Common Business-Oriented Language) is a verbose, English-like programming language designed for business data processing, heavily used in mainframes since the 1960s. SQL (Structured Query Language) is a domain-specific language for managing relational databases, introduced in the 1970s. The shift from COBOL to SQL made data querying accessible to more people, reducing the need for specialized programmers for that task.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/COBOL_programming_language">COBOL programming language</a></li>

</ul>
</details>

**Tags**: `#d-richard-hipp`, `#sql`, `#careers`, `#technology-evolution`

---

<a id="item-16"></a>
## [Guide: Custom MCP server for Claude and ChatGPT](https://simonwillison.net/2026/Jul/29/mcp-in-claude-and-chatgpt/#atom-everything) ⭐️ 7.0/10

Simon Willison published a detailed tutorial explaining how to connect a custom Model Context Protocol (MCP) server to Claude and ChatGPT's standard chat interfaces. This enables developers to extend the capabilities of these AI assistants with custom external tools. This tutorial lowers the barrier for developers to integrate custom tools into widely used AI chat interfaces, demonstrating practical use of the MCP standard. It empowers users to create more versatile AI agents by connecting them to external data sources and services. The setup involves configuring MCP client settings in Claude and ChatGPT's interfaces to point to a locally running MCP server. The server must adhere to the MCP specification and be accessible from the client, requiring careful network and authentication configuration.

rss · Simon Willison · Jul 29, 00:13

**Background**: The Model Context Protocol (MCP) is an open standard introduced by Anthropic in November 2024 to standardize how AI systems like large language models integrate with external tools and data. MCP servers expose specific capabilities (e.g., file system access, database queries) through a unified interface. This tutorial shows how to set up a custom MCP server for use with Claude and ChatGPT, extending their functionality beyond built-in features.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Model_Context_Protocol">Model Context Protocol - Wikipedia</a></li>
<li><a href="https://modelcontextprotocol.io/docs/getting-started/intro">What is the Model Context Protocol (MCP)?</a></li>

</ul>
</details>

**Tags**: `#ai`, `#generative-ai`, `#chatgpt`, `#claude`, `#model-context-protocol`

---

<a id="item-17"></a>
## [Claude Mythos Finds Cryptanalytic Weaknesses in HAWK and AES](https://simonwillison.net/2026/Jul/28/discovering-cryptographic-weaknesses-with-claude/#atom-everything) ⭐️ 7.0/10

Anthropic researchers used Claude Mythos, a powerful LLM, to discover mathematical flaws in the HAWK signature scheme and a reduced-round version of AES, though neither finding has practical impact on current systems. This demonstrates a novel application of LLMs in cryptanalysis, showing they can assist in finding subtle mathematical weaknesses, potentially accelerating cryptographic research despite the lack of immediate practical threat. Claude Mythos Preview ran for 60 hours with an estimated API cost of ~$100,000, requiring human prompts to encourage persistence and higher ambitions. The research also produced CryptanalysisBench, a new evaluation benchmark for LLM cryptanalysis abilities.

rss · Simon Willison · Jul 28, 22:45

**Background**: HAWK is a lattice-based signature scheme submitted to NIST's post-quantum cryptography standardization process, designed to resist both classical and quantum attacks. AES (Advanced Encryption Standard) is a widely used symmetric encryption algorithm; reduced-round versions have fewer encryption rounds and are known to be weaker. Claude Mythos is a highly capable LLM from Anthropic with restricted access due to its ability to find software vulnerabilities.

<details><summary>References</summary>
<ul>
<li><a href="https://hawk-sign.info/">Hawk</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_Mythos">Claude Mythos</a></li>
<li><a href="https://en.wikipedia.org/wiki/Advanced_Encryption_Standard">Advanced Encryption Standard - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#AI`, `#cryptography`, `#LLM`, `#research`

---

<a id="item-18"></a>
## [Modular Data Centers: LEGO-Like Solution to Labor Woes](https://newsletter.semianalysis.com/p/the-wild-wild-west-of-lego-datacenters) ⭐️ 7.0/10

A recent analysis from Semianalysis examines how data center construction is increasingly turning to modular, LEGO-like assembly methods to address critical labor shortages. With hyperscale data center demand surging and skilled labor in short supply, modular construction offers a faster, more scalable path to meeting capacity needs, reshaping the industry's build-out strategies. Modular data centers use prefabricated 'bricks' that can weigh up to 50,000 pounds and are assembled on-site like LEGO sets, enabling faster deployment and reduced reliance on scarce skilled workers.

rss · Semianalysis · Jul 29, 22:09

**Background**: Modular data center systems involve portable, standardized modules that can be quickly deployed and scaled. Traditional data center construction requires extensive on-site labor and faces a severe skilled worker shortage. The modular approach, often compared to assembling LEGO bricks, improves speed, cost-efficiency, and flexibility, making it increasingly attractive for hyperscale projects.

<details><summary>References</summary>
<ul>
<li><a href="https://newsletter.semianalysis.com/p/the-wild-wild-west-of-lego-datacenters">The Wild Wild West Of LEGO Datacenters</a></li>
<li><a href="https://en.wikipedia.org/wiki/Modular_data_center">Modular data center - Wikipedia</a></li>
<li><a href="https://www.bjumper.com/en_GB/blog/technology-3/modular-data-center-architecture-181">How would a data center look if LEGO designed it?</a></li>

</ul>
</details>

**Tags**: `#datacenters`, `#infrastructure`, `#modularization`, `#labor`, `#tech industry`

---

<a id="item-19"></a>
## [Fabric Tactile Sensing Startup YaoLe Tech Raises Pre-A+ for Data Gloves](https://36kr.com/p/3915175290901889?f=rss) ⭐️ 7.0/10

YaoLe Tech, a flexible tactile sensing startup, has closed a Pre-A+ funding round led by Dinghe Gaoda, with participation from listed companies Changshu Auto Trim and ZuLong Entertainment. The funds will accelerate development of fabric-based data gloves that embed sensing directly into the fabric weave, targeting embodied intelligence and world model data collection. This funding highlights the critical shortage of high-quality real-world tactile data for training embodied AI and world models, and positions data gloves as a key interface for collecting such data. YaoLe's integrated fabric sensor design could improve data reliability and scalability, addressing a bottleneck in the robotics and AI industries. YaoLe's gloves use a proprietary 'metal yarn + sandwich matrix' sensor, weaving conductive metal alloy yarns directly into a fabric matrix. This eliminates layer slippage and sweat issues common in multi-layer printed film designs, achieving material-device integration. The gloves also feature modular design with washable fabric and an integrated control box that includes a wide-angle camera for cross-validation.

rss · 36kr · Jul 29, 01:30

**Background**: Embodied intelligence refers to AI systems that learn from and interact with the physical world through sensors and actuators, requiring rich multimodal data including touch. World models are AI systems that learn an internal representation of environments to simulate physical dynamics. However, tactile data is difficult to simulate accurately due to complex physics like pressure distribution and friction, creating a sim-to-real gap. Data gloves that capture real human touch interactions are one solution to provide high-quality training data for generalist embodied models.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Embodied_intelligence">Embodied intelligence</a></li>
<li><a href="https://en.wikipedia.org/wiki/World_model_(artificial_intelligence)">World model (artificial intelligence)</a></li>
<li><a href="https://arxiv.org/html/2602.21625v1">Tacmap: Bridging the Tactile Sim-to-Real Gap via Geometry ...</a></li>

</ul>
</details>

**Tags**: `#flexible tactile sensing`, `#embodied intelligence`, `#robotics`, `#startup funding`, `#data gloves`

---

<a id="item-20"></a>
## [China Smart Hardware Enters AI-Native Phase, Report Says](https://36kr.com/p/3915066350327176?f=rss) ⭐️ 7.0/10

36Kr Research Institute released the 2026 China Smart Hardware Industry Development Report, revealing that the sector has moved from standalone smart devices to an AI-native phase where on-device intelligence redefines product logic. Key trends include rising consumer adoption (80.8% have used AI hardware) and breakthroughs in edge AI chips, lightweight large models, and multi-sensor fusion. This report provides a systematic analysis of China's smart hardware industry shift, offering crucial insights for investors, manufacturers, and policymakers. The transition to AI-native hardware with on-device intelligence could reshape global competition, as Chinese firms move from low-cost manufacturing to technology-ecosystem-service value delivery. The report notes that 32% of consumers plan to increase AI hardware spending in the next three months. It also highlights challenges: fragmented competition, supply chain cost pressure, insufficient scaled deployment, and rising data security compliance requirements. Smart robots, both humanoid and non-humanoid, are identified as a new growth driver.

rss · 36kr · Jul 28, 23:30

**Background**: Smart hardware refers to physical devices that integrate AI capabilities for sensing, processing, and decision-making. On-device AI (edge AI) allows these devices to run algorithms locally without constant cloud connectivity, reducing latency and improving privacy. Key enabling technologies include edge AI chips (specialized NPUs), lightweight large models (compressed for local use), and multi-sensor fusion (combining camera, radar, lidar data for comprehensive perception).

<details><summary>References</summary>
<ul>
<li><a href="https://baike.baidu.com/item/端侧AI芯片/67904669">端侧AI芯片 - 百度百科</a></li>
<li><a href="https://zhuanlan.zhihu.com/p/1960373488725497644">多传感器融合技术介绍 - 知乎 - 知乎专栏</a></li>
<li><a href="https://xie.infoq.cn/article/8033f733e4cc8c9d35b2433ba">文心 大 模 型 ERNIE-Tiny...</a></li>

</ul>
</details>

**Tags**: `#smart hardware`, `#AI`, `#industry report`, `#China`, `#technology trends`

---

<a id="item-21"></a>
## [US awards $874M to 7 tech firms for semiconductor R&D](https://36kr.com/newsflashes/3916694245469826?f=rss) ⭐️ 7.0/10

The U.S. Department of Commerce announced on July 29 that it has signed preliminary agreements to provide $874 million in federal incentives to seven companies for semiconductor research and development in areas such as integrated photonics and advanced packaging. This funding, part of the CHIPS Act, aims to strengthen U.S. leadership in critical semiconductor technologies. It could accelerate innovations in integrated photonics and advanced packaging, which are essential for faster, more efficient computing and communications. The announcement did not name the seven recipient companies. The funding covers integrated photonics, computing architectures, advanced packaging, substrates, materials, and memory technologies.

rss · 36kr · Jul 29, 12:27

**Background**: The CHIPS Act, signed into law in 2022, allocates over $50 billion to boost U.S. semiconductor manufacturing and R&D. Integrated photonic circuits use light instead of electrons to process information, enabling higher speed and lower power consumption. Advanced packaging techniques combine multiple semiconductor dies into a single package, improving performance and reducing size and cost.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Integrated_photonic_circuit">Integrated photonic circuit</a></li>
<li><a href="https://en.wikipedia.org/wiki/Advanced_packaging_(semiconductors)">Advanced packaging (semiconductors) - Wikipedia</a></li>
<li><a href="https://www.synopsys.com/glossary/what-is-advanced-semiconductor-packaging.html">What is Advanced Semiconductor Packaging? - Synopsys</a></li>

</ul>
</details>

**Tags**: `#semiconductor`, `#CHIPS Act`, `#R&D funding`, `#US tech policy`, `#advanced packaging`

---

<a id="item-22"></a>
## [ICLR 2027 deadline precedes NeurIPS 2026 decisions](https://www.reddit.com/r/MachineLearning/comments/1v9v4e7/iclr_2027_deadline_is_before_neurips_2026/) ⭐️ 7.0/10

The ICLR 2027 full paper deadline is set for September 16, which is 8 days before NeurIPS 2026 decisions are announced, forcing authors to decide whether to submit before receiving NeurIPS feedback. This scheduling conflict creates a dilemma for researchers who might improve their papers based on NeurIPS reviews, potentially reducing submission quality or causing unfair rejections. The ICLR 2027 deadline is September 16, while NeurIPS 2026 decisions are expected around September 24, leaving an 8-day gap with no time for revisions before the ICLR deadline.

reddit · r/MachineLearning · /u/1414vo · Jul 29, 12:43

**Background**: ICLR (International Conference on Learning Representations) and NeurIPS (Conference on Neural Information Processing Systems) are top-tier machine learning conferences. Authors often submit to multiple venues, revising based on reviews from earlier deadlines. Typically, deadlines are staggered to allow revisions, but here the ICLR deadline falls before NeurIPS decisions, breaking that pattern.

**Tags**: `#machine learning`, `#conferences`, `#ICLR`, `#NeurIPS`, `#research deadlines`

---

<a id="item-23"></a>
## [ncnn Vulkan Backend Enables 10x ML Inference Speedup on Edge](https://www.reddit.com/r/MachineLearning/comments/1v9s4mz/vendoragnostic_ml_inference_on_production_edge/) ⭐️ 7.0/10

PostSlate achieved 10x speedup for ML inference on production edge devices by using ncnn's Vulkan backend instead of CPU-based ONNX runtime, with ArcFace R50 dropping from 30ms to 3ms and SCRFD from 25ms to 2.5ms on an NVIDIA 4070. This approach removes dependency on vendor-specific runtimes (like CUDA), enabling truly cross-platform GPU inference on edge devices. It solves a common pain point for developers deploying ML on diverse hardware without forcing users to install additional drivers. The speedup comes from GPU offloading via Vulkan, but the key advantage is that Vulkan drivers are already present on almost every machine, including NVIDIA, AMD, Intel, and Apple Silicon. Model size also reduces: ArcFace from 174MB (ONNX fp32) to 87MB (ncnn fp16 weight storage).

reddit · r/MachineLearning · /u/ppchaos · Jul 29, 10:22

**Background**: ncnn is a high-performance neural network inference framework developed by Tencent, designed for mobile and edge devices with no third-party runtime dependencies. Vulkan is a cross-platform GPU API that provides low-level access to GPU hardware, making it suitable for ML inference across different vendors. Traditional approaches often rely on CUDA (NVIDIA-only) or vendor-specific runtimes, limiting deployment flexibility.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/Tencent/ncnn">Tencent/ ncnn : ncnn is a high-performance neural network inference ...</a></li>
<li><a href="https://github.khronos.org/Vulkan-Site/tutorial/latest/ML_Inference/Vulkan_Compute_for_ML/01_introduction.html">Vulkan Compute for ML: Introduction :: Vulkan Documentation Project</a></li>
<li><a href="https://www.lei.chat/posts/gpgpu-ml-inference-and-vulkan-compute/">GPGPU, ML Inference, and Vulkan Compute | Lei.Chat()</a></li>

</ul>
</details>

**Tags**: `#machine learning`, `#inference`, `#Vulkan`, `#edge devices`, `#cross-platform`

---

<a id="item-24"></a>
## [xAI sues Minnesota to block AI nudification ban](https://www.cbsnews.com/minnesota/news/elon-musk-xai-sues-minnesota-law-banning-ai-nudification/) ⭐️ 7.0/10

Elon Musk's AI company xAI filed a federal lawsuit on July 28 against Minnesota to block a state law banning AI-powered nudification, arguing it violates the First Amendment by imposing overly broad restrictions on speech. This case could set a precedent for how state-level AI regulations interact with free speech protections, potentially influencing the national debate on AI governance and the balance between innovation and harm prevention. The Minnesota law imposes strict liability on AI providers for generating non-consensual nude images, even if the content has artistic or educational value, which xAI argues chills legitimate speech. Minnesota Attorney General Keith Ellison defended the law as necessary to protect victims from harmful deepfakes.

telegram · zaihuapd · Jul 29, 02:30

**Background**: AI nudification tools use deep learning to generate nude images from clothed photos, raising serious privacy and consent concerns. Several U.S. states have passed laws targeting non-consensual deepfake pornography, but this is one of the first legal challenges by an AI company against such regulations on free speech grounds.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2411.09751v1">Analyzing the AI Nudification Application Ecosystem</a></li>
<li><a href="https://contentmavericks.com/best-nudify-app/">7 Best Nudify Apps 2026 (#1 AI Nudifier For Photos)</a></li>

</ul>
</details>

**Tags**: `#AI regulation`, `#xAI`, `#Elon Musk`, `#First Amendment`, `#AI ethics`

---

<a id="item-25"></a>
## [Windows 11 silently installs OneDrive Photos with face scanning](https://www.windowslatest.com/2026/07/29/windows-11-is-quietly-installing-onedrive-photos-another-image-viewer-that-nobody-asked-for) ⭐️ 7.0/10

Microsoft is automatically installing the OneDrive Photos app on some Windows 11 devices without user consent. If users grant authorization, the app can scan faces in photos to organize them by person. This practice raises significant privacy concerns because users may not expect an automatically installed app to have facial recognition capabilities. It also underscores Microsoft's aggressive push to integrate AI features into Windows, potentially at the expense of user control and transparency. The OneDrive Photos app uses AI to recognize and group similar faces, similar to other photo management tools. Notably, users can only name or confirm groups that OneDrive has already created, not manually tag faces themselves, and a previous report indicated a limit of disabling face scanning only three times per year.

telegram · zaihuapd · Jul 29, 05:37

**Background**: Windows 11 has a history of automatically installing suggested apps, often without clear user notification. OneDrive Photos is a new image viewer integrated with Microsoft's OneDrive cloud storage service, designed to leverage AI for photo organization. While facial recognition in photo apps is common, the automatic installation without explicit consent has drawn criticism for bypassing user choice.

<details><summary>References</summary>
<ul>
<li><a href="https://www.windowslatest.com/2026/07/29/windows-11-is-quietly-installing-onedrive-photos-another-image-viewer-that-nobody-asked-for/">Windows 11 is quietly installing OneDrive Photos, and it ...</a></li>
<li><a href="https://www.windowscentral.com/microsoft/onedrives-ai-face-scanning-feature-suggests-it-can-only-be-disabled-3-times-a-year-but-that-doesnt-seem-right">OneDrive's AI face scanning feature comes under fire ...</a></li>
<li><a href="https://learn.microsoft.com/en-us/answers/questions/5779398/onedrive-people">OneDrive People - Microsoft Q&A</a></li>

</ul>
</details>

**Tags**: `#Windows 11`, `#OneDrive`, `#Privacy`, `#Facial Recognition`, `#Software Updates`

---

<a id="item-26"></a>
## [China Bans 'Little Blue Lights' for Autonomous Driving Indicators on New Vehicles](https://www.yicai.com/brief/103296987.html) ⭐️ 7.0/10

China has banned the installation of blue indicator lights ('小蓝灯') on newly certified vehicles starting July 27, 2026, because they violate GB4785, the national standard for automotive exterior lighting. The ban applies to vehicles seeking new type certification after that date. This decision creates a conflict with a previous regulation that mandated blue-green autonomous driving indicator lights for L3+ vehicles starting July 1, 2025. It highlights a regulatory gap that automakers must navigate, potentially delaying the deployment of visible autonomous driving status indicators. The ban is driven by GB4785, which does not permit blue exterior lights (reserved for emergency vehicles) for indicating driving status. However, a separate standard for autonomous driving system (ADS) indicator lights specifies blue-green as the required color for L3+ vehicles, creating an inconsistency.

telegram · zaihuapd · Jul 29, 07:12

**Background**: In China, GB4785-2019 governs the installation of external lighting and light-signalling devices on motor vehicles, specifying allowed colors such as white, amber, and red, while blue is reserved for emergency vehicles. Separately, the autonomous driving system (ADS) indicator light standard, developed by SAE and adopted in China, mandates a blue-green light to signal when the vehicle is under autonomous control. The ban on 'little blue lights' suggests that the ADS indicator light standard has not yet been reconciled with GB4785, leading to the prohibition of blue lights on new certifications until harmonization is achieved.

<details><summary>References</summary>
<ul>
<li><a href="https://baike.baidu.com/item/自动驾驶系统标志灯/67918376">自动驾驶系统标志灯 - 百度百科</a></li>
<li><a href="https://www.autoengineer.cn/gb/40">GB4785-2019《汽车及挂车外部照明和光信号装置的安装规定》-汽车工程...</a></li>
<li><a href="https://zhuanlan.zhihu.com/p/1920215527340606275">智驾“小蓝灯”来了，将于7月1日正式实施，L3级以上车辆必须强制安装！ ...</a></li>

</ul>
</details>

**Tags**: `#autonomous driving`, `#regulation`, `#automotive`, `#China`, `#EV`

---

<a id="item-27"></a>
## [Xianyu's AI Service Orders Surge 157% in H1 2024](https://www.bianews.com/news/flash?id=242540) ⭐️ 7.0/10

In the first half of 2024, Xianyu recorded 9.816 million AI service orders, a 157% increase year-over-year, with nearly 5 million buyers purchasing AI services. This demonstrates strong real-world demand for AI services among Chinese consumers, especially in programming, which saw 1732% growth, signaling a shift toward AI-aided productivity. The fastest-growing category was AI programming and website building, with orders up 1732% year-over-year, followed by AI comic series at 1425% and AI PPT/office tools at 264%.

telegram · zaihuapd · Jul 29, 09:14

**Background**: Xianyu is Alibaba's second-hand goods marketplace that has expanded into digital services trading. AI services on the platform cover programming, design, writing, and content creation, reflecting a trend where individuals and small businesses leverage AI tools for productivity without deep technical expertise.

<details><summary>References</summary>
<ul>
<li><a href="https://m.ithome.com/html/983021.htm">闲 鱼 ：2026 上半年 AI 服 务 订单达 981.6 万单同比增长 157...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#marketplace`, `#growth`, `#China`, `#programming`

---

<a id="item-28"></a>
## [China Telecom Halts Third-Party Online SIM Card Sales](https://www.189.cn/web/notice/detail?order=1&amp;offerCode=519526800001&amp;provinceCode=600304) ⭐️ 7.0/10

China Telecom posted a notice on its official website, dated July 31, stating that starting August 1, third-party internet channels will no longer provide SIM card application services for its mobile network. This policy shift will directly affect users who rely on e-commerce platforms like JD.com and Tmall to purchase China Telecom SIM cards, potentially reducing fraud and streamlining customer acquisition for the carrier. Two nearly identical notices were found, differing only in the provinceCode parameter, suggesting the change applies across multiple provinces. The exact implementation details and exceptions (if any) have not been disclosed.

telegram · zaihuapd · Jul 29, 12:45

**Background**: China Telecom is one of the three major state-owned telecom operators in China, traditionally offering SIM cards through physical stores, official website, and third-party internet partners. The provinceCode in the URL is a code referencing China's administrative divisions, used by telecom systems to identify service regions.

<details><summary>References</summary>
<ul>
<li><a href="https://zh.wikipedia.org/zh-hk/中华人民共和国行政区划代码">中華人民共和國行政區劃代碼 - 維基百科，自由的百科全書</a></li>

</ul>
</details>

**Tags**: `#telecom`, `#China`, `#policy change`, `#SIM card`, `#Internet services`

---