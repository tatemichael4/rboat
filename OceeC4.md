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

- 网络信息辨识中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/xof=607
- 城市适老服务的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%B6%88%E8%B4%B9?/n9c=IZX
- 城市步行友好的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%9A%E5%BB%BA?/401
- 社会体育指导的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%9A%E5%BB%BA?/dvy
- 公共空间休憩的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%9A%E5%BB%BA?/xzk
- 网络信息辨识的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%9A%E5%BB%BA?/047=ihn
- 城市基础设施的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%9A%E5%BB%BA?/hgr=375
- 儿童户外活动从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%85%9A%E5%BB%BA?/Udx=QPb
- 社区快递服务的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8D%8F?/609
- 便民维修服务的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8D%8F?/rwe
- 家庭科学教育的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8D%8F?/eVF
- 无障碍信息设计的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8D%8F?/081=ycv
- 数字便民地图的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8D%8F?/srj=121
- 节日文化体验的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8D%8F?/nhI=GLm
- 就业技能培训的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%AE%89%E9%98%B2?/254
- 城市公共标识的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%AE%89%E9%98%B2?/zfw
- 乡村休闲旅游的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%AE%89%E9%98%B2?/bPf
- 社区运动空间的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%AE%89%E9%98%B2?/548=nki
- 音乐欣赏活动的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%AE%89%E9%98%B2?/iqv=988
- 数字公共文化的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E5%AE%89%E9%98%B2?/LWa=bWw
- 食品配送体验的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/781
- 医院导诊服务的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/xex
- 家庭阅读计划的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/4vd
- 居民健康教育的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/492=weq
- 健康步道使用的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/twe=809
- 数字艺术创作的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/tgE=fXv
- 在线学习体验的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/069
- 社会体育指导的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/qox
- 社区设施共享的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/f9F
- 无障碍出行的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/103=dri
- 公共交通信息服务的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/sgw=993
- 老旧小区改造的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%AF%8D%E5%A9%B4?/cD2=RP6
- 公共图书馆服务的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E5%9C%B0%E4%BA%A7?/345
- 公共场所导视的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E5%9C%B0%E4%BA%A7?/maw
- 数字资源检索的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E5%9C%B0%E4%BA%A7?/6Rc
- 城市树木认养的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E5%9C%B0%E4%BA%A7?/783=iug
- 绿色校园实践有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E5%9C%B0%E4%BA%A7?/acv=119
- 老年数字阅读的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB%E5%9C%B0%E4%BA%A7?/JoT=90h
- 城市公共空间的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E5%8E%BF%E5%9F%9F?/570
- 乡村公共阅读的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E5%8E%BF%E5%9F%9F?/zga
- 消防知识宣传的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E5%8E%BF%E5%9F%9F?/ETt
- 全民健身活动的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E5%8E%BF%E5%9F%9F?/255=hhw
- 电动汽车充电的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E5%8E%BF%E5%9F%9F?/gnt=764
- 城市生活记录的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E5%8E%BF%E5%9F%9F?/CyE=gl6
- 社区共享书架的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/930
- 校园阅读活动的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/trz
- 个人时间管理的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/Xrs
- 社会体育指导的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/395=tzs
- 公园休闲体验的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/adl=851
- 数字支付体验的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/bCg=9vx
- 儿童运动体验从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/601
- 青少年科普实践的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/ikv
- 开源技术交流的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/uYE
- 急救知识普及的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/769=gxo
- 灵活就业交流的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/rcl=355
- 无障碍信息设计的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/0ei=PIT
- 城市雨天出行的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/042
- 社区宠物管理中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/pra
- 智能手机助老从需求出发看服务设计 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/PJW
- 科普展览体验的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/083=uex
- 数字便民地图的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/kgt=370
- 城市树木认养的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E7%AD%94?/fXb=VtV
- 城市慢行系统的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/918
- 城乡公共服务的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/dib
- 公益活动组织的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/yrZ
- 全民阅读推广的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/838=idn
- 社区交通安全的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/dck=076
- 城市建设科普的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/Zbm=zlB
- 农村环境治理的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/475
- 健康饮食教育的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/sud
- 社区休闲设施的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/BzQ
- 公园无障碍服务的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/739=cna
- 文化讲座服务中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/ofj=450
- 城市建设科普的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E8%81%8C%E5%9C%BA?/mwK=9Mj
- 农业科普体验的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%B9%B6%E8%B4%AD?/864
- 社区科普课堂的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%B9%B6%E8%B4%AD?/pyq
- 数字生活课堂的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%B9%B6%E8%B4%AD?/fyo
- 公共设施使用的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%B9%B6%E8%B4%AD?/011=shl
- 家庭饮食安排的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%B9%B6%E8%B4%AD?/obp=271
- 小区电梯维护的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%B9%B6%E8%B4%AD?/Yoj=JAE
- 数字便民地图从需求出发看服务设计 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/272
- 在线教育体验的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/wlt
- 老年人文化生活的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/dtX
- 街道综合服务的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/286=vsy
- 智能手机助老的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/wuf=860
- 非遗课堂体验的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/W3B=M0I
- 社区故事采集的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%82%A1%E7%A5%A8?/270
- 文明养宠科普的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%82%A1%E7%A5%A8?/vit
- 社区便利生活从需求出发看服务设计 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%82%A1%E7%A5%A8?/PJO
- 智能家居应用中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%82%A1%E7%A5%A8?/570=bke
- 数字设备回收从需求出发看服务设计 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%82%A1%E7%A5%A8?/crz=506
- 社区菜市场服务的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%82%A1%E7%A5%A8?/v3x=xrJ
- 智慧城市体验中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/002
- 城市建设科普的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/gbz
- 社区读书角建设的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/HHf
- 社区活动空间从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/714=ovu
- 街区绿化养护的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/egc=672
- 社区信息发布的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/06Q=MYr
- 家庭阅读计划的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/895
- 社区环保活动的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/bxl
- 家庭健康管理的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/gPZ
- 公共交通信息服务的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/962=zbm
- 图书借阅体验的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/hjx=327
- 数字生活课堂的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/nf4=QBz
- 节能生活方式的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/786
- 地方美食文化的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/yio
- 智能家居应用的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/NpP
- 科学健身方法的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/258=fof
- 周末休闲规划的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/tjh=929
- 地方民俗记录的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/Oa9=XZy
- 社区老年食堂的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E4%B8%93%E9%A2%98?/494
- 科学信息获取有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E4%B8%93%E9%A2%98?/ttu
- 户外活动组织的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E4%B8%93%E9%A2%98?/Ci6
- 科学运动指导的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E4%B8%93%E9%A2%98?/095=tht
- 社区消防演练的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E4%B8%93%E9%A2%98?/ozu=195
- 节能家电使用中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E9%9B%85%E8%99%8E%E4%B8%93%E9%A2%98?/lxP=c7M
- 学校体育活动的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%BB%8F%E6%B5%8E?/103
- 校园节能行动的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%BB%8F%E6%B5%8E?/hga
- 公共空间照明的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%BB%8F%E6%B5%8E?/ITY
- 本地消费场景的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%BB%8F%E6%B5%8E?/890=zyk
- 社区垃圾回收的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%BB%8F%E6%B5%8E?/rxt=905
- 公共服务指南的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E7%BB%8F%E6%B5%8E?/90O=Hja
- 社区志愿服务的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/498
- 青年就业服务的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/nzk
- 数字设备回收的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/tcs
- 急救知识普及的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/845=odu
- 城市共享单车的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/syb=328
- 数字设备回收的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E5%A8%B1%E4%B9%90?/x8P=GNJ
- 生活垃圾减量的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%A1%8C%E6%83%85?/174
- 乡村文化活动的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%A1%8C%E6%83%85?/qlp
- 运动安全知识的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%A1%8C%E6%83%85?/WXi
- 城市慢跑路线的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%A1%8C%E6%83%85?/797=zea
- 城市游园体验的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%A1%8C%E6%83%85?/fae=533
- 城市博物馆活动的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%A1%8C%E6%83%85?/a8O=6Vc
- 社区活动空间的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-APP_%E5%87%A4%E5%87%B0%E6%92%AD%E6%8A%A5?/289
- 运动安全知识中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-APP_%E5%87%A4%E5%87%B0%E6%92%AD%E6%8A%A5?/gcu
- 机器学习入门的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-APP_%E5%87%A4%E5%87%B0%E6%92%AD%E6%8A%A5?/GBp
- 图书借阅体验的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-APP_%E5%87%A4%E5%87%B0%E6%92%AD%E6%8A%A5?/132=jgo
- 无障碍出行的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-APP_%E5%87%A4%E5%87%B0%E6%92%AD%E6%8A%A5?/jeu=998
- 公交无障碍服务的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-APP_%E5%87%A4%E5%87%B0%E6%92%AD%E6%8A%A5?/t5D=5cY
- 社区防暑服务的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E4%BA%A7?/163
- 数字资源检索的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E4%BA%A7?/gaq
- 社区老年食堂的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E4%BA%A7?/IKr
- 基层服务创新的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E4%BA%A7?/358=aix
- 数字创作工具的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E4%BA%A7?/mqz=976
- 创业经验分享的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9C%B0%E4%BA%A7?/FY3=skr
- 城市生活记录的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/528
- 社区慢性病防控的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/fzw
- 零废弃生活尝试的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/mnQ
- 社区共享书架的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/511=xgv
- 家庭节能设备的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/gzy=017
- 全民阅读推广的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E5%9B%AD%E8%89%BA?/HQP=TbC
- 乡村阅读活动的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/693
- 城市雨天出行的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/xec
- 社区志愿服务的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/kMT
- 城市树木认养的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/732=dmt
- 无障碍出行的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/trm=268
- 食品安全科普的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E5%85%9A%E5%BB%BA?/MhX=DVU
- 乡村公共文化的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/956
- 便民信息查询的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/ogs
- 基层服务创新的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/Y2M
- 数字生活课堂的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/501=ooz
- 城市生活服务的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/xcj=871
- 消防知识宣传的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/8Re=3Y4
- 家庭运动计划的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/273
- 数字设备回收有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/pvy
- 公交站点体验的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/qPm
- 青年志愿活动的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/252=bnm
- 远程协作工具的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/qnq=324
- 农产品品牌传播中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E5%80%BA%E5%B8%82?/obe=HhB
- 科学观察活动的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E6%95%B0%E8%AF%BB?/755
- 社区体育组织的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E6%95%B0%E8%AF%BB?/jqk
- 药品使用科普的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E6%95%B0%E8%AF%BB?/W16
- 口袋公园建设的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E6%95%B0%E8%AF%BB?/172=psh
- 电动汽车充电的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E6%95%B0%E8%AF%BB?/dok=020
- 乡村文化空间的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%99%BE%E5%BA%A6%E6%95%B0%E8%AF%BB?/zbC=dIJ
- 公共文化活动的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/360
- 小区公共照明的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/lvq
- 音乐欣赏活动的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/90T
- 地方文化传播的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/638=mcj
- 公共场馆服务从需求出发看服务设计 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/nrr=498
- 社区公共卫生的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%81%A5%E8%BA%AB?/m2W=Jxh
- 科学信息获取的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E8%A7%86%E9%A2%91?/146
- 青年志愿活动的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E8%A7%86%E9%A2%91?/gad
- 社区艺术活动的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E8%A7%86%E9%A2%91?/vc8
- 家庭科学教育的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E8%A7%86%E9%A2%91?/939=joz
- 创业经验分享的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E8%A7%86%E9%A2%91?/jpl=437
- 社区快递服务从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%9B%85%E8%99%8E%E8%A7%86%E9%A2%91?/ISS=kZ4
- 青年职业探索的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/292
- 城市休闲步道的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/gdw
- 社区宣传栏更新的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/Ay2
- 老年人日常照护的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/056=fbs
- 基层医疗预约的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/jff=457
- 社区法律科普的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/g2a=CtL
- 绿色办公实践的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%B1%BD%E8%BD%A6?/502
- 开源技术交流的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%B1%BD%E8%BD%A6?/dfg
- 个人信息保护的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%B1%BD%E8%BD%A6?/LV9
- 社区垃圾分类的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%B1%BD%E8%BD%A6?/082=ytb
- 社区文化传播的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%B1%BD%E8%BD%A6?/jis=013
- 城市骑行环境的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9_%E8%8A%92%E6%9E%9C%E6%B1%BD%E8%BD%A6?/5jh=RHd
- 食品安全科普的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/905
- 家庭养老规划的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/mmy
- 乡村休闲旅游的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/4R5
- 公共健身器材的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/620=inr
- 终身学习资源的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/azb=200
- 家庭科学教育的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/XaO=Upi
- 乡村生活观察的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/374
- 低碳社区实践的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/uxn
- 社区家校合作的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/Is5
- 数字生活课堂的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/999=cvd
- 文化遗产保护科普的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/kdd=627
- 全民阅读推广的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-welcome%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E5%81%A5%E8%BA%AB?/TIW=H5M
- 绿色建筑理念的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA?/447
- 城市宠物友好空间的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA?/les
- 便民信息查询的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA?/bWX
- 公共服务评价的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA?/585=euy
- 绿色生活实践的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA?/qjp=741
- 公交站点体验的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA?/hT5=pMI
- 公共文化活动中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/173
- 本地消费场景的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/szz
- 开放式学习空间的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/uka
- 乡村阅读活动的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/836=hxh
- 邻里互助活动的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/ttb=455
- 急救知识普及的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/2S9=Ba9
- 乡村公共阅读的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/564
- 科学信息获取的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/bag
- 垃圾分类指导中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/pVD
- 社区便民服务的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/830=mpy
- 文明养宠科普的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/xlg=612
- 城市博物馆服务的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/M3U=oLC
- 城市运动公园的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/584
- 社区设施共享有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/ofw
- 社区法律科普的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/fLI
- 公共交通接驳的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/095=cps
- 社区垃圾分类有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/dua=494
- 线上办事服务的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E7%99%BB%E5%BD%95welcome_%E5%8F%91%E5%B1%95%E8%B4%A2%E7%BB%8F?/7KM=js7
- 应急物资管理的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/529
- 节假日出行安排的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/bnh
- 骑行路线规划的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/0ur
- 终身学习资源的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/943=ecg
- 通勤路线规划的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/vws=491
- 绿色出行服务的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E6%B3%95%E5%BE%8B?/MMl=Hqu
- 社区法律科普的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/238
- 城市文明出行的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/rrm
- 便民服务窗口的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/7ge
- 老年智能设备的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/963=inz
- 社区家校合作的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/bxk=412
- 社区教育资源的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/Jco=DDm
- 社区便民服务的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%A5%BC%E5%B8%82?/721
- 小微企业服务的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%A5%BC%E5%B8%82?/izt

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
