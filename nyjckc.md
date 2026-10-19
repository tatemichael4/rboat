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

- 绿色生活实践的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E5%8D%83%E5%B8%86?/ufd=043
- 科学运动指导的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E5%87%A4%E5%87%B0%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E5%8D%83%E5%B8%86?/KBa=PKk
- 儿童安全出行中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/307
- 社区公共餐饮的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/mcd
- 居家适老化改造的空间设计要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/l7C
- 家庭运动计划的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/896=bax
- 城市便民驿站的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/rjz=428
- 急救知识普及的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/DWh=m7d
- 城市游园体验的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/793
- 志愿服务平台的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/wia
- 城市运动公园的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/kPr
- 图书馆亲子空间的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/850=uhp
- 地方文化传播的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/nry=695
- 农村环境治理的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/spq=i4K
- 户外活动组织的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A896623_%E6%96%B0%E6%B5%AA%E6%B1%87%E5%B8%82?/409
- 公共文化活动的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A896623_%E6%96%B0%E6%B5%AA%E6%B1%87%E5%B8%82?/end
- 公共图书馆服务的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A896623_%E6%96%B0%E6%B5%AA%E6%B1%87%E5%B8%82?/6nN
- 公共服务指南的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A896623_%E6%96%B0%E6%B5%AA%E6%B1%87%E5%B8%82?/887=ikf
- 基层服务创新的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A896623_%E6%96%B0%E6%B5%AA%E6%B1%87%E5%B8%82?/typ=642
- 绿色建筑理念的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A896623_%E6%96%B0%E6%B5%AA%E6%B1%87%E5%B8%82?/C6l=H3n
- 公共服务咨询的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_9123%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BB%8F%E6%B5%8E?/028
- 街区道路维护的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_9123%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BB%8F%E6%B5%8E?/rie
- 节日文化体验有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_9123%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BB%8F%E6%B5%8E?/KLa
- 城乡公共服务的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_9123%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BB%8F%E6%B5%8E?/165=rsg
- 城市水环境观察的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_9123%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BB%8F%E6%B5%8E?/vrt=351
- 基层健康档案的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_9123%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BB%8F%E6%B5%8E?/VDP=qZ5
- 城市慢行系统的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%99%BA%E8%83%BD%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7app_%E6%90%9C%E7%8B%97%E5%AE%9E%E5%BD%95?/553
- 绿色校园实践的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%99%BA%E8%83%BD%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7app_%E6%90%9C%E7%8B%97%E5%AE%9E%E5%BD%95?/dhm
- 青年就业服务从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%99%BA%E8%83%BD%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7app_%E6%90%9C%E7%8B%97%E5%AE%9E%E5%BD%95?/7H1
- 城市宠物友好空间的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%99%BA%E8%83%BD%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7app_%E6%90%9C%E7%8B%97%E5%AE%9E%E5%BD%95?/866=wxb
- 社区安全巡查的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%99%BA%E8%83%BD%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7app_%E6%90%9C%E7%8B%97%E5%AE%9E%E5%BD%95?/gnn=704
- 社区阅读服务的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%99%BA%E8%83%BD%E5%BD%A9%E7%A5%A8%E9%80%89%E5%8F%B7app_%E6%90%9C%E7%8B%97%E5%AE%9E%E5%BD%95?/dcj=j50
- 医院导诊服务的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_3823%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/764
- 儿童运动体验的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_3823%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/cny
- 便民服务地图的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_3823%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/PIJ
- 城市博物馆服务的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_3823%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/500=gdx
- 社区学习活动的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_3823%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/btc=686
- 基层健康档案有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_3823%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/RGy=N1W
- 光伏知识科普的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E5%9B%BD%E5%86%85?/403
- 城乡公共服务的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E5%9B%BD%E5%86%85?/evg
- 小区电梯维护的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E5%9B%BD%E5%86%85?/f8f
- 智慧停车服务的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E5%9B%BD%E5%86%85?/290=hjp
- 口袋公园建设的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E5%9B%BD%E5%86%85?/wux=060
- 无障碍信息设计从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E5%9B%BD%E5%86%85?/gXJ=Ki6
- 社区体育组织的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%85%A7%E7%9C%BC?/856
- 数字支付体验从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%85%A7%E7%9C%BC?/xmy
- 城市可持续生活的服务细节记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%85%A7%E7%9C%BC?/RRV
- 家庭阅读计划的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%85%A7%E7%9C%BC?/304=elq
- 节能家电使用的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%85%A7%E7%9C%BC?/tbr=931
- 环境监测科普的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%85%A7%E7%9C%BC?/Wyv=P27
- 社区交通安全的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8IOS_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/195
- 生成式工具使用的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8IOS_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/vmd
- 城市绿色交通的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8IOS_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/cXQ
- 城市应急广播中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8IOS_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/504=blv
- 城市休闲步道的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8IOS_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/dfa=117
- 公共服务评价的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BD%A9%E7%A5%A8IOS_%E6%8A%96%E9%9F%B3%E6%95%B0%E7%A0%81?/li8=FmM
- 城市体育设施的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/242
- 社区活动空间中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/sln
- 无障碍出行的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/THV
- 居民健康教育的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/062=qgn
- 网络安全教育的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/mjf=320
- 在线教育体验的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BD%E9%99%85?/BbW=OSv
- 社区慢性病防控的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8D%8F?/508
- 城市住房服务的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8D%8F?/llt
- 家庭节能实践的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8D%8F?/5re
- 乡村生活观察的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8D%8F?/787=nzl
- 青少年户外教育的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8D%8F?/ygd=328
- 地方美食文化的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8D%8F?/8CO=OHD
- 节假日出行安排的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/454
- 生活技能分享的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/uxe
- 绿色办公实践的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/NZC
- 骑行路线规划的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/871=raz
- 租房信息服务的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/zhp=169
- 传统节日科普的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%99%BE%E5%BA%A6%E6%96%87%E5%8C%96?/L0A=his
- 家庭阅读计划的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E7%A0%81_%E9%A1%BA%E4%B8%B0%E6%97%B6%E5%B0%9A?/011
- 农产品品牌传播的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E7%A0%81_%E9%A1%BA%E4%B8%B0%E6%97%B6%E5%B0%9A?/jgv
- 低碳社区实践的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E7%A0%81_%E9%A1%BA%E4%B8%B0%E6%97%B6%E5%B0%9A?/6Vo
- 社区儿童活动的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E7%A0%81_%E9%A1%BA%E4%B8%B0%E6%97%B6%E5%B0%9A?/091=gmz
- 图书馆亲子空间的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E7%A0%81_%E9%A1%BA%E4%B8%B0%E6%97%B6%E5%B0%9A?/qpz=796
- 家庭陪伴活动的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E7%A0%81_%E9%A1%BA%E4%B8%B0%E6%97%B6%E5%B0%9A?/bkb=uXx
- 社区商业活力的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E9%A6%96%E9%A1%B5_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/138
- 低碳社区实践的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E9%A6%96%E9%A1%B5_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/roh
- 全民阅读推广的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E9%A6%96%E9%A1%B5_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/2m7
- 城乡交通衔接的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E9%A6%96%E9%A1%B5_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/329=rib
- 垃圾分类指导的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E9%A6%96%E9%A1%B5_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/pco=149
- 城市基础设施的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E9%A6%96%E9%A1%B5_%E6%B5%B7%E5%A4%96%E8%B4%A2%E7%BB%8F?/CGp=y8O
- 城市文明实践的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%85%BE%E8%AE%AF%E5%8E%86%E5%8F%B2?/149
- 地方美食文化的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%85%BE%E8%AE%AF%E5%8E%86%E5%8F%B2?/bya
- 绿色生活实践的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%85%BE%E8%AE%AF%E5%8E%86%E5%8F%B2?/HtM
- 城市博物馆活动的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%85%BE%E8%AE%AF%E5%8E%86%E5%8F%B2?/186=bky
- 城市夜间生活的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%85%BE%E8%AE%AF%E5%8E%86%E5%8F%B2?/ybm=496
- 乡村文化空间的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7_%E8%85%BE%E8%AE%AF%E5%8E%86%E5%8F%B2?/ViB=c1U
- 社区托育服务的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%95%85%E6%B8%B8?/888
- 家庭消费规划的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%95%85%E6%B8%B8?/rwp
- 城市农夫市集的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%95%85%E6%B8%B8?/qKE
- 公共文化活动中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%95%85%E6%B8%B8?/663=lte
- 城市游园体验的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%95%85%E6%B8%B8?/kvq=712
- 环境教育课程从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%95%85%E6%B8%B8?/eEa=tmS
- 老年人日常照护的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/281
- 数字艺术创作的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/hvw
- 图书馆活动策划中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/aPP
- 城市体育设施的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/083=cur
- 公共服务评价的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/zsh=350
- 城乡交流活动的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/4DO=DKC
- 智慧停车服务的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E7%9F%A5%E4%B9%8E%E4%BF%9D%E9%99%A9?/606
- 社区消防演练的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E7%9F%A5%E4%B9%8E%E4%BF%9D%E9%99%A9?/jyo
- 城市文化路线的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E7%9F%A5%E4%B9%8E%E4%BF%9D%E9%99%A9?/1DF
- 老年学习活动从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E7%9F%A5%E4%B9%8E%E4%BF%9D%E9%99%A9?/860=fhe
- 开放数据应用的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E7%9F%A5%E4%B9%8E%E4%BF%9D%E9%99%A9?/fik=369
- 数据分析入门中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC2023_%E7%9F%A5%E4%B9%8E%E4%BF%9D%E9%99%A9?/GNp=Caf
- 小区停车协商的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E6%BE%8E%E6%B9%83%E6%A6%9C%E5%8D%95?/200
- 社区家校合作的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E6%BE%8E%E6%B9%83%E6%A6%9C%E5%8D%95?/ajm
- 公共卫生设施从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E6%BE%8E%E6%B9%83%E6%A6%9C%E5%8D%95?/KMl
- 社区菜市场服务的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E6%BE%8E%E6%B9%83%E6%A6%9C%E5%8D%95?/658=lpq
- 公共场馆服务的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E6%BE%8E%E6%B9%83%E6%A6%9C%E5%8D%95?/wap=707
- 食品安全科普的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88_%E6%BE%8E%E6%B9%83%E6%A6%9C%E5%8D%95?/5Jh=B9A
- 社区便民集市的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E6%95%B0%E8%AF%BB?/836
- 城市适老服务的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E6%95%B0%E8%AF%BB?/ygj
- 社区宠物管理的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E6%95%B0%E8%AF%BB?/EKa
- 家庭健康科普的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E6%95%B0%E8%AF%BB?/577=bas
- 老年学习活动的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E6%95%B0%E8%AF%BB?/niq=241
- 本地历史资料的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E6%95%B0%E8%AF%BB?/JgY=7cR
- 老年人出行服务的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/210
- 公共卫生设施的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/vyp
- 生活垃圾减量的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/5RI
- 家庭环保习惯的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/260=mfh
- 街区小店体验的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/qiz=470
- 儿童阅读角从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E7%9B%98%E7%82%B9?/f5k=M4A
- 城市步行环境的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/655
- 城市休闲步道的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/epw
- 社区宣传栏更新的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/Dk4
- 城市公共艺术的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/522=irz
- 音乐欣赏活动的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/xvf=724
- 社区设施共享的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/rQR=psL
- 居民健康教育的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%86%9C%E4%B8%9A?/549
- 数字资源检索的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%86%9C%E4%B8%9A?/mzt
- 家庭急救准备的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%86%9C%E4%B8%9A?/2GO
- 在线教育体验的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%86%9C%E4%B8%9A?/351=ied
- 家庭陪伴活动的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%86%9C%E4%B8%9A?/exw=886
- 乡村文化空间的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%86%9C%E4%B8%9A?/gXy=wMC
- 社区教育资源的协作机制梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%BF%85%E5%BA%94%E5%AE%A0%E7%89%A9?/263
- 学校体育活动的服务细节记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%BF%85%E5%BA%94%E5%AE%A0%E7%89%A9?/tpg
- 家庭陪伴活动的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%BF%85%E5%BA%94%E5%AE%A0%E7%89%A9?/qQM
- 老年人文化生活的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%BF%85%E5%BA%94%E5%AE%A0%E7%89%A9?/655=uhl
- 城市公共空间的服务细节记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%BF%85%E5%BA%94%E5%AE%A0%E7%89%A9?/ogm=466
- 农产品消费体验的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97_%E5%BF%85%E5%BA%94%E5%AE%A0%E7%89%A9?/eRs=Uz3
- 家庭节能设备的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E8%AE%BE%E7%BD%AE%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E5%BF%AB%E6%89%8B%E6%94%BF%E7%AD%96?/743
- 社区故事采集的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E8%AE%BE%E7%BD%AE%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E5%BF%AB%E6%89%8B%E6%94%BF%E7%AD%96?/mcy
- 数字学习资源的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E8%AE%BE%E7%BD%AE%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E5%BF%AB%E6%89%8B%E6%94%BF%E7%AD%96?/N8x
- 急救知识普及的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E8%AE%BE%E7%BD%AE%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E5%BF%AB%E6%89%8B%E6%94%BF%E7%AD%96?/888=kxz
- 公共服务预约的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E8%AE%BE%E7%BD%AE%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E5%BF%AB%E6%89%8B%E6%94%BF%E7%AD%96?/vvk=813
- 公园亲子设施的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E6%88%91%E7%9A%84%E8%B4%A6%E6%88%B7%E8%AE%BE%E7%BD%AE%E6%AD%A5%E9%AA%A4%E8%AF%A6%E8%A7%A3_%E5%BF%AB%E6%89%8B%E6%94%BF%E7%AD%96?/rl4=EYk
- 社区宠物管理的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/218
- 数字资源检索从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/vwq
- 城市博物馆服务的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/zy8
- 课后服务体验的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/484=itf
- 骑行路线规划的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/okn=566
- 青少年职业启蒙的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9app%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E8%B5%84%E8%AE%AF?/mus=LWA
- 社区家校合作的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882023_%E8%B1%86%E7%93%A3%E5%80%BA%E5%B8%82?/834
- 家庭园艺实践的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882023_%E8%B1%86%E7%93%A3%E5%80%BA%E5%B8%82?/cce
- 家庭消费规划的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882023_%E8%B1%86%E7%93%A3%E5%80%BA%E5%B8%82?/3lO
- 家庭饮食安排的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882023_%E8%B1%86%E7%93%A3%E5%80%BA%E5%B8%82?/217=fkj
- 社区协商议事的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882023_%E8%B1%86%E7%93%A3%E5%80%BA%E5%B8%82?/wbm=509
- 城市雨天出行的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%882023_%E8%B1%86%E7%93%A3%E5%80%BA%E5%B8%82?/dfM=qll
- 社区故事采集的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/549
- 儿童友好空间的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/gcn
- 城市基础设施从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/rT6
- 社区协商议事的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/836=kje
- 终身学习资源的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/qpv=012
- 社区便民服务的资源整合思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E7%99%BE%E7%9B%88%E5%BD%A9%E7%A5%A8_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/sBw=a8Z
- 社区家政服务的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/106
- 城市应急科普的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/rds
- 社区庭院绿化的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/Cwb
- 公交无障碍服务的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/895=bat
- 家庭教育交流的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/gfy=381
- 数字便民地图的服务细节记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/VED=1BQ
- 运动安全知识的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/497
- 城乡公共服务的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/jai
- 非遗体验活动的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/fpj
- 公共服务指南的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/644=efx
- 公共设施使用的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/hqs=813
- 邻里互助活动的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E6%B0%B8%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/njU=C2A
- 无障碍信息设计的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_125%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/627
- 乡村教育资源的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_125%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/ocp
- 家庭教育交流的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_125%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/nh4
- 节约用水实践的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_125%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/590=prd
- 科学睡眠习惯的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_125%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/llz=295
- 邻里共享空间的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_125%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BE%97%E7%89%A9%E6%88%B7%E5%A4%96?/kBC=vGj
- 公共场所导视的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_9299cc%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/211
- 家庭环保行动的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_9299cc%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/vrn
- 乡村阅读空间的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_9299cc%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/fO1
- 市民意见收集的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_9299cc%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/226=ayh
- 社区养老服务的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_9299cc%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/hyz=643
- 家庭陪伴活动的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_9299cc%E7%99%BE%E7%91%9E%E5%BD%A9%E7%A5%A8_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/NFB=OAk
- 城市便民驿站的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85_%E6%90%9C%E7%8B%90%E6%B6%88%E8%B4%B9?/529
- 城市噪声观察的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85_%E6%90%9C%E7%8B%90%E6%B6%88%E8%B4%B9?/bsk
- 图书馆数字服务中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85_%E6%90%9C%E7%8B%90%E6%B6%88%E8%B4%B9?/f3I
- 地方美食文化的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85_%E6%90%9C%E7%8B%90%E6%B6%88%E8%B4%B9?/982=rky
- 农产品消费体验的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85_%E6%90%9C%E7%8B%90%E6%B6%88%E8%B4%B9?/bqt=932
- 家庭节能实践的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C1.99%E5%80%8D%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85_%E6%90%9C%E7%8B%90%E6%B6%88%E8%B4%B9?/ptX=E2q
- 城市公共饮水的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E7%B4%AB%E9%87%91%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1_36%E6%B0%AA%E5%88%B8%E5%95%86?/487
- 便民服务地图的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E7%B4%AB%E9%87%91%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1_36%E6%B0%AA%E5%88%B8%E5%95%86?/rvi
- 城市展览体验的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E7%B4%AB%E9%87%91%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1_36%E6%B0%AA%E5%88%B8%E5%95%86?/31d
- 乡村文化空间的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E7%B4%AB%E9%87%91%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1_36%E6%B0%AA%E5%88%B8%E5%95%86?/555=qjo
- 公交站点体验的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E7%B4%AB%E9%87%91%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1_36%E6%B0%AA%E5%88%B8%E5%95%86?/zhy=854
- 乡村公共文化的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E7%B4%AB%E9%87%91%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1_36%E6%B0%AA%E5%88%B8%E5%95%86?/jEv=EEs
- 公园休闲体验的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A887_%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/210
- 儿童阅读角的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A887_%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/wjl
- 数字地图应用的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A887_%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/sYX
- 社区便利生活的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A887_%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/814=akl
- 城市公共自行车的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A887_%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/rrw=609
- 节约用水实践的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A887_%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/nH4=lOi
- 便民服务窗口的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_87%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%B4%B7?/910
- 在线学习体验的协作机制梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_87%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%B4%B7?/gvm
- 公共文化活动的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_87%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%B4%B7?/5kq
- 健康饮水科普中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_87%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%B4%B7?/476=aka
- 社区绿色空间的空间设计要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_87%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%B4%B7?/eed=422
- 乡村教育资源的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_87%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%B4%B7?/TkA=UMp
- 社区艺术活动的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E6%81%92%E8%A1%8C%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/811
- 图书馆活动策划的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E6%81%92%E8%A1%8C%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/ilo
- 家庭网络使用的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E6%81%92%E8%A1%8C%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/cwI
- 公共空间休憩的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E6%81%92%E8%A1%8C%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/387=dyb
- 便民服务窗口的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E6%81%92%E8%A1%8C%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/elc=586
- 数字支付体验有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E6%81%92%E8%A1%8C%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/FQA=qwu
- 城市运动公园的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A81399_%E5%A4%AE%E8%A7%86%E4%B9%A6%E7%94%BB?/379
- 公共场所导视的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A81399_%E5%A4%AE%E8%A7%86%E4%B9%A6%E7%94%BB?/zax
- 社区健康讲座的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A81399_%E5%A4%AE%E8%A7%86%E4%B9%A6%E7%94%BB?/0be
- 社区家校合作的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A81399_%E5%A4%AE%E8%A7%86%E4%B9%A6%E7%94%BB?/985=ety
- 城市适老服务的资源整合思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A81399_%E5%A4%AE%E8%A7%86%E4%B9%A6%E7%94%BB?/loz=374
- 小区电梯维护的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A81399_%E5%A4%AE%E8%A7%86%E4%B9%A6%E7%94%BB?/PJL=LYW
- 传统手工艺体验的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8500%E5%AE%98%E7%BD%91_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/993
- 城市应急广播从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8500%E5%AE%98%E7%BD%91_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/ysq
- 开放式学习空间的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8500%E5%AE%98%E7%BD%91_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/l8H
- 社区绿色空间的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8500%E5%AE%98%E7%BD%91_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/057=jnp
- 青少年科普实践的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8500%E5%AE%98%E7%BD%91_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/svd=582
- 亲子阅读活动从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8500%E5%AE%98%E7%BD%91_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/Y2m=n8E
- 城市微更新实践的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_2050%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/093
- 社区慢性病防控的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_2050%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/lgn
- 农产品品牌传播的协作机制梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_2050%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/jy2
- 老年数字阅读的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_2050%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/467=nrt
- 读书会组织的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_2050%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/ksl=291
- 城市社区治理的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_2050%E5%BD%A9%E7%A5%A8_%E6%BE%8E%E6%B9%83%E7%BB%8F%E6%B5%8E?/PXf=bKE
- 农产品品牌传播的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/546
- 社区家校合作的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/sfn
- 市民热线服务的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/ETd
- 社区设施共享的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/212=iag
- 青少年编程学习的服务细节记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/vrj=695
- 科学运动指导的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E9%80%9F%E8%A7%88?/Yrl=jAe
- 数字学习资源的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8cp785cc_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/308
- 职业技能学习的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8cp785cc_%E4%BC%98%E9%85%B7%E6%96%87%E5%8C%96?/ttb

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
