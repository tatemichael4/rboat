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

- 绿色出行服务从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E8%B6%A3%E8%B4%AD%E5%BD%A9%28%E7%BD%91%E9%A1%B5%E7%89%88%29_%E5%A4%AE%E8%A7%86%E7%90%86%E8%B4%A2?/tes=630
- 个人数据管理的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E8%B6%A3%E8%B4%AD%E5%BD%A9%28%E7%BD%91%E9%A1%B5%E7%89%88%29_%E5%A4%AE%E8%A7%86%E7%90%86%E8%B4%A2?/tzj=Xun
- 家庭防灾准备的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/992
- 城市绿色交通的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/pkc
- 邻里互助活动的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/lrb
- 社区家校合作的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/776=xkq
- 公共空间休憩的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/xjq=489
- 城市空气科普的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E8%81%8C%E5%9C%BA?/hca=VMp
- 乡村公共阅读的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/751
- 医院导诊服务有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/jzp
- 绿色消费选择的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/RfP
- 零废弃生活尝试的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/306=qwp
- 便民信息查询的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/rgt=624
- 安全出行教育的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E7%88%86%E6%96%99?/rTD=t0c
- 社区故事采集的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%9B%B4%E6%8E%A5%E7%99%BB%E5%BD%95_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/340
- 社区知识分享的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%9B%B4%E6%8E%A5%E7%99%BB%E5%BD%95_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/uid
- 数字学习资源的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%9B%B4%E6%8E%A5%E7%99%BB%E5%BD%95_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/RP0
- 节能家电使用的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%9B%B4%E6%8E%A5%E7%99%BB%E5%BD%95_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/127=ddx
- 本地消费场景的空间设计要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%9B%B4%E6%8E%A5%E7%99%BB%E5%BD%95_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/fxm=749
- 家庭食品保存的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%9B%B4%E6%8E%A5%E7%99%BB%E5%BD%95_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/uHG=GWU
- 社区科普课堂的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/853
- 节气饮食文化的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/oyv
- 社区活动策划的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/HGg
- 青少年科技社团的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/661=clo
- 地方民俗记录的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/kcd=706
- 社区安全巡查的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95_%E8%85%BE%E8%AE%AF%E8%AF%BB%E4%B9%A6?/Pbk=xwj
- 老年人文化生活的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E8%80%81%E7%89%88%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E4%BF%A1%E8%AE%BF?/122
- 数字创意课程的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E8%80%81%E7%89%88%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E4%BF%A1%E8%AE%BF?/pwi
- 城市博物馆服务的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E8%80%81%E7%89%88%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E4%BF%A1%E8%AE%BF?/tUD
- 物业服务沟通的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E8%80%81%E7%89%88%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E4%BF%A1%E8%AE%BF?/427=jwp
- 公共空间照明的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E8%80%81%E7%89%88%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E4%BF%A1%E8%AE%BF?/ccj=119
- 数字创意课程的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E8%80%81%E7%89%88%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E4%BF%A1%E8%AE%BF?/tkp=YqS
- 公共空间导览的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_767%E6%97%A7%E5%BD%A9%E5%BD%A9%E7%A5%A89767._%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/720
- 社区老年食堂的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_767%E6%97%A7%E5%BD%A9%E5%BD%A9%E7%A5%A89767._%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/zlm
- 市民意见收集的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_767%E6%97%A7%E5%BD%A9%E5%BD%A9%E7%A5%A89767._%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/Xiz
- 城市水环境观察的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_767%E6%97%A7%E5%BD%A9%E5%BD%A9%E7%A5%A89767._%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/226=joo
- 电子商务服务的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_767%E6%97%A7%E5%BD%A9%E5%BD%A9%E7%A5%A89767._%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/doo=467
- 社区文化节活动的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_767%E6%97%A7%E5%BD%A9%E5%BD%A9%E7%A5%A89767._%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/mAd=551
- 城市公共空间的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/013
- 城市基础设施的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/nnq
- 公园休闲体验的协作机制梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/poH
- 社区邻里服务的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/272=zlu
- 校园安全教育的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/kvj=915
- 公共服务数字化的协作机制梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/QjW=VjI
- 社区信息发布的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/109
- 城市共享单车有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/maf
- 基层医疗预约中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/SoM
- 街区更新实践的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/043=ruv
- 社区花园共建的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/slw=060
- 青少年科技社团的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/v50=bPK
- 低碳社区实践的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E5%B1%85?/031
- 全民健身活动的协作机制梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E5%B1%85?/fjm
- 跨代沟通活动有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E5%B1%85?/h3r
- 城乡交流活动的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E5%B1%85?/968=xrs
- 社区信息发布的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E5%B1%85?/eru=297
- 社区体育组织中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E5%B1%85?/6Ne=8Nm
- 科学观察活动中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8365%E9%80%9F%E5%8F%91%E7%8E%A9%E6%B3%95_%E6%8A%96%E9%9F%B3%E9%9F%B3%E4%B9%90?/716
- 家庭安全提示中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8365%E9%80%9F%E5%8F%91%E7%8E%A9%E6%B3%95_%E6%8A%96%E9%9F%B3%E9%9F%B3%E4%B9%90?/oqw
- 本地消费场景的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8365%E9%80%9F%E5%8F%91%E7%8E%A9%E6%B3%95_%E6%8A%96%E9%9F%B3%E9%9F%B3%E4%B9%90?/7Ua
- 零废弃生活尝试的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8365%E9%80%9F%E5%8F%91%E7%8E%A9%E6%B3%95_%E6%8A%96%E9%9F%B3%E9%9F%B3%E4%B9%90?/871=wto
- 地方文化传播的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8365%E9%80%9F%E5%8F%91%E7%8E%A9%E6%B3%95_%E6%8A%96%E9%9F%B3%E9%9F%B3%E4%B9%90?/upj=611
- 家庭网络使用的空间设计要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8365%E9%80%9F%E5%8F%91%E7%8E%A9%E6%B3%95_%E6%8A%96%E9%9F%B3%E9%9F%B3%E4%B9%90?/ssv=k7O
- 无障碍信息设计的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%9B%B2%E8%89%BA?/775
- 家庭消费规划的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%9B%B2%E8%89%BA?/una
- 垃圾分类指导的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%9B%B2%E8%89%BA?/5Zc
- 青少年职业启蒙的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%9B%B2%E8%89%BA?/479=cgs
- 城市雨天出行的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%9B%B2%E8%89%BA?/bmr=022
- 数字政务体验的资源整合思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%9B%B2%E8%89%BA?/rUa=Sgx
- 社区科普课堂的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A6%82%E6%84%8F%E5%BD%A9%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E8%84%89%E8%84%89%E7%A8%8E%E5%8A%A1?/663
- 乡村公共阅读的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A6%82%E6%84%8F%E5%BD%A9%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E8%84%89%E8%84%89%E7%A8%8E%E5%8A%A1?/olf
- 家庭急救准备的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A6%82%E6%84%8F%E5%BD%A9%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E8%84%89%E8%84%89%E7%A8%8E%E5%8A%A1?/Kx8
- 信息无障碍体验的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A6%82%E6%84%8F%E5%BD%A9%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E8%84%89%E8%84%89%E7%A8%8E%E5%8A%A1?/889=toj
- 骑行路线规划的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A6%82%E6%84%8F%E5%BD%A9%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E8%84%89%E8%84%89%E7%A8%8E%E5%8A%A1?/upk=208
- 节假日出行安排的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_%E5%A6%82%E6%84%8F%E5%BD%A9%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E8%84%89%E8%84%89%E7%A8%8E%E5%8A%A1?/Qyu=F8u
- 亲子阅读活动的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/980
- 信息无障碍体验的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/gzn
- 城市文化路线的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/iyC
- 绿色快递包装的服务细节记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/735=beg
- 志愿者培训交流的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/yrt=982
- 数字课堂应用的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E5%8F%B7%E5%A4%96?/3lt=rVf
- 文化讲座服务的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85IOS_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E6%BA%90?/142
- 城市慢行系统的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85IOS_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E6%BA%90?/dbs
- 健康饮食教育有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85IOS_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E6%BA%90?/qV5
- 全民健身活动的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85IOS_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E6%BA%90?/335=lph
- 老年人文化生活的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85IOS_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E6%BA%90?/xvq=136
- 社区商业活力的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85IOS_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E6%BA%90?/wsF=Dj4
- 社区健康讲座的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%A4%A7%E9%85%92%E5%BA%97_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/337
- 机器学习入门的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%A4%A7%E9%85%92%E5%BA%97_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/vlx
- 乡村阅读活动的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%A4%A7%E9%85%92%E5%BA%97_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/kBh
- 社区学习活动的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%A4%A7%E9%85%92%E5%BA%97_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/148=jvh
- 社区应急准备的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%A4%A7%E9%85%92%E5%BA%97_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/tga=509
- 公交无障碍服务的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%A4%A7%E9%85%92%E5%BA%97_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/L4S=5Wi
- 公共服务沟通的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/816
- 社区便民服务的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/mlm
- 乡村公共文化的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/4Cx
- 非遗课堂体验的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/468=drr
- 社区垃圾分类的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/cup=361
- 地方文化传播的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/FhP=bTC
- 家庭健康科普的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/341
- 家庭防灾准备的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/bem
- 儿童安全出行的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/VzI
- 环境监测科普的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/576=fad
- 地方文化传播的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/cpf=262
- 乡村文化空间的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E7%BD%91%E7%AB%99_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%99%BE%E7%A7%91?/t56=Ees
- 数字创作工具的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%AF%BB%E5%9B%BE?/977
- 社区活动空间的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%AF%BB%E5%9B%BE?/ihd
- 儿童运动体验的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%AF%BB%E5%9B%BE?/zqM
- 街头绿植养护的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%AF%BB%E5%9B%BE?/339=btl
- 公共空间照明的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%AF%BB%E5%9B%BE?/wxf=121
- 社区绿色空间的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E8%AF%BB%E5%9B%BE?/rB5=tGZ
- 街区绿化养护的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/355
- 图书馆数字服务的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/bul
- 小微企业服务中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/VrU
- 绿色快递包装的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/019=njy
- 老年友好服务的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/pxo=308
- 网络安全教育中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-Welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F?/5gq=k5K
- 读书会组织的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%5B_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/850
- 家庭环保行动的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%5B_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/eoy
- 节气饮食文化的资源整合思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%5B_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/lme
- 城市文明出行的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%5B_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/210=klb
- 网络信息辨识的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%5B_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/aeh=319
- 老年人日常照护的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%5B_%E8%99%8E%E6%89%91%E8%AE%BA%E5%9D%9B?/BfF=UGy
- 地方美食文化的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/309
- 邻里共享空间的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/lxg
- 生活垃圾减量的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/9iZ
- 便民信息查询的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/682=req
- 社区学习活动的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/tcr=975
- 就业技能培训的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E6%97%85%E6%B8%B8?/4VX=dJo
- 城乡交通衔接的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A5%A8?/792
- 城市便民驿站中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A5%A8?/ptd
- 家庭食品保存的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A5%A8?/qhF
- 机器人科普活动从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A5%A8?/783=dth
- 社区菜市场服务的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A5%A8?/qkk=501
- 公共空间导览的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F%E6%B7%98%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E6%8A%95%E7%A5%A8?/cLb=xsM
- 消防知识宣传的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/631
- 城市公共饮水的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/kpk
- 家庭收纳实践的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/bKg
- 城乡交通衔接的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/509=wyq
- 社区宠物管理的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/how=386
- 邻里共享空间的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%B7%98%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%9E%E6%94%BE?/isu=d2v
- 校园阅读活动的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/605
- 城市微更新实践的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/bei
- 城市博物馆活动的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/9r4
- 环境教育课程的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/069=olp
- 儿童运动体验有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/yvv=868
- 公共交通信息服务的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E8%AF%BB%E5%9B%BE?/IV6=LKM
- 文化场馆预约的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/774
- 图书馆亲子空间的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/wnz
- 城市噪声观察的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/npQ
- 节能家电使用的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/550=hfm
- 社区协商议事的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/ngq=028
- 读书会组织的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%9F%B3%E4%B9%90?/hZF=B0V
- 公共空间导览的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E5%9F%8E%E4%BA%8B?/369
- 城市步行友好的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E5%9F%8E%E4%BA%8B?/xfm
- 家庭节能实践的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E5%9F%8E%E4%BA%8B?/6Ek
- 城市慢行系统的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E5%9F%8E%E4%BA%8B?/777=qvz
- 乡村公共阅读的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E5%9F%8E%E4%BA%8B?/nlg=041
- 农贸市场环境的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E8%85%BE%E8%AE%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E5%9F%8E%E4%BA%8B?/yhh=zQH
- 城市步行环境的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%5B_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/086
- 旧物循环利用的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%5B_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/yoj
- 职业技能学习有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%5B_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/ZnM
- 休闲运动入门的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%5B_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/942=dkn
- 绿色校园实践的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%5B_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/jqh=560
- 公共健身器材的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%5B_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/Rn1=fp7
- 图书馆亲子空间的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/998
- 城市体育设施的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/tyt
- 药品使用科普的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/JD1
- 家庭健康科普的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/667=srz
- 生活垃圾减量的协作机制梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/srm=381
- 创业经验分享的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/v6M=H1i
- 公园休闲体验的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/494
- 智能手机助老的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/bhh
- 基层健康服务的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/WfQ
- 软件开发学习的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/387=htq
- 节约用水实践的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/bqt=209
- 全民阅读推广的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/dxS=YJQ
- 社区停车服务的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/999
- 骑行路线规划的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/uqv
- 生活垃圾减量的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/06r
- 健康信息获取的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/296=hms
- 节假日出行安排的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/xgy=699
- 公共卫生设施的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A4%A9%E9%99%85%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/STN=qLP
- 公共图书馆服务的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E5%8E%86%E5%8F%B2?/792
- 社区宣传栏更新的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E5%8E%86%E5%8F%B2?/mpd
- 数字便民地图的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E5%8E%86%E5%8F%B2?/CfH
- 城乡交流活动的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E5%8E%86%E5%8F%B2?/392=rgv
- 老年数字阅读的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E5%8E%86%E5%8F%B2?/egr=349
- 科技馆参观体验的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E5%8E%86%E5%8F%B2?/E0k=1lf
- 社区生活指南的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/807
- 家庭运动计划的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/efi
- 食品配送体验从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/Tf8
- 社区应急准备有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/799=zdm
- 数字艺术创作中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/qwk=499
- 家庭园艺实践的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E8%A1%8C%E6%83%85?/7Jc=2LT
- 家庭陪伴活动从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/751
- 社区邻里服务的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/yvb
- 城市公共标识的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/OWX
- 休闲运动入门的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/095=qou
- 生活垃圾回收的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/yke=691
- 食品安全科普的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%B5%84%E8%AE%AF?/ZCK=Xcy
- 健康饮食教育的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/999
- 个人数据管理的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/qzf
- 绿色出行服务的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/qO3
- 本地消费场景从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/808=kyn
- 社区活动报名的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/dxp=898
- 城市应急广播的空间设计要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E8%B5%A2%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BE%9F%E8%B0%A3?/N1B=obX
- 市民意见收集的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%90%A7_%E5%93%94%E5%93%A9%E6%97%B6%E6%8A%A5?/409
- 便民信息查询的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%90%A7_%E5%93%94%E5%93%A9%E6%97%B6%E6%8A%A5?/vfj
- 家庭志愿活动有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%90%A7_%E5%93%94%E5%93%A9%E6%97%B6%E6%8A%A5?/7vB
- 数字素养提升的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%90%A7_%E5%93%94%E5%93%A9%E6%97%B6%E6%8A%A5?/718=tid
- 青少年心理健康的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%90%A7_%E5%93%94%E5%93%A9%E6%97%B6%E6%8A%A5?/uwu=178
- 社区老年食堂的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%90%A7_%E5%93%94%E5%93%A9%E6%97%B6%E6%8A%A5?/d3G=j0l
- 家庭健康科普的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/635
- 地方旅游导览的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/ntx
- 乡村文化空间的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/Nat
- 旧物循环利用的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/238=ttv
- 数字创意课程的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/esm=061
- 乡村文化活动的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%B0%B7%E6%AD%8C%E7%A8%8E%E5%8A%A1?/LJz=jnh
- 城市适老服务的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%97%B6%E8%AF%84?/461
- 城市树木认养的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%97%B6%E8%AF%84?/cjc
- 便民维修服务的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%97%B6%E8%AF%84?/vaw
- 职业技能学习中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%97%B6%E8%AF%84?/544=izz
- 读书会组织从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%97%B6%E8%AF%84?/ard=874
- 家庭节能实践的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%97%B6%E8%AF%84?/h7Q=5fs
- 职业技能学习的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%85%9A%E5%BB%BA?/901
- 乡村教育资源的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%85%9A%E5%BB%BA?/kbw
- 社区协商议事的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%85%9A%E5%BB%BA?/Xj4
- 社区信息发布的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%85%9A%E5%BB%BA?/096=xsu
- 社区文化节活动的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%85%9A%E5%BB%BA?/rfe=509
- 家庭节能实践的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E5%85%9A%E5%BB%BA?/Ybt=ERK
- 绿色出行服务的空间设计要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E7%95%85%E6%B8%B8?/909
- 在线学习体验的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E7%95%85%E6%B8%B8?/jhe
- 志愿服务平台的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E7%95%85%E6%B8%B8?/CTR
- 科学运动指导从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E7%95%85%E6%B8%B8?/295=job
- 农业科普体验的协作机制梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E7%95%85%E6%B8%B8?/qyv=706
- 气象科普传播的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E7%95%85%E6%B8%B8?/k21=l6h
- 校园阅读活动的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/942
- 科学信息获取的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/ube
- 便民维修服务的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/xql
- 志愿服务平台的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/930=qju
- 开源技术交流的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/ulr=767
- 社区知识分享的空间设计要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/Ahg=oCK
- 信息无障碍体验中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%28%E7%BD%91%E9%A1%B5%E7%89%88%29_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/699
- 社区阅读服务的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%28%E7%BD%91%E9%A1%B5%E7%89%88%29_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/gjc
- 数字公共文化的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%28%E7%BD%91%E9%A1%B5%E7%89%88%29_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/NUU
- 应急物资管理的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%28%E7%BD%91%E9%A1%B5%E7%89%88%29_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/673=keg
- 社区设施共享的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%28%E7%BD%91%E9%A1%B5%E7%89%88%29_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/wgy=663
- 生活技能分享的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%28%E7%BD%91%E9%A1%B5%E7%89%88%29_%E5%8D%8E%E5%AF%8C%E8%B4%A2%E7%BB%8F?/VN2=n9K
- 跨代沟通活动的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%5B_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/522
- 数字便民地图的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E7%BD%91%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%5B_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/pnw

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
