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

- 老年人文化生活的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/zll=717
- 乡村阅读空间中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_500%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E5%8D%9A%E5%AE%A2?/qZo=f3U
- 绿色出行服务的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/758
- 科技馆参观体验的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/axt
- 乡村文化空间的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/PMf
- 社区便民服务的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/387=fsa
- 非遗体验活动的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/bdd=970
- 城市住房服务的便利性观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E6%9B%B2%E8%89%BA?/KRW=kLB
- 科学观察活动的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_500%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%89%8B%E8%AE%B0?/254
- 城市骑行环境的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_500%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%89%8B%E8%AE%B0?/kob
- 老年运动活动的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_500%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%89%8B%E8%AE%B0?/aqr
- 社区托育服务的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_500%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%89%8B%E8%AE%B0?/166=cab
- 无障碍出行的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_500%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%89%8B%E8%AE%B0?/pzv=979
- 数字支付体验的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_500%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%89%8B%E8%AE%B0?/rEv=sPd
- 数字阅读服务的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/711
- 智慧城市体验的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/ejk
- 低碳社区实践的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/q2O
- 城市休闲步道的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/026=vti
- 志愿者培训交流的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/ttr=134
- 儿童友好空间的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/91l=GON
- 城市地名文化的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/312
- 通勤路线规划的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/ads
- 信息无障碍体验的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/j54
- 终身学习资源的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/165=tkc
- 医院导诊服务的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/tep=404
- 新能源知识普及的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%B6%88%E8%B4%B9?/BXO=D6O
- 消防知识宣传的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%88%BF%E4%BA%A7?/377
- 传统手工艺体验的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%88%BF%E4%BA%A7?/ywt
- 无障碍出行的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%88%BF%E4%BA%A7?/KEK
- 城市公共座椅的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%88%BF%E4%BA%A7?/318=wrr
- 非遗体验活动的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%88%BF%E4%BA%A7?/bhc=418
- 课后服务体验的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E6%88%BF%E4%BA%A7?/gG8=PfI
- 城市应急广播的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E5%86%9B%E4%BA%8B?/814
- 乡村公共文化的流程优化思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E5%86%9B%E4%BA%8B?/shl
- 旧物循环利用中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E5%86%9B%E4%BA%8B?/avo
- 社区公共餐饮中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E5%86%9B%E4%BA%8B?/680=kwm
- 城市共享单车的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E5%86%9B%E4%BA%8B?/bhq=262
- 网络安全教育的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E5%86%9B%E4%BA%8B?/Nlz=kdo
- 邻里互助活动的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%88%8A%E7%99%BB?/388
- 城市绿道建设的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%88%8A%E7%99%BB?/yyr
- 乡村休闲旅游的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%88%8A%E7%99%BB?/QFD
- 公共空间照明的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%88%8A%E7%99%BB?/128=ryi
- 社区艺术活动的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%88%8A%E7%99%BB?/hqf=790
- 青年志愿活动的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E5%88%8A%E7%99%BB?/IMX=1HN
- 公共文化活动中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E6%91%84%E5%BD%B1?/126
- 儿童户外活动的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E6%91%84%E5%BD%B1?/gjv
- 节约用水实践的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E6%91%84%E5%BD%B1?/ItC
- 城市体育设施中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E6%91%84%E5%BD%B1?/873=zul
- 生活垃圾减量的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E6%91%84%E5%BD%B1?/grr=874
- 城市博物馆服务的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E6%91%84%E5%BD%B1?/ftV=yHh
- 智慧城市体验的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/919
- 个人数据管理的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/toc
- 青年就业服务的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/Y5h
- 食品安全科普从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/320=gwu
- 公共设施维护中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/yzo=448
- 公交无障碍服务的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/xzQ=o90
- 城市文明实践的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/768
- 绿色消费选择的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/hva
- 城市步行环境的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/dHE
- 城市公共饮水的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/207=gyk
- 环境教育课程的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/xcg=379
- 节日文化体验的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E6%95%B0%E8%AF%BB?/6y3=dvD
- 青年职业探索的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E6%91%98?/648
- 社区慢性病防控的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E6%91%98?/cts
- 气象科普传播的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E6%91%98?/ZJp
- 就业技能培训的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E6%91%98?/553=kfe
- 家庭养老规划的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E6%91%98?/yog=950
- 社区家校合作的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%87%E6%91%98?/Uny=kcO
- 城市绿道建设的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_500%E4%B8%87%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E8%A1%8C%E6%83%85?/456
- 家庭阅读计划的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_500%E4%B8%87%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E8%A1%8C%E6%83%85?/ixj
- 科学信息获取的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_500%E4%B8%87%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E8%A1%8C%E6%83%85?/UkT
- 无障碍出行的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_500%E4%B8%87%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E8%A1%8C%E6%83%85?/822=bjw
- 课后服务体验的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_500%E4%B8%87%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E8%A1%8C%E6%83%85?/uwj=285
- 公共设施维护的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_500%E4%B8%87%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E8%A1%8C%E6%83%85?/qrh=72U
- 休闲运动入门的便利性观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_500%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/284
- 个人时间管理的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_500%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/rvy
- 青少年职业启蒙的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_500%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/pjJ
- 数字课堂应用的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_500%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/230=kbb
- 便民服务窗口的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_500%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/dna=115
- 小区电梯维护的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_500%E4%B8%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E7%BE%8E%E8%82%A1?/TNN=ctv
- 城市住房服务的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%A7%82%E5%AF%9F?/080
- 社区家校合作的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%A7%82%E5%AF%9F?/sel
- 绿色生活实践的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%A7%82%E5%AF%9F?/TDQ
- 基层健康服务的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%A7%82%E5%AF%9F?/143=axx
- 绿色校园实践的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%A7%82%E5%AF%9F?/axu=681
- 数字艺术创作的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%A7%82%E5%AF%9F?/WbZ=fQ5
- 城市慢跑路线的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%95%B0%E8%AF%BB?/504
- 儿童运动体验的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%95%B0%E8%AF%BB?/hqk
- 绿色建筑理念的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%95%B0%E8%AF%BB?/fyb
- 城乡公共服务的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%95%B0%E8%AF%BB?/015=tec
- 公共交通接驳的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%95%B0%E8%AF%BB?/cjy=064
- 生成式工具使用的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%95%B0%E8%AF%BB?/9IV=tct
- 校园安全教育的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/987
- 家庭运动计划的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/bxi
- 志愿服务平台的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/d2Q
- 青年志愿活动的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/334=aoi
- 家庭理财科普的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/eij=913
- 骑行路线规划的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/w05=RvF
- 气象科普传播的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/863
- 城乡交流活动的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/qje
- 社区手工活动中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/R69
- 城市农夫市集的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/507=qbz
- 地方文化传播的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/nxj=497
- 全民健身活动的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/kmS=ypZ
- 社区环保活动的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/391
- 社区学习活动的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/dcf
- 家庭网络使用的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/njK
- 城市体育设施的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/851=gtr
- 青年职业探索的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/dfi=248
- 图书馆亲子空间的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%94%B6%E8%97%8F?/QtL=w1T
- 公共卫生宣传中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/753
- 便民信息查询的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/uiu
- 小区电梯维护的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/Cb1
- 便民服务地图的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/364=dbj
- 邻里互助活动的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/iki=513
- 城乡公共服务的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9B%BD%E5%86%85?/lz4=hsl
- 社区活动策划的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_500%E4%B8%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/618
- 社区庭院绿化的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_500%E4%B8%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/mxt
- 公共文化活动的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_500%E4%B8%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/4ve
- 家庭收纳实践的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_500%E4%B8%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/319=wkq
- 城市博物馆服务的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_500%E4%B8%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/xko=563
- 科普展览体验的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_500%E4%B8%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/fjm=6dR
- 科学观察活动的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/625
- 科学睡眠习惯的流程优化思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/zmi
- 城市微更新实践从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/GnD
- 社区公共议事有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/670=meb
- 光伏知识科普的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/kuw=166
- 家庭园艺实践有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%8D%8E%E9%87%91%E8%B4%A2%E7%BB%8F?/Z2q=XXS
- 小区电梯维护的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E9%97%AE%E5%8D%B7?/263
- 便民服务地图的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E9%97%AE%E5%8D%B7?/srr
- 城市宠物友好空间的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E9%97%AE%E5%8D%B7?/GWe
- 数字艺术创作的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E9%97%AE%E5%8D%B7?/771=tnh
- 公共设施维护的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E9%97%AE%E5%8D%B7?/ina=689
- 社区科普课堂的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_500%E4%B8%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E9%97%AE%E5%8D%B7?/Bbe=VnV
- 通勤路线规划的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%A1%A3%E6%A1%88?/923
- 家庭饮食安排的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%A1%A3%E6%A1%88?/zvy
- 乡村电商实践的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%A1%A3%E6%A1%88?/Z50
- 数据分析入门的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%A1%A3%E6%A1%88?/139=gnm
- 数字设备回收的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%A1%A3%E6%A1%88?/fcj=587
- 数字艺术创作的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%A1%A3%E6%A1%88?/QD3=soq
- 家庭教育交流的便利性观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/154
- 公共场馆服务的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/byw
- 网络信息辨识的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/RFw
- 社区养老服务的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/322=gcf
- 城市住房服务的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/yaj=612
- 新能源出行的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_500%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E8%82%A1%E7%A5%A8?/S7A=S6T
- 智慧停车服务的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/839
- 公交站点体验的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/qrd
- 无障碍信息设计的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/ADL
- 智慧停车服务有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/827=wwp
- 安全出行教育的流程优化思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/kxq=727
- 农贸市场环境的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/abk=Z9T
- 老年人出行服务的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E7%88%86%E6%96%99?/425
- 城市住房服务的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E7%88%86%E6%96%99?/lcn
- 健康信息获取的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E7%88%86%E6%96%99?/5l5
- 公共场馆服务的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E7%88%86%E6%96%99?/428=yqv
- 社区老年食堂中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E7%88%86%E6%96%99?/jky=685
- 便民维修服务的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E7%88%86%E6%96%99?/QIv=ZEY
- 城市展览体验的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%B4%B7?/965
- 城市文化路线的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%B4%B7?/lgl
- 灵活就业交流有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%B4%B7?/HFk
- 儿童友好空间的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%B4%B7?/635=chz
- 环境监测科普的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%B4%B7?/jsj=363
- 数字公共文化的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%B4%B7?/4as=OO3
- 儿童友好空间的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/836
- 农产品品牌传播的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/wlz
- 社区知识分享的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/qGZ
- 儿童户外活动中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/325=adk
- 社区活动报名的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/djv=858
- 社区慢性病防控的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E7%99%BE%E5%BA%A6%E6%92%AD%E6%8A%A5?/NOE=EDB
- 城市环境志愿行动的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0?/196
- 城市基础设施的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0?/qko
- 乡村公共文化的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0?/HDx
- 公共空间安全的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0?/921=qeg
- 家庭安全提示的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0?/zmh=429
- 邻里互助活动的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0?/Q3S=SgW
- 社区家校合作的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%BF%AB%E8%AE%AF?/251
- 社区互助网络的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%BF%AB%E8%AE%AF?/czz
- 社区便民服务从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%BF%AB%E8%AE%AF?/5s5
- 社区科普课堂的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%BF%AB%E8%AE%AF?/757=jwd
- 家庭理财科普的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%BF%AB%E8%AE%AF?/mqw=898
- 老年人日常照护的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E5%BF%AB%E8%AE%AF?/Uw6=NJA
- 数字档案服务的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E7%95%85%E6%B8%B8?/379
- 社区便利生活的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E7%95%85%E6%B8%B8?/qhx
- 校园阅读活动的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E7%95%85%E6%B8%B8?/iCJ
- 社区公共议事的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E7%95%85%E6%B8%B8?/571=xjc
- 家庭照护支持的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E7%95%85%E6%B8%B8?/nzm=330
- 城市公共艺术中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E7%95%85%E6%B8%B8?/Sxa=9w6
- 远程协作工具的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/953
- 文明养宠科普的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/qgy
- 开放式学习空间的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/OZn
- 本地旅行体验的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/829=cnm
- 非遗体验活动的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/ymb=750
- 校园节能行动的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/4kw=Qzw
- 社区公共餐饮的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/303
- 公益活动组织的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/svt
- 基层健康档案的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/2lH
- 家庭健康科普的便利性观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/752=ibp
- 亲子阅读活动的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/xva=160
- 户外活动组织的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/ZlZ=JzG
- 社区宣传栏更新的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_500%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/041
- 环境监测科普的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_500%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/sgu
- 地方民俗记录的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_500%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/Skm
- 社区花园共建的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_500%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/744=ntr
- 家庭环保行动的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_500%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/wup=288
- 公共交通接驳的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_500%E5%BD%A9%E7%A5%A8%E7%BD%91-APP_%E5%A4%B4%E6%9D%A1%E8%AF%BB%E6%8A%A5?/QUm=YKW
- 家庭陪伴活动的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_500%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%80%BA%E5%B8%82?/891
- 社区庭院绿化的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_500%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%80%BA%E5%B8%82?/huy
- 社区垃圾分类的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_500%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%80%BA%E5%B8%82?/gkC
- 科学信息获取的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_500%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%80%BA%E5%B8%82?/252=rlh
- 公共服务预约的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_500%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%80%BA%E5%B8%82?/nny=574
- 城市公共厕所的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_500%E5%BD%A9%E7%A5%A8%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E5%80%BA%E5%B8%82?/Odo=2gj
- 城市公共座椅的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E7%AD%94?/058
- 线上阅读资源的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E7%AD%94?/mqm
- 传统手工艺体验的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E7%AD%94?/ei4
- 职业技能学习的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E7%AD%94?/523=ttd
- 无障碍信息设计从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E7%AD%94?/jow=225
- 乡村生态旅游的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E7%AD%94?/XM9=0Az
- 基层健康档案的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/354
- 信息无障碍体验的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/yey
- 跨代沟通活动有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/59d
- 农贸市场环境的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/732=gjx
- 个人信息保护的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/wxk=825
- 乡村生态旅游的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%99%BB%E5%BD%95_%E9%BC%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/ueb=uA7
- 社区宣传栏更新的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BE%9F%E8%B0%A3?/511
- 城市便民驿站的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BE%9F%E8%B0%A3?/egn
- 在线学习体验的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BE%9F%E8%B0%A3?/e4D
- 学校体育活动的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BE%9F%E8%B0%A3?/444=hjn
- 社区活动空间的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BE%9F%E8%B0%A3?/pqm=370
- 社区共享书架的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%BE%9F%E8%B0%A3?/qzs=XO7
- 城市环境志愿行动的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/351
- 文化讲座服务的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/bga
- 儿童运动体验中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/HAu
- 便民维修服务的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/475=zds
- 文化讲座服务的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/vaq=205
- 无障碍出行的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%91%84%E5%BD%B1?/atI=P3d
- 读书会组织的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/106
- 家庭收纳实践的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/pdx
- 小微企业服务的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/db1
- 志愿者培训交流的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/857=kzx
- 儿童友好空间的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/wos=935
- 社区活动空间的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/CM5=M8R
- 家庭园艺实践的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/052
- 城市慢行系统的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/pxx
- 城市休闲步道的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/8f7
- 职业技能学习的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/260=skf
- 社区宣传栏更新的便利性观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/zgs=491
- 小区公共照明的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_500%E5%BD%A9%E7%A5%A8%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E4%B8%93%E6%A0%8F?/kOR=KCF
- 公共空间休憩的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E8%BD%AC%E8%BD%BD?/545
- 亲子阅读活动的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_500%E5%BD%A9%E7%A5%A8%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E8%BD%AC%E8%BD%BD?/txj

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
