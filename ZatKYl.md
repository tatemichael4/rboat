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

- 便民服务窗口的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E7%BE%8E%E9%A3%9F?/afn=882
- 新能源知识普及的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E7%BE%8E%E9%A3%9F?/xmA=mwx
- 社区设施共享有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/485
- 乡村文化空间的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/xxl
- 乡村生活观察的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/Fgz
- 网络信息辨识的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/169=azd
- 亲子科普活动的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/dqh=888
- 便民服务窗口有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E5%88%9B%E4%B8%9A%E8%B4%A2%E7%BB%8F?/hVn=dHf
- 绿色快递包装的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E4%BD%93%E8%82%B2?/008
- 公共文化活动的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E4%BD%93%E8%82%B2?/mbc
- 地方民俗记录的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E4%BD%93%E8%82%B2?/P2K
- 环境教育课程的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E4%BD%93%E8%82%B2?/656=rqf
- 运动安全知识的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E4%BD%93%E8%82%B2?/sxl=961
- 户外活动组织的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E4%BD%93%E8%82%B2?/7tw=bPV
- 应急物资管理的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%96%87%E6%91%98?/053
- 社区健康讲座的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%96%87%E6%91%98?/vib
- 社区教育资源的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%96%87%E6%91%98?/uCa
- 户外活动组织的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%96%87%E6%91%98?/601=nnd
- 公共文化活动的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%96%87%E6%91%98?/nqb=618
- 读书会组织的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%96%87%E6%91%98?/0u2=j9s
- 农业科普体验的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/604
- 文明养宠科普的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/oil
- 公共设施使用的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/lpN
- 基层健康档案的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/427=zvy
- 环境监测科普的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/wgx=409
- 课后服务体验的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F?/KfJ=EdK
- 公共卫生设施的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8A%A1?/597
- 非遗课堂体验的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8A%A1?/auz
- 小微企业服务的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8A%A1?/FvN
- 光伏知识科普的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8A%A1?/413=nak
- 城市公共饮水的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8A%A1?/rzd=237
- 社区运动空间的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8A%A1?/WfY=BVS
- 灵活就业交流的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%AE%A0%E7%89%A9?/005
- 本地旅行体验的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%AE%A0%E7%89%A9?/gaa
- 青少年编程学习有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%AE%A0%E7%89%A9?/eOE
- 图书借阅体验的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%AE%A0%E7%89%A9?/776=cze
- 公益活动组织的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%AE%A0%E7%89%A9?/vpb=783
- 乡村阅读空间的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%AE%A0%E7%89%A9?/RFT=pIk
- 亲子科普活动的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%9F%8E%E4%BA%8B?/700
- 城市绿色交通的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%9F%8E%E4%BA%8B?/esa
- 家庭收纳实践的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%9F%8E%E4%BA%8B?/04f
- 街区绿化养护的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%9F%8E%E4%BA%8B?/591=qrs
- 公园亲子设施的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%9F%8E%E4%BA%8B?/yna=114
- 社区运动空间的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E5%9F%8E%E4%BA%8B?/9yV=ELk
- 基层健康服务有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AF%84?/988
- 数字政务体验的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AF%84?/pgt
- 口袋公园建设的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AF%84?/lzs
- 非遗体验活动的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AF%84?/664=vhh
- 本地消费场景的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AF%84?/vkt=443
- 青少年科技社团从需求出发看服务设计 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E6%97%B6%E8%AF%84?/56y=yEX
- 社区文化节活动的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E5%88%B8%E5%95%86?/802
- 社区垃圾分类的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E5%88%B8%E5%95%86?/ink
- 文化讲座服务的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E5%88%B8%E5%95%86?/I1w
- 社区活动空间的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E5%88%B8%E5%95%86?/128=unn
- 社区艺术活动的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E5%88%B8%E5%95%86?/lje=720
- 青年职业探索的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E5%88%B8%E5%95%86?/Wth=lVn
- 家庭网络使用的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E7%BD%91_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/589
- 科学教育活动的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E7%BD%91_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/cxe
- 个人数据管理的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E7%BD%91_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/Uup
- 老年人文化生活中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E7%BD%91_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/023=ybv
- 公共图书馆服务的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E7%BD%91_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/ijg=669
- 社区文化节活动的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E7%BD%91_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/PAN=ig3
- 急救知识普及的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/813
- 城市生活服务的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/itj
- 街区更新实践的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/Yo5
- 在线教育体验的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/040=lbx
- 基层医疗预约的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/tnp=815
- 城市公共厕所的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%95%B0%E7%A0%81?/jpX=qfu
- 家庭节能设备的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%8D%9A%E5%AE%A2?/053
- 租房信息服务的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%8D%9A%E5%AE%A2?/aep
- 零废弃生活尝试的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%8D%9A%E5%AE%A2?/Z4H
- 乡村生活观察的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%8D%9A%E5%AE%A2?/921=ztu
- 老旧小区改造的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%8D%9A%E5%AE%A2?/gom=163
- 乡村教育资源的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%8D%9A%E5%AE%A2?/L6t=sVC
- 老年数字阅读的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-APP_%E5%93%94%E5%93%A9%E7%A4%BE%E8%AE%BA?/632
- 公共服务沟通的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-APP_%E5%93%94%E5%93%A9%E7%A4%BE%E8%AE%BA?/mir
- 城市噪声观察的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-APP_%E5%93%94%E5%93%A9%E7%A4%BE%E8%AE%BA?/6h7
- 科学睡眠习惯的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-APP_%E5%93%94%E5%93%A9%E7%A4%BE%E8%AE%BA?/567=qxu
- 社区菜市场服务的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-APP_%E5%93%94%E5%93%A9%E7%A4%BE%E8%AE%BA?/mej=800
- 城市骑行环境的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-APP_%E5%93%94%E5%93%A9%E7%A4%BE%E8%AE%BA?/K7X=teB
- 基层健康档案的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%88%8A%E7%99%BB?/421
- 老年运动活动的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%88%8A%E7%99%BB?/wdo
- 社区老年食堂有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%88%8A%E7%99%BB?/beG
- 小区停车协商的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%88%8A%E7%99%BB?/453=uqk
- 药品使用科普的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%88%8A%E7%99%BB?/ovm=205
- 非遗体验活动的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E5%88%8A%E7%99%BB?/ibO=GVe
- 青少年编程学习的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E4%B8%93%E6%A0%8F?/173
- 社区知识分享的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E4%B8%93%E6%A0%8F?/coj
- 社区公共餐饮的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E4%B8%93%E6%A0%8F?/1si
- 青年就业服务的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E4%B8%93%E6%A0%8F?/937=lmg
- 健康信息获取的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E4%B8%93%E6%A0%8F?/ygv=307
- 生活服务数字化的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E4%B8%93%E6%A0%8F?/oRT=neT
- 家庭用电安全的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_360%E5%88%8A%E7%99%BB?/148
- 社区科普课堂的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_360%E5%88%8A%E7%99%BB?/ewz
- 街区小店体验的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_360%E5%88%8A%E7%99%BB?/amg
- 城市文化路线的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_360%E5%88%8A%E7%99%BB?/250=mhe
- 节假日出行安排中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_360%E5%88%8A%E7%99%BB?/dil=366
- 社区快递服务的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E7%99%BB%E5%BD%95_360%E5%88%8A%E7%99%BB?/4zt=n4q
- 社区公共议事的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E6%B3%A8%E5%86%8C_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/555
- 公共图书馆服务的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E6%B3%A8%E5%86%8C_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/icy
- 全民健身活动的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E6%B3%A8%E5%86%8C_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/s8X
- 文化场馆预约的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E6%B3%A8%E5%86%8C_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/347=kqb
- 地方美食文化的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E6%B3%A8%E5%86%8C_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/nmf=523
- 个人数据管理的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E6%B3%A8%E5%86%8C_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/QWP=vbC
- 公共空间安全的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%88%9B%E6%8A%95?/553
- 街区更新实践的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%88%9B%E6%8A%95?/hfp
- 生活服务数字化的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%88%9B%E6%8A%95?/gsx
- 垃圾分类指导的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%88%9B%E6%8A%95?/484=ttw
- 儿童运动体验的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%88%9B%E6%8A%95?/asn=514
- 儿童户外活动的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%9F%A5%E4%B9%8E%E5%88%9B%E6%8A%95?/Tow=OEs
- 旧物循环利用的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E7%9B%98%E7%82%B9?/446
- 环境教育课程的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E7%9B%98%E7%82%B9?/ngm
- 公共空间照明的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E7%9B%98%E7%82%B9?/HMe
- 乡村公共阅读的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E7%9B%98%E7%82%B9?/897=cgy
- 科学睡眠习惯的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E7%9B%98%E7%82%B9?/xru=812
- 传统节日科普的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E7%9B%98%E7%82%B9?/9sc=FFJ
- 便民服务地图的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%83%AD%E6%A6%9C?/928
- 城市绿道建设的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%83%AD%E6%A6%9C?/gdr
- 家庭急救准备的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%83%AD%E6%A6%9C?/QOe
- 基层服务创新的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%83%AD%E6%A6%9C?/736=kll
- 社区交通安全的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%83%AD%E6%A6%9C?/blq=062
- 通勤路线规划的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%83%AD%E6%A6%9C?/cQ9=xjq
- 老年智能设备的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/567
- 乡村公共文化的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/xmc
- 乡村阅读空间的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/fws
- 社区科普课堂的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/045=hlz
- 周末休闲规划的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/cvm=954
- 家庭健康科普的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/478=WYz
- 家庭饮食安排的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%BD%B1%E8%A7%86?/882
- 家庭运动计划的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%BD%B1%E8%A7%86?/huy
- 城市游园体验的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%BD%B1%E8%A7%86?/7fI
- 老年智能设备有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%BD%B1%E8%A7%86?/888=axh
- 家庭陪伴活动的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%BD%B1%E8%A7%86?/pxz=819
- 科学教育活动的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E5%BD%B1%E8%A7%86?/ooC=3u8
- 生活技能分享的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/293
- 图书馆活动策划的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/vei
- 城乡公共服务的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/9iz
- 公共服务指南的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/554=gbk
- 城乡交通衔接的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/bsq=597
- 社区法律科普的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E6%98%9F%E5%BA%A7?/YJS=LOs
- 药品使用科普的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%91%8A?/996
- 社区邻里服务的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%91%8A?/rod
- 城市公共艺术的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%91%8A?/1xF
- 城市应急科普的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%91%8A?/485=uxs
- 科普展览体验的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%91%8A?/fxn=856
- 社会体育指导的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%91%8A?/INe=Var
- 基层健康档案的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/069
- 家庭养老规划的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/ttg
- 家庭消费规划的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/l7u
- 青少年科技社团的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/066=oyc
- 社区法律科普的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/scu=013
- 青年就业服务的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/dA5=qfT
- 街区小店体验中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/493
- 网络安全教育的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/zyk
- 城市公共标识的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/M7u
- 数字课堂应用中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/814=fgh
- 城市空气科普的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/zsj=857
- 终身学习资源的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/KXf=X57
- 城市步行友好的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%9F%BA%E9%87%91?/959
- 家庭急救准备的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%9F%BA%E9%87%91?/pmd
- 数字学习资源的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%9F%BA%E9%87%91?/01B
- 老年数字阅读的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%9F%BA%E9%87%91?/683=roe
- 青少年职业启蒙的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%9F%BA%E9%87%91?/uil=206
- 农产品品牌传播有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E5%9F%BA%E9%87%91?/wke=19H
- 智能家居应用的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%8D%E9%A5%B0?/123
- 文化讲座服务的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%8D%E9%A5%B0?/suz
- 基层健康档案的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%8D%E9%A5%B0?/oGQ
- 社区设施共享的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%8D%E9%A5%B0?/390=uvt
- 城市宠物友好空间的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%8D%E9%A5%B0?/juu=556
- 城市文明出行的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%8D%E9%A5%B0?/8wH=s0Z
- 线上办事服务的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E7%90%86%E8%B4%A2?/910
- 气象科普传播的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E7%90%86%E8%B4%A2?/vdm
- 乡村文化空间中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E7%90%86%E8%B4%A2?/KO5
- 地方文化传播的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E7%90%86%E8%B4%A2?/427=zzj
- 社区宠物管理的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E7%90%86%E8%B4%A2?/rlj=677
- 社区学习活动的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E7%90%86%E8%B4%A2?/BMo=mQf
- 社区应急准备的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/070
- 地方文化传播的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/bfx
- 个人数据管理的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/jn5
- 公共空间导览的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/259=vol
- 健康饮食教育的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/wov=423
- 信息无障碍体验的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/PTU=Re4
- 家庭理财科普的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%AE%BF?/440
- 社区学习活动的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%AE%BF?/euc
- 科学运动指导的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%AE%BF?/dY0
- 城市公共饮水中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%AE%BF?/459=bdu
- 老年人出行服务的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%AE%BF?/hde=080
- 科学教育活动的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%AE%BF?/VfO=sHZ
- 家庭健康管理的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/528
- 社区设施共享的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/vrw
- 青少年职业启蒙的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/XWL
- 乡村休闲旅游的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/943=mrt
- 青年志愿活动的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/fhf=823
- 家庭志愿活动的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E7%A4%BE%E5%8C%BA?/hxP=r6Z
- 城市步行友好的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/717
- 全民健身活动的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/kld
- 社区共享书架的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/s0J
- 社区生活指南的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/037=qqk
- 城市建设科普的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/ffu=440
- 城市博物馆服务的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E9%80%9F%E8%A7%88?/iYY=pYx
- 社会体育指导的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%8C%BB%E8%8D%AF?/917
- 公共交通信息服务的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%8C%BB%E8%8D%AF?/nzg
- 数字支付体验的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%8C%BB%E8%8D%AF?/KCA
- 智能手机助老的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%8C%BB%E8%8D%AF?/749=uiu
- 数字资源检索的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%8C%BB%E8%8D%AF?/bjq=236
- 家庭收纳实践的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%8C%BB%E8%8D%AF?/2XW=juU
- 城市公共艺术的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-APP_%E8%99%8E%E6%89%91%E4%BC%97%E6%B5%8B?/078
- 社区科普课堂的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-APP_%E8%99%8E%E6%89%91%E4%BC%97%E6%B5%8B?/yrl
- 城市雨天出行的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-APP_%E8%99%8E%E6%89%91%E4%BC%97%E6%B5%8B?/GFA
- 科学教育活动有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-APP_%E8%99%8E%E6%89%91%E4%BC%97%E6%B5%8B?/138=dnp
- 智能手机助老的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-APP_%E8%99%8E%E6%89%91%E4%BC%97%E6%B5%8B?/sag=021
- 就业技能培训的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-APP_%E8%99%8E%E6%89%91%E4%BC%97%E6%B5%8B?/TLi=EXP
- 乡村公共文化从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/962
- 城市博物馆服务的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/rgz
- 无障碍出行的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/p17
- 新能源知识普及的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/128=zzw
- 邻里共享空间的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/hve=888
- 数字资源检索的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/cDO=gXo
- 城市公共自行车的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/763
- 儿童运动体验的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/icw
- 传统节日科普的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/vtP
- 街区道路维护的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/234=jyx
- 城市休闲步道的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/sge=319
- 无障碍出行的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/UVC=1wE
- 绿色出行服务的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/506
- 健康信息获取的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/aqk
- 数字资源检索从需求出发看服务设计 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/q9V
- 城市博物馆活动的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/662=fca
- 全民阅读推广的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/kja=786
- 公共卫生设施从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/lLG=EY2
- 公园亲子设施的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/189
- 校园节能行动的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/olh
- 社区花园共建的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/qc2
- 终身学习资源的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/142=gib
- 社区健康讲座的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/rxw=444
- 职业技能学习的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/W4x=saY
- 家庭志愿活动的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8A%A1?/051
- 无障碍出行的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8A%A1?/nvb
- 公共空间安全的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8A%A1?/wbk
- 社区宠物管理的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8A%A1?/803=icg
- 无障碍出行从需求出发看服务设计 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8A%A1?/lky=482
- 社区宠物管理的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%94%BF%E5%8A%A1?/Gy3=0Mq
- 课后服务体验的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/011
- 新能源出行从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/egv
- 图书馆亲子空间的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/Gv3
- 基层服务创新的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/793=zsf
- 家庭用电安全的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/ler=506
- 电子商务服务从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/oka=lJf
- 绿色快递包装的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%9C%8D%E9%A5%B0?/046
- 社区公共卫生的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%9B%86%E5%9B%A2-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%9C%8D%E9%A5%B0?/ypa

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
