---
layout: default
title: "Horizon Summary: 2026-07-11 (EN)"
date: 2026-07-11
lang: en
---

> From 18 items, 7 important content pieces were selected

---

1. [Relativity rules chemical bonds in heavy elements](#item-1) ⭐️ 9.0/10
2. [Apple sues OpenAI over trade secret theft](#item-2) ⭐️ 9.0/10
3. [GPT-5.6 Sol Ultra Proves Cycle Double Cover Conjecture](#item-3) ⭐️ 9.0/10
4. [SGLang v0.5.15 boosts LLM serving with NVFP4 and Spec V2](#item-4) ⭐️ 8.0/10
5. [QuadRF Augmented Reality Tool Visualizes WiFi and Drones](#item-5) ⭐️ 8.0/10
6. [LWN examines the ongoing residential proxy and scraper battle](#item-6) ⭐️ 8.0/10
7. [T2 VFX oral history: groundbreaking tech and techniques](#item-7) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Relativity rules chemical bonds in heavy elements](https://www.brown.edu/news/2026-07-09/chemical-bonds-relativity) ⭐️ 9.0/10

A new study provides the first direct experimental evidence that Einstein's theory of relativity governs chemical bonding in heavy elements, breaking the textbook model of triple bonds. This challenges fundamental chemical theory and has implications for designing new materials and understanding heavy-element chemistry, such as the liquid state of mercury and the color of gold. The research shows that for heavy elements, relativistic effects cause strong spin-orbit coupling, which distorts the classical sigma-pi bond picture and creates entirely new bonding patterns.

hackernews · hhs · Jul 10, 22:30 · [Discussion](https://news.ycombinator.com/item?id=48866134)

**Background**: In non-relativistic quantum chemistry, chemical bonds are described by the Schrödinger equation, which works well for light elements. However, for heavy elements like gold or mercury, electrons travel at a significant fraction of the speed of light, and relativistic effects (described by the Dirac equation) become important. These effects alter electron orbitals and spin-orbit coupling, leading to properties like gold's yellow color and mercury's liquid state at room temperature.

<details><summary>References</summary>
<ul>
<li><a href="https://www.brown.edu/news/2026-07-09/chemical-bonds-relativity">Einstein's relativity rules chemical bonds in heavy elements, new ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Relativistic_quantum_chemistry">Relativistic quantum chemistry</a></li>

</ul>
</details>

**Discussion**: Commenters noted that relativistic effects on heavy elements were already known (e.g., gold's color), but the new study provides direct experimental evidence for bonds breaking down. Some questioned whether lead is still used in solar cells, sparking discussion about bismuth as an alternative.

**Tags**: `#Physics`, `#Chemistry`, `#Relativity`, `#Research`, `#Science`

---

<a id="item-2"></a>
## [Apple sues OpenAI over trade secret theft](https://9to5mac.com/2026/07/10/apple-sues-openai-trade-secret-theft/) ⭐️ 9.0/10

Apple has filed a lawsuit against OpenAI, alleging that former employees, including a senior engineer named Mr. Tan, stole trade secrets related to hardware and supplier information for competitive advantage. This high-profile legal battle between two tech giants could set a precedent for intellectual property protection in the AI industry, especially as companies race to develop advanced hardware and models. Apple claims OpenAI instructed new hires to avoid scrutiny when leaving Apple, and that ex-employees emailed themselves confidential information, including hardware specifications used to approach Apple's suppliers.

hackernews · stock_toaster · Jul 10, 20:47 · [Discussion](https://news.ycombinator.com/item?id=48865019)

**Background**: Trade secrets are confidential business information that provides a competitive edge. Apple and OpenAI are major players in AI and hardware; Apple develops its own chips and AI systems, while OpenAI focuses on large language models like GPT-4. The lawsuit highlights tensions over talent poaching and intellectual property in the tech industry.

**Discussion**: Commenters largely side with Apple, describing the allegations as 'damning' and noting that OpenAI's business model relies on copyright violations. Some predict this could be worse for OpenAI than the Waymo vs. Uber lawsuit, potentially ending its hardware efforts. Others warn that OpenAI may misuse user data sent to its models.

**Tags**: `#Apple`, `#OpenAI`, `#trade secrets`, `#AI ethics`, `#legal`

---

<a id="item-3"></a>
## [GPT-5.6 Sol Ultra Proves Cycle Double Cover Conjecture](https://cdn.openai.com/pdf/04d1d1e4-bc75-476a-97cf-49055cd98d31/cdc_proof.pdf) ⭐️ 9.0/10

OpenAI claims that its GPT-5.6 Sol Ultra model has generated a proof of the Cycle Double Cover Conjecture, a long-standing open problem in graph theory. The proof was released as a preprint on July 10, 2026. If verified, this would mark a major milestone where an AI system autonomously solves a significant mathematical problem, potentially revolutionizing how research is conducted in mathematics and theoretical computer science. It also fuels debates about AI's capabilities and the future of human expertise. The proof is notable for its conciseness, suggesting a clever trick that experts had missed. However, the methodology is unclear: it is unknown how many open problems were attempted before this success, and whether the model can consistently generate correct proofs.

hackernews · scrlk · Jul 10, 18:29 · [Discussion](https://news.ycombinator.com/item?id=48863490)

**Background**: The Cycle Double Cover Conjecture, posed by Tutte, Szekeres, Seymour, and others, states that every bridgeless graph has a collection of cycles that together contain each edge exactly twice. It is equivalent to the circular embedding conjecture and has remained open for decades. The conjecture is a central problem in graph theory with connections to graph embeddings and surface topology.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Cycle_double_cover_conjecture">Cycle double cover conjecture</a></li>

</ul>
</details>

**Discussion**: Commenters expressed both awe and caution, noting that the proof's brevity suggests a non-obvious insight, but questioning the methodology: how many failures preceded this success? Some observed that the prompt heavily instructs the model on strategies, indicating that the model is not yet autonomous. Others debated the implications for AI-assisted mathematics and the extent to which AI can replace human mathematicians.

**Tags**: `#AI`, `#mathematics`, `#graph theory`, `#breakthrough`, `#LLM`

---

<a id="item-4"></a>
## [SGLang v0.5.15 boosts LLM serving with NVFP4 and Spec V2](https://github.com/sgl-project/sglang/releases/tag/v0.5.15) ⭐️ 8.0/10

SGLang v0.5.15 introduces optimized GLM-5.2 NVFP4 on Blackwell GPUs, achieving over 500 tok/s/user on 8x B300 and 450 tok/s/user on 4x GB300. It also makes Spec V2 the default speculative decoding engine with an 11% end-to-end TPS increase, and adds IndexShare MTP to reduce draft-step cost by up to 1.9x at long context. This release represents a significant advancement in LLM serving efficiency, particularly for NVIDIA Blackwell hardware, enabling cost-effective high-throughput inference. The performance gains, such as the 500+ tok/s/user on GLM-5.2, make it easier for organizations to deploy large language models at scale with lower latency and cost. Spec V2 achieves zero-overhead scheduling through CUDA-graphable DSA draft-extend and fused metadata operations, while IndexShare MTP reuses the indexer top-k across draft steps. Additional optimizations include linear-attention kernels (KDA/GDN), TopK V2, FlashInfer autotune for draft models, and enhanced DeepSeek-V4 support with FlashMLA sparse prefill enabled by default.

github · Fridge003 · Jul 10, 22:58

**Background**: SGLang is an open-source framework for efficient LLM serving, focusing on high throughput and low latency. It supports various speculative decoding methods like EAGLE and MTP. NVFP4 is a 4-bit floating point format introduced by NVIDIA for Blackwell GPUs, enabling efficient low-precision inference with a two-level scaling strategy.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.nvidia.com/blog/introducing-nvfp4-for-efficient-and-accurate-low-precision-inference/">Introducing NVFP4 for Efficient and Accurate Low-Precision Inference | NVIDIA Technical Blog</a></li>
<li><a href="https://www.lmsys.org/blog/2026-06-15-next-generation-speculative-decoding-dflash-v2/">The next generation of speculative decoding: DFlash and Spec V2</a></li>
<li><a href="https://github.com/sgl-project/sglang/releases">Releases · sgl-project/sglang - GitHub</a></li>

</ul>
</details>

**Tags**: `#inference`, `#GPU`, `#performance`, `#LLM serving`, `#SGLang`

---

<a id="item-5"></a>
## [QuadRF Augmented Reality Tool Visualizes WiFi and Drones](https://www.jeffgeerling.com/blog/2026/quadrf-can-spot-drones-and-see-wifi-through-my-wall/) ⭐️ 8.0/10

QuadRF, an open-source RF imaging platform, converts a Raspberry Pi 5 into a real-time RF camera that visualizes wireless signals like WiFi and drone communications through augmented reality overlays on a live video feed. This democratizes RF visualization, making it accessible to hobbyists and professionals for security audits, drone detection, and RF interference hunting, while demonstrating practical consumer-grade AR applications beyond gaming. QuadRF uses a hybrid open model: the RF core firmware is proprietary, but schematics and software are open-source, allowing customization. It requires a Raspberry Pi 5 and supports a 4x4 MIMO SDR for multi-band operation.

hackernews · speckx · Jul 10, 15:59 · [Discussion](https://news.ycombinator.com/item?id=48861717)

**Background**: Software-defined radio (SDR) allows flexible processing of radio signals in software. Augmented reality (AR) overlays digital information onto the real world. QuadRF combines SDR and AR to let users see RF signals as colored overlays, similar to a thermal camera for radio waves.

<details><summary>References</summary>
<ul>
<li><a href="https://www.crowdsupply.com/scale-rf/quadrf">QuadRF | Crowd Supply</a></li>
<li><a href="https://github.com/ngoldbla/quadrf">GitHub - ngoldbla/ quadrf · GitHub</a></li>
<li><a href="https://www.opensourceforu.com/2026/07/rf-imaging-platform-visualises-wi-fi-signals/">RF Imaging Platform Visualises Wi-Fi Signals - Open Source For You</a></li>

</ul>
</details>

**Discussion**: The creator actively answered questions, and users expressed interest in lower-frequency support for amateur radio and sound visualization. Some compared it to thermal cameras and noted potential for detecting hidden transmitters.

**Tags**: `#RF`, `#open-source`, `#drones`, `#WiFi`, `#augmented-reality`

---

<a id="item-6"></a>
## [LWN examines the ongoing residential proxy and scraper battle](https://lwn.net/SubscriberLink/1080822/990a8a5e2d379085/) ⭐️ 8.0/10

LWN published an in-depth analysis of the escalating cat-and-mouse game between website operators using anti-scraping measures and scrapers leveraging residential proxy networks to avoid detection. This issue affects the openness of the web, AI training data access, and the fairness of anti-bot solutions, as residential proxies enable large-scale scraping while making it hard to distinguish bots from legitimate users. Residential proxies route traffic through real home IP addresses, making scrapers appear as ordinary users, which complicates blocking efforts and raises concerns about privacy and resource abuse.

hackernews · chmaynard · Jul 10, 19:38 · [Discussion](https://news.ycombinator.com/item?id=48864252)

**Background**: Residential proxies are IP addresses assigned by ISPs to real devices like home computers and phones, as opposed to data center proxies which come from cloud servers. Web scrapers use these proxies to hide their true identity and avoid IP-based blocking, while website operators deploy various techniques like CAPTCHAs or proof-of-work to stop them. This cat-and-mouse game has persisted for over a decade, with neither side holding a clear moral high ground.

<details><summary>References</summary>
<ul>
<li><a href="https://www.webshare.io/blog/what-are-residential-proxies">What are Residential Proxies? Explained</a></li>
<li><a href="https://iproyal.com/blog/what-is-residential-proxy/">What Is a Residential Proxy and How Does It Work?</a></li>

</ul>
</details>

**Discussion**: Commenters expressed frustration with the arms race, with some suggesting that a better common crawl could reduce the incentive for aggressive scraping. Others noted that the battle has been ongoing for over a decade without resolution, and questioned the moral legitimacy of both sides.

**Tags**: `#web scraping`, `#residential proxies`, `#anti-bot measures`, `#open web`, `#AI training`

---

<a id="item-7"></a>
## [T2 VFX oral history: groundbreaking tech and techniques](https://vfxblog.com/2017/08/23/the-tech-of-terminator-2-an-oral-history/) ⭐️ 8.0/10

An oral history article published in 2017 details the innovative technology and techniques behind the visual effects in 'Terminator 2: Judgment Day', including the first use of CGI for a main character and custom practical effects. This article is significant because it documents the pioneering work that shaped modern VFX, influencing how filmmakers approach digital and practical effects. It also highlights the collaborative problem-solving at ILM and other studios. The article features interviews with key figures such as visual effects supervisor Dennis Muren and animator Steve 'Spaz' Williams. It covers both the computer-generated T-1000 liquid metal effect and the custom squibs used for bullet impacts, noting that Softimage 3D software was utilized.

hackernews · markus_zhang · Jul 10, 16:48 · [Discussion](https://news.ycombinator.com/item?id=48862365)

**Background**: Released in 1991, 'Terminator 2: Judgment Day' was a milestone in visual effects, combining CGI with practical effects by Stan Winston. The T-1000, a liquid metal shapeshifter, was one of the first fully CG characters in a major film. Industrial Light & Magic (ILM) and other companies developed new techniques to achieve the character's morphing and metallic appearance, many of which became industry standards.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Special_effects_of_Terminator_2:_Judgment_Day">Special effects of Terminator 2: Judgment Day - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/T-1000">T-1000 - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters praised the article's depth and the ingenuity of the practical effects, particularly the custom squibs for bullet impacts. One user noted the use of Softimage and that a 4K remaster was returning to theaters. Another recommended the documentary 'Jurassic Punk' about Steve Williams, who is featured in the oral history.

**Tags**: `#VFX`, `#Computer Graphics`, `#Terminator 2`, `#Film Technology`, `#Softimage`

---