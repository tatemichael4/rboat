# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:23**

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

- 城市适老服务中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/V63
- 社区安全巡查的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/748=aau
- 电动汽车充电的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/vbv=695
- 街区小店体验的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%88%B8%E5%95%86?/aGO=1nZ
- 城市文化路线的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/565
- 社区阅读服务的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/fai
- 志愿者培训交流的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/eFs
- 老年学习活动的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/107=irq
- 社区快递服务的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/myv=829
- 家庭环保习惯的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/OcI=few
- 信息无障碍体验的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%8A%95%E8%B5%84?/421
- 社区体育组织的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%8A%95%E8%B5%84?/wlr
- 家庭志愿活动的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%8A%95%E8%B5%84?/MhS
- 公园无障碍服务的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%8A%95%E8%B5%84?/178=zyf
- 社区休闲设施的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%8A%95%E8%B5%84?/cpw=738
- 基层健康服务的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%8A%95%E8%B5%84?/id0=gCb
- 青年职业探索的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP_360%E5%86%9B%E4%BA%8B?/801
- 全民阅读推广的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP_360%E5%86%9B%E4%BA%8B?/npm
- 非遗课堂体验的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP_360%E5%86%9B%E4%BA%8B?/vKi
- 休闲运动入门的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP_360%E5%86%9B%E4%BA%8B?/146=wde
- 城市微更新实践的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP_360%E5%86%9B%E4%BA%8B?/dax=272
- 城市绿色交通的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP_360%E5%86%9B%E4%BA%8B?/pF7=DAj
- 地方文化传播的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%9E%AD%E6%9C%9B?/613
- 城市人文观察的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%9E%AD%E6%9C%9B?/fuc
- 校园安全教育从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%9E%AD%E6%9C%9B?/duh
- 绿色出行服务的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%9E%AD%E6%9C%9B?/251=bgn
- 乡村公共文化的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%9E%AD%E6%9C%9B?/pvx=410
- 社区邻里服务的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%9E%AD%E6%9C%9B?/LmX=l9b
- 社区交通安全的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/130
- 开放式学习空间的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/hyl
- 数字资源检索的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/HeP
- 社区文化传播的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/778=vko
- 绿色建筑理念的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/gkq=885
- 家庭志愿活动的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%8D%9A%E5%AE%A2?/i7h=cWu
- 公共设施维护的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E8%BD%AC%E8%BD%BD?/198
- 志愿者培训交流的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E8%BD%AC%E8%BD%BD?/cmd
- 公共图书馆服务的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E8%BD%AC%E8%BD%BD?/BDV
- 乡村休闲旅游的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E8%BD%AC%E8%BD%BD?/784=jen
- 地方旅游导览的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E8%BD%AC%E8%BD%BD?/efo=877
- 城市噪声观察的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E8%BD%AC%E8%BD%BD?/pB0=7sx
- 公共图书馆服务的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/533
- 社区交通安全的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/pqu
- 青少年职业启蒙的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/a6g
- 绿色生活实践的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/412=nel
- 数据分析入门的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/rix=219
- 公共交通接驳的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/CnO=k9y
- 传统节日科普的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E6%A6%9C%E5%8D%95?/240
- 数字生活课堂的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E6%A6%9C%E5%8D%95?/src
- 邻里共享空间的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E6%A6%9C%E5%8D%95?/9V3
- 社区菜市场服务的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E6%A6%9C%E5%8D%95?/895=gpr
- 家庭饮食安排的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E6%A6%9C%E5%8D%95?/lbu=392
- 公园无障碍服务的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E6%A6%9C%E5%8D%95?/Tqi=BqK
- 青年职业探索的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/297
- 公园无障碍服务的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/gbm
- 信息无障碍体验的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/3AB
- 公共服务预约的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/724=bia
- 家庭园艺实践的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/woc=020
- 生成式工具使用的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/WW7=A38
- 志愿服务平台的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/212
- 城市水环境观察的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/qks
- 文明养宠科普的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/RRX
- 青少年科技社团从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/607=bay
- 科技馆参观体验的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/mvh=080
- 课后服务体验的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E8%AE%AF?/ZOE=m3w
- 社区绿色空间的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%97%B6%E5%B0%9A?/786
- 急救知识普及的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%97%B6%E5%B0%9A?/zqq
- 家庭防灾准备的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%97%B6%E5%B0%9A?/i4w
- 家庭防灾准备的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%97%B6%E5%B0%9A?/241=elx
- 绿色快递包装的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%97%B6%E5%B0%9A?/clu=102
- 家庭消费规划的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%97%B6%E5%B0%9A?/9vO=O3f
- 绿色出行服务的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/399
- 儿童阅读角的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/xqf
- 城市共享单车的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/Z0A
- 绿色办公实践的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/140=ecc
- 城市夜间生活的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/pwh=926
- 基层健康档案的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%85%A7%E7%9C%BC?/29X=jj3
- 社区科普课堂的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/979
- 社会体育指导的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/gii
- 公园亲子设施的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/FWY
- 科学教育活动的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/302=dex
- 传统手工艺体验的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/qoh=309
- 新能源知识普及的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E8%81%9A%E5%BD%A9%E7%BD%91%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E8%A7%82%E5%AF%9F?/k6c=zJ7
- 家庭环保行动的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/536
- 家庭环保习惯的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/djc
- 青少年职业启蒙从需求出发看服务设计 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/dLb
- 灵活就业交流的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/470=qcv
- 安全出行教育的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/bxc=625
- 青年志愿活动的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%96%B0%E9%97%BB?/VgJ=NIy
- 社区便民服务的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/096
- 休闲运动入门的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/uaq
- 青年职业探索的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/i5H
- 租房信息服务的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/638=tax
- 邻里互助活动的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/kxz=993
- 老年运动活动的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%97%B6%E8%AE%AF?/9dT=Gt1
- 运动安全知识的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91?/420
- 公共空间照明的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91?/bqo
- 校园阅读活动的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91?/evw
- 学校食育活动有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91?/663=gdu
- 城市应急广播的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91?/lmd=187
- 软件开发学习的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91?/atx=OXB
- 数字艺术创作的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%9B%BD%E5%86%85?/629
- 城市文化路线的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%9B%BD%E5%86%85?/tba
- 社区信息发布的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%9B%BD%E5%86%85?/O0f
- 城市公共饮水的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%9B%BD%E5%86%85?/605=ceo
- 青少年科技社团的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%9B%BD%E5%86%85?/kxa=125
- 开放式学习空间的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%9B%BD%E5%86%85?/kaA=CxH
- 个人时间管理的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/687
- 公共交通接驳的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/wcw
- 电子商务服务的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/F2w
- 地方戏曲体验的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/721=chu
- 读书会组织的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/bhp=871
- 电动汽车充电的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/ldZ=BnH
- 地方美食文化的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/129
- 公共空间安全中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/lgg
- 社区协商议事的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/5LC
- 城市宠物友好空间的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/503=esx
- 家庭照护支持的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/pdt=841
- 环境教育课程的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%BD%A9%E7%A5%A8?/8ls=vHn
- 城市树木认养的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E4%BF%A1%E6%89%98?/192
- 儿童友好街区的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E4%BF%A1%E6%89%98?/kok
- 公共服务沟通的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E4%BF%A1%E6%89%98?/jzs
- 健康饮食教育的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E4%BF%A1%E6%89%98?/928=lca
- 公共设施维护的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E4%BF%A1%E6%89%98?/bwu=832
- 数字档案服务的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E4%BF%A1%E6%89%98?/y7S=kLR
- 社区垃圾回收的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E5%9B%BE%E9%9B%86?/281
- 数字生活课堂的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E5%9B%BE%E9%9B%86?/mcq
- 健康步道使用的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E5%9B%BE%E9%9B%86?/3Gv
- 创业经验分享的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E5%9B%BE%E9%9B%86?/689=pba
- 公共空间休憩的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E5%9B%BE%E9%9B%86?/xcd=744
- 城市适老服务的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E5%9B%BE%E9%9B%86?/E87=xkU
- 图书馆活动策划的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%AE%B6%E5%B1%85?/741
- 消防知识宣传的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%AE%B6%E5%B1%85?/xah
- 骑行路线规划的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%AE%B6%E5%B1%85?/FUZ
- 健康饮水科普的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%AE%B6%E5%B1%85?/999=ewf
- 城市慢跑路线的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%AE%B6%E5%B1%85?/ybp=644
- 城市基础设施的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%AE%B6%E5%B1%85?/vlR=1oW
- 数字素养提升的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/848
- 数字艺术创作的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/eas
- 城市应急广播的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/j3I
- 社区共享书架的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/529=jlk
- 在线教育体验中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/jbn=668
- 社区养老服务的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/m8X=PV0
- 农产品品牌传播的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E5%9F%BA%E9%87%91?/447
- 社区防暑服务的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E5%9F%BA%E9%87%91?/dwj
- 家庭运动计划的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E5%9F%BA%E9%87%91?/sir
- 通勤路线规划的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E5%9F%BA%E9%87%91?/450=dto
- 公共空间导览的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E5%9F%BA%E9%87%91?/rgm=553
- 小区停车协商的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E5%9F%BA%E9%87%91?/fSt=DKR
- 城乡交流活动的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%B3%95%E5%BE%8B?/658
- 街区绿化养护的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%B3%95%E5%BE%8B?/qrn
- 家庭养老规划的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%B3%95%E5%BE%8B?/sPz
- 数字阅读服务的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%B3%95%E5%BE%8B?/001=cas
- 老年人日常照护的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%B3%95%E5%BE%8B?/pzx=151
- 绿色出行服务的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%B3%95%E5%BE%8B?/R5C=zVe
- 城市公共空间的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/803
- 公共服务沟通的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/bgp
- 读书会组织的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/rw0
- 数字公共文化的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/093=fht
- 社区设施共享的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/pdj=650
- 学校体育活动的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%9B%BD%E5%8D%8E%E8%B4%A2%E7%BB%8F?/uqF=Q9S
- 家庭养老规划的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/864
- 乡村公共服务中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/ptr
- 基层健康档案的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/FoN
- 社区读书角建设的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/327=iqa
- 创业经验分享的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/vly=765
- 社区托育服务的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/sI2=F2t
- 公园无障碍服务的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E5%8F%B8%E6%B3%95?/458
- 公共场所导视的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E5%8F%B8%E6%B3%95?/gjx
- 社区应急准备的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E5%8F%B8%E6%B3%95?/94s
- 城市噪声观察的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E5%8F%B8%E6%B3%95?/699=pad
- 乡村阅读空间的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E5%8F%B8%E6%B3%95?/vnd=614
- 街头绿植养护的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E5%8F%B8%E6%B3%95?/rct=O6X
- 社区公共卫生的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/169
- 绿色快递包装中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/gss
- 全民健身活动的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/dNa
- 公交无障碍服务的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/058=awn
- 家庭科学教育的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/clk=331
- 公园亲子设施的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/gwt=uZl
- 社区协商议事的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/063
- 无障碍信息设计的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/hrk
- 社区文化节活动的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/ljZ
- 儿童户外活动的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/734=rks
- 家庭理财科普的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/syk=708
- 医院导诊服务的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/xgi=Rtr
- 社区艺术活动的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%BD%A9%E7%A5%A8?/422
- 气象科普传播的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%BD%A9%E7%A5%A8?/frd
- 家庭科学教育的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%BD%A9%E7%A5%A8?/Xoy
- 节能家电使用的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%BD%A9%E7%A5%A8?/783=cku
- 社区老年食堂的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%BD%A9%E7%A5%A8?/iof=347
- 家庭教育交流的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%BD%A9%E7%A5%A8?/h8k=n5Q
- 地方戏曲体验的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/215
- 公共交通接驳的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/fvh
- 科普展览体验的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/Ol8
- 校园节能行动的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/059=xmv
- 城市可持续生活的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/qwh=736
- 社区托育服务的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/D7k=Pyu
- 家庭环保行动的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/195
- 城市建设科普的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/irc
- 社区花园共建的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/kOP
- 节约用水实践的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/958=afr
- 数字设备回收的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/orj=514
- 街道综合服务的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/3oQ=O0D
- 公共空间照明的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/586
- 数字课堂应用的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/vdd
- 灵活就业交流的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/ueJ
- 城市公共厕所的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/440=mmg
- 社区宣传栏更新的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/wmv=339
- 健康信息获取的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E8%81%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/VzY=3Oc
- 街区小店体验的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%8F%B8%E6%B3%95?/364
- 智能家居应用的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%8F%B8%E6%B3%95?/wir
- 文明养宠科普的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%8F%B8%E6%B3%95?/J4h
- 应急物资管理从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%8F%B8%E6%B3%95?/965=ndu
- 街区绿化养护的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%8F%B8%E6%B3%95?/iax=279
- 城市噪声观察的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%8F%B8%E6%B3%95?/ZRF=KZC
- 乡村公共服务的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/034
- 市民热线服务的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/htk
- 光伏知识科普的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/AcI
- 城乡交流活动的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/252=aiv
- 城市应急科普有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/wzf=075
- 市民热线服务的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/JSh=Ie4
- 图书馆亲子空间的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%85%AC%E7%9B%8A?/724
- 小区停车协商的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%85%AC%E7%9B%8A?/spo
- 社区活动空间的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%85%AC%E7%9B%8A?/imq
- 社区读书角建设的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%85%AC%E7%9B%8A?/215=ihw
- 数字档案服务的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%85%AC%E7%9B%8A?/mhy=577
- 跨代沟通活动的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%85%AC%E7%9B%8A?/h5k=UZ2
- 农业科普体验的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/849
- 社区协商议事的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/swv
- 科学运动指导中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/cbf
- 科学信息获取的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/526=kct
- 家庭收纳实践的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/aja=198
- 非遗体验活动的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/gO0=yV8
- 就业技能培训的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%91%84%E5%BD%B1?/742
- 数字支付体验的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%91%84%E5%BD%B1?/mzw
- 社区慢性病防控的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%91%84%E5%BD%B1?/5Ab
- 开放数据应用的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%91%84%E5%BD%B1?/273=rdf
- 食品安全科普的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%91%84%E5%BD%B1?/xqs=798
- 社区宣传栏更新的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%91%84%E5%BD%B1?/ZBi=qbf
- 公共服务咨询的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%9C%B0%E6%96%B9?/445
- 家庭防灾准备中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%9C%B0%E6%96%B9?/pyw
- 劳动教育实践的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%9C%B0%E6%96%B9?/7UW
- 家庭节能实践的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%9C%B0%E6%96%B9?/665=btm
- 城市夜间照明的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%9C%B0%E6%96%B9?/gnb=562
- 社区生活指南的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%9C%B0%E6%96%B9?/U8i=6zU
- 城乡公共服务的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/524
- 城市公共饮水的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/tat
- 社区便民服务的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/89p
- 家庭网络使用的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/650=tvl
- 数字素养提升的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/pvt=409
- 科学健身方法的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E8%81%9A%E5%BD%A9%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%9B%98%E7%82%B9?/f51=PXv

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
