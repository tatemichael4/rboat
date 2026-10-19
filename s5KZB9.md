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

- 社区科普课堂的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/rox=831
- 社区宣传栏更新的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/91K=J5E
- 志愿服务平台的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E8%B5%A2_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/816
- 数字生活课堂的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E8%B5%A2_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/ane
- 城市空气科普的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E8%B5%A2_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/L3T
- 社区便民服务的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E8%B5%A2_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/385=zik
- 社区托育服务的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E8%B5%A2_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/tmm=654
- 社区文化传播的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%8A%A9%E8%B5%A2_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/egf=0N6
- 儿童运动体验的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/421
- 本地历史资料的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/mid
- 社区便利生活的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/w4m
- 志愿服务平台的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/157=zah
- 节日文化体验的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/ybl=557
- 数字创意课程有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%9B%9E%E8%A1%80%E8%AE%A1%E5%88%92_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/PEZ=qQo
- 社区公共议事的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%85%A8%E5%A4%A9%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/385
- 乡村文化活动的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%85%A8%E5%A4%A9%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/bxu
- 亲子科普活动的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%85%A8%E5%A4%A9%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/hiv
- 公共空间导览的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%85%A8%E5%A4%A9%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/269=uhs
- 电动汽车充电的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%85%A8%E5%A4%A9%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/xlo=193
- 开源技术交流的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%85%A8%E5%A4%A9%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E7%BD%91%E6%98%93%E7%A4%BE%E8%AE%BA?/Ih2=UlT
- 城市公共座椅的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/002
- 绿色生活实践的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/xbv
- 休闲运动入门的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/n6j
- 家庭环保习惯的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/685=slh
- 社区文化传播的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/ild=345
- 健康信息获取的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E6%B3%95%E5%9B%BD%E8%B4%A2%E7%BB%8F?/P3e=bhz
- 城市应急广播的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/235
- 科学运动指导的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/aun
- 生成式工具使用的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/02r
- 数字支付体验的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/580=tsd
- 社区庭院绿化的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/dma=022
- 社区生活指南的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/cb8=s2P
- 青年就业服务的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/497
- 社区故事采集的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/dwy
- 医院导诊服务的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/6Vf
- 城市可持续生活的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/073=gdl
- 城市社区治理的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/flx=473
- 家庭防灾准备的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BA%AA%E5%AE%9E?/hXV=tnv
- 家庭用电安全的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/923
- 公共服务评价的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/kir
- 地方民俗记录的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/Q1B
- 老年人文化生活的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/508=ziq
- 小区停车协商的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/hkt=373
- 垃圾分类指导的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/E7j=qQi
- 家庭健康科普的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/525
- 青年职业探索的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/jmp
- 城市住房服务的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/FHs
- 乡村生活观察的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/851=mlh
- 公共服务指南的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/gnk=862
- 垃圾分类指导的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%B0%91%E7%94%9F?/5Tm=jG3
- 公园无障碍服务的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B4%AD%E4%B9%B0_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/696
- 家庭急救准备的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B4%AD%E4%B9%B0_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/vgk
- 社区互助网络的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B4%AD%E4%B9%B0_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/vT8
- 在线教育体验的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B4%AD%E4%B9%B0_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/813=hbr
- 机器人科普活动的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B4%AD%E4%B9%B0_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/hsd=345
- 线上阅读资源的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E8%B4%AD%E4%B9%B0_%E5%87%A4%E5%87%B0%E5%8E%BF%E5%9F%9F?/Gnk=BLu
- 周末休闲规划的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%87%86_%E6%8A%96%E9%9F%B3%E8%AF%BB%E6%8A%A5?/927
- 便民信息查询的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%87%86_%E6%8A%96%E9%9F%B3%E8%AF%BB%E6%8A%A5?/upk
- 新能源出行的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%87%86_%E6%8A%96%E9%9F%B3%E8%AF%BB%E6%8A%A5?/wwH
- 社区故事采集的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%87%86_%E6%8A%96%E9%9F%B3%E8%AF%BB%E6%8A%A5?/412=rjo
- 数字素养提升的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%87%86_%E6%8A%96%E9%9F%B3%E8%AF%BB%E6%8A%A5?/gos=172
- 社区公共卫生的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%93%AA%E4%B8%AA%E5%87%86_%E6%8A%96%E9%9F%B3%E8%AF%BB%E6%8A%A5?/AtJ=FAC
- 校园安全教育的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/046
- 城市文化路线的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/obr
- 家庭节能设备的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/S1y
- 城市公共座椅的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/297=aup
- 开放式学习空间的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/rum=558
- 全民健身活动的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E6%B2%BF%E6%B5%B7%E8%B4%A2%E7%BB%8F?/tr1=T5M
- 家庭园艺实践的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/509
- 家庭消费规划的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/esa
- 数字支付体验的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/BHz
- 科学运动指导的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/946=krv
- 劳动教育实践的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/iyv=579
- 音乐欣赏活动的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/Cwv=WiN
- 社区公共餐饮的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B8%89%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%99%A8%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E8%AE%BA?/583
- 绿色出行服务的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B8%89%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%99%A8%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E8%AE%BA?/nsl
- 社会体育指导从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B8%89%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%99%A8%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E8%AE%BA?/nDO
- 社区教育资源的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B8%89%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%99%A8%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E8%AE%BA?/995=yox
- 社区生活指南的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B8%89%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%99%A8%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E8%AE%BA?/ylo=626
- 学校食育活动的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B8%89%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E5%99%A8%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E7%A4%BE%E8%AE%BA?/zRD=a2V
- 城市步行友好的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E6%91%84%E5%BD%B1?/977
- 家庭节能实践的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E6%91%84%E5%BD%B1?/arp
- 便民维修服务的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E6%91%84%E5%BD%B1?/BHs
- 老年人日常照护的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E6%91%84%E5%BD%B1?/436=dtx
- 社区教育资源的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E6%91%84%E5%BD%B1?/dvi=960
- 家庭健康管理的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88_36%E6%B0%AA%E6%91%84%E5%BD%B1?/1q5=hDF
- 街区小店体验的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/094
- 志愿者培训交流的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/jvk
- 安全出行教育的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/Ysd
- 公共交通信息服务的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/524=cyo
- 垃圾分类指导的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/djd=485
- 家庭节能设备的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2_%E5%86%B0%E5%B2%9B%E8%B4%A2%E7%BB%8F?/M3x=b3Q
- 社区菜市场服务的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%A1%8C%E6%83%85?/729
- 科学教育活动的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%A1%8C%E6%83%85?/aec
- 社区垃圾分类的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%A1%8C%E6%83%85?/Sir
- 公共图书馆服务的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%A1%8C%E6%83%85?/376=kvr
- 环境教育课程有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%A1%8C%E6%83%85?/awy=466
- 青少年编程学习的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%A1%8C%E6%83%85?/ljr=3HQ
- 数字创作工具的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6APP%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/386
- 城市文明实践的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6APP%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/tcq
- 社区邻里服务的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6APP%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/NQ3
- 家庭网络使用的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6APP%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/768=uzk
- 老年数字阅读的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6APP%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/rng=875
- 校园安全教育的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6APP%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%94%B6%E8%97%8F?/BIC=cWg
- 志愿服务平台的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BAapp_%E5%A4%B4%E6%9D%A1%E6%A1%A3%E6%A1%88?/306
- 音乐欣赏活动的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BAapp_%E5%A4%B4%E6%9D%A1%E6%A1%A3%E6%A1%88?/wtz
- 健康饮水科普的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BAapp_%E5%A4%B4%E6%9D%A1%E6%A1%A3%E6%A1%88?/L4s
- 街区道路维护有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BAapp_%E5%A4%B4%E6%9D%A1%E6%A1%A3%E6%A1%88?/663=tnp
- 公共卫生设施的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BAapp_%E5%A4%B4%E6%9D%A1%E6%A1%A3%E6%A1%88?/yuw=713
- 智能家居应用的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BAapp_%E5%A4%B4%E6%9D%A1%E6%A1%A3%E6%A1%88?/4Wa=Feh
- 新能源知识普及的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E6%89%8B%E6%9C%BA%E7%89%88_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/790
- 公共空间休憩的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E6%89%8B%E6%9C%BA%E7%89%88_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/bqf
- 就业技能培训中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E6%89%8B%E6%9C%BA%E7%89%88_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/JLK
- 市民热线服务的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E6%89%8B%E6%9C%BA%E7%89%88_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/702=ceh
- 志愿服务平台的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E6%89%8B%E6%9C%BA%E7%89%88_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/bbr=207
- 安全出行教育的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E6%89%8B%E6%9C%BA%E7%89%88_%E8%91%A1%E8%90%84%E8%B4%A2%E7%BB%8F?/lfU=qAG
- 青年职业探索的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6cpzyrj%E6%89%8B%E6%9C%BA%E7%89%88_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/222
- 信息无障碍体验中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6cpzyrj%E6%89%8B%E6%9C%BA%E7%89%88_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/lqy
- 社区公共卫生中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6cpzyrj%E6%89%8B%E6%9C%BA%E7%89%88_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/0te
- 本地历史资料的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6cpzyrj%E6%89%8B%E6%9C%BA%E7%89%88_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/961=ujd
- 数字公共文化的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6cpzyrj%E6%89%8B%E6%9C%BA%E7%89%88_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/wzr=939
- 节能家电使用的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6cpzyrj%E6%89%8B%E6%9C%BA%E7%89%88_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/pCQ=aWG
- 全民健身活动的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E6%B3%A8%E8%B5%A2%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E6%89%8B%E8%AE%B0?/767
- 图书馆亲子空间的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E6%B3%A8%E8%B5%A2%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E6%89%8B%E8%AE%B0?/yul
- 家庭养老规划的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E6%B3%A8%E8%B5%A2%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E6%89%8B%E8%AE%B0?/Cw0
- 家庭饮食安排的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E6%B3%A8%E8%B5%A2%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E6%89%8B%E8%AE%B0?/481=ece
- 社区便民集市的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E6%B3%A8%E8%B5%A2%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E6%89%8B%E8%AE%B0?/bcv=522
- 无障碍出行中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E6%B3%A8%E8%B5%A2%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E6%89%8B%E8%AE%B0?/Lym=FKF
- 街道综合服务的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/462
- 乡村公共文化的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/vcq
- 科学教育活动的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/cOA
- 数字阅读服务的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/103=wge
- 乡村教育资源的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/mgk=924
- 社区宣传栏更新的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E6%92%AD%E6%8A%A5?/mgI=4is
- 图书馆数字服务的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%BB%E8%A6%81%E6%9C%89%E5%87%A0%E7%A7%8D%E7%B1%BB%E5%9E%8B_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/663
- 日常摄影记录从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%BB%E8%A6%81%E6%9C%89%E5%87%A0%E7%A7%8D%E7%B1%BB%E5%9E%8B_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/ozu
- 社区心理支持的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%BB%E8%A6%81%E6%9C%89%E5%87%A0%E7%A7%8D%E7%B1%BB%E5%9E%8B_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/Jf3
- 家庭急救准备的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%BB%E8%A6%81%E6%9C%89%E5%87%A0%E7%A7%8D%E7%B1%BB%E5%9E%8B_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/706=rtx
- 家庭环保行动的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%BB%E8%A6%81%E6%9C%89%E5%87%A0%E7%A7%8D%E7%B1%BB%E5%9E%8B_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/vxg=489
- 绿色消费选择的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%BB%E8%A6%81%E6%9C%89%E5%87%A0%E7%A7%8D%E7%B1%BB%E5%9E%8B_%E7%95%8C%E9%9D%A2%E8%B5%84%E8%AE%AF?/uVz=IID
- 生活垃圾回收的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88_%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/495
- 乡村文化活动的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88_%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/fpb
- 全民健身活动的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88_%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/OHU
- 城市步行友好的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88_%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/872=oqa
- 城市骑行环境的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88_%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/iue=741
- 乡村电商实践的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88_%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/qDF=3eE
- 全民健身活动的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91ios_%E6%90%9C%E7%8B%97%E6%9C%AD%E8%AE%B0?/642
- 农村环境治理的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91ios_%E6%90%9C%E7%8B%97%E6%9C%AD%E8%AE%B0?/bzh
- 城市生活记录的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91ios_%E6%90%9C%E7%8B%97%E6%9C%AD%E8%AE%B0?/JiB
- 健康饮水科普的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91ios_%E6%90%9C%E7%8B%97%E6%9C%AD%E8%AE%B0?/219=rih
- 社区老年食堂的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91ios_%E6%90%9C%E7%8B%97%E6%9C%AD%E8%AE%B0?/unx=012
- 数字素养提升的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91ios_%E6%90%9C%E7%8B%97%E6%9C%AD%E8%AE%B0?/eaJ=CTg
- 乡村公共文化的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/441
- 光伏知识科普的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/csk
- 街头绿植养护的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/P4Y
- 节能生活方式的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/474=xex
- 城乡公共服务的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/fpp=062
- 社区教育资源的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E4%B8%93%E9%A2%98?/iwo=nTI
- 本地消费场景的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%AC_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/113
- 绿色建筑理念的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%AC_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/cex
- 农产品品牌传播的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%AC_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/fo8
- 新能源知识普及的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%AC_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/751=fdf
- 儿童运动体验的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%AC_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/aiy=308
- 日常摄影记录的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%AC_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/DSI=faz
- 城乡交通衔接有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/280
- 城市公共空间的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/fjq
- 社区学习活动的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/PcY
- 城市公共座椅的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/050=wyi
- 社区共享书架的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/tvi=191
- 地方戏曲体验的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E5%85%AC%E5%BC%80%E8%AF%BE?/NmM=sbo
- 消防知识宣传的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%28y2y%C2%B7cc%29.LSd_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/407
- 社区文化节活动的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%28y2y%C2%B7cc%29.LSd_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/mjm
- 城市文明实践的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%28y2y%C2%B7cc%29.LSd_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/6qC
- 老年人日常照护的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%28y2y%C2%B7cc%29.LSd_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/731=wur
- 租房信息服务的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%28y2y%C2%B7cc%29.LSd_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/kqk=491
- 文化遗产保护科普的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%28y2y%C2%B7cc%29.LSd_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/Mc2=PL8
- 城市便民驿站的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88APP%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/463
- 家庭健康管理的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88APP%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/dhe
- 基层健康服务的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88APP%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/HSh
- 城市树木认养的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88APP%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/290=vfr
- 家庭节能实践的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88APP%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/vfv=695
- 农村环境治理的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E5%85%8D%E8%B4%B9%E7%89%88APP%E4%B8%8B%E8%BD%BD_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/UZR=D5a
- 个人时间管理的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E7%94%B5%E8%84%91%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/605
- 青少年户外教育的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E7%94%B5%E8%84%91%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/aob
- 儿童友好空间的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E7%94%B5%E8%84%91%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/K0z
- 家庭运动计划的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E7%94%B5%E8%84%91%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/781=mpb
- 城市公共自行车的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E7%94%B5%E8%84%91%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/okq=885
- 公共交通信息服务的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E7%94%B5%E8%84%91%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%90%9C%E7%8B%90%E4%BF%A1%E6%89%98?/SAP=4G2
- 药品使用科普的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E5%85%AC%E6%B5%8B%E7%89%88_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/685
- 老年人出行服务的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E5%85%AC%E6%B5%8B%E7%89%88_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/wmq
- 邻里互助活动的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E5%85%AC%E6%B5%8B%E7%89%88_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/MrD
- 家庭急救准备的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E5%85%AC%E6%B5%8B%E7%89%88_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/061=udd
- 社区共享书架的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E5%85%AC%E6%B5%8B%E7%89%88_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/auf=490
- 校园节能行动的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app%E5%85%AC%E6%B5%8B%E7%89%88_%E8%84%89%E8%84%89%E5%85%AC%E7%9B%8A?/MJU=8Jo
- 在线学习体验的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A4%B4%E6%9D%A1?/256
- 公共场所导视的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A4%B4%E6%9D%A1?/clx
- 智能家居应用的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A4%B4%E6%9D%A1?/D86
- 校园社团活动的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A4%B4%E6%9D%A1?/841=jzw
- 医院导诊服务的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A4%B4%E6%9D%A1?/ohk=423
- 社区垃圾回收的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E6%B0%B8%E4%B9%85%E5%85%8D%E8%B4%B9%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%A4%B4%E6%9D%A1?/Qdy=2DX
- 公益活动组织的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E6%96%B0%E7%89%88%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/445
- 城市基础设施的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E6%96%B0%E7%89%88%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/xol
- 城市步行环境的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E6%96%B0%E7%89%88%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/Q6B
- 健康饮食教育的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E6%96%B0%E7%89%88%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/468=aah
- 农村环境治理的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E6%96%B0%E7%89%88%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/blu=365
- 健康步道使用的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E6%96%B0%E7%89%88%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/0c2=KY9
- 社区科普课堂从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/548
- 社会体育指导的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/ocg
- 城市基础设施的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/xdk
- 社区庭院绿化中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/698=nbu
- 农产品消费体验的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/kgu=101
- 智慧停车服务的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6_%E8%8A%92%E6%9E%9C%E4%B8%93%E6%A0%8F?/RLi=IlY
- 乡村教育资源的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/468
- 城市展览体验的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/pxc
- 社区消防演练的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/si5
- 机器人科普活动的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/723=rix
- 绿色快递包装有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/bgr=260
- 数字阅读服务的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E4%B8%93%E9%A2%98?/UeP=SfV
- 亲子科普活动的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E3%80%8A%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E3%80%8B%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89?/216
- 老年数字阅读的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E3%80%8A%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E3%80%8B%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89?/dgd
- 社区菜市场服务有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E3%80%8A%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E3%80%8B%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89?/LYs
- 零废弃生活尝试的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E3%80%8A%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E3%80%8B%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89?/924=rdm
- 农产品品牌传播的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E3%80%8A%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E3%80%8B%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89?/pdh=437
- 公共场馆服务的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91_%E3%80%8A%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2%E8%BD%AF%E4%BB%B6%E3%80%8B%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89?/HdI=2Go
- 社区活动策划的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E7%89%88%E3%80%8A%E5%8A%A9%E8%B5%A2%E3%80%8B_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/828
- 街区道路维护的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E7%89%88%E3%80%8A%E5%8A%A9%E8%B5%A2%E3%80%8B_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/qxr
- 城市应急科普的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E7%89%88%E3%80%8A%E5%8A%A9%E8%B5%A2%E3%80%8B_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/kK8
- 文化场馆预约的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E7%89%88%E3%80%8A%E5%8A%A9%E8%B5%A2%E3%80%8B_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/195=zln
- 农产品品牌传播的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E7%89%88%E3%80%8A%E5%8A%A9%E8%B5%A2%E3%80%8B_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/nsy=679
- 城市宠物友好空间的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E6%89%8B%E6%9C%BA%E7%89%88%E3%80%8A%E5%8A%A9%E8%B5%A2%E3%80%8B_%E5%BE%97%E7%89%A9%E8%88%86%E6%83%85?/HKq=Lmj
- 小区停车协商的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_168%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/120
- 科学教育活动的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_168%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/jdt
- 公益活动组织的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_168%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/GHK
- 科普展览体验的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_168%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/145=wha
- 社区活动报名的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_168%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/vwz=836
- 数字素养提升的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_168%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A4%BE%E5%8C%BA?/M3t=ANB
- 社区交通安全的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%28%E5%9B%BD%E9%99%85%E7%89%88%29_360%E8%A7%A3%E5%AF%86?/843
- 街区小店体验的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%28%E5%9B%BD%E9%99%85%E7%89%88%29_360%E8%A7%A3%E5%AF%86?/oji
- 公共空间休憩从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%28%E5%9B%BD%E9%99%85%E7%89%88%29_360%E8%A7%A3%E5%AF%86?/F3S
- 儿童安全出行的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%28%E5%9B%BD%E9%99%85%E7%89%88%29_360%E8%A7%A3%E5%AF%86?/704=xmm
- 公共健身器材的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%28%E5%9B%BD%E9%99%85%E7%89%88%29_360%E8%A7%A3%E5%AF%86?/pnm=748
- 职业技能学习的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92%28%E5%9B%BD%E9%99%85%E7%89%88%29_360%E8%A7%A3%E5%AF%86?/nKe=yf2
- 家庭消费规划的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/709
- 基层医疗预约的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/roq
- 小区公共照明从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/rJM
- 数字生活课堂的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/512=rug
- 乡村休闲旅游的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/fja=290
- 城市环境志愿行动的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/JCc=hld
- 数字便民地图的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/900
- 城市绿色交通的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%8A%A9%E8%B5%A2%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A6%81%E9%97%BB?/cea

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
