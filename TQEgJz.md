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

- 社区公共餐饮的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/rah=943
- 非遗课堂体验的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/khG=g8T
- 社区绿色空间中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/285
- 社区科普课堂的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/lmn
- 科学教育活动的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/0aB
- 休闲运动入门的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/670=dhz
- 家庭陪伴活动的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/hhn=745
- 家庭食品保存的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%8A%92%E6%9E%9C%E5%AE%8F%E8%A7%82?/Ri3=gKn
- 公园休闲体验的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AE%AF?/028
- 小区公共照明的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AE%AF?/grx
- 城市雨天出行的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AE%AF?/Ssb
- 日常摄影记录的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AE%AF?/888=jkm
- 地方美食文化的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AE%AF?/fgm=393
- 节气饮食文化的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AE%AF?/BOH=PQS
- 城市雨天出行的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%9B%86?/778
- 消防知识宣传的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%9B%86?/xtp
- 社区花园共建的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%9B%86?/Klp
- 城市体育设施的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%9B%86?/564=xyj
- 城市应急广播的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%9B%86?/fyh=615
- 儿童安全出行中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%9B%86?/yZz=cA5
- 个人数据管理的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/958
- 社区垃圾回收的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/lnn
- 骑行路线规划的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/GIC
- 学校食育活动的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/169=gcg
- 数字设备回收的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/zbb=512
- 儿童友好街区的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/Ify=Fpm
- 公交站点体验的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-APP_%E6%8A%96%E9%9F%B3%E8%AF%BB%E5%9B%BE?/976
- 公共卫生宣传的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-APP_%E6%8A%96%E9%9F%B3%E8%AF%BB%E5%9B%BE?/grg
- 社区花园共建的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-APP_%E6%8A%96%E9%9F%B3%E8%AF%BB%E5%9B%BE?/KCV
- 家庭急救准备的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-APP_%E6%8A%96%E9%9F%B3%E8%AF%BB%E5%9B%BE?/994=vwp
- 社区信息发布的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-APP_%E6%8A%96%E9%9F%B3%E8%AF%BB%E5%9B%BE?/mgx=939
- 数字阅读服务的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-APP_%E6%8A%96%E9%9F%B3%E8%AF%BB%E5%9B%BE?/l6K=VZQ
- 乡村公共服务的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/701
- 社区互助网络的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/lap
- 城市水环境观察的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/zm2
- 儿童友好空间的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/878=ecb
- 乡村休闲旅游的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/bea=882
- 地方旅游导览的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AF%84?/C1S=w7c
- 数字便民地图的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%A1%8C%E6%83%85?/850
- 读书会组织的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%A1%8C%E6%83%85?/jtf
- 城市应急科普的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%A1%8C%E6%83%85?/Fon
- 家庭理财科普的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%A1%8C%E6%83%85?/736=scz
- 公共交通接驳的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%A1%8C%E6%83%85?/wvl=748
- 社区停车服务的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%A1%8C%E6%83%85?/zXk=erV
- 居民健康教育中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E4%B8%93%E6%A0%8F?/183
- 智能手机助老的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E4%B8%93%E6%A0%8F?/jqg
- 家庭养老规划的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E4%B8%93%E6%A0%8F?/8qS
- 社区安全巡查的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E4%B8%93%E6%A0%8F?/587=cvs
- 社区共享书架的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E4%B8%93%E6%A0%8F?/gsn=234
- 老旧小区改造的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E4%B8%93%E6%A0%8F?/Tmt=UYa
- 小区停车协商的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/141
- 地方旅游导览的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/vls
- 智慧停车服务的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/D0x
- 城市骑行环境的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/727=cry
- 城市可持续生活的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/hke=725
- 城市休闲步道的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9F%8E%E4%BA%8B?/lhG=l0O
- 公共设施使用的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/471
- 城市绿道建设的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/kgd
- 数字创意课程的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/QY0
- 绿色校园实践的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/694=kww
- 文化场馆预约的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/nkj=451
- 社区公共议事的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E8%AE%BA%E5%9D%9B?/QOJ=zfy
- 社区宠物管理的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/808
- 社区绿色空间的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/imc
- 地方旅游导览的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/Fnc
- 社区读书角建设的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/976=znn
- 校园安全教育的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/xry=436
- 基层健康档案的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/XBU=KC7
- 农村环境治理的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/403
- 健康饮食教育的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/ghy
- 社区快递服务的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/xBa
- 亲子科普活动的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/470=vwi
- 农产品消费体验有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/myu=342
- 垃圾分类指导的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/vuO=2H5
- 数字生活课堂有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/344
- 开源技术交流的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/hry
- 城市环境志愿行动的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/n7M
- 青少年心理健康的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/894=dpv
- 社区便民服务的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/tgx=205
- 公共服务指南的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E5%AE%8F%E8%A7%82?/Wdo=9md
- 创业经验分享的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%8F%B8%E6%B3%95?/631
- 社区绿色空间的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%8F%B8%E6%B3%95?/uml
- 数字阅读服务的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%8F%B8%E6%B3%95?/XLV
- 街区道路维护的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%8F%B8%E6%B3%95?/528=gmg
- 社区科普课堂的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%8F%B8%E6%B3%95?/jkj=644
- 读书会组织的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%8F%B8%E6%B3%95?/sLy=iYB
- 农产品品牌传播的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/603
- 社区活动策划的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/lvd
- 小区电梯维护的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/dHF
- 公共健身器材的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/643=rfy
- 社区志愿服务的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/isx=133
- 智能手机助老的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ev8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E8%83%BD%E6%BA%90?/2S6=MMq
- 节能家电使用的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evi-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%BB%BC%E8%89%BA?/357
- 家庭园艺实践的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evi-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%BB%BC%E8%89%BA?/ijp
- 学校体育活动的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evi-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%BB%BC%E8%89%BA?/VRS
- 骑行路线规划的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evi-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%BB%BC%E8%89%BA?/725=bcm
- 绿色办公实践的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evi-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%BB%BC%E8%89%BA?/xta=905
- 青年职业探索的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9Evi-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E7%BB%BC%E8%89%BA?/8y0=CHK
- 信息无障碍体验的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/787
- 休闲运动入门的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/kfp
- 家庭健康管理的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/cQn
- 家庭网络使用的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/762=hxv
- 绿色办公实践的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/kwm=792
- 儿童友好空间的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85_%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F?/S6Z=fKK
- 学校体育活动的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%A5%BC%E5%B8%82?/041
- 小区停车协商中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%A5%BC%E5%B8%82?/sro
- 绿色办公实践的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%A5%BC%E5%B8%82?/Fln
- 文化讲座服务的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%A5%BC%E5%B8%82?/317=lis
- 家庭安全提示的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%A5%BC%E5%B8%82?/yyv=890
- 家庭阅读计划的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%A5%BC%E5%B8%82?/uoG=QHS
- 读书会组织的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%81%A5%E5%BA%B7?/186
- 社区邻里服务的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%81%A5%E5%BA%B7?/wei
- 城市慢跑路线的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%81%A5%E5%BA%B7?/cFJ
- 家庭网络使用的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%81%A5%E5%BA%B7?/957=ill
- 城市绿道建设的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%81%A5%E5%BA%B7?/glo=725
- 无障碍信息设计的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%81%A5%E5%BA%B7?/rZz=rCQ
- 光伏知识科普的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/336
- 社区活动报名的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/wtk
- 社区商业活力的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/zUw
- 信息无障碍体验的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/273=vde
- 家庭饮食安排的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/xkz=162
- 乡村生态观察的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/ejp=U6j
- 劳动教育实践的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/189
- 校园阅读活动从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/sve
- 数字创作工具的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/00r
- 家庭环保习惯的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/462=bbw
- 节能生活方式的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/qrk=776
- 课后服务体验的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95welcome_%E9%BC%8E%E7%9B%88%E8%B4%A2%E7%BB%8F?/kdD=3qt
- 社区艺术活动的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%85%A7%E7%9C%BC?/015
- 老年人文化生活的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%85%A7%E7%9C%BC?/fbv
- 儿童安全出行的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%85%A7%E7%9C%BC?/d4Y
- 城市社区治理的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%85%A7%E7%9C%BC?/444=qya
- 老年人出行服务的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%85%A7%E7%9C%BC?/uxz=116
- 家庭安全提示的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%85%A7%E7%9C%BC?/mc0=0sr
- 市民热线服务的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/390
- 社区活动策划的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/bcz
- 家庭节能设备的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/8nK
- 绿色生活实践中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/493=vgc
- 亲子阅读活动的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/psh=642
- 社区健康讲座的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/qS7=8oj
- 家庭消费规划的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E7%BD%91_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/568
- 终身学习资源的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E7%BD%91_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/muc
- 街区道路维护的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E7%BD%91_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/NFV
- 老年人出行服务的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E7%BD%91_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/221=qpv
- 社区垃圾分类的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E7%BD%91_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/jge=679
- 城市运动公园的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E7%BD%91_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/VhU=sBb
- 音乐欣赏活动的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%BF%AB%E8%AE%AF?/245
- 社区庭院绿化的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%BF%AB%E8%AE%AF?/yxp
- 乡村产业科普的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%BF%AB%E8%AE%AF?/i5v
- 公共服务数字化的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%BF%AB%E8%AE%AF?/894=uof
- 创业经验分享的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%BF%AB%E8%AE%AF?/lms=358
- 城市文化路线的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9Evi-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E5%BF%AB%E8%AE%AF?/Ufr=Teb
- 数字课堂应用的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Evi-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%A1%8C%E6%83%85?/264
- 乡村公共阅读的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Evi-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%A1%8C%E6%83%85?/qfp
- 城市文明出行的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Evi-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%A1%8C%E6%83%85?/PJ3
- 文明养宠科普的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Evi-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%A1%8C%E6%83%85?/892=yer
- 绿色快递包装的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Evi-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%A1%8C%E6%83%85?/sef=003
- 节日文化体验的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Evi-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E8%A1%8C%E6%83%85?/m6i=Kfh
- 青年就业服务的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-APP_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/823
- 社区学习活动的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-APP_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/bbh
- 居民健康教育的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-APP_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/4XW
- 青少年户外教育的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-APP_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/029=efb
- 城市应急科普从需求出发看服务设计 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-APP_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/vni=701
- 社区商业活力的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evi-APP_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/0ps=osU
- 城市文明实践的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/994
- 城市公共饮水从需求出发看服务设计 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/glw
- 公共设施维护的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/5Ft
- 家庭照护支持的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/702=fid
- 城市骑行环境的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/ymx=720
- 公共服务数字化的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/7Gs=nip
- 租房信息服务的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Evi-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%97%B6%E8%AE%AF?/075
- 社区信息发布从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Evi-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%97%B6%E8%AE%AF?/rfi
- 绿色出行服务的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Evi-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%97%B6%E8%AE%AF?/0PV
- 亲子科普活动的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Evi-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%97%B6%E8%AE%AF?/476=inm
- 乡村文化空间的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Evi-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%97%B6%E8%AE%AF?/fkz=214
- 公共服务指南从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Evi-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%97%B6%E8%AE%AF?/St8=r2E
- 数字公共文化中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/170
- 周末休闲规划的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/xpv
- 无障碍信息设计的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/Lqb
- 社区协商议事的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/341=njh
- 公共设施维护的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/cof=067
- 社区文化节活动的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%9Evi-%E7%99%BB%E5%BD%95_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/fUu=so3
- 绿色建筑理念的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Evi-%E6%B3%A8%E5%86%8C_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/960
- 传统节日科普的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Evi-%E6%B3%A8%E5%86%8C_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/tta
- 家庭健康科普的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Evi-%E6%B3%A8%E5%86%8C_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/d1B
- 绿色校园实践的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Evi-%E6%B3%A8%E5%86%8C_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/867=taj
- 社区科普课堂的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Evi-%E6%B3%A8%E5%86%8C_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/luc=207
- 非遗课堂体验的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9Evi-%E6%B3%A8%E5%86%8C_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/GNl=X8p
- 公共场馆服务的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/462
- 城市便民驿站的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/edq
- 城市公共厕所中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/7w9
- 地方美食文化的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/771=hhr
- 线上办事服务的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/ila=770
- 数字创作工具的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E8%88%86%E6%83%85?/Oi8=aj1
- 街头绿植养护的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/944
- 城市绿色交通中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/orl
- 智慧城市体验的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/E3Z
- 传统手工艺体验的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/583=nqg
- 城市博物馆服务从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/bhf=820
- 运动安全知识的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9Evi-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/nmb=SVF
- 家庭急救准备的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/430
- 社区知识分享的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/uvv
- 城市绿道建设的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/0Er
- 线上办事服务的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/036=mty
- 城市社区治理的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/rit=205
- 城市博物馆服务的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evi-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/aCw=VP8
- 城市共享单车的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Evi-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/718
- 创业经验分享的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Evi-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/kjb
- 校园安全教育的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Evi-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/sgt
- 社区托育服务的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Evi-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/021=zsv
- 农产品消费体验的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Evi-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/qpc=410
- 数字档案服务的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Evi-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/4rc=X5C
- 社区活动空间的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Evi-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/931
- 城市树木认养的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Evi-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/zho
- 城市公共空间的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Evi-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/p9t
- 数字学习资源的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Evi-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/636=tet
- 儿童友好空间的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Evi-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/rfw=423
- 家庭网络使用的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Evi-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/Zhc=gyY
- 文化遗产保护科普的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/053
- 乡村公共文化的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/jrt
- 低碳社区实践的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/6sF
- 社区便民服务的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/410=ehz
- 社区法律科普的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/kol=541
- 本地消费场景中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9Evi-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/9QZ=S7n
- 乡村生活观察的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/932
- 公共文化活动的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/xwq
- 环境监测科普从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/GB7
- 城市步行环境的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/397=npt
- 开放数据应用中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/pnb=841
- 老年学习活动的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/DCX=Bla
- 社区文化传播的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/767
- 青少年职业启蒙的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/syc
- 学校体育活动的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/o5H
- 家庭环保习惯的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/591=tem
- 城市夜间生活的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/npp=475
- 亲子阅读活动的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/7ah=q1L
- 户外活动组织的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/835
- 公共服务沟通的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/qui
- 数字艺术创作的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/MvU
- 节能家电使用的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/149=jdd
- 健康信息获取的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/nze=993
- 网络信息辨识的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/7rw=2px
- 社区科普课堂的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/686
- 数字创作工具的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/ard
- 儿童阅读角的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/hK8
- 乡村生态观察的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/499=vit
- 文化场馆预约的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/pzl=056
- 老年运动活动的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/qeq=xdU
- 科学健身方法的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/465
- 城市夜间照明的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9Evi%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/ytp

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
