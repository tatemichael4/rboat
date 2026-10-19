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

- 线上办事服务中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%87%A4%E5%87%B0vlI%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/Mxr
- 社区交通安全的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%87%A4%E5%87%B0vlI%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/372=hhl
- 生成式工具使用的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%87%A4%E5%87%B0vlI%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/bai=787
- 社区阅读服务有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%87%A4%E5%87%B0vlI%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/mMv=4ls
- 开放式学习空间的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0__%E8%B1%86%E7%93%A3%E7%BB%8F%E6%B5%8E?/851
- 城市夜间照明的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0__%E8%B1%86%E7%93%A3%E7%BB%8F%E6%B5%8E?/zmj
- 青年职业探索的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0__%E8%B1%86%E7%93%A3%E7%BB%8F%E6%B5%8E?/XJJ
- 生活垃圾回收的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0__%E8%B1%86%E7%93%A3%E7%BB%8F%E6%B5%8E?/816=tkq
- 家庭教育交流的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0__%E8%B1%86%E7%93%A3%E7%BB%8F%E6%B5%8E?/qgt=639
- 生活垃圾减量从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%87%A4%E5%87%B0vi%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0__%E8%B1%86%E7%93%A3%E7%BB%8F%E6%B5%8E?/Xg7=F6b
- 城市人文观察的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0V17%E8%B5%9E%E5%8A%A9%E7%A0%81_%E8%84%89%E8%84%89%E6%A1%A3%E6%A1%88?/064
- 家庭网络使用的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0V17%E8%B5%9E%E5%8A%A9%E7%A0%81_%E8%84%89%E8%84%89%E6%A1%A3%E6%A1%88?/vuu
- 社区环保活动的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0V17%E8%B5%9E%E5%8A%A9%E7%A0%81_%E8%84%89%E8%84%89%E6%A1%A3%E6%A1%88?/Mw9
- 环境教育课程的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0V17%E8%B5%9E%E5%8A%A9%E7%A0%81_%E8%84%89%E8%84%89%E6%A1%A3%E6%A1%88?/053=oel
- 家庭安全提示的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0V17%E8%B5%9E%E5%8A%A9%E7%A0%81_%E8%84%89%E8%84%89%E6%A1%A3%E6%A1%88?/oia=582
- 城市公共饮水的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0V17%E8%B5%9E%E5%8A%A9%E7%A0%81_%E8%84%89%E8%84%89%E6%A1%A3%E6%A1%88?/Y8o=ypx
- 家庭理财科普的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0V16%E8%B5%9E%E5%8A%A9%E5%90%97_%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/999
- 城乡公共服务的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0V16%E8%B5%9E%E5%8A%A9%E5%90%97_%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/wbv
- 城市绿色交通的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0V16%E8%B5%9E%E5%8A%A9%E5%90%97_%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/OMd
- 城市文化路线的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0V16%E8%B5%9E%E5%8A%A9%E5%90%97_%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/505=rcl
- 城市可持续生活的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0V16%E8%B5%9E%E5%8A%A9%E5%90%97_%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/xlh=021
- 科学教育活动的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0V16%E8%B5%9E%E5%8A%A9%E5%90%97_%E5%A4%AE%E8%A7%86%E8%AE%BF%E8%B0%88?/P7V=469
- 城市公共空间的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0V15_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/477
- 骑行路线规划的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0V15_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/vlw
- 志愿者培训交流的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0V15_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/L8T
- 社区便利生活的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0V15_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/360=qmw
- 食品安全科普的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0V15_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/qjl=672
- 公共空间照明的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%87%A4%E5%87%B0V15_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/29q=XZJ
- 社区手工活动的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0v17%E6%89%8B%E6%9C%BA%E7%89%88_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%94%BE?/418
- 社区宣传栏更新的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0v17%E6%89%8B%E6%9C%BA%E7%89%88_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%94%BE?/sel
- 图书馆活动策划的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0v17%E6%89%8B%E6%9C%BA%E7%89%88_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%94%BE?/Jdf
- 乡村休闲旅游的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0v17%E6%89%8B%E6%9C%BA%E7%89%88_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%94%BE?/724=ugs
- 公共服务预约的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0v17%E6%89%8B%E6%9C%BA%E7%89%88_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%94%BE?/rsu=454
- 城乡交通衔接的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%87%A4%E5%87%B0v17%E6%89%8B%E6%9C%BA%E7%89%88_%E8%85%BE%E8%AE%AF%E5%9B%9E%E6%94%BE?/pZE=YKy
- 公共服务评价的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%87%A4%E5%87%B0v18_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/187
- 职业技能学习的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%87%A4%E5%87%B0v18_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/zib
- 文化遗产保护科普的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%87%A4%E5%87%B0v18_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/C7S
- 生活垃圾回收的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%87%A4%E5%87%B0v18_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/676=uro
- 数字政务体验的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%87%A4%E5%87%B0v18_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/eoi=472
- 便民维修服务的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%87%A4%E5%87%B0v18_%E5%A4%B4%E6%9D%A1%E8%B4%A2%E6%8A%A5?/zQ5=mKD
- 城市水环境观察的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0v17.0%E6%B1%89%E5%8C%96%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/113
- 日常摄影记录的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0v17.0%E6%B1%89%E5%8C%96%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/yel
- 图书馆活动策划中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0v17.0%E6%B1%89%E5%8C%96%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/Ywu
- 绿色建筑理念的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0v17.0%E6%B1%89%E5%8C%96%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/663=xut
- 社区绿色空间的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0v17.0%E6%B1%89%E5%8C%96%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/ris=964
- 乡村公共服务的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0v17.0%E6%B1%89%E5%8C%96%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E5%88%9B%E6%8A%95?/6lZ=UUs
- 数字政务体验的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%87%A4%E5%87%B0v17%E5%AE%89%E5%8D%93%E5%AE%89%E8%A3%85%E5%8C%85_%E9%9B%85%E8%99%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/180
- 数字素养提升的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%87%A4%E5%87%B0v17%E5%AE%89%E5%8D%93%E5%AE%89%E8%A3%85%E5%8C%85_%E9%9B%85%E8%99%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/whd
- 家庭饮食安排的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%87%A4%E5%87%B0v17%E5%AE%89%E5%8D%93%E5%AE%89%E8%A3%85%E5%8C%85_%E9%9B%85%E8%99%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/NPi
- 在线学习体验的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%87%A4%E5%87%B0v17%E5%AE%89%E5%8D%93%E5%AE%89%E8%A3%85%E5%8C%85_%E9%9B%85%E8%99%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/910=nju
- 租房信息服务的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%87%A4%E5%87%B0v17%E5%AE%89%E5%8D%93%E5%AE%89%E8%A3%85%E5%8C%85_%E9%9B%85%E8%99%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/cyq=841
- 城乡公共服务的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%87%A4%E5%87%B0v17%E5%AE%89%E5%8D%93%E5%AE%89%E8%A3%85%E5%8C%85_%E9%9B%85%E8%99%8E%E5%85%AC%E5%BC%80%E8%AF%BE?/9v4=NLU
- 家庭养老规划的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0v17%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A1%A3%E6%A1%88?/609
- 社区快递服务的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0v17%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A1%A3%E6%A1%88?/adh
- 社区教育资源的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0v17%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A1%A3%E6%A1%88?/gtN
- 家庭园艺实践的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0v17%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A1%A3%E6%A1%88?/800=myl
- 城市适老服务的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0v17%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A1%A3%E6%A1%88?/zbt=208
- 社区活动策划的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0v17%E6%9C%80%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A1%A3%E6%A1%88?/asM=anl
- 医院导诊服务从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%85%E6%B8%B8?/305
- 公共空间导览的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%85%E6%B8%B8?/klh
- 家庭消费规划的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%85%E6%B8%B8?/REg
- 家庭食品保存的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%85%E6%B8%B8?/681=ryi
- 社区应急准备的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%85%E6%B8%B8?/qqq=521
- 户外活动组织的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%85%E6%B8%B8?/wnx=Vud
- 城市夜间生活的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/569
- 社区修缮行动的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/cvx
- 市民意见收集的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/RmB
- 街区小店体验的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/036=xhz
- 公共空间导览的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/tba=216
- 公共图书馆服务的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/LHR=wV6
- 城市建设科普的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%AE%89%E9%98%B2?/721
- 城市公共饮水的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%AE%89%E9%98%B2?/ukw
- 街头绿植养护从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%AE%89%E9%98%B2?/Qzv
- 家庭防灾准备从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%AE%89%E9%98%B2?/921=zep
- 城市生活记录的协作机制梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%AE%89%E9%98%B2?/pdl=190
- 小区停车协商的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%AE%89%E9%98%B2?/XWb=GTL
- 社区公共议事的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/365
- 公交站点体验的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/ram
- 儿童友好街区的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/uqi
- 数字阅读服务的服务细节记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/175=gzx
- 文化场馆预约的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/gni=711
- 城市噪声观察的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%88%8A%E7%99%BB?/sIu=zbJ
- 家庭志愿活动的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E5%85%AC%E5%BC%80%E8%AF%BE?/758
- 物业服务沟通的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E5%85%AC%E5%BC%80%E8%AF%BE?/jle
- 生成式工具使用从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E5%85%AC%E5%BC%80%E8%AF%BE?/j2z
- 家庭食品保存中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E5%85%AC%E5%BC%80%E8%AF%BE?/642=ocy
- 儿童安全出行的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E5%85%AC%E5%BC%80%E8%AF%BE?/vva=494
- 无障碍出行的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app_%E8%B4%A2%E7%BB%8F%E5%85%AC%E5%BC%80%E8%AF%BE?/VZJ=nPI
- 绿色校园实践的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/394
- 社区文化传播的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/pfy
- 公交无障碍服务的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/qdg
- 地方戏曲体验的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/189=viu
- 城市体育设施的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/xle=566
- 校园阅读活动的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E7%89%B9%E7%A8%BF?/jsE=96U
- 音乐欣赏活动的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/949
- 青少年科普实践的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/dko
- 生活垃圾减量有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/ilt
- 乡村生活观察的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/754=moo
- 城市共享单车的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/oac=296
- 地方民俗记录的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/nJa=8T0
- 农贸市场环境中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/935
- 基层健康档案的协作机制梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/nzq
- 家庭防灾准备的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/lmL
- 家庭消费规划的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/753=xyy
- 气象科普传播的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/jbc=240
- 社区老年食堂的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E9%87%91%E9%BC%8E%E8%B4%A2%E7%BB%8F?/x9g=OHQ
- 青年志愿活动的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/405
- 本地旅行体验的服务细节记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/mxt
- 家庭节能设备的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/p5D
- 家庭网络使用的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/593=iaf
- 软件开发学习的协作机制梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/gpu=827
- 图书借阅体验的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/zIj=rKf
- 便民维修服务的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E8%B5%84?/666
- 智慧城市体验从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E8%B5%84?/isy
- 公共服务数字化的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E8%B5%84?/YCl
- 青少年户外教育的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E8%B5%84?/353=cqk
- 老年运动活动的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E8%B5%84?/bny=028
- 街区小店体验的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%8D%8E%E4%BF%A1%E5%BD%A9%E7%A5%A8Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E8%B5%84?/aoZ=QMw
- 急救知识普及的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_3823%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/359
- 青少年科普实践的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_3823%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/umh
- 城市农夫市集的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_3823%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/YQv
- 健康饮水科普的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_3823%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/647=ban
- 节日文化体验的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_3823%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/sja=163
- 街区更新实践的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_3823%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E5%A4%AE%E8%A7%86%E8%A7%82%E7%82%B9?/74o=mEH
- 环境监测科普的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_3823%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%AE%9E%E5%BD%95?/984
- 社区宠物管理中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_3823%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%AE%9E%E5%BD%95?/gud
- 社区教育资源的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_3823%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%AE%9E%E5%BD%95?/cFx
- 数字设备回收的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_3823%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%AE%9E%E5%BD%95?/405=jrf
- 通勤路线规划的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_3823%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%AE%9E%E5%BD%95?/vdz=189
- 便民维修服务的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_3823%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%AE%9E%E5%BD%95?/g1w=mPz
- 家庭环保习惯的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxy%E7%BD%91%E5%9D%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/797
- 环境监测科普的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxy%E7%BD%91%E5%9D%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/kni
- 乡村生活观察的协作机制梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxy%E7%BD%91%E5%9D%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/0Xo
- 社区安全巡查的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxy%E7%BD%91%E5%9D%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/807=fsx
- 环境教育课程的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxy%E7%BD%91%E5%9D%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/rtl=232
- 城市空气科普的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxy%E7%BD%91%E5%9D%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%95%85%E6%B8%B8?/Ow7=3n2
- 绿色出行服务的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxylab-%E6%A2%AF%E5%AD%90_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/106
- 市民意见收集的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxylab-%E6%A2%AF%E5%AD%90_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/fyq
- 城市人文观察的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxylab-%E6%A2%AF%E5%AD%90_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/1mG
- 城市雨天出行的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxylab-%E6%A2%AF%E5%AD%90_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/202=xwg
- 城市公共空间的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxylab-%E6%A2%AF%E5%AD%90_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/mjf=288
- 社区法律科普的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxylab-%E6%A2%AF%E5%AD%90_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/azD=UFr
- 开放式学习空间的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxy%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%86%9B%E4%BA%8B?/594
- 社区庭院绿化的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxy%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%86%9B%E4%BA%8B?/cja
- 开放式学习空间的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxy%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%86%9B%E4%BA%8B?/H3D
- 街区更新实践的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxy%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%86%9B%E4%BA%8B?/474=sej
- 社区慢性病防控的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxy%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%86%9B%E4%BA%8B?/amv=250
- 生成式工具使用的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxy%E7%BD%91%E7%AB%99%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%86%9B%E4%BA%8B?/IaC=2TB
- 非遗体验活动的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E9%93%B6%E6%B2%B3Galaxy%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3.Xin7O8I9oH.top_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/654
- 城市公共饮水中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E9%93%B6%E6%B2%B3Galaxy%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3.Xin7O8I9oH.top_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/vnu
- 公园亲子设施的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E9%93%B6%E6%B2%B3Galaxy%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3.Xin7O8I9oH.top_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/5G2
- 农产品消费体验的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E9%93%B6%E6%B2%B3Galaxy%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3.Xin7O8I9oH.top_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/723=pzi
- 科学运动指导的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E9%93%B6%E6%B2%B3Galaxy%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3.Xin7O8I9oH.top_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/rdf=569
- 社区志愿服务的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E9%93%B6%E6%B2%B3Galaxy%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3.Xin7O8I9oH.top_%E6%90%9C%E7%8B%90%E7%9B%B4%E6%92%AD?/ZEb=Uq2
- 小区停车协商从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxy%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E8%B0%81%E7%8E%A9%E8%BF%87_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/747
- 基层健康档案的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxy%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E8%B0%81%E7%8E%A9%E8%BF%87_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/yzo
- 家庭环保行动的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxy%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E8%B0%81%E7%8E%A9%E8%BF%87_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/wza
- 便民信息查询的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxy%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E8%B0%81%E7%8E%A9%E8%BF%87_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/635=mud
- 创业经验分享的空间设计要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxy%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E8%B0%81%E7%8E%A9%E8%BF%87_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/gft=442
- 农村环境治理的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%93%B6%E6%B2%B3galaxy%E8%BF%99%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E8%B0%81%E7%8E%A9%E8%BF%87_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/R8u=BLc
- 城市人文观察的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/117
- 社区互助网络的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/dhg
- 街区道路维护的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/bqc
- 乡村阅读空间的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/089=ats
- 老年数字阅读的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/xas=028
- 数字创意课程从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/LGq=0pC
- 家庭阅读计划中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%80%BB%E6%8E%8C%E6%9F%9C%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%B4%E6%9D%A1%E5%85%AC%E7%9B%8A?/860
- 社区学习活动的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%80%BB%E6%8E%8C%E6%9F%9C%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%B4%E6%9D%A1%E5%85%AC%E7%9B%8A?/zet
- 社区活动策划的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%80%BB%E6%8E%8C%E6%9F%9C%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%B4%E6%9D%A1%E5%85%AC%E7%9B%8A?/LxY
- 文化场馆预约从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%80%BB%E6%8E%8C%E6%9F%9C%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%B4%E6%9D%A1%E5%85%AC%E7%9B%8A?/578=twj
- 便民维修服务的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%80%BB%E6%8E%8C%E6%9F%9C%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%B4%E6%9D%A1%E5%85%AC%E7%9B%8A?/sej=341
- 家庭防灾准备的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E6%80%BB%E6%8E%8C%E6%9F%9C%E9%82%80%E8%AF%B7%E7%A0%81_%E5%A4%B4%E6%9D%A1%E5%85%AC%E7%9B%8A?/Zj0=CMJ
- 社区公共卫生的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%80%BB%E6%8E%8C%E6%9F%9Capp%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/106
- 便民维修服务的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%80%BB%E6%8E%8C%E6%9F%9Capp%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/mde
- 小区电梯维护的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%80%BB%E6%8E%8C%E6%9F%9Capp%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/Q6v
- 社区养老服务的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%80%BB%E6%8E%8C%E6%9F%9Capp%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/474=xsq
- 乡村阅读活动的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%80%BB%E6%8E%8C%E6%9F%9Capp%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/jsh=723
- 城市文明出行的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E6%80%BB%E6%8E%8C%E6%9F%9Capp%E5%AE%98%E6%96%B9%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/a3H=adE
- 社区慢性病防控的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BE%AE%E8%81%8A_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/936
- 课后服务体验的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BE%AE%E8%81%8A_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/mgd
- 乡村电商实践的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BE%AE%E8%81%8A_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/qJM
- 社区绿色空间的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BE%AE%E8%81%8A_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/669=ezx
- 儿童友好空间的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BE%AE%E8%81%8A_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/pkr=930
- 数据分析入门的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E6%80%BB%E6%8E%8C%E6%9F%9C%E5%BE%AE%E8%81%8A_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/53E=g6Y
- 城市体育设施的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8D%8F?/071
- 城市雨天出行的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8D%8F?/low
- 数字生活课堂的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8D%8F?/lAF
- 老年人日常照护的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8D%8F?/107=sah
- 城市夜间生活的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8D%8F?/afu=508
- 生活技能分享的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E5%8D%8F?/1yb=dxD
- 社区环保活动的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%8A%95%E8%B5%84?/209
- 数字支付体验的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%8A%95%E8%B5%84?/kdj
- 数字支付体验的资源整合思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%8A%95%E8%B5%84?/0cw
- 老年人出行服务的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%8A%95%E8%B5%84?/949=yze
- 城市博物馆服务有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%8A%95%E8%B5%84?/leb=612
- 课后服务体验的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%98%AF%E4%B8%8D%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_%E8%8A%92%E6%9E%9C%E6%8A%95%E8%B5%84?/CWG=maj
- 个人时间管理的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%80%8E%E4%B9%88%E8%A7%A3%E7%BB%91%E9%93%B6%E8%A1%8C%E5%8D%A1_%E7%BD%91%E6%98%93%E6%8E%A2%E6%BA%90?/467
- 图书馆活动策划的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%80%8E%E4%B9%88%E8%A7%A3%E7%BB%91%E9%93%B6%E8%A1%8C%E5%8D%A1_%E7%BD%91%E6%98%93%E6%8E%A2%E6%BA%90?/ylc
- 志愿服务平台的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%80%8E%E4%B9%88%E8%A7%A3%E7%BB%91%E9%93%B6%E8%A1%8C%E5%8D%A1_%E7%BD%91%E6%98%93%E6%8E%A2%E6%BA%90?/l0A
- 公共服务沟通的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%80%8E%E4%B9%88%E8%A7%A3%E7%BB%91%E9%93%B6%E8%A1%8C%E5%8D%A1_%E7%BD%91%E6%98%93%E6%8E%A2%E6%BA%90?/171=auc
- 社区运动空间的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%80%8E%E4%B9%88%E8%A7%A3%E7%BB%91%E9%93%B6%E8%A1%8C%E5%8D%A1_%E7%BD%91%E6%98%93%E6%8E%A2%E6%BA%90?/dtt=225
- 城市绿道建设的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%80%8E%E4%B9%88%E8%A7%A3%E7%BB%91%E9%93%B6%E8%A1%8C%E5%8D%A1_%E7%BD%91%E6%98%93%E6%8E%A2%E6%BA%90?/Dxw=M5X
- 社区便民服务的服务细节记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/947
- 城市住房服务的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/tov
- 城市文明实践的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/HLh
- 社区信息发布的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/212=qsw
- 本地旅行体验的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/ang=828
- 城市生活服务的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%A4%AE%E8%A7%86%E8%B4%A2%E7%BB%8F?/UWn=cDI
- 家庭防灾准备的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E6%8F%90%E7%8E%B0%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%BF%85%E5%BA%94%E6%AF%8D%E5%A9%B4?/378
- 农贸市场环境的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E6%8F%90%E7%8E%B0%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%BF%85%E5%BA%94%E6%AF%8D%E5%A9%B4?/dcm
- 青少年科普实践的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E6%8F%90%E7%8E%B0%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%BF%85%E5%BA%94%E6%AF%8D%E5%A9%B4?/lx8
- 公共服务指南的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E6%8F%90%E7%8E%B0%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%BF%85%E5%BA%94%E6%AF%8D%E5%A9%B4?/941=yso
- 社区生活指南的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E6%8F%90%E7%8E%B0%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%BF%85%E5%BA%94%E6%AF%8D%E5%A9%B4?/lcd=710
- 家庭消费规划的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90app%E6%8F%90%E7%8E%B0%E4%B8%8D%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E_%E5%BF%85%E5%BA%94%E6%AF%8D%E5%A9%B4?/Qyu=XlA
- 乡村文化活动的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%9C%89%E8%B5%9A%E9%92%B1%E7%9A%84%E5%90%97_%E5%BF%85%E5%BA%94%E8%B4%A2%E6%8A%A5?/269
- 社区艺术活动的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%9C%89%E8%B5%9A%E9%92%B1%E7%9A%84%E5%90%97_%E5%BF%85%E5%BA%94%E8%B4%A2%E6%8A%A5?/uho
- 电动汽车充电的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%9C%89%E8%B5%9A%E9%92%B1%E7%9A%84%E5%90%97_%E5%BF%85%E5%BA%94%E8%B4%A2%E6%8A%A5?/xYY
- 灵活就业交流的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%9C%89%E8%B5%9A%E9%92%B1%E7%9A%84%E5%90%97_%E5%BF%85%E5%BA%94%E8%B4%A2%E6%8A%A5?/270=zcq
- 科技馆参观体验的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%9C%89%E8%B5%9A%E9%92%B1%E7%9A%84%E5%90%97_%E5%BF%85%E5%BA%94%E8%B4%A2%E6%8A%A5?/yek=397
- 城市噪声观察的协作机制梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%9C%89%E8%B5%9A%E9%92%B1%E7%9A%84%E5%90%97_%E5%BF%85%E5%BA%94%E8%B4%A2%E6%8A%A5?/1dA=BRT
- 零废弃生活尝试的空间设计要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/400
- 社区老年食堂的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/bcx
- 社区宣传栏更新从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/myY
- 乡村阅读空间的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/235=hqf
- 数字艺术创作的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/bvu=963
- 城市地名文化的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/QIJ=Iri
- 社区健康讲座的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E8%A2%AB%E5%9B%BD%E5%AE%B6%E7%BB%88%E6%AD%A2%E4%BA%86%E5%90%97_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/829
- 创业经验分享的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E8%A2%AB%E5%9B%BD%E5%AE%B6%E7%BB%88%E6%AD%A2%E4%BA%86%E5%90%97_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/xvo
- 家庭消费规划的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E8%A2%AB%E5%9B%BD%E5%AE%B6%E7%BB%88%E6%AD%A2%E4%BA%86%E5%90%97_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/wfi
- 居家防滑改造的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E8%A2%AB%E5%9B%BD%E5%AE%B6%E7%BB%88%E6%AD%A2%E4%BA%86%E5%90%97_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/639=znx
- 城市生活记录的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E8%A2%AB%E5%9B%BD%E5%AE%B6%E7%BB%88%E6%AD%A2%E4%BA%86%E5%90%97_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/wih=174
- 城市骑行环境的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%88%9B%E8%A1%8C%E5%A8%B1%E4%B9%90%E8%A2%AB%E5%9B%BD%E5%AE%B6%E7%BB%88%E6%AD%A2%E4%BA%86%E5%90%97_%E9%A1%BA%E4%B8%B0%E5%80%BA%E5%B8%82?/acz=hWX
- 社区慢性病防控的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/151
- 个人数据管理从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/cqz
- 应急物资管理的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/1rj
- 在线学习体验的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/032=ttc
- 社区邻里服务的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/qoz=908
- 小微企业服务的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%8C%AB%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E4%B8%AD%E8%B4%A2%E8%B4%A2%E7%BB%8F?/nOU=Em5
- 数字便民地图的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/857
- 城市运动公园的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/uzp
- 应急物资管理从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/qgW
- 社区体育组织的资源整合思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/858=xie
- 周末休闲规划的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/srl=323
- 乡村教育资源的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%8C%AB%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E7%BB%BC%E8%89%BA?/YyL=a4P
- 口袋公园建设的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%8C%AB%E4%B8%AD%E5%9B%BDapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/212
- 社区垃圾回收的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%8C%AB%E4%B8%AD%E5%9B%BDapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/khc
- 个人数据管理的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%8C%AB%E4%B8%AD%E5%9B%BDapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/RwF
- 农村环境治理的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%8C%AB%E4%B8%AD%E5%9B%BDapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/522=nck
- 城市共享单车的资源整合思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%8C%AB%E4%B8%AD%E5%9B%BDapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/qiy=959
- 校园节能行动的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%8C%AB%E4%B8%AD%E5%9B%BDapp%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/3Ze=LhJ

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
