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

- 本地旅行体验的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%8F%B7%E5%A4%96?/udv=096
- 城市生活服务的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%8F%B7%E5%A4%96?/LZc=uaO
- 社区互助网络的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E7%A8%B3%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%B5%8B_%E8%99%8E%E5%97%85%E8%AE%BF%E8%B0%88?/912
- 家庭志愿活动的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E7%A8%B3%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%B5%8B_%E8%99%8E%E5%97%85%E8%AE%BF%E8%B0%88?/cwd
- 生活垃圾回收的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E7%A8%B3%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%B5%8B_%E8%99%8E%E5%97%85%E8%AE%BF%E8%B0%88?/sWP
- 城市农夫市集的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E7%A8%B3%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%B5%8B_%E8%99%8E%E5%97%85%E8%AE%BF%E8%B0%88?/076=mag
- 校园阅读活动的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E7%A8%B3%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%B5%8B_%E8%99%8E%E5%97%85%E8%AE%BF%E8%B0%88?/lsb=542
- 小微企业服务的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E7%A8%B3%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%B5%8B_%E8%99%8E%E5%97%85%E8%AE%BF%E8%B0%88?/3qo=WAZ
- 城市社区治理的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E7%A8%B3%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7%E5%92%8C%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/089
- 课后服务体验的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E7%A8%B3%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7%E5%92%8C%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/ijx
- 公交站点体验的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E7%A8%B3%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7%E5%92%8C%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/DOV
- 数字素养提升的资源整合思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E7%A8%B3%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7%E5%92%8C%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/986=zkp
- 社区公共卫生的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E7%A8%B3%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7%E5%92%8C%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/ihx=955
- 垃圾分类指导的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E7%A8%B3%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%8A%80%E5%B7%A7%E5%92%8C%E6%96%B9%E6%B3%95_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/6O8=uxT
- 公共服务预约的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%9C%80%E7%89%9B%E6%9C%80%E7%A8%B3%E6%9C%80%E5%AE%89%E5%85%A8_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/493
- 社区宣传栏更新中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%9C%80%E7%89%9B%E6%9C%80%E7%A8%B3%E6%9C%80%E5%AE%89%E5%85%A8_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/rck
- 环境教育课程的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%9C%80%E7%89%9B%E6%9C%80%E7%A8%B3%E6%9C%80%E5%AE%89%E5%85%A8_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/1XG
- 数字公共文化的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%9C%80%E7%89%9B%E6%9C%80%E7%A8%B3%E6%9C%80%E5%AE%89%E5%85%A8_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/902=dzh
- 数字生活课堂的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%9C%80%E7%89%9B%E6%9C%80%E7%A8%B3%E6%9C%80%E5%AE%89%E5%85%A8_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/pzb=280
- 科学健身方法的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E6%8A%80%E5%B7%A7%E6%9C%80%E7%89%9B%E6%9C%80%E7%A8%B3%E6%9C%80%E5%AE%89%E5%85%A8_%E8%99%8E%E6%89%91%E6%99%9A%E6%8A%A5?/VJL=UXA
- 乡村产业科普的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%95%85%E6%B8%B8?/652
- 家庭收纳实践的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%95%85%E6%B8%B8?/vqa
- 城市步行友好中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%95%85%E6%B8%B8?/NxV
- 家庭科学教育的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%95%85%E6%B8%B8?/743=yuc
- 城市适老服务的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%95%85%E6%B8%B8?/hdv=389
- 社区互助网络的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%AF%BC%E5%B8%88%E5%B8%A6%E4%BA%BA%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_36%E6%B0%AA%E7%95%85%E6%B8%B8?/Mon=afG
- 青少年职业启蒙的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/036
- 药品使用科普的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/tqi
- 社区活动空间的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/KAT
- 家庭志愿活动的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/818=oqa
- 公园亲子设施的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/jkf=167
- 个人数据管理的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%A8%B3%E5%AE%9A%E8%AE%A1%E5%88%92%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88QQ_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/j9c=ac8
- 社区便民集市的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8?/303
- 青年就业服务从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8?/ons
- 农产品消费体验的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8?/UOL
- 青少年心理健康的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8?/496=spu
- 城市公共厕所的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8?/xgi=739
- 城市农夫市集的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E9%92%B1%E7%9A%84%E8%BD%AF%E4%BB%B6_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8?/6Xo=Hvn
- 社区菜市场服务的资源整合思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%80%8E%E4%B9%88%E5%88%A9%E7%94%A8%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B5%9A%E9%92%B1_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/863
- 文化讲座服务的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%80%8E%E4%B9%88%E5%88%A9%E7%94%A8%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B5%9A%E9%92%B1_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/tql
- 儿童运动体验的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%80%8E%E4%B9%88%E5%88%A9%E7%94%A8%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B5%9A%E9%92%B1_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/MUA
- 社区设施共享的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%80%8E%E4%B9%88%E5%88%A9%E7%94%A8%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B5%9A%E9%92%B1_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/424=ugl
- 家庭节能设备的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%80%8E%E4%B9%88%E5%88%A9%E7%94%A8%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B5%9A%E9%92%B1_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/jxz=003
- 社区文化传播的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E6%80%8E%E4%B9%88%E5%88%A9%E7%94%A8%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B5%9A%E9%92%B1_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/sLt=dLO
- 公园无障碍服务从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/346
- 食品安全科普的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/wwf
- 社区托育服务的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/9yE
- 通勤路线规划的空间设计要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/690=qxf
- 社区公共餐饮的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/kso=978
- 环境监测科普的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4_%E7%9F%A5%E4%B9%8E%E8%A1%8C%E6%83%85?/vHs=tsN
- 社区宣传栏更新的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E7%BE%A4_%E9%9B%85%E8%99%8E%E8%83%BD%E6%BA%90?/064
- 小区公共照明的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E7%BE%A4_%E9%9B%85%E8%99%8E%E8%83%BD%E6%BA%90?/upa
- 生活技能分享的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E7%BE%A4_%E9%9B%85%E8%99%8E%E8%83%BD%E6%BA%90?/hrp
- 口袋公园建设的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E7%BE%A4_%E9%9B%85%E8%99%8E%E8%83%BD%E6%BA%90?/472=xun
- 数字档案服务中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E7%BE%A4_%E9%9B%85%E8%99%8E%E8%83%BD%E6%BA%90?/hwq=920
- 课后服务体验的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A%E7%BE%A4_%E9%9B%85%E8%99%8E%E8%83%BD%E6%BA%90?/Yh0=QAw
- 公共服务评价的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/360
- 家庭食品保存的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/his
- 青年志愿活动的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/AEJ
- 家庭收纳实践的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/012=kps
- 健康饮水科普的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/fqt=087
- 社区便利生活的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81%E7%BE%A4%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/RV1=qtY
- 科普展览体验的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/564
- 老年友好服务中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/vde
- 城市可持续生活的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/3zk
- 健康饮水科普的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/805=tfl
- 街区小店体验的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/ogq=167
- 邻里互助活动的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99%E8%AE%A1%E5%88%92_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/UwC=plI
- 社区儿童活动的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%83%AD%E6%A6%9C?/177
- 电动汽车充电的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%83%AD%E6%A6%9C?/jdz
- 社区邻里服务的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%83%AD%E6%A6%9C?/eRz
- 城市公共自行车的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%83%AD%E6%A6%9C?/461=pyx
- 社区托育服务的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%83%AD%E6%A6%9C?/mce=311
- 城市步行环境的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%83%AD%E6%A6%9C?/IQW=BNH
- 在线学习体验的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E7%9B%88%E5%88%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A4%B4%E6%9D%A1?/462
- 乡村公共服务的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E7%9B%88%E5%88%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A4%B4%E6%9D%A1?/gdz
- 家庭用电安全的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E7%9B%88%E5%88%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A4%B4%E6%9D%A1?/N73
- 公共卫生宣传的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E7%9B%88%E5%88%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A4%B4%E6%9D%A1?/868=lpy
- 灵活就业交流的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E7%9B%88%E5%88%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A4%B4%E6%9D%A1?/grb=382
- 创业经验分享的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E7%9B%88%E5%88%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A4%B4%E6%9D%A1?/5AQ=7pV
- 家庭饮食安排的资源整合思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/393
- 音乐欣赏活动的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/eek
- 城市住房服务从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/d7P
- 开源技术交流的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/125=ktq
- 公共服务咨询的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/zyi=914
- 城市博物馆活动的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1%E4%B8%80%E5%AF%B9%E4%B8%80_%E6%96%87%E6%97%85%E8%B4%A2%E7%BB%8F?/7ym=LNW
- 运动安全知识的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%88%90%E5%8A%9F%E5%9B%9E%E6%9C%AC%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%94%B6%E8%97%8F?/904
- 骑行路线规划的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%88%90%E5%8A%9F%E5%9B%9E%E6%9C%AC%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%94%B6%E8%97%8F?/nji
- 居民健康教育的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%88%90%E5%8A%9F%E5%9B%9E%E6%9C%AC%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%94%B6%E8%97%8F?/Few
- 安全出行教育的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%88%90%E5%8A%9F%E5%9B%9E%E6%9C%AC%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%94%B6%E8%97%8F?/954=eqv
- 城市树木认养的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%88%90%E5%8A%9F%E5%9B%9E%E6%9C%AC%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%94%B6%E8%97%8F?/lts=872
- 城市公共艺术的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%88%90%E5%8A%9F%E5%9B%9E%E6%9C%AC%E4%B8%80%E5%AF%B9%E4%B8%80%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%94%B6%E8%97%8F?/Rhs=4kS
- 农村环境治理的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%8D%9A%E5%AE%A2?/381
- 小区停车协商的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%8D%9A%E5%AE%A2?/swg
- 社区故事采集的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%8D%9A%E5%AE%A2?/ofJ
- 社区故事采集的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%8D%9A%E5%AE%A2?/219=quw
- 智慧停车服务的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%8D%9A%E5%AE%A2?/ukt=106
- 食品安全科普的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E5%8D%9A%E5%AE%A2?/DC7=3tS
- 信息无障碍体验的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E4%BA%BA%E5%9B%9E%E6%9C%AC%E7%9A%84%E6%9C%80%E5%BC%BA%E5%AF%BC%E5%B8%88_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/961
- 农村环境治理的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E4%BA%BA%E5%9B%9E%E6%9C%AC%E7%9A%84%E6%9C%80%E5%BC%BA%E5%AF%BC%E5%B8%88_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/gle
- 机器人科普活动的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E4%BA%BA%E5%9B%9E%E6%9C%AC%E7%9A%84%E6%9C%80%E5%BC%BA%E5%AF%BC%E5%B8%88_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/78n
- 学校体育活动的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E4%BA%BA%E5%9B%9E%E6%9C%AC%E7%9A%84%E6%9C%80%E5%BC%BA%E5%AF%BC%E5%B8%88_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/218=ptm
- 全民阅读推广的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E4%BA%BA%E5%9B%9E%E6%9C%AC%E7%9A%84%E6%9C%80%E5%BC%BA%E5%AF%BC%E5%B8%88_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/rzx=578
- 城市公共艺术有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%9C%9F%E6%AD%A3%E8%83%BD%E5%B8%A6%E4%BA%BA%E5%9B%9E%E6%9C%AC%E7%9A%84%E6%9C%80%E5%BC%BA%E5%AF%BC%E5%B8%88_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/Flt=gb5
- 运动安全知识的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E9%87%91%E7%89%8C%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/360
- 地方民俗记录的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E9%87%91%E7%89%8C%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/xpd
- 社区快递服务的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E9%87%91%E7%89%8C%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/WLz
- 基层医疗预约的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E9%87%91%E7%89%8C%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/819=dxo
- 社区儿童活动的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E9%87%91%E7%89%8C%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/qsx=969
- 乡村文化空间的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B8%A6%E4%BA%BA%E6%9C%80%E7%A8%B3%E7%9A%84%E9%87%91%E7%89%8C%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/0VE=XV8
- 文化遗产保护科普的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BA%E7%89%88%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/181
- 在线学习体验的空间设计要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BA%E7%89%88%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/uqp
- 亲子科普活动的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BA%E7%89%88%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/CIt
- 乡村电商实践的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BA%E7%89%88%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/185=kit
- 街头绿植养护从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BA%E7%89%88%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/yxk=144
- 学校食育活动的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BA%E7%89%88%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%BF%AB%E6%89%8B%E4%BA%BA%E5%A4%A7?/pY1=2HU
- 社区休闲设施的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BAapp_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/724
- 个人信息保护中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BAapp_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/rug
- 社区读书角建设的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BAapp_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/cfp
- 亲子阅读活动的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BAapp_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/068=zla
- 传统节日科普的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BAapp_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/xod=820
- 老年人日常照护的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E6%89%8B%E6%9C%BAapp_36%E6%B0%AA%E7%A8%8E%E5%8A%A1?/CDh=wov
- 公共服务评价的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%BD%A9%E7%A5%9E_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/174
- 信息无障碍体验的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%BD%A9%E7%A5%9E_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/rqq
- 数字支付体验的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%BD%A9%E7%A5%9E_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/GnV
- 信息无障碍体验的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%BD%A9%E7%A5%9E_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/822=rpb
- 社区公共议事的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%BD%A9%E7%A5%9E_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/uhi=931
- 社区信息发布的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%AE%98%E6%96%B9%E5%BF%AB3%E5%BD%A9%E7%A5%9E_%E5%93%94%E5%93%A9%E5%9C%88%E5%AD%90?/faO=QXZ
- 老年人出行服务的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A?/564
- 非遗体验活动的服务细节记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A?/zju
- 城市应急广播中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A?/nF4
- 机器学习入门的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A?/789=hch
- 数字支付体验的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A?/kfu=663
- 节气饮食文化的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E5%B9%B8%E8%BF%90%E5%BF%AB3app%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A?/9TQ=ugq
- 基层医疗预约的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/308
- 软件开发学习的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/gmp
- 家庭科学教育中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/VKU
- 传统节日科普的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/529=rvo
- 数字阅读服务中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/ulq=400
- 家庭环保行动的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8_%E7%9F%A5%E4%B9%8E%E5%BF%AB%E6%8A%A5?/raF=Pk0
- 社区生活指南的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E6%97%B6%E9%97%B4%E8%A1%A8_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/688
- 社区庭院绿化的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E6%97%B6%E9%97%B4%E8%A1%A8_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/tio
- 传统手工艺体验的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E6%97%B6%E9%97%B4%E8%A1%A8_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/quT
- 电子商务服务中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E6%97%B6%E9%97%B4%E8%A1%A8_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/543=lpa
- 家庭节能设备的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E6%97%B6%E9%97%B4%E8%A1%A8_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/ilr=850
- 机器人科普活动中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E8%AE%A1%E5%88%92%E6%97%B6%E9%97%B4%E8%A1%A8_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/tLr=W31
- 城市人文观察的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%92%8C%E5%80%BC%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/019
- 社区宠物管理的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%92%8C%E5%80%BC%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/tvw
- 街区小店体验从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%92%8C%E5%80%BC%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/HR4
- 儿童友好街区的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%92%8C%E5%80%BC%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/445=bnn
- 社区邻里服务的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%92%8C%E5%80%BC%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/zzz=922
- 家庭科学教育的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%92%8C%E5%80%BC%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E5%AE%8F%E8%A7%82?/0V8=2OD
- 街区小店体验的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%92%8C%E5%80%BC%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/518
- 城市骑行环境的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%92%8C%E5%80%BC%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/xwf
- 城市公共艺术的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%92%8C%E5%80%BC%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/Lu1
- 数字艺术创作的资源整合思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%92%8C%E5%80%BC%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/522=gno
- 数字支付体验的资源整合思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%92%8C%E5%80%BC%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/szk=071
- 城市公共标识的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%92%8C%E5%80%BC%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/aME=kG4
- 社区安全巡查的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%21_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/762
- 科学信息获取的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%21_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/odn
- 家庭阅读计划的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%21_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/8JW
- 公共空间导览的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%21_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/109=for
- 小区公共照明从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%21_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/biq=766
- 乡村生活观察的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%21_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/j7j=ahh
- 公园亲子设施的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%92%8C%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E5%8C%BB%E8%8D%AF?/616
- 绿色建筑理念的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%92%8C%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E5%8C%BB%E8%8D%AF?/dob
- 农产品消费体验的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%92%8C%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E5%8C%BB%E8%8D%AF?/Zje
- 基层健康服务的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%92%8C%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E5%8C%BB%E8%8D%AF?/788=qrf
- 无障碍信息设计的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%92%8C%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E5%8C%BB%E8%8D%AF?/ujb=763
- 家庭志愿活动的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%92%8C%E8%A7%84%E5%BE%8B_%E9%9B%85%E8%99%8E%E5%8C%BB%E8%8D%AF?/gtq=qXD
- 基层健康档案的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC_%E6%8A%96%E9%9F%B3%E8%A7%A3%E5%AF%86?/813
- 公共空间照明的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC_%E6%8A%96%E9%9F%B3%E8%A7%A3%E5%AF%86?/kiu
- 数字阅读服务的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC_%E6%8A%96%E9%9F%B3%E8%A7%A3%E5%AF%86?/5MZ
- 零废弃生活尝试的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC_%E6%8A%96%E9%9F%B3%E8%A7%A3%E5%AF%86?/043=ubw
- 城市雨天出行的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC_%E6%8A%96%E9%9F%B3%E8%A7%A3%E5%AF%86?/fvx=945
- 城市慢行系统的服务细节记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E5%92%8C%E5%80%BC_%E6%8A%96%E9%9F%B3%E8%A7%A3%E5%AF%86?/ZBz=ojU
- 社区科普课堂的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/382
- 家庭环保行动的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/lix
- 乡村生态旅游中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/gyb
- 软件开发学习的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/496=emj
- 在线学习体验的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/xoa=660
- 家庭园艺实践的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%A8%8E%E5%8A%A1?/vMe=Yl0
- 社区便利生活的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%B0%8F%E5%80%8D%E6%8A%95_%E5%BF%AB%E6%89%8B%E6%B1%BD%E8%BD%A6?/370
- 校园阅读活动的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%B0%8F%E5%80%8D%E6%8A%95_%E5%BF%AB%E6%89%8B%E6%B1%BD%E8%BD%A6?/mmw
- 数字创作工具的空间设计要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%B0%8F%E5%80%8D%E6%8A%95_%E5%BF%AB%E6%89%8B%E6%B1%BD%E8%BD%A6?/iO6
- 城市应急科普的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%B0%8F%E5%80%8D%E6%8A%95_%E5%BF%AB%E6%89%8B%E6%B1%BD%E8%BD%A6?/867=mhy
- 社区手工活动的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%B0%8F%E5%80%8D%E6%8A%95_%E5%BF%AB%E6%89%8B%E6%B1%BD%E8%BD%A6?/rvo=041
- 开放数据应用的协作机制梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%B0%8F%E5%80%8D%E6%8A%95_%E5%BF%AB%E6%89%8B%E6%B1%BD%E8%BD%A6?/ja8=DAc
- 本地消费场景的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/710
- 骑行路线规划的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/wey
- 乡村生活观察的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/SWC
- 本地旅行体验的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/475=sfe
- 青少年职业启蒙的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/yjy=102
- 生活垃圾回收的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/LIx=jgG
- 市民意见收集的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%80%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E4%B8%80%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/790
- 地方戏曲体验中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%80%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E4%B8%80%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/qeh
- 绿色建筑理念的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%80%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E4%B8%80%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/sJy
- 城市骑行环境的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%80%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E4%B8%80%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/833=ymd
- 社区设施共享的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%80%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E4%B8%80%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/dim=537
- 家庭饮食安排的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%80%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E4%B8%80%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/aAZ=dVh
- 乡村公共阅读的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/807
- 科学睡眠习惯的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/fhd
- 健康步道使用的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/lL5
- 音乐欣赏活动的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/228=wmq
- 家庭网络使用的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/lmf=778
- 公共设施使用的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E8%99%8E%E5%97%85%E5%9B%BE%E9%89%B4?/9dQ=jrl
- 社区公共卫生的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/347
- 街头绿植养护的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/xyr
- 社区手工活动的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/zxv
- 儿童安全出行的服务细节记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/971=wmk
- 城市运动公园的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/zli=421
- 基层健康服务的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%B0%8F%E5%8F%8C%E5%8D%95%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%94%BE?/Z21=HOf
- 家庭食品保存的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E9%A1%BA%E5%8F%A3%E6%BA%9C_360%E5%88%9B%E6%8A%95?/522
- 旧物循环利用的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E9%A1%BA%E5%8F%A3%E6%BA%9C_360%E5%88%9B%E6%8A%95?/foo
- 社区体育组织的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E9%A1%BA%E5%8F%A3%E6%BA%9C_360%E5%88%9B%E6%8A%95?/033
- 文明养宠科普的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E9%A1%BA%E5%8F%A3%E6%BA%9C_360%E5%88%9B%E6%8A%95?/996=kup
- 社区托育服务的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E9%A1%BA%E5%8F%A3%E6%BA%9C_360%E5%88%9B%E6%8A%95?/fgc=751
- 生活垃圾减量的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E9%A1%BA%E5%8F%A3%E6%BA%9C_360%E5%88%9B%E6%8A%95?/Yal=0WS
- 科普展览体验的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%88%BF%E4%BA%A7?/413
- 社区手工活动的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%88%BF%E4%BA%A7?/icx
- 家庭饮食安排的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%88%BF%E4%BA%A7?/HGC
- 家庭环保习惯的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%88%BF%E4%BA%A7?/630=zpe
- 公共服务沟通的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%88%BF%E4%BA%A7?/gar=253
- 公共图书馆服务的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%90%E6%88%BF%E4%BA%A7?/aum=N3x
- 信息无障碍体验中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3%E9%95%BF%E9%BE%99%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/444
- 社区共享书架的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3%E9%95%BF%E9%BE%99%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/nqm
- 乡村文化活动的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3%E9%95%BF%E9%BE%99%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/sZD
- 户外活动组织有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3%E9%95%BF%E9%BE%99%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/530=vjj
- 节日文化体验的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3%E9%95%BF%E9%BE%99%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/elj=001
- 数字生活课堂的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E5%BF%AB3%E9%95%BF%E9%BE%99%E9%A1%BA%E9%BE%99%E7%A0%8D%E9%BE%99%E6%8A%80_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%8F%E8%A7%82?/aJn=eYm
- 青年志愿活动的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E5%B0%8F%E7%AA%8D%E9%97%A8_360%E5%8A%A8%E6%BC%AB?/997
- 社区手工活动的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E5%B0%8F%E7%AA%8D%E9%97%A8_360%E5%8A%A8%E6%BC%AB?/txe
- 老年人出行服务的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E5%B0%8F%E7%AA%8D%E9%97%A8_360%E5%8A%A8%E6%BC%AB?/83f
- 社区设施共享的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E5%B0%8F%E7%AA%8D%E9%97%A8_360%E5%8A%A8%E6%BC%AB?/092=rta
- 社区读书角建设的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E5%B0%8F%E7%AA%8D%E9%97%A8_360%E5%8A%A8%E6%BC%AB?/urd=541
- 青少年职业启蒙的空间设计要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB%E4%B8%89%E7%A0%8D%E9%BE%99%E5%B0%8F%E7%AA%8D%E9%97%A8_360%E5%8A%A8%E6%BC%AB?/f18=joU
- 绿色校园实践的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80%E7%9A%84%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%8D%E9%A5%B0?/077
- 城市生活服务的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80%E7%9A%84%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%8D%E9%A5%B0?/shd
- 职业技能学习的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80%E7%9A%84%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%8D%E9%A5%B0?/InY
- 骑行路线规划的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80%E7%9A%84%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%8D%E9%A5%B0?/379=dgy
- 社区活动策划的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80%E7%9A%84%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%8D%E9%A5%B0?/uaq=806
- 家庭环保习惯中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E6%9C%80%E7%A8%B3%E5%AE%9A%E5%9B%9E%E8%A1%80%E7%9A%84%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%8D%E9%A5%B0?/79Y=qN7
- 药品使用科普的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E6%89%8D%E8%83%BD%E5%81%9A%E5%88%B0%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%91%A2_36%E6%B0%AA%E6%9C%9F%E8%B4%A7?/431
- 节能家电使用从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E6%89%8D%E8%83%BD%E5%81%9A%E5%88%B0%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%91%A2_36%E6%B0%AA%E6%9C%9F%E8%B4%A7?/wxn
- 健康饮食教育的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E6%89%8D%E8%83%BD%E5%81%9A%E5%88%B0%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%91%A2_36%E6%B0%AA%E6%9C%9F%E8%B4%A7?/o63
- 生成式工具使用的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E6%89%8D%E8%83%BD%E5%81%9A%E5%88%B0%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%91%A2_36%E6%B0%AA%E6%9C%9F%E8%B4%A7?/768=hsb
- 街区小店体验从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E6%89%8D%E8%83%BD%E5%81%9A%E5%88%B0%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%91%A2_36%E6%B0%AA%E6%9C%9F%E8%B4%A7?/uzc=662
- 家庭陪伴活动的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%A6%82%E4%BD%95%E6%89%8D%E8%83%BD%E5%81%9A%E5%88%B0%E5%9B%9E%E8%A1%80%E4%B8%8A%E5%B2%B8%E5%91%A2_36%E6%B0%AA%E6%9C%9F%E8%B4%A7?/fdm=1uw
- 家庭防灾准备的协作机制梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E7%BD%91%E5%9D%80_%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/085
- 家庭网络使用的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E7%BD%91%E5%9D%80_%E6%BE%8E%E6%B9%83%E5%BD%B1%E8%A7%86?/kqu

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
