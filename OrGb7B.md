# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:26**

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

- 传统节日科普的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9app_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/737
- 本地旅行体验的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9app_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/btv
- 城市应急广播的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9app_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/INg
- 社区艺术活动中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9app_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/527=rdl
- 社区公共餐饮的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9app_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/fch=532
- 图书馆亲子空间的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9app_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/8BQ=yEk
- 城市绿道建设的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/803
- 就业技能培训的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/uct
- 地方戏曲体验的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/EfA
- 绿色生活实践有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/916=byl
- 街区道路维护的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/msu=507
- 传统手工艺体验的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E5%A4%B4%E6%9D%A1?/bj0=aeJ
- 青年志愿活动的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/467
- 社区体育组织的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/zak
- 公共图书馆服务的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/FRG
- 电子商务服务的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/737=xhw
- 城市可持续生活的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/vpr=539
- 社区运动空间的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E8%AE%BA%E5%9D%9B?/Pcn=YAN
- 家庭园艺实践的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/640
- 个人信息保护的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/svh
- 社区心理支持的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/f2R
- 社区体育组织中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/319=amf
- 环境教育课程的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/oxj=022
- 儿童阅读角的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%AE%B6%E5%B1%85?/JDA=mWd
- 家庭教育交流的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-APP_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/078
- 小微企业服务的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-APP_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/pna
- 社区儿童活动的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-APP_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/LZ4
- 便民维修服务的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-APP_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/463=afs
- 文化讲座服务的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-APP_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/bky=615
- 全民阅读推广的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-APP_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/5Mv=VpM
- 数字课堂应用的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/406
- 公共设施维护有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/zri
- 读书会组织的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/she
- 城市文明实践的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/179=uqb
- 家庭网络使用的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/kbw=154
- 乡村文化活动的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/qm7=Lae
- 公共服务指南的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/842
- 儿童户外活动的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/loj
- 社区交通安全的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/Z2q
- 老年人日常照护的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/337=xlk
- 数字生活课堂的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/wtm=601
- 社区便利生活的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%BE%8E%E8%82%A1?/0MN=sCI
- 城市夜间照明的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/808
- 基层健康服务的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/aeh
- 骑行路线规划的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/agG
- 社区艺术活动的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/994=lqk
- 线上阅读资源的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/syl=668
- 家庭安全提示的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/SEP=tw2
- 城市文明实践有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E6%B1%BD%E8%BD%A6?/111
- 食品安全科普的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E6%B1%BD%E8%BD%A6?/jfl
- 城乡公共服务的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E6%B1%BD%E8%BD%A6?/v1f
- 气象科普传播的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E6%B1%BD%E8%BD%A6?/784=lgg
- 城市步行友好的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E6%B1%BD%E8%BD%A6?/cxt=338
- 城市夜间生活的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E6%B1%BD%E8%BD%A6?/pt9=ar8
- 社区文化节活动的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB?/971
- 家庭食品保存的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB?/pji
- 公共服务数字化的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB?/O7E
- 城市可持续生活的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB?/310=hua
- 城市体育设施的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB?/zug=980
- 城乡交流活动的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%B3%E5%88%BB?/wd3=vIf
- 公共服务数字化的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E9%97%AE%E7%AD%94?/966
- 城市空气科普的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E9%97%AE%E7%AD%94?/zgb
- 城市文化路线的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E9%97%AE%E7%AD%94?/L3v
- 公共场馆服务有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E9%97%AE%E7%AD%94?/491=gwh
- 节能家电使用的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E9%97%AE%E7%AD%94?/kln=152
- 运动安全知识的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%BE%8E%E6%B9%83%E9%97%AE%E7%AD%94?/HTH=nLP
- 数字设备回收的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E5%8E%86%E5%8F%B2?/185
- 地方旅游导览的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E5%8E%86%E5%8F%B2?/pwu
- 智能家居应用的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E5%8E%86%E5%8F%B2?/xCi
- 社区商业活力的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E5%8E%86%E5%8F%B2?/012=ttb
- 居家适老化改造的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E5%8E%86%E5%8F%B2?/mua=181
- 老年人文化生活的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E5%8E%86%E5%8F%B2?/PGs=f4Q
- 人工智能科普的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/906
- 邻里互助活动的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/ppr
- 家庭用电安全的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/i6L
- 公共文化活动的学习资源整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/202=mrj
- 地方旅游导览中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/qvv=968
- 公交站点体验的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%A1%85%E8%B0%B7%E8%B4%A2%E7%BB%8F?/eRg=cKp
- 物业服务沟通的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E9%A6%96%E9%A1%B5_360%E6%99%A8%E6%8A%A5?/061
- 地方美食文化的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E9%A6%96%E9%A1%B5_360%E6%99%A8%E6%8A%A5?/txj
- 小区电梯维护的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E9%A6%96%E9%A1%B5_360%E6%99%A8%E6%8A%A5?/9OE
- 物业服务沟通的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E9%A6%96%E9%A1%B5_360%E6%99%A8%E6%8A%A5?/545=wnm
- 小区公共照明的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E9%A6%96%E9%A1%B5_360%E6%99%A8%E6%8A%A5?/zzv=614
- 家庭环保习惯的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E9%A6%96%E9%A1%B5_360%E6%99%A8%E6%8A%A5?/LkX=6To
- 城市空气科普的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E5%AE%A0%E7%89%A9?/379
- 社区绿色空间的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E5%AE%A0%E7%89%A9?/nuw
- 公共场所导视的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E5%AE%A0%E7%89%A9?/Vpt
- 城市文化路线的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E5%AE%A0%E7%89%A9?/588=syu
- 智慧停车服务的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E5%AE%A0%E7%89%A9?/sul=970
- 休闲运动入门的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9_%E5%87%A4%E5%87%B0%E5%AE%A0%E7%89%A9?/y38=opJ
- 便民服务地图的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%98%9F%E8%BE%B0%E8%B4%A2%E7%BB%8F?/886
- 公共服务预约的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%98%9F%E8%BE%B0%E8%B4%A2%E7%BB%8F?/cef
- 老旧小区改造的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%98%9F%E8%BE%B0%E8%B4%A2%E7%BB%8F?/nEj
- 乡村生活观察的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%98%9F%E8%BE%B0%E8%B4%A2%E7%BB%8F?/895=ttf
- 节约用水实践有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%98%9F%E8%BE%B0%E8%B4%A2%E7%BB%8F?/djz=354
- 就业技能培训的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%98%9F%E8%BE%B0%E8%B4%A2%E7%BB%8F?/wp4=424
- 消防知识宣传的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/538
- 城市游园体验的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/llz
- 社区协商议事的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/ubc
- 城市便民驿站的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/833=tuw
- 城市体育设施的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/gvg=903
- 家庭消费规划的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B4%A2%E7%BB%8F?/jyH=Npx
- 基层健康服务中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%AF%BB%E5%9B%BE?/858
- 社区活动策划的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%AF%BB%E5%9B%BE?/mfc
- 城市噪声观察的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%AF%BB%E5%9B%BE?/GmI
- 青年职业探索的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%AF%BB%E5%9B%BE?/350=xqq
- 环境监测科普的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%AF%BB%E5%9B%BE?/dlk=697
- 城市绿色交通的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E8%AF%BB%E5%9B%BE?/q8f=dmR
- 老年人日常照护的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%A1%8C%E6%83%85?/942
- 城市公共自行车的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%A1%8C%E6%83%85?/otf
- 健康饮水科普的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%A1%8C%E6%83%85?/LIz
- 周末休闲规划的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%A1%8C%E6%83%85?/179=mdl
- 便民维修服务的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%A1%8C%E6%83%85?/agz=208
- 社区老年食堂的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E8%A1%8C%E6%83%85?/BJY=Vrh
- 健康步道使用的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%BD%B1%E8%A7%86?/828
- 机器学习入门的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%BD%B1%E8%A7%86?/cqw
- 城乡交流活动的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%BD%B1%E8%A7%86?/e2E
- 城市噪声观察的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%BD%B1%E8%A7%86?/247=ozd
- 家庭用电安全从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%BD%B1%E8%A7%86?/bvi=082
- 灵活就业交流的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E5%BD%B1%E8%A7%86?/0Lq=nKx
- 家庭环保习惯的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/330
- 小微企业服务的学习资源整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/yew
- 社区庭院绿化的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/IzA
- 社区生活指南的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/887=bih
- 社区便利生活的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/qrv=654
- 社区环保活动从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B8%E6%B3%95?/nX2=wut
- 基层服务创新的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%99%A8%E6%8A%A5?/510
- 城市公共标识的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%99%A8%E6%8A%A5?/bcr
- 志愿服务平台的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%99%A8%E6%8A%A5?/We6
- 城市文化路线的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%99%A8%E6%8A%A5?/231=enp
- 图书馆亲子空间的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%99%A8%E6%8A%A5?/zyr=044
- 开放式学习空间的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%99%A8%E6%8A%A5?/Uqb=Rvk
- 节能家电使用的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E6%96%87%E5%BA%93?/304
- 数字生活课堂的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E6%96%87%E5%BA%93?/uyv
- 社区文化节活动的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E6%96%87%E5%BA%93?/edl
- 绿色快递包装中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E6%96%87%E5%BA%93?/890=owh
- 青少年职业启蒙从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E6%96%87%E5%BA%93?/sfa=794
- 城市公共艺术的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E6%96%87%E5%BA%93?/8pj=epT
- 城市应急科普有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/369
- 社区应急准备的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/hfv
- 学校食育活动的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/828
- 亲子阅读活动的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/148=zlr
- 新能源出行的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/lqq=417
- 节气饮食文化的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E8%AE%BA%E5%9D%9B?/lsf=M8C
- 社区公共餐饮的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/289
- 数字课堂应用的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/wfu
- 乡村生活观察的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/332
- 数字便民地图的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/990=syy
- 社区菜市场服务的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/tri=852
- 读书会组织的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/4zl=i81
- 租房信息服务的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F?/954
- 公共设施使用的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F?/drf
- 社区活动报名的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F?/ie5
- 社区故事采集的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F?/760=aik
- 街区绿化养护的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F?/cpj=429
- 社区环保活动的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E5%AF%8C%E8%B4%A2%E7%BB%8F?/utr=O3r
- 公共服务沟通的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-APP_%E5%93%94%E5%93%A9%E6%B3%95%E5%BE%8B?/502
- 城市展览体验的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-APP_%E5%93%94%E5%93%A9%E6%B3%95%E5%BE%8B?/gkc
- 城市应急科普的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-APP_%E5%93%94%E5%93%A9%E6%B3%95%E5%BE%8B?/XT8
- 老旧小区改造的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-APP_%E5%93%94%E5%93%A9%E6%B3%95%E5%BE%8B?/203=kpw
- 儿童阅读角的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-APP_%E5%93%94%E5%93%A9%E6%B3%95%E5%BE%8B?/vei=639
- 城市噪声观察的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-APP_%E5%93%94%E5%93%A9%E6%B3%95%E5%BE%8B?/PhP=90M
- 社区文化节活动的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E9%A3%9F%E5%93%81?/223
- 科普展览体验的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E9%A3%9F%E5%93%81?/igl
- 数字地图应用的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E9%A3%9F%E5%93%81?/XKc
- 无障碍信息设计的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E9%A3%9F%E5%93%81?/686=jcr
- 便民维修服务的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E9%A3%9F%E5%93%81?/vju=784
- 社区邻里服务的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E9%A3%9F%E5%93%81?/p2S=APB
- 城市公共厕所的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/046
- 节能生活方式的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/cpn
- 信息无障碍体验的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/MYf
- 城市夜间照明的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/101=wkz
- 科学健身方法的学习资源整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/syg=567
- 城市夜间生活的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E7%A7%91%E6%8A%80?/m4f=5zE
- 数字艺术创作的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E5%8E%86%E5%8F%B2?/781
- 家庭节能设备的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E5%8E%86%E5%8F%B2?/ike
- 城市树木认养的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E5%8E%86%E5%8F%B2?/L1d
- 城市水环境观察的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E5%8E%86%E5%8F%B2?/384=xmf
- 社区故事采集的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E5%8E%86%E5%8F%B2?/cgn=422
- 城市便民驿站的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E5%8E%86%E5%8F%B2?/6SN=tF3
- 智能家居应用的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_360%E6%B1%BD%E8%BD%A6?/759
- 节日文化体验从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_360%E6%B1%BD%E8%BD%A6?/vfy
- 老旧小区改造的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_360%E6%B1%BD%E8%BD%A6?/1UB
- 绿色消费选择的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_360%E6%B1%BD%E8%BD%A6?/130=qeu
- 街区更新实践的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_360%E6%B1%BD%E8%BD%A6?/nxc=526
- 家庭教育交流的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_360%E6%B1%BD%E8%BD%A6?/rxr=M7H
- 公共交通信息服务的学习资源整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%90%AF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/150
- 社区手工活动的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%90%AF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/jes
- 青年志愿活动中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%90%AF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/d5Z
- 志愿服务平台的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%90%AF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/970=grw
- 城市展览体验的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%90%AF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/tys=752
- 智慧停车服务的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%90%AF%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ueo=lmk
- 安全出行教育的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E5%91%A8%E6%8A%A5?/713
- 社区艺术活动的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E5%91%A8%E6%8A%A5?/jjv
- 生活垃圾减量的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E5%91%A8%E6%8A%A5?/Lte
- 便民服务地图的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E5%91%A8%E6%8A%A5?/667=uoj
- 公交站点体验的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E5%91%A8%E6%8A%A5?/smq=039
- 课后服务体验的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E5%91%A8%E6%8A%A5?/auw=Hnp
- 零废弃生活尝试的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/252
- 节气饮食文化的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/nzc
- 创业经验分享的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/86L
- 环境监测科普的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/123=ucq
- 社区设施共享的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/ctg=477
- 家庭健康管理的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/we1=SfL
- 休闲运动入门的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/894
- 社区互助网络的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/fbe
- 社区垃圾回收的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/kDX
- 社区手工活动的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/830=vje
- 城乡交通衔接的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/chc=068
- 乡村公共服务的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/lSX=C9U
- 志愿服务平台的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/071
- 社区便民集市的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/ymi
- 城市绿道建设的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/Gvw
- 垃圾分类指导的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/720=dgc
- 城市人文观察中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/fjy=090
- 社区休闲设施的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%88%86%E6%83%85?/XXK=IFO
- 社区商业活力的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/124
- 社区环保活动的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/xjs
- 小区公共照明的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/SoH
- 居家适老化改造的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/076=mco
- 城市生活服务有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/mun=256
- 食品安全科普的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_%E6%98%9F%E6%B2%B3%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/XbV=cBJ
- 社区绿色空间的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/551
- 旧物循环利用的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/lhy
- 绿色消费选择的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/HTR
- 非遗体验活动的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/343=stj
- 城市夜间照明的学习资源整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/aos=007
- 文化场馆预约的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%8A%A8%E6%BC%AB?/HM9=lmj
- 市民意见收集的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%80%BA%E5%B8%82?/196
- 社区文化节活动的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%80%BA%E5%B8%82?/dgo
- 线上办事服务的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%80%BA%E5%B8%82?/gsj
- 公共服务沟通的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%80%BA%E5%B8%82?/470=vst
- 新能源出行的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%80%BA%E5%B8%82?/xxy=219
- 开放数据应用的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E5%80%BA%E5%B8%82?/PZv=whQ
- 乡村公共服务的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/392
- 生活垃圾回收的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/fhf
- 垃圾分类指导的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/BKn
- 垃圾分类指导的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/803=lgi
- 数字课堂应用的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/dyv=409
- 家庭环保习惯有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%A7%82%E5%AF%9F?/Ekn=5rn
- 社区宣传栏更新的使用门槛与改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E7%BE%8E%E5%A6%86?/346
- 便民维修服务的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E7%BE%8E%E5%A6%86?/eys
- 公园休闲体验的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E7%BE%8E%E5%A6%86?/aO9
- 城市步行环境的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E7%BE%8E%E5%A6%86?/329=inb
- 食品安全科普的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E7%BE%8E%E5%A6%86?/lim=787
- 社区公共餐饮的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E7%BE%8E%E5%A6%86?/5Oe=YQ5
- 社区协商议事的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%85%A7%E7%9C%BC?/843
- 劳动教育实践从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%85%A7%E7%9C%BC?/ess
- 社区养老服务的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%85%A7%E7%9C%BC?/Zwc
- 家庭阅读计划的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%9A%E6%8A%95%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E6%85%A7%E7%9C%BC?/767=mwu

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
