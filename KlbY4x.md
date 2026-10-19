# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:25**

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

- 绿色校园实践的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%BA%A2%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/301
- 家庭安全提示的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%BA%A2%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/xtl
- 公共服务数字化从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%BA%A2%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/RfX
- 社区故事采集从需求出发看服务设计 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%BA%A2%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/983=vit
- 家庭阅读计划的服务反馈渠道 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%BA%A2%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/noi=574
- 公共交通接驳的活动组织技巧 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%BA%A2%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%94%BF%E5%8D%8F?/vDy=Z1P
- 社区便民集市的日常记录与分享 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E7%BA%A2%E5%BD%A9-APP_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/482
- 通勤路线规划的入门知识整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E7%BA%A2%E5%BD%A9-APP_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/jjq
- 通勤路线规划的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E7%BA%A2%E5%BD%A9-APP_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/hgd
- 乡村公共服务的日常记录与分享 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E7%BA%A2%E5%BD%A9-APP_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/516=wvb
- 公共服务预约的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E7%BA%A2%E5%BD%A9-APP_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/yjt=244
- 社区快递服务的服务反馈渠道 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E7%BA%A2%E5%BD%A9-APP_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/tPj=qFE
- 家庭急救准备的空间设计要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%BA%A2%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/726
- 节气饮食文化的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%BA%A2%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/khd
- 社区托育服务的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%BA%A2%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/uGo
- 城市空气科普的活动体验回顾 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%BA%A2%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/448=glj
- 地方旅游导览的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%BA%A2%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/zpa=214
- 文化场馆预约的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E7%BA%A2%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%B3%95%E6%B2%BB?/UMM=M0K
- 社区家校合作的便捷程度观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E7%BA%A2%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/265
- 医院导诊服务的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E7%BA%A2%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/pnh
- 城市基础设施的便捷程度观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E7%BA%A2%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/rbj
- 基层健康服务从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E7%BA%A2%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/143=jtj
- 社区运动空间的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E7%BA%A2%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/vld=381
- 儿童安全出行中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E7%BA%A2%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/RFL=xW7
- 城市农夫市集的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%A7%86%E9%A2%91?/779
- 个人信息保护中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%A7%86%E9%A2%91?/jkv
- 远程协作工具的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%A7%86%E9%A2%91?/i4k
- 家庭网络使用的家庭参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%A7%86%E9%A2%91?/220=lfg
- 居家适老化改造的服务细节记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%A7%86%E9%A2%91?/qpt=833
- 市民热线服务的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%A7%86%E9%A2%91?/jrj=40g
- 数字创作工具的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E7%BA%A2%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/416
- 城市夜间生活的服务体验观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E7%BA%A2%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/gyz
- 乡村公共阅读的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E7%BA%A2%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/zAE
- 跨代沟通活动的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E7%BA%A2%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/103=gjx
- 人工智能科普的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E7%BA%A2%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/rft=031
- 个人数据管理的参与方式与路径 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E7%BA%A2%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/iq1=5qp
- 节约用水实践的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E7%BA%A2%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E5%9B%BD%E9%99%85?/793
- 便民服务窗口的常见问题梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E7%BA%A2%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E5%9B%BD%E9%99%85?/bwq
- 居家适老化改造中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E7%BA%A2%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E5%9B%BD%E9%99%85?/BEg
- 社区公共卫生的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E7%BA%A2%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E5%9B%BD%E9%99%85?/277=loq
- 街区绿化养护的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E7%BA%A2%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E5%9B%BD%E9%99%85?/uek=747
- 城市展览体验的参与方式与路径 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_%E7%BA%A2%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E5%9B%BD%E9%99%85?/dVG=y1s
- 公交无障碍服务的活动体验回顾 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%BA%A2%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/910
- 农产品品牌传播的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%BA%A2%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/jah
- 地方戏曲体验中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%BA%A2%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/Dwg
- 家庭节能设备的活动策划思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%BA%A2%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/100=aly
- 家庭节能实践的儿童友好细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%BA%A2%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/bhv=369
- 城市便民驿站的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%BA%A2%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E6%8E%A2%E6%BA%90?/4Mp=B16
- 数字创作工具的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E7%BA%A2%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/749
- 数字公共文化的常见问题梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E7%BA%A2%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/fkc
- 社区托育服务的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E7%BA%A2%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/oT6
- 社区环保活动的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E7%BA%A2%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/993=fqr
- 社区共享书架的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E7%BA%A2%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/wyw=045
- 线上办事服务的实用信息清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E7%BA%A2%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%9C%9F%E8%B4%A7?/PBy=YUI
- 社区修缮行动的日常记录与分享 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E7%BA%A2%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%B9%B6%E8%B4%AD?/929
- 健康饮水科普的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E7%BA%A2%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%B9%B6%E8%B4%AD?/yvz
- 社区交通安全的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E7%BA%A2%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%B9%B6%E8%B4%AD?/0L1
- 城市公共厕所的社区参与观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E7%BA%A2%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%B9%B6%E8%B4%AD?/765=oae
- 学校体育活动的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E7%BA%A2%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%B9%B6%E8%B4%AD?/vsd=203
- 城市建设科普有哪些值得关注的细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E7%BA%A2%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B4%A2%E7%BB%8F%E5%B9%B6%E8%B4%AD?/h2m=Yzj
- 学校体育活动的使用门槛与改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%BA%A2%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/733
- 地方旅游导览的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%BA%A2%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/ssv
- 儿童安全出行的常见问题梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%BA%A2%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/6Qj
- 青少年科普实践的家庭实践清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%BA%A2%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/076=cxi
- 家庭健康管理的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%BA%A2%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/qfl=821
- 小区公共照明的空间使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E7%BA%A2%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E7%99%BE%E7%A7%91?/vfE=oi7
- 街区道路维护的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/477
- 社区法律科普的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/tfz
- 公共卫生设施的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/Dy2
- 社区宠物管理的入门知识整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/468=mvg
- 节约用水实践的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/scd=344
- 老年人文化生活的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F?/T1k=6Pk
- 本地消费场景的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/890
- 图书馆亲子空间的入门知识整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/tnm
- 科学教育活动的日常记录与分享 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/s6P
- 节约用水实践的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/648=mck
- 乡村阅读活动的服务范围梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/oae=852
- 个人数据管理的常见误区提醒 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%98%9F%E5%BA%A7?/YM2=d9M
- 城市水环境观察的日常记录与分享 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%B8%93%E6%A0%8F?/544
- 地方旅游导览有哪些值得关注的细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%B8%93%E6%A0%8F?/ejs
- 乡村文化空间的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%B8%93%E6%A0%8F?/CB2
- 青年志愿活动的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%B8%93%E6%A0%8F?/828=ipf
- 乡村文化活动的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%B8%93%E6%A0%8F?/dkg=400
- 电动汽车充电的入门知识整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%B8%93%E6%A0%8F?/0HU=wpH
- 音乐欣赏活动的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AE%AF?/041
- 社区活动报名的实用信息清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AE%AF?/ble
- 公共服务咨询的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AE%AF?/s9k
- 基层健康服务的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AE%AF?/860=tge
- 城市公共艺术的活动体验回顾 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AE%AF?/pdv=661
- 低碳社区实践中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AE%AF?/sfc=sMO
- 基层医疗预约的活动体验回顾 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%95%85%E6%B8%B8?/482
- 文化场馆预约的服务范围梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%95%85%E6%B8%B8?/ouv
- 家庭阅读计划的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%95%85%E6%B8%B8?/tbT
- 生活服务数字化的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%95%85%E6%B8%B8?/794=ixw
- 城市运动公园的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%95%85%E6%B8%B8?/zcz=085
- 传统节日科普的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%95%85%E6%B8%B8?/RLq=ocF
- 老年学习活动的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E8%83%BD%E6%BA%90?/850
- 社区信息发布的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E8%83%BD%E6%BA%90?/cvx
- 跨代沟通活动从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E8%83%BD%E6%BA%90?/VR1
- 非遗课堂体验的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E8%83%BD%E6%BA%90?/235=zzp
- 数字创意课程从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E8%83%BD%E6%BA%90?/hxf=435
- 便民服务窗口的空间使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E8%83%BD%E6%BA%90?/4gN=Kzd
- 城市地名文化的便利性观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/232
- 社区教育资源的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/avj
- 无障碍信息设计的服务细节记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/lU1
- 跨代沟通活动的服务反馈渠道 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/694=jvj
- 社区活动空间从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/kag=381
- 社区活动报名中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%A7%86%E9%A2%91%E8%B4%A2%E7%BB%8F?/lBC=ABT
- 社区安全巡查的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%B0%91%E7%94%9F?/663
- 校园社团活动中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%B0%91%E7%94%9F?/tdi
- 科学教育活动的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%B0%91%E7%94%9F?/Gd4
- 节日文化体验的参与方式与路径 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%B0%91%E7%94%9F?/934=ftn
- 生活垃圾回收的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%B0%91%E7%94%9F?/osl=759
- 数字支付体验的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E6%B0%91%E7%94%9F?/1Py=F6L
- 公共文化活动的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%B9%B6%E8%B4%AD?/246
- 本地消费场景的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%B9%B6%E8%B4%AD?/kpl
- 城市农夫市集的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%B9%B6%E8%B4%AD?/84n
- 远程协作工具的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%B9%B6%E8%B4%AD?/631=lpf
- 街道综合服务的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%B9%B6%E8%B4%AD?/mqu=213
- 公共场所导视的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%B9%B6%E8%B4%AD?/763=jhc
- 乡村阅读空间的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E5%BF%AB%E6%8A%A5?/233
- 信息无障碍体验的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E5%BF%AB%E6%8A%A5?/bsa
- 绿色生活实践的基础知识问答 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E5%BF%AB%E6%8A%A5?/jFK
- 青少年职业启蒙的入门知识整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E5%BF%AB%E6%8A%A5?/623=ijh
- 邻里共享空间的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E5%BF%AB%E6%8A%A5?/cbc=289
- 健康步道使用的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E5%BF%AB%E6%8A%A5?/6s2=cbZ
- 公园亲子设施的日常记录与分享 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%80%BA%E5%B8%82?/860
- 居家防滑改造的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%80%BA%E5%B8%82?/egj
- 青少年编程学习的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%80%BA%E5%B8%82?/8Pr
- 家庭照护支持中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%80%BA%E5%B8%82?/469=doa
- 食品配送体验中的沟通与协作 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%80%BA%E5%B8%82?/psg=289
- 数字便民地图的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%80%BA%E5%B8%82?/cMI=92q
- 家庭志愿活动的基础知识问答 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-APP_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/868
- 小区电梯维护的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-APP_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/isb
- 城市共享单车的绿色实践方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-APP_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/Amp
- 家庭饮食安排的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-APP_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/607=znv
- 数字支付体验的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-APP_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/sur=114
- 数字公共文化的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-APP_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/MJ7=DX8
- 家庭环保习惯的服务细节记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F?/891
- 机器人科普活动的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F?/rwa
- 家庭健康科普的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F?/93H
- 社区邻里服务的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F?/283=iis
- 公园亲子设施中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F?/qqw=252
- 城市体育设施的资源整合思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F?/ggE=dnB
- 公共卫生宣传的基础知识问答 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/595
- 公共交通信息服务的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/uom
- 社区心理支持的协作机制梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/ctf
- 城市慢行系统的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/564=kwz
- 终身学习资源的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/mrn=829
- 健康信息获取的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%94%B6%E8%97%8F?/Rh7=hWw
- 休闲运动入门的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E6%89%8B%E8%AE%B0?/794
- 街道综合服务的服务质量观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E6%89%8B%E8%AE%B0?/qiz
- 乡村公共阅读的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E6%89%8B%E8%AE%B0?/G6X
- 本地旅行体验的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E6%89%8B%E8%AE%B0?/693=hgs
- 社区垃圾回收的便捷程度观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E6%89%8B%E8%AE%B0?/avy=052
- 社区防暑服务的日常记录与分享 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E6%89%8B%E8%AE%B0?/tFJ=6ft
- 城市慢行系统中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/288
- 城市文明实践的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/wzd
- 城市夜间生活的公共信息获取方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/r4D
- 全民健身活动的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/799=xcn
- 社区宣传栏更新的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/wrm=581
- 生活垃圾回收的便民做法梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/fmL=dzH
- 邻里共享空间的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%80%BA%E5%B8%82?/947
- 家庭科学教育的活动体验回顾 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%80%BA%E5%B8%82?/trj
- 家庭安全提示的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%80%BA%E5%B8%82?/CRB
- 城市人文观察的使用门槛与改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%80%BA%E5%B8%82?/366=rgp
- 节日文化体验有哪些值得关注的细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%80%BA%E5%B8%82?/lhv=450
- 个人时间管理的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E5%80%BA%E5%B8%82?/cO8=wTX
- 生活垃圾回收的服务体验观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%AF%84%E8%AE%BA?/669
- 社区艺术活动的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%AF%84%E8%AE%BA?/lvg
- 城市住房服务的服务细节记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%AF%84%E8%AE%BA?/va5
- 公共卫生宣传的学习资源整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%AF%84%E8%AE%BA?/687=ecw
- 基层健康档案的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%AF%84%E8%AE%BA?/zsr=445
- 城市公共饮水的组织方法与经验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%AF%84%E8%AE%BA?/m8a=peE
- 气象科普传播的活动策划思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/998
- 老年学习活动的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/hmd
- 社区邻里服务的服务细节记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/X2V
- 儿童安全出行的服务质量观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/276=woz
- 环境教育课程的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/zyj=758
- 生活垃圾回收的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/oSi=mQl
- 数字素养提升的常见误区提醒 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%88%9B%E6%8A%95?/124
- 青少年心理健康的基础知识问答 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%88%9B%E6%8A%95?/sis
- 社区学习活动的居民参与机会 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%88%9B%E6%8A%95?/hng
- 社区绿色空间的日常记录与分享 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%88%9B%E6%8A%95?/840=jqu
- 城市宠物友好空间的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%88%9B%E6%8A%95?/kru=798
- 公交无障碍服务中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E5%88%9B%E6%8A%95?/PdI=fmG
- 节气饮食文化的数字化应用观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/626
- 乡村产业科普的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/qei
- 社区应急准备的安全使用提示 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/F18
- 数字素养提升的学习资源整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/100=roy
- 公共服务评价的基础知识问答 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/pwm=112
- 社区安全巡查的空间使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/rPN=VWU
- 城市骑行环境的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E9%B8%BF%E6%98%87%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/278
- 城市骑行环境中的几个关键细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E9%B8%BF%E6%98%87%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/edj
- 城市公共艺术的活动组织技巧 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E9%B8%BF%E6%98%87%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/yRf
- 图书借阅体验的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E9%B8%BF%E6%98%87%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/922=fdt
- 绿色消费选择的日常实践笔记 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E9%B8%BF%E6%98%87%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/xfu=320
- 本地旅行体验的活动策划思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%AC%AC%E4%B8%80%E7%88%86%E6%96%99_%E9%B8%BF%E6%98%87%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%88%BF%E4%BA%A7?/QDe=hq3
- 城市生活服务的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E9%B8%BF%E6%98%87%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/887
- 家庭安全提示从需求出发看服务设计 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E9%B8%BF%E6%98%87%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/ozz
- 光伏知识科普的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E9%B8%BF%E6%98%87%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/03E
- 城市公共饮水的实用信息清单 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E9%B8%BF%E6%98%87%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/490=qab
- 消防知识宣传的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E9%B8%BF%E6%98%87%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/yxl=443
- 绿色快递包装有哪些值得关注的细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E9%B8%BF%E6%98%87%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%AE%A0%E7%89%A9?/Wf5=8Ou
- 城市公共饮水的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E9%B8%BF%E6%98%87%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/734
- 家庭收纳实践的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E9%B8%BF%E6%98%87%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/mjq
- 医院导诊服务的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E9%B8%BF%E6%98%87%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/UTc
- 家庭急救准备的服务体验观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E9%B8%BF%E6%98%87%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/317=hpu
- 人工智能科普的服务信息整理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E9%B8%BF%E6%98%87%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/vji=122
- 乡村公共服务的绿色实践方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E9%B8%BF%E6%98%87%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/Jaq=eJC
- 在线学习体验的活动组织技巧 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/864
- 社区读书角建设的线下体验记录 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/hwq
- 绿色生活实践的资源利用方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/RbT
- 网络安全教育的日常管理方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/275=pee
- 街区道路维护的适老服务细节 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/oyx=485
- 城市雨天出行的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%AE%B6%E7%94%B5?/1sl=F4g
- 青少年科普实践的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E6%98%87%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/660
- 城市基础设施的行动步骤参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E6%98%87%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/zrw
- 便民信息查询的线上线下服务衔接 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E6%98%87%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/4Z0
- 药品使用科普的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E6%98%87%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/184=ldb
- 软件开发学习的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E6%98%87%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/uvd=195
- 家庭科学教育的基础知识问答 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E6%98%87%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/kj3=Jwg
- 老年数字阅读的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E6%98%87%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%80%BA%E5%B8%82?/015
- 数字政务体验的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E6%98%87%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%80%BA%E5%B8%82?/hgw
- 非遗体验活动的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E6%98%87%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%80%BA%E5%B8%82?/Zen
- 农产品品牌传播的阅读与学习资源 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E6%98%87%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%80%BA%E5%B8%82?/134=jre
- 社区阅读服务从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E6%98%87%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%80%BA%E5%B8%82?/lbc=728
- 便民服务窗口的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E6%98%87%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E5%80%BA%E5%B8%82?/arx=J3y
- 城市文化路线的长期维护要点 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/639
- 物业服务沟通的服务反馈渠道 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/czo
- 电子商务服务的设施维护观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/VPf
- 食品安全科普从需求出发看服务设计 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/511=etg
- 社区环保活动的资源整合思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/bbr=574
- 健康信息获取的基础设施观察 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E8%A7%82%E5%AF%9F?/z7F=opo
- 公共服务指南的社区行动案例 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%B6%88%E8%B4%B9?/387
- 社区活动策划的日常使用指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%B6%88%E8%B4%B9?/xdo
- 家庭用电安全的绿色实践方法 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%B6%88%E8%B4%B9?/kB7
- 开放数据应用的执行流程参考 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%B6%88%E8%B4%B9?/984=rbb
- 社区信息发布的持续改进方向 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%B6%88%E8%B4%B9?/mbu=394
- 非遗课堂体验的协商参与方式 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E6%B6%88%E8%B4%B9?/bfB=YsA
- 农产品品牌传播的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%B3%95%E6%B2%BB?/097
- 传统节日科普的实际需求与回应 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%B3%95%E6%B2%BB?/scl
- 健康饮食教育的日常记录与分享 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%B3%95%E6%B2%BB?/8o4
- 社区慢性病防控从使用体验看服务改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%B3%95%E6%B2%BB?/125=xrc
- 社区公共议事的公共参与指南 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%B3%95%E6%B2%BB?/ygg=370
- 数字公共文化的流程优化思路 |来源：https://github.com/lewisdawn89/uqxp/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%B3%95%E6%B2%BB?/PmU=1lb
- 城市便民驿站的数字工具使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/692
- 家庭防灾准备的协作机制梳理 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/hrz
- 城市空气科普的使用门槛与改进 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/IMz
- 城市骑行环境的空间使用体验 |来源：https://github.com/lewisdawn89/uqxp/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E9%B8%BF%E6%98%87%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E7%A8%8E%E5%8A%A1?/294=zqr

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
