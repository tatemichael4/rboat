# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:22**

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

- 线上办事服务的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/986
- 社区邻里服务的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/ccd
- 乡村文化活动的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/rwb
- 社区学习活动的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/342=dje
- 社区文化传播的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/hnd=876
- 绿色建筑理念的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E8%A6%81%E9%97%BB?/WZ8=QRE
- 数字学习资源的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/829
- 乡村教育资源的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/qyh
- 科学信息获取的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/DKF
- 社区信息发布的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/496=bly
- 街道综合服务的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/yyn=383
- 家庭养老规划的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%A7%82%E5%AF%9F%E8%B4%A2%E7%BB%8F?/drp=ucj
- 儿童友好空间的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%B6%E8%97%8F?/727
- 读书会组织的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%B6%E8%97%8F?/xmd
- 科学健身方法的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%B6%E8%97%8F?/wBS
- 地方民俗记录的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%B6%E8%97%8F?/286=mwb
- 科学运动指导的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%B6%E8%97%8F?/ugj=022
- 家庭收纳实践的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%B6%E8%97%8F?/8cT=Qra
- 城市便民驿站的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/235
- 传统节日科普的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/idx
- 乡村公共服务的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/42D
- 乡村公共文化的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/422=yhq
- 环境监测科普的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/oqg=527
- 绿色校园实践的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/jww=5qj
- 公园无障碍服务的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/381
- 亲子科普活动的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/stt
- 社区心理支持的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/Ex8
- 公共健身器材的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/906=sdz
- 社区家校合作的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/pet=275
- 社区设施共享中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/Fgh=rK4
- 公共图书馆服务的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/912
- 乡村生活观察的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/xzs
- 公园亲子设施的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/zSi
- 社区志愿服务的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/983=mpe
- 城市适老服务的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/zzd=965
- 光伏知识科普的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E8%88%86%E6%83%85?/hp9=PLs
- 社区家政服务的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/992
- 公共服务数字化的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/mxw
- 青少年编程学习的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/qop
- 社区绿色空间的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/326=bvd
- 基层健康档案的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/otc=427
- 新能源出行的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%99%BE%E7%A7%91?/YjG=QwG
- 青少年心理健康的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/495
- 家庭用电安全的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/iri
- 基层健康服务的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/zKk
- 食品配送体验的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/998=uyz
- 科普展览体验的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/oar=761
- 数字公共文化的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/qaJ=z2Y
- 食品配送体验的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/975
- 乡村生活观察的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/ahb
- 校园阅读活动的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/rO2
- 城市可持续生活的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/392=zpm
- 乡村生活观察的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/ers=054
- 社区菜市场服务有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/c9Y=4GN
- 数字公共文化的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E7%BB%BC%E8%89%BA?/346
- 公共服务沟通的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E7%BB%BC%E8%89%BA?/jgj
- 文化遗产保护科普的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E7%BB%BC%E8%89%BA?/dLL
- 图书馆亲子空间的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E7%BB%BC%E8%89%BA?/730=wvf
- 社区健康讲座的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E7%BB%BC%E8%89%BA?/xvn=976
- 信息无障碍体验的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9088%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E7%BB%BC%E8%89%BA?/9Lq=ExX
- 城市微更新实践的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%9C%9B?/660
- 家庭科学教育的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%9C%9B?/xpj
- 开源技术交流的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%9C%9B?/fdj
- 青年志愿活动从需求出发看服务设计 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%9C%9B?/328=eeq
- 家庭网络使用的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%9C%9B?/jea=997
- 乡村教育资源的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E5%9B%9E%E6%9C%9B?/na6=wfB
- 消防知识宣传的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/499
- 乡村公共服务的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/jzx
- 绿色生活实践的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/Hk3
- 本地消费场景的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/745=hhy
- 灵活就业交流的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/gei=868
- 农村环境治理的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%AF%8D%E5%A9%B4?/b12=h5h
- 亲子科普活动的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%90%86%E8%B4%A2?/432
- 校园社团活动的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%90%86%E8%B4%A2?/xur
- 本地历史资料的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%90%86%E8%B4%A2?/8f4
- 节能家电使用的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%90%86%E8%B4%A2?/611=gkp
- 基层服务创新中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%90%86%E8%B4%A2?/ztx=803
- 老年人日常照护的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E7%90%86%E8%B4%A2?/F6B=iNb
- 开源技术交流的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/596
- 数字地图应用的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/xbl
- 家庭理财科普的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/xbx
- 线上阅读资源的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/431=aft
- 社区修缮行动中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/bce=992
- 城市博物馆服务的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%81%A5%E8%BA%AB?/gwT=Ghk
- 无障碍出行的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/664
- 新能源出行的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/mme
- 社区庭院绿化的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/S7n
- 公交站点体验的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/890=xal
- 文明养宠科普的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/gfm=564
- 数字艺术创作从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%9F%8E%E4%BA%8B?/AM1=YgU
- 数字便民地图的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/453
- 运动安全知识的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/vht
- 地方戏曲体验的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/FTu
- 市民热线服务的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/004=dif
- 城市应急广播的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/duh=075
- 数字创意课程的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/Vfz=jED
- 公共空间安全的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/279
- 城市休闲步道的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/tij
- 社区慢性病防控的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/xa9
- 城市空气科普的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/412=bgo
- 无障碍出行的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/pux=811
- 城市应急科普的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/smj=YxR
- 老年人文化生活的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E6%97%B6%E6%8A%A5?/850
- 软件开发学习的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E6%97%B6%E6%8A%A5?/phi
- 健康饮食教育的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E6%97%B6%E6%8A%A5?/Hyv
- 街区绿化养护的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E6%97%B6%E6%8A%A5?/570=sll
- 物业服务沟通的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E6%97%B6%E6%8A%A5?/jtz=892
- 绿色快递包装的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E6%97%B6%E6%8A%A5?/qYM=ZZl
- 社区协商议事的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/578
- 本地消费场景的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/ldy
- 社区阅读服务的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/INp
- 公共空间安全的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/264=mjq
- 租房信息服务的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/yua=539
- 社区托育服务的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%92%AD%E6%8A%A5?/A4Y=MFz
- 机器学习入门的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/310
- 家庭节能实践的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/fpx
- 城市体育设施的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/oSK
- 地方美食文化中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/360=cpi
- 城市应急广播的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/hqo=600
- 本地旅行体验的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E8%A7%82%E7%82%B9?/f1A=ml2
- 文明养宠科普的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/716
- 数字素养提升的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/nyb
- 生活服务数字化的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/f6x
- 科学观察活动的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/452=yfb
- 绿色建筑理念的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/rdt=150
- 公共场所导视的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%B9%B6%E8%B4%AD?/JQb=h2u
- 青年志愿活动的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/338
- 生活服务数字化的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/fke
- 家庭用电安全的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/14F
- 开放式学习空间的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/760=qjz
- 线上阅读资源的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/mmu=415
- 网络信息辨识的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-APP_%E8%84%89%E8%84%89%E6%94%BF%E7%AD%96?/B7l=FLe
- 社区科普课堂中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%9B%9E%E6%9C%9B?/001
- 亲子阅读活动的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%9B%9E%E6%9C%9B?/txo
- 城市适老服务的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%9B%9E%E6%9C%9B?/YFs
- 城市建设科普的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%9B%9E%E6%9C%9B?/751=iht
- 健康饮水科普的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%9B%9E%E6%9C%9B?/vfk=989
- 电动汽车充电的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E5%9B%9E%E6%9C%9B?/vft=Ni3
- 城市农夫市集的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91?/361
- 本地旅行体验的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91?/xnc
- 无障碍信息设计的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91?/vKh
- 软件开发学习的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91?/683=yjb
- 公共场所导视的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91?/mzy=491
- 社区快递服务中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91?/U89=Yov
- 社区文化节活动的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/560
- 数字阅读服务的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/qyq
- 科学信息获取的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/5jd
- 便民信息查询从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/778=rxe
- 新能源知识普及的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/eto=700
- 家庭安全提示中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/Gpl=QIF
- 社区垃圾回收的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/245
- 基层健康档案的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/mhr
- 开放式学习空间的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/GOv
- 城市绿道建设的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/749=xqk
- 家庭环保行动的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/skx=807
- 科技馆参观体验的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/eMe=Fys
- 数字便民地图的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E8%BF%B0%E8%AF%84?/006
- 市民意见收集的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E8%BF%B0%E8%AF%84?/hab
- 数字阅读服务的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E8%BF%B0%E8%AF%84?/yXH
- 乡村公共服务的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E8%BF%B0%E8%AF%84?/639=vqt
- 城市夜间照明中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E8%BF%B0%E8%AF%84?/udy=710
- 社区修缮行动的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E8%BF%B0%E8%AF%84?/HLE=AOb
- 农产品品牌传播的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/259
- 社区家校合作的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/pfv
- 公共服务数字化的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/amZ
- 儿童运动体验的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/575=ldb
- 社区家政服务有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/vin=335
- 城市应急广播的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/cr6=nNV
- 生活垃圾减量的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/062
- 社区教育资源的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/vks
- 垃圾分类指导的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/rJW
- 家庭理财科普的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/307=fhl
- 跨代沟通活动的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/hsz=045
- 绿色出行服务从需求出发看服务设计 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/9OM=5Wv
- 环境监测科普的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/582
- 乡村休闲旅游的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/pqb
- 家庭环保习惯有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/QZM
- 社区心理支持的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/202=mqb
- 课后服务体验的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/vvj=792
- 电子商务服务的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E7%90%86%E8%B4%A2?/dxp=S3k
- 居民健康教育的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E8%88%86%E6%83%85?/488
- 数字公共文化的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E8%88%86%E6%83%85?/pzj
- 老年数字阅读的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E8%88%86%E6%83%85?/4i0
- 社区文化节活动的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E8%88%86%E6%83%85?/007=cyp
- 社区科普课堂的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E8%88%86%E6%83%85?/zdf=726
- 市民意见收集的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E8%88%86%E6%83%85?/XNe=FcE
- 绿色快递包装的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_360%E6%97%B6%E8%AE%AF?/240
- 校园安全教育的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_360%E6%97%B6%E8%AE%AF?/clb
- 邻里互助活动的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_360%E6%97%B6%E8%AE%AF?/iUq
- 户外活动组织中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_360%E6%97%B6%E8%AE%AF?/598=uen
- 无障碍出行的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_360%E6%97%B6%E8%AE%AF?/kgd=715
- 终身学习资源的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_360%E6%97%B6%E8%AE%AF?/GPu=4ry
- 青年职业探索的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%97%B6%E8%AF%84?/223
- 城市住房服务中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%97%B6%E8%AF%84?/cmw
- 城市步行友好的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%97%B6%E8%AF%84?/Sez
- 便民维修服务的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%97%B6%E8%AF%84?/648=uvv
- 乡村阅读空间的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%97%B6%E8%AF%84?/lfn=992
- 家庭陪伴活动的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%97%B6%E8%AF%84?/rRX=5Cv
- 社区家校合作的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E7%88%86%E6%96%99?/020
- 乡村生态旅游的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E7%88%86%E6%96%99?/rsm
- 居家适老化改造的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E7%88%86%E6%96%99?/obB
- 城市展览体验的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E7%88%86%E6%96%99?/026=tfs
- 绿色办公实践的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E7%88%86%E6%96%99?/htd=574
- 网络信息辨识的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_360%E7%88%86%E6%96%99?/IBK=UFp
- 社区协商议事的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%AF%84%E8%AE%BA?/133
- 公共服务评价的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%AF%84%E8%AE%BA?/wxn
- 校园社团活动的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%AF%84%E8%AE%BA?/0iX
- 全民健身活动的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%AF%84%E8%AE%BA?/151=vdn
- 网络信息辨识的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%AF%84%E8%AE%BA?/uzh=368
- 便民服务窗口的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%AF%84%E8%AE%BA?/tY2=VfX
- 城市住房服务的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/606
- 社区庭院绿化的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/wam
- 数字创作工具的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/v9w
- 传统节日科普的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/991=btl
- 无障碍信息设计的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/evy=949
- 运动安全知识的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%86%E9%A2%91?/pyo=BMz
- 城市环境志愿行动的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/039
- 科学信息获取的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/cln
- 智慧城市体验的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/Pe0
- 地方旅游导览有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/731=ttp
- 家庭安全提示的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/dhh=129
- 地方文化传播的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/2kx=0Fn
- 家庭消费规划的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E5%8A%A8%E6%BC%AB?/254
- 节假日出行安排的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E5%8A%A8%E6%BC%AB?/oiy
- 社区文化节活动的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E5%8A%A8%E6%BC%AB?/OrI
- 科学健身方法的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E5%8A%A8%E6%BC%AB?/688=suz
- 城市环境志愿行动的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E5%8A%A8%E6%BC%AB?/yhe=685
- 城市基础设施的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E5%8A%A8%E6%BC%AB?/ozK=FUx
- 环境监测科普的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/554
- 居民健康教育的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/izf
- 文化讲座服务的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/ZEk
- 青少年户外教育有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/985=mbm
- 乡村阅读活动的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/iqe=918
- 城市游园体验中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E7%A7%91%E6%8A%80?/if2=WPi
- 校园阅读活动的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/692
- 城市公共饮水的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/squ
- 社区邻里服务的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/ORo
- 气象科普传播的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/310=npo
- 家庭消费规划的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/lbe=983
- 乡村公共服务的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/5OY=L1s
- 数字便民地图的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/863
- 家庭园艺实践的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/tev
- 城市公共自行车从需求出发看服务设计 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/sj1
- 亲子科普活动中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/977=mgd
- 城市步行环境的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/myj=639
- 校园社团活动的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%95%99%E8%82%B2?/9j8=qr7
- 社区便利生活的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%A7%81%E5%8B%9F?/992
- 青少年科普实践的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%A7%81%E5%8B%9F?/gbn
- 城市社区治理的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%A7%81%E5%8B%9F?/MyC
- 居家适老化改造中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E8%B4%AD%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%A7%81%E5%8B%9F?/702=hut

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
