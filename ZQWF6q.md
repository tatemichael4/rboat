# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:30**

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

- 绿色消费选择的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_pc%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/dim=813
- 绿色快递包装的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_pc%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E9%A1%BA%E4%B8%B0%E5%9B%9E%E6%9C%9B?/hCB=QHl
- 家庭陪伴活动的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%AF%AE%E7%90%83%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/007
- 社区健康讲座中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%AF%AE%E7%90%83%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/cuh
- 社区修缮行动的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%AF%AE%E7%90%83%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/WjJ
- 环境教育课程的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%AF%AE%E7%90%83%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/711=xys
- 科学睡眠习惯的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%AF%AE%E7%90%83%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/bsb=144
- 儿童友好空间的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%AF%AE%E7%90%83%E8%B5%8C%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A23%E7%A7%8D%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/reU=hqc
- 家庭环保行动的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A850%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/037
- 社区垃圾分类的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A850%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/yng
- 食品安全科普的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A850%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/pd0
- 社区公共卫生从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A850%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/326=cqj
- 社区环保活动的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A850%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/ujl=962
- 文明养宠科普的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A850%E6%9C%9F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/40i=2UA
- 城市步行友好的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/505
- 生成式工具使用的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/fus
- 公共场馆服务的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/v8c
- 城市环境志愿行动的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/014=phs
- 社区垃圾分类的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/nbu=854
- 跨代沟通活动的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%B8%AD%E5%95%86%E8%B4%A2%E7%BB%8F?/MJ1=KzH
- 公园无障碍服务的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E8%B6%B3%E5%BD%A92.0%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/405
- 家庭阅读计划的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E8%B6%B3%E5%BD%A92.0%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/ajw
- 社区便民集市的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E8%B6%B3%E5%BD%A92.0%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/E6v
- 生活垃圾减量的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E8%B6%B3%E5%BD%A92.0%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/641=jqz
- 线上阅读资源的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E8%B6%B3%E5%BD%A92.0%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/qyd=489
- 社区学习活动的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E8%B6%B3%E5%BD%A92.0%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E8%B1%86%E7%93%A3%E6%B1%87%E5%B8%82?/0Cl=P8P
- 儿童户外活动的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/785
- 乡村文化空间有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/sgy
- 安全出行教育的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/NbN
- 科学观察活动的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/143=qrz
- 老年人日常照护的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/rzq=948
- 城市步行友好的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E6%96%87%E6%91%98?/sZW=Uri
- 城市基础设施的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%AD%E8%89%BA?/586
- 乡村文化活动的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%AD%E8%89%BA?/xpj
- 公共空间导览的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%AD%E8%89%BA?/tsT
- 全民健身活动有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%AD%E8%89%BA?/262=qxj
- 公共卫生设施有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%AD%E8%89%BA?/sgp=139
- 社区家校合作的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%AD%E8%89%BA?/liT=Pjo
- 社区应急准备的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_5000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/209
- 乡村阅读活动的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_5000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/rcn
- 社区阅读服务有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_5000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/q0p
- 城市应急科普的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_5000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/084=htv
- 城市博物馆活动的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_5000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/nra=486
- 便民服务窗口的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_5000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/ax6=CJN
- 老年学习活动从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E4%B8%80%E5%8D%83%E5%85%83%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/813
- 开放式学习空间的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E4%B8%80%E5%8D%83%E5%85%83%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/khx
- 老年运动活动的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E4%B8%80%E5%8D%83%E5%85%83%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/oq9
- 绿色校园实践的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E4%B8%80%E5%8D%83%E5%85%83%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/814=ybo
- 城市水环境观察的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E4%B8%80%E5%8D%83%E5%85%83%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/yoo=658
- 城市应急广播的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E4%B8%80%E5%8D%83%E5%85%83%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E5%AE%B6%E7%94%B5?/VlZ=FEN
- 公园休闲体验的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E6%89%93%E5%85%BC%E8%81%8C%E6%97%A5%E7%BB%93%E4%BD%A3%E9%87%91_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/933
- 药品使用科普的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E6%89%93%E5%85%BC%E8%81%8C%E6%97%A5%E7%BB%93%E4%BD%A3%E9%87%91_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/lav
- 家庭养老规划的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E6%89%93%E5%85%BC%E8%81%8C%E6%97%A5%E7%BB%93%E4%BD%A3%E9%87%91_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/s2c
- 文明养宠科普的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E6%89%93%E5%85%BC%E8%81%8C%E6%97%A5%E7%BB%93%E4%BD%A3%E9%87%91_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/033=tlo
- 街区小店体验的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E6%89%93%E5%85%BC%E8%81%8C%E6%97%A5%E7%BB%93%E4%BD%A3%E9%87%91_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/cdf=218
- 乡村教育资源的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E6%89%93%E5%85%BC%E8%81%8C%E6%97%A5%E7%BB%93%E4%BD%A3%E9%87%91_%E6%96%B0%E6%B5%AA%E6%B0%91%E7%94%9F?/kcM=Co0
- 青少年科普实践的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E5%8E%8B%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%9A_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/559
- 数字档案服务的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E5%8E%8B%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%9A_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/cdg
- 城市夜间照明的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E5%8E%8B%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%9A_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/qsS
- 城市夜间照明的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E5%8E%8B%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%9A_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/922=aur
- 口袋公园建设从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E5%8E%8B%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%9A_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/iwi=286
- 绿色校园实践的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E5%8E%8B%E5%A4%A7%E5%B0%8F%E7%A8%B3%E8%B5%9A_%E5%8C%BA%E5%9F%9F%E8%B4%A2%E7%BB%8F?/9sM=hEv
- 乡村生态观察的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_100%E5%85%83%E5%80%8D%E6%8A%9516%E6%9C%9F%E6%96%B9%E6%A1%88_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/252
- 社区便民服务的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_100%E5%85%83%E5%80%8D%E6%8A%9516%E6%9C%9F%E6%96%B9%E6%A1%88_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/ckf
- 公共空间照明的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_100%E5%85%83%E5%80%8D%E6%8A%9516%E6%9C%9F%E6%96%B9%E6%A1%88_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/xsz
- 急救知识普及的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_100%E5%85%83%E5%80%8D%E6%8A%9516%E6%9C%9F%E6%96%B9%E6%A1%88_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/548=oum
- 小微企业服务的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_100%E5%85%83%E5%80%8D%E6%8A%9516%E6%9C%9F%E6%96%B9%E6%A1%88_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/ati=746
- 社区运动空间的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_100%E5%85%83%E5%80%8D%E6%8A%9516%E6%9C%9F%E6%96%B9%E6%A1%88_%E6%9D%83%E5%A8%81%E8%B4%A2%E7%BB%8F?/vGI=Q2H
- 城市公共座椅的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%956%E7%A7%8D%E7%A8%B3%E7%9B%88%E6%96%B9%E6%B3%95_36%E6%B0%AA?/070
- 城市应急广播的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%956%E7%A7%8D%E7%A8%B3%E7%9B%88%E6%96%B9%E6%B3%95_36%E6%B0%AA?/nfx
- 家庭运动计划的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%956%E7%A7%8D%E7%A8%B3%E7%9B%88%E6%96%B9%E6%B3%95_36%E6%B0%AA?/xRS
- 基层服务创新的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%956%E7%A7%8D%E7%A8%B3%E7%9B%88%E6%96%B9%E6%B3%95_36%E6%B0%AA?/824=yud
- 社区消防演练的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%956%E7%A7%8D%E7%A8%B3%E7%9B%88%E6%96%B9%E6%B3%95_36%E6%B0%AA?/xtg=098
- 乡村文化空间的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E6%AD%A3%E7%A1%AE%E5%80%8D%E6%8A%956%E7%A7%8D%E7%A8%B3%E7%9B%88%E6%96%B9%E6%B3%95_36%E6%B0%AA?/FOW=FR7
- 城市体育设施的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_500%E5%85%83-%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/119
- 公共服务数字化的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_500%E5%85%83-%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/vbk
- 数字政务体验的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_500%E5%85%83-%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/T4j
- 节日文化体验的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_500%E5%85%83-%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/169=cco
- 校园社团活动的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_500%E5%85%83-%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/wfh=850
- 社区便利生活的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_500%E5%85%83-%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B5%84%E8%AE%AF?/ieZ=ykS
- 青少年心理健康的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E7%9A%84%E6%9C%80%E5%A5%BD%E6%96%B9%E6%A1%88_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/702
- 公园亲子设施的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E7%9A%84%E6%9C%80%E5%A5%BD%E6%96%B9%E6%A1%88_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/efj
- 小区电梯维护的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E7%9A%84%E6%9C%80%E5%A5%BD%E6%96%B9%E6%A1%88_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/YrP
- 数字支付体验的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E7%9A%84%E6%9C%80%E5%A5%BD%E6%96%B9%E6%A1%88_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/418=jci
- 社区防暑服务的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E7%9A%84%E6%9C%80%E5%A5%BD%E6%96%B9%E6%A1%88_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/key=077
- 社区活动报名的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E7%9A%84%E6%9C%80%E5%A5%BD%E6%96%B9%E6%A1%88_%E5%A4%B4%E6%9D%A1%E7%A7%91%E6%8A%80?/LUm=KSO
- 课后服务体验的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_1000%E6%9C%AC%E9%87%91%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC%E5%88%92%E5%80%8D%E6%8A%95_%E7%BD%91%E6%98%93%E6%9B%B2%E8%89%BA?/725
- 社区活动空间从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_1000%E6%9C%AC%E9%87%91%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC%E5%88%92%E5%80%8D%E6%8A%95_%E7%BD%91%E6%98%93%E6%9B%B2%E8%89%BA?/svr
- 绿色生活实践的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_1000%E6%9C%AC%E9%87%91%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC%E5%88%92%E5%80%8D%E6%8A%95_%E7%BD%91%E6%98%93%E6%9B%B2%E8%89%BA?/LCk
- 儿童安全出行中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_1000%E6%9C%AC%E9%87%91%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC%E5%88%92%E5%80%8D%E6%8A%95_%E7%BD%91%E6%98%93%E6%9B%B2%E8%89%BA?/619=guy
- 小区停车协商的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_1000%E6%9C%AC%E9%87%91%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC%E5%88%92%E5%80%8D%E6%8A%95_%E7%BD%91%E6%98%93%E6%9B%B2%E8%89%BA?/rmr=128
- 网络信息辨识的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_1000%E6%9C%AC%E9%87%91%E8%AE%A1%E5%88%92%E8%A1%A8%E6%A0%BC%E5%88%92%E5%80%8D%E6%8A%95_%E7%BD%91%E6%98%93%E6%9B%B2%E8%89%BA?/ef0=mB4
- 创业经验分享的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%9C%80%E7%A8%B3%E5%A6%A5%E7%9A%84%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E5%8A%A8%E6%BC%AB?/887
- 地方民俗记录的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%9C%80%E7%A8%B3%E5%A6%A5%E7%9A%84%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E5%8A%A8%E6%BC%AB?/uwn
- 家庭用电安全的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%9C%80%E7%A8%B3%E5%A6%A5%E7%9A%84%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E5%8A%A8%E6%BC%AB?/KPx
- 本地旅行体验的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%9C%80%E7%A8%B3%E5%A6%A5%E7%9A%84%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E5%8A%A8%E6%BC%AB?/409=cka
- 社区邻里服务的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%9C%80%E7%A8%B3%E5%A6%A5%E7%9A%84%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E5%8A%A8%E6%BC%AB?/qpb=468
- 城市体育设施的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8F%8D%E5%80%8D%E6%8A%95%E6%9C%80%E7%A8%B3%E5%A6%A5%E7%9A%84%E6%96%B9%E6%B3%95_%E5%A4%AE%E8%A7%86%E5%8A%A8%E6%BC%AB?/PrM=yIw
- 创业经验分享的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_1-3-5-8-15-24%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE20%E6%AC%A1_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/217
- 社区体育组织的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_1-3-5-8-15-24%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE20%E6%AC%A1_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/jli
- 城市慢跑路线的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_1-3-5-8-15-24%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE20%E6%AC%A1_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/0Rm
- 食品安全科普的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_1-3-5-8-15-24%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE20%E6%AC%A1_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/360=lcv
- 网络信息辨识的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_1-3-5-8-15-24%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE20%E6%AC%A1_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/uza=578
- 乡村公共服务的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_1-3-5-8-15-24%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E5%9B%BE20%E6%AC%A1_%E9%9B%85%E8%99%8E%E6%A5%BC%E5%B8%82?/1oA=6iC
- 科学运动指导的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E8%B4%9F%E5%80%BA%E7%B4%AF%E7%B4%AF%E7%9A%84%E4%B8%8A%E5%B2%B8%E6%96%B9%E6%B3%95_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/974
- 图书馆数字服务的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E8%B4%9F%E5%80%BA%E7%B4%AF%E7%B4%AF%E7%9A%84%E4%B8%8A%E5%B2%B8%E6%96%B9%E6%B3%95_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/eyg
- 乡村休闲旅游的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E8%B4%9F%E5%80%BA%E7%B4%AF%E7%B4%AF%E7%9A%84%E4%B8%8A%E5%B2%B8%E6%96%B9%E6%B3%95_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/zVJ
- 乡村阅读活动的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E8%B4%9F%E5%80%BA%E7%B4%AF%E7%B4%AF%E7%9A%84%E4%B8%8A%E5%B2%B8%E6%96%B9%E6%B3%95_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/138=avo
- 城市共享单车的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E8%B4%9F%E5%80%BA%E7%B4%AF%E7%B4%AF%E7%9A%84%E4%B8%8A%E5%B2%B8%E6%96%B9%E6%B3%95_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/wrt=049
- 城市共享单车的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E8%B4%9F%E5%80%BA%E7%B4%AF%E7%B4%AF%E7%9A%84%E4%B8%8A%E5%B2%B8%E6%96%B9%E6%B3%95_%E5%AE%8F%E7%9B%88%E8%B4%A2%E7%BB%8F?/hkf=h23
- 城市噪声观察的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6_360%E4%BA%B2%E5%AD%90?/668
- 在线教育体验的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6_360%E4%BA%B2%E5%AD%90?/ggj
- 绿色出行服务的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6_360%E4%BA%B2%E5%AD%90?/Hdw
- 医院导诊服务的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6_360%E4%BA%B2%E5%AD%90?/927=tej
- 城市建设科普的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6_360%E4%BA%B2%E5%AD%90?/imz=467
- 乡村休闲旅游的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_5000%E6%9C%AC%E9%87%91%E6%AF%8F%E5%A4%A9%E8%B5%A2100%E5%B0%B1%E6%94%B6_360%E4%BA%B2%E5%AD%90?/aWH=mpk
- 家庭志愿活动有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%BD%91%E8%B5%8C%E9%95%BF%E6%9C%9F%E7%9B%88%E5%88%A9%E7%9A%84%E6%96%B9%E6%B3%95_%E5%87%A4%E5%87%B0%E8%A1%8C%E6%83%85?/603
- 线上阅读资源的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%BD%91%E8%B5%8C%E9%95%BF%E6%9C%9F%E7%9B%88%E5%88%A9%E7%9A%84%E6%96%B9%E6%B3%95_%E5%87%A4%E5%87%B0%E8%A1%8C%E6%83%85?/xbk
- 社区艺术活动的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%BD%91%E8%B5%8C%E9%95%BF%E6%9C%9F%E7%9B%88%E5%88%A9%E7%9A%84%E6%96%B9%E6%B3%95_%E5%87%A4%E5%87%B0%E8%A1%8C%E6%83%85?/rSr
- 家庭收纳实践的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%BD%91%E8%B5%8C%E9%95%BF%E6%9C%9F%E7%9B%88%E5%88%A9%E7%9A%84%E6%96%B9%E6%B3%95_%E5%87%A4%E5%87%B0%E8%A1%8C%E6%83%85?/418=xbi
- 青年就业服务的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%BD%91%E8%B5%8C%E9%95%BF%E6%9C%9F%E7%9B%88%E5%88%A9%E7%9A%84%E6%96%B9%E6%B3%95_%E5%87%A4%E5%87%B0%E8%A1%8C%E6%83%85?/dfy=965
- 在线学习体验的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%BD%91%E8%B5%8C%E9%95%BF%E6%9C%9F%E7%9B%88%E5%88%A9%E7%9A%84%E6%96%B9%E6%B3%95_%E5%87%A4%E5%87%B0%E8%A1%8C%E6%83%85?/Iqg=dT6
- 社区便民集市从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E5%8D%81%E5%A4%A7%E5%BF%85%E8%83%9C%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/956
- 公共卫生宣传的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E5%8D%81%E5%A4%A7%E5%BF%85%E8%83%9C%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/xck
- 安全出行教育的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E5%8D%81%E5%A4%A7%E5%BF%85%E8%83%9C%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/5D1
- 课后服务体验的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E5%8D%81%E5%A4%A7%E5%BF%85%E8%83%9C%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/898=qnz
- 老年学习活动的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E5%8D%81%E5%A4%A7%E5%BF%85%E8%83%9C%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/rpa=591
- 城市慢行系统的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%87%AF%E5%88%A9%E5%85%AC%E5%BC%8F%E5%8D%81%E5%A4%A7%E5%BF%85%E8%83%9C%E6%8A%80%E5%B7%A7_%E7%95%8C%E9%9D%A2%E8%AE%BF%E8%B0%88?/RrW=oz9
- 节气饮食文化的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/037
- 社区托育服务的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/mqa
- 家庭科学教育的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/4Ja
- 城市宠物友好空间的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/741=ahs
- 邻里互助活动的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/une=453
- 社区慢性病防控的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E5%A6%82%E4%BD%95%E7%9C%8B_%E5%87%A4%E5%87%B0%E5%BF%AB%E8%AE%AF?/v5G=fMm
- 传统手工艺体验的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_600%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E7%9A%84%E6%B3%A8%E7%A0%81%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/078
- 社区文化节活动的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_600%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E7%9A%84%E6%B3%A8%E7%A0%81%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/jvt
- 城市适老服务的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_600%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E7%9A%84%E6%B3%A8%E7%A0%81%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/nTM
- 机器学习入门的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_600%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E7%9A%84%E6%B3%A8%E7%A0%81%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/577=qst
- 城市树木认养的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_600%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E7%9A%84%E6%B3%A8%E7%A0%81%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/hmy=325
- 社区环保活动中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_600%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E7%9A%84%E6%B3%A8%E7%A0%81%E6%8A%80%E5%B7%A7_%E8%99%8E%E6%89%91%E8%88%86%E6%83%85?/5pn=q4X
- 社区绿色空间的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A6%82%E4%BD%95%E5%80%8D%E6%8A%95%E6%89%8D%E6%98%AF%E6%9C%80%E7%A8%B3_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/965
- 居家防滑改造的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A6%82%E4%BD%95%E5%80%8D%E6%8A%95%E6%89%8D%E6%98%AF%E6%9C%80%E7%A8%B3_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/khs
- 居民健康教育的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A6%82%E4%BD%95%E5%80%8D%E6%8A%95%E6%89%8D%E6%98%AF%E6%9C%80%E7%A8%B3_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/RLC
- 家庭运动计划的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A6%82%E4%BD%95%E5%80%8D%E6%8A%95%E6%89%8D%E6%98%AF%E6%9C%80%E7%A8%B3_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/893=lfe
- 社区交通安全的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A6%82%E4%BD%95%E5%80%8D%E6%8A%95%E6%89%8D%E6%98%AF%E6%9C%80%E7%A8%B3_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/ifj=325
- 科学睡眠习惯中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A6%82%E4%BD%95%E5%80%8D%E6%8A%95%E6%89%8D%E6%98%AF%E6%9C%80%E7%A8%B3_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/MvQ=1sl
- 公共设施维护的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_137%E5%80%8D%E6%8A%959%E5%8F%A3%E5%85%AC%E5%BC%8F_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/346
- 生活技能分享的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_137%E5%80%8D%E6%8A%959%E5%8F%A3%E5%85%AC%E5%BC%8F_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/wcv
- 读书会组织的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_137%E5%80%8D%E6%8A%959%E5%8F%A3%E5%85%AC%E5%BC%8F_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/9WA
- 校园社团活动的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_137%E5%80%8D%E6%8A%959%E5%8F%A3%E5%85%AC%E5%BC%8F_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/626=kon
- 城市博物馆服务的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_137%E5%80%8D%E6%8A%959%E5%8F%A3%E5%85%AC%E5%BC%8F_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/trg=913
- 信息无障碍体验的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_137%E5%80%8D%E6%8A%959%E5%8F%A3%E5%85%AC%E5%BC%8F_%E8%B7%A8%E5%A2%83%E8%B4%A2%E7%BB%8F?/Gen=3rU
- 城市公共艺术中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F10%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/531
- 城市休闲步道的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F10%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/edz
- 本地旅行体验的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F10%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/TGN
- 学校食育活动的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F10%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/828=cmu
- 智能家居应用的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F10%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/usr=960
- 全民阅读推广的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F10%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/gXF=bgt
- 基层服务创新的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E4%B8%AA%E6%88%90%E5%8A%9F%E8%B5%8C%E5%BE%92%E7%9A%84%E6%B3%A8%E7%A0%81%E6%B3%95_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/208
- 城市适老服务中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E4%B8%AA%E6%88%90%E5%8A%9F%E8%B5%8C%E5%BE%92%E7%9A%84%E6%B3%A8%E7%A0%81%E6%B3%95_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/sdz
- 城市便民驿站中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E4%B8%AA%E6%88%90%E5%8A%9F%E8%B5%8C%E5%BE%92%E7%9A%84%E6%B3%A8%E7%A0%81%E6%B3%95_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/jYb
- 新能源出行的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E4%B8%AA%E6%88%90%E5%8A%9F%E8%B5%8C%E5%BE%92%E7%9A%84%E6%B3%A8%E7%A0%81%E6%B3%95_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/377=oza
- 社区艺术活动的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E4%B8%AA%E6%88%90%E5%8A%9F%E8%B5%8C%E5%BE%92%E7%9A%84%E6%B3%A8%E7%A0%81%E6%B3%95_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/xdx=180
- 食品安全科普的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E4%B8%AA%E6%88%90%E5%8A%9F%E8%B5%8C%E5%BE%92%E7%9A%84%E6%B3%A8%E7%A0%81%E6%B3%95_36%E6%B0%AA%E5%AE%8F%E8%A7%82?/qZk=95D
- 绿色出行服务的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_1%E6%AF%940.95%E5%88%B7%E6%B5%81%E6%B0%B4%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/627
- 青少年科普实践的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_1%E6%AF%940.95%E5%88%B7%E6%B5%81%E6%B0%B4%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/vpx
- 健康饮食教育的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_1%E6%AF%940.95%E5%88%B7%E6%B5%81%E6%B0%B4%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/84m
- 城市空气科普的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_1%E6%AF%940.95%E5%88%B7%E6%B5%81%E6%B0%B4%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/391=jzf
- 城市博物馆服务的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_1%E6%AF%940.95%E5%88%B7%E6%B5%81%E6%B0%B4%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/vyj=021
- 学校食育活动中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_1%E6%AF%940.95%E5%88%B7%E6%B5%81%E6%B0%B4%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/izT=RHt
- 社区读书角建设的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E7%AB%9E%E5%BD%A92%E4%B8%B2%E4%B8%80%E8%B5%9A%E4%BA%86%E5%87%A0%E5%8D%81%E4%B8%87_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/222
- 绿色消费选择的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E7%AB%9E%E5%BD%A92%E4%B8%B2%E4%B8%80%E8%B5%9A%E4%BA%86%E5%87%A0%E5%8D%81%E4%B8%87_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/glo
- 便民维修服务的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E7%AB%9E%E5%BD%A92%E4%B8%B2%E4%B8%80%E8%B5%9A%E4%BA%86%E5%87%A0%E5%8D%81%E4%B8%87_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/Nkt
- 数字课堂应用的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E7%AB%9E%E5%BD%A92%E4%B8%B2%E4%B8%80%E8%B5%9A%E4%BA%86%E5%87%A0%E5%8D%81%E4%B8%87_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/051=uhm
- 家庭园艺实践的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E7%AB%9E%E5%BD%A92%E4%B8%B2%E4%B8%80%E8%B5%9A%E4%BA%86%E5%87%A0%E5%8D%81%E4%B8%87_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/lus=348
- 职业技能学习中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E7%AB%9E%E5%BD%A92%E4%B8%B2%E4%B8%80%E8%B5%9A%E4%BA%86%E5%87%A0%E5%8D%81%E4%B8%87_%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F?/aO0=HNj
- 公共服务评价的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E6%AF%8F%E5%A4%A9%E8%B5%A2300%E8%B5%A2%E4%BA%86%E4%B8%80%E5%B9%B4_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/306
- 食品配送体验从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E6%AF%8F%E5%A4%A9%E8%B5%A2300%E8%B5%A2%E4%BA%86%E4%B8%80%E5%B9%B4_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/pxm
- 环境教育课程的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E6%AF%8F%E5%A4%A9%E8%B5%A2300%E8%B5%A2%E4%BA%86%E4%B8%80%E5%B9%B4_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/A46
- 软件开发学习的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E6%AF%8F%E5%A4%A9%E8%B5%A2300%E8%B5%A2%E4%BA%86%E4%B8%80%E5%B9%B4_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/208=paf
- 基层健康服务的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E6%AF%8F%E5%A4%A9%E8%B5%A2300%E8%B5%A2%E4%BA%86%E4%B8%80%E5%B9%B4_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/arc=427
- 城市夜间生活的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E6%AF%8F%E5%A4%A9%E8%B5%A2300%E8%B5%A2%E4%BA%86%E4%B8%80%E5%B9%B4_%E4%BA%AC%E4%B8%9C%E6%91%84%E5%BD%B1?/miy=72h
- 社区儿童活动的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E9%A3%9E%E8%89%876%E7%A0%81345678%E4%B8%8D%E6%AD%BB%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%91%84%E5%BD%B1?/441
- 社区志愿服务的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E9%A3%9E%E8%89%876%E7%A0%81345678%E4%B8%8D%E6%AD%BB%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%91%84%E5%BD%B1?/otr
- 家庭节能实践的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E9%A3%9E%E8%89%876%E7%A0%81345678%E4%B8%8D%E6%AD%BB%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%91%84%E5%BD%B1?/EaK
- 课后服务体验的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E9%A3%9E%E8%89%876%E7%A0%81345678%E4%B8%8D%E6%AD%BB%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%91%84%E5%BD%B1?/610=hoo
- 城市绿色交通的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E9%A3%9E%E8%89%876%E7%A0%81345678%E4%B8%8D%E6%AD%BB%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%91%84%E5%BD%B1?/sbi=847
- 城市应急广播的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E9%A3%9E%E8%89%876%E7%A0%81345678%E4%B8%8D%E6%AD%BB%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E6%91%84%E5%BD%B1?/yv7=Hb4
- 校园社团活动的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_50%E6%A6%82%E7%8E%87-%E8%B5%8C%E5%A4%A7%E5%B0%8F%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/310
- 城市公共座椅中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_50%E6%A6%82%E7%8E%87-%E8%B5%8C%E5%A4%A7%E5%B0%8F%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/tdx
- 城市基础设施的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_50%E6%A6%82%E7%8E%87-%E8%B5%8C%E5%A4%A7%E5%B0%8F%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/Nss
- 线上办事服务的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_50%E6%A6%82%E7%8E%87-%E8%B5%8C%E5%A4%A7%E5%B0%8F%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/152=brj
- 社区协商议事的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_50%E6%A6%82%E7%8E%87-%E8%B5%8C%E5%A4%A7%E5%B0%8F%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/coh=845
- 公共交通信息服务的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_50%E6%A6%82%E7%8E%87-%E8%B5%8C%E5%A4%A7%E5%B0%8F%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/W8x=Yzf
- 线上阅读资源的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%951123%E6%8A%80%E5%B7%A7_360%E7%BE%8E%E5%A6%86?/974
- 数字艺术创作的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%951123%E6%8A%80%E5%B7%A7_360%E7%BE%8E%E5%A6%86?/vhn
- 数字资源检索的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%951123%E6%8A%80%E5%B7%A7_360%E7%BE%8E%E5%A6%86?/8gi
- 城市骑行环境的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%951123%E6%8A%80%E5%B7%A7_360%E7%BE%8E%E5%A6%86?/693=tbp
- 城市公共标识的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%951123%E6%8A%80%E5%B7%A7_360%E7%BE%8E%E5%A6%86?/mqt=263
- 社区慢性病防控的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%951123%E6%8A%80%E5%B7%A7_360%E7%BE%8E%E5%A6%86?/w7l=sGJ
- 科普展览体验的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/299
- 数字支付体验的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/yes
- 家庭节能设备中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/eYP
- 家庭阅读计划的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/456=sjb
- 周末休闲规划的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/nis=262
- 气象科普传播的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E6%9C%80%E5%8E%89%E5%AE%B3%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/ZA5=fUp
- 农村环境治理的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E9%BB%91%E5%BD%A9%E6%8C%A3%E9%92%B1%E7%9A%84%E4%B8%89%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/434
- 城市运动公园的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E9%BB%91%E5%BD%A9%E6%8C%A3%E9%92%B1%E7%9A%84%E4%B8%89%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/pcf
- 乡村阅读活动的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E9%BB%91%E5%BD%A9%E6%8C%A3%E9%92%B1%E7%9A%84%E4%B8%89%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/GCX
- 城市应急广播的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E9%BB%91%E5%BD%A9%E6%8C%A3%E9%92%B1%E7%9A%84%E4%B8%89%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/731=qdf
- 便民维修服务有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E9%BB%91%E5%BD%A9%E6%8C%A3%E9%92%B1%E7%9A%84%E4%B8%89%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/gft=807
- 家庭健康管理的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E9%BB%91%E5%BD%A9%E6%8C%A3%E9%92%B1%E7%9A%84%E4%B8%89%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/cR1=jK8
- 劳动教育实践的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E9%97%A8%E6%89%93%E5%85%AC%E5%BC%8F%E5%8E%BB%E7%A8%B3%E6%8C%A3%E7%9A%84%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%9F%E8%B4%A7?/491
- 公共场所导视的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E9%97%A8%E6%89%93%E5%85%AC%E5%BC%8F%E5%8E%BB%E7%A8%B3%E6%8C%A3%E7%9A%84%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%9F%E8%B4%A7?/jai
- 校园阅读活动的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E9%97%A8%E6%89%93%E5%85%AC%E5%BC%8F%E5%8E%BB%E7%A8%B3%E6%8C%A3%E7%9A%84%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%9F%E8%B4%A7?/6XN
- 智慧城市体验的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E9%97%A8%E6%89%93%E5%85%AC%E5%BC%8F%E5%8E%BB%E7%A8%B3%E6%8C%A3%E7%9A%84%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%9F%E8%B4%A7?/743=plu
- 数字阅读服务的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E9%97%A8%E6%89%93%E5%85%AC%E5%BC%8F%E5%8E%BB%E7%A8%B3%E6%8C%A3%E7%9A%84%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%9F%E8%B4%A7?/nwz=959
- 地方美食文化的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E9%97%A8%E6%89%93%E5%85%AC%E5%BC%8F%E5%8E%BB%E7%A8%B3%E6%8C%A3%E7%9A%84%E5%90%97_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9C%9F%E8%B4%A7?/Hzx=dy2
- 青少年科技社团的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/745
- 便民维修服务的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/cex
- 社区读书角建设的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/ayL
- 社区老年食堂的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/289=idj
- 青少年心理健康的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/lno=186
- 节气饮食文化的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E7%AE%97%E6%B3%95%E5%85%AC%E5%BC%8F%E5%9B%BE_%E7%99%BE%E5%BA%A6%E5%9F%8E%E4%BA%8B?/PJ8=4Kn
- 乡村公共服务的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8%E7%A0%81%E8%BF%9B%E4%B8%80%E9%80%80%E4%BA%8C%E5%80%8D%E6%8A%95%E6%B3%95_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/687
- 城市可持续生活的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8%E7%A0%81%E8%BF%9B%E4%B8%80%E9%80%80%E4%BA%8C%E5%80%8D%E6%8A%95%E6%B3%95_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/rcg
- 老年友好服务的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8%E7%A0%81%E8%BF%9B%E4%B8%80%E9%80%80%E4%BA%8C%E5%80%8D%E6%8A%95%E6%B3%95_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/QmF
- 急救知识普及的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8%E7%A0%81%E8%BF%9B%E4%B8%80%E9%80%80%E4%BA%8C%E5%80%8D%E6%8A%95%E6%B3%95_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/930=quw
- 光伏知识科普的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8%E7%A0%81%E8%BF%9B%E4%B8%80%E9%80%80%E4%BA%8C%E5%80%8D%E6%8A%95%E6%B3%95_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/guh=639
- 数字地图应用的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8%E7%A0%81%E8%BF%9B%E4%B8%80%E9%80%80%E4%BA%8C%E5%80%8D%E6%8A%95%E6%B3%95_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/Ahv=1vB
- 图书借阅体验中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E8%B5%8C%E5%BE%92%E6%8A%BC%E6%B3%A8%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E6%96%B9%E6%B3%95_360%E6%99%9A%E6%8A%A5?/967
- 公共服务沟通的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E8%B5%8C%E5%BE%92%E6%8A%BC%E6%B3%A8%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E6%96%B9%E6%B3%95_360%E6%99%9A%E6%8A%A5?/wti
- 家庭园艺实践的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E8%B5%8C%E5%BE%92%E6%8A%BC%E6%B3%A8%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E6%96%B9%E6%B3%95_360%E6%99%9A%E6%8A%A5?/5ZS
- 节假日出行安排的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E8%B5%8C%E5%BE%92%E6%8A%BC%E6%B3%A8%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E6%96%B9%E6%B3%95_360%E6%99%9A%E6%8A%A5?/377=wso
- 机器人科普活动的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E8%B5%8C%E5%BE%92%E6%8A%BC%E6%B3%A8%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E6%96%B9%E6%B3%95_360%E6%99%9A%E6%8A%A5?/hnk=335
- 乡村生态观察的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E8%B5%8C%E5%BE%92%E6%8A%BC%E6%B3%A8%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E6%96%B9%E6%B3%95_360%E6%99%9A%E6%8A%A5?/RwM=XC8
- 开源技术交流的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%8D%9A%E7%8E%8B%E7%A7%91%E5%AD%A6%E5%80%8D%E6%8A%9510%E4%B8%AD4_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/080
- 亲子阅读活动的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%8D%9A%E7%8E%8B%E7%A7%91%E5%AD%A6%E5%80%8D%E6%8A%9510%E4%B8%AD4_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/msc
- 城市文明实践的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%8D%9A%E7%8E%8B%E7%A7%91%E5%AD%A6%E5%80%8D%E6%8A%9510%E4%B8%AD4_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/CH3
- 街区更新实践的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%8D%9A%E7%8E%8B%E7%A7%91%E5%AD%A6%E5%80%8D%E6%8A%9510%E4%B8%AD4_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/833=dpl
- 家庭环保行动的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%8D%9A%E7%8E%8B%E7%A7%91%E5%AD%A6%E5%80%8D%E6%8A%9510%E4%B8%AD4_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/cdd=375
- 音乐欣赏活动的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E5%8D%9A%E7%8E%8B%E7%A7%91%E5%AD%A6%E5%80%8D%E6%8A%9510%E4%B8%AD4_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/ghY=ZOk
- 家庭食品保存的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E7%BD%91%E8%B5%8C%E5%AF%B9%E5%88%B7%E4%B8%80%E4%B8%AA%E6%9C%88%E6%8C%A3300%E4%B8%87_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/000
- 城市文化路线的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E7%BD%91%E8%B5%8C%E5%AF%B9%E5%88%B7%E4%B8%80%E4%B8%AA%E6%9C%88%E6%8C%A3300%E4%B8%87_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/uxh
- 公益活动组织的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E7%BD%91%E8%B5%8C%E5%AF%B9%E5%88%B7%E4%B8%80%E4%B8%AA%E6%9C%88%E6%8C%A3300%E4%B8%87_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/JAF
- 乡村生态观察从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E7%BD%91%E8%B5%8C%E5%AF%B9%E5%88%B7%E4%B8%80%E4%B8%AA%E6%9C%88%E6%8C%A3300%E4%B8%87_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/372=zzi
- 城乡公共服务的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E7%BD%91%E8%B5%8C%E5%AF%B9%E5%88%B7%E4%B8%80%E4%B8%AA%E6%9C%88%E6%8C%A3300%E4%B8%87_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/vcm=782
- 日常摄影记录的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E7%BD%91%E8%B5%8C%E5%AF%B9%E5%88%B7%E4%B8%80%E4%B8%AA%E6%9C%88%E6%8C%A3300%E4%B8%87_%E7%9F%A5%E4%B9%8E%E5%88%B8%E5%95%86?/F7V=tOf
- 公共空间休憩的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_6%E7%A0%81345678%E4%B8%8D%E6%AD%BB%E8%A7%84%E5%BE%8B%E5%9B%BE%E7%89%87_%E6%8A%96%E9%9F%B3%E8%B4%A2%E6%8A%A5?/042
- 农产品品牌传播的基础知识问答 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_6%E7%A0%81345678%E4%B8%8D%E6%AD%BB%E8%A7%84%E5%BE%8B%E5%9B%BE%E7%89%87_%E6%8A%96%E9%9F%B3%E8%B4%A2%E6%8A%A5?/qvv

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
