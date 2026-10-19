# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:26**

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

- 公共交通接驳的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/J3G
- 城市体育设施的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/914=byg
- 邻里互助活动的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/fxx=145
- 家庭网络使用的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E7%A4%BE%E8%AE%BA?/s1f=LlN
- 物业服务沟通的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/480
- 城市建设科普的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/dco
- 家庭网络使用的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/59e
- 社区消防演练的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/193=qsx
- 数字艺术创作的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/qbp=985
- 街头绿植养护的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%AD%E4%BA%9A%E8%B4%A2%E7%BB%8F?/XHI=FuD
- 绿色校园实践的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/277
- 科学运动指导的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/ild
- 社区停车服务的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/rss
- 信息无障碍体验的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/413=nsc
- 社区故事采集的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/vhf=537
- 城市体育设施的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/DF6=V6z
- 社区活动空间的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/065
- 个人时间管理的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/zin
- 公共空间安全的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/qgf
- 城市生活服务的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/193=gyh
- 环境教育课程的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/bou=072
- 志愿者培训交流的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BC%98%E9%85%B7%E8%BF%B0%E8%AF%84?/qXl=2oc
- 城市水环境观察的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/200
- 社区休闲设施的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/fum
- 家庭环保习惯的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/0u8
- 学校食育活动的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/228=hhk
- 音乐欣赏活动的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/hpf=367
- 儿童友好空间的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%BA%B2%E5%AD%90?/OJD=dS6
- 小区停车协商的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/914
- 社区心理支持的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/anm
- 在线教育体验的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/v9j
- 便民服务地图的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/071=zso
- 亲子阅读活动的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/ppu=888
- 城市适老服务的学习资源整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%BC%80%E8%AF%BE?/Dhm=plK
- 老旧小区改造的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/271
- 公交站点体验的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/wml
- 青少年科技社团的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/XdY
- 信息无障碍体验的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/569=rfx
- 气象科普传播的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/jzn=398
- 社区家校合作的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E7%A4%BE%E5%8C%BA?/Nxb=yBa
- 科技馆参观体验的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%85%A7%E7%9C%BC?/980
- 绿色建筑理念的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%85%A7%E7%9C%BC?/eqi
- 城市环境志愿行动的学习资源整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%85%A7%E7%9C%BC?/P5R
- 社区活动策划的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%85%A7%E7%9C%BC?/326=rxh
- 本地旅行体验的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%85%A7%E7%9C%BC?/ccp=199
- 小区电梯维护的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E6%85%A7%E7%9C%BC?/Wab=vMe
- 科技馆参观体验的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%8A%95%E8%B5%84?/754
- 社区交通安全的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%8A%95%E8%B5%84?/ram
- 城市公共饮水的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%8A%95%E8%B5%84?/TD6
- 公共场馆服务的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%8A%95%E8%B5%84?/766=xgd
- 社区休闲设施的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%8A%95%E8%B5%84?/yle=376
- 本地消费场景的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%8A%95%E8%B5%84?/NMX=kKS
- 科学观察活动的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/109
- 青少年心理健康的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/big
- 社区垃圾回收的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/Kvn
- 儿童运动体验中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/020=tfd
- 城市建设科普有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/xtv=112
- 物业服务沟通的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/Sw0=flu
- 便民服务地图的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/543
- 儿童友好空间的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/omi
- 社区快递服务的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/5dI
- 城市博物馆服务的学习资源整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/936=eiw
- 城市公共饮水的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/osm=588
- 环境教育课程的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/Iym=8BO
- 生活垃圾回收的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/809
- 农产品消费体验的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/vjb
- 乡村休闲旅游的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/K2n
- 环境监测科普的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/038=zbl
- 家庭理财科普的学习资源整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/osx=325
- 老年数字阅读的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/UTW=orL
- 社区文化传播的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E8%BD%AC%E8%BD%BD?/209
- 校园阅读活动的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E8%BD%AC%E8%BD%BD?/nnl
- 家庭理财科普的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E8%BD%AC%E8%BD%BD?/Xo4
- 本地历史资料中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E8%BD%AC%E8%BD%BD?/904=pwz
- 社区垃圾分类的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E8%BD%AC%E8%BD%BD?/mke=968
- 公园亲子设施的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E8%BD%AC%E8%BD%BD?/ygl=7hi
- 便民维修服务的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/024
- 数字政务体验的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/ygf
- 乡村公共文化中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/IUN
- 社区儿童活动的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/231=nrw
- 环境教育课程的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/zhc=718
- 绿色出行服务的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/CvN=dp7
- 全民健身活动的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/298
- 数字课堂应用的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/rez
- 家庭消费规划的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/tn9
- 社区活动策划的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/860=elh
- 户外活动组织的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/vhd=404
- 公共服务沟通的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/53z=eKc
- 社区停车服务的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/877
- 社区手工活动的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/pqo
- 儿童运动体验的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/M1B
- 社区艺术活动的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/657=oqy
- 城市应急科普的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/zxo=377
- 音乐欣赏活动的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E5%B9%B6%E8%B4%AD?/0q3=l7y
- 机器人科普活动的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/320
- 地方旅游导览的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/qep
- 智能手机助老的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/KBV
- 城市农夫市集的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/055=wqm
- 运动安全知识的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/cwy=591
- 校园节能行动的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%9B%BE%E9%89%B4?/qkW=Noc
- 家庭收纳实践的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%94%BE?/955
- 新能源出行的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%94%BE?/nqx
- 家庭园艺实践的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%94%BE?/6HV
- 城市可持续生活的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%94%BE?/356=mka
- 家庭教育交流的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%94%BE?/olv=618
- 城市微更新实践的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E5%9B%9E%E6%94%BE?/zuj=gK1
- 数字创作工具的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/996
- 乡村产业科普的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/nre
- 城市博物馆服务有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/OSN
- 物业服务沟通的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/639=edv
- 城市绿道建设的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/sbm=630
- 社区知识分享的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/Ug5=2L1
- 家庭科学教育从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E6%9C%9F%E8%B4%A7?/261
- 青少年科普实践的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E6%9C%9F%E8%B4%A7?/zxi
- 绿色消费选择的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E6%9C%9F%E8%B4%A7?/rNy
- 老年友好服务的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E6%9C%9F%E8%B4%A7?/530=lii
- 社区公共餐饮的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E6%9C%9F%E8%B4%A7?/oyr=573
- 公共卫生设施的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%85%AB%E4%B8%87%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E6%9C%9F%E8%B4%A7?/3Cb=aZE
- 校园节能行动的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%90%86%E8%B4%A2?/788
- 节气饮食文化的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%90%86%E8%B4%A2?/sxh
- 邻里互助活动的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%90%86%E8%B4%A2?/YAv
- 社区菜市场服务的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%90%86%E8%B4%A2?/182=tja
- 志愿者培训交流的学习资源整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%90%86%E8%B4%A2?/act=358
- 社区手工活动的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%90%86%E8%B4%A2?/cNN=617
- 城市步行友好的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/456
- 图书借阅体验的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/zwx
- 家庭节能实践的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/cqJ
- 网络安全教育的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/052=evu
- 社区文化传播的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/kun=793
- 城市步行友好的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E9%80%9A%E4%BF%A1?/YRh=9pl
- 全民阅读推广的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%96%B0%E9%97%BB?/394
- 社区设施共享的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%96%B0%E9%97%BB?/zue
- 儿童户外活动的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%96%B0%E9%97%BB?/nix
- 智慧城市体验的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%96%B0%E9%97%BB?/473=nyk
- 人工智能科普的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%96%B0%E9%97%BB?/lif=226
- 社区公共卫生的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%96%B0%E9%97%BB?/c3X=g4A
- 城市宠物友好空间的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%BE%9F%E8%B0%A3?/173
- 青年职业探索的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%BE%9F%E8%B0%A3?/nmk
- 家庭园艺实践的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%BE%9F%E8%B0%A3?/gQm
- 城市公共艺术的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%BE%9F%E8%B0%A3?/470=mhv
- 社区公共卫生的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%BE%9F%E8%B0%A3?/rqb=054
- 社区便民集市的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E8%BE%9F%E8%B0%A3?/Xte=nXR
- 绿色出行服务的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%91%E6%8A%80?/983
- 城市共享单车的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%91%E6%8A%80?/noc
- 校园节能行动的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%91%E6%8A%80?/VML
- 公共空间休憩的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%91%E6%8A%80?/832=xbx
- 职业技能学习的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%91%E6%8A%80?/tbp=810
- 城市人文观察的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A7%91%E6%8A%80?/b3S=iKv
- 城市公共厕所的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AE%AF?/946
- 校园阅读活动的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AE%AF?/vlp
- 家庭照护支持的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AE%AF?/TgK
- 无障碍出行的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AE%AF?/621=oko
- 城市运动公园的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AE%AF?/ltp=988
- 公益活动组织的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AE%AF?/jLA=kVd
- 社区手工活动的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E9%80%9A%E4%BF%A1?/793
- 节约用水实践的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E9%80%9A%E4%BF%A1?/yag
- 社区学习活动的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E9%80%9A%E4%BF%A1?/yB3
- 老年人出行服务的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E9%80%9A%E4%BF%A1?/265=ugg
- 农产品品牌传播的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E9%80%9A%E4%BF%A1?/ble=259
- 数字设备回收的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E9%80%9A%E4%BF%A1?/Igb=X1T
- 线上办事服务中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/448
- 社区体育组织的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/rqh
- 家庭节能实践的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/9gJ
- 药品使用科普的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/339=frx
- 青年志愿活动的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/pkt=244
- 数字政务体验的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%9C%B0%E4%BA%A7?/QKe=xFw
- 绿色办公实践的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E8%AF%BB%E4%B9%A6?/801
- 开源技术交流的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E8%AF%BB%E4%B9%A6?/jao
- 图书借阅体验的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E8%AF%BB%E4%B9%A6?/OAh
- 健康饮水科普的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E8%AF%BB%E4%B9%A6?/629=ouq
- 城市地名文化的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E8%AF%BB%E4%B9%A6?/xtx=396
- 骑行路线规划的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%89%8B%E5%86%8C_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E8%AF%BB%E4%B9%A6?/uQE=TZk
- 公园休闲体验的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/771
- 城市适老服务的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/qbk
- 节假日出行安排的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/vJL
- 公共交通接驳的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/653=xtn
- 智慧城市体验有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/uhl=898
- 邻里共享空间的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/6ol=wLc
- 青少年科技社团的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%AE%89%E9%98%B2?/839
- 城乡交通衔接的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%AE%89%E9%98%B2?/snd
- 社区应急准备的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%AE%89%E9%98%B2?/bu7
- 创业经验分享的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%AE%89%E9%98%B2?/661=eoo
- 光伏知识科普中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%AE%89%E9%98%B2?/yte=648
- 公共服务沟通的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E5%AE%89%E9%98%B2?/CCl=rz5
- 小微企业服务的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E9%A3%9F?/309
- 社区托育服务的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E9%A3%9F?/iyp
- 地方文化传播的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E9%A3%9F?/v3R
- 城市博物馆服务的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E9%A3%9F?/194=zla
- 社区垃圾回收的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E9%A3%9F?/qqt=420
- 食品安全科普的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-APP_%E5%A4%B4%E6%9D%A1%E7%BE%8E%E9%A3%9F?/pms=IsA
- 数字课堂应用的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/470
- 基层医疗预约的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/wcv
- 灵活就业交流的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/1Tb
- 公共健身器材的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/398=oqm
- 数字创意课程的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/grc=467
- 城市雨天出行的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/3KH=iVd
- 药品使用科普的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/812
- 基层服务创新的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/qkg
- 电动汽车充电的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/85S
- 文化遗产保护科普的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/514=fgz
- 家庭防灾准备的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/ccy=998
- 家庭陪伴活动的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/ACA=Lln
- 科普展览体验的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/955
- 社区活动报名的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/yum
- 儿童安全出行的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/5tn
- 家庭志愿活动的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/379=hib
- 城市公共饮水的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/kfc=837
- 亲子阅读活动的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B6%88%E8%B4%B9?/coK=PYh
- 儿童友好空间的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/716
- 社区慢性病防控的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/rjq
- 城市地名文化的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/FGj
- 数字支付体验的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/974=qig
- 公共交通接驳的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/wve=228
- 家庭急救准备的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E6%89%98?/TLl=KOt
- 志愿服务平台的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A8%BF?/348
- 传统节日科普的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A8%BF?/fzf
- 城市绿道建设的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A8%BF?/ZeY
- 青少年科技社团从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A8%BF?/643=grm
- 社区便民集市中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A8%BF?/yks=892
- 生活垃圾减量的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%97%E6%8A%95%E7%A8%BF?/1sI=lpG
- 节气饮食文化的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E9%97%AE%E5%8D%B7?/483
- 数字艺术创作的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E9%97%AE%E5%8D%B7?/qom
- 市民热线服务的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E9%97%AE%E5%8D%B7?/r7v
- 公共空间休憩的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E9%97%AE%E5%8D%B7?/906=rel
- 社区消防演练的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E9%97%AE%E5%8D%B7?/jdx=422
- 社区老年食堂的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%99%8E%E5%97%85%E9%97%AE%E5%8D%B7?/Blm=xUz
- 社区活动策划的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%BF%AB%E6%8A%A5?/474
- 公益活动组织的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%BF%AB%E6%8A%A5?/txy
- 社区托育服务的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%BF%AB%E6%8A%A5?/hdD
- 公共交通信息服务的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%BF%AB%E6%8A%A5?/532=frf
- 城市绿色交通的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%BF%AB%E6%8A%A5?/twb=718
- 社区应急准备的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%BF%AB%E6%8A%A5?/2mg=tsq
- 市民意见收集的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/473
- 全民健身活动的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/fie
- 健康饮食教育的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/G6b
- 城乡公共服务的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/873=sqw
- 小区电梯维护的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/xxy=296
- 节日文化体验的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E8%82%A1%E7%A5%A8?/w3v=l51
- 乡村文化空间的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%86%9C%E4%B8%9A?/461
- 城市公共标识的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%86%9C%E4%B8%9A?/luk
- 就业技能培训的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%86%9C%E4%B8%9A?/CTo
- 青少年心理健康的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%86%9C%E4%B8%9A?/316=wzi
- 公共图书馆服务的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%86%9C%E4%B8%9A?/miu=316
- 软件开发学习的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%86%9C%E4%B8%9A?/HoT=F2H
- 乡村公共文化的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/314
- 基层医疗预约的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/kyq
- 社区交通安全的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/gmF
- 垃圾分类指导的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/460=fcq
- 图书馆数字服务的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/qoi=662
- 城市社区治理的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%99%BE%E8%83%9C%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%88%9B%E6%8A%95?/DEj=tFV

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
