# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:17**

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

- 个人数据管理的日常管理方法 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%BF%AB%E4%B9%908%E4%B8%93%E5%AE%B6%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E5%BF%85%E5%BA%94%E8%AE%BA%E5%9D%9B?/mty=968
- 地方美食文化的社区行动案例 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%BF%AB%E4%B9%908%E4%B8%93%E5%AE%B6%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81_%E5%BF%85%E5%BA%94%E8%AE%BA%E5%9D%9B?/YVu=uwq
- 节气饮食文化的数字工具使用体验 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BB%9F%E8%AE%A1%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E7%A4%BE%E5%8C%BA?/682
- 家庭运动计划的活动组织技巧 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BB%9F%E8%AE%A1%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E7%A4%BE%E5%8C%BA?/agn
- 城市共享单车的资源整合思路 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BB%9F%E8%AE%A1%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E7%A4%BE%E5%8C%BA?/qfN
- 城市文明出行的家庭参与方式 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BB%9F%E8%AE%A1%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E7%A4%BE%E5%8C%BA?/002=irw
- 社区休闲设施的协作机制梳理 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BB%9F%E8%AE%A1%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E7%A4%BE%E5%8C%BA?/vqd=277
- 城市便民驿站的活动组织技巧 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%BB%9F%E8%AE%A1%E8%BD%AF%E4%BB%B6_%E9%9B%85%E8%99%8E%E7%A4%BE%E5%8C%BA?/hP9=WfD
- 城市绿道建设的实用信息清单 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E9%A3%9F?/484
- 志愿者培训交流的家庭参与方式 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E9%A3%9F?/ukb
- 地方戏曲体验的学习资源整理 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E9%A3%9F?/uyJ
- 社区体育组织中的沟通与协作 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E9%A3%9F?/719=lmb
- 数字档案服务的流程优化思路 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E9%A3%9F?/kcc=231
- 无障碍出行的协商参与方式 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E9%A3%9F?/vZP=vAT
- 街区绿化养护的基础设施观察 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%86%B7%E7%83%AD%E5%8F%B7%E6%80%8E%E4%B9%88%E7%9C%8B_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/229
- 城市空气科普的日常使用指南 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%86%B7%E7%83%AD%E5%8F%B7%E6%80%8E%E4%B9%88%E7%9C%8B_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/buy
- 农贸市场环境的阅读与学习资源 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%86%B7%E7%83%AD%E5%8F%B7%E6%80%8E%E4%B9%88%E7%9C%8B_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/qER
- 儿童友好街区的家庭参与方式 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%86%B7%E7%83%AD%E5%8F%B7%E6%80%8E%E4%B9%88%E7%9C%8B_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/277=ibi
- 家庭理财科普的活动组织技巧 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%86%B7%E7%83%AD%E5%8F%B7%E6%80%8E%E4%B9%88%E7%9C%8B_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/pst=960
- 开放式学习空间的绿色实践方法 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%86%B7%E7%83%AD%E5%8F%B7%E6%80%8E%E4%B9%88%E7%9C%8B_%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F?/KhA=VKt
- 街区更新实践有哪些值得关注的细节 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%88%86%E6%9E%90_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/026
- 绿色校园实践的基础设施观察 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%88%86%E6%9E%90_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/lxg
- 公共服务评价的参与方式与路径 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%88%86%E6%9E%90_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/P3G
- 数字政务体验的日常实践笔记 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%88%86%E6%9E%90_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/609=vlo
- 城市文明出行的活动策划思路 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%88%86%E6%9E%90_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/tos=632
- 智慧城市体验的数字化应用观察 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%88%86%E6%9E%90_%E5%A4%B4%E6%9D%A1%E5%85%9A%E5%BB%BA?/ou1=g6D
- 日常摄影记录的常见问题梳理 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE_%E5%BF%AB%E6%89%8B%E8%BF%B0%E8%AF%84?/369
- 课后服务体验的社区行动案例 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE_%E5%BF%AB%E6%89%8B%E8%BF%B0%E8%AF%84?/zxs
- 数字创意课程中的几个关键细节 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE_%E5%BF%AB%E6%89%8B%E8%BF%B0%E8%AF%84?/Ts8
- 城市微更新实践的数字工具使用体验 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE_%E5%BF%AB%E6%89%8B%E8%BF%B0%E8%AF%84?/055=pdt
- 新能源知识普及的阅读与学习资源 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE_%E5%BF%AB%E6%89%8B%E8%BF%B0%E8%AF%84?/vdw=876
- 家庭陪伴活动的协商参与方式 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BF%AB3%E9%81%97%E6%BC%8F%E6%95%B0%E6%8D%AE_%E5%BF%AB%E6%89%8B%E8%BF%B0%E8%AF%84?/oY7=Aap
- 城市公共饮水的儿童友好细节 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%9F%A5%E8%A1%A8_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/032
- 公共场所导视的阅读与学习资源 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%9F%A5%E8%A1%A8_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/pkh
- 公共设施维护中的几个关键细节 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%9F%A5%E8%A1%A8_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/Lal
- 数字艺术创作的家庭实践清单 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%9F%A5%E8%A1%A8_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/713=mfc
- 绿色办公实践的学习资源整理 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%9F%A5%E8%A1%A8_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/hoh=296
- 网络安全教育的公共参与指南 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%9F%A5%E8%A1%A8_%E6%8E%A8%E8%8D%90%E8%B4%A2%E7%BB%8F?/dJV=PoK
- 城市住房服务的设施维护观察 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_360%E7%99%BE%E7%A7%91?/861
- 社区健康讲座的持续改进方向 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_360%E7%99%BE%E7%A7%91?/csz
- 乡村公共阅读的空间使用体验 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_360%E7%99%BE%E7%A7%91?/Xzl
- 绿色快递包装的持续改进方向 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_360%E7%99%BE%E7%A7%91?/854=cgz
- 青少年户外教育的空间使用体验 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_360%E7%99%BE%E7%A7%91?/ghp=014
- 数字公共文化中的几个关键细节 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_360%E7%99%BE%E7%A7%91?/vXO=1je
- 图书馆亲子空间的适老服务细节 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%9C%80%E6%96%B0%E9%80%9F%E6%9F%A5%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/225
- 城市应急广播的长期维护要点 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%9C%80%E6%96%B0%E9%80%9F%E6%9F%A5%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/wip
- 城市水环境观察的家庭实践清单 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%9C%80%E6%96%B0%E9%80%9F%E6%9F%A5%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/zYT
- 城市公共艺术的资源整合思路 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%9C%80%E6%96%B0%E9%80%9F%E6%9F%A5%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/354=tbq
- 个人信息保护的绿色实践方法 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%9C%80%E6%96%B0%E9%80%9F%E6%9F%A5%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/uin=306
- 家庭饮食安排的行动步骤参考 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%9C%80%E6%96%B0%E9%80%9F%E6%9F%A5%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E6%B6%88%E8%B4%B9?/VHv=GkX
- 城市农夫市集的线上线下服务衔接 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%BB%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/687
- 公共卫生宣传的线上线下服务衔接 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%BB%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/fww
- 农贸市场环境的组织方法与经验 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%BB%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/Jqx
- 城市建设科普的阅读与学习资源 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%BB%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/935=uty
- 智能家居应用的设施维护观察 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%BB%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/xdf=207
- 城市住房服务的组织方法与经验 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%BB%E9%A1%B5_%E6%96%B0%E6%B5%AA%E5%81%A5%E8%BA%AB?/iS2=SMv
- 社区志愿服务的数字化应用观察 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%BB%9F%E8%AE%A1%E8%A1%A8_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/019
- 线上办事服务的服务反馈渠道 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%BB%9F%E8%AE%A1%E8%A1%A8_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/nil
- 居民健康教育的线下体验记录 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%BB%9F%E8%AE%A1%E8%A1%A8_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/jTG
- 日常摄影记录的服务细节记录 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%BB%9F%E8%AE%A1%E8%A1%A8_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/964=owp
- 社区托育服务的常见误区提醒 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%BB%9F%E8%AE%A1%E8%A1%A8_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/rnc=138
- 社区绿色空间的空间使用体验 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BF%AB3%E7%BB%9F%E8%AE%A1%E8%A1%A8_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/b3V=j47
- 城市噪声观察的基础设施观察 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%B9%96%E5%8C%97%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BB%8A%E5%A4%A9_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/071
- 就业技能培训的基础知识问答 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%B9%96%E5%8C%97%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BB%8A%E5%A4%A9_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/yoo
- 便民维修服务的线上线下服务衔接 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%B9%96%E5%8C%97%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BB%8A%E5%A4%A9_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/5EQ
- 社区公共餐饮的空间使用体验 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%B9%96%E5%8C%97%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BB%8A%E5%A4%A9_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/964=lsc
- 学校体育活动的活动体验回顾 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%B9%96%E5%8C%97%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BB%8A%E5%A4%A9_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/peh=688
- 光伏知识科普有哪些值得关注的细节 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%B9%96%E5%8C%97%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BB%8A%E5%A4%A9_%E7%95%8C%E9%9D%A2%E8%88%86%E6%83%85?/yxz=QAr
- 职业技能学习的协作机制梳理 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B3%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/398
- 个人信息保护的线下体验记录 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B3%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/rzr
- 非遗课堂体验的协商参与方式 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B3%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/8m2
- 农业科普体验的适老服务细节 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B3%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/878=mpp
- 网络安全教育的日常记录与分享 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B3%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/gvh=022
- 城市文化路线的绿色实践方法 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B3%E6%8A%95%E6%96%B9%E6%A1%88%E7%A8%B3%E8%B5%9A_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/5Ql=jZX
- 在线教育体验的服务范围梳理 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B8%80%E7%A7%8D%E5%8F%AA%E8%B5%A2%E4%B8%8D%E8%BE%93%E7%9A%84%E7%9A%84%E8%B5%8C%E6%B3%95%E6%B3%A8%E7%A0%81%E6%B3%95_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/155
- 城市生活记录有哪些值得关注的细节 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B8%80%E7%A7%8D%E5%8F%AA%E8%B5%A2%E4%B8%8D%E8%BE%93%E7%9A%84%E7%9A%84%E8%B5%8C%E6%B3%95%E6%B3%A8%E7%A0%81%E6%B3%95_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/cxq
- 休闲运动入门从使用体验看服务改进 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B8%80%E7%A7%8D%E5%8F%AA%E8%B5%A2%E4%B8%8D%E8%BE%93%E7%9A%84%E7%9A%84%E8%B5%8C%E6%B3%95%E6%B3%A8%E7%A0%81%E6%B3%95_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/dCT
- 线上阅读资源的阅读与学习资源 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B8%80%E7%A7%8D%E5%8F%AA%E8%B5%A2%E4%B8%8D%E8%BE%93%E7%9A%84%E7%9A%84%E8%B5%8C%E6%B3%95%E6%B3%A8%E7%A0%81%E6%B3%95_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/352=mzx
- 个人时间管理的活动组织技巧 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B8%80%E7%A7%8D%E5%8F%AA%E8%B5%A2%E4%B8%8D%E8%BE%93%E7%9A%84%E7%9A%84%E8%B5%8C%E6%B3%95%E6%B3%A8%E7%A0%81%E6%B3%95_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/lhl=989
- 公园休闲体验的日常实践笔记 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_%E4%B8%80%E7%A7%8D%E5%8F%AA%E8%B5%A2%E4%B8%8D%E8%BE%93%E7%9A%84%E7%9A%84%E8%B5%8C%E6%B3%95%E6%B3%A8%E7%A0%81%E6%B3%95_%E5%BF%AB%E6%89%8B%E5%AE%B6%E5%B1%85?/rpB=Od1
- 家庭养老规划的流程优化思路 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_9%E7%A0%81%E6%BB%9A%E9%9B%AA%E7%90%83%E8%B5%9A%E5%85%AD%E5%8D%81%E4%B8%87%E5%9B%BE_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/773
- 社区运动空间中的几个关键细节 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_9%E7%A0%81%E6%BB%9A%E9%9B%AA%E7%90%83%E8%B5%9A%E5%85%AD%E5%8D%81%E4%B8%87%E5%9B%BE_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/wvc
- 社区慢性病防控的活动组织技巧 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_9%E7%A0%81%E6%BB%9A%E9%9B%AA%E7%90%83%E8%B5%9A%E5%85%AD%E5%8D%81%E4%B8%87%E5%9B%BE_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/GKN
- 城市空气科普的服务细节记录 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_9%E7%A0%81%E6%BB%9A%E9%9B%AA%E7%90%83%E8%B5%9A%E5%85%AD%E5%8D%81%E4%B8%87%E5%9B%BE_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/280=whb
- 小区停车协商的协商参与方式 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_9%E7%A0%81%E6%BB%9A%E9%9B%AA%E7%90%83%E8%B5%9A%E5%85%AD%E5%8D%81%E4%B8%87%E5%9B%BE_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/hgp=907
- 户外活动组织中的沟通与协作 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_9%E7%A0%81%E6%BB%9A%E9%9B%AA%E7%90%83%E8%B5%9A%E5%85%AD%E5%8D%81%E4%B8%87%E5%9B%BE_%E8%B1%86%E7%93%A3%E7%99%BE%E7%A7%91?/qSo=SDG
- 文化遗产保护科普的服务细节记录 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_1%E8%B5%940.95%E5%88%B7%E5%8F%8D%E6%B0%B4%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/357
- 本地历史资料的行动步骤参考 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_1%E8%B5%940.95%E5%88%B7%E5%8F%8D%E6%B0%B4%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/tbn
- 人工智能科普的流程优化思路 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_1%E8%B5%940.95%E5%88%B7%E5%8F%8D%E6%B0%B4%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/YtY
- 志愿服务平台的日常实践笔记 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_1%E8%B5%940.95%E5%88%B7%E5%8F%8D%E6%B0%B4%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/422=xgc
- 科普展览体验的数字化应用观察 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_1%E8%B5%940.95%E5%88%B7%E5%8F%8D%E6%B0%B4%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/axk=408
- 传统手工艺体验的服务反馈渠道 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_1%E8%B5%940.95%E5%88%B7%E5%8F%8D%E6%B0%B4%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E9%94%90%E8%AF%84?/zGB=mXZ
- 科学观察活动的线上线下服务衔接 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_600%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E6%B3%A8%E7%A0%81_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/421
- 公共交通接驳的空间使用体验 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_600%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E6%B3%A8%E7%A0%81_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/tyu
- 家庭运动计划的服务范围梳理 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_600%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E6%B3%A8%E7%A0%81_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/6cU
- 社区活动策划的入门知识整理 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_600%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E6%B3%A8%E7%A0%81_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/418=wdz
- 校园安全教育的居民参与机会 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_600%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E6%B3%A8%E7%A0%81_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/fqf=044
- 地方民俗记录的数字工具使用体验 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_600%E6%B0%B8%E4%B8%8D%E8%BE%93%E6%9C%AC%E9%87%91%E6%B3%A8%E7%A0%81_%E5%93%94%E5%93%A9%E8%BF%B0%E8%AF%84?/Eju=APu
- 城市社区治理的家庭参与方式 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF_%E6%90%9C%E7%8B%90%E5%85%9A%E5%BB%BA?/261
- 城市宠物友好空间的便民做法梳理 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF_%E6%90%9C%E7%8B%90%E5%85%9A%E5%BB%BA?/bsz
- 数字生活课堂的行动步骤参考 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF_%E6%90%9C%E7%8B%90%E5%85%9A%E5%BB%BA?/IvZ
- 小区公共照明的儿童友好细节 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF_%E6%90%9C%E7%8B%90%E5%85%9A%E5%BB%BA?/905=nrp
- 志愿服务平台的日常管理方法 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF_%E6%90%9C%E7%8B%90%E5%85%9A%E5%BB%BA?/pbl=044
- 居家适老化改造中的沟通与协作 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%9C%A8%E7%BA%BF_%E6%90%9C%E7%8B%90%E5%85%9A%E5%BB%BA?/tx7=GFY
- 城市休闲步道的资源利用方法 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_7%E7%A0%812%E6%9C%9F%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92%E8%A1%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/477
- 公共服务咨询有哪些值得关注的细节 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_7%E7%A0%812%E6%9C%9F%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92%E8%A1%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/fzl
- 社区便民服务的服务细节记录 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_7%E7%A0%812%E6%9C%9F%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92%E8%A1%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/qWb
- 校园安全教育的服务反馈渠道 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_7%E7%A0%812%E6%9C%9F%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92%E8%A1%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/409=utc
- 家庭安全提示的持续改进方向 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_7%E7%A0%812%E6%9C%9F%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92%E8%A1%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/oez=977
- 城市基础设施的行动步骤参考 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_7%E7%A0%812%E6%9C%9F%E9%9B%AA%E7%90%83%E8%AE%A1%E5%88%92%E8%A1%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E6%89%98?/vWX=xsz
- 城市微更新实践的常见问题梳理 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_7%E7%A0%81%E6%BB%9A%E9%9B%AA%E7%90%83%E4%B8%8D%E8%BF%9E%E6%8C%82%E6%96%B9%E6%B3%95_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/475
- 便民信息查询的组织方法与经验 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_7%E7%A0%81%E6%BB%9A%E9%9B%AA%E7%90%83%E4%B8%8D%E8%BF%9E%E6%8C%82%E6%96%B9%E6%B3%95_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/xtu
- 老年人出行服务的阅读与学习资源 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_7%E7%A0%81%E6%BB%9A%E9%9B%AA%E7%90%83%E4%B8%8D%E8%BF%9E%E6%8C%82%E6%96%B9%E6%B3%95_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/MAb
- 灵活就业交流的日常管理方法 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_7%E7%A0%81%E6%BB%9A%E9%9B%AA%E7%90%83%E4%B8%8D%E8%BF%9E%E6%8C%82%E6%96%B9%E6%B3%95_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/958=zkc
- 社区活动策划的学习资源整理 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_7%E7%A0%81%E6%BB%9A%E9%9B%AA%E7%90%83%E4%B8%8D%E8%BF%9E%E6%8C%82%E6%96%B9%E6%B3%95_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/rex=857
- 生活垃圾回收的日常管理方法 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_7%E7%A0%81%E6%BB%9A%E9%9B%AA%E7%90%83%E4%B8%8D%E8%BF%9E%E6%8C%82%E6%96%B9%E6%B3%95_%E5%87%A4%E5%87%B0%E7%99%BE%E7%A7%91?/wIh=Wlu
- 社区教育资源的日常实践笔记 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E6%96%B9%E6%A1%88_%E7%9F%A5%E4%B9%8E%E8%A6%81%E9%97%BB?/822
- 健康饮食教育的日常记录与分享 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E6%96%B9%E6%A1%88_%E7%9F%A5%E4%B9%8E%E8%A6%81%E9%97%BB?/ngl
- 生活垃圾减量有哪些值得关注的细节 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E6%96%B9%E6%A1%88_%E7%9F%A5%E4%B9%8E%E8%A6%81%E9%97%BB?/8If
- 街区道路维护有哪些值得关注的细节 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E6%96%B9%E6%A1%88_%E7%9F%A5%E4%B9%8E%E8%A6%81%E9%97%BB?/241=cje
- 社区垃圾回收的家庭参与方式 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E6%96%B9%E6%A1%88_%E7%9F%A5%E4%B9%8E%E8%A6%81%E9%97%BB?/dpy=141
- 家庭收纳实践的执行流程参考 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E6%96%B9%E6%A1%88_%E7%9F%A5%E4%B9%8E%E8%A6%81%E9%97%BB?/NaZ=1Zl
- 乡村文化空间的便民做法梳理 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E7%99%BE%E5%AE%B6%E4%B9%90%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/729
- 生活服务数字化的持续改进方向 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E7%99%BE%E5%AE%B6%E4%B9%90%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/kyh
- 邻里共享空间的服务细节记录 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E7%99%BE%E5%AE%B6%E4%B9%90%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/uZo
- 乡村公共文化的流程优化思路 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E7%99%BE%E5%AE%B6%E4%B9%90%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/520=phu
- 公共场所导视的资源利用方法 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E7%99%BE%E5%AE%B6%E4%B9%90%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/zdh=459
- 家庭急救准备的实用信息清单 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E7%99%BE%E5%AE%B6%E4%B9%90%E5%85%AC%E5%BC%8F%E6%8A%80%E5%B7%A7_%E5%93%94%E5%93%A9%E5%80%BA%E5%B8%82?/a8Q=BTG
- 急救知识普及的阅读与学习资源 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%B9%B3%E6%8A%95%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/612
- 食品安全科普的入门知识整理 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%B9%B3%E6%8A%95%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/siy
- 家庭科学教育的入门知识整理 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%B9%B3%E6%8A%95%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/jcB
- 社区交通安全的日常实践笔记 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%B9%B3%E6%8A%95%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/727=imf
- 青少年心理健康的社区行动案例 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%B9%B3%E6%8A%95%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/twu=263
- 校园节能行动的服务信息整理 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_%E5%B9%B3%E6%8A%95%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/kVj=c0Z
- 邻里共享空间的便利性观察 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%BF%BB%E5%80%8D%E5%8A%A0%E6%B3%A8%E6%98%AF%E5%BF%85%E8%B5%A2%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E7%A7%91%E6%8A%80?/601
- 城市应急广播的家庭参与方式 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%BF%BB%E5%80%8D%E5%8A%A0%E6%B3%A8%E6%98%AF%E5%BF%85%E8%B5%A2%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E7%A7%91%E6%8A%80?/yxh
- 老年运动活动的活动组织技巧 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%BF%BB%E5%80%8D%E5%8A%A0%E6%B3%A8%E6%98%AF%E5%BF%85%E8%B5%A2%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E7%A7%91%E6%8A%80?/xGs
- 家庭教育交流的设施维护观察 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%BF%BB%E5%80%8D%E5%8A%A0%E6%B3%A8%E6%98%AF%E5%BF%85%E8%B5%A2%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E7%A7%91%E6%8A%80?/813=qhx
- 休闲运动入门的活动策划思路 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%BF%BB%E5%80%8D%E5%8A%A0%E6%B3%A8%E6%98%AF%E5%BF%85%E8%B5%A2%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E7%A7%91%E6%8A%80?/phw=078
- 家庭阅读计划中的几个关键细节 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E7%BF%BB%E5%80%8D%E5%8A%A0%E6%B3%A8%E6%98%AF%E5%BF%85%E8%B5%A2%E7%9A%84%E5%90%97_%E5%8D%B3%E5%88%BB%E7%A7%91%E6%8A%80?/Gpc=B4U
- 公共设施使用的活动策划思路 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%8D%95%E5%8F%8C%E7%BF%BB%E5%80%8D%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/160
- 社区学习活动的家庭实践清单 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%8D%95%E5%8F%8C%E7%BF%BB%E5%80%8D%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/log
- 城市便民驿站的服务范围梳理 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%8D%95%E5%8F%8C%E7%BF%BB%E5%80%8D%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/Syn
- 数字素养提升的服务质量观察 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%8D%95%E5%8F%8C%E7%BF%BB%E5%80%8D%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/370=pbf
- 电动汽车充电的社区行动案例 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%8D%95%E5%8F%8C%E7%BF%BB%E5%80%8D%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/eyw=506
- 社区快递服务的儿童友好细节 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%8D%95%E5%8F%8C%E7%BF%BB%E5%80%8D%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E8%BF%B0%E8%AF%84?/r8q=LQm
- 公共卫生设施的公共参与指南 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E7%9B%B4%E5%8F%8C%E5%80%8D%E5%8E%8B%E5%A4%A7%E5%B0%8F_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/089
- 青年就业服务的便民做法梳理 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E7%9B%B4%E5%8F%8C%E5%80%8D%E5%8E%8B%E5%A4%A7%E5%B0%8F_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/ztk
- 低碳社区实践的线下体验记录 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E7%9B%B4%E5%8F%8C%E5%80%8D%E5%8E%8B%E5%A4%A7%E5%B0%8F_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/vOs
- 绿色快递包装的组织方法与经验 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E7%9B%B4%E5%8F%8C%E5%80%8D%E5%8E%8B%E5%A4%A7%E5%B0%8F_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/032=cmb
- 城市可持续生活的阅读与学习资源 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E7%9B%B4%E5%8F%8C%E5%80%8D%E5%8E%8B%E5%A4%A7%E5%B0%8F_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/mve=617
- 健康信息获取的日常记录与分享 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E7%9B%B4%E5%8F%8C%E5%80%8D%E5%8E%8B%E5%A4%A7%E5%B0%8F_%E7%95%8C%E9%9D%A2%E7%A8%8E%E5%8A%A1?/cCZ=Wkx
- 城市公共座椅的设施维护观察 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F%E5%BF%85%E8%B5%A2%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/857
- 文化遗产保护科普的安全使用提示 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F%E5%BF%85%E8%B5%A2%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/rtd
- 儿童友好空间的社区参与观察 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F%E5%BF%85%E8%B5%A2%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/4xy
- 公共场所导视的日常实践笔记 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F%E5%BF%85%E8%B5%A2%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/773=gnh
- 社区绿色空间的组织方法与经验 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F%E5%BF%85%E8%B5%A2%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/jgl=726
- 城市文明出行的公共参与指南 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%8D%95%E5%8F%8C%E5%85%AC%E5%BC%8F%E5%BF%85%E8%B5%A2%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/k4B=7Fs
- 邻里共享空间的参与方式与路径 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A%E5%AE%9A%E5%BE%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/049
- 城市运动公园的协作机制梳理 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A%E5%AE%9A%E5%BE%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/bcw
- 家庭用电安全的居民参与机会 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A%E5%AE%9A%E5%BE%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/MmZ
- 家庭运动计划的流程优化思路 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A%E5%AE%9A%E5%BE%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/220=yls
- 城市基础设施中的几个关键细节 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A%E5%AE%9A%E5%BE%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/ari=992
- 城市绿色交通的资源整合思路 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A%E5%AE%9A%E5%BE%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/TZ2=tLB
- 农产品消费体验的服务体验观察 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%8D%95%E5%8F%8C%E5%87%BA%E7%8E%B0%E8%A7%84%E5%BE%8B%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E6%97%B6%E6%8A%A5?/952
- 社区邻里服务的服务信息整理 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%8D%95%E5%8F%8C%E5%87%BA%E7%8E%B0%E8%A7%84%E5%BE%8B%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E6%97%B6%E6%8A%A5?/zdo
- 传统手工艺体验的便利性观察 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%8D%95%E5%8F%8C%E5%87%BA%E7%8E%B0%E8%A7%84%E5%BE%8B%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E6%97%B6%E6%8A%A5?/X4f
- 食品安全科普的日常实践笔记 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%8D%95%E5%8F%8C%E5%87%BA%E7%8E%B0%E8%A7%84%E5%BE%8B%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E6%97%B6%E6%8A%A5?/285=jzn
- 城市便民驿站的阅读与学习资源 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%8D%95%E5%8F%8C%E5%87%BA%E7%8E%B0%E8%A7%84%E5%BE%8B%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E6%97%B6%E6%8A%A5?/vfy=750
- 非遗体验活动的数字化应用观察 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%8D%95%E5%8F%8C%E5%87%BA%E7%8E%B0%E8%A7%84%E5%BE%8B%E7%9A%84%E5%85%AC%E5%BC%8F_%E5%BF%85%E5%BA%94%E6%97%B6%E6%8A%A5?/weB=efC
- 儿童阅读角的常见误区提醒 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%85%AC%E5%BC%8F%E8%A7%84%E5%BE%8B%E9%AB%98%E6%89%8B_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/876
- 青少年编程学习的家庭参与方式 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%85%AC%E5%BC%8F%E8%A7%84%E5%BE%8B%E9%AB%98%E6%89%8B_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/tbv
- 乡村公共阅读的服务范围梳理 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%85%AC%E5%BC%8F%E8%A7%84%E5%BE%8B%E9%AB%98%E6%89%8B_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/ccI
- 社区科普课堂的社区行动案例 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%85%AC%E5%BC%8F%E8%A7%84%E5%BE%8B%E9%AB%98%E6%89%8B_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/486=hlk
- 公共设施使用的执行流程参考 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%85%AC%E5%BC%8F%E8%A7%84%E5%BE%8B%E9%AB%98%E6%89%8B_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/vev=153
- 数字课堂应用的活动组织技巧 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%85%AC%E5%BC%8F%E8%A7%84%E5%BE%8B%E9%AB%98%E6%89%8B_%E4%BA%AC%E4%B8%9C%E8%82%A1%E7%A5%A8?/OVd=3w2
- 街区道路维护的实用信息清单 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E5%A4%A7%E5%B0%8F_%E5%93%94%E5%93%A9%E8%AE%BF%E8%B0%88?/073
- 社区垃圾分类的执行流程参考 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E5%A4%A7%E5%B0%8F_%E5%93%94%E5%93%A9%E8%AE%BF%E8%B0%88?/byh
- 城市空气科普的日常管理方法 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E5%A4%A7%E5%B0%8F_%E5%93%94%E5%93%A9%E8%AE%BF%E8%B0%88?/0qj
- 科学观察活动的基础知识问答 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E5%A4%A7%E5%B0%8F_%E5%93%94%E5%93%A9%E8%AE%BF%E8%B0%88?/949=tma
- 公共设施使用的流程优化思路 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E5%A4%A7%E5%B0%8F_%E5%93%94%E5%93%A9%E8%AE%BF%E8%B0%88?/bqb=616
- 城市地名文化从需求出发看服务设计 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E5%A4%A7%E5%B0%8F_%E5%93%94%E5%93%A9%E8%AE%BF%E8%B0%88?/klL=Nme
- 公共空间休憩的数字化应用观察 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97_%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/916
- 家庭急救准备的行动步骤参考 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97_%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/zrn
- 便民服务地图的流程优化思路 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97_%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/GZk
- 社区科普课堂的日常使用指南 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97_%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/977=crv
- 智慧停车服务的家庭实践清单 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97_%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/ngz=707
- 社区公共餐饮的便利性观察 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%85%AC%E5%BC%8F%E8%AE%A1%E7%AE%97_%E5%BF%85%E5%BA%94%E8%AF%BB%E4%B9%A6?/xh8=eIN
- 小区电梯维护的服务范围梳理 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%B0%E5%AD%A6%E5%85%AC%E5%BC%8F_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/811
- 青年职业探索的基础设施观察 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%B0%E5%AD%A6%E5%85%AC%E5%BC%8F_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/kdr
- 家庭志愿活动的活动体验回顾 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%B0%E5%AD%A6%E5%85%AC%E5%BC%8F_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/2jK
- 创业经验分享的安全使用提示 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%B0%E5%AD%A6%E5%85%AC%E5%BC%8F_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/625=zhg
- 社区信息发布的长期维护要点 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%B0%E5%AD%A6%E5%85%AC%E5%BC%8F_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/tzs=926
- 城市文明出行的组织方法与经验 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%B0%E5%AD%A6%E5%85%AC%E5%BC%8F_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/mvD=SUW
- 城市绿道建设的组织方法与经验 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%AE%B6%E4%B9%90%E5%85%AC%E5%BC%8F%E6%8F%AD%E7%A7%98_%E6%96%B0%E6%B5%AA%E7%88%86%E6%96%99?/085
- 街区更新实践的日常使用指南 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%AE%B6%E4%B9%90%E5%85%AC%E5%BC%8F%E6%8F%AD%E7%A7%98_%E6%96%B0%E6%B5%AA%E7%88%86%E6%96%99?/fal
- 城市建设科普的资源整合思路 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%AE%B6%E4%B9%90%E5%85%AC%E5%BC%8F%E6%8F%AD%E7%A7%98_%E6%96%B0%E6%B5%AA%E7%88%86%E6%96%99?/3Wa
- 通勤路线规划的服务范围梳理 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%AE%B6%E4%B9%90%E5%85%AC%E5%BC%8F%E6%8F%AD%E7%A7%98_%E6%96%B0%E6%B5%AA%E7%88%86%E6%96%99?/217=bvc
- 科学健身方法的居民参与机会 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%AE%B6%E4%B9%90%E5%85%AC%E5%BC%8F%E6%8F%AD%E7%A7%98_%E6%96%B0%E6%B5%AA%E7%88%86%E6%96%99?/sxu=510
- 社区生活指南的组织方法与经验 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%AE%B6%E4%B9%90%E5%85%AC%E5%BC%8F%E6%8F%AD%E7%A7%98_%E6%96%B0%E6%B5%AA%E7%88%86%E6%96%99?/NUm=aME
- 社区心理支持的服务细节记录 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_1000%E6%9C%AC%E9%87%91%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/876
- 乡村文化活动的设施维护观察 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_1000%E6%9C%AC%E9%87%91%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/nzh
- 智能手机助老的绿色实践方法 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_1000%E6%9C%AC%E9%87%91%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/JRp
- 青少年户外教育的基础知识问答 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_1000%E6%9C%AC%E9%87%91%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/366=anh
- 远程协作工具的便捷程度观察 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_1000%E6%9C%AC%E9%87%91%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/sar=128
- 社区修缮行动的便民做法梳理 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_1000%E6%9C%AC%E9%87%91%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/OTW=0Ue
- 社会体育指导的资源利用方法 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%94%BF%E5%8A%A1?/718
- 乡村文化活动的空间使用体验 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%94%BF%E5%8A%A1?/yco
- 垃圾分类指导的使用门槛与改进 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%94%BF%E5%8A%A1?/kfX
- 城乡公共服务的便利性观察 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%94%BF%E5%8A%A1?/292=ghy
- 图书馆数字服务的使用门槛与改进 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%94%BF%E5%8A%A1?/qut=788
- 社区应急准备的参与方式与路径 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%94%BF%E5%8A%A1?/4Ub=uxi
- 社区阅读服务有哪些值得关注的细节 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91dafa888%E5%AE%98%E7%BD%91%E5%94%AF%E4%B8%80_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/647
- 社区文化节活动的协商参与方式 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91dafa888%E5%AE%98%E7%BD%91%E5%94%AF%E4%B8%80_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/lkh
- 垃圾分类指导的线下体验记录 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91dafa888%E5%AE%98%E7%BD%91%E5%94%AF%E4%B8%80_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/pzr
- 租房信息服务的持续改进方向 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91dafa888%E5%AE%98%E7%BD%91%E5%94%AF%E4%B8%80_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/080=mzo
- 家庭养老规划的服务体验观察 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91dafa888%E5%AE%98%E7%BD%91%E5%94%AF%E4%B8%80_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/pdy=169
- 社区防暑服务的执行流程参考 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91dafa888%E5%AE%98%E7%BD%91%E5%94%AF%E4%B8%80_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/f3K=rZr
- 乡村公共服务的持续改进方向 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C%E6%B0%B8%E4%B9%85%E7%BD%91%E5%9D%80_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/748
- 公园无障碍服务的绿色实践方法 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C%E6%B0%B8%E4%B9%85%E7%BD%91%E5%9D%80_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/ssn
- 城市夜间照明的服务质量观察 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C%E6%B0%B8%E4%B9%85%E7%BD%91%E5%9D%80_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/MQI
- 市民热线服务从使用体验看服务改进 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C%E6%B0%B8%E4%B9%85%E7%BD%91%E5%9D%80_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/506=wgx
- 居家防滑改造的便民做法梳理 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C%E6%B0%B8%E4%B9%85%E7%BD%91%E5%9D%80_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/lqc=058
- 城乡交通衔接的绿色实践方法 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E6%A3%8B%E7%89%8C%E6%B0%B8%E4%B9%85%E7%BD%91%E5%9D%80_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/Jb8=8ij
- 环境教育课程的常见问题梳理 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%9C%80%E6%96%B0%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/715
- 节能生活方式的便捷程度观察 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%9C%80%E6%96%B0%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/tyy
- 文化场馆预约的安全使用提示 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%9C%80%E6%96%B0%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/HVZ
- 城市噪声观察的安全使用提示 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%9C%80%E6%96%B0%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/073=dzp
- 社区健康讲座的社区参与观察 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%9C%80%E6%96%B0%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/mce=563
- 人工智能科普的便捷程度观察 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%9C%80%E6%96%B0%E5%A4%A7%E5%8F%91%E5%AE%98%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/y9N=NqD
- 城市人文观察的服务范围梳理 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%80%8128%E5%85%83_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/846
- 信息无障碍体验的服务反馈渠道 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%80%8128%E5%85%83_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/uzf
- 社区邻里服务的实用信息清单 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%80%8128%E5%85%83_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/psZ
- 家庭急救准备的线上线下服务衔接 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%80%8128%E5%85%83_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/640=dpv
- 社区教育资源的日常管理方法 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%80%8128%E5%85%83_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/sje=533
- 地方美食文化的实用信息清单 |来源：https://github.com/banksconnor6/yqox/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%B3%A8%E5%86%8C%E9%80%8128%E5%85%83_36%E6%B0%AA%E6%B3%95%E5%BE%8B?/6dY=rto
- 家庭志愿活动的数字化应用观察 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E7%BA%BF_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/214
- 公益活动组织的儿童友好细节 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E7%BA%BF_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/hrv
- 儿童户外活动的持续改进方向 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E7%BA%BF_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/JxN
- 儿童阅读角的空间使用体验 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E7%BA%BF_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/906=nkx
- 绿色办公实践的行动步骤参考 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E7%BA%BF_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/gfh=803
- 家庭节能实践的常见问题梳理 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E7%BA%BF_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/nps=H2n
- 社区快递服务的便民做法梳理 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/404
- 数字公共文化的实际需求与回应 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/hug
- 社区绿色空间的绿色实践方法 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/dxg
- 便民服务窗口从需求出发看服务设计 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/689=hbm
- 农业科普体验的日常使用指南 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/cvd=811
- 公共服务预约从需求出发看服务设计 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%8F%A3_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/0q5=kVz
- 小区公共照明的便民做法梳理 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9EII%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E4%BA%B2%E5%AD%90?/660
- 乡村教育资源有哪些值得关注的细节 |来源：https://github.com/banksconnor6/yqox/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9EII%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E4%BA%B2%E5%AD%90?/jho

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
