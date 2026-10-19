# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:30**

---

## 🔥 今日头条

**1️⃣ Meta 发布首个前沿模型系列 Muse Wonder，全球前沿竞赛进一步多极化。** 10月12日，Meta 超级智能实验室（Meta Superintelligence Labs，AI 负责人 Alexandr Wang）正式发布 Muse Wonder 与 Muse Wonder Full 两款模型（开发代号"Watermelon"），称其在个人与专业智能体（Agentic）任务、记忆与编程场景达到业界前沿水平。Meta 公布的基准显示其性能与 Anthropic 的 Claude Fable 5.1、OpenAI 的 GPT-6 Astra 相当；在 Artificial Analysis 智能指数 v4.3 中，Wonder Full 得分 56（标准版 52），仅次于 Claude Opus 5.5（58 分）、高于 OpenAI 与 Google 的最强模型（各 53 分）；中文媒体转述称其编程智能体表现与 Claude 并列第一。定价 $4/$20 每百万 token（输入/输出），与 Opus 5.5 同价位；已通过 Meta Model API 与 Muse Code 提供（Full 版限高级订阅，新增 Active Memory / Active Focus 能力）。发布当日 Meta 股价上涨约 3.4%–4.1%（约报 $748）。[来源：TechCrunch/WIRED/NYT/The Verge/新浪科技]

**2️⃣ 微软发布第三代自研 AI 芯片 Maia 300：从"最大押注"到百万颗级部署。** 10月12日于 OCP 全球峰会（圣何塞）亮相：288GB HBM4 显存、18TB/s 带宽；微软称其每兆瓦可产出比"领先 GPU 系统"多 40% 的 token，机架级吞吐为 Maia 200 的 7 倍。微软计划 2027 年起以"多吉瓦级"规模部署超 100 万颗 Maia 300，使其成为自家 AI 服务的主要推理硬件；公司预计今年资本开支超 1,750 亿美元。纳德拉称其为"对自研芯片的最大一笔押注"；当日微软股价涨约 2.4%，英伟达、AMD 承压。[来源：GeekWire/CNBC/Reuters/HPCwire]

---

## ☝ Headlines

- **Meta·Muse Wonder**：Meta 首个前沿模型发布，对标 Claude Opus 5.5/Fable 5.1 与 GPT-6 Astra，$4/$20 定价、发布日股价涨约 3-4%
- **微软·Maia 300**：第三代自研 AI 芯片亮相，2027 年部署超百万颗、能效 +40%/MW
- **亚马逊·Decart**：洽谈约 70 亿美元收购 AI 芯片软件公司 Decart（Anthropic 尽调后退出、亚马逊接手）
- **英国 AI 安全**：白宫解除 17 天冻结，UK AISI 恢复 OpenAI/Anthropic/DeepMind 预发布模型访问；同日英国公布 AI 风险防御包
- **DeepMind·AlphaProof Nexus**：解出 9 个 Erdős 开放数学问题（2 个悬置 56 年）+ 44 个数列猜想，并通过同行评审
- **中国 AI**：大模型周调用量 86.74 万亿 Token（环比 +50.96%）连续 24 周全球第一、前五全为中国模型；美国头部两家厂商则占近九成收入

---

## 📊 分类详报

### 🧠 模型与技术

- **Meta Muse Wonder 更多细节**：该系列由 Meta 超级智能实验室开发（2025 年 6 月招入 Scale AI 创始人 Alexandr Wang 后启动 AI 重构，历时约 14 个月），定位"面向个人与专业智能体任务的前沿模型"，较前代 Muse Spark 明显升级（Artificial Analysis 智能指数 48 → 52/56）。WIRED 评价其"让 Meta 重回 AI 前沿"。社区侧：开发者对比指出 Wonder 定价与 Opus 5.5 完全持平，但在 Meta 自家 14 项基准中有 9 项落后（dev.to 分析）；Full 版目前仅限 Meta 高级 AI 编码订阅用户。[来源：TechCrunch/WIRED/NYT/Artificial Analysis/dev.to]

- **Claude Opus 5.5 Max 首次登顶 Arena 智能体榜**：Anthropic 新模型首次入榜即夺得智能体榜第一，工具幻觉率仅 0.37%；综合榜由 Google gemini-4-argon-high 居首；国产模型 kimi-k3-max 稳居综合榜前 20，qwen3.8-max 等多款保持中上游。[来源：Arena AI 周榜（网易/搜狐转载）]

- **OpenRouter 周度调用数据（10月5日-11日）**：全球总调用量 172 万亿 Token（环比 +3.61%）；中国大模型 86.74 万亿（+50.96%），连续 24 周超过美国（18.97 万亿，+17.1%），约为其 4.6 倍；全球前五全为中国模型——DeepSeek V4.1 Flash（41 万亿、+60%）、智谱 GLM 5.3 Flash（12.2 万亿）、小米 MiMo-V2.6-Flash（11.5 万亿）、阶跃星辰 Step 5 Preview（8.84 万亿）、腾讯 Hy4 preview（8.28 万亿）；Claude Opus 5.5 居第八（5.02 万亿）。[来源：每日经济新闻/OpenRouter 测算]

