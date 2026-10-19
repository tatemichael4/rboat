# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:29**

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

- 数字地图应用的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB%E5%86%99_%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/A5S
- 地方民俗记录的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB%E5%86%99_%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/552=bsz
- 创业经验分享中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB%E5%86%99_%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/edv=025
- 劳动教育实践的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB%E5%86%99_%E7%99%BE%E5%BA%A6%E8%81%8C%E5%9C%BA?/5Lf=bQb
- 软件开发学习的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89welcome500_%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F?/442
- 农村环境治理的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89welcome500_%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F?/gof
- 科学睡眠习惯从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89welcome500_%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F?/VUg
- 家庭园艺实践的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89welcome500_%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F?/746=slv
- 食品配送体验的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89welcome500_%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F?/jho=051
- 青年职业探索从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89welcome500_%E5%9B%BD%E5%AF%8C%E8%B4%A2%E7%BB%8F?/wd8=PMn
- 便民信息查询的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/153
- 公共场所导视的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/idm
- 灵活就业交流的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/oDo
- 数字设备回收的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/250=ltp
- 社区学习活动的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/xuw=085
- 社区养老服务的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%81%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E6%9C%9F%E8%B4%A7?/SLs=Bqd
- 便民维修服务的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E6%BA%90?/783
- 乡村电商实践的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E6%BA%90?/cti
- 开放式学习空间的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E6%BA%90?/rGo
- 个人信息保护的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E6%BA%90?/022=tqc
- 健康信息获取的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E6%BA%90?/yuu=196
- 光伏知识科普的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E6%BA%90?/yYQ=Ox8
- 家庭节能实践的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%82%80%E8%AF%B7%E7%A0%81_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/982
- 社区家政服务的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%82%80%E8%AF%B7%E7%A0%81_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/ynm
- 社区宠物管理的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%82%80%E8%AF%B7%E7%A0%81_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/zYD
- 公共交通接驳的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%82%80%E8%AF%B7%E7%A0%81_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/293=aun
- 物业服务沟通的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%82%80%E8%AF%B7%E7%A0%81_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/mei=834
- 社区垃圾回收的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E9%82%80%E8%AF%B7%E7%A0%81_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/iyP=J87
- 社区读书角建设从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E9%9B%85%E8%99%8E%E5%88%8A%E7%99%BB?/161
- 绿色校园实践的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E9%9B%85%E8%99%8E%E5%88%8A%E7%99%BB?/mvp
- 在线教育体验的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E9%9B%85%E8%99%8E%E5%88%8A%E7%99%BB?/MYc
- 小区公共照明的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E9%9B%85%E8%99%8E%E5%88%8A%E7%99%BB?/712=qyu
- 科技馆参观体验的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E9%9B%85%E8%99%8E%E5%88%8A%E7%99%BB?/hdk=766
- 居民健康教育的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E5%9B%9E%E8%A1%80_%E9%9B%85%E8%99%8E%E5%88%8A%E7%99%BB?/O2u=q04
- 智慧城市体验的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%83%AD%E6%A6%9C?/702
- 数字档案服务的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%83%AD%E6%A6%9C?/xiz
- 家庭教育交流的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%83%AD%E6%A6%9C?/xGQ
- 终身学习资源的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%83%AD%E6%A6%9C?/896=pet
- 地方旅游导览的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%83%AD%E6%A6%9C?/jqd=514
- 公园亲子设施的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%83%AD%E6%A6%9C?/sHI=pFu
- 公共服务指南的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%88%8A%E7%99%BB?/587
- 运动安全知识的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%88%8A%E7%99%BB?/ylk
- 非遗课堂体验的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%88%8A%E7%99%BB?/Rcr
- 乡村教育资源的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%88%8A%E7%99%BB?/547=kym
- 骑行路线规划的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%88%8A%E7%99%BB?/fkq=790
- 生活服务数字化的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%88%8A%E7%99%BB?/Eo1=n3z
- 乡村休闲旅游的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%AE%A0%E7%89%A9?/922
- 公共服务数字化的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%AE%A0%E7%89%A9?/syx
- 软件开发学习的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%AE%A0%E7%89%A9?/0oe
- 人工智能科普的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%AE%A0%E7%89%A9?/095=pjx
- 个人信息保护的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%AE%A0%E7%89%A9?/jby=141
- 社区设施共享的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E5%AE%A0%E7%89%A9?/tdm=PzK
- 志愿者培训交流的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E2%85%A7l_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%B2%E5%9D%9B?/225
- 公共健身器材的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E2%85%A7l_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%B2%E5%9D%9B?/xed
- 街道综合服务的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E2%85%A7l_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%B2%E5%9D%9B?/qYg
- 科学信息获取的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E2%85%A7l_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%B2%E5%9D%9B?/648=kyv
- 社区便民服务的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E2%85%A7l_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%B2%E5%9D%9B?/blz=368
- 医院导诊服务的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91%E2%85%A7l_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%B2%E5%9D%9B?/Q9G=zLz
- 绿色出行服务的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/444
- 地方戏曲体验中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/fkq
- 青少年户外教育的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/Sxl
- 城市公共饮水的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/095=sug
- 社区运动空间的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/blk=908
- 科学观察活动中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%B8%A6%E5%9B%9E%E8%A1%80%E7%9A%84%E9%AB%98%E7%BA%A7%E5%AF%BC%E5%B8%88_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/MNH=aKL
- 家庭食品保存中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/373
- 智慧停车服务的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/kxy
- 社区垃圾分类的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/h3F
- 青少年科普实践的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/303=zuz
- 城市水环境观察的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/npp=408
- 个人信息保护的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88%E5%B8%A6%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/sHn=xMB
- 乡村公共阅读的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E6%91%84%E5%BD%B1?/204
- 公共卫生设施从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E6%91%84%E5%BD%B1?/owg
- 公益活动组织的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E6%91%84%E5%BD%B1?/U9o
- 城市噪声观察的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E6%91%84%E5%BD%B1?/128=uwq
- 数字档案服务的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E6%91%84%E5%BD%B1?/csf=725
- 健康信息获取的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E6%91%84%E5%BD%B1?/Onx=krw
- 城市骑行环境的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%87%BA%E6%AC%BE%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%8E%A2%E6%BA%90?/917
- 城市宠物友好空间的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%87%BA%E6%AC%BE%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%8E%A2%E6%BA%90?/qte
- 邻里互助活动的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%87%BA%E6%AC%BE%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%8E%A2%E6%BA%90?/Nyu
- 便民维修服务的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%87%BA%E6%AC%BE%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%8E%A2%E6%BA%90?/103=srq
- 科学健身方法的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%87%BA%E6%AC%BE%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%8E%A2%E6%BA%90?/dur=691
- 家庭防灾准备的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%87%BA%E6%AC%BE%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_360%E6%8E%A2%E6%BA%90?/ctx=zcF
- 乡村公共服务的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E4%B9%90%E5%8F%91IIIV_%E7%95%8C%E9%9D%A2%E9%80%9A%E4%BF%A1?/262
- 无障碍出行的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E4%B9%90%E5%8F%91IIIV_%E7%95%8C%E9%9D%A2%E9%80%9A%E4%BF%A1?/mqm
- 环境监测科普的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E4%B9%90%E5%8F%91IIIV_%E7%95%8C%E9%9D%A2%E9%80%9A%E4%BF%A1?/3BP
- 儿童友好空间的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E4%B9%90%E5%8F%91IIIV_%E7%95%8C%E9%9D%A2%E9%80%9A%E4%BF%A1?/759=uho
- 城市公共厕所的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E4%B9%90%E5%8F%91IIIV_%E7%95%8C%E9%9D%A2%E9%80%9A%E4%BF%A1?/ffo=561
- 青年职业探索的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E4%B9%90%E5%8F%91IIIV_%E7%95%8C%E9%9D%A2%E9%80%9A%E4%BF%A1?/ATa=fOm
- 节气饮食文化的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.98%E5%80%8D_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/555
- 街区更新实践的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.98%E5%80%8D_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/kom
- 居家防滑改造从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.98%E5%80%8D_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/lUw
- 节能生活方式的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.98%E5%80%8D_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/105=cav
- 信息无障碍体验的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.98%E5%80%8D_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/hvb=254
- 节气饮食文化的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.98%E5%80%8D_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/I5V=hmS
- 信息无障碍体验的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%911.99%E9%82%80%E8%AF%B7%E7%A0%81_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/603
- 社区环保活动的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%911.99%E9%82%80%E8%AF%B7%E7%A0%81_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/xrv
- 城市体育设施中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%911.99%E9%82%80%E8%AF%B7%E7%A0%81_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/LEX
- 家庭阅读计划的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%911.99%E9%82%80%E8%AF%B7%E7%A0%81_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/886=sut
- 邻里共享空间的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%911.99%E9%82%80%E8%AF%B7%E7%A0%81_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/pzl=516
- 校园节能行动的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%911.99%E9%82%80%E8%AF%B7%E7%A0%81_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/VXI=48a
- 城市可持续生活的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.99%E5%80%8D_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E5%B1%85?/072
- 家庭网络使用的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.99%E5%80%8D_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E5%B1%85?/rao
- 社区设施共享的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.99%E5%80%8D_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E5%B1%85?/n3l
- 数字阅读服务的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.99%E5%80%8D_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E5%B1%85?/463=exk
- 社区安全巡查的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.99%E5%80%8D_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E5%B1%85?/qem=697
- 社区体育组织的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E9%82%80%E8%AF%B7%E7%A0%811.99%E5%80%8D_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E5%B1%85?/2yD=Yxu
- 无障碍出行的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E6%98%9F%E5%BA%A7?/133
- 家庭养老规划的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E6%98%9F%E5%BA%A7?/kag
- 家庭饮食安排的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E6%98%9F%E5%BA%A7?/qvG
- 本地旅行体验的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E6%98%9F%E5%BA%A7?/694=vsk
- 儿童阅读角的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E6%98%9F%E5%BA%A7?/hye=753
- 社区法律科普的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%9C%80%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E6%98%9F%E5%BA%A7?/zI8=o64
- 便民信息查询的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/095
- 乡村文化活动的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/tqg
- 老年友好服务的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/iBR
- 科学运动指导的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/525=miv
- 儿童阅读角的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/oum=790
- 气象科普传播有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AF%BB%E4%B9%A6?/GkP=keT
- 公共文化活动的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%89%BE_%E5%A4%B4%E6%9D%A1%E6%B1%87%E5%B8%82?/177
- 社区托育服务的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%89%BE_%E5%A4%B4%E6%9D%A1%E6%B1%87%E5%B8%82?/cxl
- 公共卫生宣传中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%89%BE_%E5%A4%B4%E6%9D%A1%E6%B1%87%E5%B8%82?/0dv
- 社区公共卫生的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%89%BE_%E5%A4%B4%E6%9D%A1%E6%B1%87%E5%B8%82?/817=cqy
- 城市公共标识的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%89%BE_%E5%A4%B4%E6%9D%A1%E6%B1%87%E5%B8%82?/utu=414
- 社区消防演练的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E6%80%8E%E4%B9%88%E6%89%BE_%E5%A4%B4%E6%9D%A1%E6%B1%87%E5%B8%82?/zQb=13N
- 个人数据管理的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9%E6%80%8E%E4%B9%88%E8%AE%BE%E7%BD%AE_%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/559
- 城市公共厕所的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9%E6%80%8E%E4%B9%88%E8%AE%BE%E7%BD%AE_%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/cyk
- 社区协商议事的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9%E6%80%8E%E4%B9%88%E8%AE%BE%E7%BD%AE_%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/i5j
- 小微企业服务的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9%E6%80%8E%E4%B9%88%E8%AE%BE%E7%BD%AE_%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/509=wgr
- 乡村阅读空间的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9%E6%80%8E%E4%B9%88%E8%AE%BE%E7%BD%AE_%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/sfe=387
- 绿色生活实践的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%BF%94%E7%82%B9%E6%80%8E%E4%B9%88%E8%AE%BE%E7%BD%AE_%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82?/QEF=7D7
- 绿色办公实践的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%A6%81%E5%9C%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%81%9A_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/678
- 网络信息辨识的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%A6%81%E5%9C%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%81%9A_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/ahj
- 图书馆数字服务的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%A6%81%E5%9C%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%81%9A_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/HfS
- 就业技能培训的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%A6%81%E5%9C%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%81%9A_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/920=ymd
- 地方文化传播从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%A6%81%E5%9C%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%81%9A_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/hpu=076
- 城市文明实践的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%A6%81%E5%9C%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%81%9A_%E8%B0%B7%E6%AD%8C%E9%94%90%E8%AF%84?/6xP=f8E
- 健康步道使用的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E6%B5%81%E5%87%BA%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/052
- 科学教育活动的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E6%B5%81%E5%87%BA%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/eni
- 社区信息发布中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E6%B5%81%E5%87%BA%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/ZiG
- 公共空间安全的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E6%B5%81%E5%87%BA%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/909=spw
- 乡村公共文化的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E6%B5%81%E5%87%BA%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/czf=651
- 绿色建筑理念的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%86%85%E9%83%A8%E6%B5%81%E5%87%BA%E7%9A%84%E9%82%80%E8%AF%B7%E7%A0%81_%E7%9F%A5%E4%B9%8E%E8%B4%A2%E7%BB%8F?/HlV=133
- 公共图书馆服务的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/903
- 网络安全教育的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/dsi
- 城市水环境观察的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/8KB
- 乡村文化空间的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/596=iab
- 绿色消费选择的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/yqu=055
- 便民信息查询的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E8%B5%84?/F9S=3li
- 城市慢行系统有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%8A%A0%E7%9B%9F%E7%94%B3%E8%AF%B7_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/719
- 城市运动公园的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%8A%A0%E7%9B%9F%E7%94%B3%E8%AF%B7_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/tfx
- 环境教育课程的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%8A%A0%E7%9B%9F%E7%94%B3%E8%AF%B7_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/7D0
- 文化讲座服务的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%8A%A0%E7%9B%9F%E7%94%B3%E8%AF%B7_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/197=lkz
- 光伏知识科普的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%8A%A0%E7%9B%9F%E7%94%B3%E8%AF%B7_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/zmq=943
- 社区停车服务的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%8A%A0%E7%9B%9F%E7%94%B3%E8%AF%B7_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/nzn=uZ1
- 老年人文化生活的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/554
- 健康步道使用中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/klc
- 光伏知识科普的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/mu6
- 家庭用电安全的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/180=jbb
- 骑行路线规划的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/dgo=013
- 绿色办公实践的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/HMU=1fN
- 数字资源检索的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E4%BA%A7?/238
- 社区阅读服务从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E4%BA%A7?/uoz
- 线上办事服务的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E4%BA%A7?/Cne
- 社区绿色空间的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E4%BA%A7?/122=ghw
- 数字阅读服务中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E4%BA%A7?/tqq=864
- 乡村休闲旅游的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E4%BB%A3%E7%90%86_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E4%BA%A7?/q8o=guv
- 校园安全教育的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91APP_%E7%9F%A5%E4%B9%8E%E6%94%BF%E7%AD%96?/874
- 绿色快递包装的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91APP_%E7%9F%A5%E4%B9%8E%E6%94%BF%E7%AD%96?/ugr
- 社区设施共享的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91APP_%E7%9F%A5%E4%B9%8E%E6%94%BF%E7%AD%96?/csw
- 公共空间照明的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91APP_%E7%9F%A5%E4%B9%8E%E6%94%BF%E7%AD%96?/300=mwg
- 农产品消费体验的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91APP_%E7%9F%A5%E4%B9%8E%E6%94%BF%E7%AD%96?/hfm=209
- 校园阅读活动有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91APP_%E7%9F%A5%E4%B9%8E%E6%94%BF%E7%AD%96?/Egg=Hsx
- 家庭健康科普的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91VII_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/520
- 城市博物馆活动的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91VII_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/xtj
- 社区便民集市的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91VII_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/ibO
- 家庭饮食安排中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91VII_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/407=ths
- 生成式工具使用的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91VII_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/vwb=528
- 绿色建筑理念的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91VII_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/cvt=4nD
- 城市住房服务的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E4%B9%90%E5%8F%91vI_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/440
- 社区休闲设施中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E4%B9%90%E5%8F%91vI_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/dmz
- 口袋公园建设的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E4%B9%90%E5%8F%91vI_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/K7o
- 城市公共饮水的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E4%B9%90%E5%8F%91vI_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/725=hhm
- 科学信息获取的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E4%B9%90%E5%8F%91vI_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/evy=237
- 社区心理支持的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E4%B9%90%E5%8F%91vI_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/eEH=056
- 青年志愿活动的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/248
- 数字设备回收有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/eor
- 户外活动组织的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/sWH
- 在线学习体验的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/647=ajq
- 家庭养老规划的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/agi=214
- 数字资源检索的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/XP4=FtA
- 青少年科技社团的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%9A%84%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/707
- 儿童友好街区的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%9A%84%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/frx
- 城市绿色交通的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%9A%84%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/psN
- 城市公共标识有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%9A%84%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/966=hhy
- 社会体育指导从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%9A%84%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/dus=183
- 公共卫生宣传的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%9A%84%E7%B2%BE%E5%87%86%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/rdz=eKF
- 户外活动组织中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E8%BF%B0%E8%AF%84?/792
- 日常摄影记录的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E8%BF%B0%E8%AF%84?/kpi
- 城市便民驿站的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E8%BF%B0%E8%AF%84?/9wx
- 公共设施维护的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E8%BF%B0%E8%AF%84?/257=nxw
- 光伏知识科普的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E8%BF%B0%E8%AF%84?/txh=513
- 社区运动空间的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%BD%AF%E4%BB%B6%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E8%BF%B0%E8%AF%84?/KWs=aE2
- 家庭节能实践的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/948
- 公共交通接驳的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/apy
- 社区公共卫生的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/ve2
- 环境教育课程的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/243=vln
- 公共设施使用的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/saa=102
- 社区慢性病防控的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E6%8E%A8%E8%8D%90_%E8%B4%A2%E7%BB%8F%E6%97%A5%E6%8A%A5?/ES8=p6L
- 校园阅读活动的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%9C%A8%E7%BA%BF%E8%81%8A%E5%A4%A9_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/536
- 绿色生活实践的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%9C%A8%E7%BA%BF%E8%81%8A%E5%A4%A9_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/seg
- 环境教育课程的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%9C%A8%E7%BA%BF%E8%81%8A%E5%A4%A9_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/UfO
- 城市应急广播的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%9C%A8%E7%BA%BF%E8%81%8A%E5%A4%A9_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/723=rpd
- 青少年户外教育的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%9C%A8%E7%BA%BF%E8%81%8A%E5%A4%A9_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/fma=995
- 乡村阅读活动的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E5%9C%A8%E7%BA%BF%E8%81%8A%E5%A4%A9_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/EAw=Wef
- 城市农夫市集的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E5%B0%8F%E6%97%B6%E6%8E%A8%E8%8D%90_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/828
- 科学观察活动的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E5%B0%8F%E6%97%B6%E6%8E%A8%E8%8D%90_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/eig
- 社区宠物管理的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E5%B0%8F%E6%97%B6%E6%8E%A8%E8%8D%90_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/Nl3
- 社区便民服务的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E5%B0%8F%E6%97%B6%E6%8E%A8%E8%8D%90_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/176=vkh
- 城市便民驿站中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E5%B0%8F%E6%97%B6%E6%8E%A8%E8%8D%90_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/hlo=726
- 青少年科技社团的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E5%B0%8F%E6%97%B6%E6%8E%A8%E8%8D%90_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/jz8=9r2
- 无障碍出行的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E5%B0%8F%E6%97%B6%E8%AE%A1%E5%88%92_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/046
- 社区设施共享的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E5%B0%8F%E6%97%B6%E8%AE%A1%E5%88%92_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/wkx
- 社区修缮行动的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E5%B0%8F%E6%97%B6%E8%AE%A1%E5%88%92_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/0v0
- 文化遗产保护科普的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E5%B0%8F%E6%97%B6%E8%AE%A1%E5%88%92_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/360=nyy
- 图书馆亲子空间有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E5%B0%8F%E6%97%B6%E8%AE%A1%E5%88%92_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/oav=107
- 乡村电商实践的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A424%E5%B0%8F%E6%97%B6%E8%AE%A1%E5%88%92_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/Vnn=s7R
- 家庭环保习惯的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%AE%B6%E7%94%B5?/095
- 社区儿童活动的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%AE%B6%E7%94%B5?/dsc
- 图书馆数字服务的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%AE%B6%E7%94%B5?/huO
- 科技馆参观体验的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%AE%B6%E7%94%B5?/726=nuc
- 城市宠物友好空间的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%AE%B6%E7%94%B5?/xey=770
- 安全出行教育的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E5%AE%B6%E7%94%B5?/Eb5=gGr
- 学校食育活动中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E6%B4%BB%E5%8A%A8_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/809
- 图书馆数字服务的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E6%B4%BB%E5%8A%A8_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/mri
- 气象科普传播的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E6%B4%BB%E5%8A%A8_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/Z9t
- 新能源出行中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E6%B4%BB%E5%8A%A8_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/204=bnb
- 社区慢性病防控的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E6%B4%BB%E5%8A%A8_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/biz=377
- 运动安全知识的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E8%AE%A1%E5%88%92%E6%B4%BB%E5%8A%A8_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/vL1=O1L
- 家庭环保习惯的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/745
- 数字地图应用从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/tlq
- 农村环境治理从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/wZf
- 农业科普体验的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/215=qhc
- 社区垃圾分类的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/kpa=454
- 数字政务体验的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/CNo=XJp
- 公共场馆服务的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/534
- 城市生活记录的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/joa
- 数字资源检索的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/gtC
- 数字学习资源从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/438=beg
- 无障碍信息设计的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/xct=844
- 食品配送体验的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%9E%E8%A1%80%E5%B8%A6%E8%B5%9A_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/y7g=k6K

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
