# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:27**

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

- 机器人科普活动的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/wqq=254
- 邻里共享空间的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%B4%A2%E7%BB%8F?/N32=EOu
- 社区活动报名的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/367
- 城市便民驿站的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/rja
- 数字生活课堂的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/oeR
- 小区电梯维护的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/176=lsg
- 电动汽车充电的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/wwa=625
- 公共服务指南的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/Jlt=80F
- 社区休闲设施的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/557
- 城市文化路线的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/sfk
- 城市博物馆活动的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/xtb
- 社区垃圾分类的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/634=zqb
- 市民热线服务的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/uhp=018
- 基层健康服务的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/IXG=GVg
- 社区绿色空间的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/530
- 便民维修服务的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/fvv
- 青少年科技社团的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/ilc
- 青年就业服务的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/166=kgj
- 社区活动报名的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/oje=692
- 社区慢性病防控的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%9B%98%E7%82%B9?/qsE=8zy
- 城市公共艺术的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/690
- 社区健康讲座的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/twk
- 社区心理支持的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/onx
- 社区修缮行动的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/302=zwp
- 文化遗产保护科普的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/mus=556
- 社区环保活动从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/NHJ=FFK
- 数字便民地图的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/487
- 远程协作工具的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/urs
- 绿色快递包装的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/n64
- 志愿者培训交流的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/340=yyk
- 乡村生态旅游的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/aip=574
- 家庭收纳实践的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/tRc=I4Y
- 社区法律科普的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/789
- 家庭防灾准备的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/iny
- 家庭阅读计划中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/tBF
- 地方旅游导览有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/947=lzh
- 校园社团活动的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/jqa=506
- 智慧城市体验的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/6Os=d2f
- 家庭防灾准备的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%B8%AF%E8%82%A1?/370
- 城市文明出行的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%B8%AF%E8%82%A1?/oil
- 科学运动指导的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%B8%AF%E8%82%A1?/lSO
- 城市应急科普的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%B8%AF%E8%82%A1?/493=lhd
- 社区艺术活动的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%B8%AF%E8%82%A1?/gvu=007
- 公共服务评价的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%B8%AF%E8%82%A1?/A3F=6iN
- 社区防暑服务的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/003
- 居民健康教育的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/jri
- 急救知识普及从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/ClR
- 儿童阅读角的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/054=jck
- 安全出行教育的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/rnh=982
- 城市夜间照明的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9C%B0%E4%BA%A7?/aSP=3tU
- 城市地名文化的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/156
- 家庭阅读计划的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/ebn
- 社区艺术活动的学习资源整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/LXW
- 城市公共饮水的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/855=ztu
- 城市慢跑路线的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/gxi=014
- 乡村电商实践的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F?/18r=WWR
- 社区便利生活的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/529
- 社区儿童活动的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/apt
- 乡村公共服务的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/UkC
- 城市博物馆服务的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/845=ebb
- 公共场馆服务的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/kdh=728
- 图书馆亲子空间的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/3Li=gJV
- 儿童阅读角从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%99%9A%E6%8A%A5?/364
- 乡村文化空间的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%99%9A%E6%8A%A5?/emm
- 学校食育活动的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%99%9A%E6%8A%A5?/KDH
- 便民维修服务的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%99%9A%E6%8A%A5?/374=vwd
- 城市生活服务的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%99%9A%E6%8A%A5?/ypg=748
- 社区手工活动的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%99%9A%E6%8A%A5?/3E4=npi
- 劳动教育实践的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/992
- 公共空间休憩的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/cjo
- 生活服务数字化的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/szf
- 小微企业服务的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/496=xjq
- 家庭志愿活动的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/ryd=772
- 社区便民服务的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E7%91%9E%E8%B4%A2%E7%BB%8F?/qFN=PVR
- 乡村阅读活动的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%85%A7%E7%9C%BC?/819
- 家庭运动计划的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%85%A7%E7%9C%BC?/niw
- 农贸市场环境的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%85%A7%E7%9C%BC?/AZU
- 健康信息获取的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%85%A7%E7%9C%BC?/517=ugt
- 城市慢跑路线的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%85%A7%E7%9C%BC?/ena=870
- 在线教育体验的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%85%A7%E7%9C%BC?/Szp=qtg
- 节日文化体验的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/639
- 城市人文观察的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/yiw
- 劳动教育实践的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/0PI
- 个人时间管理的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/661=qqr
- 青年职业探索的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/gyf=030
- 儿童户外活动的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E5%86%9B%E4%BA%8B?/WEh=Vcg
- 社区公共餐饮的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/452
- 地方戏曲体验的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/uwk
- 公园亲子设施的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/Z1i
- 青年职业探索的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/257=odw
- 亲子科普活动的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/nhy=267
- 城市公共标识从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%90%AF%E8%88%AA%E5%9B%BD%E9%99%85%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E5%8F%B8%E6%B3%95?/bHi=oN8
- 城市文化路线中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%9C%88%E5%AD%90?/454
- 社区应急准备的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%9C%88%E5%AD%90?/eqx
- 数字资源检索的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%9C%88%E5%AD%90?/swY
- 读书会组织的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%9C%88%E5%AD%90?/912=fpu
- 数字支付体验的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%9C%88%E5%AD%90?/igw=572
- 儿童安全出行的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%9C%88%E5%AD%90?/geg=abb
- 职业技能学习的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%85%A7%E7%9C%BC?/714
- 地方民俗记录的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%85%A7%E7%9C%BC?/azt
- 小区停车协商的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%85%A7%E7%9C%BC?/Vhl
- 地方民俗记录的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%85%A7%E7%9C%BC?/996=myt
- 公园休闲体验的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%85%A7%E7%9C%BC?/dzm=170
- 绿色出行服务的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%85%A7%E7%9C%BC?/VnN=j7j
- 城市生活服务的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/475
- 城市雨天出行的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/pce
- 家庭节能实践的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/LDe
- 校园社团活动的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/174=uwr
- 居家防滑改造的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/jpv=279
- 城市微更新实践的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/07v=8L9
- 城市绿色交通的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8C%BB%E8%8D%AF?/357
- 数字课堂应用的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8C%BB%E8%8D%AF?/tjs
- 地方文化传播的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8C%BB%E8%8D%AF?/BhA
- 骑行路线规划的学习资源整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8C%BB%E8%8D%AF?/389=qxf
- 灵活就业交流的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8C%BB%E8%8D%AF?/tlf=596
- 健康信息获取的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8C%BB%E8%8D%AF?/4CG=JMZ
- 社区体育组织的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/802
- 社区读书角建设的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/khy
- 节气饮食文化的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/AAs
- 社区法律科普的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/944=mep
- 非遗体验活动的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/xjg=843
- 绿色办公实践的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%BA%B5%E6%A8%AA%E8%B4%A2%E7%BB%8F?/GeF=itW
- 城市绿色交通的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%81%A5%E8%BA%AB?/285
- 城市夜间照明的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%81%A5%E8%BA%AB?/rld
- 城市宠物友好空间的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%81%A5%E8%BA%AB?/VF6
- 城市水环境观察的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%81%A5%E8%BA%AB?/688=trh
- 机器学习入门的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%81%A5%E8%BA%AB?/ohy=300
- 图书馆活动策划的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%81%A5%E8%BA%AB?/5GS=ft7
- 公共卫生宣传的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E6%8A%A5?/079
- 绿色出行服务的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E6%8A%A5?/fzj
- 城市公共艺术有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E6%8A%A5?/EGE
- 社区快递服务的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E6%8A%A5?/292=zwc
- 食品配送体验有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E6%8A%A5?/yai=222
- 文明养宠科普的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E5%BF%AB%E6%8A%A5?/oY2=5IW
- 社区协商议事的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/075
- 街区道路维护的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/ohv
- 节约用水实践的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/fXf
- 机器人科普活动的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/351=zbu
- 网络安全教育的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/mbs=526
- 儿童运动体验的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/PON=DZk
- 环境监测科普的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/877
- 零废弃生活尝试的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/dmw
- 城市休闲步道的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/cfo
- 低碳社区实践的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/806=ard
- 社区便民集市的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/krf=909
- 公共服务沟通的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E8%B4%A2%E7%BB%8F?/NeS=sUF
- 公共图书馆服务的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/043
- 公共场所导视的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/ghn
- 城市应急广播的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/Nt4
- 家庭节能设备的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/165=scg
- 环境教育课程的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/ftn=163
- 城市夜间照明的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E6%88%B7%E5%A4%96?/Kjo=Gdk
- 街区更新实践的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/469
- 绿色生活实践的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/xqf
- 消防知识宣传的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/9wj
- 全民健身活动的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/716=fwf
- 地方美食文化的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/fpw=561
- 社区便民服务中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%85%9A%E5%BB%BA?/Mp2=C7V
- 科学教育活动的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-APP_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/792
- 图书馆亲子空间的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-APP_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/eju
- 社区环保活动的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-APP_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/ehl
- 公共服务沟通的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-APP_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/377=gye
- 节能家电使用的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-APP_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/bra=369
- 本地历史资料的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-APP_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/JIa=OFv
- 乡村公共文化的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/692
- 公共服务预约的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/aii
- 居家防滑改造的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/Smj
- 公共服务数字化的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/820=azv
- 社区垃圾回收的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/rbc=737
- 城市骑行环境的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%B1%BD%E8%BD%A6?/e2V=Ch4
- 城市公共标识的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E5%8D%B7?/163
- 社区商业活力的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E5%8D%B7?/jxm
- 节气饮食文化的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E5%8D%B7?/e6Y
- 小区停车协商的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E5%8D%B7?/073=aye
- 消防知识宣传的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E5%8D%B7?/emb=504
- 城乡公共服务的学习资源整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%97%AE%E5%8D%B7?/rF7=0eq
- 个人信息保护的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/109
- 公共卫生宣传的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/yyu
- 基层健康档案的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/xbZ
- 乡村公共文化的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/574=iqb
- 家庭阅读计划的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/onq=201
- 家庭理财科普的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%97%A5%E6%8A%A5?/D8e=rVP
- 小区停车协商的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/940
- 智能家居应用从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/iys
- 家庭节能设备的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/8dZ
- 社区艺术活动的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/027=tur
- 城市绿色交通的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/bne=353
- 职业技能学习的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B0%B7%E6%AD%8C%E8%A7%86%E9%A2%91?/8mV=X2c
- 居家防滑改造中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%B8%AF%E8%82%A1?/977
- 乡村文化活动的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%B8%AF%E8%82%A1?/oqu
- 老年人文化生活的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%B8%AF%E8%82%A1?/tiA
- 社区交通安全的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%B8%AF%E8%82%A1?/043=bbb
- 周末休闲规划的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%B8%AF%E8%82%A1?/kxy=756
- 农产品品牌传播的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B1%86%E7%93%A3%E6%B8%AF%E8%82%A1?/sfm=AbY
- 便民服务窗口的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/519
- 公共服务指南的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/nbn
- 个人时间管理的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/IVL
- 数字素养提升的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/979=drm
- 软件开发学习的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/msd=411
- 城市社区治理的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E7%9F%A5%E8%AF%86_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%98%E9%85%B7%E6%96%B0%E9%97%BB?/MsK=sNK
- 青年志愿活动的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/232
- 运动安全知识的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/vrv
- 社区志愿服务的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/SRw
- 通勤路线规划从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/421=xvs
- 周末休闲规划从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/oqt=701
- 节约用水实践的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%99%9A%E6%8A%A5?/AhI=ur4
- 城市水环境观察的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/236
- 城市慢跑路线的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/xnp
- 青少年编程学习中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/dCB
- 青少年科普实践的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/762=ffu
- 城市应急科普的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/rjw=171
- 公共卫生宣传的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/gaC=cQS
- 城市公共饮水的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%85%E6%B8%B8?/524
- 农产品消费体验的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%85%E6%B8%B8?/bqg
- 医院导诊服务的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%85%E6%B8%B8?/qgO
- 骑行路线规划的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%85%E6%B8%B8?/507=rqk
- 节气饮食文化的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%85%E6%B8%B8?/kwe=338
- 志愿者培训交流的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%85%E6%B8%B8?/5Q2=tYf
- 家庭教育交流中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E8%BD%AC%E8%BD%BD?/672
- 老年人出行服务的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E8%BD%AC%E8%BD%BD?/cad
- 街头绿植养护的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E8%BD%AC%E8%BD%BD?/Xt6
- 儿童阅读角的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E8%BD%AC%E8%BD%BD?/371=hjb
- 地方民俗记录的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E8%BD%AC%E8%BD%BD?/cng=317
- 城乡交流活动的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%93%94%E5%93%A9%E8%BD%AC%E8%BD%BD?/k1k=JJ9
- 社区环保活动的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/954
- 亲子阅读活动从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/omb
- 社区便利生活的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/820
- 社区故事采集的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/762=wfy
- 公共健身器材的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/zcy=212
- 城乡交流活动的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%BA%93?/cmb=6ZY
- 城市步行环境的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%81%A5%E8%BA%AB?/382
- 城市基础设施的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%81%A5%E8%BA%AB?/reb
- 公园无障碍服务的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%81%A5%E8%BA%AB?/58E
- 社区环保活动的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%81%A5%E8%BA%AB?/279=dkh
- 家庭节能实践的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%81%A5%E8%BA%AB?/eix=423
- 乡村生态旅游的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E5%81%A5%E8%BA%AB?/k75=ys2
- 社区活动报名的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/421
- 城市博物馆活动的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/gnf
- 街头绿植养护的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/7Dk
- 城市骑行环境的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/635=bra
- 数字地图应用从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/dof=379
- 绿色消费选择的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/9fa=OQW
- 健康饮食教育的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/537
- 乡村产业科普的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/ash
- 开放式学习空间的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/bVt
- 社区科普课堂的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/622=tpk
- 城市生活服务的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/myx=691
- 数字课堂应用的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E7%95%85%E6%B8%B8?/DBh=0ZX
- 社区科普课堂的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E7%9B%98%E7%82%B9?/165
- 公共交通接驳的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%85%A8%E7%90%83%E8%B4%AD%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E7%9B%98%E7%82%B9?/omm

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