### 📋 政策与监管

- **英国恢复前沿模型预发布访问权（10月12日）**：白宫逆转此前"企业须先获美国批准才能向英方共享模型"的政策，为期 17 天的冻结解除。英国 AI 部长 Kanishka Narayan 确认：UK AISI 将继续对 OpenAI、Anthropic、Google DeepMind 的最强模型进行发布前安全评估（正评估 Gemini 4 Argon 等系统）；其称目标是让英国"成为全球最难被 AI 攻击的国家之一"。[来源：Quartz/Bloomberg/Firstpost/TheNextWeb]

- **英国公布 AI 风险防御包（10月12日）**：追加系列国家级防御措施——延长"用前沿 AI 审计政府代码"试点（既有两轮试点已发现 1,000+ 潜在漏洞；其中已公布一轮以约 £13,000 的 token 成本发现 407 处弱点）；政府表示或立法保护关键基础设施免受 AI 网络威胁，并着手准备"自主系统脱离人类控制"类事件的应急机制（有专家呼吁"终止开关"）。[来源：Unite.AI/TheNextWeb/bankinfosecurity/resiliencemedia]

- **美国 CAISI 拟"并入"白宫**：路透报道，特朗普政府计划将商务部 AI 标准与创新中心（CAISI）的三名高级官员转入白宫编制、直接向白宫汇报（重组仍在敲定中）；CAISI 此前负责与 OpenAI、Google、微软等开展自愿性模型评估。[来源：Reuters/US News/cryptobriefing]

- **Brad Smith："牛奶受到的监管都比 AI 多"**：微软副董事长兼总裁 Brad Smith 呼吁建立全球统一的 AI 安全规则，包括独立评估机构与面向开发者的"紧急刹车"机制——并称当前 AI 的安全要求比一盒牛奶还少。[来源：Reuters/Fox Business]

- **比尔·盖茨警告（10月11-12日）**：在 CNN 采访中称 AI 是"人类发明过的最危险的技术"，最紧迫威胁是"未来一年内 AI 驱动的网络攻击"；强调不能让企业"自我监管"，并提到社会需讨论如何对 AI 与机器人的使用征税。[来源：CNN/Yahoo Finance]

- **中国：《关于发展新质生产力的意见》持续发酵**：中共中央、国务院 10 月 9 日印发该文件，明确"全面实施'人工智能+'行动"、加快推进 AI 手机/电脑等新一代智能终端应用，并建立技术监测、风险预警与应急响应体系、确保 AI"安全、可靠、可控"；本周进入配套落实期（如工信部"AI 应用服务商培育专项行动"）。[来源：国家发改委/财新/VOA]

- **布鲁金斯学会：AI 智能体（Agent）的全球治理**：发文探讨 AI 智能体跨境运行带来的治理缺口（责任归属、跨国部署合规）。[来源：Brookings]

### 💰 产业与商业

- **亚马逊洽购 Decart（约 70 亿美元）**：WSJ 首发（10月11日晚）——Decart 开发让 AI 模型跨不同芯片高效运行的软件，并研发"世界模型"（模拟 3D 环境）；公司 2023 年成立，今年 5 月估值近 40 亿美元（若按 70 亿成交，较该估值高出约 75%）。此前 Anthropic 8 月曾洽谈约 60 亿美元收购、9 月尽调后放弃；亚马逊为其战略客户并给予 Trainium 芯片早期访问。交易若落地将强化 AWS 自研芯片生态、进一步对冲英伟达依赖。[来源：WSJ/Bloomberg/Calcalist/Quartz]

- **微软 Maia 300 详细规格与部署计划**：288GB HBM4、18TB/s 带宽；每兆瓦 token 数 +40% vs 领先 GPU 系统、机架吞吐 7× vs Maia 200；2027 年"多吉瓦"部署、逾 100 万颗；年内资本开支预期超 1,750 亿美元。市场解读：微软推理算力从"英伟达为主"转向"自研为主"的转折点。[来源：The Verge/Notebookcheck/The Tech Portal/Reuters]

- **英伟达联合 AMD、Google、Meta 发布"开放数据中心规范 v0.7"**：在 OCP 全球峰会上联合发布统一 AI 工厂设施蓝图（覆盖电力架构、冷却、物理布局）；Google、Meta、微软、英伟达另发布"OCP 电网韧性规范"（应对公用事业扰动、快速恢复）；英伟达同时通过 MGX 1.2 开放 Vera Rubin NVL72 机架设计（支持 250kW 级机架），并宣布 ConnectX-10 / BlueField 支持 Google Falcon 传输协议（开放互联再进一步）。[来源：NVIDIA博客/StorageReview/Yahoo Finance]

