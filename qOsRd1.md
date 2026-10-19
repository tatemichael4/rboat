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

- 机器学习入门的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/402
- 通勤路线规划的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/bom
- 跨代沟通活动的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/TAH
- 乡村公共服务的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/966=ftg
- 城市慢行系统的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/cbd=578
- 光伏知识科普的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E7%A5%9E%E5%BD%A98%E4%BA%89%E9%9C%B8_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/0zj=4Z1
- 家庭饮食安排的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/393
- 社区知识分享的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/wqj
- 社区读书角建设的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/UeA
- 电子商务服务的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/187=ruk
- 城市公共艺术的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/gfz=710
- 文化讲座服务中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F?/jHf=zZs
- 垃圾分类指导的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/232
- 城市地名文化的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/mpr
- 城市适老服务从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/cdI
- 个人数据管理的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/074=zfg
- 线上办事服务的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/nvt=406
- 老年学习活动的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E6%BE%8E%E6%B9%83%E8%A7%82%E5%AF%9F?/f67=Jvi
- 校园安全教育的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2_%E5%A4%B4%E6%9D%A1?/705
- 数字素养提升的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2_%E5%A4%B4%E6%9D%A1?/uit
- 开放数据应用的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2_%E5%A4%B4%E6%9D%A1?/IAD
- 节能家电使用的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2_%E5%A4%B4%E6%9D%A1?/231=oep
- 城乡交通衔接的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2_%E5%A4%B4%E6%9D%A1?/hdn=420
- 社区快递服务的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2_%E5%A4%B4%E6%9D%A1?/LWA=jD8
- 城乡交流活动的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E7%B2%BE%E5%87%86%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%82%A1%E7%A5%A8?/255
- 街区道路维护的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E7%B2%BE%E5%87%86%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%82%A1%E7%A5%A8?/wun
- 城市文化路线的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E7%B2%BE%E5%87%86%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%82%A1%E7%A5%A8?/Pqh
- 乡村教育资源的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E7%B2%BE%E5%87%86%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%82%A1%E7%A5%A8?/631=yru
- 校园社团活动的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E7%B2%BE%E5%87%86%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%82%A1%E7%A5%A8?/vvd=757
- 文明养宠科普的空间设计要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E7%B2%BE%E5%87%86%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E8%82%A1%E7%A5%A8?/qCR=Rs6
- 个人时间管理的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E5%B9%B3_%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/678
- 家庭防灾准备的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E5%B9%B3_%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/kgf
- 城市文明出行的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E5%B9%B3_%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/pjj
- 信息无障碍体验的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E5%B9%B3_%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/474=qpu
- 家庭急救准备的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E5%B9%B3_%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/uib=757
- 全民健身活动的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_1%E5%88%86%E5%BF%AB3%E5%B9%B3_%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E8%84%89%E8%84%89%E5%9B%9E%E6%9C%9B?/xi9=vgF
- 家庭理财科普的空间设计要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E9%97%AE%E5%8D%B7?/979
- 乡村休闲旅游的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E9%97%AE%E5%8D%B7?/oxo
- 家庭园艺实践的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E9%97%AE%E5%8D%B7?/BWB
- 社区设施共享的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E9%97%AE%E5%8D%B7?/017=azu
- 学校食育活动的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E9%97%AE%E5%8D%B7?/csr=754
- 公共场所导视的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%85%A8%E5%9B%BD%E5%BF%AB3%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E9%97%AE%E5%8D%B7?/zIC=dQM
- 社区法律科普的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/367
- 城市生活记录的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/gpf
- 非遗课堂体验的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/71U
- 居民健康教育的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/430=cjd
- 老年数字阅读的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/gju=068
- 老年智能设备的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/88S=W2E
- 社区健康讲座的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%85%A8%E5%9B%BD%E5%BF%AB3-%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/359
- 地方戏曲体验中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%85%A8%E5%9B%BD%E5%BF%AB3-%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/ncl
- 生活垃圾减量的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%85%A8%E5%9B%BD%E5%BF%AB3-%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/wmt
- 乡村阅读空间中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%85%A8%E5%9B%BD%E5%BF%AB3-%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/301=bkj
- 社区活动策划的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%85%A8%E5%9B%BD%E5%BF%AB3-%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/lxx=188
- 城市基础设施的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E5%85%A8%E5%9B%BD%E5%BF%AB3-%E6%89%8B%E6%9C%BA%E5%AE%98%E7%BD%91_%E5%8D%8E%E5%A4%8F%E8%B4%A2%E7%BB%8F?/OkX=fbS
- 社区互助网络的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9lv%E4%BA%89%E9%9C%B8_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%AE%BF?/589
- 社区宠物管理的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9lv%E4%BA%89%E9%9C%B8_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%AE%BF?/str
- 社区交通安全的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9lv%E4%BA%89%E9%9C%B8_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%AE%BF?/fbE
- 志愿服务平台的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9lv%E4%BA%89%E9%9C%B8_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%AE%BF?/420=rlq
- 在线学习体验的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9lv%E4%BA%89%E9%9C%B8_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%AE%BF?/bgn=590
- 居家防滑改造的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%8F%91%E7%A5%9E%E5%BD%A9lv%E4%BA%89%E9%9C%B8_%E4%BC%98%E9%85%B7%E4%BF%A1%E8%AE%BF?/SxI=mpl
- 乡村阅读空间的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E6%98%AF%E8%B0%81_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/725
- 乡村公共阅读的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E6%98%AF%E8%B0%81_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/olv
- 市民意见收集的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E6%98%AF%E8%B0%81_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/EUw
- 亲子科普活动的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E6%98%AF%E8%B0%81_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/642=uhk
- 公共设施维护的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E6%98%AF%E8%B0%81_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/qtc=168
- 城市环境志愿行动的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E6%98%AF%E8%B0%81_36%E6%B0%AA%E5%8F%B8%E6%B3%95?/Im2=Wbs
- 全民阅读推广的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%AF%94%E8%BE%83_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/199
- 公共卫生宣传的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%AF%94%E8%BE%83_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/fsp
- 社区绿色空间的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%AF%94%E8%BE%83_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/Yb5
- 农产品消费体验的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%AF%94%E8%BE%83_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/596=cue
- 社区商业活力中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%AF%94%E8%BE%83_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/obr=660
- 智慧停车服务的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0%E6%AF%94%E8%BE%83_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A5%A8?/ftR=DZT
- 城市公共饮水的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/944
- 亲子阅读活动的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/anu
- 社区艺术活动的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/hw9
- 社会体育指导的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/187=mbw
- 公共交通接驳的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/szt=358
- 数字资源检索的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F_%E7%88%B1%E5%A5%87%E8%89%BA%E6%99%9A%E6%8A%A5?/sd9=m3Z
- 城市空气科普的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BF%AB%EF%BC%8F3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E6%B3%95%E5%BE%8B?/662
- 校园安全教育的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BF%AB%EF%BC%8F3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E6%B3%95%E5%BE%8B?/zci
- 社区手工活动的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BF%AB%EF%BC%8F3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E6%B3%95%E5%BE%8B?/O6I
- 音乐欣赏活动的实用信息清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BF%AB%EF%BC%8F3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E6%B3%95%E5%BE%8B?/475=cis
- 社区花园共建的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BF%AB%EF%BC%8F3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E6%B3%95%E5%BE%8B?/hbv=988
- 社区快递服务的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BF%AB%EF%BC%8F3%E5%B8%A6%E8%B5%9A%E8%AE%A1%E5%88%92%E6%9C%80%E5%8E%89%E5%AE%B3%E4%B8%89%E4%B8%AA%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E6%B3%95%E5%BE%8B?/OuI=gwg
- 居家防滑改造的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1%E5%88%86%E4%BA%AB_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/764
- 智能家居应用的服务细节记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1%E5%88%86%E4%BA%AB_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/dqb
- 儿童安全出行的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1%E5%88%86%E4%BA%AB_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/XEg
- 社区志愿服务的服务范围梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1%E5%88%86%E4%BA%AB_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/952=qek
- 儿童友好街区的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1%E5%88%86%E4%BA%AB_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/amx=783
- 口袋公园建设的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E7%9A%84%E8%AE%A1%E5%88%92%E7%BE%A4%E5%B8%A6%E4%BD%A0%E8%B5%9A%E9%92%B1%E5%88%86%E4%BA%AB_%E8%85%BE%E8%AE%AF%E5%B9%B6%E8%B4%AD?/1tQ=Ti3
- 市民热线服务的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A824%E5%B0%8F%E6%97%B6%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/829
- 科学运动指导从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A824%E5%B0%8F%E6%97%B6%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/snc
- 人工智能科普的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A824%E5%B0%8F%E6%97%B6%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/aJD
- 社区邻里服务的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A824%E5%B0%8F%E6%97%B6%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/381=jsw
- 绿色快递包装的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A824%E5%B0%8F%E6%97%B6%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/bxy=977
- 家庭食品保存的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A824%E5%B0%8F%E6%97%B6%E5%9C%A8%E7%BA%BF%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/QUh=9YN
- 乡村文化空间的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%B7%9F%E8%AE%A1%E5%88%92%E7%BE%A4%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/703
- 社区科普课堂的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%B7%9F%E8%AE%A1%E5%88%92%E7%BE%A4%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/fxl
- 科学信息获取的服务质量观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%B7%9F%E8%AE%A1%E5%88%92%E7%BE%A4%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/daG
- 社区环保活动的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%B7%9F%E8%AE%A1%E5%88%92%E7%BE%A4%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/693=vql
- 志愿服务平台的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%B7%9F%E8%AE%A1%E5%88%92%E7%BE%A4%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/kti=349
- 城市人文观察的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E8%B7%9F%E8%AE%A1%E5%88%92%E7%BE%A4%E6%89%8D%E8%83%BD%E8%B5%9A%E9%92%B1_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/Zzm=47B
- 数据分析入门有哪些值得关注的细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%93%94%E5%93%A9%E6%8A%95%E7%A5%A8?/087
- 社区阅读服务的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%93%94%E5%93%A9%E6%8A%95%E7%A5%A8?/dgm
- 城乡公共服务的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%93%94%E5%93%A9%E6%8A%95%E7%A5%A8?/g5c
- 老年友好服务的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%93%94%E5%93%A9%E6%8A%95%E7%A5%A8?/151=uer
- 图书馆活动策划的空间使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%93%94%E5%93%A9%E6%8A%95%E7%A5%A8?/ews=327
- 社区艺术活动的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%93%94%E5%93%A9%E6%8A%95%E7%A5%A8?/s55=pDW
- 社区互助网络的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E5%BE%97%E7%89%A9%E5%9F%8E%E4%BA%8B?/459
- 公共服务预约的基础知识问答 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E5%BE%97%E7%89%A9%E5%9F%8E%E4%BA%8B?/jnj
- 农村环境治理的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E5%BE%97%E7%89%A9%E5%9F%8E%E4%BA%8B?/QEW
- 个人信息保护的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E5%BE%97%E7%89%A9%E5%9F%8E%E4%BA%8B?/611=vpq
- 家庭健康科普的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E5%BE%97%E7%89%A9%E5%9F%8E%E4%BA%8B?/gdb=609
- 社区阅读服务的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%AE%A1%E5%88%92%E5%A4%A7%E5%85%A8_%E5%BE%97%E7%89%A9%E5%9F%8E%E4%BA%8B?/xKR=sdg
- 城市运动公园的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%BE%A4%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/585
- 数字创作工具的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%BE%A4%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/iug
- 社区手工活动的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%BE%A4%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/aBS
- 社区活动空间从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%BE%A4%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/034=qwo
- 家庭陪伴活动的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%BE%A4%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/kkz=136
- 气象科普传播的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%BE%A4%E5%AF%BC%E5%B8%88_%E6%90%9C%E7%8B%97%E6%9B%B2%E8%89%BA?/BlA=3tT
- 社区养老服务的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%884%E5%88%86%E9%92%9F%E7%90%86%E8%A7%A3_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/015
- 社区家政服务的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%884%E5%88%86%E9%92%9F%E7%90%86%E8%A7%A3_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/mac
- 社区便民服务的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%884%E5%88%86%E9%92%9F%E7%90%86%E8%A7%A3_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/10G
- 城市慢跑路线的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%884%E5%88%86%E9%92%9F%E7%90%86%E8%A7%A3_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/412=fef
- 数字资源检索的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%884%E5%88%86%E9%92%9F%E7%90%86%E8%A7%A3_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/rgz=769
- 生活垃圾减量的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%884%E5%88%86%E9%92%9F%E7%90%86%E8%A7%A3_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/29M=IUC
- 家庭消费规划的长期维护要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E5%BE%97%E7%89%A9?/328
- 公园休闲体验的空间设计要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E5%BE%97%E7%89%A9?/bek
- 节气饮食文化的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E5%BE%97%E7%89%A9?/IL6
- 城市文明实践的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E5%BE%97%E7%89%A9?/568=ctf
- 公共场所导视的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E5%BE%97%E7%89%A9?/jia=661
- 社区商业活力的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pc%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E6%9D%80%E7%BB%84%E5%90%88_%E5%BE%97%E7%89%A9?/2Us=ErJ
- 城市体育设施的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%BC%8F%E6%B4%9E_%E7%BD%91%E6%98%93%E5%85%AC%E5%91%8A?/482
- 青少年科技社团的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%BC%8F%E6%B4%9E_%E7%BD%91%E6%98%93%E5%85%AC%E5%91%8A?/qhj
- 城市夜间照明的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%BC%8F%E6%B4%9E_%E7%BD%91%E6%98%93%E5%85%AC%E5%91%8A?/sIO
- 传统节日科普的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%BC%8F%E6%B4%9E_%E7%BD%91%E6%98%93%E5%85%AC%E5%91%8A?/334=qiv
- 灵活就业交流的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%BC%8F%E6%B4%9E_%E7%BD%91%E6%98%93%E5%85%AC%E5%91%8A?/qxq=785
- 文化遗产保护科普的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%BC%8F%E6%B4%9E_%E7%BD%91%E6%98%93%E5%85%AC%E5%91%8A?/H15=Mdx
- 科学教育活动的便捷程度观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E4%B8%93%E4%B8%9A%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/209
- 农产品品牌传播的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E4%B8%93%E4%B8%9A%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/mng
- 社区停车服务的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E4%B8%93%E4%B8%9A%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/87f
- 绿色办公实践的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E4%B8%93%E4%B8%9A%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/447=nqi
- 青少年科普实践的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E4%B8%93%E4%B8%9A%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/rdu=247
- 青少年科普实践的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E4%B8%93%E4%B8%9A%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E7%BD%91%E6%98%93%E6%97%A5%E6%8A%A5?/CdD=YYq
- 数字创作工具的家庭实践清单 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%85%A8%E7%BD%91%E6%9C%80%E5%BC%BA%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/219
- 非遗课堂体验的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%85%A8%E7%BD%91%E6%9C%80%E5%BC%BA%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/pjr
- 乡村生态旅游的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%85%A8%E7%BD%91%E6%9C%80%E5%BC%BA%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/fmg
- 个人时间管理的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%85%A8%E7%BD%91%E6%9C%80%E5%BC%BA%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/107=zrz
- 城市适老服务的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%85%A8%E7%BD%91%E6%9C%80%E5%BC%BA%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/lkm=603
- 图书馆亲子空间的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_%E5%85%A8%E7%BD%91%E6%9C%80%E5%BC%BA%E5%BF%AB3%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E8%99%8E%E5%97%85%E6%98%9F%E5%BA%A7?/8At=rgA
- 城市游园体验的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BF%AB3%E6%9C%80%E5%BC%BA%E7%9A%84%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/038
- 文明养宠科普的公共信息获取方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BF%AB3%E6%9C%80%E5%BC%BA%E7%9A%84%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/jun
- 社区体育组织的行动步骤参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BF%AB3%E6%9C%80%E5%BC%BA%E7%9A%84%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/Bfv
- 本地历史资料的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BF%AB3%E6%9C%80%E5%BC%BA%E7%9A%84%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/190=thd
- 公共空间照明的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BF%AB3%E6%9C%80%E5%BC%BA%E7%9A%84%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/nft=311
- 数字素养提升的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%BF%AB3%E6%9C%80%E5%BC%BA%E7%9A%84%E5%9B%9E%E6%9C%AC%E5%AF%BC%E5%B8%88_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/5PW=vEI
- 青年职业探索的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%AF%B9%E5%8D%95%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/803
- 基层健康服务的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%AF%B9%E5%8D%95%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/iir
- 乡村公共文化中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%AF%B9%E5%8D%95%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/pCw
- 开放数据应用的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%AF%B9%E5%8D%95%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/299=qig
- 开放数据应用的社区参与观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%AF%B9%E5%8D%95%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/mpo=116
- 社区活动空间的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%AF%B9%E5%8D%95%E5%B8%A6%E5%9B%9E%E6%9C%AC_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%A3%E5%AF%86?/Fim=AhB
- 就业技能培训的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88QQ_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/459
- 城市共享单车的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88QQ_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/gvn
- 开放数据应用的安全使用提示 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88QQ_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/ZjG
- 城市骑行环境的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88QQ_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/737=lzz
- 社区运动空间的居民参与机会 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88QQ_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/kyt=201
- 数字公共文化的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E9%87%91%E7%89%8C%E8%AE%A1%E5%88%92%E7%A8%B3%E5%AE%9A%E5%AF%BC%E5%B8%88QQ_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/isf=vlS
- 社区菜市场服务的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E5%B8%A6%E8%B5%9A%E9%92%B1%29_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/160
- 社区科普课堂的社区行动案例 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E5%B8%A6%E8%B5%9A%E9%92%B1%29_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/vtq
- 文明养宠科普的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E5%B8%A6%E8%B5%9A%E9%92%B1%29_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/Lda
- 在线学习体验的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E5%B8%A6%E8%B5%9A%E9%92%B1%29_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/924=dny
- 家庭陪伴活动的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E5%B8%A6%E8%B5%9A%E9%92%B1%29_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/trt=806
- 安全出行教育的活动体验回顾 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BF%AB3%E6%89%80%E6%9C%89%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E5%B8%A6%E8%B5%9A%E9%92%B1%29_%E7%99%BE%E5%BA%A6%E5%AE%B6%E7%94%B5?/PpE=P9T
- 城市绿色交通的数字工具使用体验 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%AE%98%E6%96%B9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/248
- 环境教育课程的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%AE%98%E6%96%B9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/luz
- 公共设施维护的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%AE%98%E6%96%B9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/g4G
- 职业技能学习的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%AE%98%E6%96%B9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/654=yqh
- 家庭健康科普的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%AE%98%E6%96%B9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/toj=850
- 安全出行教育的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%AE%98%E6%96%B9%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/jGS=stE
- 地方旅游导览的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/268
- 城市文明实践的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/vvb
- 邻里互助活动的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/eYp
- 公共空间照明的公共参与指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/448=ttl
- 社区故事采集从需求出发看服务设计 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/tam=032
- 农业科普体验的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/zcA=bCi
- 光伏知识科普的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92345678%E4%B8%8D%E5%AE%9A%E4%BD%8D%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2?/102
- 家庭教育交流的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92345678%E4%B8%8D%E5%AE%9A%E4%BD%8D%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2?/qnp
- 基层健康档案的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92345678%E4%B8%8D%E5%AE%9A%E4%BD%8D%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2?/nRt
- 线上阅读资源的资源整合思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92345678%E4%B8%8D%E5%AE%9A%E4%BD%8D%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2?/032=pbe
- 低碳社区实践的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92345678%E4%B8%8D%E5%AE%9A%E4%BD%8D%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2?/xph=620
- 家庭健康管理的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92345678%E4%B8%8D%E5%AE%9A%E4%BD%8D%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2?/nMS=lJf
- 街道综合服务的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/340
- 社区家政服务的活动组织技巧 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/fft
- 老年人文化生活的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/Mid
- 家庭消费规划的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/879=kvi
- 网络信息辨识的协商参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/uzn=152
- 城市公共座椅的设施维护观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%B9%B8%E8%BF%90%E5%BF%AB3_%E7%88%B1%E5%A5%87%E8%89%BA%E5%BF%AB%E6%8A%A5?/Dnt=Sh8
- 城市公共空间的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E7%8B%AC%E5%AE%B6%E5%B9%B2%E8%B4%A7%29_%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/407
- 乡村文化空间的日常使用指南 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E7%8B%AC%E5%AE%B6%E5%B9%B2%E8%B4%A7%29_%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/lsh
- 城市夜间照明从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E7%8B%AC%E5%AE%B6%E5%B9%B2%E8%B4%A7%29_%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/BAQ
- 无障碍出行的线下体验记录 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E7%8B%AC%E5%AE%B6%E5%B9%B2%E8%B4%A7%29_%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/201=sob
- 读书会组织的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E7%8B%AC%E5%AE%B6%E5%B9%B2%E8%B4%A7%29_%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/xca=160
- 软件开发学习的执行流程参考 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%94%BB%E7%95%A5%28%E7%8B%AC%E5%AE%B6%E5%B9%B2%E8%B4%A7%29_%E6%BE%8E%E6%B9%83%E6%94%B6%E8%97%8F?/YKG=pjx
- 家庭健康科普的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BD%A9%E5%85%AB%E4%BB%99%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/226
- 社区生活指南的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BD%A9%E5%85%AB%E4%BB%99%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/vco
- 数字创意课程的组织方法与经验 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BD%A9%E5%85%AB%E4%BB%99%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/aym
- 电动汽车充电中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BD%A9%E5%85%AB%E4%BB%99%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/805=pxa
- 社区公共卫生的便利性观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BD%A9%E5%85%AB%E4%BB%99%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/qro=422
- 社区协商议事的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E5%BD%A9%E5%85%AB%E4%BB%99%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E8%B5%84%E8%AE%AF?/Mcs=mRB
- 家庭急救准备的数字化应用观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E8%A1%A8_%E6%96%B0%E6%B5%AA%E7%90%86%E8%B4%A2?/501
- 青年职业探索的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E8%A1%A8_%E6%96%B0%E6%B5%AA%E7%90%86%E8%B4%A2?/xzl
- 便民维修服务的阅读与学习资源 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E8%A1%A8_%E6%96%B0%E6%B5%AA%E7%90%86%E8%B4%A2?/WYg
- 网络信息辨识的持续改进方向 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E8%A1%A8_%E6%96%B0%E6%B5%AA%E7%90%86%E8%B4%A2?/398=cux
- 信息无障碍体验的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E8%A1%A8_%E6%96%B0%E6%B5%AA%E7%90%86%E8%B4%A2?/htd=738
- 乡村教育资源的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E5%85%AC%E5%BC%8F%E8%A1%A8_%E6%96%B0%E6%B5%AA%E7%90%86%E8%B4%A2?/5ed=YI6
- 社区故事采集的常见误区提醒 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E9%80%9A%E4%BF%A1?/640
- 健康饮食教育中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E9%80%9A%E4%BF%A1?/fuk
- 居家防滑改造的参与方式与路径 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E9%80%9A%E4%BF%A1?/DY9
- 乡村产业科普的流程优化思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E9%80%9A%E4%BF%A1?/137=aiv
- 食品配送体验的服务信息整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E9%80%9A%E4%BF%A1?/jzp=784
- 城市公共艺术的常见问题梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3-%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E6%BE%8E%E6%B9%83%E9%80%9A%E4%BF%A1?/9H4=VCz
- 公园无障碍服务中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_360%E6%AF%8D%E5%A9%B4?/906
- 在线学习体验的家庭参与方式 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_360%E6%AF%8D%E5%A9%B4?/dou
- 家庭节能实践的便民做法梳理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_360%E6%AF%8D%E5%A9%B4?/7b1
- 家庭健康管理的儿童友好细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_360%E6%AF%8D%E5%A9%B4?/257=ruj
- 城市水环境观察的使用门槛与改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_360%E6%AF%8D%E5%A9%B4?/cii=869
- 城市休闲步道的日常管理方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_360%E6%AF%8D%E5%A9%B4?/oZc=Txi
- 家庭理财科普的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%87%91%E5%BD%A9%E6%B1%87%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/296
- 信息无障碍体验的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%87%91%E5%BD%A9%E6%B1%87%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/dij
- 社区修缮行动的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%87%91%E5%BD%A9%E6%B1%87%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/0IE
- 社区儿童活动的实际需求与回应 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%87%91%E5%BD%A9%E6%B1%87%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/401=lbd
- 老年人出行服务的资源整合思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%87%91%E5%BD%A9%E6%B1%87%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/dkr=292
- 邻里共享空间中的几个关键细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%87%91%E5%BD%A9%E6%B1%87%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/I40=FSW
- 城市噪声观察的日常记录与分享 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E9%85%B7%E5%BD%A9app_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/138
- 公共服务预约的日常实践笔记 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E9%85%B7%E5%BD%A9app_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/ajn
- 个人信息保护的基础设施观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E9%85%B7%E5%BD%A9app_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/TrI
- 青少年户外教育中的沟通与协作 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E9%85%B7%E5%BD%A9app_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/154=hak
- 儿童友好空间的线上线下服务衔接 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E9%85%B7%E5%BD%A9app_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/xbx=146
- 非遗体验活动的服务体验观察 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E9%85%B7%E5%BD%A9app_%E8%B4%A2%E7%BB%8F%E9%9F%B3%E4%B9%90?/l98=SnJ
- 网络安全教育从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/093
- 通勤路线规划的适老服务细节 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/dxx
- 社区艺术活动的学习资源整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/rNv
- 骑行路线规划从使用体验看服务改进 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/925=mpv
- 社区家校合作的空间设计要点 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/xay=883
- 社区便利生活的服务反馈渠道 |来源：https://github.com/williamsnicholas31/escl/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E7%9F%A5%E4%B9%8E%E6%94%B6%E8%97%8F?/VQ1=nHf
- 城市应急科普的资源利用方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%A7%86%E9%A2%91?/879
- 儿童安全出行的绿色实践方法 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%A7%86%E9%A2%91?/aeq
- 城乡交通衔接的入门知识整理 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%A7%86%E9%A2%91?/mYk
- 本地旅行体验的活动策划思路 |来源：https://github.com/williamsnicholas31/escl/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%92%8C%E5%80%BC%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E8%A7%86%E9%A2%91?/540=ajs

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
