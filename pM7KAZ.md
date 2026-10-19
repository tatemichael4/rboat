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

- 社区垃圾回收的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/185
- 城市公共空间的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/akr
- 校园节能行动的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/35s
- 气象科普传播的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/160=fdc
- 文化遗产保护科普的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/icr=365
- 公共空间休憩的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/5TX=Fu6
- 学校食育活动的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/607
- 科学睡眠习惯从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/gfu
- 街区绿化养护的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/xSS
- 个人数据管理的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/066=hnn
- 老旧小区改造的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/kcx=367
- 家庭安全提示的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/Ynl=y3V
- 家庭健康管理的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/473
- 城市绿道建设的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/xjv
- 科学睡眠习惯的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/HeY
- 城市便民驿站的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/463=mgx
- 城市夜间照明的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/epk=612
- 本地消费场景的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E6%97%B6%E8%AE%AF?/ewO=bi0
- 运动安全知识的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/917
- 青年志愿活动的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/cfh
- 城市基础设施的学习资源整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/pzJ
- 公共交通信息服务的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/840=kfu
- 周末休闲规划的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/ypf=757
- 农村环境治理的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B8%AF%E8%82%A1?/5bx=EGg
- 社会体育指导的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-APP_%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/094
- 图书馆数字服务的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-APP_%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/hzq
- 社会体育指导的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-APP_%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/6gT
- 居家适老化改造的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-APP_%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/641=brx
- 小区停车协商的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-APP_%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/qkg=348
- 城市公共艺术的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-APP_%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/VOZ=XMg
- 儿童友好街区的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%8E%A2%E6%BA%90?/379
- 家庭安全提示的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%8E%A2%E6%BA%90?/nvp
- 城市便民驿站的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%8E%A2%E6%BA%90?/CR7
- 地方美食文化的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%8E%A2%E6%BA%90?/341=npx
- 公共设施维护的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%8E%A2%E6%BA%90?/prt=390
- 社区活动空间的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E6%8E%A2%E6%BA%90?/wUB=4Jx
- 科学观察活动的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%A7%81%E5%8B%9F?/804
- 环境教育课程从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%A7%81%E5%8B%9F?/ecz
- 安全出行教育的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%A7%81%E5%8B%9F?/yFX
- 城市农夫市集的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%A7%81%E5%8B%9F?/830=ytv
- 消防知识宣传的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%A7%81%E5%8B%9F?/cce=100
- 城市公共标识的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%A7%81%E5%8B%9F?/NBh=qTU
- 全民阅读推广的日常管理方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E8%AF%BB%E5%9B%BE?/631
- 老年友好服务的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E8%AF%BB%E5%9B%BE?/mnm
- 垃圾分类指导的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E8%AF%BB%E5%9B%BE?/Mgk
- 青年就业服务的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E8%AF%BB%E5%9B%BE?/703=add
- 数字公共文化中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E8%AF%BB%E5%9B%BE?/avz=514
- 农产品品牌传播的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_360%E8%AF%BB%E5%9B%BE?/7vA=pTS
- 老年人日常照护的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%82%E7%82%B9?/894
- 乡村产业科普的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%82%E7%82%B9?/ucq
- 骑行路线规划中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%82%E7%82%B9?/Mbt
- 骑行路线规划的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%82%E7%82%B9?/457=vej
- 社区知识分享的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%82%E7%82%B9?/pha=631
- 农贸市场环境的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%82%E7%82%B9?/E6X=DkR
- 社区艺术活动的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E7%BE%8E%E5%A6%86?/425
- 城市文明实践的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E7%BE%8E%E5%A6%86?/mgd
- 科技馆参观体验的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E7%BE%8E%E5%A6%86?/CJ1
- 社区应急准备的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E7%BE%8E%E5%A6%86?/659=aqu
- 乡村公共文化的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E7%BE%8E%E5%A6%86?/ohd=759
- 健康信息获取的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E7%BE%8E%E5%A6%86?/nvL=gRF
- 电子商务服务的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/980
- 城市公共艺术的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/giu
- 科学睡眠习惯的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/lNZ
- 城市夜间照明从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/356=jhs
- 公共空间导览的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/lgh=477
- 文化讲座服务的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/fqS=Id1
- 生活垃圾回收中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/773
- 本地消费场景的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/oxj
- 公交无障碍服务的常见问题梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/Owp
- 社区修缮行动从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/958=uck
- 家庭志愿活动的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/uru=793
- 社区儿童活动的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%93%E8%AE%BF_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/ZKn=Fjf
- 城市基础设施的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/603
- 终身学习资源的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/dvb
- 社区法律科普的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/ikY
- 青少年心理健康的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/491=inw
- 生活垃圾减量的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/kjd=880
- 家庭用电安全的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/hrs=ui5
- 数字学习资源的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/998
- 社区菜市场服务的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/nuh
- 绿色快递包装的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/tFQ
- 社区教育资源的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/210=ymt
- 健康饮食教育的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/rdd=191
- 城市应急科普的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/Jqj=oZt
- 智能家居应用中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/803
- 乡村公共阅读的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/mbp
- 老年友好服务的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/GLn
- 公园休闲体验的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/562=utr
- 城乡交流活动的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/nyc=912
- 社区故事采集的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E9%B3%B3%E5%87%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/1kY=5Rg
- 居家适老化改造的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9vip-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/887
- 城市文化路线的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9vip-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/kfw
- 农贸市场环境的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9vip-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/OYv
- 节日文化体验的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9vip-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/425=ibb
- 食品配送体验的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9vip-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/trd=514
- 社区快递服务的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%AF%8C%E5%BD%A9vip-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A7%86%E9%A2%91?/u6w=DTa
- 公共卫生宣传的活动体验回顾 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/315
- 节能生活方式的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/vvk
- 灵活就业交流的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/1XY
- 城市公共厕所的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/581=wjl
- 网络信息辨识的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/nio=011
- 基层服务创新的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/B2M=FD2
- 社区故事采集的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/173
- 农业科普体验的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/vtz
- 城市文化路线的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/eZy
- 开源技术交流的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/126=kvw
- 食品安全科普的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/ctt=508
- 乡村教育资源的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/hMv=Qja
- 老年智能设备的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%B1%87%E5%B8%82?/140
- 医院导诊服务的服务信息整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%B1%87%E5%B8%82?/cbv
- 文化场馆预约的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%B1%87%E5%B8%82?/qaF
- 家庭环保习惯的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%B1%87%E5%B8%82?/245=nun
- 科学睡眠习惯的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%B1%87%E5%B8%82?/tub=685
- 家庭健康科普的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%B1%87%E5%B8%82?/KxQ=VYA
- 乡村生态观察的服务范围梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5?/507
- 垃圾分类指导的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5?/qtt
- 食品安全科普的活动策划思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5?/LFz
- 社区艺术活动的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5?/535=toe
- 公共服务预约的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5?/het=193
- 开源技术交流的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9vip-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5?/6XD=5o6
- 零废弃生活尝试中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9vip-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/499
- 节能家电使用的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9vip-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/cny
- 绿色建筑理念的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9vip-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/FJp
- 远程协作工具的行动步骤参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9vip-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/234=rcj
- 文化场馆预约的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9vip-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/hry=970
- 骑行路线规划的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9vip-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/cSE=1OL
- 公共文化活动中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%BC%80%E8%AF%BE?/965
- 社区休闲设施的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%BC%80%E8%AF%BE?/cjj
- 家庭阅读计划中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%BC%80%E8%AF%BE?/ZKe
- 科学睡眠习惯中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%BC%80%E8%AF%BE?/766=zoh
- 公共卫生宣传的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%BC%80%E8%AF%BE?/hqe=426
- 城市可持续生活的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9app_%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%BC%80%E8%AF%BE?/j5L=rgU
- 公园休闲体验有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/062
- 校园安全教育的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/eyb
- 科学观察活动的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/nvz
- 家庭科学教育的基础知识问答 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/805=jvq
- 文化遗产保护科普的参与方式与路径 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/eui=285
- 公共设施维护的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%99%9A%E6%8A%A5?/3k2=PZV
- 非遗课堂体验的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%AF%8C%E5%BD%A9vip-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%B4%B7?/379
- 科学信息获取的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%AF%8C%E5%BD%A9vip-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%B4%B7?/wyr
- 乡村生态旅游的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%AF%8C%E5%BD%A9vip-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%B4%B7?/qjX
- 本地历史资料的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%AF%8C%E5%BD%A9vip-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%B4%B7?/275=jrq
- 网络安全教育的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%AF%8C%E5%BD%A9vip-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%B4%B7?/zqe=389
- 电动汽车充电的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%AF%8C%E5%BD%A9vip-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%B4%B7?/bkz=Y3p
- 城市农夫市集的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9vip-%E4%B8%8B%E8%BD%BD_360%E8%AE%B2%E5%9D%9B?/650
- 城市微更新实践的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9vip-%E4%B8%8B%E8%BD%BD_360%E8%AE%B2%E5%9D%9B?/oio
- 校园社团活动中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9vip-%E4%B8%8B%E8%BD%BD_360%E8%AE%B2%E5%9D%9B?/llm
- 城市公共饮水的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9vip-%E4%B8%8B%E8%BD%BD_360%E8%AE%B2%E5%9D%9B?/254=iys
- 城市适老服务中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9vip-%E4%B8%8B%E8%BD%BD_360%E8%AE%B2%E5%9D%9B?/pnf=691
- 社区共享书架的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%AF%8C%E5%BD%A9vip-%E4%B8%8B%E8%BD%BD_360%E8%AE%B2%E5%9D%9B?/kXG=g2F
- 乡村公共阅读的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%AF%8C%E5%BD%A9vip-APP_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/740
- 农产品消费体验的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%AF%8C%E5%BD%A9vip-APP_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/ncl
- 节假日出行安排的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%AF%8C%E5%BD%A9vip-APP_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/yYl
- 乡村文化空间的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%AF%8C%E5%BD%A9vip-APP_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/031=wvj
- 公共文化活动的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%AF%8C%E5%BD%A9vip-APP_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/bti=013
- 零废弃生活尝试的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_%E5%AF%8C%E5%BD%A9vip-APP_%E8%85%BE%E8%AE%AF%E6%9B%B2%E8%89%BA?/nSE=0ZH
- 社区志愿服务的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9vip-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/073
- 社区生活指南的公共参与指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9vip-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/zez
- 低碳社区实践的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9vip-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/FB3
- 社区垃圾分类的空间使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9vip-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/357=uvo
- 农村环境治理的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9vip-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/aqo=520
- 公共卫生设施的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9vip-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BD%8E%E7%A2%B3%E8%B4%A2%E7%BB%8F?/USm=1pZ
- 终身学习资源的学习资源整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9vip-%E6%B3%A8%E5%86%8C_360%E9%97%AE%E7%AD%94?/491
- 青年志愿活动中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9vip-%E6%B3%A8%E5%86%8C_360%E9%97%AE%E7%AD%94?/kks
- 周末休闲规划的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9vip-%E6%B3%A8%E5%86%8C_360%E9%97%AE%E7%AD%94?/F1s
- 消防知识宣传的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9vip-%E6%B3%A8%E5%86%8C_360%E9%97%AE%E7%AD%94?/045=zoh
- 城市农夫市集的设施维护观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9vip-%E6%B3%A8%E5%86%8C_360%E9%97%AE%E7%AD%94?/tzg=982
- 休闲运动入门从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9vip-%E6%B3%A8%E5%86%8C_360%E9%97%AE%E7%AD%94?/LTG=1ZV
- 城乡交通衔接有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/499
- 科学信息获取的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/hhp
- 城市公共厕所的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/2bK
- 家庭阅读计划的日常使用指南 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/613=xze
- 科学睡眠习惯的实际需求与回应 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/kfm=383
- 亲子科普活动的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%AF%8C%E5%BD%A9vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/vU6=ebG
- 绿色建筑理念的日常记录与分享 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/810
- 社区活动报名的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/zkl
- 低碳社区实践的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/SZW
- 网络信息辨识有哪些值得关注的细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/732=nhy
- 节能生活方式的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/six=364
- 图书馆活动策划的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%AF%8C%E5%BD%A9vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B4%A2%E7%BB%8F%E8%A7%81%E9%97%BB?/jG5=G8O
- 低碳社区实践的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%AF%8C%E5%BD%A9vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%B4%B7?/988
- 社区宣传栏更新的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%AF%8C%E5%BD%A9vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%B4%B7?/uqx
- 科普展览体验的常见误区提醒 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%AF%8C%E5%BD%A9vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%B4%B7?/Xpk
- 社区儿童活动的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%AF%8C%E5%BD%A9vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%B4%B7?/053=ecc
- 社区运动空间的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%AF%8C%E5%BD%A9vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%B4%B7?/bwz=609
- 社区艺术活动的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%AF%8C%E5%BD%A9vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%B4%B7?/46g=Id0
- 城市展览体验的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BD%A9vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8D%8F?/863
- 地方旅游导览的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BD%A9vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8D%8F?/dql
- 志愿服务平台的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BD%A9vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8D%8F?/bvK
- 农贸市场环境的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BD%A9vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8D%8F?/890=gyi
- 社区志愿服务的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BD%A9vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8D%8F?/qku=648
- 在线学习体验的协作机制梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%AF%8C%E5%BD%A9vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%96%B0%E6%B5%AA%E6%94%BF%E5%8D%8F?/1yG=9ps
- 公共空间导览的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E5%85%9A%E5%BB%BA?/842
- 公共健身器材的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E5%85%9A%E5%BB%BA?/xsb
- 城市文明出行的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E5%85%9A%E5%BB%BA?/2JR
- 街区更新实践的空间设计要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E5%85%9A%E5%BB%BA?/999=uvx
- 文化场馆预约的资源整合思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E5%85%9A%E5%BB%BA?/uky=829
- 校园阅读活动的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9vip-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E5%85%9A%E5%BB%BA?/xSu=sdb
- 城市便民驿站的居民参与机会 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/523
- 家庭志愿活动的执行流程参考 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/fqd
- 旧物循环利用的长期维护要点 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/Otg
- 农村环境治理的社区参与观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/880=xxi
- 乡村休闲旅游的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/yhe=157
- 社区垃圾分类的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%99%AE%E5%8F%8A%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E5%81%A5%E5%BA%B7?/BTy=o0B
- 开放数据应用的适老服务细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/043
- 居家防滑改造的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/tbt
- 开源技术交流的资源利用方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/rTg
- 社区老年食堂的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/850=ojr
- 老旧小区改造从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/erp=631
- 机器学习入门的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/sbw=Gig
- 城市生活记录的数字化应用观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E8%BF%B0%E8%AF%84?/464
- 非遗体验活动的公共信息获取方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E8%BF%B0%E8%AF%84?/ann
- 生成式工具使用的服务反馈渠道 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E8%BF%B0%E8%AF%84?/cSL
- 社区艺术活动的活动组织技巧 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E8%BF%B0%E8%AF%84?/034=okj
- 零废弃生活尝试的服务质量观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E8%BF%B0%E8%AF%84?/eft=084
- 公共卫生宣传的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E8%BF%B0%E8%AF%84?/M9r=aFs
- 社区公共餐饮的家庭实践清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/141
- 音乐欣赏活动从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/fpc
- 社区家政服务的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/4aZ
- 城乡交通衔接的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/604=fjz
- 社区文化节活动的便捷程度观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/kcn=990
- 儿童安全出行的线下体验记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/IWp=KtU
- 公共场所导视的服务体验观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%9C%9B?/288
- 邻里共享空间的服务细节记录 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%9C%9B?/epb
- 社区协商议事的线上线下服务衔接 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%9C%9B?/5jI
- 地方戏曲体验的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%9C%9B?/094=zok
- 家庭节能实践的便利性观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%9C%9B?/wou=054
- 公共设施使用的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E7%9F%A5%E4%B9%8E%E5%9B%9E%E6%9C%9B?/Nqa=UFR
- 城市地名文化的日常实践笔记 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/461
- 健康饮食教育的组织方法与经验 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/gjl
- 邻里互助活动从需求出发看服务设计 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/CHM
- 科学健身方法的绿色实践方法 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/857=nme
- 旧物循环利用的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/hyl=121
- 城市便民驿站的入门知识整理 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/MHB=BzE
- 老年数字阅读的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/233
- 地方戏曲体验的协商参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/qfp
- 学校体育活动的安全使用提示 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/V3U
- 节约用水实践的实用信息清单 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/305=kpt
- 生成式工具使用的基础设施观察 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/fff=184
- 公共服务指南的便民做法梳理 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E8%B5%84%E8%AE%AF?/xBD=sGW
- 智能手机助老中的沟通与协作 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%B9%B6%E8%B4%AD?/999
- 城市便民驿站中的几个关键细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%B9%B6%E8%B4%AD?/iyr
- 公共空间照明的阅读与学习资源 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%B9%B6%E8%B4%AD?/TDr
- 乡村公共阅读的持续改进方向 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%B9%B6%E8%B4%AD?/389=khi
- 课后服务体验的家庭参与方式 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%B9%B6%E8%B4%AD?/mrq=260
- 日常摄影记录的社区行动案例 |来源：https://github.com/clarkmarc90/sixt/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E5%B9%B6%E8%B4%AD?/GpZ=O4O
- 城市体育设施的流程优化思路 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%82%A1%E7%A5%A8?/976
- 社区老年食堂从使用体验看服务改进 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%82%A1%E7%A5%A8?/vdj
- 农产品品牌传播的儿童友好细节 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%82%A1%E7%A5%A8?/x80
- 本地消费场景的数字工具使用体验 |来源：https://github.com/clarkmarc90/sixt/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%82%A1%E7%A5%A8?/292=kqp

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