- **Salesforce 收购以色列 AI 分析公司 Loops（约 3,000 万美元）**：并入 Tableau，主打"agentic analytics"（解释业务指标变动并给出行动建议）；预计 11 月初交割；消息后 CRM 涨约 3%。[来源：CTech/Globes/Proactive Investors]

- **中美 AI 商业化分化（分析）**：Menlo Ventures 数据显示，2025 年 OpenAI + Anthropic 合计占企业 LLM API 支出 67%；其 5 月报告显示两家在追踪的 34 家头部 AI 初创中占 89% 收入；Ramp 数据称首次采购 AI 的企业中 Anthropic 占逾 73% 支出。对照中国侧"调用量份额领先、收入份额有限"的结构——模型能力差距正快速转化为商业收入差距。[来源：新浪科技（投资者内参）]

### 🚀 应用与产品

- **Apple "Welcome Home" 发布会（今日 10月13日，9:00 ET 纽约）**：预计推出智能家居中枢（HomePad 类新品）、新一代 Apple TV 4K、HomePod mini 等；以"新闻稿 + 媒体体验"形式发布，AI 家庭中枢为核心看点。[来源：The Verge/9to5Mac/MacRumors]

- **阶跃星辰 STEPX Neo 智能体手机（今日上海发布）**：阶跃终端"Ready Builder One"发布会推出首款"大模型原生智能体手机"；同日，千问新一代 AI 眼镜现货发售；阶跃星辰将于 10月15日 正式开源 Step 5 Preview（该模型已上线腾讯 WorkBuddy）。[来源：智东西/华尔街见闻/东方财富/IT之家]

- **富士胶片 Synapse Pathology v3.0**（10月12日）：数字病理平台扩展 AI 能力。[来源：BioSpace]

### 🔬 研究前沿

- **DeepMind "AlphaProof Nexus" 解出 9 个 Erdős 开放问题（10月12日集中报道）**：从 353 个未解 Erdős 问题中解出 9 个（其中 2 个自 1970 年起悬置 56 年），另证明 44 个 OEIS 数列猜想；解法先行在线公开、成果通过同行评审——AI 数学推理从"竞赛题"走向真实开放问题的标志性一步。[来源：the-decoder/Reddit/The Daily Star]

- **TikTok CEO 周受资（Shou Zi Chew）：AI 将在 3 年内带来"重大科学突破"**（CNBC，10月12日）——认为 AI 对科学的推动（药物研发、材料等）将在三年内集中兑现。[来源：CNBC]

---

## ⚡ 明日关注

- **10月14日：Anthropic 上市前投资者日（Investor Day）**——已向机构投资者发出邀请（Bloomberg）；正式 IPO 营销或于 11月9日当周启动、目标感恩节前挂牌。市场关注其 ARR 指引与算力承诺兑现节奏（22V Research 视其为"市场内部结构与 AI 前景的重要节点"）。
- **10月15日：台积电 Q3 财报**（14:00 台北时间）——营收预计 NT$1.49 万亿（约 $467 亿、同比 +51%，创纪录）、净利润预计同比 +65%；AI 需求风向标；同周还有 ASML 财报。
- **10月15日：阶跃星辰正式开源 Step 5 Preview**（600B 稀疏 MoE，面向 Agentic 任务）。
- **10月13-16日：TechCrunch Disrupt 2026（旧金山）与 OCP 全球峰会持续**——更多 AI 基础设施/芯片发布与创业公司动向。
- **持续跟踪**：① 英伟达-Reflection AI 谈判进展；② Anthropic IPO 流程（投资者日 → 路演）；③ 英国 AI 立法动向（关键基础设施保护）。

---

## ⚡ 其他新闻

