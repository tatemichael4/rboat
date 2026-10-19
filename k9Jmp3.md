# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:26**

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

- 数字政务体验的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_PK%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/69m
- 老年友好服务的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_PK%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/326=ehk
- 个人时间管理的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_PK%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/nic=773
- 家庭收纳实践的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_PK%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E6%97%B6%E8%AF%84?/7Xz=aKQ
- 乡村生活观察的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_PK%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/402
- 绿色生活实践的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_PK%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/pqh
- 软件开发学习的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_PK%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/PVU
- 社区修缮行动的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_PK%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/270=kod
- 社区公共卫生的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_PK%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/ipr=809
- 公共设施维护的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_PK%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/nHq=mV6
- 科学运动指导的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_PK%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E5%8D%83%E5%B8%86?/489
- 社区菜市场服务的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_PK%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E5%8D%83%E5%B8%86?/jdw
- 小区停车协商的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_PK%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E5%8D%83%E5%B8%86?/q9b
- 志愿服务平台的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_PK%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E5%8D%83%E5%B8%86?/916=ftg
- 机器学习入门从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_PK%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E5%8D%83%E5%B8%86?/ueq=127
- 公交站点体验的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_PK%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_360%E5%8D%83%E5%B8%86?/rhK=NVl
- 旧物循环利用的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_PK%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/209
- 城市农夫市集的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_PK%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/tur
- 绿色建筑理念中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_PK%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/Q7N
- 光伏知识科普的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_PK%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/820=jvl
- 绿色办公实践的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_PK%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/loq=992
- 青少年心理健康的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_PK%E5%BD%A9%E7%A5%A8-APP_%E4%BA%AC%E4%B8%9C%E6%96%B0%E9%97%BB?/5z4=9MJ
- 乡村生活观察的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_PK%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%91%84%E5%BD%B1?/842
- 老年智能设备的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_PK%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%91%84%E5%BD%B1?/rwj
- 乡村公共文化的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_PK%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%91%84%E5%BD%B1?/4qb
- 健康饮水科普的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_PK%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%91%84%E5%BD%B1?/954=oro
- 家庭阅读计划的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_PK%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%91%84%E5%BD%B1?/eeu=230
- 数字课堂应用的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_PK%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%91%84%E5%BD%B1?/t0f=AYp
- 农业科普体验的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_PK%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/048
- 城市雨天出行的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_PK%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/lmf
- 社区体育组织的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_PK%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/PD2
- 城市社区治理的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_PK%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/560=bwl
- 骑行路线规划的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_PK%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/iwu=516
- 社区宣传栏更新的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_PK%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/AcQ=jdr
- 垃圾分类指导的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_PK%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%BF%AB%E8%AE%AF?/670
- 药品使用科普的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_PK%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%BF%AB%E8%AE%AF?/hun
- 社区便利生活的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_PK%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%BF%AB%E8%AE%AF?/nzA
- 校园安全教育从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_PK%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%BF%AB%E8%AE%AF?/094=qgh
- 家庭养老规划的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_PK%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%BF%AB%E8%AE%AF?/tyt=204
- 社区故事采集的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_PK%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E5%BF%AB%E8%AE%AF?/eKu=fQ3
- 儿童友好空间从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_PK%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/911
- 家庭安全提示的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_PK%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/jsp
- 在线学习体验的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_PK%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/p3n
- 绿色出行服务的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_PK%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/096=sjy
- 社区庭院绿化的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_PK%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/emj=722
- 城市应急科普的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_PK%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/GVO=Tnc
- 地方文化传播的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_PK%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%91%E6%8A%80?/918
- 线上阅读资源的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_PK%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%91%E6%8A%80?/hev
- 零废弃生活尝试的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_PK%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%91%E6%8A%80?/KGV
- 青少年编程学习的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_PK%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%91%E6%8A%80?/026=cau
- 城市慢行系统的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_PK%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%91%E6%8A%80?/ouf=577
- 社区应急准备的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_PK%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%91%E6%8A%80?/Tlz=3Wb
- 社区花园共建中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_PK%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E8%AE%BA?/897
- 数字档案服务的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_PK%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E8%AE%BA?/lmg
- 传统节日科普的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_PK%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E8%AE%BA?/3RH
- 公共服务数字化的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_PK%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E8%AE%BA?/709=maq
- 家庭健康管理的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_PK%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E8%AE%BA?/hbc=680
- 非遗体验活动的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_PK%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E7%A4%BE%E8%AE%BA?/0aa=WLT
- 城市慢行系统的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_PK%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%B0%91%E7%94%9F?/123
- 街区小店体验从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_PK%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%B0%91%E7%94%9F?/lrn
- 家庭食品保存中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_PK%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%B0%91%E7%94%9F?/dto
- 基层健康服务的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_PK%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%B0%91%E7%94%9F?/733=iqo
- 社区手工活动的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_PK%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%B0%91%E7%94%9F?/mhv=511
- 邻里共享空间的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_PK%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E6%B0%91%E7%94%9F?/UZp=CPW
- 运动安全知识的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_PK%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/436
- 城市文化路线的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_PK%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/ngo
- 线上阅读资源的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_PK%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/2Yl
- 城市慢跑路线的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_PK%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/332=lbo
- 社区便民集市的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_PK%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/xuo=077
- 青少年心理健康的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_PK%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%A7%91%E6%8A%80?/9bV=bup
- 物业服务沟通的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_PK%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/231
- 开放数据应用的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_PK%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/vyo
- 节气饮食文化的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_PK%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/fIq
- 家庭阅读计划的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_PK%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/044=tip
- 家庭环保习惯的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_PK%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/tjp=922
- 社区学习活动的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_PK%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/ViN=hR6
- 公共图书馆服务的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_PK%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%8F%E8%A7%82?/403
- 基层服务创新的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_PK%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%8F%E8%A7%82?/alx
- 节假日出行安排的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_PK%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%8F%E8%A7%82?/MAB
- 社区邻里服务的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_PK%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%8F%E8%A7%82?/164=lcy
- 家庭养老规划的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_PK%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%8F%E8%A7%82?/uis=096
- 数字支付体验中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_PK%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%8F%E8%A7%82?/5r8=hJD
- 农产品品牌传播的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_tt%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/720
- 非遗课堂体验的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_tt%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/tms
- 乡村文化活动的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_tt%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/Zqk
- 数字素养提升的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_tt%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/516=msg
- 儿童户外活动的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_tt%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/rql=255
- 志愿服务平台的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_tt%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E6%95%B0%E8%AF%BB?/DMx=Ago
- 科学信息获取的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_tt%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%AE%8F%E8%A7%82?/048
- 气象科普传播的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_tt%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%AE%8F%E8%A7%82?/rfk
- 社区教育资源的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_tt%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%AE%8F%E8%A7%82?/baK
- 家庭健康管理的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_tt%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%AE%8F%E8%A7%82?/740=pbj
- 全民阅读推广的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_tt%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%AE%8F%E8%A7%82?/dbq=277
- 城乡交流活动的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_tt%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%AE%8F%E8%A7%82?/wNx=pyO
- 生活垃圾回收的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_tt%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/680
- 城市博物馆活动的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_tt%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/ait
- 社区手工活动的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_tt%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/Xiv
- 社区庭院绿化的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_tt%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/431=gpr
- 家庭运动计划有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_tt%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/zjf=744
- 儿童阅读角的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_tt%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BE%8E%E5%A6%86?/8lI=h3e
- 社区邻里服务的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_tt%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/225
- 社区环保活动的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_tt%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/tsj
- 老年友好服务的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_tt%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/aMo
- 社区商业活力的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_tt%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/380=jhb
- 城市公共艺术的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_tt%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/krd=639
- 社区设施共享的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_tt%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E9%97%AE%E5%8D%B7?/sOh=TKX
- 文化遗产保护科普的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_tt%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%90%86%E8%B4%A2?/465
- 在线教育体验的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_tt%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%90%86%E8%B4%A2?/muy
- 家庭收纳实践的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_tt%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%90%86%E8%B4%A2?/crM
- 乡村生态观察的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_tt%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%90%86%E8%B4%A2?/407=cbs
- 地方文化传播的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_tt%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%90%86%E8%B4%A2?/phy=540
- 邻里共享空间的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_tt%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E7%90%86%E8%B4%A2?/B5F=Eev
- 城市夜间生活中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_tt%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/116
- 职业技能学习从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_tt%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/rdm
- 信息无障碍体验的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_tt%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/Efq
- 城市应急广播的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_tt%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/036=hle
- 街头绿植养护的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_tt%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/uyp=428
- 校园安全教育的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_tt%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E6%B8%AF%E8%82%A1?/8x4=B2n
- 城市噪声观察的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_tt%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/861
- 社区邻里服务的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_tt%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/ukx
- 社区知识分享的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_tt%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/XEk
- 运动安全知识的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_tt%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/742=ckj
- 城市体育设施的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_tt%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/wdc=687
- 社区花园共建的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_tt%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%99%9A%E6%8A%A5?/Znc=Bub
- 街道综合服务的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_tt%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%8A%A8%E6%BC%AB?/893
- 图书馆亲子空间的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_tt%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%8A%A8%E6%BC%AB?/ipj
- 街区小店体验的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_tt%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%8A%A8%E6%BC%AB?/kBp
- 街区道路维护的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_tt%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%8A%A8%E6%BC%AB?/281=fik
- 科学健身方法的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_tt%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%8A%A8%E6%BC%AB?/voy=442
- 基层服务创新的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_tt%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E5%8A%A8%E6%BC%AB?/O8b=20u
- 学校体育活动的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_tt%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/758
- 城市公共自行车从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_tt%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/lvv
- 街头绿植养护的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_tt%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/3qt
- 社区阅读服务的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_tt%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/098=wpj
- 数据分析入门的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_tt%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/eqg=430
- 小区停车协商的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_tt%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/dpX=s9A
- 城市树木认养的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_tt%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/792
- 软件开发学习的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_tt%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/cpd
- 志愿服务平台的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_tt%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/JIc
- 数字便民地图的学习资源整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_tt%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/754=fvq
- 乡村公共服务的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_tt%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/ale=817
- 公共空间休憩的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_tt%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E7%94%B5?/WkB=Ayf
- 公园休闲体验的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_tt%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/307
- 消防知识宣传的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_tt%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/zkf
- 生活垃圾减量的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_tt%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/kb4
- 社区公共议事中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_tt%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/875=pam
- 社区公共餐饮的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_tt%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/zam=700
- 社区学习活动的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_tt%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/5X8=Qof
- 居家防滑改造的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_tt%E5%BD%A9-APP_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/770
- 家庭安全提示的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_tt%E5%BD%A9-APP_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/hpd
- 儿童户外活动的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_tt%E5%BD%A9-APP_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/qTx
- 社区停车服务从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_tt%E5%BD%A9-APP_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/447=hzl
- 老年智能设备的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_tt%E5%BD%A9-APP_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/yxo=167
- 儿童运动体验的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_tt%E5%BD%A9-APP_%E7%BD%91%E6%98%93%E6%8E%A2%E5%BA%97?/JR9=roj
- 社区文化节活动的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_tt%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%83%AD%E6%A6%9C?/342
- 校园社团活动的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_tt%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%83%AD%E6%A6%9C?/irs
- 乡村公共文化的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_tt%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%83%AD%E6%A6%9C?/5TF
- 社区停车服务的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_tt%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%83%AD%E6%A6%9C?/054=qht
- 社区老年食堂的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_tt%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%83%AD%E6%A6%9C?/fgg=234
- 公益活动组织的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_tt%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%83%AD%E6%A6%9C?/DUi=A4l
- 节假日出行安排的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_tt%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%B8%93%E9%A2%98?/759
- 社区便利生活的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_tt%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%B8%93%E9%A2%98?/nzt
- 城市绿色交通的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_tt%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%B8%93%E9%A2%98?/PZz
- 社区垃圾分类的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_tt%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%B8%93%E9%A2%98?/300=xur
- 数字公共文化的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_tt%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%B8%93%E9%A2%98?/nzs=471
- 社区安全巡查的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_tt%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E4%B8%93%E9%A2%98?/bLS=o1U
- 社区志愿服务的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_tt%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E7%BB%BC%E8%89%BA?/408
- 传统手工艺体验的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_tt%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E7%BB%BC%E8%89%BA?/ano
- 无障碍出行的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_tt%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E7%BB%BC%E8%89%BA?/6IS
- 居民健康教育的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_tt%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E7%BB%BC%E8%89%BA?/727=usf
- 家庭环保行动的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_tt%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E7%BB%BC%E8%89%BA?/ywd=422
- 城市适老服务的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_tt%E5%BD%A9-%E7%99%BB%E5%BD%95_%E8%B1%86%E7%93%A3%E7%BB%BC%E8%89%BA?/RMQ=SAh
- 数字创意课程的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_tt%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E5%AE%9E%E5%BD%95?/368
- 城市共享单车的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_tt%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E5%AE%9E%E5%BD%95?/fsf
- 数字档案服务从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_tt%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E5%AE%9E%E5%BD%95?/poO
- 城市空气科普的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_tt%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E5%AE%9E%E5%BD%95?/957=gyx
- 社区共享书架的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_tt%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E5%AE%9E%E5%BD%95?/lyg=612
- 节假日出行安排的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_tt%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E5%AE%9E%E5%BD%95?/H72=XUp
- 城市便民驿站的学习资源整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_tt%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/044
- 生活垃圾回收的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_tt%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/dnf
- 社区公共议事的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_tt%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/J1v
- 节气饮食文化的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_tt%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/273=tab
- 社区家校合作的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_tt%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/xqq=318
- 乡村电商实践的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_tt%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/RQk=el2
- 地方民俗记录的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_tt%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/988
- 家庭阅读计划的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_tt%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/ljy
- 街区更新实践的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_tt%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/cuZ
- 公共空间照明的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_tt%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/589=cwt
- 公共交通信息服务的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_tt%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/hwv=612
- 公益活动组织的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_tt%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/XWX=3A4
- 社区快递服务的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_tt%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%AF%BB%E4%B9%A6?/230
- 终身学习资源的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_tt%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%AF%BB%E4%B9%A6?/vxj
- 租房信息服务的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_tt%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%AF%BB%E4%B9%A6?/WDT
- 社区文化节活动的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_tt%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%AF%BB%E4%B9%A6?/071=soi
- 社区菜市场服务的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_tt%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%AF%BB%E4%B9%A6?/rdv=706
- 社区消防演练的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_tt%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%AF%BB%E4%B9%A6?/Zg5=UWW
- 社区便民集市的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_tt%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/384
- 地方美食文化的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_tt%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/bdx
- 本地历史资料的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_tt%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/Z7D
- 城市建设科普的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_tt%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/005=txt
- 灵活就业交流的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_tt%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/psa=518
- 城市公共空间的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_tt%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/Myh=4ZQ
- 机器人科普活动从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_tt%E5%BD%A9-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%A5%BC%E5%B8%82?/569
- 读书会组织的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_tt%E5%BD%A9-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%A5%BC%E5%B8%82?/emy
- 校园节能行动的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_tt%E5%BD%A9-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%A5%BC%E5%B8%82?/VHG
- 社区手工活动的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_tt%E5%BD%A9-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%A5%BC%E5%B8%82?/504=ljd
- 乡村休闲旅游的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_tt%E5%BD%A9-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%A5%BC%E5%B8%82?/nae=132
- 信息无障碍体验的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_tt%E5%BD%A9-%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%A5%BC%E5%B8%82?/FZh=pyH
- 数字生活课堂的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_VR%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E7%89%A9?/696
- 社区协商议事的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_VR%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E7%89%A9?/ran
- 社区公共议事的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_VR%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E7%89%A9?/5Tp
- 劳动教育实践的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_VR%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E7%89%A9?/821=rur
- 健康步道使用的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_VR%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E7%89%A9?/kpn=710
- 城市基础设施有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_VR%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E7%89%A9?/VxN=vZS
- 城市公共自行车的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_VR%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/562
- 小区电梯维护的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_VR%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/ebf
- 全民阅读推广的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_VR%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/k7f
- 远程协作工具的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_VR%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/537=zwu
- 家庭科学教育的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_VR%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/lse=654
- 家庭饮食安排的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_VR%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/LHw=dT7
- 网络安全教育的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_VR%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/682
- 社区生活指南的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_VR%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/zbv
- 社区文化节活动的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_VR%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/yNw
- 城市便民驿站的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_VR%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/956=pgj
- 公共设施使用的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_VR%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/uic=739
- 便民服务地图的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_VR%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%B4%A2%E7%BB%8F?/HhB=e16
- 小区停车协商的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_VR%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/545
- 农业科普体验的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_VR%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/moy
- 家庭园艺实践的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_VR%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/k2p
- 低碳社区实践的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_VR%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/942=ynl
- 租房信息服务的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_VR%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/iqc=706
- 口袋公园建设的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_VR%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%B5%84%E8%AE%AF?/XLZ=R5O
- 城市公共空间的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_VR%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%95%B0%E7%A0%81?/187
- 社区运动空间中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_VR%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%95%B0%E7%A0%81?/xnd
- 生活垃圾回收的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_VR%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%95%B0%E7%A0%81?/5GT
- 智能家居应用的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_VR%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%95%B0%E7%A0%81?/669=sxp
- 无障碍出行的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_VR%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%95%B0%E7%A0%81?/bau=788
- 数字课堂应用的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_VR%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%AC%E4%B8%9C%E6%95%B0%E7%A0%81?/px9=n4u
- 城市微更新实践的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_VR%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/368
- 家庭网络使用的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_VR%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/qxl
- 老年友好服务的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_VR%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/KoG
- 农产品品牌传播的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_VR%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/228=zse
- 全民健身活动的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_VR%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/mbr=464
- 城市公共自行车的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_VR%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/bUr=90c
- 社区故事采集的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_VR%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/218
- 社区菜市场服务的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_VR%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/piq
- 城乡交流活动的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_VR%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/q6i
- 城市体育设施的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_VR%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/224=lhw
- 生活垃圾减量的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_VR%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/tur=527
- 学校体育活动从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_VR%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%B4%E6%9D%A1%E6%8A%95%E8%B5%84?/iNv=qZk

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
