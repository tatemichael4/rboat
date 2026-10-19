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

- 社区心理支持的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/tur=756
- 社区艺术活动的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%8F%B7%E5%A4%96?/XtE=rgJ
- 社区托育服务的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E7%A5%9E%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%BC%AB%E8%AF%84?/240
- 社区便民集市从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E7%A5%9E%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%BC%AB%E8%AF%84?/mve
- 环境监测科普的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E7%A5%9E%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%BC%AB%E8%AF%84?/QPQ
- 城乡公共服务中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E7%A5%9E%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%BC%AB%E8%AF%84?/643=xuc
- 农村环境治理的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E7%A5%9E%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%BC%AB%E8%AF%84?/dkg=022
- 家庭收纳实践的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E7%A5%9E%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E6%BC%AB%E8%AF%84?/YzV=3e7
- 新能源知识普及中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/129
- 农产品品牌传播的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/xnv
- 青少年编程学习的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/dHk
- 骑行路线规划的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/252=kra
- 科普展览体验的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/bvq=807
- 家庭环保行动的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/x7D=hnz
- 图书馆活动策划的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E8%A6%81%E9%97%BB?/065
- 数字课堂应用的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E8%A6%81%E9%97%BB?/nue
- 数字生活课堂的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E8%A6%81%E9%97%BB?/z3l
- 社区法律科普的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E8%A6%81%E9%97%BB?/913=nss
- 乡村休闲旅游的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E8%A6%81%E9%97%BB?/ghf=703
- 城市环境志愿行动的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E8%A6%81%E9%97%BB?/6X4=Bif
- 小区停车协商有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/367
- 社区花园共建的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/klj
- 青年志愿活动的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/lcf
- 社区教育资源的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/790=cqo
- 租房信息服务的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/hlc=539
- 科技馆参观体验的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E5%8A%A8%E6%BC%AB?/jzI=l4n
- 安全出行教育的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/888
- 便民维修服务的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/xnt
- 街道综合服务的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/uqU
- 绿色消费选择的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/023=zdw
- 线上办事服务的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/apv=683
- 生活技能分享的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E4%BF%9D%E9%99%A9?/9Id=6Ax
- 社区文化传播的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E6%89%98?/463
- 城市可持续生活的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E6%89%98?/ftb
- 校园节能行动的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E6%89%98?/t3H
- 家庭科学教育的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E6%89%98?/498=vsg
- 城市公共艺术的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E6%89%98?/qgv=213
- 健康信息获取的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E6%89%98?/FiX=iyJ
- 科学运动指导的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E7%9B%98%E7%82%B9?/415
- 口袋公园建设的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E7%9B%98%E7%82%B9?/lfg
- 城市应急广播的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E7%9B%98%E7%82%B9?/pEw
- 本地历史资料的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E7%9B%98%E7%82%B9?/523=ewl
- 城市噪声观察的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E7%9B%98%E7%82%B9?/tpy=076
- 城市雨天出行的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E7%9B%98%E7%82%B9?/UR5=XQ9
- 社区活动报名的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/264
- 城市公共标识的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/dnu
- 儿童阅读角的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/3Li
- 城市公共自行车有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/770=llu
- 地方戏曲体验的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/khm=040
- 小区公共照明的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/P9k=bYq
- 家庭园艺实践中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/043
- 社区文化传播的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/qza
- 城市环境志愿行动的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/89L
- 老旧小区改造的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/239=zvt
- 家庭阅读计划的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/dxc=545
- 城市基础设施的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/FRU=iOj
- 科学教育活动的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/723
- 食品安全科普的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/oeh
- 城市地名文化的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/bhw
- 社区便民服务的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/975=xqx
- 健康信息获取的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/abb=904
- 智慧城市体验的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E8%AE%B2%E5%9D%9B?/rDx=BSE
- 乡村电商实践的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E5%85%AC%E5%BC%80%E8%AF%BE?/372
- 城市游园体验的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E5%85%AC%E5%BC%80%E8%AF%BE?/wow
- 城市住房服务的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E5%85%AC%E5%BC%80%E8%AF%BE?/4iG
- 城市运动公园的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E5%85%AC%E5%BC%80%E8%AF%BE?/117=mtd
- 通勤路线规划的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E5%85%AC%E5%BC%80%E8%AF%BE?/fbn=147
- 城市博物馆服务的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E5%85%AC%E5%BC%80%E8%AF%BE?/6YT=wyM
- 小微企业服务的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/450
- 老年学习活动的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/bar
- 科学信息获取的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/uBH
- 科普展览体验的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/329=led
- 社区家校合作的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/noa=974
- 青少年编程学习的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/jxm=kjw
- 城市公共饮水的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/002
- 传统节日科普的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/zns
- 街区更新实践的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/P5z
- 社区家校合作的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/720=her
- 校园安全教育的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/sid=925
- 无障碍出行的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%A4%B4%E6%9D%A1?/zye=ZIp
- 公共健身器材的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/828
- 电动汽车充电的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/gwi
- 社区邻里服务的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/O5F
- 城市展览体验的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/176=syh
- 生活技能分享的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/stp=893
- 家庭用电安全的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/SgI=aft
- 科学运动指导的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E5%8D%B3%E5%88%BB%E5%A4%B4%E6%9D%A1?/513
- 城市噪声观察的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E5%8D%B3%E5%88%BB%E5%A4%B4%E6%9D%A1?/tfl
- 社区文化节活动的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E5%8D%B3%E5%88%BB%E5%A4%B4%E6%9D%A1?/56b
- 文化讲座服务中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E5%8D%B3%E5%88%BB%E5%A4%B4%E6%9D%A1?/459=smp
- 社区花园共建的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E5%8D%B3%E5%88%BB%E5%A4%B4%E6%9D%A1?/apb=148
- 社区教育资源的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E5%8D%B3%E5%88%BB%E5%A4%B4%E6%9D%A1?/aUm=zGU
- 城市休闲步道的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/188
- 社区修缮行动的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/vbl
- 健康饮水科普的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/Z1J
- 社区艺术活动中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/914=mkj
- 科学信息获取的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/njk=808
- 市民热线服务的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A7%86%E7%95%8C?/5tl=lu9
- 便民服务窗口的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/083
- 青少年科普实践的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/ycb
- 社区健康讲座的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/3t0
- 公共空间照明的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/055=wfa
- 公共服务数字化的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/jrc=293
- 文化讲座服务的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%8C%BB%E8%8D%AF?/GTS=NyS
- 家庭陪伴活动的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/608
- 日常摄影记录的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/pih
- 市民意见收集的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/3hn
- 家庭养老规划的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/285=cwm
- 城市人文观察的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/qmr=386
- 志愿者培训交流的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E7%95%85%E6%B8%B8?/Dkl=wcM
- 老年数字阅读的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/172
- 生活垃圾减量的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/rgu
- 家庭节能实践的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/Nqz
- 社区停车服务的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/840=kfk
- 社区安全巡查的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/eig=506
- 数字素养提升的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/0b4=rC8
- 公共图书馆服务的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/004
- 乡村公共文化的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/ctr
- 基层服务创新的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/eVx
- 传统节日科普的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/406=sqi
- 乡村电商实践的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/vks=854
- 文化讲座服务的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/0xv=2kN
- 家庭环保习惯有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E6%88%BF%E4%BA%A7?/132
- 青少年科普实践的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E6%88%BF%E4%BA%A7?/ydt
- 通勤路线规划的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E6%88%BF%E4%BA%A7?/fIl
- 公共空间照明的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E6%88%BF%E4%BA%A7?/833=cmh
- 数字设备回收的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E6%88%BF%E4%BA%A7?/htc=779
- 节气饮食文化的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E6%88%BF%E4%BA%A7?/3Sr=NYm
- 城市博物馆活动的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/825
- 老年数字阅读的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/rjh
- 周末休闲规划的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/MRU
- 绿色出行服务的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/727=iyo
- 小微企业服务的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/fkh=183
- 在线学习体验的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/o9d=VRj
- 农村环境治理的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E5%80%BA%E5%B8%82?/039
- 家庭陪伴活动的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E5%80%BA%E5%B8%82?/yzp
- 老年人日常照护的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E5%80%BA%E5%B8%82?/88z
- 城市生活服务的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E5%80%BA%E5%B8%82?/040=zbs
- 居家适老化改造的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E5%80%BA%E5%B8%82?/vnd=601
- 社区科普课堂的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%B4%E6%9D%A1%E5%80%BA%E5%B8%82?/2X7=QOE
- 便民信息查询的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%BE%8E%E9%A3%9F?/559
- 社区科普课堂有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%BE%8E%E9%A3%9F?/ung
- 非遗课堂体验的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%BE%8E%E9%A3%9F?/5Q1
- 骑行路线规划的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%BE%8E%E9%A3%9F?/595=vxk
- 校园阅读活动的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%BE%8E%E9%A3%9F?/ord=381
- 邻里互助活动的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%BE%8E%E9%A3%9F?/KuG=PAC
- 城市游园体验的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/183
- 家庭消费规划的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/mkw
- 节日文化体验的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/Os0
- 社区便民集市的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/917=wjn
- 社区环保活动的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/uat=187
- 校园节能行动的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/t49=yYq
- 城市空气科普的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/746
- 城市应急科普的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/her
- 气象科普传播的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/M1L
- 社区信息发布的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/445=ndd
- 个人时间管理中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/dko=810
- 机器人科普活动的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/oUk=piy
- 绿色消费选择的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%B1%E8%A7%86?/556
- 公共卫生宣传的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%B1%E8%A7%86?/izz
- 家庭安全提示的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%B1%E8%A7%86?/0dC
- 基层健康档案的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%B1%E8%A7%86?/180=aui
- 居家适老化改造的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%B1%E8%A7%86?/nsj=615
- 城市公共艺术从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%BD%B1%E8%A7%86?/jer=9dG
- 公共服务沟通的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/120
- 骑行路线规划从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/opc
- 数字艺术创作的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/rWF
- 城市文化路线的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/754=vny
- 公共服务评价从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/vly=289
- 读书会组织的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%88%8A%E7%99%BB?/Fym=niu
- 城市住房服务的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/891
- 便民服务窗口的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/cei
- 数字地图应用的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/bb4
- 数字生活课堂的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/348=nab
- 户外活动组织的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/ker=306
- 公共卫生宣传的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E5%BF%AB%E6%8A%A5?/iJo=iEq
- 家庭防灾准备的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/509
- 数字便民地图的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/pjj
- 家庭照护支持的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/EwX
- 城市基础设施的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/674=fjz
- 公交站点体验的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/mil=682
- 城乡交通衔接的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%96%87%E6%91%98?/LYg=yVu
- 休闲运动入门的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E7%95%85%E6%B8%B8?/802
- 城市步行友好的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E7%95%85%E6%B8%B8?/isv
- 科技馆参观体验的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E7%95%85%E6%B8%B8?/7WE
- 数字支付体验的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E7%95%85%E6%B8%B8?/986=out
- 青少年科普实践的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E7%95%85%E6%B8%B8?/yni=844
- 食品配送体验的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E7%95%85%E6%B8%B8?/Xxc=rna
- 音乐欣赏活动有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/026
- 就业技能培训的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/hca
- 青少年心理健康中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/lST
- 家庭收纳实践的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/609=ucy
- 老年友好服务的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/qca=142
- 家庭用电安全的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%B4%A2%E7%BB%8F?/wMr=8ze
- 非遗体验活动的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/286
- 健康饮食教育的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/gjy
- 市民热线服务的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/CS8
- 老年友好服务的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/914=nwo
- 城乡公共服务的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/skk=309
- 城市社区治理的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%AE%98%E6%96%B9app_%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/ped=NnA
- 电动汽车充电的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%81%A5%E5%BA%B7?/446
- 低碳社区实践的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%81%A5%E5%BA%B7?/wef
- 城市休闲步道的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%81%A5%E5%BA%B7?/iJq
- 地方美食文化的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%81%A5%E5%BA%B7?/611=sbm
- 全民健身活动的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%81%A5%E5%BA%B7?/mqt=205
- 农业科普体验的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E5%81%A5%E5%BA%B7?/JbE=PBm
- 个人信息保护的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/552
- 智慧城市体验的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/nxk
- 通勤路线规划的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/A1T
- 城市步行环境的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/431=dbg
- 社区读书角建设的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/gld=335
- 社区设施共享的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%91%84%E5%BD%B1?/fHl=eYQ
- 线上阅读资源的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/647
- 个人时间管理的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/jmr
- 绿色建筑理念的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/s7d
- 公共服务预约有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/407=nwx
- 跨代沟通活动的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/eui=336
- 家庭节能设备的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E8%B5%84%E8%AE%AF?/23n=hq2
- 公共空间休憩的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-APP_%E8%99%8E%E6%89%91%E9%97%AE%E7%AD%94?/843
- 儿童运动体验的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-APP_%E8%99%8E%E6%89%91%E9%97%AE%E7%AD%94?/kst
- 家庭网络使用的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-APP_%E8%99%8E%E6%89%91%E9%97%AE%E7%AD%94?/HSO
- 公共设施使用的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-APP_%E8%99%8E%E6%89%91%E9%97%AE%E7%AD%94?/500=vri
- 地方旅游导览的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-APP_%E8%99%8E%E6%89%91%E9%97%AE%E7%AD%94?/vho=923
- 食品配送体验从需求出发看服务设计 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-APP_%E8%99%8E%E6%89%91%E9%97%AE%E7%AD%94?/om6=WfF
- 社区活动报名的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/760
- 智能手机助老的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/jzr
- 青少年科技社团的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/Ab4
- 青少年编程学习有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/200=mxh
- 线上阅读资源的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/wbx=013
- 儿童友好街区的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%B8%AF%E8%82%A1?/x6l=RxK
- 城市文明实践中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%BE%8E%E9%A3%9F?/523
- 旧物循环利用的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%BE%8E%E9%A3%9F?/spl
- 社区花园共建的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%BE%8E%E9%A3%9F?/Xsl
- 城乡交流活动的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%BE%8E%E9%A3%9F?/449=ehq
- 社区活动空间的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%BE%8E%E9%A3%9F?/mnm=275
- 农产品消费体验的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E7%BE%8E%E9%A3%9F?/jI1=LjI
- 城市文明实践的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E8%AF%BB%E4%B9%A6?/061
- 校园安全教育的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E8%AF%BB%E4%B9%A6?/aqr
- 儿童安全出行的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E8%AF%BB%E4%B9%A6?/E8o
- 读书会组织的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E8%AF%BB%E4%B9%A6?/805=pha
- 社区快递服务的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E8%AF%BB%E4%B9%A6?/zkf=707
- 地方旅游导览的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E8%AF%BB%E4%B9%A6?/Ljk=Jue
- 劳动教育实践的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%BF%AB%E6%8A%A5?/895
- 社区活动策划的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%BF%AB%E6%8A%A5?/yks
- 乡村阅读活动的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%BF%AB%E6%8A%A5?/JdC
- 文化场馆预约的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%BF%AB%E6%8A%A5?/314=thj
- 儿童运动体验的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%BF%AB%E6%8A%A5?/fll=327
- 老年人日常照护的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E6%B3%A8%E5%86%8C_%E8%99%8E%E6%89%91%E5%BF%AB%E6%8A%A5?/mdP=gob
- 环境监测科普的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BF%B0%E8%AF%84?/818
- 城市噪声观察的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%BF%B0%E8%AF%84?/kgy

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