- 图书馆数字服务的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/CqG
- 亲子科普活动的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/308=lfv
- 社区体育组织的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/tdk=495
- 家庭用电安全的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%B8%B8%E6%88%8F?/iDg=j0a
- 数字学习资源的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/334
- 家庭节能实践的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/ejr
- 垃圾分类指导的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/DTS
- 基层健康档案的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/684=upe
- 社区志愿服务的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/pdw=626
- 公共服务数字化的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%AE%B6%E7%94%B5?/xc1=L4q
- 公交站点体验的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%BD%93%E8%82%B2?/834
- 科学教育活动的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%BD%93%E8%82%B2?/wxc
- 远程协作工具的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%BD%93%E8%82%B2?/MLm
- 跨代沟通活动的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%BD%93%E8%82%B2?/531=rjo
- 校园节能行动的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%BD%93%E8%82%B2?/prb=528
- 社区环保活动的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E4%BD%93%E8%82%B2?/5LS=YL4
- 网络信息辨识的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Elllv%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93?/288
- 个人时间管理的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Elllv%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93?/ssr
- 软件开发学习的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Elllv%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93?/nnZ
- 城市骑行环境的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Elllv%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93?/073=pdd
- 乡村生活观察的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Elllv%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93?/cas=364
- 户外活动组织的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Elllv%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93?/AIl=Idy
- 城市便民驿站的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%AE%98%E7%BD%91%E7%89%88_%E7%99%BE%E5%BA%A6%E5%A4%B4%E6%9D%A1?/566
- 社区家校合作的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%AE%98%E7%BD%91%E7%89%88_%E7%99%BE%E5%BA%A6%E5%A4%B4%E6%9D%A1?/vyd
- 数字课堂应用的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%AE%98%E7%BD%91%E7%89%88_%E7%99%BE%E5%BA%A6%E5%A4%B4%E6%9D%A1?/IwX
- 城市公共标识中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%AE%98%E7%BD%91%E7%89%88_%E7%99%BE%E5%BA%A6%E5%A4%B4%E6%9D%A1?/109=bae
- 社区绿色空间的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%AE%98%E7%BD%91%E7%89%88_%E7%99%BE%E5%BA%A6%E5%A4%B4%E6%9D%A1?/ujf=942
- 乡村公共文化的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%AE%98%E7%BD%91%E7%89%88_%E7%99%BE%E5%BA%A6%E5%A4%B4%E6%9D%A1?/4ZW=uSN
- 家庭照护支持的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_1%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/788
- 公共设施使用的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_1%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/oxm
- 城市树木认养的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_1%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/9S8
- 社区家政服务的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_1%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/677=ipy
- 乡村生活观察的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_1%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/fvz=123
- 城市基础设施的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_1%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%97%B6%E6%8A%A5?/BGh=kox
- 图书馆亲子空间的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/056
- 居民健康教育的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/fft
- 数据分析入门的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/Hoy
- 校园社团活动的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/673=glf
- 社区互助网络的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/zpi=928
- 小区公共照明的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/rAp=YYi
- 社区科普课堂的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_500app%E5%BD%A9%E7%A5%A8%E7%BD%91_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/294
- 城市空气科普的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_500app%E5%BD%A9%E7%A5%A8%E7%BD%91_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/xya
- 信息无障碍体验的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_500app%E5%BD%A9%E7%A5%A8%E7%BD%91_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/07A
- 智慧城市体验的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_500app%E5%BD%A9%E7%A5%A8%E7%BD%91_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/772=qzw
- 城乡交通衔接的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_500app%E5%BD%A9%E7%A5%A8%E7%BD%91_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/awa=498
- 数字课堂应用的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_500app%E5%BD%A9%E7%A5%A8%E7%BD%91_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/Ily=8T0
- 气象科普传播的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9Ewelcome_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/671
- 城市适老服务的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9Ewelcome_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/dxx
- 科学健身方法的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9Ewelcome_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/x3d
- 公共服务指南的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9Ewelcome_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/541=uss
- 老年友好服务的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9Ewelcome_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/deu=538
- 城市慢行系统的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%9Ewelcome_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/ABl=T81
- 家庭收纳实践的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%85%A8%E6%B0%91%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%AD%E8%89%BA?/702
- 软件开发学习中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%85%A8%E6%B0%91%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%AD%E8%89%BA?/hui
- 节日文化体验的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%85%A8%E6%B0%91%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%AD%E8%89%BA?/s0Q
- 休闲运动入门的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%85%A8%E6%B0%91%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%AD%E8%89%BA?/088=xhd
- 社区花园共建中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%85%A8%E6%B0%91%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%AD%E8%89%BA?/rka=101
- 乡村生活观察的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%85%A8%E6%B0%91%E4%B9%90app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%9B%AD%E8%89%BA?/MPj=cRl
- 公共服务预约的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A8%81%E5%B0%BC%E4%BA%BA%E6%96%AFapp%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/412
- 基层健康档案的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A8%81%E5%B0%BC%E4%BA%BA%E6%96%AFapp%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/rin
- 节能家电使用的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A8%81%E5%B0%BC%E4%BA%BA%E6%96%AFapp%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/iIJ
- 公园亲子设施的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A8%81%E5%B0%BC%E4%BA%BA%E6%96%AFapp%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/409=vjt
- 口袋公园建设的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A8%81%E5%B0%BC%E4%BA%BA%E6%96%AFapp%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/fka=119
- 数字政务体验的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A8%81%E5%B0%BC%E4%BA%BA%E6%96%AFapp%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B4%A2%E7%BB%8F?/kkv=hWy
- 儿童运动体验的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E6%97%BA%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83app%E5%AE%89%E5%8D%93%E7%89%88%E6%9C%80%E7%B2%BE%E5%87%86_%E5%A4%B4%E6%9D%A1%E5%BD%A9%E7%A5%A8?/646
- 绿色办公实践的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E6%97%BA%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83app%E5%AE%89%E5%8D%93%E7%89%88%E6%9C%80%E7%B2%BE%E5%87%86_%E5%A4%B4%E6%9D%A1%E5%BD%A9%E7%A5%A8?/weq
- 城市运动公园的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E6%97%BA%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83app%E5%AE%89%E5%8D%93%E7%89%88%E6%9C%80%E7%B2%BE%E5%87%86_%E5%A4%B4%E6%9D%A1%E5%BD%A9%E7%A5%A8?/2B6
- 气象科普传播的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E6%97%BA%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83app%E5%AE%89%E5%8D%93%E7%89%88%E6%9C%80%E7%B2%BE%E5%87%86_%E5%A4%B4%E6%9D%A1%E5%BD%A9%E7%A5%A8?/017=rfi
- 公共服务数字化的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E6%97%BA%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83app%E5%AE%89%E5%8D%93%E7%89%88%E6%9C%80%E7%B2%BE%E5%87%86_%E5%A4%B4%E6%9D%A1%E5%BD%A9%E7%A5%A8?/rik=980
- 儿童友好空间的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E6%97%BA%E5%BD%A9%E5%8F%8C%E8%89%B2%E7%90%83app%E5%AE%89%E5%8D%93%E7%89%88%E6%9C%80%E7%B2%BE%E5%87%86_%E5%A4%B4%E6%9D%A1%E5%BD%A9%E7%A5%A8?/fQf=PIg
- 科学运动指导的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91V8%E5%BD%A9%E7%A5%9E_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A5%A8?/083
- 青少年职业启蒙的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91V8%E5%BD%A9%E7%A5%9E_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A5%A8?/ewm
- 城市公共饮水的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91V8%E5%BD%A9%E7%A5%9E_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A5%A8?/yO2
- 绿色校园实践的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91V8%E5%BD%A9%E7%A5%9E_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A5%A8?/466=vco
- 生活服务数字化的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91V8%E5%BD%A9%E7%A5%9E_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A5%A8?/vxj=729
- 城市建设科普的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91V8%E5%BD%A9%E7%A5%9E_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A5%A8?/EUh=sWS
- 城市公共标识的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%93%AA%E9%87%8C%E6%9C%89_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/796
- 社区手工活动的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%93%AA%E9%87%8C%E6%9C%89_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/sgt
- 数据分析入门中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%93%AA%E9%87%8C%E6%9C%89_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/xn0
- 生活垃圾减量的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%93%AA%E9%87%8C%E6%9C%89_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/749=tdr
- 口袋公园建设从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%93%AA%E9%87%8C%E6%9C%89_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/pfl=015
- 城市博物馆服务的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%93%AA%E9%87%8C%E6%9C%89_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/kF2=Sut
- 居民健康教育的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/569
- 老年运动活动的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/eiq
- 零废弃生活尝试的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/sCi
- 青少年户外教育的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/712=xsu
- 城市应急广播的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/tpd=196
- 数字公共文化的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E9%A1%BA%E4%B8%B0%E8%A1%8C%E6%83%85?/AuO=CLz
- 文明养宠科普的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%A6%82%E4%BD%95%E7%94%B3%E8%AF%B7%E6%9C%80%E9%AB%98%E7%9A%84_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/011
- 乡村阅读活动的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%A6%82%E4%BD%95%E7%94%B3%E8%AF%B7%E6%9C%80%E9%AB%98%E7%9A%84_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/sla
- 农贸市场环境的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%A6%82%E4%BD%95%E7%94%B3%E8%AF%B7%E6%9C%80%E9%AB%98%E7%9A%84_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/Qbc
- 基层健康服务的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%A6%82%E4%BD%95%E7%94%B3%E8%AF%B7%E6%9C%80%E9%AB%98%E7%9A%84_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/092=mtm
- 科学信息获取的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%A6%82%E4%BD%95%E7%94%B3%E8%AF%B7%E6%9C%80%E9%AB%98%E7%9A%84_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/vsy=969
- 城市水环境观察的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%A6%82%E4%BD%95%E7%94%B3%E8%AF%B7%E6%9C%80%E9%AB%98%E7%9A%84_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/qRM=E9R
- 城市公共饮水的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%8E%BB%E5%93%AA%E8%A6%81_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/279
- 基层医疗预约的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%8E%BB%E5%93%AA%E8%A6%81_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/iuf
- 社区便民集市的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%8E%BB%E5%93%AA%E8%A6%81_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/zuZ
- 社区公共卫生中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%8E%BB%E5%93%AA%E8%A6%81_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/862=ooy
- 公共卫生设施的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%8E%BB%E5%93%AA%E8%A6%81_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/ven=632
- 社区停车服务的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E5%8E%BB%E5%93%AA%E8%A6%81_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/8cl=XhN
- 非遗体验活动中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%89%8D%E8%83%BD%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E5%B9%B6%E8%B4%AD?/020
- 绿色办公实践中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%89%8D%E8%83%BD%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E5%B9%B6%E8%B4%AD?/byf
- 社区活动策划的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%89%8D%E8%83%BD%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E5%B9%B6%E8%B4%AD?/eIg
- 城市慢行系统的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%89%8D%E8%83%BD%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E5%B9%B6%E8%B4%AD?/747=xrv
- 健康信息获取的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%89%8D%E8%83%BD%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E5%B9%B6%E8%B4%AD?/hml=509
- 社区健康讲座的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%89%8D%E8%83%BD%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E5%B9%B6%E8%B4%AD?/2mt=Ef6
- 传统手工艺体验的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%9C%80%E5%A5%BD_%E8%B0%B7%E6%AD%8C%E8%BF%B0%E8%AF%84?/131
- 城市步行友好的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%9C%80%E5%A5%BD_%E8%B0%B7%E6%AD%8C%E8%BF%B0%E8%AF%84?/zxh
- 公共空间照明的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%9C%80%E5%A5%BD_%E8%B0%B7%E6%AD%8C%E8%BF%B0%E8%AF%84?/RUw
- 城市步行环境的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%9C%80%E5%A5%BD_%E8%B0%B7%E6%AD%8C%E8%BF%B0%E8%AF%84?/023=ihi
- 乡村休闲旅游的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%9C%80%E5%A5%BD_%E8%B0%B7%E6%AD%8C%E8%BF%B0%E8%AF%84?/ayh=592
- 数字便民地图的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E9%82%80%E8%AF%B7%E7%A0%81%E6%9C%80%E9%AB%98%E6%9C%80%E5%A5%BD_%E8%B0%B7%E6%AD%8C%E8%BF%B0%E8%AF%84?/Ppf=X9y
- 节假日出行安排的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/029
- 街道综合服务的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/ftu
- 城市博物馆服务的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/H92
- 城市游园体验的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/203=abr
- 社区协商议事的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/lcr=051
- 绿色校园实践的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/XMw=JlV
- 社区学习活动的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E6%89%BE%E8%B0%81%E9%A2%86%E5%8F%96_%E5%BE%97%E7%89%A9%E7%88%86%E6%96%99?/478
- 亲子阅读活动的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E6%89%BE%E8%B0%81%E9%A2%86%E5%8F%96_%E5%BE%97%E7%89%A9%E7%88%86%E6%96%99?/nsd
- 健康信息获取的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E6%89%BE%E8%B0%81%E9%A2%86%E5%8F%96_%E5%BE%97%E7%89%A9%E7%88%86%E6%96%99?/Ewe
- 科学信息获取的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E6%89%BE%E8%B0%81%E9%A2%86%E5%8F%96_%E5%BE%97%E7%89%A9%E7%88%86%E6%96%99?/264=fnc
- 家庭理财科普的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E6%89%BE%E8%B0%81%E9%A2%86%E5%8F%96_%E5%BE%97%E7%89%A9%E7%88%86%E6%96%99?/xhn=627
- 低碳社区实践的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E6%89%BE%E8%B0%81%E9%A2%86%E5%8F%96_%E5%BE%97%E7%89%A9%E7%88%86%E6%96%99?/Oyy=eKW
- 职业技能学习的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E5%9C%88%E5%AD%90?/102
- 青少年职业启蒙的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E5%9C%88%E5%AD%90?/bgt
- 生成式工具使用从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E5%9C%88%E5%AD%90?/Fzi
- 街区更新实践的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E5%9C%88%E5%AD%90?/031=obk
- 公共卫生设施的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E5%9C%88%E5%AD%90?/vlh=615
- 街头绿植养护从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B4%A2%E7%BB%8F%E5%9C%88%E5%AD%90?/6UQ=WBm
- 城乡公共服务的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E8%84%89%E8%84%89%E7%A4%BE%E5%8C%BA?/505
- 社区知识分享的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E8%84%89%E8%84%89%E7%A4%BE%E5%8C%BA?/off
- 城市绿道建设有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E8%84%89%E8%84%89%E7%A4%BE%E5%8C%BA?/zL6
- 社区垃圾回收的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E8%84%89%E8%84%89%E7%A4%BE%E5%8C%BA?/928=bbz
- 社区手工活动的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E8%84%89%E8%84%89%E7%A4%BE%E5%8C%BA?/nfi=494
- 城市可持续生活的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%85%A8%E7%BD%91%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E8%84%89%E8%84%89%E7%A4%BE%E5%8C%BA?/EvN=bgh
- 基层服务创新的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%8E%A2%E6%BA%90?/042
- 图书借阅体验的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%8E%A2%E6%BA%90?/jcy
- 智能手机助老的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%8E%A2%E6%BA%90?/Fnv
- 家庭健康科普的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%8E%A2%E6%BA%90?/046=vas
- 绿色校园实践中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%8E%A2%E6%BA%90?/yon=891
- 儿童户外活动中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%8E%A2%E6%BA%90?/TXL=WEx
- 老年友好服务的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B0%B7%E6%AD%8C%E6%97%B6%E5%B0%9A?/392
- 居民健康教育的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B0%B7%E6%AD%8C%E6%97%B6%E5%B0%9A?/vog
- 城市游园体验的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B0%B7%E6%AD%8C%E6%97%B6%E5%B0%9A?/r73
- 城市文化路线的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B0%B7%E6%AD%8C%E6%97%B6%E5%B0%9A?/150=cgd
- 公共服务指南的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B0%B7%E6%AD%8C%E6%97%B6%E5%B0%9A?/evn=386
- 城市地名文化的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81%E6%98%AF%E5%A4%9A%E5%B0%91_%E8%B0%B7%E6%AD%8C%E6%97%B6%E5%B0%9A?/QgB=Ogp
- 文化场馆预约的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_500%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%AE%B6%E5%B1%85?/089
- 公共交通信息服务从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_500%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%AE%B6%E5%B1%85?/hgn
- 城市生活服务的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_500%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%AE%B6%E5%B1%85?/YEn
- 家庭节能实践的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_500%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%AE%B6%E5%B1%85?/865=qpt
- 家庭科学教育的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_500%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%AE%B6%E5%B1%85?/keo=460
- 节气饮食文化的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_500%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E5%AE%B6%E5%B1%85?/T6R=7a6
- 软件开发学习的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/602
- 科学教育活动的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/icd
- 社区手工活动的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/v2b
- 儿童友好空间的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/272=pgh
- 青年职业探索的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/npc=158
- 社区心理支持中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E6%AD%A3%E8%A7%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/D18=E0N
- 乡村生态旅游的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E6%8A%95%E5%BD%A9%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/757
- 公共设施维护有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E6%8A%95%E5%BD%A9%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/jvl
- 新能源出行的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E6%8A%95%E5%BD%A9%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/zqC
- 邻里共享空间的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E6%8A%95%E5%BD%A9%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/798=ugh
- 社区文化节活动的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E6%8A%95%E5%BD%A9%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/qsq=355
- 城市生活记录的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E6%8A%95%E5%BD%A9%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F?/cb8=MGi
- 城市文明出行的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91vll_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/698
- 绿色生活实践的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91vll_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/yat
- 农产品消费体验的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91vll_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/OZJ
- 个人信息保护从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91vll_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/302=rxs
- 市民意见收集的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91vll_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/jaa=751
- 公共服务沟通的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91vll_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/Zlm=ayu
- 社区活动空间的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91welcome%E7%9A%84%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/396
- 城市水环境观察的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91welcome%E7%9A%84%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/zqa
- 城市休闲步道的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91welcome%E7%9A%84%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/foj
- 图书馆亲子空间的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91welcome%E7%9A%84%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/949=mez
- 学校体育活动的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91welcome%E7%9A%84%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/hcu=127
- 乡村电商实践的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E4%B9%90%E5%8F%91welcome%E7%9A%84%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/5nh=bBm
- 信息无障碍体验的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%B1%86%E7%93%A3%E7%BE%8E%E9%A3%9F?/265
- 社区绿色空间的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%B1%86%E7%93%A3%E7%BE%8E%E9%A3%9F?/crm
- 儿童安全出行的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%B1%86%E7%93%A3%E7%BE%8E%E9%A3%9F?/VGE
- 物业服务沟通的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%B1%86%E7%93%A3%E7%BE%8E%E9%A3%9F?/105=uca
- 开源技术交流的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%B1%86%E7%93%A3%E7%BE%8E%E9%A3%9F?/axm=934
- 青年志愿活动的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91lv%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%B1%86%E7%93%A3%E7%BE%8E%E9%A3%9F?/AYG=36A
- 公共服务指南的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91lll_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/367
- 城乡公共服务的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91lll_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/qzx
- 社区慢性病防控的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91lll_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/7jg
- 社区便利生活的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91lll_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/121=kfr
- 乡村文化空间的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91lll_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/sva=661
- 地方美食文化的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91lll_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/IdR=Z1d
- 公共空间休憩的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91%E2%85%A1%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/989
- 城市空气科普的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91%E2%85%A1%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/muh
- 家庭教育交流中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91%E2%85%A1%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/yoj
- 乡村阅读活动的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91%E2%85%A1%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/027=ofm
- 社区家校合作的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91%E2%85%A1%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/ctb=677
- 社区体育组织的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E4%B9%90%E5%8F%91%E2%85%A1%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%A8%B1%E4%B9%90?/k7A=jrm
- 环境教育课程的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91IV%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A99123_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/738
- 农业科普体验有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91IV%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A99123_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/kqy
- 周末休闲规划中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91IV%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A99123_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/Goa
- 个人信息保护的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91IV%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A99123_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/570=muf
- 城乡公共服务的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91IV%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A99123_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/aju=517
- 智慧停车服务的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E4%B9%90%E5%8F%91IV%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A99123_%E5%A4%B4%E6%9D%A1%E8%A7%82%E7%82%B9?/CyP=NG0
- 绿色办公实践的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/524
- 社区慢性病防控的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/ddx
- 便民服务窗口的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/xCA
- 城市水环境观察的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/905=gos
- 物业服务沟通的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/iuj=295
- 街头绿植养护的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%85%A8%E6%B0%91%E4%B9%90%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%80%89%E8%B4%A2%E7%BB%8F?/MLC=n1Y
- 儿童运动体验的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BF%AB%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/171
- 老年人日常照护的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BF%AB%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/rwq
- 数字便民地图的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BF%AB%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/O4A
- 家庭防灾准备的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BF%AB%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/683=lcw
- 远程协作工具的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BF%AB%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/kop=812
- 城市展览体验的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%BF%AB%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/Nqt=40a
- 创业经验分享的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%AF%E7%90%83%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E7%AC%AC%E4%B8%80%E5%93%81%E7%89%8C_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/227
- 在线学习体验的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%AF%E7%90%83%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E7%AC%AC%E4%B8%80%E5%93%81%E7%89%8C_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/ano
- 机器人科普活动的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%AF%E7%90%83%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E7%AC%AC%E4%B8%80%E5%93%81%E7%89%8C_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/HbQ
- 社区修缮行动的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%AF%E7%90%83%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E7%AC%AC%E4%B8%80%E5%93%81%E7%89%8C_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/393=bvi
- 医院导诊服务的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%AF%E7%90%83%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E7%AC%AC%E4%B8%80%E5%93%81%E7%89%8C_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/agk=069
- 科学睡眠习惯的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%8E%AF%E7%90%83%E5%9C%A8%E7%BA%BF%E5%A8%B1%E4%B9%90%E7%AC%AC%E4%B8%80%E5%93%81%E7%89%8C_%E6%90%9C%E7%8B%90%E8%A7%86%E9%A2%91?/8ev=pkh
- 乡村阅读空间的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/425
- 公园亲子设施的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/fxx
- 公共健身器材的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/cTH
- 智能手机助老的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/818=asu
- 传统节日科普的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/hus=216
- 城市人文观察的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/wyN=seV
- 社区老年食堂的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E5%8F%AF%E4%BB%A5%E7%94%A8%E5%90%97_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/037
- 科普展览体验的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E5%8F%AF%E4%BB%A5%E7%94%A8%E5%90%97_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/buk
- 城市便民驿站的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E5%8F%AF%E4%BB%A5%E7%94%A8%E5%90%97_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/MR9
- 数字档案服务的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E5%8F%AF%E4%BB%A5%E7%94%A8%E5%90%97_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/001=kts
- 社区设施共享的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E5%8F%AF%E4%BB%A5%E7%94%A8%E5%90%97_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/aaq=205
- 城市农夫市集的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E5%8F%AF%E4%BB%A5%E7%94%A8%E5%90%97_%E8%8A%92%E6%9E%9C%E6%B8%B8%E6%88%8F?/2Cy=9m2
- 城市博物馆服务的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/245
- 数据分析入门的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/wvo
- 家庭收纳实践的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/Vyt
- 社区慢性病防控中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/884=ykp
- 社区手工活动的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/giy=976
- 城市步行友好的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E7%9F%A5%E4%B9%8E%E5%9B%BD%E9%99%85?/RNa=iD1
- 城市微更新实践的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/540
- 老年人出行服务的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/fdn
- 校园社团活动的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/U8P
- 家庭环保习惯的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/274=hzm
- 劳动教育实践的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/moa=973
- 数字阅读服务的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%8D%B3%E5%88%BB%E7%99%BE%E7%A7%91?/C6y=KWE
- 社区活动策划的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/855
- 公交无障碍服务的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/yye
- 社区快递服务的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/7BX
- 青少年职业启蒙的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/047=fch
- 城市公共厕所的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/wbq=628
- 城市游园体验的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%97%A7%E7%89%88app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/FEh=6Ze

