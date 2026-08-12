---
layout: default
title: "Horizon Summary: 2026-08-12 (EN)"
date: 2026-08-12
lang: en
---

> From 52 items, 22 important content pieces were selected

---

1. [DeepSeek V4 Pro 0813 Releases on OpenRouter, Undercuts Rivals on Price](#item-1) ⭐️ 9.0/10
2. [Qwen Releases Qwen3.8-2.4T-A95B MoE Model](#item-2) ⭐️ 9.0/10
3. [Tailscale Traces Database Corruption to 16-Year-Old SQLite WAL Reset Bug](#item-3) ⭐️ 8.0/10
4. [xAI Releases Grok 4.6, Fueling Frontier Model Competition](#item-4) ⭐️ 8.0/10
5. [AI Could Eliminate Mid-Level Software Engineering Jobs?](#item-5) ⭐️ 8.0/10
6. [License Plate Reader Searches Should Require a Warrant](#item-6) ⭐️ 8.0/10
7. [Gowers Examines Which Math LLMs Excel At](#item-7) ⭐️ 8.0/10
8. [Woxi: Open-Source Rust Reimplementation of Wolfram Language](#item-8) ⭐️ 8.0/10
9. [Developer warns AI-generated code creates systems no one understands](#item-9) ⭐️ 8.0/10
10. [Researchers Steal Hidden Reasoning Traces from Major LLM APIs](#item-10) ⭐️ 8.0/10
11. [Adam's Per-Coordinate Scaling Breaks Rotation Invariance and Low-Rank Bias](#item-11) ⭐️ 8.0/10
12. [LTX Releases Open-Source Video Model LTX-2.5, Runs Locally on a Single RTX 5090](#item-12) ⭐️ 8.0/10
13. [WeChat Releases WeLM, Resource-Efficient LLM Family](#item-13) ⭐️ 8.0/10
14. [Zed launches Delta for realtime collaborative AI conversations](#item-14) ⭐️ 7.0/10
15. [Tim King, Key AmigaDOS Developer, Passes Away](#item-15) ⭐️ 7.0/10
16. [Mass Scans Spoof AI Bot User Agents Like ClaudeBot](#item-16) ⭐️ 7.0/10
17. [Why Tiny JPEGs Look Different in Chrome: A Technical Walkthrough](#item-17) ⭐️ 7.0/10
18. [uBlock Origin Stops Fighting Facebook Ads, Cites Unsustainable Effort](#item-18) ⭐️ 7.0/10
19. [LLMs Can't Losslessly Transform Text: Authors Must Own Every Sentence](#item-19) ⭐️ 7.0/10
20. [Musk says all future Teslas will get Starlink, starting with Cybercab](#item-20) ⭐️ 7.0/10
21. [Tencent Q2 Revenue Beats, AI Capex Surge Turns Free Cash Flow Negative](#item-21) ⭐️ 7.0/10
22. [Enterprise SSDs Reach 48% of NAND Shipments; YMTC Enters Top Three](#item-22) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [DeepSeek V4 Pro 0813 Releases on OpenRouter, Undercuts Rivals on Price](https://openrouter.ai/deepseek/deepseek-v4-pro-0813) ⭐️ 9.0/10

DeepSeek V4 Pro 0813 has been released on the OpenRouter platform, and community benchmarks and hands-on tests show it is competitive with top-tier models while carrying a much lower price. One pricing comparison put it at roughly 20 times cheaper than Opus 4.8. This release intensifies price competition in the LLM API market and gives developers a low-cost alternative for demanding tasks. As a Chinese open-weight model maker, DeepSeek continues to challenge Western providers on both capability and cost. Community-provided benchmarks on OpenRouter list HLE scores for DeepSeek V4 Pro 0813 and several rivals, and one test on the Codex CLI showed the model completed a feature for $0.12 but introduced a bug, while Grok 4.6 finished cleanly for $1.41. The model is described as competitive with Opus 4.8 but weaker than Sol or Fable.

hackernews · explosion-s · Aug 12, 16:04 · [Discussion](https://news.ycombinator.com/item?id=49274600)

**Background**: DeepSeek is a Chinese AI company known for open-weight large language models trained at unusually low cost; its 2025 R1 release was widely seen as a challenge to US AI dominance. OpenRouter is a platform that provides a unified API for routing requests to hundreds of models from different providers, making it a natural place for new and low-cost models to reach developers quickly.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/OpenRouter">OpenRouter</a></li>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek</a></li>
<li><a href="https://openrouter.ai/">OpenRouter</a></li>

</ul>
</details>

**Discussion**: Discussion was extensive and mixed: some users shared detailed benchmark tables and price comparisons, while others ran hands-on coding tests and reported bugs or weaker-than-expected results. One off-topic comment about a bicycle chain also appeared, and overall sentiment balanced enthusiasm for the low cost against concerns about real-world reliability.

**Tags**: `#DeepSeek`, `#LLM`, `#AI`, `#model-release`, `#benchmarks`

---

<a id="item-2"></a>
## [Qwen Releases Qwen3.8-2.4T-A95B MoE Model](https://huggingface.co/Qwen/Qwen3.8-2.4T-A95B) ⭐️ 9.0/10

Alibaba's Qwen team released Qwen3.8-2.4T-A95B, a Mixture-of-Experts LLM with 2.4T total parameters and 95B active parameters, on Hugging Face in BF16 and FP8 formats. The model supports a native 262,144-token context, extendable to 1,010,000 tokens, and benchmarks reportedly place it between Opus 4.8 and Fable 5. This release pushes open-weight MoE models to a new scale while keeping inference costs low thanks to only 95B active parameters. The availability of FP8 and community 1-bit quantized versions (down to ~397GB) could bring near-frontier performance to high-end desktops, making it accessible to individuals and small teams. The full BF16 checkpoint is about 4.9TB, while the official FP8 version reduces this to roughly 2.4TB; community quantizations target ~1.3TB at Q4 and ~397GB at 1-bit. Notably, the open-weight release lacks vision input, non-thinking mode, and the default 1M-token context length found in the commercial Qwen3.8-Max, and its license restricts serving revenue beyond $50M/year.

hackernews · Philpax · Aug 12, 15:01 · [Discussion](https://news.ycombinator.com/item?id=49273478)

**Background**: Mixture of Experts (MoE) is an LLM architecture that uses many specialized sub-networks (experts) with a router that activates only a subset per token, cutting inference compute while keeping the model's full knowledge capacity. FP8 quantization compresses weights to 8-bit floating point, reducing memory and serving cost with less accuracy loss than integer formats. These techniques are why a 2.4T-parameter model can have only 95B active parameters and be served at practical speeds.

<details><summary>References</summary>
<ul>
<li><a href="https://www.ibm.com/think/topics/mixture-of-experts">What is mixture of experts? | IBM</a></li>
<li><a href="https://arxiv.org/abs/2507.11181">[2507.11181] Mixture of Experts in Large Language Models</a></li>
<li><a href="https://arxiv.org/abs/2208.09225">[2208.09225] FP8 Quantization: The Power of the Exponent</a></li>

</ul>
</details>

**Discussion**: Commenters are impressed by the 1-bit Unsloth quant (397GB) that puts Opus 4.5-level performance on consumer hardware, but note the large serving footprint at launch since only BF16/FP8 are official, lacking QAT for Q4. Others point out the license restrictions and that the open-weight model drops vision and extended context compared to Qwen3.8-Max, while DeepSeek V4 Pro's benchmarks add competitive context.

**Tags**: `#LLM`, `#Qwen`, `#HuggingFace`, `#MoE`, `#AI`

---

<a id="item-3"></a>
## [Tailscale Traces Database Corruption to 16-Year-Old SQLite WAL Reset Bug](https://tailscale.com/blog/sqlite-wal-reset-bug) ⭐️ 8.0/10

Tailscale has identified a 16-year-old race condition in SQLite's write-ahead logging (WAL) mode that caused intermittent database corruption, and funded an open-source VFS shim that helped isolate and fix the bug. This bug demonstrates that even the most widely used and thoroughly tested software can contain subtle concurrency flaws. The case highlights the value of funded open-source debugging tools, as well as the importance of proper SQLite usage patterns. The WAL reset bug occurs only when there are multiple concurrent connections to a WAL-mode database, and the writer/checkpoint logic spans more than one connection. Tailscale also uncovered a second, unrelated stale expression index bug while investigating.

hackernews · ropbear · Aug 12, 14:22 · [Discussion](https://news.ycombinator.com/item?id=49272832)

**Background**: SQLite is an embedded SQL database engine that is widely used across applications. WAL (Write-Ahead Logging) mode improves concurrency by allowing readers to continue reading while writes are appended to a separate log file, but it introduces specific synchronization requirements. A VFS shim is a wrapper around SQLite's OS interface that can intercept and instrument file operations, making it useful for debugging low-level issues like this race condition.

<details><summary>References</summary>
<ul>
<li><a href="https://sqlite.org/vfs.html">The SQLite OS Interface or "VFS"</a></li>
<li><a href="https://www.youngju.dev/blog/2026-07-16-sqlite-wal-reset-bug.en">The SQLite WAL - Reset Bug: A Data Corruption Race That Hid for 15...</a></li>
<li><a href="https://blog.pecar.me/sqlite-wal/">SQLite Write-Ahead Logging | Anže's Blog</a></li>

</ul>
</details>

**Discussion**: Commenters appreciated the well-written post and the example of a company funding open-source development. Some noted the subtlety of the bug, pointing out that standard SQLite usage (single writer with one connection) would avoid it. Others referenced SQLite's massive test suite and the inherent limitation that tests cannot prove the absence of bugs.

**Tags**: `#SQLite`, `#database`, `#debugging`, `#open-source`, `#Tailscale`

---

<a id="item-4"></a>
## [xAI Releases Grok 4.6, Fueling Frontier Model Competition](https://x.ai/news/grok-4-6) ⭐️ 8.0/10

xAI has released Grok 4.6, a new frontier large language model announced on its official news page. The release immediately sparked community debate over API default system prompts and the model's competitive positioning against other leading AI labs. As a major release from a well-funded lab, Grok 4.6 intensifies competition in the frontier AI arena and gives developers another high-performance option. Community reactions show the model is already being benchmarked against other leading labs' offerings, which could shift industry expectations for API pricing and capability. Developer reports on the xAI API suggest Grok 4.6 ships with a forced default system prompt whose non-disclosure clause can override user-supplied instructions, causing the model to refuse discussion about its own prompts. Community members also highlight xAI's heavy investment in its own inference infrastructure, which they say makes high-effort frontier-model usage unusually affordable.

hackernews · iLuddite · Aug 12, 15:32 · [Discussion](https://news.ycombinator.com/item?id=49274027)

**Background**: A frontier model represents the current state of the art in general AI capability at a given moment, a designation that shifts as the field advances. System prompts are predefined directives that take precedence over user inputs and guide how an LLM behaves, which is why the xAI API's injected default system prompt has drawn scrutiny. Grok is xAI's large language model family, built to compete directly with frontier models from OpenAI, Google, and Anthropic.

<details><summary>References</summary>
<ul>
<li><a href="https://tenbrief.com/en/2026/08/04/what-is-frontier-model/">What ' frontier model ' means — how to read AI news</a></li>
<li><a href="https://promptengineering.org/system-prompts-in-large-language-models/">System Prompts in Large Language Models</a></li>
<li><a href="https://arxiv.org/abs/2505.21091">[2505.21091] Position is Power: System Prompts as a Mechanism of Bias in Large Language Models (LLMs)</a></li>

</ul>
</details>

**Discussion**: Community sentiment is mixed but engaged: some developers are annoyed that the API's injected default system prompt overrides user instructions, while others argue Grok's pricing and inference investment make it a legitimate frontier competitor. One user questioned whether several labs suddenly reaching similar capability levels within two months suggests benchmark hacking rather than genuine progress, while another praised Grok's strong security-review performance and its polished Build TUI.

**Tags**: `#AI`, `#Grok`, `#xAI`, `#LLM`, `#API`

---

<a id="item-5"></a>
## [AI Could Eliminate Mid-Level Software Engineering Jobs?](https://blog.florianherrengt.com/ai-removing-middle-class-software-engineering.html) ⭐️ 8.0/10

A blog post argues that AI will eliminate mid-level software engineering work by automating routine coding tasks, widening the gap between senior and junior engineers. It also warns that AI can amplify the impact of low-quality work across an organization. This debate is significant for the software industry and its workforce as AI coding tools become widespread. Engineers, employers, and educators need to understand which roles are most vulnerable and how to adapt. The post highlights that 'bad' engineers can now amplify their poor output tenfold across the organization, and that the traditional handoff of carefully specified tickets from senior to junior engineers is becoming obsolete. It draws attention to the danger of combining long tenure with lost interest in the craft, which can lead to shipping mediocre work at scale.

hackernews · florianherrengt · Aug 12, 13:20 · [Discussion](https://news.ycombinator.com/item?id=49271994)

**Background**: Large language models (LLMs) are increasingly applied to software engineering tasks, from code generation to refactoring and review. Recent studies show AI can dramatically boost developer productivity—one report found that the top users shipped 61% more code—but also raise concerns about code quality and the changing nature of engineering roles. Tools like OpenAI's Codex and Cursor are now widely used for coding assistance, fueling debates about how AI will reshape the profession.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2308.10620">[2308.10620] Large Language Models for Software Engineering: A Systematic Literature Review</a></li>
<li><a href="https://arxiv.org/html/2509.19708v1">Intuition to Evidence: Measuring AI’s True Impact on Developer Productivity</a></li>
<li><a href="https://openai.com/codex/">Codex in ChatGPT | AI Coding Agents for Software... | OpenAI</a></li>

</ul>
</details>

**Discussion**: Commenters largely agreed that AI will reshape mid-level roles, but disagreed on whether this is a net negative. Some worried that 'bad' engineers can now amplify low-quality code tenfold, while others drew parallels to machinists transitioning to CNC machines, arguing the role changes rather than disappears. A recurring theme was the importance of never outsourcing critical thinking to an LLM and continuing to learn deeply.

**Tags**: `#AI`, `#software-engineering`, `#LLM`, `#future-of-work`, `#productivity`

---

<a id="item-6"></a>
## [License Plate Reader Searches Should Require a Warrant](https://andrewpwheeler.com/2026/08/12/license-plate-reader-searches-should-require-a-warrant/) ⭐️ 8.0/10

The blog post argues that law enforcement should be required to obtain a warrant before searching automatic license plate reader (ALPR) databases, citing privacy risks and the dangers of mass surveillance. The post challenges current practices where police can access this data without judicial oversight. This matters because ALPR networks are expanding rapidly and can track millions of innocent people, raising constitutional questions under the Fourth Amendment. The debate affects civil liberties, police accountability, and how courts apply surveillance law to new digital technologies. ALPRs are AI-powered cameras that capture and analyze images of all passing vehicles, storing location, date, and time even for people not linked to any crime. The article likely discusses the third-party doctrine and the Supreme Court's Carpenter decision, which required warrants for some cell-site data but left ALPRs in a legal gray area.

hackernews · apwheele · Aug 12, 14:43 · [Discussion](https://news.ycombinator.com/item?id=49273165)

**Background**: Automatic license plate readers (ALPRs) consist of networked cameras that use optical character recognition to read license plates and log the time and location of every vehicle that passes. Unlike manual checks against hot lists, many systems store all data indefinitely, creating a searchable history of people's movements. Privacy advocates argue this constitutes mass surveillance, and courts are still deciding whether existing warrant requirements apply when police search these databases. The article is part of a broader policy debate about regulating police use of connected camera networks such as Flock Safety.

<details><summary>References</summary>
<ul>
<li><a href="https://sls.eff.org/technologies/automated-license-plate-readers-alprs">Automated License Plate Readers</a></li>
<li><a href="https://deflock.org/">DeFlock is an open-source project that maps license plate readers ...</a></li>
<li><a href="https://www.flocksafety.com/blog/how-an-automatic-license-plate-recognition-system-works">How an Automatic License Plate Recognition System Works</a></li>

</ul>
</details>

**Discussion**: Commenters expressed deep skepticism of mass data collection, arguing that warrants do not legitimize bulk surveillance, which should not exist by default. Some noted that ALPR cameras are general-purpose internet-connected devices that could be repurposed, while others suggested open access or database-poisoning tactics as countermeasures. A recurring theme was that police have misused stored data for stalking, so better court oversight is necessary.

**Tags**: `#privacy`, `#surveillance`, `#law-and-policy`, `#civil-liberties`, `#technology-ethics`

---

<a id="item-7"></a>
## [Gowers Examines Which Math LLMs Excel At](https://gowers.wordpress.com/2026/08/12/what-sort-of-maths-are-llms-good-at/) ⭐️ 8.0/10

In a new blog post, mathematician Timothy Gowers analyzes what kinds of mathematics large language models are currently good at, and proposes what would count as convincing evidence of human-level theorem proving. He argues that surprising, beautiful, and natural proof methods that are hard to stumble upon by accident would be a strong signal. This analysis comes from a Fields Medalist and prominent mathematician, so it shapes how the research community thinks about AI's mathematical abilities and where to set benchmarks. It also connects to broader discussions of test-time scaling and whether scaling inference compute is the path to human-level reasoning. Gowers never uses the term 'test-time scaling,' but commenters note the post is essentially about it. He suggests that current LLM successes largely come from sampling many candidate answers, as exemplified by AlphaCode generating millions of programs and filtering them in 2022, rather than from genuinely novel mathematical insight.

hackernews · ColinWright · Aug 12, 10:04 · [Discussion](https://news.ycombinator.com/item?id=49270022)

**Background**: Test-time scaling (TTS) refers to techniques that allocate more computation during inference to improve reasoning, such as letting a model generate multiple samples or extended chains of thought. In mathematics, LLMs have shown progress on competition-style problems but struggle with formal theorem proving in systems like Lean 4; recent benchmarks like MA-ProofBench and TheoremBench aim to evaluate longer, more dependency-rich proofs. Gowers' post fits into a broader debate about whether these advances indicate genuine mathematical understanding or only pattern matching.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2503.24235">[2503.24235] A Survey on Test-Time Scaling in Large Language Models: What, How, Where, and How Well?</a></li>
<li><a href="https://arxiv.org/html/2606.13782v1">MA-ProofBench: A Two-Tiered Evaluation of LLMs for Theorem Proving in Mathematical Analysis</a></li>
<li><a href="https://arxiv.org/html/2606.09450v1">TheoremBench: Evaluating LLMs on Theorem Proving in Formal Mathematics</a></li>

</ul>
</details>

**Discussion**: Commenters generally engage with Gowers' argument. One highlights that the post is essentially about test-time scaling, noting AlphaCode's early success with massive sampling. Another agrees with Gowers' criterion for human-level proofs, while a third points to lists of AI math accomplishments and wonders if the field is too focused on prominent, pre-stated problems. A fourth speculates about testing LLMs on temporal logic, given coding agents' known difficulties with concurrent code.

**Tags**: `#LLMs`, `#mathematics`, `#AI research`, `#theorem proving`, `#test-time scaling`

---

<a id="item-8"></a>
## [Woxi: Open-Source Rust Reimplementation of Wolfram Language](https://woxi.ad-si.com/) ⭐️ 8.0/10

Woxi is a new open-source interpreter for the Wolfram Language written in Rust, released with a desktop GUI (Woxi Studio) plus CLI, Jupyter, Python, npm, and WASM interfaces. It aims to be a free alternative to Mathematica with dramatically faster startup times. Mathematica is a powerful but expensive proprietary tool, so a fast, embeddable open-source reimplementation could broaden access to the Wolfram Language for students, researchers, and developers. It may also offer a more integrated alternative to existing open-source systems like Sage, which glue together many disjoint libraries. The project is validated by about 26,000 unit tests and roughly 900 .wls snapshot tests. Current development priorities are fixing edge cases, improving performance, and growing the community; the author requests feedback on compatibility and missing functionality.

hackernews · adius · Aug 12, 10:06 · [Discussion](https://news.ycombinator.com/item?id=49270040)

**Background**: The Wolfram Language is the programming language behind Mathematica, a computational system widely used in math, science, and engineering. Woxi's GUI is built with iced, a cross-platform Rust GUI library inspired by Elm. Because wolframscript typically takes seconds to start, Woxi's millisecond startup makes it practical for shell scripting, one-liners, and embedded use; it can even run in a browser via WebAssembly.

<details><summary>References</summary>
<ul>
<li><a href="https://www.wolfram.com/mathematica/">Wolfram Mathematica: Modern Technical Computing</a></li>
<li><a href="https://iced.rs/">iced - A cross-platform GUI library for Rust</a></li>
<li><a href="https://github.com/iced-rs/iced">GitHub - iced-rs/iced: A cross-platform GUI library for Rust, inspired by Elm · GitHub</a></li>

</ul>
</details>

**Discussion**: Commenters appreciated the project but noted limitations: some missed shortcuts like the % variable and multiple statements per block, while others suggested non-series approximations and a control systems module. One user reported that Woxi Studio successfully displayed multivariable calculus visualizations, though they couldn't verify correctness without Mathematica. Another commenter pointed out that the project was previously posted on Hacker News six months ago.

**Tags**: `#Wolfram Language`, `#Rust`, `#Open Source`, `#Computational Engine`, `#Mathematica Alternative`

---

<a id="item-9"></a>
## [Developer warns AI-generated code creates systems no one understands](https://simonwillison.net/2026/Aug/12/florian-herrengt/) ⭐️ 8.0/10

Florian Herrengt, a software engineer, published a blog post cautioning that AI-assisted development can produce "convoluted systems" so layered that no team member can grasp them. Simon Willison highlighted the quote, sparking discussion about the risks of relying on AI to write and debug code. This matters because it exposes a hidden cost of adopting AI coding assistants like Claude Fable: they can boost productivity while eroding developers' mental models of the codebase, making maintenance and debugging harder. It fuels a critical industry debate about whether AI-assisted programming improves or degrades software engineering practices. The quote explicitly references "Fable," likely referring to Anthropic's Claude Fable 5, an AI coding assistant capable of running autonomous agents for days. Herrengt's scenario depicts a team where even the AI cannot fix a recurring bug, and a developer answers "I don't know — let me ask Claude," illustrating over-reliance on AI systems.

rss · Simon Willison · Aug 12, 15:08

**Background**: The quote comes from Florian Herrengt's blog post "AI is removing the middle class of software engineering," written in 2026. As AI coding tools like Claude Fable become more powerful and are integrated into IDEs (e.g., GitHub Copilot with Fable 5), developers increasingly delegate complex tasks to them. Simon Willison, a prominent voice in the AI developer community, frequently shares such posts to provoke discussion about the long-term implications of AI-assisted programming.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>
<li><a href="https://www.developersdigest.tech/blog/best-ai-coding-tools-june-2026-post-fable5">Best AI Coding Tools July 2026: Updated After Opus 5 and Fable 5 API-Only - Developers Digest</a></li>

</ul>
</details>

**Tags**: `#AI`, `#software engineering`, `#code quality`, `#maintainability`, `#AI-assisted development`

---

<a id="item-10"></a>
## [Researchers Steal Hidden Reasoning Traces from Major LLM APIs](https://simonwillison.net/2026/Aug/11/stealing-reasoning-traces/) ⭐️ 8.0/10

A new paper shows that encrypted chain-of-thought blocks returned by Anthropic, OpenAI, and Google can be replayed into weaker sibling models, which can be jailbroken to reveal the stronger model's hidden reasoning in plaintext. The providers have reportedly fixed the vulnerability after being notified. This exposes a practical attack against the confidentiality guarantees of proprietary LLM APIs, showing that encrypted reasoning traces are not safe from determined adversaries. It raises urgent questions about how AI providers protect chain-of-thought data and has broad implications for model privacy, security audits, and competitive intelligence. The attack works because models in the same family share the same encryption key, allowing a trace captured from a frontier model to be replayed into a weaker sibling like Claude Haiku 4.5 and decrypted. The disclosure says providers fixed the issue, but the paper includes extracted traces and examples such as a prompt-injection variant that triggers data-exfiltration thinking.

rss · Simon Willison · Aug 11, 22:40

**Background**: Chain-of-thought (CoT) prompting is a technique that encourages a model to produce intermediate reasoning steps before a final answer, often improving accuracy on complex tasks. Frontier LLM APIs from companies like OpenAI, Anthropic, and Google return these reasoning traces to the client in encrypted form so that end users cannot read the hidden chain of thought. A replay attack is a security exploit in which valid data is intercepted and retransmitted in a different context; here a reasoning block captured from one session is replayed into a different model. Since weaker model siblings were found to share the same encryption key, the replayed block could be decrypted and then extracted via a jailbreak.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Chain-of-thought_reasoning">Chain-of-thought reasoning</a></li>
<li><a href="https://en.wikipedia.org/wiki/Replay_attack">Replay attack</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#security`, `#privacy`, `#chain-of-thought`, `#AI`

---

<a id="item-11"></a>
## [Adam's Per-Coordinate Scaling Breaks Rotation Invariance and Low-Rank Bias](https://www.reddit.com/r/MachineLearning/comments/1vmjb3p/the_loss_does_not_see_the_basis_but_adam_does_r/) ⭐️ 8.0/10

A Reddit analysis demonstrates that Adam's per-coordinate second-moment estimates break rotation invariance in factored models, causing it to lose the implicit low-rank bias that gradient descent preserves. Tests on nine update rules for underdetermined matrix sensing found two clean clusters: GD, shared-scalar Adam, Muon, and Shampoo keep the bias, while Adam, RMSProp, Lion, signum, and Adafactor lose it. This distinction clarifies which optimizers retain the beneficial implicit low-rank bias, which can affect generalization in overparameterized models. The findings may prompt practitioners to prefer shared-scalar or rotation-invariant optimizers when low-rank structure matters. The experiments matched training loss across all methods and used a one-parameter family interpolating between per-coordinate and shared-scalar denominators, showing recovery improves monotonically with shared-scalar updates. Muon behaves unexpectedly: it is exact on truly low-rank targets but degrades fastest when a spectral tail is added, crossing over with GD near 4% tail energy.

reddit · r/MachineLearning · /u/EtherealGlyph · Aug 12, 16:39

**Background**: In a factored model W = UV^T, the loss is invariant to rotations (U,V) → (UQ, VQ), and plain gradient descent respects this symmetry. Adam's per-coordinate scaling depends on the basis in which the factors are written, so it breaks the symmetry; this anisotropy is linked to losing the implicit low-rank bias that helps optimization find simple solutions. Prior work has shown that gradient-based methods often exhibit a low-rank simplicity bias, and the Muon optimizer uses Newton-Schulz orthogonalization to keep updates in a rotation-invariant form.

<details><summary>References</summary>
<ul>
<li><a href="https://kellerjordan.github.io/posts/muon/">Muon: An optimizer for hidden layers in neural networks | Keller Jordan blog</a></li>
<li><a href="https://minyoungg.github.io/overparam/resources/overparam-v2.pdf">Preprint revision 2 THE LOW-RANK SIMPLICITY BIAS IN DEEP NETWORKS Minyoung Huh</a></li>
<li><a href="https://cbmm.mit.edu/sites/default/files/publications/Implicit+Rank+Minimization.pdf">CBMM Memo No. 134 March 28, 2022 SGD Noise and Implicit Low-Rank Bias in Deep</a></li>

</ul>
</details>

**Tags**: `#optimizers`, `#implicit bias`, `#low-rank`, `#Adam`, `#matrix factorization`

---

<a id="item-12"></a>
## [LTX Releases Open-Source Video Model LTX-2.5, Runs Locally on a Single RTX 5090](https://ltx.io/model/ltx-2-5) ⭐️ 8.0/10

LTX released LTX-2.5, an open-source video generation foundation model with full weights, training code, and inference pipeline, capable of running locally on a single RTX 5090. It introduces a new diffusion video decoder and a Gemma 4 12B text encoder, and supports text-to-video and image-to-video generation with improved multi-shot coherence. This release is significant because high-quality video generation models previously required large cloud infrastructure or remained closed-source, while LTX-2.5 makes advanced text-to-video and image-to-video capabilities accessible on consumer hardware. The permissive licensing, free for companies with annual revenue below $10 million, could accelerate experimentation and adoption among independent developers and startups. LTX-2.5 can generate multi-shot scenes in one pass, edit real footage, and export cinema-grade EXR sequences. According to LTX, on a 98-prompt text-to-video artifact benchmark, LTX 2.5 Pro ranked first among ten models.

telegram · zaihuapd · Aug 12, 02:15

**Background**: Video generation models synthesize short clips from text or image prompts, typically using diffusion architectures that iteratively denoise latents into pixels. LTX-2.5 is part of a growing trend of open-weight models that run on consumer GPUs such as the RTX 5090. The diffusion video decoder itself is a small diffusion model that denoises pixels conditioned on latents, as noted in the Hugging Face diffusers implementation. Gemma 4 12B is a 12-billion-parameter multimodal transformer from Google, used here as the text encoder.

<details><summary>References</summary>
<ul>
<li><a href="https://ltx.io/model/ltx-2-5">LTX - 2 . 5 : LTX's Latest AI Open-Source Foundation Model | LTX</a></li>
<li><a href="https://github.com/huggingface/diffusers/blob/main/src/diffusers/pipelines/ltx2/pipeline_ltx2_diffusion_decode.py">diffusers/src/diffusers/pipelines/ltx2/pipeline_ltx2_ diffusion _ decode .py...</a></li>
<li><a href="https://blog.google/innovation-and-ai/technology/developers-tools/introducing-gemma-4-12b/">Introducing Gemma 4 12 B</a></li>

</ul>
</details>

**Tags**: `#video generation`, `#open-source`, `#AI model`, `#local inference`, `#LTX`

---

<a id="item-13"></a>
## [WeChat Releases WeLM, Resource-Efficient LLM Family](https://x.com/Weixin_WeChat/status/2087509298310209718) ⭐️ 8.0/10

Tencent's WeChat team announced WeLM, a family of general large language models focused on resource efficiency. The WeLM-80B model (3B activated parameters) is now deployed in WeChat's AI agent Xiaowei, and the MoE-based WeLM-617B (23B activated) is in development. This marks a significant push toward resource-efficient large language models, allowing advanced AI to scale across WeChat's massive user base without prohibitive compute costs. The MoE architecture enables a larger model with a modest activation footprint, potentially influencing how other LLMs are designed for real-world deployment. WeLM-80B has 80 billion total parameters but activates only 3 billion per inference, and it already powers Xiaowei, enabling dialogue, search, WeChat native operations, and mini-program calls. The in-development WeLM-617B activates just 23 billion parameters with a mixture-of-experts design and is intended for complex WeChat tasks such as smart mini-program development and small-tool generation.

telegram · zaihuapd · Aug 12, 13:58

**Background**: Traditional dense large language models activate all their parameters for every token, making them computationally expensive. Mixture of Experts (MoE) addresses this by dividing the network into specialized experts and using a router to activate only the most relevant ones per input, enabling massive scale with minimal compute. Activated parameters are the subset of a model's total parameters actually used during a single inference, as seen in models like Qwen3-235B-A22B.

<details><summary>References</summary>
<ul>
<li><a href="https://newsletter.maartengrootendorst.com/p/a-visual-guide-to-mixture-of-experts">A Visual Guide to Mixture of Experts ( MoE )</a></li>
<li><a href="https://researchaudio.io/p/mixture-of-experts-moe-in-large-language-models">Mixture of Experts ( MoE ) in Large Language Models</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#WeChat`, `#MoE`, `#AI`, `#Language Models`

---

<a id="item-14"></a>
## [Zed launches Delta for realtime collaborative AI conversations](https://zed.dev/blog/introducing-delta) ⭐️ 7.0/10

Zed announced Delta, a feature that enables realtime collaborative AI conversations with inline comments and conversation-as-document workflows. The announcement describes Delta as a focused place to iterate on these primitives, with DeltaDB coming to Zed later. This shifts AI-assisted coding from solitary chat to a multiplayer, document-centric workflow, making AI conversations reviewable and shareable. It could reshape code review, mentoring, and how teams audit AI-generated code changes. Delta treats AI conversations as documents, allowing inline comments within agent threads rather than attaching discussion to code only after a commit or pull request. Zed says DeltaDB, its delta-based local storage engine that tracks code history and agent conversations, will also come to Zed in the future.

hackernews · khy · Aug 12, 18:19 · [Discussion](https://news.ycombinator.com/item?id=49276574)

**Background**: Zed is a high-performance, multiplayer code editor built for realtime collaboration. As AI coding agents become more common, teams need ways to review and understand how AI-generated changes were produced. Delta’s conversation-as-document approach answers this by turning ephemeral AI chats into durable, editable artifacts, contrasting with traditional pull requests that attach discussion after code is pushed.

<details><summary>References</summary>
<ul>
<li><a href="https://zed.dev/blog/introducing-delta">Introducing Delta — Zed 's Blog</a></li>
<li><a href="https://runtimewire.com/article/zed-deltadb-version-control-agent-conversations">Nathan Sobo's Zed takes aim at pull requests with... - RuntimeWire</a></li>
<li><a href="https://asibiont.com/en/blog/zed-deltadb-fishka-vibe-coding-kak-uskorit-razrabotku-v-10-raz">Zed DeltaDB: The Hidden Engine Behind Seamless... — ASI Biont Blog</a></li>

</ul>
</details>

**Discussion**: Reactions were mixed. Some commenters were intrigued by the potential for mentoring and auditing PRs, while others found AI prose verbose and low-contrast page design hurt readability. One skeptic argued that rapid advances in frontier models have made Delta’s value proposition less compelling, suggesting the real opportunity lies in a service that stores data and runs agent sessions.

**Tags**: `#AI`, `#code collaboration`, `#Zed`, `#LLM`, `#realtime editing`

---

<a id="item-15"></a>
## [Tim King, Key AmigaDOS Developer, Passes Away](https://amiga-news.de/en/news/AN-2026-08-00070-EN.html) ⭐️ 7.0/10

Tim King, a key developer of AmigaDOS, has died, according to a report from Amiga-news.de. The news has prompted heartfelt recollections from the retrocomputing community about his impact on their careers. King's work on AmigaDOS shaped the command-line experience of the Amiga, a platform that influenced many developers and enthusiasts. His passing marks the loss of an important figure in early personal-computing history, and the community's response shows how deeply his contributions resonated. AmigaDOS was the disk operating system component of AmigaOS, providing the command-line interface, file system management, and file utilities. According to community comments, King was also the founder of UK Online, and an October 2021 interview with him has been shared in the discussion.

hackernews · doener · Aug 12, 14:09 · [Discussion](https://news.ycombinator.com/item?id=49272655)

**Background**: The Amiga was a family of personal computers introduced in the mid-1980s, celebrated for its advanced graphics and sound capabilities. AmigaDOS, built on a port of the TRIPOS operating system, handled the command-line interface and file management for AmigaOS. Tim King was among the developers who adapted TRIPOS into AmigaDOS, helping define how users interacted with the system. The Amiga retains a dedicated retrocomputing community that continues to preserve and celebrate its history.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AmigaDOS">AmigaDOS - Wikipedia</a></li>
<li><a href="https://www.osnews.com/story/15710/history-of-the-amiga/">History of the Amiga – OSnews</a></li>

</ul>
</details>

**Discussion**: Commenters expressed gratitude and shared personal memories of Tim King. Several credited AmigaDOS with steering them toward command-line interfaces and eventually Linux, while one recalled him as a friendly founder of UK Online. Another commenter provided a link to an interview with King from October 2021.

**Tags**: `#Amiga`, `#AmigaDOS`, `#Obituary`, `#Retrocomputing`

---

<a id="item-16"></a>
## [Mass Scans Spoof AI Bot User Agents Like ClaudeBot](https://knownagents.com/insights) ⭐️ 7.0/10

Mass vulnerability scans are spoofing AI bot user agents such as ClaudeBot, according to Knownagents insights. This adds a layer of subterfuge to the typical internet background traffic from automated scanners. This matters because security teams and site operators often allowlist or prioritize AI crawlers, and attackers may exploit that trust to evade detection. It highlights that user-agent strings alone are no longer a reliable signal for bot identification. The spoofing appears in HTTP User-Agent headers, which can be verified by checking the owning ASN of the requesting IP. Blocking most VPS providers reportedly removes many faked bots, though some originate from residential or hijacked mobile connections.

hackernews · gavinhking · Aug 12, 14:02 · [Discussion](https://news.ycombinator.com/item?id=49272569)

**Background**: ClaudeBot is Anthropic's web crawler used to train AI models, and many websites choose to allow it in their robots.txt settings. User agent spoofing is a well-known technique where a client deliberately changes its User-Agent HTTP header to impersonate another application or bot. Because AI crawlers are often trusted, malicious scanners may mimic them to blend in with legitimate traffic while probing for vulnerabilities.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ClaudeBot">ClaudeBot</a></li>
<li><a href="https://en.wikipedia.org/wiki/User_agent_spoofing">User agent spoofing</a></li>
<li><a href="https://primores.org/blog/anthropic-crawlers/">Anthropic's Crawlers: ClaudeBot , Claude -SearchBot... | Primores</a></li>

</ul>
</details>

**Discussion**: Commenters largely downplayed the novelty, noting that any server with open ports already sees thousands of scans daily and this is just a new twist on old junk traffic. They recommend checking ASN ownership, blocking VPS ranges, and using tools like tcpdump; one commenter also shared Cloudflare Workers they built to combat such traffic. A dissenting view questioned why attackers would impersonate AI bots, since those are often blocked anyway, suggesting it might be intended to make AI companies look bad.

**Tags**: `#security`, `#bot detection`, `#vulnerability scanning`, `#web infrastructure`, `#AI bots`

---

<a id="item-17"></a>
## [Why Tiny JPEGs Look Different in Chrome: A Technical Walkthrough](https://guillaumetech.github.io/posts/jpg-scaling-chrome/) ⭐️ 7.0/10

The article investigates why small JPEG images are rendered with visibly different results in Chrome compared with Firefox. It identifies Chrome's specific image-scaling optimization, which trades some rendering fidelity for faster decoding of tiny images, as the root cause. This matters for web developers who serve small icons or thumbnails: the same image can look blurry, aliased, or otherwise wrong depending on the browser. Understanding the difference helps them choose appropriate image formats and resolutions instead of fighting browser-specific artifacts. The optimization appears to be triggered when Chrome decodes JPEGs at a reduced scale (for example, a 2000x2000 image displayed at 20x20), avoiding a full decode and high-quality resample. Firefox currently performs a full decode and uses different downscaling filters, which often results in sharper output but with slightly more ringing artifacts; a Firefox change for lower-scale JPEG decompression is tracked in bugzilla.mozilla.org/show_bug.cgi?id=2033250.

hackernews · gutechh · Aug 12, 14:00 · [Discussion](https://news.ycombinator.com/item?id=49272549)

**Background**: JPEG is a lossy image format that stores images in 8x8 DCT blocks, making it possible to decode only part of the frequency data to produce a lower-resolution version cheaply. Browsers need to resample images whenever a page displays them smaller than their intrinsic size, and each browser has its own algorithms and performance shortcuts. Chrome's shortcut is generally good for large photos, but for very small renderings it produces visually different results than Firefox's full decode plus high-quality downscaling approach. Such browser differences are the reason developers sometimes need CSS/image-rendering hints or dedicated extensions to get consistent results.

<details><summary>References</summary>
<ul>
<li><a href="https://entropymine.com/resamplescope/notes/browsers/">How web browsers resize images</a></li>
<li><a href="https://chromewebstore.google.com/detail/better-image-scaling/cjifmfjjelmmfknfijnfdciabkblgame">Better Image Scaling - Chrome Web Store</a></li>

</ul>
</details>

**Discussion**: Commenters broadly agree with the article's conclusion while adding nuance: one notes that PNGs are also affected through the same Chrome optimization and that it broke icons in an Electron app, another stresses that developers should use appropriately sized images instead of huge sources for tiny icons, and someone points out Firefox already has work in progress for lower-scale JPEG decompression. There is also a debate about whether Firefox does full rendering then scaling, and many commenters say they prefer Firefox's sharper algorithm over Chrome's blurrier output.

**Tags**: `#web-development`, `#browser-engineering`, `#image-processing`, `#jpeg`, `#chrome`

---

<a id="item-18"></a>
## [uBlock Origin Stops Fighting Facebook Ads, Cites Unsustainable Effort](https://digitalescapetools.com/2026/08/ublock-origin-stops-chasing-facebook-ads.html) ⭐️ 7.0/10

uBlock Origin has announced it will no longer maintain filters designed to block ads on Facebook, citing the unsustainable technical effort required to keep pace with Facebook's countermeasures. The decision was confirmed by coverage on Neowin and discussed extensively on the r/uBlockOrigin subreddit. This marks a significant concession in the ad-blocking arms race, showing that even the most popular open-source ad blockers can struggle against platforms that control their own ad delivery. Users who rely on ad blockers to use Facebook without ads will be directly affected, and the broader ad-blocking community may need to rethink its strategies. Facebook serves ads as first-party content from its own domain, which makes them nearly indistinguishable from organic posts using traditional filter lists. uBlock Origin's developer Raymond Hill and the community concluded that the continuous cat-and-mouse effort was no longer worth the resources.

hackernews · Markoff · Aug 12, 11:28 · [Discussion](https://news.ycombinator.com/item?id=49270726)

**Background**: uBlock Origin is a free, open-source browser extension for content filtering and ad blocking, with tens of millions of active users across Firefox and Chromium-based browsers. It relies on filter lists such as EasyList to block requests to known advertising and tracking domains. However, first-party advertising—ads served from the same domain as the content—circumvents this approach, because the requests cannot be blocked without breaking the site itself.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/UBlock_Origin">UBlock Origin</a></li>
<li><a href="https://ublockorigin.com/">uBlock Origin - Free, open-source ad blocker extension</a></li>

</ul>
</details>

**Discussion**: Reddit commenters largely supported the decision, with some noting that Facebook's ads are nearly impossible to block at scale. Others speculated that the arms race may eventually end with on-device computer vision models that visually detect ads, while a few questioned why Facebook invests so much in bypassing users who are unlikely to click ads anyway.

**Tags**: `#ad-blocking`, `#privacy`, `#Facebook`, `#uBlock Origin`, `#web`

---

<a id="item-19"></a>
## [LLMs Can't Losslessly Transform Text: Authors Must Own Every Sentence](https://simonwillison.net/2026/Aug/11/there-are-no-lossless-transformations-of-natural-language-text/) ⭐️ 7.0/10

Sophie Alpert published an internal engineering policy arguing that LLMs cannot losslessly transform natural-language text, so any AI-assisted writing must be fully vetted by the author. Simon Willison highlighted this as crucial guidance for engineers who use LLMs to draft documentation. This matters because AI-assisted writing is now common in engineering teams, and unexamined AI text can mislead readers and erode trust. The policy provides a concrete, enforceable rule: every sentence must represent the author's own thoughts, preventing the 'AI wrote it, ignore it' excuse. The core argument is that every rewrite changes meaning, and an LLM lacks the author's detailed mental model, so information is inevitably lost. Alpert's post is deliberately short, demonstrating the recommended style it advocates.

rss · Simon Willison · Aug 11, 23:48

**Background**: In information theory, lossless transformations preserve all original information, while lossy transformations discard some detail. The post applies this metaphor to natural-language text: LLM paraphrasing functions as a lossy transformation because the model cannot know the author's full intent. This connects to broader discussions about AI misuse in documentation and the need for human accountability.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Lossless_compression">Lossless compression - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Lossy_compression">Lossy compression - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#AI-writing`, `#LLM`, `#documentation`, `#engineering-policy`, `#natural-language`

---

<a id="item-20"></a>
## [Musk says all future Teslas will get Starlink, starting with Cybercab](https://www.techspot.com/news/113429-elon-musk-every-tesla-have-starlink-starting.html) ⭐️ 7.0/10

During Tesla's earnings call, Elon Musk announced that Starlink will be integrated into all future Tesla vehicles, at least in markets where Starlink operates. Tesla's official Robotaxi account showcased a Cybercab with a built-in Starlink V5 antenna, capable of up to 375 Mbps, positioned in the rear roof. This announcement signals a deep integration between Tesla and SpaceX, giving vehicles ubiquitous satellite connectivity that could enable autonomous driving and entertainment features anywhere. It positions Starlink as a key infrastructure layer for Tesla's robotaxi fleet and creates a unique competitive advantage over rivals dependent on cellular networks. The Cybercab, which has no steering wheel or pedals, uses the satellite connection for navigation, customer service, and fleet management. The Starlink V5 dish is smaller and more energy-efficient than previous models but offers slightly lower speeds (375+ Mbps) compared to the V4's 400+ Mbps. No production timeline for Starlink-equipped vehicles has been announced.

telegram · zaihuapd · Aug 12, 03:53

**Background**: Starlink is SpaceX's satellite internet constellation, designed to provide high-speed broadband globally, especially in underserved areas. The Tesla Cybercab is a purpose-built autonomous vehicle unveiled in October 2024, with no steering wheel or pedals, intended for Tesla's future robotaxi service. Pilot production of the Cybercab is reported to have begun in February 2026, and using Starlink could ensure continuous connectivity for autonomous operations beyond cellular coverage.

<details><summary>References</summary>
<ul>
<li><a href="https://www.engadget.com/2219549/tesla-teases-cybercab-with-a-built-in-starlink-v5-antenna/">Tesla teases Cybercab with a built-in Starlink V5 antenna - Engadget</a></li>
<li><a href="https://en.wikipedia.org/wiki/Tesla_Cybercab">Tesla Cybercab</a></li>
<li><a href="https://ground.news/article/starlink-app-quietly-adds-new-v5-dish">Starlink V5 Is Here, and It’s Lighter, Smarter, and Far More Efficient</a></li>

</ul>
</details>

**Tags**: `#Tesla`, `#Starlink`, `#Cybercab`, `#satellite internet`, `#autonomous vehicles`

---

<a id="item-21"></a>
## [Tencent Q2 Revenue Beats, AI Capex Surge Turns Free Cash Flow Negative](https://wallstreetcn.com/articles/3779275) ⭐️ 7.0/10

Tencent reported Q2 2026 revenue of 204.8 billion RMB, up 11% year-over-year and slightly above Bloomberg consensus. Net profit rose only 0.7% to 56 billion RMB, missing expectations, while capital expenditure nearly tripled to 52.8 billion RMB, driving free cash flow to negative 13.8 billion RMB. This underscores how deeply Tencent is betting on AI infrastructure, with tripled capex pushing free cash flow negative, a trend also seen at Alphabet and Tesla amid intensifying AI spending. Investors must weigh short-term cash flow deterioration against long-term AI competitiveness for major tech firms. Excluding prepayments for AI compute capacity, adjusted free cash flow was 37.6 billion RMB. Marketing services revenue led with 22% growth, domestic games rose 17%, and international games dipped 0.8% due to exchange rates. AI office assistant WorkBuddy saw accelerating user growth and ranked first in monthly desktop AI office agent visits in China.

telegram · zaihuapd · Aug 12, 10:30

**Background**: Tencent is one of China's largest internet companies, deriving revenue from gaming, advertising, and cloud/AI services. Free cash flow equals operating cash flow minus capital expenditure, and turning negative means investment spending has outstripped operational cash generation. In 2025-2026, major global tech companies have sharply increased capex for AI data centers and computing power, causing similar free cash flow swings at firms like Alphabet and Tesla. WorkBuddy is Tencent Cloud's desktop AI agent office tool that autonomously plans and delivers multimodal complex tasks.

<details><summary>References</summary>
<ul>
<li><a href="https://www.workbuddy.cn/">WorkBuddy - AI Agent 办 公 新范式</a></li>
<li><a href="https://wallstreetcn.com/articles/3777767">谷歌、特斯拉双双 现 金 流 转 负 ，对于AI交易意味着什么？ - 华尔街见闻</a></li>

</ul>
</details>

**Tags**: `#Tencent`, `#earnings`, `#AI infrastructure`, `#capital expenditure`, `#financial results`

---

<a id="item-22"></a>
## [Enterprise SSDs Reach 48% of NAND Shipments; YMTC Enters Top Three](https://china.counterpointresearch.com/%e6%9c%8d%e5%8a%a1%e5%99%a8%e9%9c%80%e6%b1%82%e6%8e%a8%e5%8d%87%e4%bc%81%e4%b8%9a%e7%ba%a7-ssd-%e5%8d%a0-nand-%e5%87%ba%e8%b4%a7%e9%87%8f%e7%99%be%e5%88%86%e4%b9%8b-48/) ⭐️ 7.0/10

According to a Counterpoint report, enterprise SSDs accounted for 48% of global NAND shipments in the second quarter of 2026, nearly doubling year-over-year, with industry revenue growing fivefold from a year earlier. Yangtze Memory Technologies Co. (YMTC) surpassed Kioxia for the first time to take third place with a 14% shipment share. This shift shows that AI-driven workloads, especially inference, are reshaping the storage market, making enterprise SSDs the core driver of NAND consumption. It also signals a changing competitive landscape, with a Chinese NAND maker breaking into the top three for the first time. Samsung led with a 25% share and SK hynix followed with 22%, while YMTC ranked third by shipment share but only fifth by revenue because its products are more consumer-oriented. The report expects enterprise SSDs to consume more than half of total NAND bit shipments by the end of the year.

telegram · zaihuapd · Aug 12, 11:00

**Background**: Enterprise SSDs are built for data centers and servers, requiring far higher performance, reliability, and endurance than consumer SSDs, which creates a much higher technical barrier. NAND bit shipments measure total flash storage capacity shipped, not just unit count. YMTC is one of China's leading 3D NAND flash memory manufacturers and has been expanding rapidly in the storage chip market.

<details><summary>References</summary>
<ul>
<li><a href="https://h5.ifeng.com/c/vivoArticle/v002QqzWzsSMS-_HoyZh2etUnZE2wUomovbK6NdMfmFr40Ew__?isNews=1&showComments=0">大普微创 业 板IPO注册生效 国产高端存储拥抱AI浪潮</a></li>
<li><a href="https://zh.wikipedia.org/wiki/中国半导体产业">中国半导体产业 - 维基百科，自由的百科全书</a></li>
<li><a href="https://www.ymtc.com/">首页| 长 江 存 储 官网- 长 江 存 储</a></li>

</ul>
</details>

**Tags**: `#SSD`, `#NAND`, `#AI`, `#storage`, `#market-analysis`

---