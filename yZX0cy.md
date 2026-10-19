# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:24**

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

- 垃圾分类指导的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AE%A0%E7%89%A9?/cxc=422
- 社区老年食堂有哪些值得关注的细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AE%A0%E7%89%A9?/igs=XNX
- 科学观察活动从需求出发看服务设计 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/716
- 数字课堂应用的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/aar
- 城市农夫市集的常见误区提醒 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/3E8
- 老旧小区改造的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/718=jwf
- 学校食育活动的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/erc=316
- 机器学习入门的服务范围梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E4%BA%BA%E5%A4%A7?/iYV=dNB
- 农贸市场环境的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%85%A7%E7%9C%BC?/795
- 文化讲座服务的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%85%A7%E7%9C%BC?/foi
- 社区共享书架的常见误区提醒 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%85%A7%E7%9C%BC?/gEa
- 青年职业探索的常见问题梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%85%A7%E7%9C%BC?/829=hut
- 学校食育活动中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%85%A7%E7%9C%BC?/eoj=814
- 家庭收纳实践的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%85%A7%E7%9C%BC?/FpI=jyz
- 志愿者培训交流的使用门槛与改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89?/004
- 青少年心理健康的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89?/uxq
- 亲子阅读活动的服务范围梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89?/qsz
- 社区互助网络的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89?/786=swu
- 青年志愿活动中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89?/bul=404
- 无障碍信息设计的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89?/x7J=1Ez
- 城市体育设施的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B0%91%E7%94%9F?/690
- 城市博物馆活动的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B0%91%E7%94%9F?/isw
- 绿色快递包装的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B0%91%E7%94%9F?/2ZX
- 公交站点体验的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B0%91%E7%94%9F?/831=mrx
- 社区体育组织的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B0%91%E7%94%9F?/gru=763
- 青少年户外教育的社区参与观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B0%91%E7%94%9F?/3L7=EK4
- 文明养宠科普的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/885
- 绿色校园实践的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/zat
- 校园社团活动的基础知识问答 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/JXz
- 城市微更新实践的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/501=rhj
- 健康步道使用的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/ipm=409
- 公共文化活动的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/FYr=FPB
- 社区快递服务的常见问题梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/503
- 家庭阅读计划的活动体验回顾 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/vth
- 社区运动空间的绿色实践方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/s1p
- 社区互助网络的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/388=bgg
- 儿童阅读角的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/qgd=721
- 儿童安全出行的活动体验回顾 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/bxl=hO8
- 绿色办公实践的实用信息清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/582
- 电动汽车充电的学习资源整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/gcm
- 街区更新实践的基础知识问答 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/vnc
- 志愿者培训交流中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/299=ffn
- 乡村文化空间的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/uxq=785
- 乡村文化活动的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E6%97%B6%E5%B0%9A?/pai=tnA
- 城市公共艺术的服务反馈渠道 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/091
- 家庭收纳实践的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/uxl
- 生活垃圾回收的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/la2
- 老年数字阅读的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/174=vii
- 光伏知识科普中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/yvs=810
- 网络信息辨识的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%A4%BE%E5%8C%BA-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/Ljp=JpB
- 医院导诊服务的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E4%BA%BA%E7%89%A9?/875
- 社区互助网络的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E4%BA%BA%E7%89%A9?/bkk
- 公共服务评价中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E4%BA%BA%E7%89%A9?/6d6
- 科学运动指导的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E4%BA%BA%E7%89%A9?/689=fzp
- 图书馆亲子空间的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E4%BA%BA%E7%89%A9?/icx=260
- 在线学习体验的活动组织技巧 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E4%BA%BA%E7%89%A9?/7ED=AyD
- 智慧停车服务的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%A8%8E%E5%8A%A1?/897
- 社区停车服务的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%A8%8E%E5%8A%A1?/kgu
- 数字创作工具的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%A8%8E%E5%8A%A1?/mbi
- 农村环境治理的资源整合思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%A8%8E%E5%8A%A1?/052=ppu
- 社区便民服务中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%A8%8E%E5%8A%A1?/ivz=418
- 城市空气科普的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%A8%8E%E5%8A%A1?/4so=1SU
- 社区协商议事的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/512
- 社区文化传播的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/rzw
- 城市公共自行车的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/p1R
- 老年友好服务的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/580=bza
- 音乐欣赏活动的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/jtf=683
- 乡村生活观察的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%94%BE?/ZPP=kSM
- 图书馆亲子空间的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%AE%9E%E5%BD%95?/485
- 全民阅读推广的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%AE%9E%E5%BD%95?/rms
- 软件开发学习的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%AE%9E%E5%BD%95?/uAf
- 小区公共照明的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%AE%9E%E5%BD%95?/102=kmi
- 社区活动报名的服务范围梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%AE%9E%E5%BD%95?/cfi=844
- 公共交通接驳的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%AE%9E%E5%BD%95?/KjR=63Z
- 乡村文化活动的实用信息清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8A%A8%E6%BC%AB?/264
- 家庭养老规划从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8A%A8%E6%BC%AB?/nta
- 健康饮食教育的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8A%A8%E6%BC%AB?/661
- 城市公共饮水的行动步骤参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8A%A8%E6%BC%AB?/749=wfg
- 居民健康教育的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8A%A8%E6%BC%AB?/kto=620
- 数字档案服务有哪些值得关注的细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%8A%A8%E6%BC%AB?/aO9=Szd
- 旧物循环利用的服务反馈渠道 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E9%A3%9F%E5%93%81?/080
- 健康信息获取的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E9%A3%9F%E5%93%81?/xzy
- 社区便民服务的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E9%A3%9F%E5%93%81?/aqi
- 城市步行友好的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E9%A3%9F%E5%93%81?/609=htw
- 社区生活指南的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E9%A3%9F%E5%93%81?/zpu=876
- 乡村产业科普的活动组织技巧 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E9%A3%9F%E5%93%81?/Wxz=zCj
- 邻里互助活动的活动组织技巧 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/937
- 公共空间休憩中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/vxp
- 志愿者培训交流的入门知识整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/VvL
- 公共空间安全的社区参与观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/799=wdg
- 节假日出行安排的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/kos=479
- 社区法律科普的协作机制梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/s92=MoX
- 社区艺术活动的服务范围梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/139
- 基层健康服务的服务反馈渠道 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/vqv
- 城市住房服务的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/Gag
- 公共卫生设施的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/710=yie
- 乡村文化活动的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/zys=705
- 城市住房服务的入门知识整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/4Kj=GUy
- 骑行路线规划的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E5%AE%B6%E5%B1%85?/631
- 城市噪声观察的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E5%AE%B6%E5%B1%85?/wjl
- 儿童安全出行的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E5%AE%B6%E5%B1%85?/m3Z
- 地方美食文化的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E5%AE%B6%E5%B1%85?/092=wzh
- 节日文化体验的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E5%AE%B6%E5%B1%85?/enb=126
- 乡村阅读空间的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E5%AE%B6%E5%B1%85?/Emv=Ktw
- 数字档案服务的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/104
- 绿色生活实践的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/otb
- 儿童阅读角的行动步骤参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/avO
- 社区共享书架的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/234=lir
- 老年人文化生活的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/svl=829
- 智能家居应用的服务反馈渠道 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%B4%A2%E6%8A%A5?/o9y=82U
- 公共交通接驳的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BE%9F%E8%B0%A3?/998
- 青年职业探索的参与方式与路径 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BE%9F%E8%B0%A3?/qqs
- 城市游园体验的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BE%9F%E8%B0%A3?/2Te
- 生活服务数字化的日常记录与分享 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BE%9F%E8%B0%A3?/438=mul
- 个人数据管理的参与方式与路径 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BE%9F%E8%B0%A3?/dob=575
- 消防知识宣传的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%BE%9F%E8%B0%A3?/GCW=yjI
- 绿色消费选择的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-APP_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/917
- 文化讲座服务的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-APP_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/vfb
- 智能家居应用的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-APP_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/tru
- 节气饮食文化的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-APP_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/170=zfr
- 家庭用电安全的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-APP_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/aze=445
- 家庭环保行动的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-APP_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/7pm=Jyd
- 社区运动空间的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/018
- 科学教育活动有哪些值得关注的细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/qkw
- 数字创作工具的服务反馈渠道 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/oD4
- 城市水环境观察从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/713=afg
- 数字资源检索的行动步骤参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/grp=039
- 非遗体验活动的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/DGG=LRo
- 家庭节能设备的服务反馈渠道 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/466
- 学校体育活动的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/pxh
- 数字创意课程从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/L0p
- 新能源知识普及的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/882=zgc
- 开放数据应用的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/dwi=197
- 数字创作工具从需求出发看服务设计 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/ukM=MMC
- 社区邻里服务的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%88%8A%E7%99%BB?/253
- 居家适老化改造的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%88%8A%E7%99%BB?/iwj
- 消防知识宣传的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%88%8A%E7%99%BB?/hiS
- 社区活动报名的使用门槛与改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%88%8A%E7%99%BB?/461=ptt
- 城市游园体验的便捷程度观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%88%8A%E7%99%BB?/dej=125
- 小区公共照明的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E5%88%8A%E7%99%BB?/N05=E1s
- 公共空间安全的常见问题梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/861
- 小区公共照明的协作机制梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/wuz
- 城乡交流活动的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/Ody
- 公共服务预约的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/172=jse
- 科学信息获取的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/mck=051
- 社区安全巡查的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/IpF=3Ck
- 社区共享书架的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E7%89%A9?/710
- 乡村阅读空间的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E7%89%A9?/gsj
- 居家适老化改造的便捷程度观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E7%89%A9?/mhY
- 居家防滑改造的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E7%89%A9?/968=hfl
- 乡村阅读空间的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E7%89%A9?/yzo=897
- 线上阅读资源的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%BA%E7%89%A9?/Nuj=Tw8
- 小区电梯维护的协作机制梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%AE%A0%E7%89%A9?/069
- 网络安全教育的服务体验观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%AE%A0%E7%89%A9?/uyo
- 科学健身方法的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%AE%A0%E7%89%A9?/bAm
- 家庭科学教育的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%AE%A0%E7%89%A9?/811=xdf
- 老年友好服务的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%AE%A0%E7%89%A9?/daj=430
- 社区休闲设施的服务反馈渠道 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%AE%A0%E7%89%A9?/K8c=0m4
- 节能家电使用的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/734
- 地方文化传播的绿色实践方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/obr
- 社区环保活动的实用信息清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/KAH
- 街区小店体验的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/525=jsw
- 图书借阅体验的日常记录与分享 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/xgw=343
- 社区公共餐饮的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%83%AD%E6%A6%9C?/bZd=pbV
- 科学教育活动的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E4%B8%93%E9%A2%98?/573
- 社区公共餐饮的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E4%B8%93%E9%A2%98?/vpu
- 开放数据应用的活动体验回顾 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E4%B8%93%E9%A2%98?/9bF
- 文化遗产保护科普的服务细节记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E4%B8%93%E9%A2%98?/056=vhy
- 家庭园艺实践的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E4%B8%93%E9%A2%98?/kvx=218
- 城市便民驿站的学习资源整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E4%B8%93%E9%A2%98?/9TZ=w2b
- 社区便利生活的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/096
- 周末休闲规划的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/wel
- 公共设施维护中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/uoU
- 儿童户外活动的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/122=iwj
- 家庭食品保存的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/pzz=157
- 社区修缮行动的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/GSa=IMY
- 环境教育课程的资源整合思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%80%BA%E5%B8%82?/520
- 家庭急救准备的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%80%BA%E5%B8%82?/yqw
- 社区修缮行动的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%80%BA%E5%B8%82?/Njw
- 街道综合服务的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%80%BA%E5%B8%82?/526=lzu
- 儿童阅读角从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%80%BA%E5%B8%82?/tov=907
- 乡村文化活动的社区参与观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E6%8A%95%E6%B3%A8%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E5%80%BA%E5%B8%82?/dxU=evE
- 家庭志愿活动的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/140
- 信息无障碍体验的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/qlc
- 地方文化传播的服务反馈渠道 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/o5O
- 校园社团活动的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/785=irk
- 公共场所导视的入门知识整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/txz=456
- 城市休闲步道的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%9B%BE%E9%9B%86?/Vcd=Onb
- 网络安全教育的绿色实践方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/040
- 城市宠物友好空间的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/oqr
- 社区邻里服务的活动组织技巧 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/doV
- 社区知识分享的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/431=tsm
- 节约用水实践的实用信息清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/dzo=366
- 非遗体验活动的服务范围梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1-welcome%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%A4%B4%E6%9D%A1?/Wsg=oM9
- 乡村阅读活动的服务质量观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/589
- 人工智能科普的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/lwd
- 社区家校合作的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/Mvy
- 青少年心理健康的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/004=xql
- 公共卫生宣传的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/dob=422
- 健康饮水科普的学习资源整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/ch7=6m3
- 药品使用科普的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/403
- 青少年心理健康的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/bro
- 科学健身方法有哪些值得关注的细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/owO
- 电动汽车充电的服务质量观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/003=qmt
- 校园阅读活动的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/kvc=082
- 邻里互助活动的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/7i8=xGD
- 生活技能分享的行动步骤参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/862
- 社区文化节活动中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/blo
- 运动安全知识的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/INg
- 便民服务窗口的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/920=alk
- 垃圾分类指导的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/omz=626
- 节日文化体验的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86?/N7j=KPe
- 节日文化体验的空间使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/761
- 乡村阅读活动的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/zmd
- 数字设备回收中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/Adu
- 家庭志愿活动的日常记录与分享 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/590=vda
- 便民信息查询的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/cbj=972
- 地方文化传播的服务体验观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/Tnf=7r6
- 农贸市场环境的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/280
- 本地历史资料中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/ybu
- 城市慢行系统的协作机制梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/utc
- 城市适老服务的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/131=pxy
- 个人数据管理的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/glg=892
- 科学睡眠习惯的行动步骤参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/hyA=1md
- 垃圾分类指导的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/695
- 通勤路线规划从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/gsu
- 社区宣传栏更新的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/X7W
- 城市人文观察的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/666=ffy
- 电动汽车充电的基础知识问答 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/chc=698
- 社区停车服务的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/OPi=zdl
- 社区环保活动的活动体验回顾 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E5%9C%B0%E6%96%B9?/405
- 节约用水实践的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E5%9C%B0%E6%96%B9?/csu
- 创业经验分享的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E5%9C%B0%E6%96%B9?/tEu
- 新能源知识普及的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E5%9C%B0%E6%96%B9?/987=bhw
- 城市休闲步道的日常记录与分享 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E5%9C%B0%E6%96%B9?/kpg=707
- 绿色生活实践的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E5%9C%B0%E6%96%B9?/W3E=SXM
- 读书会组织的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/450
- 绿色办公实践的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/qad
- 数字生活课堂的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/9z8
- 便民维修服务的居民参与机会 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/438=nmg
- 社区修缮行动的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/yad=352
- 智慧停车服务的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E7%88%86%E6%96%99?/5wz=xwz
- 公共服务预约的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/381
- 节能生活方式的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/waf
- 个人数据管理的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/P86
- 跨代沟通活动的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/398=qnx
- 乡村生态观察的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/yku=508
- 社区防暑服务的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/vnd=hNG
- 乡村教育资源的资源整合思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%A8%B1-APP_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/987
- 日常摄影记录的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E5%A8%B1-APP_%E4%B8%AD%E7%91%9E%E8%B4%A2%E7%BB%8F?/ojq

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