---

## 📈 关键数据（10月11-13日）

| 指标 | 数值 | 变化/说明 |
|------|------|------|
| 全球大模型周调用量（10/5-11） | 172 万亿 Token | 环比 +3.61%（OpenRouter 测算） |
| 中国大模型周调用量 | 86.74 万亿 Token | 环比 +50.96%；连续 24 周全球第一 |
| 美国大模型周调用量 | 18.97 万亿 Token | 环比 +17.1% |
| Meta Muse Wonder 定价 | $4 / $20（每百万 Token 入/出） | 与 Claude Opus 5.5 同价位 |
| Meta / 微软股价（10/12） | Meta 约 $748（+3.4%–4.1%）；MSFT +2.4% | 模型与自研芯片发布驱动 |
| 微软 Maia 300 | 288GB HBM4；18TB/s；+40% tokens/MW | 2027 年部署超 100 万颗；资本开支预期 >$1750 亿（今年） |
| 亚马逊洽购 Decart | 约 $70 亿 | 较 5 月估值（近 $40 亿）高约 75% |
| AlphaProof Nexus 成果 | 9 个 Erdős 问题 + 44 个数列猜想 | 其中 2 题悬置 56 年；已通过同行评审 |
| 英国网络防御试点 | 累计发现 1,000+ 潜在漏洞 | 单轮试点：407 处弱点/£13,000 token 成本 |

---

*本简报由 Hermes Agent 自动生成*  
*数据来源：Google News、Reuters、Bloomberg、TechCrunch、The Verge、WIRED、NYT、CNBC、GeekWire、每日经济新闻、财联社、智东西、华尔街见闻、the-decoder  @PHWT7等*  
*仅供参考，不构成投资建议*
