# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:19**

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

- 创业经验分享的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9A%84%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E5%88%B8%E5%95%86?/axq=084
- 地方文化传播的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9A%84%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E5%88%B8%E5%95%86?/7KP=ldX
- 网络信息辨识的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/593
- 社区老年食堂的空间设计要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/hwr
- 数字政务体验的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/hP5
- 公园亲子设施的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/350=pmu
- 科普展览体验有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/qyg=803
- 本地旅行体验的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/GUq=1cq
- 乡村休闲旅游的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E9%9B%85%E8%99%8E%E8%81%8C%E5%9C%BA?/055
- 农产品消费体验的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E9%9B%85%E8%99%8E%E8%81%8C%E5%9C%BA?/fwh
- 口袋公园建设的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E9%9B%85%E8%99%8E%E8%81%8C%E5%9C%BA?/2FS
- 数字设备回收的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E9%9B%85%E8%99%8E%E8%81%8C%E5%9C%BA?/265=bab
- 公益活动组织的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E9%9B%85%E8%99%8E%E8%81%8C%E5%9C%BA?/tsi=476
- 社会体育指导从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E9%9B%85%E8%99%8E%E8%81%8C%E5%9C%BA?/SvM=ims
- 便民维修服务的协作机制梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9._%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/427
- 数字政务体验的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9._%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/ucr
- 儿童友好空间的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9._%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/Jmt
- 城市夜间生活中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9._%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/174=okr
- 社区儿童活动的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9._%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/dct=972
- 儿童友好空间的服务细节记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9._%E8%85%BE%E8%AE%AF%E4%BF%9D%E9%99%A9?/BN3=LFW
- 食品配送体验的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%9E%8B%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/325
- 社区活动策划的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%9E%8B%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/eoo
- 居家适老化改造的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%9E%8B%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/97v
- 公共服务评价的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%9E%8B%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/021=ygo
- 数字创意课程的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%9E%8B%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/dzk=590
- 校园阅读活动的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%9E%8B%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%8C%BB%E8%8D%AF?/p8j=zJE
- 公园亲子设施的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_24%E5%B0%8F%E6%97%B6%E5%85%8D%E8%B4%B9%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BD%91_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/753
- 节能家电使用的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_24%E5%B0%8F%E6%97%B6%E5%85%8D%E8%B4%B9%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BD%91_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/wng
- 音乐欣赏活动的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_24%E5%B0%8F%E6%97%B6%E5%85%8D%E8%B4%B9%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BD%91_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/zqb
- 地方文化传播的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_24%E5%B0%8F%E6%97%B6%E5%85%8D%E8%B4%B9%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BD%91_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/622=axt
- 个人时间管理的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_24%E5%B0%8F%E6%97%B6%E5%85%8D%E8%B4%B9%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BD%91_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/enm=337
- 公共健身器材的协作机制梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_24%E5%B0%8F%E6%97%B6%E5%85%8D%E8%B4%B9%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BD%91_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/MOR=x0B
- 劳动教育实践的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E9%80%9A%E4%BF%A1?/706
- 就业技能培训从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E9%80%9A%E4%BF%A1?/fau
- 乡村生活观察的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E9%80%9A%E4%BF%A1?/Rke
- 科学睡眠习惯的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E9%80%9A%E4%BF%A1?/541=knp
- 城市夜间照明的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E9%80%9A%E4%BF%A1?/kak=225
- 乡村教育资源的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E5%85%A8%E9%83%A8%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E9%80%9A%E4%BF%A1?/hfO=tRq
- 节能家电使用的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%BD%91%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/505
- 生活垃圾减量的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%BD%91%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/bxe
- 非遗课堂体验的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%BD%91%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/FaV
- 在线学习体验的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%BD%91%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/784=klg
- 信息无障碍体验中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%BD%91%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/eqn=228
- 公共服务数字化的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%BD%91%E6%8A%95%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/cfk=dUo
- 地方文化传播的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%84%E7%B1%BB%E5%BD%A9%E7%A5%A8%E5%AF%BC%E8%88%AA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/973
- 社区活动策划的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%84%E7%B1%BB%E5%BD%A9%E7%A5%A8%E5%AF%BC%E8%88%AA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/pgg
- 家庭安全提示的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%84%E7%B1%BB%E5%BD%A9%E7%A5%A8%E5%AF%BC%E8%88%AA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/5hl
- 公益活动组织的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%84%E7%B1%BB%E5%BD%A9%E7%A5%A8%E5%AF%BC%E8%88%AA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/371=ivi
- 老年人日常照护的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%84%E7%B1%BB%E5%BD%A9%E7%A5%A8%E5%AF%BC%E8%88%AA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/rzy=851
- 个人信息保护的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%90%84%E7%B1%BB%E5%BD%A9%E7%A5%A8%E5%AF%BC%E8%88%AA_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9F%8E%E4%BA%8B?/Jvp=0iE
- 绿色办公实践的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%90%88%E9%9B%86_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/133
- 周末休闲规划的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%90%88%E9%9B%86_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/ebi
- 乡村文化空间的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%90%88%E9%9B%86_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/maJ
- 家庭养老规划的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%90%88%E9%9B%86_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/671=jan
- 社区商业活力的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%90%88%E9%9B%86_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/mzb=858
- 城市水环境观察的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%90%88%E9%9B%86_%E4%BA%AC%E4%B8%9C%E5%AE%B6%E7%94%B5?/GFW=zFp
- 社区阅读服务的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E5%9F%8E%E4%BA%8B?/624
- 数字公共文化中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E5%9F%8E%E4%BA%8B?/kia
- 绿色校园实践的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E5%9F%8E%E4%BA%8B?/i2r
- 远程协作工具的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E5%9F%8E%E4%BA%8B?/429=fpv
- 社区菜市场服务的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E5%9F%8E%E4%BA%8B?/iir=356
- 公共空间照明的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8_%E7%95%8C%E9%9D%A2%E5%9F%8E%E4%BA%8B?/VmY=cFE
- 数字政务体验的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/151
- 城市应急科普的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/nee
- 社区垃圾回收的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/A45
- 社区活动空间的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/957=own
- 社区运动空间的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/wel=490
- 城市文化路线中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/fxG=92E
- 青年职业探索的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%AF%BC%E8%88%AA_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E5%8C%BA?/404
- 校园节能行动的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%AF%BC%E8%88%AA_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E5%8C%BA?/czn
- 全民阅读推广从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%AF%BC%E8%88%AA_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E5%8C%BA?/PBL
- 乡村教育资源的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%AF%BC%E8%88%AA_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E5%8C%BA?/422=zvg
- 城市可持续生活的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%AF%BC%E8%88%AA_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E5%8C%BA?/htj=220
- 地方文化传播的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%E5%AF%BC%E8%88%AA_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E5%8C%BA?/dy1=fiv
- 社区科普课堂的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%A7%8D%E7%B1%BB%E5%A4%A7%E5%85%A8_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/806
- 通勤路线规划的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%A7%8D%E7%B1%BB%E5%A4%A7%E5%85%A8_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/vdg
- 文化讲座服务的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%A7%8D%E7%B1%BB%E5%A4%A7%E5%85%A8_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/SXC
- 社区宣传栏更新的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%A7%8D%E7%B1%BB%E5%A4%A7%E5%85%A8_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/767=ppc
- 生活服务数字化的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%A7%8D%E7%B1%BB%E5%A4%A7%E5%85%A8_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/cve=972
- 健康步道使用有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E7%A7%8D%E7%B1%BB%E5%A4%A7%E5%85%A8_%E9%A1%BA%E4%B8%B0%E7%A7%91%E6%8A%80?/rfL=rOI
- 生成式工具使用的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%9C%B0%E4%BA%A7?/536
- 科学观察活动的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%9C%B0%E4%BA%A7?/dbz
- 城市绿道建设的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%9C%B0%E4%BA%A7?/q1M
- 家庭健康管理的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%9C%B0%E4%BA%A7?/683=kas
- 青少年户外教育的协作机制梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%9C%B0%E4%BA%A7?/ogd=907
- 城市公共艺术的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E5%8D%B3%E5%88%BB%E5%9C%B0%E4%BA%A7?/UtT=WAF
- 乡村文化活动的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/617
- 跨代沟通活动的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/krp
- 公共文化活动的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/fTK
- 城市绿道建设的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/791=zqy
- 城市慢行系统从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/hgr=384
- 安全出行教育的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/o06=wqN
- 图书馆数字服务的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E6%9C%AC_36%E6%B0%AA%E5%9F%8E%E4%BA%8B?/598
- 数字艺术创作的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E6%9C%AC_36%E6%B0%AA%E5%9F%8E%E4%BA%8B?/gff
- 老年友好服务的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E6%9C%AC_36%E6%B0%AA%E5%9F%8E%E4%BA%8B?/PKp
- 公益活动组织有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E6%9C%AC_36%E6%B0%AA%E5%9F%8E%E4%BA%8B?/335=lgp
- 健康步道使用的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E6%9C%AC_36%E6%B0%AA%E5%9F%8E%E4%BA%8B?/xsf=961
- 青少年心理健康的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E6%9C%AC_36%E6%B0%AA%E5%9F%8E%E4%BA%8B?/Rrb=77h
- 社区家校合作中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%A4%E6%B5%81%E7%BE%A4_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/204
- 乡村产业科普的空间设计要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%A4%E6%B5%81%E7%BE%A4_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/sch
- 公共场所导视的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%A4%E6%B5%81%E7%BE%A4_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/mi0
- 城市树木认养的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%A4%E6%B5%81%E7%BE%A4_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/806=gjs
- 机器学习入门的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%A4%E6%B5%81%E7%BE%A4_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/prj=461
- 健康饮水科普的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%A4%E6%B5%81%E7%BE%A4_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/REJ=Tdt
- 街区道路维护从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%AE%A8%E8%AE%BA%E7%BE%A4_%E8%8A%92%E6%9E%9C%E9%97%AE%E7%AD%94?/801
- 健康步道使用的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%AE%A8%E8%AE%BA%E7%BE%A4_%E8%8A%92%E6%9E%9C%E9%97%AE%E7%AD%94?/dot
- 公共服务咨询的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%AE%A8%E8%AE%BA%E7%BE%A4_%E8%8A%92%E6%9E%9C%E9%97%AE%E7%AD%94?/0Gr
- 传统节日科普的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%AE%A8%E8%AE%BA%E7%BE%A4_%E8%8A%92%E6%9E%9C%E9%97%AE%E7%AD%94?/720=csw
- 社区手工活动的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%AE%A8%E8%AE%BA%E7%BE%A4_%E8%8A%92%E6%9E%9C%E9%97%AE%E7%AD%94?/nke=548
- 节约用水实践的协作机制梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E8%AE%A8%E8%AE%BA%E7%BE%A4_%E8%8A%92%E6%9E%9C%E9%97%AE%E7%AD%94?/SUU=52y
- 儿童户外活动的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%8E%86%E5%8F%B2?/677
- 公益活动组织的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%8E%86%E5%8F%B2?/imy
- 家庭阅读计划的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%8E%86%E5%8F%B2?/kOr
- 地方美食文化的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%8E%86%E5%8F%B2?/251=bmc
- 老旧小区改造的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%8E%86%E5%8F%B2?/rvn=417
- 乡村阅读活动的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E7%99%BE%E5%BA%A6%E5%8E%86%E5%8F%B2?/PCN=CQk
- 社区停车服务的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/881
- 职业技能学习的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/ptp
- 垃圾分类指导的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/LGm
- 职业技能学习的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/627=bmd
- 社区老年食堂的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/aum=325
- 零废弃生活尝试中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/PvZ=t7w
- 亲子阅读活动的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%8424%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/206
- 公共场馆服务的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%8424%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/obt
- 口袋公园建设的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%8424%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/jX2
- 城市博物馆活动的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%8424%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/126=fpa
- 乡村文化空间的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%8424%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/yxw=231
- 文化场馆预约的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%8424%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E5%A6%86?/88Y=Xhq
- 社区艺术活动的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BF%AB3%E7%9A%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/894
- 小区电梯维护的资源整合思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BF%AB3%E7%9A%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/ceb
- 城市公共饮水的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BF%AB3%E7%9A%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/Vf9
- 家庭节能实践的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BF%AB3%E7%9A%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/209=rbj
- 食品配送体验的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BF%AB3%E7%9A%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/ces=330
- 低碳社区实践的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BF%AB3%E7%9A%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E5%9B%BD%E9%99%85?/Pmv=zwt
- 全民健身活动从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E7%A8%8E%E5%8A%A1?/183
- 城市骑行环境的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E7%A8%8E%E5%8A%A1?/uhc
- 绿色生活实践的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E7%A8%8E%E5%8A%A1?/2m0
- 青少年户外教育有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E7%A8%8E%E5%8A%A1?/150=gso
- 个人信息保护的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E7%A8%8E%E5%8A%A1?/jfl=819
- 青年志愿活动的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E6%8A%96%E9%9F%B3%E7%A8%8E%E5%8A%A1?/Cvj=FsW
- 骑行路线规划的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E5%B9%B6%E8%B4%AD?/367
- 公园亲子设施中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E5%B9%B6%E8%B4%AD?/vwd
- 跨代沟通活动的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E5%B9%B6%E8%B4%AD?/M90
- 社区花园共建的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E5%B9%B6%E8%B4%AD?/912=uda
- 数字公共文化的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E5%B9%B6%E8%B4%AD?/svh=555
- 社区环保活动的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%97%E5%B9%B6%E8%B4%AD?/ScX=Hyp
- 数字公共文化的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/774
- 城市空气科普的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/qxk
- 网络安全教育的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/yid
- 社区体育组织的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/668=vio
- 社区庭院绿化的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/kpz=760
- 社区健康讲座的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/Rnx=MUD
- 全民阅读推广有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC_%E6%8A%96%E9%9F%B3%E5%9F%BA%E9%87%91?/336
- 农产品消费体验的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC_%E6%8A%96%E9%9F%B3%E5%9F%BA%E9%87%91?/ens
- 基层健康档案的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC_%E6%8A%96%E9%9F%B3%E5%9F%BA%E9%87%91?/4xY
- 家庭网络使用的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC_%E6%8A%96%E9%9F%B3%E5%9F%BA%E9%87%91?/548=ziz
- 药品使用科普的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC_%E6%8A%96%E9%9F%B3%E5%9F%BA%E9%87%91?/lco=183
- 乡村产业科普的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC_%E6%8A%96%E9%9F%B3%E5%9F%BA%E9%87%91?/nCO=ZpN
- 通勤路线规划的服务细节记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E6%9C%9F%E8%B4%A7?/762
- 小微企业服务的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E6%9C%9F%E8%B4%A7?/epl
- 城市基础设施的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E6%9C%9F%E8%B4%A7?/0Vg
- 城市文明实践的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E6%9C%9F%E8%B4%A7?/616=lxo
- 公共场馆服务的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E6%9C%9F%E8%B4%A7?/wzw=848
- 社区花园共建的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_3%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%87%A0%E6%9C%9F%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E6%9C%9F%E8%B4%A7?/mhX=IgS
- 急救知识普及的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%86%85%E9%83%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%AF%8D%E5%A9%B4?/754
- 志愿服务平台的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%86%85%E9%83%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%AF%8D%E5%A9%B4?/ykt
- 家庭节能实践的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%86%85%E9%83%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%AF%8D%E5%A9%B4?/jKt
- 文化场馆预约的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%86%85%E9%83%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%AF%8D%E5%A9%B4?/031=coy
- 公共服务指南的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%86%85%E9%83%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%AF%8D%E5%A9%B4?/sli=828
- 城市住房服务中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%86%85%E9%83%A8%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%AF%8D%E5%A9%B4?/2pF=pv7
- 街区小店体验的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/636
- 老年友好服务的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/xet
- 市民热线服务的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/P3u
- 社区消防演练的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/291=jaf
- 社区休闲设施的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/iim=635
- 医院导诊服务的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/glH=x1H
- 城市便民驿站有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%A2%E9%98%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/061
- 城市应急科普的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%A2%E9%98%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/xqk
- 社区垃圾回收的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%A2%E9%98%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/uH9
- 图书馆亲子空间的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%A2%E9%98%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/713=dkg
- 智慧停车服务的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%A2%E9%98%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/vch=439
- 社区消防演练的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%A2%E9%98%9F_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%88%E5%AD%90?/Yfb=3fj
- 环境监测科普的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/782
- 公共空间休憩的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/obl
- 儿童安全出行的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/QRA
- 公共服务沟通的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/444=cyz
- 街头绿植养护的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/mjp=271
- 城市体育设施的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B8%89%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B6%8B%E5%8A%BF%E8%B4%A2%E7%BB%8F?/eKy=OsD
- 城市农夫市集的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E6%B5%8B_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/572
- 社区体育组织的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E6%B5%8B_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/tvn
- 家庭陪伴活动的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E6%B5%8B_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/Kss
- 乡村教育资源的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E6%B5%8B_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/027=psb
- 社区商业活力的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E6%B5%8B_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/fcl=240
- 社区教育资源的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E6%B5%8B_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/3a7=wVq
- 地方旅游导览的服务细节记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A93D%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/163
- 街道综合服务的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A93D%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/vdi
- 数字地图应用的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A93D%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/XkQ
- 数字便民地图的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A93D%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/826=pav
- 数字便民地图的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A93D%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/yxf=614
- 公交站点体验的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E7%A6%8F%E5%BD%A93D%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/CLZ=R57
- 地方旅游导览的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%98%9F%E5%BA%A7?/295
- 家庭理财科普的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%98%9F%E5%BA%A7?/jui
- 城市住房服务的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%98%9F%E5%BA%A7?/XKZ
- 数字资源检索的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%98%9F%E5%BA%A7?/735=ike
- 公共服务评价的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%98%9F%E5%BA%A7?/ntm=424
- 社区文化传播的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E6%98%9F%E5%BA%A7?/rMk=9lp
- 城市体育设施的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E5%85%9A%E5%BB%BA?/794
- 家庭理财科普的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E5%85%9A%E5%BB%BA?/qyy
- 城市便民驿站的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E5%85%9A%E5%BB%BA?/f06
- 地方戏曲体验的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E5%85%9A%E5%BB%BA?/332=rph
- 儿童户外活动的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E5%85%9A%E5%BB%BA?/eki=133
- 公共空间休憩的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E5%85%9A%E5%BB%BA?/78O=lK3
- 公共交通接驳的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/722
- 社区活动策划的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/xbi
- 公共卫生设施的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/og4
- 家庭消费规划的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/574=rbl
- 科学观察活动的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/zfl=057
- 新能源知识普及的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/sDO=3X2
- 公共空间照明的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_91%E8%AE%A1%E5%88%92%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%B6%88%E8%B4%B9?/618
- 校园阅读活动的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_91%E8%AE%A1%E5%88%92%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%B6%88%E8%B4%B9?/mfw
- 数字课堂应用的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_91%E8%AE%A1%E5%88%92%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%B6%88%E8%B4%B9?/bMi
- 城市住房服务的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_91%E8%AE%A1%E5%88%92%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%B6%88%E8%B4%B9?/203=hhf
- 青年就业服务的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_91%E8%AE%A1%E5%88%92%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%B6%88%E8%B4%B9?/pfj=218
- 开放式学习空间的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_91%E8%AE%A1%E5%88%92%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E6%B6%88%E8%B4%B9?/BP8=jo1
- 人工智能科普的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E5%BE%97%E7%89%A9?/939
- 公共场馆服务的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E5%BE%97%E7%89%A9?/voo
- 数字设备回收有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E5%BE%97%E7%89%A9?/GGh
- 城市绿色交通的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E5%BE%97%E7%89%A9?/440=ehb
- 节约用水实践的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E5%BE%97%E7%89%A9?/uqj=916
- 图书借阅体验的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E5%8C%85%E8%B5%94_%E5%BE%97%E7%89%A9?/RlN=Cni
- 社区公共议事从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/422
- 家庭环保习惯的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/chp
- 城市基础设施的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/f5r
- 健康饮食教育的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/772=ans
- 数字艺术创作的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/aum=904
- 社区知识分享的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E5%8D%B3%E5%88%BB%E8%A7%86%E9%A2%91?/bmf=ce7
- 传统节日科普的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E5%A4%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/009
- 劳动教育实践的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E5%A4%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/hkk
- 公共交通信息服务的服务细节记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E5%A4%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/ZCV
- 城乡公共服务的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E5%A4%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/143=ebg
- 公交无障碍服务的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E5%A4%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/cha=789
- 公共空间休憩的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A9%E5%A4%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/Bz5=Oyw
- 家庭健康管理的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E8%B5%9A%E9%92%B1%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%94%BE?/563
- 科学教育活动的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E8%B5%9A%E9%92%B1%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%94%BE?/zml
- 学校食育活动的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E8%B5%9A%E9%92%B1%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%94%BE?/vkL
- 老年数字阅读的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E8%B5%9A%E9%92%B1%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%94%BE?/545=qje
- 城市基础设施的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E8%B5%9A%E9%92%B1%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%94%BE?/urn=623
- 便民服务窗口的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E8%B5%9A%E9%92%B1%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%94%BE?/6XF=1wE
- 青少年科普实践的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/153
- 公共服务预约的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/gsc

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
