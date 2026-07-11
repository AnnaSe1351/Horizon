---
layout: default
title: "Horizon Summary: 2026-07-11 (EN)"
date: 2026-07-11
lang: en
---

> From 18 items, 6 important content pieces were selected

---

1. [GPT-5.6 Sol Ultra Claims Proof of Cycle Double Cover Conjecture](#item-1) ⭐️ 9.0/10
2. [SGLang v0.5.15 Boosts LLM Serving with Spec V2 and NVFP4](#item-2) ⭐️ 8.0/10
3. [Relativity Governs Chemical Bonds in Heavy Elements](#item-3) ⭐️ 8.0/10
4. [QuadRF open-source RF visualizer detects drones and WiFi through walls](#item-4) ⭐️ 8.0/10
5. [Apple Sues OpenAI Over Trade Secret Theft via Ex-Employees](#item-5) ⭐️ 8.0/10
6. [Residential proxies and the scraper battle](#item-6) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [GPT-5.6 Sol Ultra Claims Proof of Cycle Double Cover Conjecture](https://cdn.openai.com/pdf/04d1d1e4-bc75-476a-97cf-49055cd98d31/cdc_proof.pdf) ⭐️ 9.0/10

On July 10, 2026, OpenAI released a preprint claiming that its GPT-5.6 Sol Ultra model produced a proof of the Cycle Double Cover Conjecture, a long-standing open problem in graph theory. If verified, this would be a landmark AI achievement, demonstrating that large language models can solve major open mathematical problems. It could fundamentally change how mathematical research is conducted and accelerate discovery. The proof is concise and may exploit a clever trick overlooked by human experts. However, the methodology is unclear: it is unknown how many open problems were attempted before this success, and the prompt required significant hand-holding to guide the model.

hackernews · scrlk · Jul 10, 18:29 · [Discussion](https://news.ycombinator.com/item?id=48863490)

**Background**: The Cycle Double Cover Conjecture, posed by Tutte, Itai and Rodeh, Szekeres, and Seymour, asserts that every bridgeless undirected graph has a collection of cycles covering each edge exactly twice. It has been open since the 1970s and is closely related to graph embeddings. The conjecture is a central problem in graph theory, and a proof would have significant implications.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Cycle_double_cover_conjecture">Cycle double cover conjecture</a></li>
<li><a href="https://cdn.openai.com/pdf/04d1d1e4-bc75-476a-97cf-49055cd98d31/cdc_proof.pdf">Introduction A PROOF OF THE CYCLE DOUBLE COV</a></li>

</ul>
</details>

**Discussion**: Commenters are impressed but cautious, emphasizing the need for verification. They question whether the result was a one-shot success or one of many attempts, and note that the extensive prompt engineering suggests the model did not act entirely autonomously.

**Tags**: `#AI`, `#mathematics`, `#proof`, `#GPT`, `#graph theory`

---

<a id="item-2"></a>
## [SGLang v0.5.15 Boosts LLM Serving with Spec V2 and NVFP4](https://github.com/sgl-project/sglang/releases/tag/v0.5.15) ⭐️ 8.0/10

SGLang v0.5.15 enables Speculative Decoding V2 by default, introduces IndexShare MTP for up to 1.9x lower draft-step cost, and tunes GLM-5.2 NVFP4 on Blackwell hardware to achieve 500+ tok/s/user on 8x B300. These optimizations significantly enhance LLM inference throughput and latency, especially for large models and long-context scenarios, and SGLang continues to push the frontier of open-source serving engines. Spec V2 eliminates D2H/H2D syncs and fuses metadata ops, achieving +11% end-to-end TPS, while IndexShare MTP reuses indexer top-k across draft steps to reduce compute.

github · Fridge003 · Jul 10, 22:58

**Background**: Speculative decoding accelerates LLM inference by using a smaller draft model to predict multiple tokens, which are then verified by the main model. Multi-Token Prediction (MTP) extends this by predicting several future tokens simultaneously. NVFP4 is a 4-bit floating-point format from NVIDIA for Blackwell architecture, designed for efficient low-precision inference with a two-level scaling strategy.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.sglang.io/docs/advanced_features/speculative_decoding">Speculative Decoding - SGLang Documentation</a></li>
<li><a href="https://www.lmsys.org/blog/2026-06-15-next-generation-speculative-decoding-dflash-v2/">The next generation of speculative decoding: DFlash and Spec V2</a></li>
<li><a href="https://developer.nvidia.com/blog/introducing-nvfp4-for-efficient-and-accurate-low-precision-inference/">Introducing NVFP4 for Efficient and Accurate Low-Precision Inference | NVIDIA Technical Blog</a></li>

</ul>
</details>

**Tags**: `#SGLang`, `#LLM serving`, `#performance optimization`, `#speculative decoding`, `#NVIDIA Blackwell`

---

<a id="item-3"></a>
## [Relativity Governs Chemical Bonds in Heavy Elements](https://www.brown.edu/news/2026-07-09/chemical-bonds-relativity) ⭐️ 8.0/10

New research published in Science demonstrates that Einstein's theory of relativity dictates the formation of chemical bonds in heavy elements like bismuth and gold. This finding deepens our understanding of heavy element chemistry, with potential applications in replacing toxic lead with bismuth in solar cells and other materials. For heavy elements, inner electrons move at a significant fraction of the speed of light, leading to spin-orbit coupling that affects bonding, as detailed in the study.

hackernews · hhs · Jul 10, 22:30 · [Discussion](https://news.ycombinator.com/item?id=48866134)

**Background**: Relativistic effects in chemistry are known to explain phenomena like the color of gold and mercury's liquid state at room temperature. This study extends the concept to chemical bonding, showing that relativity determines bond formation in heavy elements.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Relativistic_quantum_chemistry">Relativistic quantum chemistry - Wikipedia</a></li>
<li><a href="https://pubs.acs.org/doi/10.1021/acsomega.7b00802">Relativistic Effects in the Electronic Structure of Atoms | ACS Omega</a></li>
<li><a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/9783527667550.ch16">Relativistic Effects in Chemistry - Relativistic Quantum Chemistry - Wiley Online Library</a></li>

</ul>
</details>

**Discussion**: Comments noted that relativistic effects in heavy elements are already known (e.g., gold's color, mercury's liquidity), but praised the new focus on bonding. Some questioned the novelty, while others appreciated the extension to bismuth for solar cells.

**Tags**: `#physics`, `#chemistry`, `#relativity`, `#heavy elements`, `#chemical bonding`

---

<a id="item-4"></a>
## [QuadRF open-source RF visualizer detects drones and WiFi through walls](https://www.jeffgeerling.com/blog/2026/quadrf-can-spot-drones-and-see-wifi-through-my-wall/) ⭐️ 8.0/10

QuadRF, a 4x4 MIMO software-defined radio (SDR) phased-array development kit, has been demonstrated as an open-source RF visualizer capable of detecting drone signals and WiFi networks through walls, with a community post showing the device in action. This brings affordable phased-array RF sensing to hobbyists and researchers, enabling practical applications like drone detection, RF interference hunting, and security auditing without expensive equipment. QuadRF operates as a 4x4 MIMO SDR with phased-array capabilities, allowing beamforming and spatial awareness of RF signals; the creator noted that camera alignment and gain settings could be improved, and the project is fully open-source for customization.

hackernews · speckx · Jul 10, 15:59 · [Discussion](https://news.ycombinator.com/item?id=48861717)

**Background**: Software-defined radio (SDR) uses digital signal processing to replace traditional analog radio hardware, allowing flexible reconfiguration for different frequencies and protocols. Phased-array systems combine multiple antennas to steer beams electronically, enabling direction finding and spatial filtering. QuadRF brings these technologies together in an open-source kit.

<details><summary>References</summary>
<ul>
<li><a href="https://www.crowdsupply.com/scale-rf/quadrf">QuadRF | Crowd Supply</a></li>
<li><a href="https://moonrf.com/docs/">QuadRF Documentation</a></li>
<li><a href="https://en.wikipedia.org/wiki/Software-defined_radio">Software-defined radio</a></li>

</ul>
</details>

**Discussion**: The QuadRF creator engaged directly in the comments, answering questions and pointing to demo videos. Commenters discussed potential low-frequency (3-30 MHz) use for RFI hunting in amateur radio, and drew parallels to thermal cameras and sound localization applications.

**Tags**: `#RF`, `#open-source`, `#drone detection`, `#WiFi`, `#SDR`

---

<a id="item-5"></a>
## [Apple Sues OpenAI Over Trade Secret Theft via Ex-Employees](https://9to5mac.com/2026/07/10/apple-sues-openai-trade-secret-theft/) ⭐️ 8.0/10

Apple has filed a lawsuit against OpenAI, accusing the AI company of stealing trade secrets through former Apple employees who reportedly emailed confidential information and instructed others to conceal their positions when leaving Apple. This high-profile lawsuit between two tech giants could set a precedent for intellectual property protection in the AI industry, potentially impacting OpenAI's hardware partnerships and business practices. It also highlights ongoing tensions over data and IP theft in generative AI. Apple discovered a pattern where OpenAI recruits emailed themselves confidential information upon leaving Apple, including one Mr. Tan. OpenAI also allegedly used confidential Apple hardware information to approach Apple suppliers and instructed new hires on avoiding scrutiny.

hackernews · stock_toaster · Jul 10, 20:47 · [Discussion](https://news.ycombinator.com/item?id=48865019)

**Background**: Trade secret lawsuits involve the misappropriation of confidential business information that provides a competitive advantage. Apple has a history of aggressively protecting its intellectual property, and this suit echoes the Waymo vs. Uber case that led to Uber's self-driving project being shut down. The outcome could influence how AI companies recruit from competitors.

**Discussion**: Commenters are largely critical of OpenAI, calling it a company built on copyright violation and predicting severe consequences, including the potential end of OpenAI's hardware ambitions. Some warn businesses using OpenAI models to be cautious about data security. The sentiment is that this lawsuit appears 'open and shut' given Apple's resources.

**Tags**: `#AI`, `#Legal`, `#Trade Secrets`, `#OpenAI`, `#Apple`

---

<a id="item-6"></a>
## [Residential proxies and the scraper battle](https://lwn.net/SubscriberLink/1080822/990a8a5e2d379085/) ⭐️ 8.0/10

An LWN article examines the escalating cat-and-mouse game between websites and scrapers using residential proxies, highlighting the challenges of distinguishing bots from humans and community-proposed countermeasures. This issue affects the openness of the web, AI data acquisition, and the balance between protecting websites and preserving access for legitimate users and researchers. Residential proxies route traffic through real ISP-assigned IPs, making them hard to block. Proposed solutions like proof-of-work (e.g., Anubis) may be bypassed by using vast botnets of residential devices.

hackernews · chmaynard · Jul 10, 19:38 · [Discussion](https://news.ycombinator.com/item?id=48864252)

**Background**: A residential proxy is a proxy server that uses IP addresses assigned to real residential devices, often from hacked or user-installed apps. This allows scrapers to appear as regular users, complicating anti-bot measures. The web scraping ecosystem involves a constant arms race between data collectors and site owners.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/Residential_proxy">Residential proxy</a></li>
<li><a href="https://trustytech.io/residential-proxy/">Residential Proxy Service Ratings | TrustyTech</a></li>
<li><a href="https://decodo.com/proxies/residential-proxies">Residential Proxies From $2/GB – 115M+ IPs</a></li>

</ul>
</details>

**Discussion**: Commenters note that mobile app stores make it trivial for apps to install residential proxies without user awareness, fueling the problem. Some argue that aggressive anti-scraping rhetoric may harm the open web and empower centralized gatekeepers like Cloudflare.

**Tags**: `#web scraping`, `#residential proxies`, `#anti-bot`, `#AI data`, `#open web`

---