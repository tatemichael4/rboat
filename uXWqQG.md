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

- 图书馆亲子空间的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E5%BF%AB%E9%80%9F%E5%9B%9E%E6%9C%AC_%E8%8A%92%E6%9E%9C%E7%9B%98%E7%82%B9?/yoS
- 便民信息查询的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E5%BF%AB%E9%80%9F%E5%9B%9E%E6%9C%AC_%E8%8A%92%E6%9E%9C%E7%9B%98%E7%82%B9?/469=jvv
- 街区小店体验的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E5%BF%AB%E9%80%9F%E5%9B%9E%E6%9C%AC_%E8%8A%92%E6%9E%9C%E7%9B%98%E7%82%B9?/cwo=855
- 数字课堂应用的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E4%B8%80%E5%AF%B9%E4%B8%80%E5%B8%A6%E5%BF%AB%E9%80%9F%E5%9B%9E%E6%9C%AC_%E8%8A%92%E6%9E%9C%E7%9B%98%E7%82%B9?/WqT=SjE
- 城市公共自行车的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E7%9A%84%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%88%8A%E7%99%BB?/663
- 新能源知识普及的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E7%9A%84%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%88%8A%E7%99%BB?/tob
- 乡村生活观察的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E7%9A%84%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%88%8A%E7%99%BB?/UDb
- 家庭节能设备的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E7%9A%84%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%88%8A%E7%99%BB?/896=exg
- 公共服务预约有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E7%9A%84%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%88%8A%E7%99%BB?/dus=177
- 社区休闲设施的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E7%9A%84%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E5%88%8A%E7%99%BB?/BOe=ApE
- 数字政务体验的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/439
- 旧物循环利用的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/gfi
- 社区活动策划的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/2qa
- 文化遗产保护科普的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/338=bqh
- 城市环境志愿行动的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/tyo=392
- 急救知识普及的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%94_%E8%87%AA%E8%B4%B8%E8%B4%A2%E7%BB%8F?/oLE=nZs
- 邻里互助活动的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%93%94%E5%93%A9%E5%86%9C%E4%B8%9A?/072
- 志愿者培训交流的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%93%94%E5%93%A9%E5%86%9C%E4%B8%9A?/yia
- 消防知识宣传的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%93%94%E5%93%A9%E5%86%9C%E4%B8%9A?/Fve
- 城市社区治理的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%93%94%E5%93%A9%E5%86%9C%E4%B8%9A?/232=utt
- 电子商务服务的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%93%94%E5%93%A9%E5%86%9C%E4%B8%9A?/nvq=616
- 社区故事采集的协作机制梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%93%94%E5%93%A9%E5%86%9C%E4%B8%9A?/6tc=yuW
- 小区电梯维护的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A8%BF?/840
- 绿色出行服务的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A8%BF?/nci
- 城市步行友好有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A8%BF?/lZr
- 非遗课堂体验的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A8%BF?/039=jrn
- 社区垃圾分类的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A8%BF?/mut=373
- 本地消费场景的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A8%BF?/IPy=xde
- 市民意见收集的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%8F%B0%E5%AD%90_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/033
- 软件开发学习的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%8F%B0%E5%AD%90_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/xlf
- 社区宠物管理的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%8F%B0%E5%AD%90_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/Fiv
- 社区互助网络的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%8F%B0%E5%AD%90_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/688=xew
- 数字设备回收中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%8F%B0%E5%AD%90_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/jrz=201
- 社区修缮行动从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E5%AE%9A%E7%9A%84%E5%8F%B0%E5%AD%90_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/nDR=wqc
- 地方戏曲体验的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E7%99%BE%E5%BA%A6%E5%9C%B0%E6%96%B9?/368
- 城市公共空间的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E7%99%BE%E5%BA%A6%E5%9C%B0%E6%96%B9?/pfc
- 健康信息获取的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E7%99%BE%E5%BA%A6%E5%9C%B0%E6%96%B9?/LzF
- 地方戏曲体验的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E7%99%BE%E5%BA%A6%E5%9C%B0%E6%96%B9?/648=yun
- 公共服务评价的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E7%99%BE%E5%BA%A6%E5%9C%B0%E6%96%B9?/vtb=305
- 公园休闲体验的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E7%99%BE%E5%BA%A6%E5%9C%B0%E6%96%B9?/frr=UcQ
- 社区手工活动的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%80%BA%E5%B8%82?/026
- 智慧停车服务的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%80%BA%E5%B8%82?/gcc
- 城市应急科普的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%80%BA%E5%B8%82?/Lnc
- 城市地名文化有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%80%BA%E5%B8%82?/232=lze
- 节日文化体验的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%80%BA%E5%B8%82?/prf=207
- 社区垃圾回收的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%80%E7%A8%B3%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E5%80%BA%E5%B8%82?/RrD=okz
- 老年学习活动的空间设计要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%8F%91%E8%B5%B0%E5%8A%BF%E5%91%A2_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/608
- 家庭理财科普的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%8F%91%E8%B5%B0%E5%8A%BF%E5%91%A2_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/sut
- 数字支付体验的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%8F%91%E8%B5%B0%E5%8A%BF%E5%91%A2_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/TJ5
- 绿色出行服务的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%8F%91%E8%B5%B0%E5%8A%BF%E5%91%A2_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/526=qhu
- 城市农夫市集的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%8F%91%E8%B5%B0%E5%8A%BF%E5%91%A2_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/wde=747
- 生活技能分享的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%A6%82%E4%BD%95%E7%9C%8B%E5%A4%A7%E5%8F%91%E8%B5%B0%E5%8A%BF%E5%91%A2_%E8%99%8E%E6%89%91%E6%94%BF%E7%AD%96?/7Dt=6bg
- 校园节能行动的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%80%E5%85%B1%E6%9C%89%E5%A4%9A%E5%B0%91%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%95%8A_%E9%BC%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/795
- 零废弃生活尝试的协作机制梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%80%E5%85%B1%E6%9C%89%E5%A4%9A%E5%B0%91%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%95%8A_%E9%BC%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/eep
- 食品安全科普的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%80%E5%85%B1%E6%9C%89%E5%A4%9A%E5%B0%91%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%95%8A_%E9%BC%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/lXO
- 儿童阅读角的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%80%E5%85%B1%E6%9C%89%E5%A4%9A%E5%B0%91%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%95%8A_%E9%BC%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/192=zly
- 公交无障碍服务的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%80%E5%85%B1%E6%9C%89%E5%A4%9A%E5%B0%91%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%95%8A_%E9%BC%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/yru=489
- 低碳社区实践的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%80%E5%85%B1%E6%9C%89%E5%A4%9A%E5%B0%91%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E5%95%8A_%E9%BC%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/SLM=F9k
- 公共空间休憩的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%A4%9A%E5%B0%91%E4%B8%AA_%E5%BF%85%E5%BA%94%E7%88%86%E6%96%99?/421
- 社区便民集市的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%A4%9A%E5%B0%91%E4%B8%AA_%E5%BF%85%E5%BA%94%E7%88%86%E6%96%99?/jei
- 公园无障碍服务的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%A4%9A%E5%B0%91%E4%B8%AA_%E5%BF%85%E5%BA%94%E7%88%86%E6%96%99?/86X
- 公共服务指南的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%A4%9A%E5%B0%91%E4%B8%AA_%E5%BF%85%E5%BA%94%E7%88%86%E6%96%99?/718=iyz
- 非遗课堂体验的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%A4%9A%E5%B0%91%E4%B8%AA_%E5%BF%85%E5%BA%94%E7%88%86%E6%96%99?/xvt=376
- 开放式学习空间的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%A4%9A%E5%B0%91%E4%B8%AA_%E5%BF%85%E5%BA%94%E7%88%86%E6%96%99?/Ppf=V6t
- 地方旅游导览的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%B0%B8%E8%BF%9C%E4%B8%8D%E4%BC%9A%E8%BE%93%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/443
- 远程协作工具的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%B0%B8%E8%BF%9C%E4%B8%8D%E4%BC%9A%E8%BE%93%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/ywa
- 乡村阅读活动的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%B0%B8%E8%BF%9C%E4%B8%8D%E4%BC%9A%E8%BE%93%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/ti7
- 社区环保活动的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%B0%B8%E8%BF%9C%E4%B8%8D%E4%BC%9A%E8%BE%93%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/075=age
- 应急物资管理的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%B0%B8%E8%BF%9C%E4%B8%8D%E4%BC%9A%E8%BE%93%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/rek=918
- 课后服务体验的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%B0%B8%E8%BF%9C%E4%B8%8D%E4%BC%9A%E8%BE%93%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E4%BA%B2%E5%AD%90?/yLk=U12
- 城乡公共服务的协作机制梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E9%AB%98%E7%BA%A7%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%9C%BA%E5%88%B6_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/058
- 健康信息获取的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E9%AB%98%E7%BA%A7%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%9C%BA%E5%88%B6_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/kpn
- 家庭志愿活动的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E9%AB%98%E7%BA%A7%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%9C%BA%E5%88%B6_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/5PY
- 家庭用电安全的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E9%AB%98%E7%BA%A7%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%9C%BA%E5%88%B6_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/061=iee
- 休闲运动入门的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E9%AB%98%E7%BA%A7%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%9C%BA%E5%88%B6_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/jkq=924
- 学校体育活动的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E9%AB%98%E7%BA%A7%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E6%9C%BA%E5%88%B6_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/Oqe=HiB
- 街区道路维护的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%B8%B8%E6%88%8F%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84%E5%95%8A_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/272
- 地方民俗记录的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%B8%B8%E6%88%8F%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84%E5%95%8A_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/lcu
- 街区更新实践的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%B8%B8%E6%88%8F%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84%E5%95%8A_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/h9N
- 城市应急广播的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%B8%B8%E6%88%8F%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84%E5%95%8A_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/276=jhv
- 数字支付体验的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%B8%B8%E6%88%8F%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84%E5%95%8A_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/ceg=688
- 社区家校合作的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E6%B8%B8%E6%88%8F%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84%E5%95%8A_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AF%84?/szz=O49
- 社区艺术活动的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/328
- 校园社团活动的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/kgo
- 社区便利生活的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/vBh
- 家庭健康科普的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/911=iej
- 城市社区治理的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/hvd=433
- 传统节日科普的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81%E5%A4%A7%E5%85%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/c6T=thB
- 小微企业服务的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E6%9C%80%E6%96%B0%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E8%81%8C%E5%9C%BA?/460
- 公共卫生宣传的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E6%9C%80%E6%96%B0%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E8%81%8C%E5%9C%BA?/wsn
- 网络信息辨识的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E6%9C%80%E6%96%B0%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E8%81%8C%E5%9C%BA?/KUn
- 小区停车协商的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E6%9C%80%E6%96%B0%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E8%81%8C%E5%9C%BA?/911=zvi
- 基层健康档案的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E6%9C%80%E6%96%B0%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E8%81%8C%E5%9C%BA?/mpm=640
- 家庭养老规划的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E6%9C%80%E6%96%B0%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E8%81%8C%E5%9C%BA?/XYM=9gU
- 社区设施共享有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%86%9B%E4%BA%8B?/464
- 社区活动空间中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%86%9B%E4%BA%8B?/wrn
- 地方旅游导览的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%86%9B%E4%BA%8B?/JWL
- 生活垃圾减量的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%86%9B%E4%BA%8B?/731=ght
- 线上阅读资源的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%86%9B%E4%BA%8B?/moa=127
- 城乡交流活动的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8D%95%E5%B0%8F%E5%8F%8C%E6%AD%A3%E8%A7%84%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E5%86%9B%E4%BA%8B?/2Uw=4Tf
- 家庭食品保存的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/204
- 城市步行友好的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/ebi
- 家庭收纳实践的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/Ru7
- 社区便利生活的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/533=ijb
- 线上办事服务的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/hxv=453
- 家庭环保习惯的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E4%BF%A1%E8%AA%89%E6%9C%80%E5%A5%BD%E7%9A%84_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/ivW=eBa
- 小区电梯维护的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E7%82%89_%E8%85%BE%E8%AE%AF%E6%A5%BC%E5%B8%82?/692
- 安全出行教育的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E7%82%89_%E8%85%BE%E8%AE%AF%E6%A5%BC%E5%B8%82?/oji
- 青年职业探索的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E7%82%89_%E8%85%BE%E8%AE%AF%E6%A5%BC%E5%B8%82?/eyE
- 社区慢性病防控的资源整合思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E7%82%89_%E8%85%BE%E8%AE%AF%E6%A5%BC%E5%B8%82?/423=soy
- 地方旅游导览的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E7%82%89_%E8%85%BE%E8%AE%AF%E6%A5%BC%E5%B8%82?/npq=121
- 城市公共标识的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E9%9D%A0%E8%B0%B1%E5%B9%B3%C2%B7%E5%8F%B0%E5%87%BA%E7%82%89_%E8%85%BE%E8%AE%AF%E6%A5%BC%E5%B8%82?/ypb=HyA
- 街区小店体验的资源整合思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/573
- 乡村教育资源的服务细节记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/sej
- 社区庭院绿化的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/uUp
- 公益活动组织的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/757=kax
- 基层服务创新的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/saj=867
- 公交无障碍服务的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/GKw=9Pu
- 传统手工艺体验的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/644
- 社区科普课堂的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/jax
- 乡村休闲旅游的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/uaN
- 环境监测科普的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/556=jir
- 地方美食文化的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/xbb=287
- 线上阅读资源的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/qs8=oCq
- 校园节能行动的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/883
- 老年人文化生活的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/jim
- 社区交通安全的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/hdl
- 创业经验分享的空间设计要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/394=auj
- 社区生活指南的资源整合思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/gja=313
- 农村环境治理的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E6%97%A5%E6%8A%A5?/jY1=ahu
- 城市生活服务的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E5%BF%AB%E6%89%8B%E7%A4%BE%E5%8C%BA?/244
- 社区垃圾分类的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E5%BF%AB%E6%89%8B%E7%A4%BE%E5%8C%BA?/jeg
- 公共设施使用的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E5%BF%AB%E6%89%8B%E7%A4%BE%E5%8C%BA?/Ahg
- 公共服务数字化的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E5%BF%AB%E6%89%8B%E7%A4%BE%E5%8C%BA?/110=gfs
- 智能手机助老的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E5%BF%AB%E6%89%8B%E7%A4%BE%E5%8C%BA?/rkk=566
- 数字档案服务从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F_%E5%BF%AB%E6%89%8B%E7%A4%BE%E5%8C%BA?/61P=7K2
- 健康信息获取的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E6%8E%A2%E5%BA%97?/907
- 小区电梯维护的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E6%8E%A2%E5%BA%97?/svs
- 社区菜市场服务从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E6%8E%A2%E5%BA%97?/Jsh
- 绿色消费选择的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E6%8E%A2%E5%BA%97?/223=mxq
- 城市文化路线的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E6%8E%A2%E5%BA%97?/zus=585
- 城乡公共服务有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E5%BF%85%E5%BA%94%E6%8E%A2%E5%BA%97?/9Vc=v3d
- 家庭收纳实践的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88_36%E6%B0%AA%E6%96%87%E5%8C%96?/590
- 数字设备回收的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88_36%E6%B0%AA%E6%96%87%E5%8C%96?/bfq
- 社区活动策划的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88_36%E6%B0%AA%E6%96%87%E5%8C%96?/NUn
- 机器人科普活动的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88_36%E6%B0%AA%E6%96%87%E5%8C%96?/460=seh
- 学校食育活动的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88_36%E6%B0%AA%E6%96%87%E5%8C%96?/zha=510
- 地方民俗记录的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E6%9C%80%E7%A8%B3%E8%AE%A1%E5%88%92%E6%98%AF%E4%BB%80%E4%B9%88_36%E6%B0%AA%E6%96%87%E5%8C%96?/gCr=ljN
- 数字创意课程的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/508
- 公共空间休憩的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/kww
- 志愿者培训交流的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/WsS
- 邻里互助活动的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/080=okc
- 科普展览体验的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/rey=245
- 城市游园体验的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E5%AF%BC%E5%B8%88%E5%9B%A2%E9%98%9F%E8%AE%A1%E5%88%92_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/7Xr=bj2
- 乡村公共服务的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%90%A7_%E6%90%9C%E7%8B%97%E5%88%9B%E6%8A%95?/866
- 非遗课堂体验的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%90%A7_%E6%90%9C%E7%8B%97%E5%88%9B%E6%8A%95?/beo
- 公共服务预约的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%90%A7_%E6%90%9C%E7%8B%97%E5%88%9B%E6%8A%95?/4UE
- 绿色生活实践的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%90%A7_%E6%90%9C%E7%8B%97%E5%88%9B%E6%8A%95?/624=nje
- 社区公共议事从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%90%A7_%E6%90%9C%E7%8B%97%E5%88%9B%E6%8A%95?/dsq=428
- 家庭运动计划的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E5%90%A7_%E6%90%9C%E7%8B%97%E5%88%9B%E6%8A%95?/Ync=GfH
- 家庭用电安全的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9Fapp_%E6%BE%8E%E6%B9%83%E6%B0%91%E7%94%9F?/444
- 社区文化节活动的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9Fapp_%E6%BE%8E%E6%B9%83%E6%B0%91%E7%94%9F?/yii
- 数字设备回收的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9Fapp_%E6%BE%8E%E6%B9%83%E6%B0%91%E7%94%9F?/5K3
- 口袋公园建设的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9Fapp_%E6%BE%8E%E6%B9%83%E6%B0%91%E7%94%9F?/646=cfx
- 数字生活课堂的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9Fapp_%E6%BE%8E%E6%B9%83%E6%B0%91%E7%94%9F?/khq=794
- 城市微更新实践的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9Fapp_%E6%BE%8E%E6%B9%83%E6%B0%91%E7%94%9F?/cbV=CvQ
- 城市噪声观察的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/062
- 便民服务地图的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/ulu
- 城市文明出行的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/LcG
- 城市可持续生活的协作机制梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/760=kyu
- 基层服务创新的空间设计要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/dgq=791
- 节日文化体验从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81%E6%80%8E%E4%B9%88%E5%A1%AB_%E7%99%BE%E5%BA%A6%E5%88%B8%E5%95%86?/tsZ=CGl
- 全民阅读推广的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E9%A1%BA%E4%B8%B0%E5%BD%A9%E7%A5%A8?/350
- 职业技能学习有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E9%A1%BA%E4%B8%B0%E5%BD%A9%E7%A5%A8?/kpp
- 个人信息保护从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E9%A1%BA%E4%B8%B0%E5%BD%A9%E7%A5%A8?/5TZ
- 远程协作工具的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E9%A1%BA%E4%B8%B0%E5%BD%A9%E7%A5%A8?/260=gdv
- 数字档案服务有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E9%A1%BA%E4%B8%B0%E5%BD%A9%E7%A5%A8?/apc=059
- 智能手机助老的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%81_%E9%A1%BA%E4%B8%B0%E5%BD%A9%E7%A5%A8?/dG3=90N
- 社区公共卫生的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E9%AB%98%E8%B5%94%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%9D%E9%99%A9?/481
- 城市可持续生活的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E9%AB%98%E8%B5%94%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%9D%E9%99%A9?/ydh
- 社区老年食堂的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E9%AB%98%E8%B5%94%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%9D%E9%99%A9?/0Uk
- 智慧停车服务的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E9%AB%98%E8%B5%94%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%9D%E9%99%A9?/115=cqv
- 乡村公共文化的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E9%AB%98%E8%B5%94%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%9D%E9%99%A9?/pig=745
- 城市公共饮水的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E9%AB%98%E8%B5%94%E7%8E%87%E6%98%AF%E5%A4%9A%E5%B0%91_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%9D%E9%99%A9?/SiC=z2W
- 生成式工具使用的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E4%B8%93%E4%B8%9A%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/872
- 社区活动空间的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E4%B8%93%E4%B8%9A%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/nqf
- 社区文化传播的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E4%B8%93%E4%B8%9A%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/HQf
- 地方文化传播的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E4%B8%93%E4%B8%9A%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/659=bof
- 数字设备回收的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E4%B8%93%E4%B8%9A%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/okg=115
- 健康步道使用的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BA%91%E7%B3%BB%E7%BB%9F%E4%B8%93%E4%B8%9A%E7%9A%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/ClX=usn
- 本地旅行体验的空间设计要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E8%80%81%E6%9C%80%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/215
- 青年就业服务的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E8%80%81%E6%9C%80%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/mjk
- 老年数字阅读的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E8%80%81%E6%9C%80%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/u4O
- 城市适老服务的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E8%80%81%E6%9C%80%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/989=lur
- 社区老年食堂的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E8%80%81%E6%9C%80%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/jsl=506
- 社区法律科普的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E7%B3%BB%E7%BB%9F%E6%9C%80%E8%80%81%E6%9C%80%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/U55=mUC
- 社区快递服务的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B3%BB%E7%BB%9Fapp_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/753
- 街区绿化养护的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B3%BB%E7%BB%9Fapp_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/hsf
- 数字公共文化的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B3%BB%E7%BB%9Fapp_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/PKD
- 城市地名文化的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B3%BB%E7%BB%9Fapp_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/862=dwq
- 个人数据管理的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B3%BB%E7%BB%9Fapp_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/cer=558
- 数字生活课堂的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92%E7%B3%BB%E7%BB%9Fapp_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/Dse=VvU
- 家庭安全提示的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E4%B9%A6?/146
- 家庭园艺实践的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E4%B9%A6?/cih
- 科学睡眠习惯的资源整合思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E4%B9%A6?/GKi
- 生活服务数字化的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E4%B9%A6?/873=qks
- 应急物资管理的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E4%B9%A6?/lsd=100
- 远程协作工具的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7%E7%8E%A9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E4%B9%A6?/mCr=sPi
- 社会体育指导的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E7%89%88%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%A4%BE%E8%AE%BA?/297
- 城市游园体验的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E7%89%88%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%A4%BE%E8%AE%BA?/zlz
- 邻里共享空间的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E7%89%88%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%A4%BE%E8%AE%BA?/nDB
- 无障碍出行的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E7%89%88%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%A4%BE%E8%AE%BA?/824=geq
- 家庭饮食安排的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E7%89%88%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%A4%BE%E8%AE%BA?/fyb=534
- 青少年编程学习的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%AE%98%E6%96%B9%E7%89%88%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%A4%BE%E8%AE%BA?/Xcl=ITy
- 校园节能行动有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%89%88_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E5%A4%A7?/643
- 城乡交流活动的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%89%88_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E5%A4%A7?/mxp
- 乡村生活观察的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%89%88_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E5%A4%A7?/7PB
- 家庭收纳实践中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%89%88_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E5%A4%A7?/888=iwc
- 城市公共空间的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%89%88_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E5%A4%A7?/sql=159
- 零废弃生活尝试的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%81%8A%E5%A4%A9%E5%AE%A4%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%89%88_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E5%A4%A7?/6sE=OPL
- 城市骑行环境的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/304
- 社区托育服务的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/ajg
- 社区运动空间的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/msx
- 家庭用电安全的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/158=qeu
- 绿色出行服务从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/brp=227
- 社区儿童活动的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%9B%9E%E8%A1%80%E4%B8%80%E5%AF%B9%E4%B8%80_%E9%9B%B6%E5%94%AE%E8%B4%A2%E7%BB%8F?/tBz=lTz
- 消防知识宣传的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E6%BA%90?/408
- 智慧城市体验的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E6%BA%90?/yfz
- 智能家居应用的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E6%BA%90?/J3Z
- 垃圾分类指导的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E6%BA%90?/628=zuj
- 老年运动活动的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E6%BA%90?/qmv=489
- 家庭教育交流中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E7%B2%BE%E5%87%86%E4%B8%8A%E5%B2%B8%E8%AE%A1%E5%88%92%E5%B8%A6%E8%B5%9A_%E7%9F%A5%E4%B9%8E%E6%8E%A2%E6%BA%90?/p7g=TL6
- 农业科普体验的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%AE%89%E8%A3%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%8C%96?/071
- 家庭急救准备的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%AE%89%E8%A3%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%8C%96?/yyv
- 乡村电商实践的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%AE%89%E8%A3%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%8C%96?/8OQ
- 旧物循环利用的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%AE%89%E8%A3%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%8C%96?/911=okp
- 城市运动公园的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%AE%89%E8%A3%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%8C%96?/kvm=762
- 科学观察活动的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E5%AE%89%E8%A3%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%8C%96?/HmN=KBh
- 青年职业探索的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E7%BD%91%E8%B5%8C%E5%AF%BC%E5%B8%88%E7%9C%9F%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%90%97_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/382
- 乡村休闲旅游的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E7%BD%91%E8%B5%8C%E5%AF%BC%E5%B8%88%E7%9C%9F%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%90%97_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/zbx
- 信息无障碍体验的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E7%BD%91%E8%B5%8C%E5%AF%BC%E5%B8%88%E7%9C%9F%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%90%97_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/Qbi
- 数字资源检索的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E7%BD%91%E8%B5%8C%E5%AF%BC%E5%B8%88%E7%9C%9F%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%90%97_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/704=ceu
- 城市夜间照明的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E7%BD%91%E8%B5%8C%E5%AF%BC%E5%B8%88%E7%9C%9F%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%90%97_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/oug=641
- 环境监测科普的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E7%BD%91%E8%B5%8C%E5%AF%BC%E5%B8%88%E7%9C%9F%E8%83%BD%E5%B8%A6%E5%9B%9E%E8%A1%80%E5%90%97_%E5%BF%AB%E6%89%8B%E9%97%AE%E7%AD%94?/7bn=D7J
- 无障碍出行的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9APP%E5%AE%98%E6%96%B9%E7%89%88_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/220
- 全民阅读推广的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9APP%E5%AE%98%E6%96%B9%E7%89%88_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/iep
- 社区互助网络的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9APP%E5%AE%98%E6%96%B9%E7%89%88_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/q7r
- 社区故事采集的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9APP%E5%AE%98%E6%96%B9%E7%89%88_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/675=cvr
- 数字创作工具的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9APP%E5%AE%98%E6%96%B9%E7%89%88_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/kmu=854
- 电动汽车充电的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9APP%E5%AE%98%E6%96%B9%E7%89%88_%E5%BF%AB%E6%89%8B%E8%BE%9F%E8%B0%A3?/GKx=XvP

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
