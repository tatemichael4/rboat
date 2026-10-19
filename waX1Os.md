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

- 乡村教育资源的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E7%9A%84%E5%BE%AE%E4%BF%A1_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%91%8A?/651
- 健康步道使用的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E7%9A%84%E5%BE%AE%E4%BF%A1_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%91%8A?/pbc
- 城市农夫市集的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E7%9A%84%E5%BE%AE%E4%BF%A1_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%91%8A?/ufu
- 终身学习资源从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E7%9A%84%E5%BE%AE%E4%BF%A1_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%91%8A?/533=wam
- 城乡交流活动的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E7%9A%84%E5%BE%AE%E4%BF%A1_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%91%8A?/aru=169
- 小区停车协商有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E7%9A%84%E5%BE%AE%E4%BF%A1_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%91%8A?/W1v=emq
- 青年志愿活动的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E6%9C%80%E7%A8%B3%E5%A5%BD%E7%A4%BC%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/383
- 日常摄影记录的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E6%9C%80%E7%A8%B3%E5%A5%BD%E7%A4%BC%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/ene
- 社区便民集市的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E6%9C%80%E7%A8%B3%E5%A5%BD%E7%A4%BC%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/Tgz
- 青年就业服务的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E6%9C%80%E7%A8%B3%E5%A5%BD%E7%A4%BC%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/459=vkf
- 家庭消费规划的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E6%9C%80%E7%A8%B3%E5%A5%BD%E7%A4%BC%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/qhv=585
- 运动安全知识的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E6%9C%80%E7%A8%B3%E5%A5%BD%E7%A4%BC%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E8%A7%A3%E5%AF%86?/6aX=qPY
- 公共空间导览的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E8%8A%92%E6%9E%9C%E7%9B%98%E7%82%B9?/035
- 街道综合服务的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E8%8A%92%E6%9E%9C%E7%9B%98%E7%82%B9?/jzy
- 邻里互助活动的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E8%8A%92%E6%9E%9C%E7%9B%98%E7%82%B9?/bHj
- 公共卫生宣传的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E8%8A%92%E6%9E%9C%E7%9B%98%E7%82%B9?/215=rfm
- 城市公共座椅的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E8%8A%92%E6%9E%9C%E7%9B%98%E7%82%B9?/fyw=441
- 城市共享单车的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92%E4%B8%8A%E5%B2%B8_%E8%8A%92%E6%9E%9C%E7%9B%98%E7%82%B9?/Lk5=bsX
- 校园社团活动的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E4%BD%B3%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/653
- 公交无障碍服务的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E4%BD%B3%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/hpg
- 开源技术交流的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E4%BD%B3%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/q2I
- 社区休闲设施的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E4%BD%B3%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/048=jds
- 公共服务预约的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E4%BD%B3%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/sty=186
- 社区家校合作的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E4%BD%B3%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%94%BE?/NVi=k2g
- 城市文化路线的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/436
- 基层健康档案中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/rfy
- 社区宣传栏更新中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/Ib1
- 环境监测科普的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/285=kge
- 青年职业探索的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/pcf=864
- 农产品消费体验的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E4%B8%AD_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/UF0=cxN
- 数字阅读服务的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E6%94%BB%E7%95%A5_360%E7%A4%BE%E5%8C%BA?/875
- 社区庭院绿化的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E6%94%BB%E7%95%A5_360%E7%A4%BE%E5%8C%BA?/fgn
- 老年数字阅读的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E6%94%BB%E7%95%A5_360%E7%A4%BE%E5%8C%BA?/eKV
- 家庭健康科普的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E6%94%BB%E7%95%A5_360%E7%A4%BE%E5%8C%BA?/523=ktg
- 传统节日科普的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E6%94%BB%E7%95%A5_360%E7%A4%BE%E5%8C%BA?/svf=505
- 公共设施维护的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%80%9F%E5%9B%9E%E8%A1%80%E6%94%BB%E7%95%A5_360%E7%A4%BE%E5%8C%BA?/R32=oKJ
- 绿色校园实践的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/771
- 节能生活方式的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/oyo
- 城市文明出行的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/jd0
- 机器学习入门的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/185=jbu
- 线上办事服务的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/ald=441
- 远程协作工具的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/BtT=tlD
- 家庭阅读计划的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E5%A5%BD%E5%A4%9A%E6%B1%82%E7%BB%8F%E9%AA%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%99%8E%E5%97%85%E8%AF%BB%E4%B9%A6?/082
- 社区家校合作的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E5%A5%BD%E5%A4%9A%E6%B1%82%E7%BB%8F%E9%AA%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%99%8E%E5%97%85%E8%AF%BB%E4%B9%A6?/tbk
- 社区防暑服务的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E5%A5%BD%E5%A4%9A%E6%B1%82%E7%BB%8F%E9%AA%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%99%8E%E5%97%85%E8%AF%BB%E4%B9%A6?/YOw
- 邻里共享空间的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E5%A5%BD%E5%A4%9A%E6%B1%82%E7%BB%8F%E9%AA%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%99%8E%E5%97%85%E8%AF%BB%E4%B9%A6?/186=suy
- 儿童户外活动的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E5%A5%BD%E5%A4%9A%E6%B1%82%E7%BB%8F%E9%AA%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%99%8E%E5%97%85%E8%AF%BB%E4%B9%A6?/quu=665
- 个人时间管理的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%BE%93%E4%BA%86%E5%A5%BD%E5%A4%9A%E6%B1%82%E7%BB%8F%E9%AA%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8_%E8%99%8E%E5%97%85%E8%AF%BB%E4%B9%A6?/pIz=euY
- 城市文明出行的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%85%A5%E5%9B%9E%E8%A1%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/637
- 城市应急广播的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%85%A5%E5%9B%9E%E8%A1%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/jlx
- 节日文化体验的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%85%A5%E5%9B%9E%E8%A1%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/O5O
- 社区协商议事的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%85%A5%E5%9B%9E%E8%A1%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/117=kdo
- 城市博物馆活动的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%85%A5%E5%9B%9E%E8%A1%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/aza=477
- 健康步道使用的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%B8%A6%E5%85%A5%E5%9B%9E%E8%A1%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/dXr=eNv
- 数字资源检索的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%BE_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/560
- 儿童阅读角的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%BE_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/khe
- 城市骑行环境的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%BE_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/wPh
- 社区艺术活动的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%BE_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/280=pdv
- 社区环保活动的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%BE_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/pvy=003
- 无障碍信息设计的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99%E6%80%8E%E4%B9%88%E6%89%BE_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/rEn=RzW
- 电子商务服务的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/521
- 应急物资管理的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/qdh
- 乡村阅读活动的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/hdx
- 公共服务咨询的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/132=zzf
- 线上办事服务的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/gsk=587
- 低碳社区实践的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/wMV=LSA
- 老旧小区改造的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/391
- 新能源出行的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/irc
- 乡村休闲旅游从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/vX4
- 数字艺术创作的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/339=fiv
- 基层健康服务的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/ozp=435
- 文化遗产保护科普中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/A56=8k7
- 社区商业活力的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E8%80%81%E7%9A%84%E5%AE%89%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/584
- 公共空间照明的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E8%80%81%E7%9A%84%E5%AE%89%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/nap
- 非遗体验活动的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E8%80%81%E7%9A%84%E5%AE%89%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/8E4
- 公共服务数字化从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E8%80%81%E7%9A%84%E5%AE%89%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/422=ehc
- 城市公共标识从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E8%80%81%E7%9A%84%E5%AE%89%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/eue=328
- 科普展览体验的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E8%80%81%E7%9A%84%E5%AE%89%E5%85%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%A1%A3%E6%A1%88?/EAq=VVJ
- 户外活动组织中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/897
- 社区健康讲座的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/vey
- 基层服务创新的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/S9U
- 社区商业活力的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/778=vlc
- 学校体育活动的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/gzy=197
- 乡村文化活动的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E8%AE%AF?/aM2=ErP
- 数字档案服务的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%AE%98%E6%96%B9%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7%E6%80%BB%E4%BB%A3%E7%90%86_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/651
- 地方民俗记录的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%AE%98%E6%96%B9%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7%E6%80%BB%E4%BB%A3%E7%90%86_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/bsr
- 城市便民驿站的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%AE%98%E6%96%B9%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7%E6%80%BB%E4%BB%A3%E7%90%86_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/pKI
- 乡村生活观察的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%AE%98%E6%96%B9%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7%E6%80%BB%E4%BB%A3%E7%90%86_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/798=pmy
- 绿色建筑理念的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%AE%98%E6%96%B9%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7%E6%80%BB%E4%BB%A3%E7%90%86_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/vyf=511
- 老年人出行服务的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%AE%98%E6%96%B9%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7%E6%80%BB%E4%BB%A3%E7%90%86_%E8%B1%86%E7%93%A3%E8%B5%84%E8%AE%AF?/9jt=p8s
- 数字学习资源从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81_%E8%99%8E%E6%89%91%E9%A3%9F%E5%93%81?/126
- 地方戏曲体验的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81_%E8%99%8E%E6%89%91%E9%A3%9F%E5%93%81?/aap
- 公共服务数字化的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81_%E8%99%8E%E6%89%91%E9%A3%9F%E5%93%81?/HGT
- 乡村公共阅读的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81_%E8%99%8E%E6%89%91%E9%A3%9F%E5%93%81?/060=edm
- 垃圾分类指导的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81_%E8%99%8E%E6%89%91%E9%A3%9F%E5%93%81?/jvc=857
- 城市树木认养的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E9%82%80%E8%AF%B7%E7%A0%81_%E8%99%8E%E6%89%91%E9%A3%9F%E5%93%81?/U2H=RWm
- 青少年职业启蒙的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%BB%A3%E7%90%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BF%9D%E6%B3%95%E5%90%97_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/676
- 青少年户外教育的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%BB%A3%E7%90%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BF%9D%E6%B3%95%E5%90%97_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/kae
- 社区宠物管理的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%BB%A3%E7%90%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BF%9D%E6%B3%95%E5%90%97_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/HVD
- 青少年职业启蒙的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%BB%A3%E7%90%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BF%9D%E6%B3%95%E5%90%97_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/896=faq
- 城市公共座椅的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%BB%A3%E7%90%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BF%9D%E6%B3%95%E5%90%97_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/tkf=609
- 旧物循环利用的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E4%BB%A3%E7%90%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BF%9D%E6%B3%95%E5%90%97_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/rzP=17s
- 社区绿色空间的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%82%B9%E5%83%8F%E5%93%AA%E4%B8%AA%E9%83%A8%E9%97%A8%E7%94%B3%E8%AF%B7_%E7%BD%91%E6%98%93%E5%85%AC%E7%9B%8A?/033
- 城市博物馆服务的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%82%B9%E5%83%8F%E5%93%AA%E4%B8%AA%E9%83%A8%E9%97%A8%E7%94%B3%E8%AF%B7_%E7%BD%91%E6%98%93%E5%85%AC%E7%9B%8A?/mev
- 儿童运动体验的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%82%B9%E5%83%8F%E5%93%AA%E4%B8%AA%E9%83%A8%E9%97%A8%E7%94%B3%E8%AF%B7_%E7%BD%91%E6%98%93%E5%85%AC%E7%9B%8A?/cej
- 便民服务窗口的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%82%B9%E5%83%8F%E5%93%AA%E4%B8%AA%E9%83%A8%E9%97%A8%E7%94%B3%E8%AF%B7_%E7%BD%91%E6%98%93%E5%85%AC%E7%9B%8A?/478=cwv
- 街区绿化养护的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%82%B9%E5%83%8F%E5%93%AA%E4%B8%AA%E9%83%A8%E9%97%A8%E7%94%B3%E8%AF%B7_%E7%BD%91%E6%98%93%E5%85%AC%E7%9B%8A?/pai=462
- 休闲运动入门的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%82%B9%E5%83%8F%E5%93%AA%E4%B8%AA%E9%83%A8%E9%97%A8%E7%94%B3%E8%AF%B7_%E7%BD%91%E6%98%93%E5%85%AC%E7%9B%8A?/IqT=EuN
- 小区公共照明的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8C%A3%E9%92%B1_%E9%9B%85%E8%99%8E%E8%AF%BB%E5%9B%BE?/647
- 人工智能科普的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8C%A3%E9%92%B1_%E9%9B%85%E8%99%8E%E8%AF%BB%E5%9B%BE?/ahj
- 家庭健康科普的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8C%A3%E9%92%B1_%E9%9B%85%E8%99%8E%E8%AF%BB%E5%9B%BE?/y9g
- 学校食育活动的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8C%A3%E9%92%B1_%E9%9B%85%E8%99%8E%E8%AF%BB%E5%9B%BE?/429=cth
- 邻里互助活动的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8C%A3%E9%92%B1_%E9%9B%85%E8%99%8E%E8%AF%BB%E5%9B%BE?/bzi=071
- 老年运动活动的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8C%A3%E9%92%B1_%E9%9B%85%E8%99%8E%E8%AF%BB%E5%9B%BE?/Iy1=l6q
- 儿童安全出行的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/991
- 家庭理财科普的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/bat
- 社区垃圾回收的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/lFY
- 公共卫生设施的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/797=wox
- 城市公共座椅的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/egp=311
- 科技馆参观体验的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/0o4=1wU
- 青少年户外教育的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%80%8E%E4%B9%88%E5%8A%A0%E7%9B%9F%E4%BB%A3%E7%90%86_%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/433
- 图书借阅体验的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%80%8E%E4%B9%88%E5%8A%A0%E7%9B%9F%E4%BB%A3%E7%90%86_%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/nwi
- 节气饮食文化的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%80%8E%E4%B9%88%E5%8A%A0%E7%9B%9F%E4%BB%A3%E7%90%86_%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/jYS
- 公共场馆服务的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%80%8E%E4%B9%88%E5%8A%A0%E7%9B%9F%E4%BB%A3%E7%90%86_%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/696=ekc
- 终身学习资源的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%80%8E%E4%B9%88%E5%8A%A0%E7%9B%9F%E4%BB%A3%E7%90%86_%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/rav=989
- 市民意见收集的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BC%80%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%80%8E%E4%B9%88%E5%8A%A0%E7%9B%9F%E4%BB%A3%E7%90%86_%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/An8=CMq
- 城市展览体验的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%9C%89%E5%A4%9A%E5%A4%A7%E5%88%A9%E6%B6%A6_%E8%85%BE%E8%AE%AF%E6%8E%A2%E6%BA%90?/333
- 光伏知识科普的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%9C%89%E5%A4%9A%E5%A4%A7%E5%88%A9%E6%B6%A6_%E8%85%BE%E8%AE%AF%E6%8E%A2%E6%BA%90?/cjp
- 城市宠物友好空间的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%9C%89%E5%A4%9A%E5%A4%A7%E5%88%A9%E6%B6%A6_%E8%85%BE%E8%AE%AF%E6%8E%A2%E6%BA%90?/kO2
- 城市慢跑路线的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%9C%89%E5%A4%9A%E5%A4%A7%E5%88%A9%E6%B6%A6_%E8%85%BE%E8%AE%AF%E6%8E%A2%E6%BA%90?/414=lls
- 健康步道使用的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%9C%89%E5%A4%9A%E5%A4%A7%E5%88%A9%E6%B6%A6_%E8%85%BE%E8%AE%AF%E6%8E%A2%E6%BA%90?/rwz=327
- 数字课堂应用的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%9C%89%E5%A4%9A%E5%A4%A7%E5%88%A9%E6%B6%A6_%E8%85%BE%E8%AE%AF%E6%8E%A2%E6%BA%90?/KUq=Qf0
- 地方美食文化的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E6%80%8E%E4%B9%88%E5%81%9A%E9%BB%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/326
- 公共服务数字化的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E6%80%8E%E4%B9%88%E5%81%9A%E9%BB%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/vde
- 乡村电商实践的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E6%80%8E%E4%B9%88%E5%81%9A%E9%BB%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/Mh9
- 本地消费场景的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E6%80%8E%E4%B9%88%E5%81%9A%E9%BB%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/545=lkt
- 地方戏曲体验的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E6%80%8E%E4%B9%88%E5%81%9A%E9%BB%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/uje=155
- 城市人文观察的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E6%80%8E%E4%B9%88%E5%81%9A%E9%BB%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86_%E5%BE%97%E7%89%A9%E4%BA%B2%E5%AD%90?/aLF=43v
- 个人信息保护的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/967
- 公园无障碍服务的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/tzg
- 城市人文观察的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/EXR
- 社区便利生活的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/620=yal
- 社区商业活力的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/qys=880
- 城市可持续生活的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%BB%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E7%94%B3%E8%AF%B7_%E6%BE%8E%E6%B9%83%E8%B5%84%E8%AE%AF?/YY5=064
- 城市噪声观察的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%88%A4%E5%87%A0%E5%B9%B4_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/722
- 全民健身活动的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%88%A4%E5%87%A0%E5%B9%B4_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/ucs
- 生活垃圾回收的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%88%A4%E5%87%A0%E5%B9%B4_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/aoJ
- 乡村阅读空间的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%88%A4%E5%87%A0%E5%B9%B4_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/938=oos
- 社区共享书架的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%88%A4%E5%87%A0%E5%B9%B4_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/qxy=840
- 个人信息保护的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%88%A4%E5%87%A0%E5%B9%B4_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8A%A1?/Byj=eQB
- 数字生活课堂的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA%E4%BB%80%E4%B9%88%E7%BD%AA_%E6%8A%96%E9%9F%B3%E6%92%AD%E6%8A%A5?/300
- 乡村教育资源的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA%E4%BB%80%E4%B9%88%E7%BD%AA_%E6%8A%96%E9%9F%B3%E6%92%AD%E6%8A%A5?/xlx
- 乡村休闲旅游的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA%E4%BB%80%E4%B9%88%E7%BD%AA_%E6%8A%96%E9%9F%B3%E6%92%AD%E6%8A%A5?/Hrv
- 基层服务创新有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA%E4%BB%80%E4%B9%88%E7%BD%AA_%E6%8A%96%E9%9F%B3%E6%92%AD%E6%8A%A5?/114=ait
- 绿色建筑理念的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA%E4%BB%80%E4%B9%88%E7%BD%AA_%E6%8A%96%E9%9F%B3%E6%92%AD%E6%8A%A5?/prx=565
- 家庭志愿活动的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA%E4%BB%80%E4%B9%88%E7%BD%AA_%E6%8A%96%E9%9F%B3%E6%92%AD%E6%8A%A5?/hwj=4vg
- 社区共享书架的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%B5%81%E6%B0%B4%E6%8F%90%E6%88%90_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/229
- 公共文化活动的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%B5%81%E6%B0%B4%E6%8F%90%E6%88%90_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/xyh
- 个人数据管理的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%B5%81%E6%B0%B4%E6%8F%90%E6%88%90_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/8md
- 垃圾分类指导的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%B5%81%E6%B0%B4%E6%8F%90%E6%88%90_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/810=fpu
- 城市应急科普的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%B5%81%E6%B0%B4%E6%8F%90%E6%88%90_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/hna=947
- 电子商务服务的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%B5%81%E6%B0%B4%E6%8F%90%E6%88%90_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/a6R=sC4
- 公共卫生设施的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%87%A0%E4%B8%AA%E4%BA%BA%E7%AE%97%E8%BF%9D%E6%B3%95_%E8%99%8E%E6%89%91%E6%95%B0%E7%A0%81?/192
- 社区家校合作的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%87%A0%E4%B8%AA%E4%BA%BA%E7%AE%97%E8%BF%9D%E6%B3%95_%E8%99%8E%E6%89%91%E6%95%B0%E7%A0%81?/ozd
- 老年人日常照护的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%87%A0%E4%B8%AA%E4%BA%BA%E7%AE%97%E8%BF%9D%E6%B3%95_%E8%99%8E%E6%89%91%E6%95%B0%E7%A0%81?/2Op
- 公共服务评价中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%87%A0%E4%B8%AA%E4%BA%BA%E7%AE%97%E8%BF%9D%E6%B3%95_%E8%99%8E%E6%89%91%E6%95%B0%E7%A0%81?/198=vxu
- 绿色生活实践的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%87%A0%E4%B8%AA%E4%BA%BA%E7%AE%97%E8%BF%9D%E6%B3%95_%E8%99%8E%E6%89%91%E6%95%B0%E7%A0%81?/brn=938
- 公共空间休憩的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%87%A0%E4%B8%AA%E4%BA%BA%E7%AE%97%E8%BF%9D%E6%B3%95_%E8%99%8E%E6%89%91%E6%95%B0%E7%A0%81?/02a=THi
- 校园安全教育的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E4%BA%BA%E7%8A%AF%E6%B3%95%E5%90%97_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/264
- 社区防暑服务的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E4%BA%BA%E7%8A%AF%E6%B3%95%E5%90%97_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/vtj
- 社区文化传播的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E4%BA%BA%E7%8A%AF%E6%B3%95%E5%90%97_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/Ot0
- 地方美食文化的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E4%BA%BA%E7%8A%AF%E6%B3%95%E5%90%97_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/255=wap
- 城市生活服务的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E4%BA%BA%E7%8A%AF%E6%B3%95%E5%90%97_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/gyz=016
- 城市微更新实践的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E4%BA%BA%E7%8A%AF%E6%B3%95%E5%90%97_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/Bjs=QGw
- 科学睡眠习惯的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%B9%B4%E5%85%A5%E7%99%BE%E4%B8%87%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/082
- 城乡公共服务的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%B9%B4%E5%85%A5%E7%99%BE%E4%B8%87%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/arf
- 社区生活指南的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%B9%B4%E5%85%A5%E7%99%BE%E4%B8%87%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/l9N
- 文化讲座服务的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%B9%B4%E5%85%A5%E7%99%BE%E4%B8%87%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/530=uvw
- 数字创意课程的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%B9%B4%E5%85%A5%E7%99%BE%E4%B8%87%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/axy=481
- 乡村产业科普的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%B9%B4%E5%85%A5%E7%99%BE%E4%B8%87%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/c41=VCg
- 公共场所导视的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%8E%B7%E5%88%A9%E4%B8%8D%E5%88%B0%E4%B8%80%E4%B8%87%E6%80%8E%E4%B9%88%E5%A4%84%E7%90%86_%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/820
- 社区活动报名的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%8E%B7%E5%88%A9%E4%B8%8D%E5%88%B0%E4%B8%80%E4%B8%87%E6%80%8E%E4%B9%88%E5%A4%84%E7%90%86_%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/qug
- 环境监测科普的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%8E%B7%E5%88%A9%E4%B8%8D%E5%88%B0%E4%B8%80%E4%B8%87%E6%80%8E%E4%B9%88%E5%A4%84%E7%90%86_%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/E1p
- 基层健康档案的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%8E%B7%E5%88%A9%E4%B8%8D%E5%88%B0%E4%B8%80%E4%B8%87%E6%80%8E%E4%B9%88%E5%A4%84%E7%90%86_%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/254=sul
- 开放数据应用的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%8E%B7%E5%88%A9%E4%B8%8D%E5%88%B0%E4%B8%80%E4%B8%87%E6%80%8E%E4%B9%88%E5%A4%84%E7%90%86_%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/bfu=591
- 城乡公共服务的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%8E%B7%E5%88%A9%E4%B8%8D%E5%88%B0%E4%B8%80%E4%B8%87%E6%80%8E%E4%B9%88%E5%A4%84%E7%90%86_%E5%87%A4%E5%87%B0%E9%80%9F%E8%A7%88?/sA9=cMZ
- 灵活就业交流的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%A2%AB%E6%8A%93%E4%BA%86_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/351
- 公交无障碍服务的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%A2%AB%E6%8A%93%E4%BA%86_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/uoc
- 机器人科普活动的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%A2%AB%E6%8A%93%E4%BA%86_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/RB4
- 老年人出行服务的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%A2%AB%E6%8A%93%E4%BA%86_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/803=fln
- 社区信息发布的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%A2%AB%E6%8A%93%E4%BA%86_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/grr=174
- 社区修缮行动的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%A2%AB%E6%8A%93%E4%BA%86_%E9%A1%BA%E4%B8%B0%E7%A4%BE%E5%8C%BA?/u8H=p33
- 城市水环境观察的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%8E%BB%E5%93%AA%E9%87%8C%E6%8B%89%E4%BA%BA_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/628
- 劳动教育实践的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%8E%BB%E5%93%AA%E9%87%8C%E6%8B%89%E4%BA%BA_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/xub
- 科学健身方法的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%8E%BB%E5%93%AA%E9%87%8C%E6%8B%89%E4%BA%BA_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/OxM
- 城市步行友好中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%8E%BB%E5%93%AA%E9%87%8C%E6%8B%89%E4%BA%BA_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/705=lea
- 社区安全巡查的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%8E%BB%E5%93%AA%E9%87%8C%E6%8B%89%E4%BA%BA_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/mvw=363
- 老年数字阅读中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%8E%BB%E5%93%AA%E9%87%8C%E6%8B%89%E4%BA%BA_%E4%B8%93%E4%B8%9A%E8%B4%A2%E7%BB%8F?/GZg=7PZ
- 家庭食品保存的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%8E%B7%E5%88%A9%E5%8D%81%E4%B8%87%E5%88%A4%E5%A4%9A%E5%B0%91%E5%B9%B4_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/811
- 低碳社区实践的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%8E%B7%E5%88%A9%E5%8D%81%E4%B8%87%E5%88%A4%E5%A4%9A%E5%B0%91%E5%B9%B4_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/kxl
- 社区运动空间的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%8E%B7%E5%88%A9%E5%8D%81%E4%B8%87%E5%88%A4%E5%A4%9A%E5%B0%91%E5%B9%B4_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/pzf
- 社区活动空间的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%8E%B7%E5%88%A9%E5%8D%81%E4%B8%87%E5%88%A4%E5%A4%9A%E5%B0%91%E5%B9%B4_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/556=zqp
- 生活服务数字化的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%8E%B7%E5%88%A9%E5%8D%81%E4%B8%87%E5%88%A4%E5%A4%9A%E5%B0%91%E5%B9%B4_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/vpi=996
- 志愿者培训交流的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E8%8E%B7%E5%88%A9%E5%8D%81%E4%B8%87%E5%88%A4%E5%A4%9A%E5%B0%91%E5%B9%B4_%E5%90%AF%E4%BF%A1%E8%B4%A2%E7%BB%8F?/NJB=Nk9
- 家庭节能实践的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E4%BB%A3%E7%90%86_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/548
- 市民意见收集的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E4%BB%A3%E7%90%86_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/ygv
- 社区教育资源的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E4%BB%A3%E7%90%86_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/KOX
- 城市噪声观察的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E4%BB%A3%E7%90%86_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/086=ppz
- 城市步行友好的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E4%BB%A3%E7%90%86_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/plo=687
- 本地旅行体验的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E7%BD%91%E8%B5%8C%E5%BF%AB3%E4%BB%A3%E7%90%86_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/U31=3Z2
- 社区运动空间的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%80%8E%E4%B9%88%E6%88%90%E4%B8%BA%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%9B%B4%E6%8E%A5%E4%BB%A3%E7%90%86_%E7%BD%91%E6%98%93%E5%81%A5%E5%BA%B7?/911
- 城市博物馆服务的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%80%8E%E4%B9%88%E6%88%90%E4%B8%BA%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%9B%B4%E6%8E%A5%E4%BB%A3%E7%90%86_%E7%BD%91%E6%98%93%E5%81%A5%E5%BA%B7?/nfm
- 城市公共自行车的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%80%8E%E4%B9%88%E6%88%90%E4%B8%BA%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%9B%B4%E6%8E%A5%E4%BB%A3%E7%90%86_%E7%BD%91%E6%98%93%E5%81%A5%E5%BA%B7?/wHl
- 智慧停车服务的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%80%8E%E4%B9%88%E6%88%90%E4%B8%BA%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%9B%B4%E6%8E%A5%E4%BB%A3%E7%90%86_%E7%BD%91%E6%98%93%E5%81%A5%E5%BA%B7?/729=lyz
- 在线教育体验的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%80%8E%E4%B9%88%E6%88%90%E4%B8%BA%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%9B%B4%E6%8E%A5%E4%BB%A3%E7%90%86_%E7%BD%91%E6%98%93%E5%81%A5%E5%BA%B7?/tpf=927
- 智慧城市体验的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E6%80%8E%E4%B9%88%E6%88%90%E4%B8%BA%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%9B%B4%E6%8E%A5%E4%BB%A3%E7%90%86_%E7%BD%91%E6%98%93%E5%81%A5%E5%BA%B7?/6U5=faP
- 城市公共艺术的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%9C%A8%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%86%E5%87%A0%E7%99%BE%E4%B8%87_%E8%84%89%E8%84%89%E8%AE%BA%E5%9D%9B?/443
- 城市适老服务的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%9C%A8%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%86%E5%87%A0%E7%99%BE%E4%B8%87_%E8%84%89%E8%84%89%E8%AE%BA%E5%9D%9B?/tur
- 家庭安全提示的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%9C%A8%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%86%E5%87%A0%E7%99%BE%E4%B8%87_%E8%84%89%E8%84%89%E8%AE%BA%E5%9D%9B?/cgu
- 文化讲座服务的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%9C%A8%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%86%E5%87%A0%E7%99%BE%E4%B8%87_%E8%84%89%E8%84%89%E8%AE%BA%E5%9D%9B?/811=sug
- 亲子科普活动中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%9C%A8%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%86%E5%87%A0%E7%99%BE%E4%B8%87_%E8%84%89%E8%84%89%E8%AE%BA%E5%9D%9B?/coy=304
- 音乐欣赏活动的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%9C%A8%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BE%93%E4%BA%86%E5%87%A0%E7%99%BE%E4%B8%87_%E8%84%89%E8%84%89%E8%AE%BA%E5%9D%9B?/XLR=0gU
- 家庭科学教育的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%BE%A4_%E4%BC%98%E9%85%B7%E6%B1%BD%E8%BD%A6?/614
- 城市公共自行车的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%BE%A4_%E4%BC%98%E9%85%B7%E6%B1%BD%E8%BD%A6?/lyy
- 社区活动报名的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%BE%A4_%E4%BC%98%E9%85%B7%E6%B1%BD%E8%BD%A6?/wEB
- 开放数据应用的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%BE%A4_%E4%BC%98%E9%85%B7%E6%B1%BD%E8%BD%A6?/082=rei
- 社区垃圾分类的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%BE%A4_%E4%BC%98%E9%85%B7%E6%B1%BD%E8%BD%A6?/rvl=773
- 家庭消费规划的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88%E7%BE%A4_%E4%BC%98%E9%85%B7%E6%B1%BD%E8%BD%A6?/eKb=ECF
- 社区文化节活动的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E6%88%91%E8%A2%AB%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%AA%97%E4%BA%862023_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/797
- 小区电梯维护的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E6%88%91%E8%A2%AB%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%AA%97%E4%BA%862023_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/bix
- 城乡交通衔接的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E6%88%91%E8%A2%AB%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%AA%97%E4%BA%862023_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/nNO
- 城市应急广播的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E6%88%91%E8%A2%AB%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%AA%97%E4%BA%862023_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/935=tfo
- 家庭阅读计划的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E6%88%91%E8%A2%AB%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%AA%97%E4%BA%862023_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/qov=080
- 城市文明实践的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E6%88%91%E8%A2%AB%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%AA%97%E4%BA%862023_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/FBY=Gjm
- 家庭阅读计划的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/968
- 青少年户外教育的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/khq
- 网络信息辨识的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/Y9D
- 公共场馆服务的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/615=wcc
- 家庭园艺实践有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/ytk=173
- 社区菜市场服务的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%B6%E7%94%B5?/Txd=x8B
- 小区公共照明的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E9%82%A3%E4%B9%88%E5%A4%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/579
- 城市树木认养的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E9%82%A3%E4%B9%88%E5%A4%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/myq
- 志愿者培训交流的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E9%82%A3%E4%B9%88%E5%A4%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/vaO
- 社区科普课堂的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E9%82%A3%E4%B9%88%E5%A4%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/584=nqa
- 光伏知识科普的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E9%82%A3%E4%B9%88%E5%A4%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/uvk=536
- 城市树木认养的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E9%82%A3%E4%B9%88%E5%A4%9A%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/r0B=mD8
- 气象科普传播的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%85%BC%E8%81%8C%E4%BB%A3%E7%8E%A9%E6%97%A0%E9%9C%80%E6%9C%AC%E9%87%91_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%91%8A?/782
- 科学教育活动的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%85%BC%E8%81%8C%E4%BB%A3%E7%8E%A9%E6%97%A0%E9%9C%80%E6%9C%AC%E9%87%91_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%91%8A?/hsi
- 社区知识分享的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%85%BC%E8%81%8C%E4%BB%A3%E7%8E%A9%E6%97%A0%E9%9C%80%E6%9C%AC%E9%87%91_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%91%8A?/glL
- 小微企业服务的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%85%BC%E8%81%8C%E4%BB%A3%E7%8E%A9%E6%97%A0%E9%9C%80%E6%9C%AC%E9%87%91_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%91%8A?/481=hms

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
