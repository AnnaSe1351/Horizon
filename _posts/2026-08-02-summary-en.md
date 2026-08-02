---
layout: default
title: "Horizon Summary: 2026-08-02 (EN)"
date: 2026-08-02
lang: en
---

> From 52 items, 13 important content pieces were selected

---

1. [Karpathy's 'Pelican on a Bicycle' Tweet Sparks AI Benchmark Debate](#item-1) ⭐️ 8.0/10
2. [Tech Giants Back Open-Weight AI in Microsoft-Led Letter](#item-2) ⭐️ 8.0/10
3. [How ESL Vocabulary Lists Have Shifted Since 1953](#item-3) ⭐️ 7.0/10
4. [Bor: Open-source real-time policy management for Linux desktops](#item-4) ⭐️ 7.0/10
5. [Truth Social Launches $100K-per-Month API for Fast Access to Trump Posts](#item-5) ⭐️ 7.0/10
6. [Google Earth suspends AI image generator after fake disaster images](#item-6) ⭐️ 7.0/10
7. [Chinese AI Models Sweep Top Five in OpenRouter Global Usage Rankings](#item-7) ⭐️ 7.0/10
8. [Context Degradation in LLMs: Research Findings and Practical Mitigation Habits](#item-8) ⭐️ 7.0/10
9. [CausalVLBench: New Benchmark for Visual Causal Reasoning in VLMs](#item-9) ⭐️ 7.0/10
10. [AI Chip Counts Double Every 9 Months, Projected to Hit 200 Million by 2028](#item-10) ⭐️ 7.0/10
11. [Apple Caps Bug Reports, Adds 30-Day Cooldown to Thwart AI-Generated Spam](#item-11) ⭐️ 7.0/10
12. [Chinese AI Framework Detects Bitcoin Money Laundering with ~90% Accuracy](#item-12) ⭐️ 7.0/10
13. [Microplastics Found in 92% of Animals Near Deep-Sea Hydrothermal Vents](#item-13) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Karpathy's 'Pelican on a Bicycle' Tweet Sparks AI Benchmark Debate](https://twitter.com/karpathy/status/2083749667410727319) ⭐️ 8.0/10

Andrej Karpathy tweeted about using 'pelican on a bicycle' as an AI benchmark, triggering a debate about whether it truly tests physical world understanding. The benchmark, originally created by Simon Willison, asks models to generate an SVG of a pelican riding a bicycle. This debate highlights the growing challenge of evaluating AI models' understanding of the physical world beyond simple text or image tasks. How the community responds could shape future benchmark design and whether models are seen as genuinely intelligent or just overfitted to popular prompts. The benchmark is informal and relies on a single prompt: 'Generate an SVG of a pelican riding a bicycle.' Some community members argue that current models show janky results and that multi-year exposure to AI content has lowered quality expectations, while others see it as a useful qualitative measure of progress.

hackernews · delichon · Aug 2, 04:05 · [Discussion](https://news.ycombinator.com/item?id=49140998)

**Background**: The 'pelican on a bicycle' benchmark was created by developer Simon Willison in late 2024 as a way to test LLMs' code generation and spatial reasoning abilities. It has gained popularity as an informal benchmark because it requires models to understand the relationship between a pelican and a bicycle in a visual code output. Recent analysis, such as Dylan Castillo's 'pelicanmaxxing' investigation, has examined whether AI labs might be training models specifically on this benchmark, though data suggests pelicans are not unusually common in model outputs.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/Pelican_on_a_bicycle_AI_benchmark">Pelican on a bicycle (AI benchmark)</a></li>
<li><a href="https://github.com/simonw/pelican-bicycle">GitHub - simonw/ pelican - bicycle : LLM benchmark : Generate an SVG...</a></li>
<li><a href="https://dylancastillo.co/posts/pelicanmaxxing.html">Are AI labs pelicanmaxxing? – Dylan Castillo</a></li>

</ul>
</details>

**Discussion**: Commenters expressed mixed views: some worried that the benchmark is being treated as 'exhausted' and that AI exposure has lowered quality expectations, while others defended it as a useful qualitative benchmark for physical world understanding. One commenter noted that Anthropic models seem specifically trained on three.js code, making such benchmarks less indicative of general ability, while another joked about generating an SVG of an AI generating an SVG of a pelican on a bicycle.

**Tags**: `#AI`, `#benchmarking`, `#machine learning`, `#evaluation`, `#Karpathy`

---

<a id="item-2"></a>
## [Tech Giants Back Open-Weight AI in Microsoft-Led Letter](https://simonwillison.net/2026/Aug/2/open-letters/#atom-everything) ⭐️ 8.0/10

Simon Willison summarized recent open letters on AI development, highlighting Microsoft's 'Open Weights and American AI Leadership' letter dated July 24th, signed by 235 AI-adjacent companies including NVIDIA, Amazon, and OpenAI. Anthropic notably did not sign and published its own opposing position three days later. This open letter reflects a major industry divide over open-weight AI policy, potentially influencing U.S. government decisions on whether to restrict such models. The outcome will shape the future of open-source AI and competition among AI providers. The Microsoft letter explicitly supports distillation, the practice of training models on other models' outputs, arguing policymakers should not conflate it with misappropriation. Anthropic's response, led by CEO Dario Amodei, calls for a crackdown on industrial-scale distillation operations while claiming it has never advocated a ban on open-weights models.

rss · Simon Willison · Aug 2, 04:16

**Background**: Open-weight models publicly release the trained numerical parameters (weights) of an AI model, allowing anyone to download, run, and fine-tune them, though they are not fully open source since training data and code may remain proprietary. The letter appears designed to counter U.S. government instincts to ban or limit such models over safety concerns, especially after a directive suspended access to Claude Fable 5. Proponents argue open weights reduce single points of failure and enable broader scrutiny, while critics worry about misuse by authoritarian governments or malicious actors.

<details><summary>References</summary>
<ul>
<li><a href="https://www.nytimes.com/2026/07/28/technology/open-weight-ai.html">What Is Open-Weights A.I.? - The New York Times</a></li>
<li><a href="https://hai.stanford.edu/ai-definitions/what-is-an-open-weight-model">What is an Open-Weight Model? - Stanford HAI</a></li>

</ul>
</details>

**Tags**: `#AI policy`, `#open weights`, `#open source`, `#AI regulation`, `#industry`

---

<a id="item-3"></a>
## [How ESL Vocabulary Lists Have Shifted Since 1953](https://pudding.cool/2026/07/essential-words/) ⭐️ 7.0/10

An interactive data analysis from Pudding.cool reveals that the vocabulary taught to English language learners underwent dramatic changes between 1953 and 2023, with many traditional words replaced by newer terms reflecting social shifts. This matters because it shows how language education mirrors broader cultural and social trends, affecting the priorities and values conveyed to millions of English learners worldwide. It also sparks discussion about the trade-offs in choosing which words to teach. The analysis found that the 'Social-Communicative' level of vocabulary stayed roughly the same size, but nearly a quarter of the words from the 1953 list disappeared by 2023, while 39% of the 2023 words are new. Words like humble, loyalty, fellowship, and polite gave way to community, identity, organization, ethnic, gender, and narrative.

hackernews · c-oreills · Aug 2, 15:41 · [Discussion](https://news.ycombinator.com/item?id=49145590)

**Background**: The analysis likely compares curated word lists used in English language teaching, such as the General Service List, which have been influential in ESL curricula for decades. Such lists are designed to prioritize the most useful words for learners, but what counts as 'useful' shifts with cultural, technological, and economic changes. The study period from 1953 to 2023 captures post-war, late-20th-century, and digital-era priorities in vocabulary instruction.

**Discussion**: Community comments range from practical reflections on building vocabulary lists for other languages, to debates about language change and inequality shaping word choices. Some users criticized the article's scrolling interaction as frustrating, while others engaged deeply with the linguistic and pedagogical implications, such as the shift from words about close personal relationships to more abstract social categories.

**Tags**: `#English language learning`, `#vocabulary`, `#linguistics`, `#education`, `#data analysis`

---

<a id="item-4"></a>
## [Bor: Open-source real-time policy management for Linux desktops](https://getbor.dev/blog/2026-08-02-bor-v080-release/) ⭐️ 7.0/10

Bor 0.8 has been released as an open-source system for centralized Linux desktop management, featuring a lightweight Go agent and a central server that streams policies (Firefox, Chrome, KDE, dconf, polkit, package management, and more) to clients in real time over mTLS/gRPC. New in 0.8 are policy types for Thunderbird, Microsoft Edge for Business, and FirewallD zones. Bor addresses a long-standing gap in Linux workstation management, providing IT teams and organizations a modern, real-time alternative to manual configuration or legacy configuration management tools. With support for common desktop stacks and growing policy coverage, it could make Linux a more viable managed platform for enterprises and non-profits. The agent communicates with the server via mTLS/gRPC, and policies are streamed in real time without polling. Version 0.8 adds Thunderbird, Microsoft Edge for Business, and FirewallD zone policies; the community has raised questions about custom scripts, user mapping (e.g., with Authentik), drift enforcement, and why mTLS was chosen over SSH.

hackernews · eniac111 · Aug 2, 09:06 · [Discussion](https://news.ycombinator.com/item?id=49142569)

**Background**: Bor is built for centralized management of Linux desktops, streaming configuration policies to client machines over a secure gRPC channel. The policies cover desktop environments and system services, including dconf (the low-level configuration system used by GNOME), polkit (an authorization framework for fine-grained access control), and FirewallD zones (which define trust levels for network interfaces). This approach resembles mobile device management (MDM) but for Linux workstations, targeting both small-scale deployments and enterprise fleets.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Dconf">dconf - Wikipedia</a></li>
<li><a href="https://linuxconfig.org/introduction-to-polkit-navigating-authorization-frameworks-in-linux">Introduction to Polkit: Navigating Authorization Frameworks in Linux</a></li>
<li><a href="https://firewalld.org/documentation/zone/">Documentation - Zone | firewalld</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion is largely positive and practical, with commenters asking about integration details such as running custom scripts and mapping external identity providers like Authentik to Linux users. Several questions probe the architecture—why mTLS instead of SSH, how policy drift is enforced without polling—and others ask how Bor compares to existing tools or System76's Cosmic Sync. There is also feedback on documentation quality, specifically suggesting replacing ASCII diagrams with Mermaid.

**Tags**: `#linux-desktop`, `#policy-management`, `#open-source`, `#gRPC`, `#devops`

---

<a id="item-5"></a>
## [Truth Social Launches $100K-per-Month API for Fast Access to Trump Posts](https://36kr.com/newsflashes/3922088228957576?f=rss) ⭐️ 7.0/10

On August 1, Truth Social officially launched the 'Truth API', a data feed that sells Wall Street firms early access to posts from top accounts, including President Donald Trump's, for $100,000 per month. The service is specifically marketed to high-frequency trading firms. The API raises serious concerns about insider trading and conflicts of interest, as Trump's social media posts frequently move stock, bond, and commodity markets. If paying clients can react faster than ordinary investors, it could undermine market fairness and intensify regulatory scrutiny of how political communications are monetized. The service costs $100,000 per month and targets high-frequency trading firms, offering what Truth Social calls the 'fastest' real-time access to posts from the highest-ranking accounts. Critics note that even though posts are theoretically released to the public simultaneously, faster data delivery combined with automated trading systems could let paying subscribers act before retail investors.

rss · 36kr · Aug 2, 08:15

**Background**: Truth Social is a social media platform owned by Trump Media & Technology Group (TMTG), which announced plans for the Truth API in mid-July. Trump frequently uses Truth Social to make policy announcements on tariffs, wars, and central bank leadership, and markets often react sharply to these posts. For example, in April, Trump's praise of Palantir Technologies and Intel caused immediate stock price movements. The API's commercial model effectively charges financial firms for a speed advantage in reacting to these market-moving statements.

<details><summary>References</summary>
<ul>
<li><a href="https://www.businessinsider.com/trump-truth-social-early-access-api-markets-2026-8">What smart people are saying about Trump Media charging for early access to the president's Truth Social posts</a></li>
<li><a href="https://thehill.com/policy/technology/5972998-trump-media-technology-group-launch-truth-api/">Trump Media & Technology Group to launch Truth API to sell to Wall Street</a></li>
<li><a href="https://time.com/article/2026/07/17/truth-social-api-wall-street-trump-media/">Trump Media to Sell Traders 'the Fastest' Access to Truth ...</a></li>

</ul>
</details>

**Tags**: `#API`, `#finance`, `#social media`, `#ethics`, `#regulation`

---

<a id="item-6"></a>
## [Google Earth suspends AI image generator after fake disaster images](https://36kr.com/newsflashes/3922077104664199?f=rss) ⭐️ 7.0/10

Google suspended the AI image generation feature in Google Earth less than 48 hours after its launch. The feature, called Nano Banana, allowed users to generate realistic imagery of locations using text prompts, and was rolled back due to policy violations involving fake disaster scenes. This incident highlights the growing risk of AI-generated content being blended with real satellite imagery to spread misinformation. It also demonstrates the tension between AI innovation and the need for stronger safety guardrails in geospatial tools. The AI-generated images were watermarked and never appeared in the public Google Earth experience, but users shared screenshots outside the platform. Google said it is working on stronger guardrails before restoring the feature.

rss · 36kr · Aug 2, 07:51

**Background**: Google Earth's image generation feature, dubbed 'Nano Banana', was built on the company's Gemini AI model and allowed users to reimagine locations with text prompts, such as turning a vacant lot into a park. Previous research on geospatial misinformation has shown that location-based false narratives can spread rapidly on social media, especially when they mimic local news or depict disasters. The rollout was intended for creative and professional use, but the rapid creation of realistic fake disaster imagery triggered an immediate backlash.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.google/products-and-platforms/products/earth/nano-banana-google-earth-image-generation/">Transform any place with Nano Banana in Google Earth</a></li>
<li><a href="https://www.businessinsider.com/google-earth-nano-banana-gemini-ai-satellite-image-generation-function-2026-7">Google Earth's new AI image generation function didn't survive a day after users deepfaked disasters</a></li>

</ul>
</details>

**Tags**: `#AI安全`, `#谷歌地球`, `#虚假信息`, `#图像生成`, `#内容审核`

---

<a id="item-7"></a>
## [Chinese AI Models Sweep Top Five in OpenRouter Global Usage Rankings](https://36kr.com/newsflashes/3921989528432259?f=rss) ⭐️ 7.0/10

Chinese AI models claimed all top five spots in OpenRouter's weekly global AI model usage rankings, led by Xiaomi MiMo-V2.5 and DeepSeek, signaling rapid adoption of Chinese LLMs.

rss · 36kr · Aug 2, 06:14

**Tags**: `#AI`, `#LLM`, `#OpenRouter`, `#Chinese tech`, `#model adoption`

---

<a id="item-8"></a>
## [Context Degradation in LLMs: Research Findings and Practical Mitigation Habits](https://www.reddit.com/r/MachineLearning/comments/1vdsgcj/context_degradation_in_llms_what_the_papers/) ⭐️ 7.0/10

A Reddit user posted a practical guide in r/MachineLearning that synthesizes what research papers actually show about context degradation in large language models, along with habits they built for long analysis sessions. The post combines research-backed findings with hands-on strategies for maintaining model performance over extended conversations. This matters because context degradation is a well-documented but often overlooked problem that affects instruction fidelity and factual recall in long sessions. The post offers practitioners concrete habits to combat the issue, which can improve the reliability of LLM-driven analysis in real-world workflows. The guide is grounded in academic papers that show LLMs do not process all context tokens uniformly—performance can degrade as input length grows. Suggested mitigations typically include context isolation, retrieval-augmented generation, and explicit memory management, though the specific habits from the post are not detailed in the snippet.

reddit · r/MachineLearning · /u/usernamehere93 · Aug 2, 20:20

**Background**: LLMs process a limited context window—the number of tokens they can handle at once—and researchers have observed that performance on tasks using tokens near the start or middle of the input often drops as the window fills up. This phenomenon is sometimes called context degradation, context rot, or Context Degradation Syndrome, and it can undermine instruction following and accurate recall of earlier information. Techniques like truncation, RAG, and memory buffering are commonly used to manage context length and reduce these effects.

<details><summary>References</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/context-degradation-in-large-language-models">Context Degradation in LLMs</a></li>
<li><a href="https://www.trychroma.com/research/context-rot">Context Rot: How Increasing Input Tokens Impacts LLM Performance | Chroma</a></li>
<li><a href="https://www.morphllm.com/context-rot">Context Rot: Why LLMs Degrade as Context Grows (Complete Guide)</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#context degradation`, `#prompting`, `#practical AI`

---

<a id="item-9"></a>
## [CausalVLBench: New Benchmark for Visual Causal Reasoning in VLMs](https://www.reddit.com/r/MachineLearning/comments/1vdd7ty/r_causalvlbench_benchmarking_visual_causal/) ⭐️ 7.0/10

A new benchmark called CausalVLBench has been proposed to evaluate the visual causal reasoning capabilities of large vision-language models (VLMs). It fills a gap by providing a dedicated evaluation suite for this specific ability. Causal understanding is crucial for robust AI, yet existing VLM benchmarks focus on perception and basic reasoning. CausalVLBench enables researchers to measure and compare how well models infer cause-effect relationships from visual scenes, guiding future model development. The benchmark likely includes tasks that require counterfactual reasoning, intervention inference, and temporal causality in images or videos. Specific dataset construction, task formats, and model performance results are not available in the provided content.

reddit · r/MachineLearning · /u/moschles · Aug 2, 09:07

**Background**: Large vision-language models (VLMs) combine visual and textual understanding, enabling tasks like image captioning and visual question answering. Visual causal reasoning goes a step further, requiring models to understand cause-and-effect relationships, such as what would happen if an object were moved or removed. Benchmarks are essential tools for systematically evaluating and comparing model capabilities in the research community.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/blog/vlms">Vision Language Models Explained</a></li>
<li><a href="https://scispace.com/pdf/causal-reasoning-meets-visual-representation-learning-a-3fro8z70.pdf">Causal Reasoning Meets Visual Representation</a></li>
<li><a href="https://openreview.net/pdf?id=XIaubzyOTN">Compositional Visual Causal Reasoning with Language Prompts</a></li>

</ul>
</details>

**Tags**: `#benchmark`, `#vision-language models`, `#causal reasoning`, `#evaluation`, `#machine learning`

---

<a id="item-10"></a>
## [AI Chip Counts Double Every 9 Months, Projected to Hit 200 Million by 2028](https://www.nytimes.com/interactive/2026/07/29/technology/ai-chips-data-center-boom.html) ⭐️ 7.0/10

Global AI chip numbers are doubling every nine months and are expected to reach roughly 200 million by the end of 2028, according to Epoch AI. This would represent a ten-fold increase from the current estimated 20 million chips. The projection reflects an unprecedented infrastructure buildout, with IDC forecasting AI infrastructure investment to surpass $1 trillion by 2029, up from $318 billion last year. However, it also raises concerns about rising electricity prices, environmental disputes, and whether spending is outpacing actual profitability. The U.S. controls about 80% of global AI computing power, and Google alone is believed to have four times as many AI chips as all Chinese companies combined. China is racing to catch up through self-developed semiconductors and AI infrastructure.

telegram · zaihuapd · Aug 2, 01:01

**Background**: The growth is driven by 'scaling laws,' an empirical finding that AI model performance improves predictably as compute, data, and parameters increase. Epoch AI is a research institute that studies AI trajectories and provided the chip-count estimate, while IDC is a market research firm behind the investment forecast. These projections highlight how the AI boom is now as much about physical infrastructure — chips, data centers, and power — as about algorithms.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Neural_scaling_law">Neural scaling law - Wikipedia</a></li>
<li><a href="https://www.linkedin.com/company/epochai">Epoch AI | LinkedIn</a></li>

</ul>
</details>

**Tags**: `#AI hardware`, `#data centers`, `#AI infrastructure`, `#industry trends`

---

<a id="item-11"></a>
## [Apple Caps Bug Reports, Adds 30-Day Cooldown to Thwart AI-Generated Spam](https://www.ft.com/content/4532122d-90f2-4433-9df6-ca99d8a141d2?syn-25a6b1a6=1) ⭐️ 7.0/10

Apple confirmed it began limiting the number of concurrent vulnerability report submissions in June, imposing a 30-day cooldown to cope with a flood of low-quality, AI-generated security reports. Italian startup Bynario says it used ChatGPT to find more than 50 vulnerabilities in the latest macOS in three weeks, including a privilege escalation chain enabling full control, but was blocked by the submission cap. The move highlights how AI-generated noise is straining vulnerability disclosure channels, forcing vendors to add guardrails that can also block legitimate researchers. It also shows Apple is simultaneously adopting AI for defense, with its latest update fixing roughly five times the usual number of vulnerabilities with help from Anthropic and OpenAI tools. The 30-day cooldown reportedly limits how many reports a researcher can submit at once, and Apple says it has contacted Bynario and reviewed its submissions. Apple credited Anthropic and OpenAI tools for helping identify the vulnerabilities fixed in its latest macOS security update, which contained about five times more fixes than typical releases.

telegram · zaihuapd · Aug 2, 05:50

**Background**: Bug bounty programs allow security researchers to report vulnerabilities in exchange for recognition or rewards, with major companies like Apple, Microsoft, and Google operating their own. In recent months, maintainers of open-source projects such as Log4j and curl have also reported being overwhelmed by low-quality, AI-generated vulnerability reports that look professional but lack real substance, prompting policies such as instant bans for AI-generated submissions.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bug_bounty_program">Bug bounty program</a></li>
<li><a href="https://aiproductivity.ai/news/log4j-ai-generated-security-report-spam/">Log4j Maintainers Drowning in AI - Generated Security Reports , 95...</a></li>
<li><a href="https://biggo.com/news/202506301402_AI_Security_Report_Spam_Hits_curl">AI - Generated Security Reports Flood curl Project... - BigGo News</a></li>

</ul>
</details>

**Tags**: `#security`, `#AI`, `#Apple`, `#vulnerability research`, `#bug bounty`

---

<a id="item-12"></a>
## [Chinese AI Framework Detects Bitcoin Money Laundering with ~90% Accuracy](https://www.scmp.com/news/china/science/article/3362493/chinese-police-ai-algorithm-tracks-bitcoin-money-laundering-90-accuracy) ⭐️ 7.0/10

Researchers at People's Public Security University of China developed an AI framework combining memory modules and large language models that identifies illegal cryptocurrency transactions with nearly 90% accuracy. The peer-reviewed findings were published in the May issue of the Journal of Intelligence. This marks a practical application of AI in financial crime detection, offering law enforcement an explainable and generalizable tool to combat crypto money laundering. As cryptocurrency crime grows, such AI-driven methods could become a key component of regulatory oversight. The framework reportedly achieves nearly 90% accuracy in detecting laundering behaviors hidden in anonymous, cross-border Bitcoin transactions. The research team says it offers an explainable path for regulators; China's Supreme People's Procuratorate data shows 3,259 suspects were prosecuted in 2025 for money laundering involving virtual currencies and underground banks.

telegram · zaihuapd · Aug 2, 08:22

**Background**: Bitcoin transactions are recorded on a public ledger, but users are pseudonymous, making it hard to trace the real identities behind cross-border transfers. AI models like recurrent neural networks and memory networks are increasingly used to analyze sequential transaction data, and large language models have recently been applied to anomaly detection in blockchain. Combining memory modules with LLMs can help capture long-term transaction patterns that simple heuristics miss.

<details><summary>References</summary>
<ul>
<li><a href="https://informationengineering.dinfo.unifi.it/phdinfo-seminar-francesco-marchetti-the-memory-in-deep-learning-from-recurrent-neural-network-to-memory-network/">PhDInfo Seminar: Francesco Marchetti, “The Memory in Deep learning...</a></li>
<li><a href="https://arxiv.org/html/2410.04039">BlockScan: Detecting Anomalies in Blockchain Transactions</a></li>
<li><a href="https://www.researchgate.net/publication/387104775_AD-LLM_Benchmarking_Large_Language_Models_for_Anomaly_Detection">AD-LLM: Benchmarking Large Language Models for Anomaly ...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#cryptocurrency`, `#money laundering`, `#LLM`, `#law enforcement`

---

<a id="item-13"></a>
## [Microplastics Found in 92% of Animals Near Deep-Sea Hydrothermal Vents](https://www.yahoo.com/news/science/articles/most-isolated-environments-microplastics-finding-020000452.html) ⭐️ 7.0/10

A study led by the Korea Research Institute of Bioscience and Biotechnology, published in Water Research, detected microplastics in 11 of 12 (92%) animals sampled near deep-sea hydrothermal vents about 2,000 meters deep in the Southwest Pacific and Indian Ocean. The animals, including snails and mussels, contained an average of 3.42 microplastic pieces per individual, primarily polystyrene. This finding reveals that plastic pollution has reached one of the most isolated and extreme deep-sea ecosystems on Earth, affecting creatures that were previously considered beyond the reach of surface-borne contaminants. It underscores the urgency of reducing plastic emissions at the source, as deep-sea cleanup efforts are practically impossible and the impact on these unique chemosynthetic communities could be long-lasting. The study sampled four species, with filter-feeding mussels showing evenly distributed microplastics, while herbivorous snails had microplastics concentrated in their digestive organs. Additionally, microplastic concentrations were higher in samples from the Indian Ocean than from the Pacific.

telegram · zaihuapd · Aug 2, 11:00

**Background**: Deep-sea hydrothermal vents are underwater geysers where seawater seeps into cracks in the seafloor, is heated by magma, and then erupts as mineral-rich fluids, sometimes forming towering chimneys and 'black smoker' plumes. These extreme ecosystems support life without sunlight through chemosynthesis, a process in which microbes convert chemicals into energy. Filter feeding is a feeding strategy where organisms, such as mussels, strain suspended particles like plankton from the water, inadvertently also ingesting microplastics. This study adds to growing evidence that microplastic pollution has penetrated virtually every marine environment, from surface waters to the deep seafloor.

<details><summary>References</summary>
<ul>
<li><a href="http://www.extremescience.com.s3-website-us-west-2.amazonaws.com/deep-sea-vents.htm">Deep Sea Hydrothermal vents</a></li>
<li><a href="https://www.linkedin.com/posts/woods-hole-oceanographic-institution_deepseadiscovery-extremelife-activity-7298748542427287552-4DDe">What are hydrothermal vents ? | Woods Hole... | LinkedIn</a></li>
<li><a href="https://fiveable.me/key-terms/marine-biology/filter-feeding">Filter Feeding - ( Marine Biology ) - Vocab, Definition... | Fiveable</a></li>

</ul>
</details>

**Tags**: `#microplastics`, `#deep-sea`, `#pollution`, `#marine biology`, `#environmental science`

---