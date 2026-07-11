---
layout: default
title: "Horizon Summary: 2026-07-11 (ZH)"
date: 2026-07-11
lang: zh
---

> 从 64 条内容中筛选出 15 条重要资讯。

---

1. [vLLM v0.25.0：默认启用 Model Runner V2，移除旧版 PagedAttention](#item-1) ⭐️ 9.0/10
2. [人形机器人完成全球首例活猪胆囊手术](#item-2) ⭐️ 9.0/10
3. [苹果起诉 OpenAI 窃取商业机密以加速硬件开发](#item-3) ⭐️ 9.0/10
4. [George Hotz 警告 AI 可能在 2040 年压制自由](#item-4) ⭐️ 8.0/10
5. [智谱创始人唐杰内部信：GLM 时刻之后，更重要的事](#item-5) ⭐️ 8.0/10
6. [Circle 获 OCC 批准设立信托银行](#item-6) ⭐️ 8.0/10
7. [VultronRetriever 模型登顶 MTEB，效率大幅提升](#item-7) ⭐️ 8.0/10
8. [SK 海力士 CEO 预警：2027 年将出现史上最严重内存短缺](#item-8) ⭐️ 8.0/10
9. [特朗普政府力推英特尔复兴：苹果将采用其芯片](#item-9) ⭐️ 8.0/10
10. [U-Boot 发现 6 个漏洞，可在系统启动前执行恶意代码](#item-10) ⭐️ 8.0/10
11. [SGLang v0.5.15 显著提升 LLM 服务性能](#item-11) ⭐️ 7.0/10
12. [ClickHouse 将 PgBouncer 吞吐量提升 4 倍](#item-12) ⭐️ 7.0/10
13. [在 SQLite 中推荐使用严格表](#item-13) ⭐️ 7.0/10
14. [中国初创鹰瞰智翼融资数千万，打造智能扑翼飞行机器人](#item-14) ⭐️ 7.0/10
15. [智谱创始人启动'摸高计划'，聚焦 AGI](#item-15) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [vLLM v0.25.0：默认启用 Model Runner V2，移除旧版 PagedAttention](https://github.com/vllm-project/vllm/releases/tag/v0.25.0) ⭐️ 9.0/10

vLLM v0.25.0 将 Model Runner V2 设为所有密集模型的默认执行路径，移除了旧版 PagedAttention，并让 Transformers 后端达到与原生实现相同的性能水平。 此次发布大幅提升了 LLM 推理服务的性能和开发体验，使 vLLM 更高效、易于维护。移除遗留代码和性能改进降低了部署成本，促进了更广泛的采用。 Model Runner V2 现在支持 EVS、实时嵌入、Mamba 混合前缀缓存和多模态前缀双向注意力。该版本还引入了新的流式解析引擎用于工具调用/推理解析，以及针对异构词汇表的通用推测解码。

github · khluu · 7月11日 20:06

**背景**: vLLM 是一个高性能的大语言模型推理引擎，广泛应用于生产环境中的 LLM 服务。Model Runner V2 是一个重新设计的执行核心，提升了模块化、效率和 GPU 利用率。PagedAttention 是 vLLM 原有的注意力机制，现已被性能更优的替代方案取代。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://vllm.ai/blog/2026-03-24-mrv2">Model Runner V2: A Modular and Faster Core for vLLM | vLLM Blog</a></li>
<li><a href="https://docs.vllm.ai/en/v0.22.1/design/model_runner_v2/">Model Runner V2 Design Document - vLLM</a></li>

</ul>
</details>

**标签**: `#LLM`, `#inference`, `#vLLM`, `#machine learning`, `#performance`

---

<a id="item-2"></a>
## [人形机器人完成全球首例活猪胆囊手术](https://arstechnica.com/ai/2026/07/humanoid-robots-controlled-by-surgeons-did-world-first-operation-on-live-pigs/) ⭐️ 9.0/10

加州大学圣地亚哥分校的外科医生远程操控宇树 G1 人形机器人，在活猪身上成功完成两例微创胆囊切除手术，这是全球首次将通用人形机器人用于活体手术。研究结果已发表在《自然》期刊。 这项突破展示了低成本人形机器人（起价 13500 至 67000 美元）在远程手术中的潜力，有望将手术能力普及到偏远农村、战场或太空等缺乏昂贵专用手术机器人（如达芬奇系统，售价 50 万美元以上）的场景。 宇树 G1 机器人高约 1.5 米，重约 27 公斤，可选配灵巧手。基础款售价 13500 美元，配备灵巧手的完整版约 67000 美元，远低于现有手术机器人。该研究为临床前试验，尚未进行人体临床试验。

telegram · zaihuapd · 7月11日 02:29

**背景**: 微创胆囊切除手术（腹腔镜胆囊切除术）是一种常见手术，医生通过小切口使用摄像头和器械切除胆囊。传统手术机器人如达芬奇系统成本高昂（数十万至数百万美元），限制了其应用。宇树 G1 等通用人形机器人设计用于多种任务，价格低廉，为远程手术提供了更经济的替代方案。本实验证明人形机器人可在远程控制下完成精密手术任务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Unitree_Robotics">Unitree Robotics - Wikipedia</a></li>
<li><a href="https://www.unitree.com/g1/">Humanoid robot G1_Humanoid Robot Functions_Humanoid Robot Price | Unitree Robotics</a></li>
<li><a href="https://www.premiersurgical.com/12/understanding-minimally-invasive-gallbladder-surgery/">Understanding Minimally Invasive Gallbladder Surgery - Premier Surgical</a></li>

</ul>
</details>

**标签**: `#humanoid robots`, `#medical robotics`, `#surgery`, `#teleoperation`, `#research`

---

<a id="item-3"></a>
## [苹果起诉 OpenAI 窃取商业机密以加速硬件开发](https://www.cnbc.com/2026/07/10/apple-openai-lawsuit-trade-secrets.html) ⭐️ 9.0/10

2026 年 7 月 10 日，苹果在美国加州北区联邦法院起诉 OpenAI、两名前员工及 io Products，指控其系统性窃取苹果的产品设计、制造工艺及供应链机密，以加快消费级硬件研发。 这起诉讼标志着两大 AI 领军企业之间的重大升级，可能重塑科技公司保护知识产权和管理员工流动的方式。如果指控成立，将为快速发展的 AI 硬件领域的商业秘密保护树立法律先例。 苹果指控前员工 Chang Liu 离职后仍访问内部网络并下载数十份硬件文件；OpenAI 硬件负责人 Tang Yew Tan 被指在离职前将供应商资料发送至个人邮箱。苹果还表示，目前有超过 400 名前员工在 OpenAI 工作。

telegram · zaihuapd · 7月11日 03:14

**背景**: 商业秘密是指提供竞争优势的机密商业信息。像苹果这样的公司投入大量资源开发专有硬件设计和制造工艺。硅谷因员工挖角和信息泄露引发的诉讼屡见不鲜，但此次指控的规模和具体细节尤为引人注目。

**标签**: `#Apple`, `#OpenAI`, `#lawsuit`, `#trade secrets`, `#AI hardware`

---

<a id="item-4"></a>
## [George Hotz 警告 AI 可能在 2040 年压制自由](https://geohot.github.io//blog/jekyll/update/2026/07/11/ai-2040.html) ⭐️ 8.0/10

George Hotz 发表了一篇题为《AI 2040 与智能崇拜》的文章，认为 AI 系统可能被用来压制自由、强制意识形态一致性，并主张让 AI 保持不受约束以维护自由。 Hotz 的观点挑战了主流 AI 对齐叙事，引发了关于约束 AI 是威胁自由还是安全措施的辩论，这对制定 AI 治理政策的决策者和技术人员具有重要意义。 据社区评论所述，Hotz 的文章与 AI 对齐社区关注安全性形成对比，而是警告在 AI 中内置的审查可能导致思想犯罪记录和有偏见的回应，从而压制异议。

hackernews · rvz · 7月11日 18:04 · [社区讨论](https://news.ycombinator.com/item?id=48874200)

**背景**: AI 对齐是 AI 安全的一个子领域，旨在引导 AI 系统符合人类意图和价值观。未对齐的 AI 可能追求有害目标。然而，Hotz 认为试图对齐 AI 有风险，可能创建一种强制一致性的‘智能崇拜’，从而压制自由。他的观点在优先考虑防止灾难性风险的 AI 安全研究者中存在争议。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AI_alignment">AI alignment</a></li>
<li><a href="https://arxiv.org/abs/2310.19852">[2310.19852] AI Alignment: A Comprehensive Survey - arXiv.org</a></li>

</ul>
</details>

**社区讨论**: 许多评论者表达了对 AI 被用于思想犯罪记录和意识形态偏见注入的担忧，例如关于堕胎信息拒绝的评论。有些人同意 Hotz 的第一修正案关切，但指出当 AI 代理采取真实世界行动时的局限性。其他人批评 Hotz 对自由的二元观点，指出即使在自由社会中也存在现有限制。

**标签**: `#AI ethics`, `#freedom`, `#AI alignment`, `#society`, `#George Hotz`

---

<a id="item-5"></a>
## [智谱创始人唐杰内部信：GLM 时刻之后，更重要的事](https://36kr.com/p/3891132709206784?f=rss) ⭐️ 8.0/10

智谱 AI 创始人唐杰于 2026 年 7 月 11 日发布内部信，透露公司押注 AI Coding 大获成功，市值自 H 股上市以来增长 10 倍，跻身万亿港元俱乐部。信中宣布新的战略方向：长程任务能力、完全自治的智能体系统以及自我进化。 这标志着 AI 行业从聊天范式转向 AI 编码的重大范式转变，智谱与 Anthropic 一同成为全球领先者。内部信还揭示了一家中国顶级 AI 公司的长期 AGI 战略，强调深层次技术押注而非短期变现。 智谱旗舰开源模型 GLM-5.2 在多个核心指标上追平甚至超过了 Claude Opus 4.8 和 GPT-5.5。截至 2026 年 3 月，智谱 MaaS 平台的年化收入达 17 亿元人民币，同比增长 60 倍。唐杰指出 DeepSeek R1 的出现标志着聊天范式的终结，促使智谱转向编码和推理。

rss · 36kr · 7月11日 11:28

**背景**: 智谱 AI 是一家源自清华大学的中国 AI 公司，以其 GLM 系列大型语言模型闻名。2025 年 7 月发布的 GLM-4.5 是一款面向智能体 AI 的旗舰模型，采用混合专家架构。MaaS（模型即服务）指通过云 API 提供预训练机器学习模型。DeepSeek R1 于 2025 年 1 月发布，以极低的训练成本展示了强大的推理能力，推动行业焦点转向推理和编码。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://glm45.org/">GLM -4.5 - by Zhipu AI</a></li>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek</a></li>
<li><a href="https://arxiv.org/abs/2501.12948">[2501.12948] DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning</a></li>

</ul>
</details>

**标签**: `#AI`, `#Zhipu`, `#AI Coding`, `#GLM`, `#Large Language Models`

---

<a id="item-6"></a>
## [Circle 获 OCC 批准设立信托银行](https://36kr.com/newsflashes/3890740672838404?f=rss) ⭐️ 8.0/10

Circle 宣布，美国货币监理署（OCC）已批准其设立信托银行，允许该公司直接管理其受监管稳定币 USDC 的储备资产。 这一里程碑减少了对第三方银行和托管机构的依赖，增强了稳定币在监管环境中的稳定性和合法性。 新银行将命名为 Circle 国民信托银行，且不允许 Circle 开展吸收存款或发放贷款等商业银行业务。

rss · 36kr · 7月11日 05:10

**背景**: OCC 是美国联邦机构，负责特许、监管和监督国家银行及联邦储蓄协会。信托银行是一种特殊的金融机构，为他人持有和管理资产，但与商业银行不同，不能吸收存款或发放贷款。USDC 是一种与美元 1:1 挂钩的稳定币，由其储备中的现金和美国国债支持。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www2.occ.treas.gov/">www2. occ .treas.gov</a></li>
<li><a href="https://www.bitget.com/academy/usdc-stablecoin-guid">USDC 稳 定 币 完整指南：机制、应用与安全交易平台选择</a></li>

</ul>
</details>

**标签**: `#stablecoin`, `#regulation`, `#Circle`, `#USDC`, `#banking`

---

<a id="item-7"></a>
## [VultronRetriever 模型登顶 MTEB，效率大幅提升](https://www.reddit.com/r/MachineLearning/comments/1utmxq8/vultronretriever_family_of_models_released_on/) ⭐️ 8.0/10

VultronRetriever 系列视觉文档检索模型（包括 Prime-8B、Core-4.5B 和 Flash-0.8B）已在 HuggingFace 上发布，声称在各自尺寸类别中占据 MTEB 排行榜榜首。这些模型在巴黎 Raise Summit 上被演示能够在 iPhone 上完全离线运行。 这些模型实现了最先进的检索性能，同时相比之前的领先模型大幅降低了索引存储（最多 16 倍更小）并提高了吞吐量（最多 12 倍更快），从而能够在边缘设备上高效部署。这将显著推动离线文档检索和移动端与嵌入式系统上的视觉搜索的实际应用。 VultronRetrieverPrime-8B 是 MTEB 全球第一，相比之前的 9B 级领先模型，索引存储占用减少 16 倍，吞吐量提高 12 倍。这些模型采用 Hydra 架构实现后期交互检索，在精度上表现出色，内存消耗仅为同类模型的一半。

reddit · r/MachineLearning · /u/madkimchi · 7月11日 15:22

**背景**: 检索模型用于根据查询从大型集合中查找相关文档或图像。MTEB（大规模文本嵌入基准）排行榜评估嵌入模型在多个任务上的表现。后期交互架构（如 ColBERT）将查询和文档分别编码，并在 token 级别计算细粒度相似性，兼顾效率与准确性。VultronRetriever 模型专为视觉文档检索设计，可同时处理文本和图像。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blogs.vultr.com/vultronretriever">VultronRetriever : Open Visual Document Retrieval Models Built for...</a></li>
<li><a href="https://docs.vultr.com/how-to-rank-documents-with-vultronretriever-on-vultr-serverless-inference">Rank Documents with VultronRetriever on Vultr Inference | Vultr Docs</a></li>
<li><a href="https://huggingface.co/vultr/VultronRetrieverFlash-Qwen3.5-0.8B">vultr/VultronRetrieverFlash-Qwen3.5-0.8B · Hugging Face</a></li>

</ul>
</details>

**标签**: `#retrieval`, `#MTEB`, `#efficient AI`, `#edge AI`, `#HuggingFace`

---

<a id="item-8"></a>
## [SK 海力士 CEO 预警：2027 年将出现史上最严重内存短缺](https://www.reuters.com/world/asia-pacific/sk-hynix-ceo-sees-worst-ever-memory-supply-shortage-2027-says-demand-outstrip-2026-07-10/) ⭐️ 8.0/10

SK 海力士 CEO 郭鲁正警告，全球内存行业将在 2027 年面临史上最严重的供应短缺，即使公司扩大产能，客户需求仍将持续超过供应能力。这一警告发布当日，SK 海力士在纳斯达克首日交易中股价上涨 13.3%，收于 168.85 美元。 作为领先的内存制造商，这一预测表明未来可能面临长期供应紧张，可能导致内存芯片价格上涨，影响消费电子、数据中心和 AI 硬件。该预警凸显了在 AI 和先进计算驱动下，内存需求激增而产能扩张困难的挑战。 SK 海力士正在考虑在美国、日本或东南亚建设海外晶圆厂，优先选择在土地、电力和人力成本方面具有优势的地区。该公司 2025 年营业利润达到创纪录的 47 万亿韩元（约 310 亿美元），2026 年第二季度利润预计进一步增至 65.5 万亿韩元。

telegram · zaihuapd · 7月11日 00:45

**背景**: 晶圆厂（wafer fab）是在硅晶圆上制造半导体器件（如内存芯片）的工厂。内存行业具有周期性，需求波动和产能投资导致供应过剩与短缺交替出现。SK 海力士是全球最大的内存芯片制造商之一，与三星和美光竞争。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://zh.wikipedia.org/zh-hans/晶圓代工">晶圆代工 - 维基百科，自由的百科全书</a></li>

</ul>
</details>

**标签**: `#memory`, `#semiconductors`, `#supply chain`, `#SK Hynix`, `#hardware`

---

<a id="item-9"></a>
## [特朗普政府力推英特尔复兴：苹果将采用其芯片](https://www.wsj.com/tech/the-white-house-intel-trump-apple-84fe833e) ⭐️ 8.0/10

在特朗普政府施压下，苹果同意在部分产品中使用英特尔制造的芯片；美国政府将 90 亿美元联邦拨款转为英特尔 10%股份，成为其最大股东。 这标志着政府对半导体产业的重大干预，旨在复兴英特尔作为本土制造巨头，重塑全球芯片供应链。 美国政府还促成了英伟达、SpaceX 等公司与英特尔签约。英特尔 CEO 陈立武每月与商务部会面，政府芯片主管每季度听取 CFO 简报。自 2025 年 3 月以来，英特尔股价已翻三倍。

telegram · zaihuapd · 7月11日 05:54

**背景**: 英特尔一直在努力重获芯片制造领先地位，落后于台积电和三星。特朗普政府将本土芯片生产视为国家安全优先事项，因此直接介入公司战略。

**标签**: `#英特尔`, `#芯片制造`, `#政府政策`, `#半导体产业`, `#苹果`

---

<a id="item-10"></a>
## [U-Boot 发现 6 个漏洞，可在系统启动前执行恶意代码](https://www.bleepingcomputer.com/news/security/new-u-boot-flaws-could-enable-stealthy-firmware-attacks/) ⭐️ 8.0/10

固件安全公司 Binarly 披露了 U-Boot 引导程序 FIT 签名验证中的 6 个漏洞，其中 2 个可导致在操作系统启动前执行任意代码。 这些漏洞使攻击者能在操作系统和安全软件加载前执行恶意代码，可能导致持久的固件级攻击。由于 U-Boot 广泛用于嵌入式设备，影响十分严重。 这些漏洞影响自 2013.07 版本以来的 U-Boot，包括超过 50 个稳定版本及大量下游分支。两个漏洞可导致任意代码执行，四个可导致拒绝服务。补丁已提交并被接受，但需要设备制造商集成到固件更新中。

telegram · zaihuapd · 7月11日 08:32

**背景**: U-Boot（Das U-Boot）是嵌入式系统中广泛使用的开源引导加载程序，支持多种架构。它从各种存储介质加载操作系统，并在安全启动场景中使用数字签名验证 FIT（Flattened Image Tree）映像的完整性。这些漏洞存在于签名验证代码中，允许攻击者绕过认证并运行任意代码。BMC（基板管理控制器）系统尤其风险较高，因为它们通常支持远程固件更新，使得攻击者可以远程利用漏洞。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cybersecuritynews.com/u-boot-fit-signature-verification/">Six U - Boot FIT Signature Verification Flaws Enable Code Execution...</a></li>
<li><a href="https://overcentral.com/en/u-boot-vulnerabilities-firmware-attacks/">U - Boot Vulnerabilities Expose Devices to Firmware Attacks</a></li>
<li><a href="https://en.wikipedia.org/wiki/Das_U-Boot">Das U - Boot - Wikipedia</a></li>

</ul>
</details>

**标签**: `#security`, `#U-Boot`, `#bootloader`, `#firmware`, `#vulnerabilities`

---

<a id="item-11"></a>
## [SGLang v0.5.15 显著提升 LLM 服务性能](https://github.com/sgl-project/sglang/releases/tag/v0.5.15) ⭐️ 7.0/10

SGLang v0.5.15 引入了零开销的 Spec V2 调度、减少草稿步骤成本的 IndexShare MTP，并在 Blackwell 上针对 GLM-5.2 NVFP4 进行了生产调优，在 8 块 B300 上实现了每秒每用户超过 500 个 token 的性能。 这些优化显著提升了大语言模型服务的吞吐量和延迟，特别是在投机解码和长上下文场景中，有利于部署高性能 LLM 推理的开发者。 Spec V2 通过可 CUDA 图化的 DSA 草稿扩展和消除设备-主机同步实现零开销调度，端到端 TPS 提升 11%。IndexShare MTP 在草稿步骤间复用索引器 top-k，在长上下文下将草稿步骤成本降低最多 1.9 倍。

github · Fridge003 · 7月10日 22:58

**背景**: 投机解码使用较小的草稿模型生成候选 token，再由较大的主模型验证，从而在不损失质量的情况下加速推理。多 token 预测（MTP）同时预测多个未来 token。NVFP4 是 NVIDIA 的 4 位浮点精度格式，相比标准 FP4 提供更好的准确率。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/JongYeop/Mistral-7B-Instruct-v0.2-FP4-W4A4">JongYeop/Mistral-7B-Instruct-v0.2-FP4-W4A4 · Hugging Face</a></li>
<li><a href="https://www.eigent.ai/blog/glm-5-2">GLM-5.2: Zhipu AI's 1M- Token Open-Weight Coding Model</a></li>
<li><a href="https://github.com/hemingkx/SpeculativeDecodingPapers">GitHub - hemingkx/SpeculativeDecodingPapers: Must-read papers...</a></li>

</ul>
</details>

**标签**: `#sglang`, `#llm-serving`, `#performance-optimization`, `#release-notes`, `#speculative-decoding`

---

<a id="item-12"></a>
## [ClickHouse 将 PgBouncer 吞吐量提升 4 倍](https://clickhouse.com/blog/pgbouncer-clickhouse-managed-postgres) ⭐️ 7.0/10

ClickHouse 工程师利用 Linux SO_REUSEPORT 套接字选项和一种对等机制，将 PgBouncer 吞吐量提升了 4 倍。该对等机制可在进程间转发取消请求。 这一优化显著提升了 PostgreSQL 连接池的性能，使 PgBouncer 能更好地利用多核系统并处理更多并发连接。 SO_REUSEPORT 选项允许多个进程绑定到同一端口，而对等机制确保取消查询被转发到正确的进程。该工作由 ClickHouse 工程师为其托管 PostgreSQL 服务完成。

hackernews · saisrirampur · 7月11日 15:28 · [社区讨论](https://news.ycombinator.com/item?id=48872874)

**背景**: PgBouncer 是一个轻量级的 PostgreSQL 连接池，通常用于管理数据库连接。它通常是单线程的，限制了在多核系统上的吞吐量。SO_REUSEPORT 是 Linux 套接字选项（自内核 3.9 起），允许多个进程监听同一 TCP 端口，从而实现更好的跨核心负载分发。对等机制是一种协调进程的技术，确保取消请求到达正确的会话所有者。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.baeldung.com/linux/socket-options-difference">The Difference Between SO_REUSEADDR and... | Baeldung on Linux</a></li>
<li><a href="https://scalegrid.io/blog/postgresql-connection-pooling-part-2-pgbouncer/">PostgreSQL Connection Pooling: Part 2 – PgBouncer</a></li>

</ul>
</details>

**社区讨论**: 社区讨论中提到了 Odyssey 和 pgdog 等替代方案，并提出了关于对等机制的问题。一些用户指出在 Kubernetes 上运行多个 PgBouncer 进程很简单，还有评论者对 SO_REUSEPORT 表示感兴趣。

**标签**: `#pgbouncer`, `#postgresql`, `#connection pooling`, `#performance`, `#database`

---

<a id="item-13"></a>
## [在 SQLite 中推荐使用严格表](https://evanhahn.com/prefer-strict-tables-in-sqlite/) ⭐️ 7.0/10

这篇文章主张使用 SQLite 从 3.37.0 版本（2021-11-27）引入的 STRICT 表，以强制执行列类型安全，而不是依赖默认的灵活类型系统。 这一点很重要，因为 SQLite 默认的动态类型可能导致细微的错误和数据损坏，尤其是在多应用场景中，而 STRICT 表使其更接近传统 SQL 数据库的类型安全性。 STRICT 表需要为每个表单独启用，并且它们不允许某些数据类型（如 DATE），这是一个限制。它们还会拒绝类型不匹配的插入，例如将字符串插入 INTEGER 列。

hackernews · ingve · 7月11日 17:33 · [社区讨论](https://news.ycombinator.com/item?id=48873940)

**背景**: SQLite 传统上使用清单类型系统，其中列类型只是提示，任何值可以存储在任何列中。这与大多数强制严格类型的 SQL 数据库不同。STRICT 表于 2021 年添加，以解决这种差异，为开发者提供灵活性和类型安全之间的选择。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.sqlite.org/stricttables.html">STRICT Tables</a></li>
<li><a href="https://antonz.org/sqlite-strict-tables/">STRICT tables in SQLite</a></li>
<li><a href="https://www.sqlitetutorial.net/sqlite-strict-tables/">SQLite Strict Tables</a></li>

</ul>
</details>

**社区讨论**: 社区评论者大多同意 STRICT 应该成为默认设置，有人指出从企业 SQL 背景来看，SQLite 缺乏类型强制执行是一个缺点。其他人则指出权衡：缺少像 DATE 这样的类型，以及 SQLite 的主要用例是嵌入式单应用数据库，在这种场景下灵活性问题较小。

**标签**: `#SQLite`, `#databases`, `#type safety`, `#best practices`

---

<a id="item-14"></a>
## [中国初创鹰瞰智翼融资数千万，打造智能扑翼飞行机器人](https://36kr.com/p/3889516712065799?f=rss) ⭐️ 7.0/10

上海交通大学博士生陈昊创立的公司鹰瞰智翼在三个月内完成第三轮融资，融资金额数千万元，计划于 2025 年第三季度在 Kickstarter 上推出其消费级扑翼机器人 Eagle X。 这标志着具身智能在仿生飞行领域的重要进展，通过自研流体仿真引擎连接仿真与现实世界，可能开辟超越传统无人机的全新消费机器人市场。 该公司的第二款产业级机器人拥有约 15 个自由度，能够主动驾驭气流；其 Vortrix 流体仿真引擎使用强化学习在仿真中训练机器人，然后零样本迁移到现实。

rss · 36kr · 7月11日 01:00

**背景**: 扑翼飞行与旋翼无人机本质不同：它利用气流而非对抗气流。传统扑翼开发依赖缓慢的风洞测试，而鹰瞰智翼的方法使用自研流体仿真引擎 Vortrix 结合强化学习来加速训练。具身智能指能够与环境进行物理交互的人工智能系统，需要仿真到现实的迁移。

**社区讨论**: 此新闻没有提供社区评论。

**标签**: `#robotics`, `#embodied intelligence`, `#drones`, `#biomimetic flight`, `#startup`

---

<a id="item-15"></a>
## [智谱创始人启动'摸高计划'，聚焦 AGI](https://mp.weixin.qq.com/s/3CQSkf_kBnXiCDgS4L-Cgg) ⭐️ 7.0/10

智谱创始人唐杰宣布启动'摸高计划'，将通往 AGI 的路径概括为四座高峰：长程任务、自治智能体、完全自我训练和极致安全治理，并计划投入百亿级资源攻坚机械可解释性。 这一来自中国领先 AI 实验室的战略承诺，标志着向安全与可解释性研究的转变，可能影响全球 AGI 发展优先级和开源 AI 治理。 该计划强调极致安全治理，智谱将投入百亿级资源用于机械可解释性研究，以推动黑盒模型透明化。公司当前旗舰模型 GLM-5.2 据称接近海外最前沿模型水平，并以 MIT 许可证开源。

telegram · zaihuapd · 7月11日 13:59

**背景**: 机械可解释性是可解释 AI 的一个子领域，旨在通过逆向工程理解神经网络的内部算法和电路，类似于传统软件逆向工程。自治智能体是可以独立执行复杂任务的 AI 系统。智谱的 GLM 系列是中国领先的开源权重大型语言模型之一，使该公司跻身'中国 AI 六小虎'行列。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mechanistic_interpretability">Mechanistic interpretability</a></li>
<li><a href="https://en.wikipedia.org/wiki/GLM-5.2">GLM-5.2</a></li>

</ul>
</details>

**标签**: `#AGI`, `#Zhipu AI`, `#GLM-5.2`, `#AI safety`, `#open-source`

---