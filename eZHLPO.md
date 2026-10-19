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

- 城市适老服务的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E4%BC%97-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%A6%81%E9%97%BB?/ekl=799
- 全民健身活动的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E4%BC%97-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%A6%81%E9%97%BB?/4VB=sty
- 社区防暑服务的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E6%9C%AD%E8%AE%B0?/017
- 节能生活方式的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E6%9C%AD%E8%AE%B0?/ldm
- 青少年心理健康的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E6%9C%AD%E8%AE%B0?/eqP
- 社区体育组织的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E6%9C%AD%E8%AE%B0?/706=loa
- 公园无障碍服务的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E6%9C%AD%E8%AE%B0?/fww=337
- 社区慢性病防控的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E6%9C%AD%E8%AE%B0?/Iv5=W6G
- 电子商务服务的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%BF%AB%E6%8A%A5?/578
- 社区共享书架的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%BF%AB%E6%8A%A5?/jix
- 家庭理财科普的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%BF%AB%E6%8A%A5?/WOG
- 公共交通信息服务的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%BF%AB%E6%8A%A5?/121=mtz
- 城乡交流活动的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%BF%AB%E6%8A%A5?/ajx=709
- 物业服务沟通的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%BF%AB%E6%8A%A5?/hMm=Bgw
- 街区道路维护的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/274
- 社区修缮行动的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/hox
- 电动汽车充电的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/ny6
- 城市应急广播的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/221=pfc
- 城市夜间生活的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/equ=781
- 乡村公共服务的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/d2Q=tLa
- 公共服务沟通的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E4%BC%97-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/648
- 城市慢跑路线的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E4%BC%97-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/kij
- 城市文明出行的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E4%BC%97-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/IT8
- 城市公共自行车的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E4%BC%97-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/607=czc
- 基层健康服务的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E4%BC%97-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/wbd=845
- 智能手机助老的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%A4%A7%E4%BC%97-%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%9C%B0%E6%96%B9?/pu8=dVX
- 社区便民集市的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E4%BC%97-APP_%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/692
- 新能源知识普及的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E4%BC%97-APP_%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/xzq
- 公共健身器材的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E4%BC%97-APP_%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/BjL
- 社区宠物管理的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E4%BC%97-APP_%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/059=whr
- 机器学习入门的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E4%BC%97-APP_%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/ltl=449
- 青少年科普实践的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E4%BC%97-APP_%E5%87%A4%E5%87%B0%E8%A6%81%E9%97%BB?/NOL=ebP
- 绿色快递包装的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/834
- 公共交通接驳的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/zzs
- 地方美食文化的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/sNe
- 租房信息服务的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/358=zij
- 城市步行友好的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/sie=000
- 乡村教育资源的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E7%A8%8E%E5%8A%A1?/YLl=rs6
- 便民服务窗口的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%BC%97-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/982
- 社区便民服务的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%BC%97-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/fky
- 健康信息获取的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%BC%97-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/rq6
- 科技馆参观体验的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%BC%97-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/005=jkd
- 城市公共标识的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%BC%97-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/twh=104
- 图书馆亲子空间的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%BC%97-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%9F%BA%E9%87%91?/KQf=81K
- 城市应急广播的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/433
- 环境教育课程的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/cnk
- 乡村教育资源的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/vhh
- 智慧停车服务的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/685=vsd
- 公共文化活动的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/wna=198
- 线上办事服务的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/TQQ=jGG
- 乡村生活观察的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E4%BC%97-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%AD%E8%89%BA?/504
- 社区绿色空间的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E4%BC%97-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%AD%E8%89%BA?/qqc
- 基层服务创新的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E4%BC%97-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%AD%E8%89%BA?/ljA
- 城市博物馆活动的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E4%BC%97-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%AD%E8%89%BA?/388=acu
- 家庭用电安全的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E4%BC%97-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%AD%E8%89%BA?/fgl=411
- 健康饮水科普的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%A4%A7%E4%BC%97-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%AD%E8%89%BA?/viW=n8A
- 城市公共自行车的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E4%BC%97-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/061
- 家庭陪伴活动的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E4%BC%97-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/pgk
- 数字艺术创作的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E4%BC%97-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/Gsh
- 公交无障碍服务的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E4%BC%97-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/232=jhc
- 社区教育资源的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E4%BC%97-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/wuw=074
- 公共空间安全的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%A4%A7%E4%BC%97-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/N22=PvS
- 智能家居应用的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E4%BC%97-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/007
- 社区安全巡查的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E4%BC%97-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/xxb
- 社区活动空间的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E4%BC%97-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/5KL
- 文明养宠科普的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E4%BC%97-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/541=qlo
- 乡村生态观察的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E4%BC%97-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/zec=705
- 家庭健康科普的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E4%BC%97-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9B%9B%E7%91%9E%E8%B4%A2%E7%BB%8F?/L42=GlK
- 网络安全教育的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E4%BC%97-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/940
- 无障碍信息设计的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E4%BC%97-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/gcq
- 数据分析入门的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E4%BC%97-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/vvs
- 数字资源检索的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E4%BC%97-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/896=kvq
- 城市公共空间的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E4%BC%97-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/dcx=224
- 全民健身活动的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%A4%A7%E4%BC%97-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%85%9A%E5%BB%BA?/IW7=Viy
- 社会体育指导的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E4%BC%97-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E6%B1%87%E5%B8%82?/578
- 生活垃圾回收的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E4%BC%97-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E6%B1%87%E5%B8%82?/cgh
- 乡村阅读空间的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E4%BC%97-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E6%B1%87%E5%B8%82?/fdO
- 周末休闲规划的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E4%BC%97-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E6%B1%87%E5%B8%82?/650=may
- 生活服务数字化的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E4%BC%97-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E6%B1%87%E5%B8%82?/dlk=476
- 公园休闲体验的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%A4%A7%E4%BC%97-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%95%8C%E9%9D%A2%E6%B1%87%E5%B8%82?/BkO=X37
- 公共交通信息服务的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/470
- 社区协商议事的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/ljq
- 电子商务服务的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/Xlp
- 校园阅读活动的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/249=lye
- 信息无障碍体验的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/lbh=398
- 租房信息服务的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%BC%97-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E5%85%AC%E5%BC%80%E8%AF%BE?/tS7=yF6
- 消防知识宣传的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%88%8A%E7%99%BB?/785
- 城市适老服务的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%88%8A%E7%99%BB?/xab
- 公园无障碍服务的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%88%8A%E7%99%BB?/aJg
- 社区文化节活动的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%88%8A%E7%99%BB?/197=uwd
- 街区小店体验中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%88%8A%E7%99%BB?/vac=842
- 医院导诊服务的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E5%88%8A%E7%99%BB?/8Ll=dQh
- 老年人出行服务的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E9%80%9A%E4%BF%A1?/105
- 文化场馆预约的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E9%80%9A%E4%BF%A1?/kxn
- 家庭园艺实践的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E9%80%9A%E4%BF%A1?/90B
- 乡村电商实践的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E9%80%9A%E4%BF%A1?/034=otn
- 绿色快递包装有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E9%80%9A%E4%BF%A1?/gmm=948
- 公园亲子设施的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E9%80%9A%E4%BF%A1?/i54=rgL
- 网络信息辨识的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/143
- 家庭理财科普的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/mdr
- 公共服务数字化的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/yDc
- 公交无障碍服务的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/001=izt
- 劳动教育实践的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/cqv=240
- 小微企业服务的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%A5%E6%8A%A5?/owY=32B
- 城市建设科普的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/400
- 生活垃圾回收的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/dkn
- 青年志愿活动的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/6ql
- 社区商业活力的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/516=gms
- 城市生活服务的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/srk=518
- 零废弃生活尝试的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/ssK=p48
- 社区宠物管理的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/567
- 街区小店体验的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/arc
- 文明养宠科普的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/S6A
- 职业技能学习的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/431=tbd
- 节气饮食文化的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/nju=150
- 物业服务沟通的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/Hyc=mPw
- 社区宣传栏更新的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/079
- 开放数据应用的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/ejl
- 电动汽车充电的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/MEA
- 乡村生态旅游的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/307=zty
- 家庭养老规划的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/uah=232
- 图书馆数字服务的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%91%84%E5%BD%B1?/4hM=YNX
- 科学运动指导的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%92%AD%E6%8A%A5?/518
- 老年人文化生活的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%92%AD%E6%8A%A5?/jxr
- 社区体育组织中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%92%AD%E6%8A%A5?/iRp
- 公园无障碍服务的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%92%AD%E6%8A%A5?/700=kfi
- 居民健康教育的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%92%AD%E6%8A%A5?/jvo=827
- 乡村电商实践的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%92%AD%E6%8A%A5?/Lry=BoK
- 地方美食文化的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/782
- 社区老年食堂的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/eqc
- 消防知识宣传的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/dA5
- 公共空间导览的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/528=lxc
- 老年人文化生活的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/lqq=519
- 家庭收纳实践中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/pEN=Aui
- 家庭消费规划的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%8D%9A%E5%AE%A2?/538
- 户外活动组织的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%8D%9A%E5%AE%A2?/ibu
- 安全出行教育的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%8D%9A%E5%AE%A2?/CAO
- 科学健身方法有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%8D%9A%E5%AE%A2?/746=cee
- 老年数字阅读的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%8D%9A%E5%AE%A2?/apm=448
- 节假日出行安排的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%8D%9A%E5%AE%A2?/FGL=3Hx
- 城市绿道建设的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/968
- 节能生活方式的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/bct
- 城市噪声观察的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/ESA
- 灵活就业交流的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/620=oqu
- 社区艺术活动的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/smh=727
- 社区心理支持的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E6%94%BF%E5%8D%8F?/fQC=H2P
- 社区设施共享的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%A8%B1%E4%B9%90?/533
- 社区读书角建设的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%A8%B1%E4%B9%90?/fvh
- 农村环境治理的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%A8%B1%E4%B9%90?/ezW
- 社区托育服务的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%A8%B1%E4%B9%90?/927=hjk
- 便民维修服务的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%A8%B1%E4%B9%90?/fxk=940
- 社区健康讲座的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E5%A8%B1%E4%B9%90?/ZIr=ph8
- 城市夜间生活的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%81%8C%E5%9C%BA?/168
- 电子商务服务的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%81%8C%E5%9C%BA?/qyk
- 家庭用电安全的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%81%8C%E5%9C%BA?/3aq
- 街头绿植养护的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%81%8C%E5%9C%BA?/925=zbn
- 绿色出行服务的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%81%8C%E5%9C%BA?/ssk=555
- 老年人日常照护的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%81%8C%E5%9C%BA?/8qQ=FCW
- 城市生活服务的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA?/505
- 基层健康档案的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA?/lsf
- 家庭陪伴活动的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA?/hEr
- 乡村阅读空间的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA?/036=duh
- 乡村产业科普有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA?/pcc=748
- 家庭环保习惯的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA?/psS=P7f
- 城乡交流活动的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/278
- 儿童户外活动中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/fph
- 公交站点体验的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/OHs
- 便民服务地图的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/107=gyl
- 社区活动空间的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/wno=670
- 地方美食文化的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%9B%9E%E6%9C%9B?/CQh=t5I
- 青年职业探索的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E5%BA%B7?/804
- 节假日出行安排的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E5%BA%B7?/phu
- 急救知识普及的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E5%BA%B7?/qpN
- 社区生活指南的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E5%BA%B7?/595=tvs
- 家庭急救准备的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E5%BA%B7?/nkl=004
- 医院导诊服务的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E5%BA%B7?/AiR=axk
- 居民健康教育的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/176
- 城市文明出行的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/jxx
- 城市文化路线的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/Zge
- 城市共享单车的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/214=mmc
- 农产品品牌传播的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/aka=945
- 社区环保活动的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%B3%95%E6%B2%BB?/vl7=L8e
- 旧物循环利用的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E8%A7%A3%E5%AF%86?/497
- 公共服务评价的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E8%A7%A3%E5%AF%86?/jdt
- 家庭志愿活动的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E8%A7%A3%E5%AF%86?/XTc
- 节气饮食文化的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E8%A7%A3%E5%AF%86?/835=kpx
- 食品配送体验中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E8%A7%A3%E5%AF%86?/mdy=294
- 乡村公共服务中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%87%A4%E5%87%B0%E8%A7%A3%E5%AF%86?/k9s=PQ5
- 公共设施使用的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/896
- 乡村休闲旅游的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/qry
- 通勤路线规划的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/7y9
- 数字资源检索的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/066=snc
- 家庭运动计划的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/ccp=879
- 网络安全教育的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E8%AF%86_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/ZCE=J8n
- 社区文化传播的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%9C%9B?/927
- 乡村休闲旅游的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%9C%9B?/wjh
- 家庭志愿活动的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%9C%9B?/cNC
- 农产品品牌传播的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%9C%9B?/719=wlh
- 节约用水实践的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%9C%9B?/eoc=977
- 文化遗产保护科普的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%9E%E6%9C%9B?/8gj=gwd
- 公共空间导览的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%96%B0%E9%97%BB?/639
- 环境教育课程的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%96%B0%E9%97%BB?/ewz
- 社区故事采集的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%96%B0%E9%97%BB?/RRL
- 科学观察活动的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%96%B0%E9%97%BB?/979=est
- 社区防暑服务从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%96%B0%E9%97%BB?/osv=741
- 生活垃圾回收的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%96%B0%E9%97%BB?/cBq=7QN
- 家庭健康科普的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/427
- 公共交通信息服务的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/kof
- 数字支付体验的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/GMw
- 开放式学习空间从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/923=byy
- 城市建设科普的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/cuu=125
- 城市公共艺术的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%97%85%E6%B8%B8?/2dl=f16
- 智能家居应用的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E5%9B%9E%E6%94%BE?/925
- 在线学习体验的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E5%9B%9E%E6%94%BE?/tiz
- 城市公共空间的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E5%9B%9E%E6%94%BE?/Y0O
- 数字公共文化的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E5%9B%9E%E6%94%BE?/228=anf
- 城市宠物友好空间的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E5%9B%9E%E6%94%BE?/kww=785
- 绿色快递包装的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E5%9B%9E%E6%94%BE?/HgL=PND
- 便民服务窗口的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/068
- 城乡交流活动的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/xbn
- 城市适老服务的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/Xmj
- 公共卫生设施的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/878=uns
- 家庭环保行动的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/gil=568
- 安全出行教育的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/avy=PnJ
- 非遗课堂体验的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/368
- 传统节日科普的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/juu
- 儿童阅读角的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/fAl
- 青少年户外教育的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/843=kfl
- 城乡公共服务的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/dtv=670
- 城市博物馆服务的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%AF%BB%E4%B9%A6?/X4E=Yfq
- 居家适老化改造的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/241
- 儿童友好空间的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/yef
- 社区垃圾回收的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/Ky0
- 小区停车协商的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/833=hah
- 光伏知识科普的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/icy=102
- 社区家政服务有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/uDU=DBg
- 食品安全科普的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E8%A7%A3%E5%AF%86?/815
- 气象科普传播的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E8%A7%A3%E5%AF%86?/stz
- 老年运动活动的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E8%A7%A3%E5%AF%86?/DmQ
- 乡村生态观察的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E8%A7%A3%E5%AF%86?/935=cwr
- 健康饮水科普的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E8%A7%A3%E5%AF%86?/wnm=383
- 个人时间管理的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%8A%96%E9%9F%B3%E8%A7%A3%E5%AF%86?/ss9=88c
- 线上阅读资源的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/967
- 生活技能分享的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/scw
- 个人数据管理的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/dVi
- 农村环境治理中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/343=vsr
- 新能源知识普及中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/gbp=732
- 公共服务咨询的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%9C%9F%E8%B4%A7?/DIx=Gzg
- 图书馆活动策划中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E4%BA%BA%E7%89%A9?/862
- 学校体育活动的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E4%BA%BA%E7%89%A9?/row

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
