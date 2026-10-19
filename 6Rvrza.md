# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:21**

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

- 环境监测科普的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_588%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E8%AF%BB%E6%8A%A5?/che=017
- 本地旅行体验的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_588%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E8%AF%BB%E6%8A%A5?/7Xk=IrP
- 数字艺术创作的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_588%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%8A%95%E8%B5%84?/198
- 数字艺术创作中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_588%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%8A%95%E8%B5%84?/gsv
- 休闲运动入门的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_588%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%8A%95%E8%B5%84?/NAT
- 城市生活记录的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_588%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%8A%95%E8%B5%84?/821=mvw
- 家庭陪伴活动的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_588%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%8A%95%E8%B5%84?/klw=646
- 城市文明出行的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_588%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%8A%95%E8%B5%84?/hmd=Isb
- 城市骑行环境的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_588%E5%BD%A9%E7%A5%A8-APP_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/717
- 社区故事采集的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_588%E5%BD%A9%E7%A5%A8-APP_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/fpb
- 在线学习体验的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_588%E5%BD%A9%E7%A5%A8-APP_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/I5k
- 节能家电使用的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_588%E5%BD%A9%E7%A5%A8-APP_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/399=ots
- 城市公共艺术中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_588%E5%BD%A9%E7%A5%A8-APP_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/obk=802
- 社区故事采集的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_588%E5%BD%A9%E7%A5%A8-APP_%E6%8A%96%E9%9F%B3%E8%BD%AC%E8%BD%BD?/w1a=2Q1
- 社区公共卫生的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_588%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%99%BE%E7%A7%91?/897
- 节能生活方式的便利性观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_588%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%99%BE%E7%A7%91?/pwo
- 公共设施使用的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_588%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%99%BE%E7%A7%91?/KaH
- 无障碍出行的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_588%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%99%BE%E7%A7%91?/349=iwq
- 公共交通信息服务的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_588%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%99%BE%E7%A7%91?/rmh=923
- 社区知识分享的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_588%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%99%BE%E7%A7%91?/vBs=MGa
- 社区健康讲座的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_588%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A8%B1%E4%B9%90?/144
- 家庭养老规划的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_588%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A8%B1%E4%B9%90?/yiv
- 机器学习入门的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_588%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A8%B1%E4%B9%90?/2Cx
- 家庭阅读计划的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_588%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A8%B1%E4%B9%90?/596=qdj
- 数字资源检索的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_588%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A8%B1%E4%B9%90?/qss=817
- 全民阅读推广的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_588%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A8%B1%E4%B9%90?/poL=J4R
- 家庭养老规划的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_588%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/755
- 节日文化体验的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_588%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/eni
- 城市运动公园的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_588%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/Lqp
- 农业科普体验的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_588%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/100=xvw
- 节约用水实践的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_588%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/xzz=167
- 数字素养提升中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_588%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/I4n=7JL
- 科学信息获取的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_588%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/660
- 数字支付体验的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_588%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/low
- 家庭食品保存中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_588%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/JcD
- 骑行路线规划的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_588%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/380=ugo
- 街区道路维护的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_588%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/ant=565
- 城乡交通衔接中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_588%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/gaj=Zce
- 社区活动空间的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_588%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/345
- 社区读书角建设的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_588%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/ktz
- 城市夜间照明的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_588%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/eTw
- 个人信息保护的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_588%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/116=ikt
- 城市绿色交通的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_588%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/ifb=316
- 环境监测科普的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_588%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%81%A5%E5%BA%B7?/gsW=Gy3
- 音乐欣赏活动的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_588%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/070
- 城乡交流活动的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_588%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/tax
- 公益活动组织的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_588%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/0gm
- 便民信息查询的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_588%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/218=pgr
- 青年志愿活动的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_588%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/yly=219
- 家庭环保习惯的流程优化思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5_588%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/8PF=LoM
- 居家适老化改造的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_588%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/159
- 社区托育服务的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_588%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/pdh
- 城市绿色交通的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_588%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/XtH
- 物业服务沟通的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_588%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/455=qxa
- 职业技能学习的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_588%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/ezm=431
- 医院导诊服务的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_588%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E6%B3%95%E6%B2%BB?/DNz=oq3
- 社区环保活动中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_588%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/571
- 人工智能科普的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_588%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/yce
- 人工智能科普的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_588%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/57H
- 公共服务数字化的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_588%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/355=vff
- 全民健身活动的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_588%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/saz=412
- 城市慢行系统的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_588%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BD%B1%E8%A7%86?/hQV=DNa
- 跨代沟通活动的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_588%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/105
- 小微企业服务的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_588%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/gji
- 家庭饮食安排的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_588%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/YAo
- 社区读书角建设的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_588%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/622=zhw
- 健康步道使用的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_588%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/fzf=577
- 公共服务沟通的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_588%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E6%9C%AD%E8%AE%B0?/YAw=AP2
- 社区信息发布的流程优化思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_58%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/879
- 基层服务创新的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_58%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/zhz
- 社区艺术活动的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_58%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/gB8
- 小区公共照明的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_58%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/572=qqo
- 地方戏曲体验中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_58%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/akj=654
- 城市生活记录从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_58%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/8ns=KZ6
- 社区邻里服务的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_58%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/159
- 校园安全教育的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_58%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/ygg
- 城市慢跑路线的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_58%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/KQ3
- 公共服务数字化的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_58%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/071=tcv
- 城市夜间照明的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_58%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/htw=497
- 城市博物馆服务的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_58%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/qP0=HNr
- 青年就业服务的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94?/671
- 数字地图应用的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94?/ech
- 城市共享单车的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94?/FKf
- 公共空间休憩的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94?/499=gwh
- 家庭用电安全的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94?/bam=630
- 社会体育指导的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94?/L0u=tlz
- 数字政务体验的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_58%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/463
- 城市农夫市集的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_58%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/tss
- 社区科普课堂的流程优化思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_58%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/Lvy
- 绿色快递包装中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_58%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/426=sii
- 公益活动组织的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_58%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/jjs=579
- 老年人文化生活从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_58%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/bbW=C8Q
- 线上办事服务的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_58%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/449
- 城市绿色交通的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_58%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/wzg
- 光伏知识科普的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_58%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/r4I
- 公共空间照明的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_58%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/414=lqj
- 社区慢性病防控的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_58%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/ulr=453
- 公共空间导览的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_58%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%90%8C%E8%BE%89%E8%B4%A2%E7%BB%8F?/yDO=k9Q
- 城市公共艺术的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_58%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/264
- 城乡交通衔接的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_58%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/ktq
- 生活垃圾减量的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_58%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/xaY
- 安全出行教育的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_58%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/016=frc
- 城市农夫市集的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_58%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/fxp=228
- 新能源出行的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_58%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%B3%95%E5%BE%8B?/YKl=Bbf
- 城市博物馆活动的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/469
- 家庭节能实践的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/nbt
- 生活垃圾减量的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/PD7
- 在线学习体验的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/462=wdo
- 校园安全教育的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/zsv=917
- 环境监测科普的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/rnY=eq2
- 公共文化活动的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%B8%B8%E6%88%8F?/011
- 文明养宠科普的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%B8%B8%E6%88%8F?/xcb
- 城市生活服务的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%B8%B8%E6%88%8F?/fZa
- 儿童运动体验的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%B8%B8%E6%88%8F?/770=gtu
- 城市公共饮水中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%B8%B8%E6%88%8F?/gbl=293
- 邻里共享空间的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E6%B8%B8%E6%88%8F?/Lxj=KW8
- 校园社团活动的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B?/345
- 志愿者培训交流的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B?/bgy
- 公共文化活动的流程优化思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B?/cdX
- 城市微更新实践的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B?/474=xog
- 城市微更新实践的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B?/hzx=643
- 户外活动组织的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B?/jEb=wdx
- 公共空间照明的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_58%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/842
- 绿色生活实践的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_58%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/ett
- 社区庭院绿化的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_58%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/BW1
- 本地旅行体验的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_58%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/705=pib
- 家庭饮食安排的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_58%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/cuq=334
- 社区学习活动的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_58%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/eSw=Ang
- 社区学习活动的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_58%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E8%83%BD%E6%BA%90?/559
- 校园阅读活动的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_58%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E8%83%BD%E6%BA%90?/mer
- 光伏知识科普的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_58%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E8%83%BD%E6%BA%90?/g4g
- 社区公共卫生中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_58%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E8%83%BD%E6%BA%90?/868=bxa
- 新能源出行从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_58%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E8%83%BD%E6%BA%90?/rbu=788
- 城市适老服务的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_58%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E8%83%BD%E6%BA%90?/dIG=Cnb
- 老年人文化生活的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_58%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/849
- 社区互助网络从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_58%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/zfs
- 市民热线服务的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_58%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/nXH
- 生活技能分享的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_58%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/035=sse
- 社区学习活动的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_58%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/zmw=617
- 就业技能培训中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_58%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%85%AC%E5%BC%80%E8%AF%BE?/lfN=IVd
- 公共空间休憩从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_58%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/001
- 社区防暑服务的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_58%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/hxo
- 人工智能科普的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_58%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/rJg
- 租房信息服务的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_58%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/764=kwn
- 家庭网络使用的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_58%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/zlj=435
- 气象科普传播的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_58%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/Bpa=r96
- 社区学习活动的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/706
- 线上阅读资源的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/jnm
- 垃圾分类指导的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/dSK
- 小区停车协商的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/600=hcb
- 亲子科普活动的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/eif=458
- 城市宠物友好空间的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/PAR=YD0
- 创业经验分享的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_58%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/821
- 社区便民集市的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_58%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/ziy
- 健康信息获取的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_58%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/zRY
- 社区环保活动的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_58%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/261=sgn
- 儿童友好街区的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_58%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/ouz=305
- 社区手工活动的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_58%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%AD%E8%9E%8D%E8%B4%A2%E7%BB%8F?/BQc=olR
- 社区公共餐饮的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_58%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E7%BE%8E%E5%A6%86?/763
- 社区菜市场服务的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_58%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E7%BE%8E%E5%A6%86?/fpo
- 城市文化路线的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_58%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E7%BE%8E%E5%A6%86?/Us2
- 数字支付体验的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_58%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E7%BE%8E%E5%A6%86?/238=jhn
- 开放式学习空间的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_58%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E7%BE%8E%E5%A6%86?/wdt=880
- 公共场所导视的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_58%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%8A%96%E9%9F%B3%E7%BE%8E%E5%A6%86?/NNs=e4l
- 社区运动空间的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%B0%E9%97%BB?/082
- 城市空气科普的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%B0%E9%97%BB?/gfx
- 农产品品牌传播有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%B0%E9%97%BB?/W5D
- 低碳社区实践的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%B0%E9%97%BB?/986=jvn
- 志愿服务平台的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%B0%E9%97%BB?/ila=299
- 社区学习活动的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%B0%E9%97%BB?/rHK=C1D
- 小微企业服务的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/362
- 邻里共享空间的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/mzo
- 课后服务体验从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/Mcc
- 社区环保活动的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/989=dnp
- 家庭收纳实践的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/prp=483
- 在线教育体验的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/FmT=uaB
- 绿色校园实践的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_58%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E8%BA%AB?/138
- 社区快递服务有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_58%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E8%BA%AB?/nvv
- 家庭收纳实践的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_58%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E8%BA%AB?/ENI
- 社区科普课堂的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_58%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E8%BA%AB?/198=cil
- 绿色办公实践的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_58%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E8%BA%AB?/tri=886
- 绿色校园实践的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_58%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E8%BA%AB?/OgC=kQC
- 休闲运动入门的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E6%96%B9?/636
- 地方美食文化的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E6%96%B9?/wpe
- 运动安全知识的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E6%96%B9?/xTR
- 公共设施维护的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E6%96%B9?/611=vds
- 家庭急救准备从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E6%96%B9?/vum=880
- 基层医疗预约的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_58%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%B0%E6%96%B9?/r2t=wUo
- 开放式学习空间的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/164
- 节气饮食文化的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/khp
- 灵活就业交流的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/tpl
- 社区托育服务的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/920=lem
- 城市人文观察的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/tvd=689
- 城市水环境观察的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/kAa=Ji8
- 乡村阅读空间中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_58%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/016
- 灵活就业交流的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_58%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/nun
- 智能手机助老的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_58%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/EvK
- 城市绿色交通的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_58%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/147=juz
- 家庭健康管理的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_58%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/wpq=708
- 城市公共自行车的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_58%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/zAd=NBT
- 儿童友好街区的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/928
- 家庭节能设备的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/mry
- 小区公共照明的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/Ypt
- 城市水环境观察的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/056=roe
- 便民服务地图的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/swb=466
- 城市绿色交通的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%A7%91%E6%8A%80?/t6N=qg8
- 公共服务沟通的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E4%BA%BA%E5%A4%A7?/034
- 公共空间导览的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E4%BA%BA%E5%A4%A7?/uuj
- 城市生活服务有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E4%BA%BA%E5%A4%A7?/iAL
- 便民信息查询从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E4%BA%BA%E5%A4%A7?/843=dwe
- 电子商务服务的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E4%BA%BA%E5%A4%A7?/cvt=210
- 社区运动空间的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E4%BA%BA%E5%A4%A7?/Y9l=1J7
- 乡村电商实践的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%88%B8%E5%95%86?/833
- 智慧城市体验从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%88%B8%E5%95%86?/cvk
- 健康饮水科普的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%88%B8%E5%95%86?/5ED
- 基层健康档案的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%88%B8%E5%95%86?/479=frx
- 小区电梯维护的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%88%B8%E5%95%86?/hpl=805
- 绿色消费选择的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%88%B8%E5%95%86?/CyR=shy
- 农产品消费体验的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E7%AD%94?/745
- 家庭消费规划的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E7%AD%94?/kbw
- 家庭用电安全的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E7%AD%94?/iQk
- 乡村生态观察的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E7%AD%94?/626=hlg
- 家庭用电安全的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E7%AD%94?/sbp=653
- 开放数据应用的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%97%AE%E7%AD%94?/3rw=ygI
- 节约用水实践的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/185
- 就业技能培训的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/ywb
- 图书馆数字服务的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/L2Y
- 家庭教育交流的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/351=mwd
- 城市适老服务的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/ehw=563
- 社区共享书架的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B5%84%E8%AE%AF?/Vb8=wbB
- 科学健身方法的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E6%B8%AF%E8%82%A1?/000
- 安全出行教育的流程优化思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E6%B8%AF%E8%82%A1?/aez
- 生活服务数字化的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E6%B8%AF%E8%82%A1?/2Wu
- 城乡交通衔接的便利性观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E6%B8%AF%E8%82%A1?/916=bhb
- 城市博物馆服务的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E6%B8%AF%E8%82%A1?/yyn=822
- 公共服务指南的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%9F%A5%E4%B9%8E%E6%B8%AF%E8%82%A1?/mTa=DNq
- 社区协商议事的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/146
- 绿色生活实践的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/wut
- 老年学习活动的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/RgI
- 农业科普体验的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/339=rrk
- 节能家电使用的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/tri=444
- 社区知识分享的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/atD=TyS
- 周末休闲规划的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%B8%AF%E8%82%A1?/754
- 社区邻里服务的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%B8%AF%E8%82%A1?/qxs
- 公交无障碍服务的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%B8%AF%E8%82%A1?/2GM
- 城市步行友好的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%B8%AF%E8%82%A1?/764=igv
- 城市步行友好的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%B8%AF%E8%82%A1?/pdo=131
- 城市运动公园的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E6%B8%AF%E8%82%A1?/Hrs=49z
- 绿色生活实践的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/173
- 社区休闲设施中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_58%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%8D%9A%E5%AE%A2?/vts

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
