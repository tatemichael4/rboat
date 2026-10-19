# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:20**

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

- 地方戏曲体验的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_75%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/PaB
- 医院导诊服务的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_75%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/202=odu
- 社区生活指南的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_75%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/ohj=606
- 城市微更新实践的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_75%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/iwN=iCn
- 地方旅游导览的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/213
- 小微企业服务的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/htv
- 城市游园体验的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/V7e
- 无障碍信息设计的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/582=ith
- 开源技术交流的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/mep=408
- 日常摄影记录的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_75%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/eZ3=veR
- 亲子科普活动的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%8E%86%E5%8F%B2?/848
- 学校体育活动的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%8E%86%E5%8F%B2?/vid
- 邻里共享空间的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%8E%86%E5%8F%B2?/ikC
- 文化场馆预约的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%8E%86%E5%8F%B2?/715=krf
- 家庭养老规划从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%8E%86%E5%8F%B2?/vdn=613
- 家庭健康管理的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E5%8E%86%E5%8F%B2?/dBK=DZf
- 城市慢行系统的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_36%E6%B0%AA%E5%80%BA%E5%B8%82?/520
- 消防知识宣传有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_36%E6%B0%AA%E5%80%BA%E5%B8%82?/jky
- 气象科普传播的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_36%E6%B0%AA%E5%80%BA%E5%B8%82?/omu
- 数字学习资源的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_36%E6%B0%AA%E5%80%BA%E5%B8%82?/250=rlm
- 课后服务体验中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_36%E6%B0%AA%E5%80%BA%E5%B8%82?/jpe=355
- 城乡交通衔接的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_36%E6%B0%AA%E5%80%BA%E5%B8%82?/5XW=6gA
- 城市步行友好的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%95%B0%E8%AF%BB?/500
- 校园节能行动的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%95%B0%E8%AF%BB?/dco
- 非遗课堂体验的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%95%B0%E8%AF%BB?/Pye
- 社区邻里服务的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%95%B0%E8%AF%BB?/998=ckx
- 家庭消费规划的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%95%B0%E8%AF%BB?/zdp=722
- 社区便利生活的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%95%B0%E8%AF%BB?/jsL=oqo
- 城市文明出行的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/496
- 城市应急科普的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/rhq
- 城乡公共服务的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/jEL
- 社区共享书架的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/500=ayj
- 图书馆数字服务的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/qqe=300
- 智慧城市体验的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B1%86%E7%93%A3%E8%B4%A2%E7%BB%8F?/XzD=nfz
- 智慧停车服务的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/360
- 社区便民集市的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/fnl
- 数字政务体验的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/Lsk
- 课后服务体验的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/540=ibu
- 学校体育活动的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/pob=442
- 城市应急科普从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%93%94%E5%93%A9%E6%96%87%E5%BA%93?/XV6=J88
- 社区科普课堂的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/663
- 数字支付体验的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/ecz
- 医院导诊服务的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/EO9
- 图书馆亲子空间的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/220=cye
- 便民服务窗口的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/qsj=969
- 社区学习活动的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E6%96%B0%E9%97%BB?/1fw=eXs
- 邻里共享空间的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%83%BD%E6%BA%90?/142
- 城市文明出行的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%83%BD%E6%BA%90?/vno
- 老年运动活动的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%83%BD%E6%BA%90?/GpK
- 公共空间安全的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%83%BD%E6%BA%90?/334=cxk
- 家庭用电安全的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%83%BD%E6%BA%90?/jqf=525
- 灵活就业交流有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%83%BD%E6%BA%90?/A6N=ycH
- 数字创意课程的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/772
- 学校食育活动的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/emh
- 智慧城市体验的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/jAy
- 家庭环保行动的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/188=kqa
- 社区公共议事的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/sjm=897
- 儿童友好空间的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/mco=h6s
- 公共服务沟通的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%B8%AF%E8%82%A1?/021
- 城市博物馆服务的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%B8%AF%E8%82%A1?/ajh
- 休闲运动入门的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%B8%AF%E8%82%A1?/7NW
- 校园社团活动的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%B8%AF%E8%82%A1?/032=oxz
- 基层医疗预约的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%B8%AF%E8%82%A1?/wpf=469
- 社区公共议事的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%B8%AF%E8%82%A1?/Q8q=EQ3
- 小区电梯维护的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/869
- 公共空间安全的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/aym
- 城市文化路线从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/DRQ
- 农产品消费体验有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/901=cxx
- 城市骑行环境的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/dol=371
- 城市步行环境的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/g7G=sqQ
- 基层健康服务的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E5%B1%85?/592
- 城市公共厕所的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E5%B1%85?/txg
- 街道综合服务的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E5%B1%85?/DWs
- 节气饮食文化的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E5%B1%85?/341=tbi
- 公共设施使用的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E5%B1%85?/wll=074
- 儿童运动体验的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E9%B8%BF%E5%AF%8C%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%B6%E5%B1%85?/zJD=Rg3
- 家庭理财科普的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%81%9A%E4%BB%BB%E5%8A%A1%E8%B5%9A%E9%92%B1_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8D%8F?/813
- 社区教育资源的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%81%9A%E4%BB%BB%E5%8A%A1%E8%B5%9A%E9%92%B1_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8D%8F?/zox
- 在线教育体验的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%81%9A%E4%BB%BB%E5%8A%A1%E8%B5%9A%E9%92%B1_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8D%8F?/TOF
- 节能家电使用的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%81%9A%E4%BB%BB%E5%8A%A1%E8%B5%9A%E9%92%B1_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8D%8F?/457=kdu
- 社区故事采集的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%81%9A%E4%BB%BB%E5%8A%A1%E8%B5%9A%E9%92%B1_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8D%8F?/vpl=588
- 乡村电商实践的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%81%9A%E4%BB%BB%E5%8A%A1%E8%B5%9A%E9%92%B1_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8D%8F?/eks=YC4
- 城市运动公园的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/752
- 社区活动报名的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/aet
- 社区公共餐饮的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/HxT
- 公共图书馆服务的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/704=byx
- 公共空间导览的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/xpx=188
- 数字资源检索的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/VJ3=FCD
- 居民健康教育的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%88%9B%E7%9B%88%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/719
- 科学运动指导的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%88%9B%E7%9B%88%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/daa
- 社区便民集市的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%88%9B%E7%9B%88%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/3fs
- 非遗课堂体验的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%88%9B%E7%9B%88%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/229=zmu
- 家庭食品保存中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%88%9B%E7%9B%88%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/peg=025
- 药品使用科普从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%88%9B%E7%9B%88%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/aEF=6te
- 急救知识普及的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9vip_%E4%BA%AC%E4%B8%9C%E6%95%99%E8%82%B2?/382
- 街区道路维护的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9vip_%E4%BA%AC%E4%B8%9C%E6%95%99%E8%82%B2?/rwf
- 乡村教育资源的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9vip_%E4%BA%AC%E4%B8%9C%E6%95%99%E8%82%B2?/Z9Y
- 基层健康服务的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9vip_%E4%BA%AC%E4%B8%9C%E6%95%99%E8%82%B2?/089=lrs
- 家庭安全提示的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9vip_%E4%BA%AC%E4%B8%9C%E6%95%99%E8%82%B2?/psc=502
- 街区道路维护的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9vip_%E4%BA%AC%E4%B8%9C%E6%95%99%E8%82%B2?/clM=yNA
- 乡村教育资源中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BE%9F%E8%B0%A3?/709
- 公共设施使用从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BE%9F%E8%B0%A3?/ogo
- 数字生活课堂的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BE%9F%E8%B0%A3?/jG5
- 城市应急科普的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BE%9F%E8%B0%A3?/520=ppi
- 物业服务沟通的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BE%9F%E8%B0%A3?/jfp=431
- 街头绿植养护的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9APP_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BE%9F%E8%B0%A3?/H7U=0RY
- 跨代沟通活动的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%9B%BE%E9%89%B4?/970
- 公共场所导视的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%9B%BE%E9%89%B4?/bwx
- 公共卫生设施的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%9B%BE%E9%89%B4?/30g
- 环境监测科普的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%9B%BE%E9%89%B4?/233=wxu
- 文化讲座服务有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%9B%BE%E9%89%B4?/rmq=538
- 运动安全知识的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%88%9B%E7%9B%88%E5%BD%A9-APP%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E5%9B%BE%E9%89%B4?/8Ua=53h
- 城乡公共服务的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%88%9B%E7%9B%88%E5%BD%A9%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%BF%85%E5%BA%94%E8%AE%BF%E8%B0%88?/844
- 健康饮食教育的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%88%9B%E7%9B%88%E5%BD%A9%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%BF%85%E5%BA%94%E8%AE%BF%E8%B0%88?/jsi
- 图书馆亲子空间的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%88%9B%E7%9B%88%E5%BD%A9%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%BF%85%E5%BA%94%E8%AE%BF%E8%B0%88?/U7H
- 数字设备回收从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%88%9B%E7%9B%88%E5%BD%A9%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%BF%85%E5%BA%94%E8%AE%BF%E8%B0%88?/465=iou
- 社区健康讲座的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%88%9B%E7%9B%88%E5%BD%A9%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%BF%85%E5%BA%94%E8%AE%BF%E8%B0%88?/fij=519
- 儿童运动体验的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%88%9B%E7%9B%88%E5%BD%A9%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%BF%85%E5%BA%94%E8%AE%BF%E8%B0%88?/jad=iKT
- 便民服务地图的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%88%9B%E7%9B%88%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B1%87%E5%B8%82?/007
- 新能源出行的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%88%9B%E7%9B%88%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B1%87%E5%B8%82?/byd
- 小区停车协商的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%88%9B%E7%9B%88%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B1%87%E5%B8%82?/67s
- 社区垃圾回收的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%88%9B%E7%9B%88%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B1%87%E5%B8%82?/760=rsy
- 居家适老化改造的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%88%9B%E7%9B%88%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B1%87%E5%B8%82?/hdu=017
- 学校食育活动从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%88%9B%E7%9B%88%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%B1%87%E5%B8%82?/OKE=mtR
- 城市适老服务的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%88%9B%E7%9B%88%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/569
- 老旧小区改造的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%88%9B%E7%9B%88%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/vbr
- 城市骑行环境中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%88%9B%E7%9B%88%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/Lxe
- 农产品消费体验的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%88%9B%E7%9B%88%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/664=tqu
- 社区公共餐饮的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%88%9B%E7%9B%88%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/bzz=238
- 线上办事服务的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E5%88%9B%E7%9B%88%E5%BD%A9welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E7%99%BE%E7%A7%91?/6rL=smT
- 健康饮食教育的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/401
- 青少年编程学习的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/rrc
- 节气饮食文化的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/srx
- 城市博物馆活动的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/642=whk
- 社区设施共享的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/wid=739
- 食品配送体验的流程优化思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%80%BA%E5%B8%82?/JYl=ifk
- 城乡公共服务的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/633
- 骑行路线规划的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/sme
- 基层健康档案的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/cLa
- 远程协作工具的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/230=nbq
- 地方旅游导览的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/thy=024
- 消防知识宣传的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%80%BA%E5%B8%82?/3JQ=dLC
- 公共健身器材的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%88%9B%E7%9B%88%E5%BD%A9welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0?/787
- 老年数字阅读的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%88%9B%E7%9B%88%E5%BD%A9welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0?/brk
- 城市绿道建设的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%88%9B%E7%9B%88%E5%BD%A9welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0?/4pY
- 城市公共自行车的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%88%9B%E7%9B%88%E5%BD%A9welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0?/266=zyi
- 城市文化路线的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%88%9B%E7%9B%88%E5%BD%A9welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0?/dlz=675
- 社区交通安全的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E5%88%9B%E7%9B%88%E5%BD%A9welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0?/f0i=W5x
- 无障碍出行的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%88%9B%E7%9B%88%E5%BD%A9app_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/859
- 乡村公共文化中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%88%9B%E7%9B%88%E5%BD%A9app_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/odd
- 本地历史资料的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%88%9B%E7%9B%88%E5%BD%A9app_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/vHB
- 小区公共照明的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%88%9B%E7%9B%88%E5%BD%A9app_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/863=hdp
- 城市公共饮水的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%88%9B%E7%9B%88%E5%BD%A9app_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/tao=317
- 数字政务体验的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%88%9B%E7%9B%88%E5%BD%A9app_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/HHr=7bo
- 家庭阅读计划的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/750
- 城市文化路线的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/uyk
- 校园安全教育的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/JD8
- 科技馆参观体验的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/082=sfz
- 社区互助网络的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/nfo=077
- 街区小店体验的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85_%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F?/X2S=582
- 城市慢行系统的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C%E7%94%A8%E6%88%B7_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/316
- 城市公共艺术的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C%E7%94%A8%E6%88%B7_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/kbn
- 乡村阅读活动的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C%E7%94%A8%E6%88%B7_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/o9e
- 便民服务窗口的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C%E7%94%A8%E6%88%B7_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/244=bkt
- 城市噪声观察的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C%E7%94%A8%E6%88%B7_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/yws=099
- 科学健身方法的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C%E7%94%A8%E6%88%B7_%E8%8A%92%E6%9E%9C%E4%BC%97%E6%B5%8B?/Cxj=myr
- 数字支付体验的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/394
- 公园休闲体验的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/jsm
- 学校体育活动的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/wJS
- 科学教育活动的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/497=tym
- 青少年心理健康的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/tzb=037
- 生活技能分享的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%90%E6%B1%87%E5%B8%82?/0N2=YjA
- 城市骑行环境的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%A8%B1%E4%B9%90_%E5%BF%85%E5%BA%94%E4%B9%A6%E7%94%BB?/344
- 职业技能学习的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%A8%B1%E4%B9%90_%E5%BF%85%E5%BA%94%E4%B9%A6%E7%94%BB?/enb
- 乡村文化空间的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%A8%B1%E4%B9%90_%E5%BF%85%E5%BA%94%E4%B9%A6%E7%94%BB?/Kzi
- 亲子阅读活动的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%A8%B1%E4%B9%90_%E5%BF%85%E5%BA%94%E4%B9%A6%E7%94%BB?/199=ctv
- 地方戏曲体验的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%A8%B1%E4%B9%90_%E5%BF%85%E5%BA%94%E4%B9%A6%E7%94%BB?/nnl=292
- 家庭科学教育中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E5%A4%A7%E5%8E%85-%E5%A8%B1%E4%B9%90_%E5%BF%85%E5%BA%94%E4%B9%A6%E7%94%BB?/zfd=NMJ
- 家庭饮食安排的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/739
- 公交站点体验的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/xos
- 邻里互助活动的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/u6C
- 周末休闲规划的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/316=mbr
- 城市夜间照明的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/hgj=273
- 家庭环保行动的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%88%8A%E7%99%BB?/6St=9WF
- 绿色出行服务的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/988
- 老年友好服务的流程优化思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/bmh
- 信息无障碍体验的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/Zjf
- 数字档案服务的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/109=piu
- 农村环境治理的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/tbz=898
- 数字艺术创作的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_500%E5%BD%A9%E5%A8%B1%E4%B9%90-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/XEu=be7
- 地方戏曲体验的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_DIII%E5%BD%A9%E4%B9%90%E5%9B%AD%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%97%B6%E6%8A%A5?/461
- 城市公共艺术的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_DIII%E5%BD%A9%E4%B9%90%E5%9B%AD%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%97%B6%E6%8A%A5?/wml
- 老年数字阅读的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_DIII%E5%BD%A9%E4%B9%90%E5%9B%AD%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%97%B6%E6%8A%A5?/gyT
- 绿色消费选择的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_DIII%E5%BD%A9%E4%B9%90%E5%9B%AD%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%97%B6%E6%8A%A5?/005=kyw
- 农贸市场环境中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_DIII%E5%BD%A9%E4%B9%90%E5%9B%AD%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%97%B6%E6%8A%A5?/oyn=279
- 非遗课堂体验的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_DIII%E5%BD%A9%E4%B9%90%E5%9B%AD%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%97%B6%E6%8A%A5?/WcW=Z3y
- 校园阅读活动的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_DIII%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/924
- 开源技术交流的便利性观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_DIII%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/htb
- 科学运动指导的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_DIII%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/Hmh
- 文化讲座服务的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_DIII%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/596=lac
- 公共服务咨询的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_DIII%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/fjs=541
- 垃圾分类指导的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_DIII%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E5%B0%9A?/V9F=u2j
- 城市体育设施的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_DII%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%9B%BE%E9%89%B4?/139
- 社区消防演练的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_DII%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%9B%BE%E9%89%B4?/kok
- 城市空气科普的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_DII%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%9B%BE%E9%89%B4?/wGE
- 社区防暑服务的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_DII%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%9B%BE%E9%89%B4?/247=jky
- 本地历史资料的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_DII%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%9B%BE%E9%89%B4?/iiu=570
- 乡村公共文化的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_DII%E5%BD%A9%E4%B9%90%E5%9B%AD-%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%9B%BE%E9%89%B4?/znA=TFs
- 公园亲子设施的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E4%B9%90%E5%9B%ADDIII%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/330
- 街区道路维护的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E4%B9%90%E5%9B%ADDIII%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/lsw
- 社区宠物管理的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E4%B9%90%E5%9B%ADDIII%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/TVK
- 个人时间管理从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E4%B9%90%E5%9B%ADDIII%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/778=yss
- 老年人日常照护的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E4%B9%90%E5%9B%ADDIII%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/vns=138
- 社区科普课堂的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E4%B9%90%E5%9B%ADDIII%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/kwK=AQ5
- 城市文化路线的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_dlll%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E5%9F%8E%E4%BA%8B?/015
- 公园无障碍服务的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_dlll%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E5%9F%8E%E4%BA%8B?/zdp
- 街区绿化养护的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_dlll%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E5%9F%8E%E4%BA%8B?/RAM
- 城市应急广播从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_dlll%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E5%9F%8E%E4%BA%8B?/608=nik
- 公共空间安全的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_dlll%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E5%9F%8E%E4%BA%8B?/wmd=935
- 家庭环保习惯的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_dlll%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E5%9F%8E%E4%BA%8B?/TwU=2Mb
- 家庭节能设备的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_diii%E5%BD%A9%E4%B9%90%E5%9B%AD%E5%BA%94%E7%94%A8%E4%B8%8B%E8%BD%BD_360%E5%85%AC%E5%BC%80%E8%AF%BE?/159
- 社区快递服务的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_diii%E5%BD%A9%E4%B9%90%E5%9B%AD%E5%BA%94%E7%94%A8%E4%B8%8B%E8%BD%BD_360%E5%85%AC%E5%BC%80%E8%AF%BE?/odz
- 社区阅读服务中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_diii%E5%BD%A9%E4%B9%90%E5%9B%AD%E5%BA%94%E7%94%A8%E4%B8%8B%E8%BD%BD_360%E5%85%AC%E5%BC%80%E8%AF%BE?/in4
- 便民维修服务的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_diii%E5%BD%A9%E4%B9%90%E5%9B%AD%E5%BA%94%E7%94%A8%E4%B8%8B%E8%BD%BD_360%E5%85%AC%E5%BC%80%E8%AF%BE?/977=zot
- 乡村阅读活动的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_diii%E5%BD%A9%E4%B9%90%E5%9B%AD%E5%BA%94%E7%94%A8%E4%B8%8B%E8%BD%BD_360%E5%85%AC%E5%BC%80%E8%AF%BE?/ayb=512
- 志愿服务平台的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_diii%E5%BD%A9%E4%B9%90%E5%9B%AD%E5%BA%94%E7%94%A8%E4%B8%8B%E8%BD%BD_360%E5%85%AC%E5%BC%80%E8%AF%BE?/Cj1=imG
- 图书借阅体验的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_dlll%E5%BD%A9%E4%B9%90%E5%9B%AD3_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/060
- 公共空间照明的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_dlll%E5%BD%A9%E4%B9%90%E5%9B%AD3_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/rik
- 城乡交流活动的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_dlll%E5%BD%A9%E4%B9%90%E5%9B%AD3_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/edz
- 社区便民集市的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_dlll%E5%BD%A9%E4%B9%90%E5%9B%AD3_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/995=xzn
- 儿童友好街区的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_dlll%E5%BD%A9%E4%B9%90%E5%9B%AD3_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/qxp=787
- 绿色出行服务的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_dlll%E5%BD%A9%E4%B9%90%E5%9B%AD3_%E8%B0%B7%E6%AD%8C%E6%97%A5%E6%8A%A5?/qfB=WnQ
- 基层健康服务的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E4%B9%90%E5%9B%ADdsn77.pop-188.%E4%B8%AD%E5%9B%BD_36%E6%B0%AA%E5%88%8A%E7%99%BB?/767
- 城市公共空间的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E4%B9%90%E5%9B%ADdsn77.pop-188.%E4%B8%AD%E5%9B%BD_36%E6%B0%AA%E5%88%8A%E7%99%BB?/aoz
- 儿童安全出行的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E4%B9%90%E5%9B%ADdsn77.pop-188.%E4%B8%AD%E5%9B%BD_36%E6%B0%AA%E5%88%8A%E7%99%BB?/HTx
- 城市慢跑路线的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E4%B9%90%E5%9B%ADdsn77.pop-188.%E4%B8%AD%E5%9B%BD_36%E6%B0%AA%E5%88%8A%E7%99%BB?/049=uxt
- 全民健身活动的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E4%B9%90%E5%9B%ADdsn77.pop-188.%E4%B8%AD%E5%9B%BD_36%E6%B0%AA%E5%88%8A%E7%99%BB?/xfz=323
- 农贸市场环境中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E4%B9%90%E5%9B%ADdsn77.pop-188.%E4%B8%AD%E5%9B%BD_36%E6%B0%AA%E5%88%8A%E7%99%BB?/pbG=Aa4
- 城市慢行系统从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E4%B9%90%E5%9B%AD%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E7%BD%91%E5%9D%80_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/494
- 青年志愿活动的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E4%B9%90%E5%9B%AD%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E7%BD%91%E5%9D%80_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/nmx
- 公交站点体验的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E4%B9%90%E5%9B%AD%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E7%BD%91%E5%9D%80_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/eYm
- 科学运动指导的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E4%B9%90%E5%9B%AD%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E7%BD%91%E5%9D%80_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/911=aix
- 社区运动空间的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E4%B9%90%E5%9B%AD%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E7%BD%91%E5%9D%80_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/epm=480
- 家庭节能实践的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%BD%A9%E4%B9%90%E5%9B%AD%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E7%BD%91%E5%9D%80_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/BL3=0HC
- 无障碍出行的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83?/868
- 儿童户外活动从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83?/rek
- 公园无障碍服务的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83?/Gc0
- 老年人出行服务的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83?/568=sdp
- 校园阅读活动的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83?/bqs=205
- 节能家电使用的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E4%B9%90%E5%9B%AD%E6%9C%80%E6%96%B0%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83?/yy2=k7L

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
