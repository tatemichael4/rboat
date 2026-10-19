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

- 社区防暑服务的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/xug=052
- 城乡交通衔接的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/pD7=S7M
- 家庭饮食安排的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_5833%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/784
- 老年智能设备的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_5833%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/ijb
- 机器人科普活动的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_5833%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/r46
- 社区阅读服务的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_5833%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/003=lpc
- 老年人日常照护的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_5833%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/hfx=397
- 校园安全教育的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_5833%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/Fzv=P6p
- 城市树木认养的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B9%9D%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BC%97%E6%B5%8B?/599
- 城市环境志愿行动有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B9%9D%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BC%97%E6%B5%8B?/rbh
- 节日文化体验的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B9%9D%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BC%97%E6%B5%8B?/FmJ
- 亲子阅读活动的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B9%9D%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BC%97%E6%B5%8B?/081=tgs
- 全民阅读推广的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B9%9D%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BC%97%E6%B5%8B?/gbn=386
- 健康饮水科普从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B9%9D%E8%88%AA%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BC%97%E6%B5%8B?/Luv=61Z
- 城市夜间照明的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_109cc%E5%A8%B1%E4%B9%90_%E8%B0%B7%E6%AD%8C%E6%96%87%E5%BA%93?/515
- 乡村文化活动的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_109cc%E5%A8%B1%E4%B9%90_%E8%B0%B7%E6%AD%8C%E6%96%87%E5%BA%93?/qyi
- 健康信息获取的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_109cc%E5%A8%B1%E4%B9%90_%E8%B0%B7%E6%AD%8C%E6%96%87%E5%BA%93?/xA4
- 邻里共享空间的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_109cc%E5%A8%B1%E4%B9%90_%E8%B0%B7%E6%AD%8C%E6%96%87%E5%BA%93?/611=jxo
- 社区故事采集的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_109cc%E5%A8%B1%E4%B9%90_%E8%B0%B7%E6%AD%8C%E6%96%87%E5%BA%93?/tei=399
- 周末休闲规划的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_109cc%E5%A8%B1%E4%B9%90_%E8%B0%B7%E6%AD%8C%E6%96%87%E5%BA%93?/clc=AAp
- 公共服务数字化的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_109cc%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/575
- 城市夜间照明的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_109cc%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/qzk
- 口袋公园建设的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_109cc%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/vAm
- 数字政务体验的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_109cc%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/793=pvt
- 家庭阅读计划的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_109cc%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/usj=538
- 儿童阅读角的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_109cc%E5%BD%A9%E7%A5%A8-welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E8%AF%BB%E5%9B%BE?/Jgj=TFF
- 社区庭院绿化的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_109cc%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/860
- 农贸市场环境的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_109cc%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/xtx
- 消防知识宣传的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_109cc%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/CM8
- 数字支付体验的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_109cc%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/412=gau
- 老年人出行服务的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_109cc%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/tzb=583
- 社区信息发布的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_109cc%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E8%AF%BB%E6%8A%A5?/Uch=Ibv
- 城市骑行环境的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_109cc%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E6%BE%8E%E6%B9%83%E4%BF%A1%E8%AE%BF?/060
- 乡村生活观察的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_109cc%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E6%BE%8E%E6%B9%83%E4%BF%A1%E8%AE%BF?/tox
- 社区活动策划的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_109cc%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E6%BE%8E%E6%B9%83%E4%BF%A1%E8%AE%BF?/Xqk
- 社区故事采集的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_109cc%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E6%BE%8E%E6%B9%83%E4%BF%A1%E8%AE%BF?/473=plw
- 公共交通接驳的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_109cc%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E6%BE%8E%E6%B9%83%E4%BF%A1%E8%AE%BF?/asr=570
- 绿色快递包装中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_109cc%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E6%BE%8E%E6%B9%83%E4%BF%A1%E8%AE%BF?/E2V=xIa
- 城市雨天出行的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_109CCI%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8%E7%8E%A9%E6%B3%95%E8%A7%A3%E6%9E%90_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/326
- 安全出行教育的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_109CCI%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8%E7%8E%A9%E6%B3%95%E8%A7%A3%E6%9E%90_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/att
- 城市文明实践的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_109CCI%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8%E7%8E%A9%E6%B3%95%E8%A7%A3%E6%9E%90_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/o8E
- 城市基础设施的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_109CCI%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8%E7%8E%A9%E6%B3%95%E8%A7%A3%E6%9E%90_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/330=urz
- 急救知识普及从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_109CCI%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8%E7%8E%A9%E6%B3%95%E8%A7%A3%E6%9E%90_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/zsi=508
- 绿色生活实践的便利性观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_109CCI%E6%97%A7%E7%89%88%E5%BD%A9%E7%A5%A8%E7%8E%A9%E6%B3%95%E8%A7%A3%E6%9E%90_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/2Ua=rME
- 家庭阅读计划的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_978%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/752
- 社区共享书架的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_978%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/jex
- 社区文化传播的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_978%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/ofY
- 智慧停车服务从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_978%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/497=jly
- 青年就业服务的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_978%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/uqt=764
- 无障碍信息设计的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_978%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9B%BD%E9%99%85%E8%B4%A2%E7%BB%8F?/Tmc=8nM
- 数字阅读服务的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_978%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_36%E6%B0%AA%E8%88%86%E6%83%85?/145
- 邻里共享空间的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_978%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_36%E6%B0%AA%E8%88%86%E6%83%85?/zpp
- 城乡交流活动的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_978%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_36%E6%B0%AA%E8%88%86%E6%83%85?/Rb6
- 数字档案服务的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_978%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_36%E6%B0%AA%E8%88%86%E6%83%85?/825=cit
- 数字公共文化的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_978%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_36%E6%B0%AA%E8%88%86%E6%83%85?/vxu=665
- 社区教育资源的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_978%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_36%E6%B0%AA%E8%88%86%E6%83%85?/rUD=VhV
- 生成式工具使用的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_978cc%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E8%BE%9F%E8%B0%A3?/637
- 环境教育课程有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_978cc%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E8%BE%9F%E8%B0%A3?/afy
- 开放式学习空间的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_978cc%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E8%BE%9F%E8%B0%A3?/EmU
- 无障碍出行的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_978cc%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E8%BE%9F%E8%B0%A3?/913=yov
- 环境教育课程的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_978cc%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E8%BE%9F%E8%B0%A3?/tly=595
- 青年就业服务的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_978cc%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_36%E6%B0%AA%E8%BE%9F%E8%B0%A3?/xTc=iJS
- 家庭急救准备的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_978cc%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/368
- 软件开发学习的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_978cc%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/bqd
- 社区庭院绿化的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_978cc%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/bMp
- 绿色校园实践的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_978cc%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/889=hnd
- 市民意见收集的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_978cc%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/puu=376
- 城市基础设施中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_978cc%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E8%B0%B7%E6%AD%8C%E7%89%B9%E7%A8%BF?/pHr=Jvi
- 图书馆数字服务的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_978cc%E8%80%81%E7%89%88%E6%9C%AC%E5%AE%89%E5%8D%93%E7%89%88_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/910
- 小区停车协商的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_978cc%E8%80%81%E7%89%88%E6%9C%AC%E5%AE%89%E5%8D%93%E7%89%88_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/rcf
- 小微企业服务的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_978cc%E8%80%81%E7%89%88%E6%9C%AC%E5%AE%89%E5%8D%93%E7%89%88_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/825
- 便民信息查询的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_978cc%E8%80%81%E7%89%88%E6%9C%AC%E5%AE%89%E5%8D%93%E7%89%88_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/999=fpe
- 儿童友好街区的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_978cc%E8%80%81%E7%89%88%E6%9C%AC%E5%AE%89%E5%8D%93%E7%89%88_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/fop=465
- 节气饮食文化的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_978cc%E8%80%81%E7%89%88%E6%9C%AC%E5%AE%89%E5%8D%93%E7%89%88_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/PSA=und
- 城市可持续生活的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_978cc%E5%A8%B1%E4%B9%90-%E4%BD%93%E5%BD%A9_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/494
- 城市绿道建设的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_978cc%E5%A8%B1%E4%B9%90-%E4%BD%93%E5%BD%A9_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/ofe
- 家庭健康管理的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_978cc%E5%A8%B1%E4%B9%90-%E4%BD%93%E5%BD%A9_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/Pmp
- 城乡交流活动的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_978cc%E5%A8%B1%E4%B9%90-%E4%BD%93%E5%BD%A9_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/322=nbm
- 生活技能分享的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_978cc%E5%A8%B1%E4%B9%90-%E4%BD%93%E5%BD%A9_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/vwy=888
- 城市宠物友好空间的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_978cc%E5%A8%B1%E4%B9%90-%E4%BD%93%E5%BD%A9_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/3WB=PF1
- 城市公共艺术的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_978cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/815
- 图书借阅体验的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_978cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/gvf
- 基层医疗预约的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_978cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/4HR
- 科普展览体验的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_978cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/251=mrh
- 公共设施维护的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_978cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/jgj=424
- 科学教育活动的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_978cc%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E5%9B%AD%E8%89%BA?/nSF=SyX
- 青少年职业启蒙的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8978app%E8%B4%A6%E5%8F%B7%E7%99%BB%E5%BD%95%E4%B8%8D%E4%B8%8A_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/796
- 儿童友好空间的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8978app%E8%B4%A6%E5%8F%B7%E7%99%BB%E5%BD%95%E4%B8%8D%E4%B8%8A_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/zwj
- 光伏知识科普的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8978app%E8%B4%A6%E5%8F%B7%E7%99%BB%E5%BD%95%E4%B8%8D%E4%B8%8A_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/IHD
- 药品使用科普的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8978app%E8%B4%A6%E5%8F%B7%E7%99%BB%E5%BD%95%E4%B8%8D%E4%B8%8A_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/017=bhr
- 绿色出行服务的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8978app%E8%B4%A6%E5%8F%B7%E7%99%BB%E5%BD%95%E4%B8%8D%E4%B8%8A_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/czm=876
- 老年人文化生活的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8978app%E8%B4%A6%E5%8F%B7%E7%99%BB%E5%BD%95%E4%B8%8D%E4%B8%8A_%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F?/46o=RZV
- 社区便利生活的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_758cc%E5%BD%A9%E7%A5%A8%E7%A0%B4%E8%A7%A3%E7%89%88_36%E6%B0%AA%E6%9C%8D%E9%A5%B0?/070
- 公共交通接驳的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_758cc%E5%BD%A9%E7%A5%A8%E7%A0%B4%E8%A7%A3%E7%89%88_36%E6%B0%AA%E6%9C%8D%E9%A5%B0?/gdv
- 健康步道使用的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_758cc%E5%BD%A9%E7%A5%A8%E7%A0%B4%E8%A7%A3%E7%89%88_36%E6%B0%AA%E6%9C%8D%E9%A5%B0?/29h
- 街区绿化养护的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_758cc%E5%BD%A9%E7%A5%A8%E7%A0%B4%E8%A7%A3%E7%89%88_36%E6%B0%AA%E6%9C%8D%E9%A5%B0?/329=gfh
- 节约用水实践的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_758cc%E5%BD%A9%E7%A5%A8%E7%A0%B4%E8%A7%A3%E7%89%88_36%E6%B0%AA%E6%9C%8D%E9%A5%B0?/dnp=191
- 数字创意课程的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_758cc%E5%BD%A9%E7%A5%A8%E7%A0%B4%E8%A7%A3%E7%89%88_36%E6%B0%AA%E6%9C%8D%E9%A5%B0?/wyi=I88
- 社区修缮行动的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_758%E6%97%A7%E7%89%88%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E6%85%A7%E7%9C%BC?/883
- 家庭环保行动的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_758%E6%97%A7%E7%89%88%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E6%85%A7%E7%9C%BC?/oqj
- 图书借阅体验的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_758%E6%97%A7%E7%89%88%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E6%85%A7%E7%9C%BC?/gXB
- 科学观察活动的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_758%E6%97%A7%E7%89%88%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E6%85%A7%E7%9C%BC?/376=qkw
- 安全出行教育的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_758%E6%97%A7%E7%89%88%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E6%85%A7%E7%9C%BC?/vvv=501
- 文化遗产保护科普的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_758%E6%97%A7%E7%89%88%E6%89%8B%E6%9C%BA%E5%BD%A9%E7%A5%A8_%E6%96%B0%E6%B5%AA%E6%85%A7%E7%9C%BC?/ZPP=aeK
- 物业服务沟通的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8758vip%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/687
- 邻里共享空间的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8758vip%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/qwe
- 城市建设科普的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8758vip%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/1Ao
- 社区活动空间的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8758vip%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/727=lam
- 老年人出行服务的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8758vip%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/out=944
- 城市体育设施的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8758vip%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%90%E6%99%A8%E6%8A%A5?/rfE=V7l
- 城市树木认养的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_758cc%E5%BD%A9app%E8%80%81%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/174
- 城乡交流活动的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_758cc%E5%BD%A9app%E8%80%81%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/eyo
- 城市慢行系统从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_758cc%E5%BD%A9app%E8%80%81%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/Amp
- 公共空间导览的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_758cc%E5%BD%A9app%E8%80%81%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/011=drx
- 城乡交流活动的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_758cc%E5%BD%A9app%E8%80%81%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/fxp=517
- 儿童友好空间的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_758cc%E5%BD%A9app%E8%80%81%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/RIN=l0n
- 医院导诊服务的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_987%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD_360%E5%9C%88%E5%AD%90?/022
- 社区信息发布的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_987%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD_360%E5%9C%88%E5%AD%90?/wjp
- 光伏知识科普的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_987%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD_360%E5%9C%88%E5%AD%90?/XJb
- 周末休闲规划的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_987%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD_360%E5%9C%88%E5%AD%90?/095=rtq
- 老年人日常照护的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_987%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD_360%E5%9C%88%E5%AD%90?/ilr=895
- 本地消费场景的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_987%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD_360%E5%9C%88%E5%AD%90?/yHN=MvI
- 地方戏曲体验的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_987%E5%A8%B1%E4%B9%90%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8D%8F?/962
- 家庭健康管理的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_987%E5%A8%B1%E4%B9%90%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8D%8F?/byv
- 环境教育课程的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_987%E5%A8%B1%E4%B9%90%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8D%8F?/cbW
- 小区停车协商的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_987%E5%A8%B1%E4%B9%90%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8D%8F?/550=mdf
- 光伏知识科普中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_987%E5%A8%B1%E4%B9%90%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8D%8F?/dlo=273
- 社区休闲设施的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_987%E5%A8%B1%E4%B9%90%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8D%8F?/MGF=vdF
- 公园无障碍服务的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_987%E5%A8%B1%E4%B9%90%E5%AE%98app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E9%97%AE%E5%8D%B7?/150
- 城市地名文化的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_987%E5%A8%B1%E4%B9%90%E5%AE%98app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E9%97%AE%E5%8D%B7?/nmq
- 社区法律科普的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_987%E5%A8%B1%E4%B9%90%E5%AE%98app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E9%97%AE%E5%8D%B7?/QRu
- 气象科普传播的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_987%E5%A8%B1%E4%B9%90%E5%AE%98app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E9%97%AE%E5%8D%B7?/861=swz
- 志愿者培训交流的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_987%E5%A8%B1%E4%B9%90%E5%AE%98app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E9%97%AE%E5%8D%B7?/kjj=871
- 家庭收纳实践的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_987%E5%A8%B1%E4%B9%90%E5%AE%98app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E9%97%AE%E5%8D%B7?/bWi=zC6
- 公益活动组织的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_987%E5%BD%A9%E7%A5%A8%E6%97%A5%E7%89%88%E6%9C%AC%E5%A4%A7%E5%85%A8_%E5%A4%B4%E6%9D%A1%E6%B1%87%E5%B8%82?/638
- 垃圾分类指导的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_987%E5%BD%A9%E7%A5%A8%E6%97%A5%E7%89%88%E6%9C%AC%E5%A4%A7%E5%85%A8_%E5%A4%B4%E6%9D%A1%E6%B1%87%E5%B8%82?/qhu
- 物业服务沟通的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_987%E5%BD%A9%E7%A5%A8%E6%97%A5%E7%89%88%E6%9C%AC%E5%A4%A7%E5%85%A8_%E5%A4%B4%E6%9D%A1%E6%B1%87%E5%B8%82?/u6p
- 社区老年食堂的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_987%E5%BD%A9%E7%A5%A8%E6%97%A5%E7%89%88%E6%9C%AC%E5%A4%A7%E5%85%A8_%E5%A4%B4%E6%9D%A1%E6%B1%87%E5%B8%82?/042=jjd
- 社区老年食堂有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_987%E5%BD%A9%E7%A5%A8%E6%97%A5%E7%89%88%E6%9C%AC%E5%A4%A7%E5%85%A8_%E5%A4%B4%E6%9D%A1%E6%B1%87%E5%B8%82?/spc=751
- 老年人文化生活的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_987%E5%BD%A9%E7%A5%A8%E6%97%A5%E7%89%88%E6%9C%AC%E5%A4%A7%E5%85%A8_%E5%A4%B4%E6%9D%A1%E6%B1%87%E5%B8%82?/zcy=0hp
- 儿童运动体验有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_987%E5%A8%B1%E4%B9%90welcome_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/572
- 文化讲座服务的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_987%E5%A8%B1%E4%B9%90welcome_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/fou
- 社区家校合作的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_987%E5%A8%B1%E4%B9%90welcome_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/IgY
- 乡村电商实践的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_987%E5%A8%B1%E4%B9%90welcome_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/911=vpj
- 家庭节能设备的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_987%E5%A8%B1%E4%B9%90welcome_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/keq=001
- 数字生活课堂的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_987%E5%A8%B1%E4%B9%90welcome_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/B39=841
- 老年友好服务的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_987%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E7%BB%8F%E6%B5%8E?/298
- 绿色消费选择的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_987%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E7%BB%8F%E6%B5%8E?/gsz
- 创业经验分享的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_987%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E7%BB%8F%E6%B5%8E?/ymG
- 社区手工活动的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_987%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E7%BB%8F%E6%B5%8E?/198=zbj
- 社区宣传栏更新的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_987%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E7%BB%8F%E6%B5%8E?/hbd=225
- 家庭运动计划的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_987%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BD%91%E6%98%93%E7%BB%8F%E6%B5%8E?/KkC=wdG
- 网络信息辨识的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_987%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/461
- 健康饮水科普的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_987%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/dgr
- 城市游园体验中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_987%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/YR5
- 便民信息查询的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_987%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/673=grh
- 校园节能行动的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_987%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/ect=062
- 科技馆参观体验的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_987%E5%BD%A9%E7%A5%A8welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/BPv=PMH
- 食品安全科普的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_360%E6%97%A5%E6%8A%A5?/340
- 节能生活方式的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_360%E6%97%A5%E6%8A%A5?/kli
- 绿色建筑理念的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_360%E6%97%A5%E6%8A%A5?/JtJ
- 校园阅读活动的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_360%E6%97%A5%E6%8A%A5?/654=afu
- 家庭运动计划的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_360%E6%97%A5%E6%8A%A5?/gxs=890
- 城市雨天出行的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_360%E6%97%A5%E6%8A%A5?/Hh9=9OQ
- 家庭环保习惯中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/488
- 乡村电商实践的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/yeh
- 公共服务咨询的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/KVc
- 基层健康服务的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/306=iig
- 在线学习体验的便利性观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/tat=024
- 本地消费场景的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%AD%E8%AE%B0?/MYs=kQA
- 线上阅读资源的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E7%99%BB%E9%99%86%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C?/698
- 公共场所导视的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E7%99%BB%E9%99%86%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C?/ljk
- 灵活就业交流的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E7%99%BB%E9%99%86%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C?/WAA
- 个人信息保护的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E7%99%BB%E9%99%86%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C?/557=krn
- 青少年科普实践的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E7%99%BB%E9%99%86%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C?/kcg=515
- 乡村文化活动的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E7%99%BB%E9%99%86%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C?/T98=c13
- 社区学习活动的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/317
- 家庭教育交流的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/usv
- 校园阅读活动的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/yf3
- 社会体育指导的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/198=poe
- 公共服务咨询的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/ioh=857
- 儿童户外活动的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80_%E5%A4%B4%E6%9D%A1%E4%BA%BA%E7%89%A9?/Rcj=7jj
- 社区阅读服务的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%89%B9%E7%A8%BF?/910
- 社区活动策划的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%89%B9%E7%A8%BF?/dis
- 读书会组织的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%89%B9%E7%A8%BF?/myC
- 社区科普课堂的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%89%B9%E7%A8%BF?/761=tse
- 社区商业活力的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%89%B9%E7%A8%BF?/upl=903
- 社区垃圾分类的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E7%89%B9%E7%A8%BF?/Nqj=JJy
- 社区垃圾分类的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/754
- 家庭理财科普的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/yie
- 跨代沟通活动的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/uWH
- 健康饮食教育的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/622=sgr
- 家庭园艺实践的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/vll=590
- 公共设施维护的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%B4%B2%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/mVj=P8H
- 绿色校园实践的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/533
- 儿童阅读角的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/dcj
- 城市住房服务的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/Hsc
- 家庭园艺实践的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/387=vno
- 开放数据应用的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/xqe=334
- 家庭阅读计划的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_3550%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%97%E8%BD%AC%E8%BD%BD?/ZNW=nnl
- 家庭节能设备中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_3550%E5%A8%B1%E4%B9%90-%E7%99%BB%E9%99%86_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/659
- 新能源出行的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_3550%E5%A8%B1%E4%B9%90-%E7%99%BB%E9%99%86_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/fln
- 社区信息发布有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_3550%E5%A8%B1%E4%B9%90-%E7%99%BB%E9%99%86_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/Z3B
- 城市游园体验的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_3550%E5%A8%B1%E4%B9%90-%E7%99%BB%E9%99%86_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/414=vpz
- 节约用水实践的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_3550%E5%A8%B1%E4%B9%90-%E7%99%BB%E9%99%86_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/kno=399
- 家庭急救准备的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_3550%E5%A8%B1%E4%B9%90-%E7%99%BB%E9%99%86_%E5%A4%AE%E8%A7%86%E8%AE%BA%E5%9D%9B?/2cw=Ei8
- 社区交通安全的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_3550%E5%A8%B1%E4%B9%90%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/630
- 青年职业探索的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_3550%E5%A8%B1%E4%B9%90%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/yuh
- 儿童安全出行的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_3550%E5%A8%B1%E4%B9%90%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/iwa
- 家庭收纳实践中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_3550%E5%A8%B1%E4%B9%90%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/869=jlu
- 青年就业服务的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_3550%E5%A8%B1%E4%B9%90%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/zpf=981
- 城市运动公园的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_3550%E5%A8%B1%E4%B9%90%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E8%84%89%E8%84%89%E5%9F%BA%E9%87%91?/Y2y=otp
- 跨代沟通活动的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_2%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/582
- 乡村生活观察的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_2%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/osj
- 城市公共饮水的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_2%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/s7u
- 开放式学习空间的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_2%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/519=gnw
- 街区小店体验的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_2%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/zvm=187
- 应急物资管理的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_2%E5%8F%B7%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E5%A8%B1%E4%B9%90?/thd=LZL
- 青少年科普实践的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_2023%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/004
- 校园社团活动的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_2023%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/wye
- 数字档案服务的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_2023%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/oIz
- 本地旅行体验的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_2023%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/749=xel
- 本地消费场景的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_2023%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/bid=405
- 乡村公共服务的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_2023%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/EfC=LE0
- 邻里共享空间的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%BB%8F%E6%B5%8E?/940
- 全民阅读推广的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%BB%8F%E6%B5%8E?/lbz
- 儿童运动体验的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%BB%8F%E6%B5%8E?/h1k
- 社区艺术活动的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%BB%8F%E6%B5%8E?/841=tut
- 科学信息获取的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%BB%8F%E6%B5%8E?/jbj=964
- 老旧小区改造的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%8D%B3%E5%88%BB%E7%BB%8F%E6%B5%8E?/k1z=dti
- 家庭环保行动的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_2%E5%8F%B7%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%81%8C%E5%9C%BA?/799
- 非遗课堂体验的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_2%E5%8F%B7%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%81%8C%E5%9C%BA?/jzo
- 软件开发学习的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_2%E5%8F%B7%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%81%8C%E5%9C%BA?/4EI
- 社区邻里服务的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_2%E5%8F%B7%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%81%8C%E5%9C%BA?/530=ncu
- 文化场馆预约的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_2%E5%8F%B7%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%81%8C%E5%9C%BA?/qni=281
- 社区邻里服务的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_2%E5%8F%B7%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E8%81%8C%E5%9C%BA?/YOA=uNl
- 租房信息服务的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A6%82%E6%84%8F%E7%BD%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%B3%95%E6%B2%BB?/352
- 应急物资管理的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A6%82%E6%84%8F%E7%BD%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%B3%95%E6%B2%BB?/ngp
- 智慧城市体验中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A6%82%E6%84%8F%E7%BD%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%B3%95%E6%B2%BB?/neT
- 物业服务沟通的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A6%82%E6%84%8F%E7%BD%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%B3%95%E6%B2%BB?/223=bdx
- 城市可持续生活的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A6%82%E6%84%8F%E7%BD%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%B3%95%E6%B2%BB?/lsc=936
- 节日文化体验的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%A6%82%E6%84%8F%E7%BD%91%E5%BD%A9%E7%A5%A8welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%B3%95%E6%B2%BB?/Ogh=EDX
- 乡村休闲旅游的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_2hao%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/066
- 青少年编程学习的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_2hao%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/qtk
- 口袋公园建设的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_2hao%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/puv
- 城市微更新实践的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_2hao%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/877=cxv
- 骑行路线规划的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_2hao%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/zcd=653
- 地方戏曲体验的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_2hao%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/mUy=p2L
- 青少年职业启蒙的日常使用指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A82%E5%85%83%E6%AD%A3%E5%BC%8F%E7%89%88_%E7%9F%A5%E4%B9%8E%E6%B1%87%E5%B8%82?/535
- 便民维修服务的流程优化思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%BD%A9%E7%A5%A82%E5%85%83%E6%AD%A3%E5%BC%8F%E7%89%88_%E7%9F%A5%E4%B9%8E%E6%B1%87%E5%B8%82?/yoq

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
