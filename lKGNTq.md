# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:30**

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

- 公交无障碍服务的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/336
- 社区便民服务的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/hcw
- 家庭志愿活动的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/X0N
- 公园亲子设施的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/590=eyu
- 城市水环境观察的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/xom=079
- 音乐欣赏活动的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/C8r=h7V
- 无障碍信息设计的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E5%8C%BB%E8%8D%AF?/331
- 城市公共空间的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E5%8C%BB%E8%8D%AF?/pxa
- 网络信息辨识的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E5%8C%BB%E8%8D%AF?/lFW
- 社区公共议事中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E5%8C%BB%E8%8D%AF?/827=hbg
- 城市步行环境的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E5%8C%BB%E8%8D%AF?/dmm=890
- 公共设施维护的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E4%BA%AC%E4%B8%9C%E5%8C%BB%E8%8D%AF?/WYq=Gbc
- 儿童运动体验的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1_%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/148
- 家庭收纳实践的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1_%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/prn
- 绿色出行服务的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1_%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/eVt
- 绿色快递包装的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1_%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/532=awn
- 家庭安全提示的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1_%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/rys=420
- 社区生活指南的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%8C%85%E8%B5%9A%E5%8C%85%E8%B5%94%E8%AE%A1%E5%88%92%E5%BE%AE%E4%BF%A1_%E8%99%8E%E5%97%85%E5%8F%B8%E6%B3%95?/bzF=y2z
- 社区托育服务的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%8D%E9%A5%B0?/088
- 家庭理财科普的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%8D%E9%A5%B0?/kng
- 音乐欣赏活动的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%8D%E9%A5%B0?/SY5
- 公共空间休憩的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%8D%E9%A5%B0?/775=krk
- 科技馆参观体验的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%8D%E9%A5%B0?/sac=338
- 城市公共自行车的协作机制梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1app%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%8D%E9%A5%B0?/gSh=9QR
- 本地旅行体验的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1APP_%E9%9B%85%E8%99%8E%E7%A4%BE%E8%AE%BA?/610
- 软件开发学习的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1APP_%E9%9B%85%E8%99%8E%E7%A4%BE%E8%AE%BA?/fgf
- 亲子阅读活动的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1APP_%E9%9B%85%E8%99%8E%E7%A4%BE%E8%AE%BA?/jBL
- 社区垃圾回收的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1APP_%E9%9B%85%E8%99%8E%E7%A4%BE%E8%AE%BA?/043=xbs
- 智能手机助老的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1APP_%E9%9B%85%E8%99%8E%E7%A4%BE%E8%AE%BA?/nlb=242
- 家庭消费规划的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E9%92%B1APP_%E9%9B%85%E8%99%8E%E7%A4%BE%E8%AE%BA?/1B9=psW
- 公园休闲体验的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E7%A8%B3%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/207
- 社区互助网络的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E7%A8%B3%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/opw
- 安全出行教育中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E7%A8%B3%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/iih
- 家庭安全提示的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E7%A8%B3%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/537=dti
- 城市地名文化从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E7%A8%B3%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/yvn=859
- 家庭健康科普的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_%E7%A8%B3%E8%B5%9A%E5%AF%BC%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1%E5%BE%AE%E4%BF%A1_%E5%93%94%E5%93%A9%E6%8A%95%E7%A8%BF?/1CT=lUv
- 农村环境治理的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/080
- 儿童户外活动的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/jac
- 学校体育活动的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/a3J
- 社区设施共享的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/642=cho
- 儿童运动体验的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/wtv=669
- 城市社区治理的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E7%A8%B3%E5%AE%9A%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/WFn=hO0
- 小微企业服务的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/473
- 青年就业服务的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/ejm
- 生活垃圾回收的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/FrR
- 地方美食文化的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/433=igy
- 社区互助网络的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/jbv=315
- 户外活动组织的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88_%E5%90%AF%E8%88%AA%E8%B4%A2%E7%BB%8F?/5tR=F1W
- 节假日出行安排的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%89%8B%E8%AE%B0?/444
- 家庭养老规划的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%89%8B%E8%AE%B0?/rvw
- 社区托育服务的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%89%8B%E8%AE%B0?/QRf
- 绿色快递包装的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%89%8B%E8%AE%B0?/677=nxk
- 城乡交流活动的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%89%8B%E8%AE%B0?/uqe=593
- 气象科普传播的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%A7%92%E9%80%9F%E5%BF%AB3%E8%AE%A1%E5%88%92_%E7%9F%A5%E4%B9%8E%E6%89%8B%E8%AE%B0?/0B0=GAM
- 社区快递服务的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E5%9B%BD%E5%86%85?/417
- 个人信息保护的长期维护要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E5%9B%BD%E5%86%85?/qeg
- 社区便民集市的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E5%9B%BD%E5%86%85?/PP1
- 远程协作工具的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E5%9B%BD%E5%86%85?/110=pfu
- 周末休闲规划的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E5%9B%BD%E5%86%85?/fdo=557
- 社区故事采集的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E9%A6%99%E6%B8%AF%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E5%9B%BD%E5%86%85?/V6B=wp2
- 城市休闲步道的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E9%87%8D%E5%BA%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%82%AF%E5%B0%BC%E8%B4%A2%E7%BB%8F?/510
- 劳动教育实践的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E9%87%8D%E5%BA%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%82%AF%E5%B0%BC%E8%B4%A2%E7%BB%8F?/aoh
- 家庭环保行动的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E9%87%8D%E5%BA%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%82%AF%E5%B0%BC%E8%B4%A2%E7%BB%8F?/agp
- 农产品品牌传播的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E9%87%8D%E5%BA%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%82%AF%E5%B0%BC%E8%B4%A2%E7%BB%8F?/536=kco
- 社区科普课堂的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E9%87%8D%E5%BA%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%82%AF%E5%B0%BC%E8%B4%A2%E7%BB%8F?/wog=152
- 农产品品牌传播的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_%E9%87%8D%E5%BA%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%82%AF%E5%B0%BC%E8%B4%A2%E7%BB%8F?/hn9=BwX
- 智能手机助老的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%AF%8C%E5%BD%A9%E5%AE%B6%E5%BF%AB3%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/667
- 街区道路维护的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%AF%8C%E5%BD%A9%E5%AE%B6%E5%BF%AB3%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/fry
- 周末休闲规划的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%AF%8C%E5%BD%A9%E5%AE%B6%E5%BF%AB3%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/1tn
- 公共卫生宣传的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%AF%8C%E5%BD%A9%E5%AE%B6%E5%BF%AB3%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/362=wwk
- 儿童户外活动的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%AF%8C%E5%BD%A9%E5%AE%B6%E5%BF%AB3%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/qps=333
- 社区文化传播的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%AF%8C%E5%BD%A9%E5%AE%B6%E5%BF%AB3%E8%AE%A1%E5%88%92_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/gZs=T4r
- 零废弃生活尝试的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_24%E5%B0%8F%E6%97%B6%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BD%91_%E6%90%9C%E7%8B%97%E5%9B%BD%E5%86%85?/140
- 家庭园艺实践的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_24%E5%B0%8F%E6%97%B6%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BD%91_%E6%90%9C%E7%8B%97%E5%9B%BD%E5%86%85?/fdk
- 社区休闲设施的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_24%E5%B0%8F%E6%97%B6%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BD%91_%E6%90%9C%E7%8B%97%E5%9B%BD%E5%86%85?/bcf
- 城市步行环境从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_24%E5%B0%8F%E6%97%B6%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BD%91_%E6%90%9C%E7%8B%97%E5%9B%BD%E5%86%85?/407=qst
- 公共场馆服务的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_24%E5%B0%8F%E6%97%B6%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BD%91_%E6%90%9C%E7%8B%97%E5%9B%BD%E5%86%85?/dwr=073
- 图书馆数字服务的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_24%E5%B0%8F%E6%97%B6%E5%BF%AB%E4%B8%89%E8%AE%A1%E5%88%92%E7%BD%91_%E6%90%9C%E7%8B%97%E5%9B%BD%E5%86%85?/cTr=03h
- 社区文化节活动的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%9124%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/807
- 社区慢性病防控的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%9124%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/dff
- 城市绿道建设的日常记录与分享 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%9124%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/uRw
- 家庭陪伴活动的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%9124%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/862=gnq
- 绿色建筑理念的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%9124%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/qsw=589
- 城市雨天出行的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%9124%E4%B8%AA%E5%B0%8F%E6%97%B6%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%85%BE%E8%AE%AF%E8%A7%82%E5%AF%9F?/kTL=A2t
- 图书馆亲子空间的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/463
- 公共服务沟通的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/sva
- 图书馆数字服务的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/lHk
- 电子商务服务的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/666=kgo
- 健康步道使用的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/ygq=336
- 街区更新实践中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E4%B8%89%E5%88%86%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/2gP=N64
- 社区邻里服务的家庭实践清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%89%E4%BA%BA%E5%B8%A6%E5%8F%AF%E4%BF%A1%E5%90%97_%E5%A4%AE%E8%A7%86%E4%B9%A6%E7%94%BB?/800
- 街区道路维护的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%89%E4%BA%BA%E5%B8%A6%E5%8F%AF%E4%BF%A1%E5%90%97_%E5%A4%AE%E8%A7%86%E4%B9%A6%E7%94%BB?/rgd
- 社区活动空间的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%89%E4%BA%BA%E5%B8%A6%E5%8F%AF%E4%BF%A1%E5%90%97_%E5%A4%AE%E8%A7%86%E4%B9%A6%E7%94%BB?/NaN
- 劳动教育实践的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%89%E4%BA%BA%E5%B8%A6%E5%8F%AF%E4%BF%A1%E5%90%97_%E5%A4%AE%E8%A7%86%E4%B9%A6%E7%94%BB?/393=opz
- 公益活动组织的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%89%E4%BA%BA%E5%B8%A6%E5%8F%AF%E4%BF%A1%E5%90%97_%E5%A4%AE%E8%A7%86%E4%B9%A6%E7%94%BB?/qxl=247
- 生活服务数字化的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E8%AE%A1%E5%88%92%E6%9C%89%E4%BA%BA%E5%B8%A6%E5%8F%AF%E4%BF%A1%E5%90%97_%E5%A4%AE%E8%A7%86%E4%B9%A6%E7%94%BB?/msG=joL
- 基层服务创新的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E4%B8%80%E4%B8%AA%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%95%99%E8%82%B2?/392
- 社区生活指南的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E4%B8%80%E4%B8%AA%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%95%99%E8%82%B2?/wcb
- 信息无障碍体验的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E4%B8%80%E4%B8%AA%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%95%99%E8%82%B2?/xcc
- 本地消费场景的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E4%B8%80%E4%B8%AA%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%95%99%E8%82%B2?/897=ewx
- 社区便利生活的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E4%B8%80%E4%B8%AA%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%95%99%E8%82%B2?/nug=328
- 家庭饮食安排的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E4%B8%80%E4%B8%AA%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%95%99%E8%82%B2?/Zdu=HOP
- 便民维修服务的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%925%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF_%E8%8A%92%E6%9E%9C%E6%BC%AB%E8%AF%84?/055
- 亲子阅读活动的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%925%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF_%E8%8A%92%E6%9E%9C%E6%BC%AB%E8%AF%84?/qcf
- 软件开发学习的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%925%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF_%E8%8A%92%E6%9E%9C%E6%BC%AB%E8%AF%84?/5ms
- 数字学习资源的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%925%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF_%E8%8A%92%E6%9E%9C%E6%BC%AB%E8%AF%84?/167=hbw
- 农村环境治理的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%925%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF_%E8%8A%92%E6%9E%9C%E6%BC%AB%E8%AF%84?/qnc=276
- 文化场馆预约的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%925%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF_%E8%8A%92%E6%9E%9C%E6%BC%AB%E8%AF%84?/xbO=q4J
- 科技馆参观体验中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%A1%A3%E6%A1%88?/768
- 小区公共照明的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%A1%A3%E6%A1%88?/ulj
- 乡村文化空间的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%A1%A3%E6%A1%88?/Fug
- 青少年科普实践的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%A1%A3%E6%A1%88?/168=zjg
- 社区运动空间的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%A1%A3%E6%A1%88?/vpx=684
- 家庭科学教育的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8F%91%E4%BA%BA%E5%B7%A5%E7%B2%BE%E5%87%86%E5%85%A8%E5%A4%A9%E8%AE%A1%E5%88%92_%E5%A4%AE%E8%A7%86%E6%A1%A3%E6%A1%88?/2Ia=UE9
- 社区生活指南的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BC%98%E9%85%B7%E8%BD%AC%E8%BD%BD?/730
- 社区教育资源的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BC%98%E9%85%B7%E8%BD%AC%E8%BD%BD?/due
- 社区文化节活动的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BC%98%E9%85%B7%E8%BD%AC%E8%BD%BD?/yqa
- 社会体育指导的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BC%98%E9%85%B7%E8%BD%AC%E8%BD%BD?/090=vwi
- 社区应急准备的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BC%98%E9%85%B7%E8%BD%AC%E8%BD%BD?/obw=423
- 个人信息保护的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E9%9D%A0%E8%B0%B1%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%BC%98%E9%85%B7%E8%BD%AC%E8%BD%BD?/Ya0=AyP
- 公共空间休憩的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/029
- 绿色校园实践的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/kud
- 城市公共艺术的阅读与学习资源 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/CHn
- 绿色消费选择的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/420=sik
- 公共场馆服务从使用体验看服务改进 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/ezf=201
- 社区垃圾回收的参与方式与路径 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%A8%B3%E8%B5%9A_%E9%A1%BA%E4%B8%B0%E6%A6%9C%E5%8D%95?/iTZ=8Xv
- 家庭园艺实践的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%BC%80%E6%8C%82%E8%BE%85%E5%8A%A9%E5%99%A8_%E6%90%9C%E7%8B%97%E4%BA%B2%E5%AD%90?/545
- 社区家政服务的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%BC%80%E6%8C%82%E8%BE%85%E5%8A%A9%E5%99%A8_%E6%90%9C%E7%8B%97%E4%BA%B2%E5%AD%90?/nxb
- 居家适老化改造的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%BC%80%E6%8C%82%E8%BE%85%E5%8A%A9%E5%99%A8_%E6%90%9C%E7%8B%97%E4%BA%B2%E5%AD%90?/yVZ
- 数字政务体验的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%BC%80%E6%8C%82%E8%BE%85%E5%8A%A9%E5%99%A8_%E6%90%9C%E7%8B%97%E4%BA%B2%E5%AD%90?/028=voc
- 健康饮食教育的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%BC%80%E6%8C%82%E8%BE%85%E5%8A%A9%E5%99%A8_%E6%90%9C%E7%8B%97%E4%BA%B2%E5%AD%90?/tcr=096
- 地方文化传播的常见问题梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%BC%80%E6%8C%82%E8%BE%85%E5%8A%A9%E5%99%A8_%E6%90%9C%E7%8B%97%E4%BA%B2%E5%AD%90?/UQE=TzN
- 社区体育组织的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/554
- 乡村公共服务的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/juc
- 社区交通安全的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/D6j
- 社区故事采集的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/720=iww
- 社区公共议事有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/hvq=647
- 个人时间管理的持续改进方向 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E5%8A%A8%E6%BC%AB?/RQs=RRL
- 城市休闲步道的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AE%AF?/295
- 青少年职业启蒙的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AE%AF?/jdi
- 个人时间管理的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AE%AF?/UJI
- 城市人文观察的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AE%AF?/464=tlk
- 数字素养提升的服务信息整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AE%AF?/shd=986
- 社区手工活动的使用门槛与改进 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%9B%A2%E9%98%9F%E5%AF%BC%E5%B8%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AE%AF?/H5L=1uw
- 社区消防演练的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/037
- 乡村文化活动的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/seq
- 租房信息服务的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/rSP
- 社区活动报名的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/406=lnw
- 公共服务预约从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/noa=891
- 青少年编程学习中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AE%A1%E5%88%92_%E7%95%8C%E9%9D%A2%E8%A7%86%E9%A2%91?/QTC=BzV
- 新能源知识普及的社区行动案例 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/148
- 城市公共自行车的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/aoo
- 数字便民地图的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/Pwp
- 便民信息查询的服务体验观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/505=icw
- 青年就业服务的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/rdr=507
- 本地旅行体验的基础设施观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E7%A8%B3%E5%AE%9A%E5%A4%A7%E5%B0%8F%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/n80=fOz
- 城市地名文化的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E5%BF%AB3%E6%B0%B8%E4%B9%85%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/700
- 社区手工活动的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E5%BF%AB3%E6%B0%B8%E4%B9%85%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/tnj
- 户外活动组织中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E5%BF%AB3%E6%B0%B8%E4%B9%85%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/v2n
- 社区共享书架的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E5%BF%AB3%E6%B0%B8%E4%B9%85%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/863=wdz
- 老年人出行服务的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E5%BF%AB3%E6%B0%B8%E4%B9%85%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/vjp=717
- 社区手工活动的执行流程参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E5%BF%AB3%E6%B0%B8%E4%B9%85%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B0%B7%E6%AD%8C%E8%B5%84%E8%AE%AF?/AjB=N3A
- 个人信息保护的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/156
- 社区休闲设施的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/yjq
- 城市空气科普的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/o4R
- 社区健康讲座中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/975=onj
- 社区交通安全的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/hca=560
- 小微企业服务的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B1%86%E7%93%A3%E9%97%AE%E7%AD%94?/jVU=eNV
- 城市运动公园的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%9E%E6%97%B6%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%8E%E4%BA%8B?/417
- 城市文明出行的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%9E%E6%97%B6%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%8E%E4%BA%8B?/kve
- 数字地图应用中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%9E%E6%97%B6%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%8E%E4%BA%8B?/gIg
- 地方民俗记录的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%9E%E6%97%B6%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%8E%E4%BA%8B?/657=faq
- 公园无障碍服务的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%9E%E6%97%B6%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%8E%E4%BA%8B?/vkh=014
- 亲子阅读活动的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%9E%E6%97%B6%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%8E%E4%BA%8B?/lj0=E96
- 智能家居应用的数字工具使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81QQ%E7%BE%A4_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/424
- 运动安全知识的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81QQ%E7%BE%A4_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/dnr
- 家庭网络使用的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81QQ%E7%BE%A4_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/rIV
- 家庭志愿活动的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81QQ%E7%BE%A4_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/627=rhb
- 电动汽车充电的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81QQ%E7%BE%A4_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/zsu=859
- 社区便民服务的儿童友好细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E8%AE%A1%E5%88%92%E4%BA%A4%E6%B5%81QQ%E7%BE%A4_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/tnH=uT4
- 无障碍信息设计的居民参与机会 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4QQ_%E8%8A%92%E6%9E%9C%E5%9B%AD%E8%89%BA?/181
- 课后服务体验的学习资源整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4QQ_%E8%8A%92%E6%9E%9C%E5%9B%AD%E8%89%BA?/pxt
- 机器学习入门的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4QQ_%E8%8A%92%E6%9E%9C%E5%9B%AD%E8%89%BA?/tM2
- 公共设施使用的资源利用方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4QQ_%E8%8A%92%E6%9E%9C%E5%9B%AD%E8%89%BA?/607=hdz
- 软件开发学习的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4QQ_%E8%8A%92%E6%9E%9C%E5%9B%AD%E8%89%BA?/jqt=094
- 城市体育设施的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4QQ_%E8%8A%92%E6%9E%9C%E5%9B%AD%E8%89%BA?/9AQ=XyV
- 学校体育活动的活动体验回顾 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E5%A4%B4%E6%9D%A1%E8%A7%82%E5%AF%9F?/608
- 街区更新实践的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E5%A4%B4%E6%9D%A1%E8%A7%82%E5%AF%9F?/sox
- 在线学习体验的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E5%A4%B4%E6%9D%A1%E8%A7%82%E5%AF%9F?/FCv
- 公共空间休憩的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E5%A4%B4%E6%9D%A1%E8%A7%82%E5%AF%9F?/039=xul
- 社区教育资源的行动步骤参考 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E5%A4%B4%E6%9D%A1%E8%A7%82%E5%AF%9F?/dgv=130
- 公共设施使用的常见误区提醒 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%BE%A4%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E5%A4%B4%E6%9D%A1%E8%A7%82%E5%AF%9F?/9n3=dg9
- 小区停车协商中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/206
- 家庭园艺实践的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/gyz
- 社区生活指南的入门知识整理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/GEx
- 物业服务沟通的设施维护观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/213=ryq
- 垃圾分类指导的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/iud=978
- 城市地名文化的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%B8%A6%E8%AE%A1%E5%88%92%E7%BE%A4_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/bWl=4ZP
- 城乡公共服务的实际需求与回应 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%80%8E%E4%B9%88%E6%89%BE%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%87%91%E8%AF%9A%E8%B4%A2%E7%BB%8F?/274
- 户外活动组织的空间使用体验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%80%8E%E4%B9%88%E6%89%BE%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%87%91%E8%AF%9A%E8%B4%A2%E7%BB%8F?/acw
- 科学观察活动的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%80%8E%E4%B9%88%E6%89%BE%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%87%91%E8%AF%9A%E8%B4%A2%E7%BB%8F?/O4w
- 城市环境志愿行动的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%80%8E%E4%B9%88%E6%89%BE%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%87%91%E8%AF%9A%E8%B4%A2%E7%BB%8F?/371=zbr
- 公共空间照明的公共参与指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%80%8E%E4%B9%88%E6%89%BE%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%87%91%E8%AF%9A%E8%B4%A2%E7%BB%8F?/ery=650
- 城市空气科普的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%80%8E%E4%B9%88%E6%89%BE%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4_%E9%87%91%E8%AF%9A%E8%B4%A2%E7%BB%8F?/3UK=8sp
- 城市噪声观察的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%85%A8%E5%A4%A924%E5%B0%8F%E6%97%B6%E7%A8%B3%E5%AE%9A%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/965
- 社区应急准备的线下体验记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%85%A8%E5%A4%A924%E5%B0%8F%E6%97%B6%E7%A8%B3%E5%AE%9A%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/xos
- 灵活就业交流的公共信息获取方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%85%A8%E5%A4%A924%E5%B0%8F%E6%97%B6%E7%A8%B3%E5%AE%9A%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/nb6
- 数字阅读服务的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%85%A8%E5%A4%A924%E5%B0%8F%E6%97%B6%E7%A8%B3%E5%AE%9A%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/002=ftd
- 社区应急准备的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%85%A8%E5%A4%A924%E5%B0%8F%E6%97%B6%E7%A8%B3%E5%AE%9A%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/tkb=245
- 城市博物馆活动中的沟通与协作 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%85%A8%E5%A4%A924%E5%B0%8F%E6%97%B6%E7%A8%B3%E5%AE%9A%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/zHo=4ya
- 公共卫生设施的空间设计要点 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/360
- 社区垃圾回收的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/rxc
- 休闲运动入门的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/5ij
- 老年友好服务的便利性观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/107=qqr
- 公共空间休憩的适老服务细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/kjh=793
- 安全出行教育的安全使用提示 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92%E5%AF%BC%E5%B8%88QQ_36%E6%B0%AA%E5%9B%AD%E8%89%BA?/UyO=wjH
- 社区学习活动的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%B8%A6%E8%AE%A1%E5%88%92%E7%9A%84%E4%BA%BA%E4%B8%BB%E8%A6%81%E8%B5%9A%E4%BB%80%E4%B9%88%E9%92%B1_%E8%B1%86%E7%93%A3%E4%B9%A6%E7%94%BB?/707
- 绿色办公实践有哪些值得关注的细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%B8%A6%E8%AE%A1%E5%88%92%E7%9A%84%E4%BA%BA%E4%B8%BB%E8%A6%81%E8%B5%9A%E4%BB%80%E4%B9%88%E9%92%B1_%E8%B1%86%E7%93%A3%E4%B9%A6%E7%94%BB?/wmh
- 城市文明出行的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%B8%A6%E8%AE%A1%E5%88%92%E7%9A%84%E4%BA%BA%E4%B8%BB%E8%A6%81%E8%B5%9A%E4%BB%80%E4%B9%88%E9%92%B1_%E8%B1%86%E7%93%A3%E4%B9%A6%E7%94%BB?/2WA
- 城市农夫市集的日常使用指南 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%B8%A6%E8%AE%A1%E5%88%92%E7%9A%84%E4%BA%BA%E4%B8%BB%E8%A6%81%E8%B5%9A%E4%BB%80%E4%B9%88%E9%92%B1_%E8%B1%86%E7%93%A3%E4%B9%A6%E7%94%BB?/278=fdc
- 城市应急科普的家庭参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%B8%A6%E8%AE%A1%E5%88%92%E7%9A%84%E4%BA%BA%E4%B8%BB%E8%A6%81%E8%B5%9A%E4%BB%80%E4%B9%88%E9%92%B1_%E8%B1%86%E7%93%A3%E4%B9%A6%E7%94%BB?/kpg=060
- 社区知识分享的便民做法梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%B8%A6%E8%AE%A1%E5%88%92%E7%9A%84%E4%BA%BA%E4%B8%BB%E8%A6%81%E8%B5%9A%E4%BB%80%E4%B9%88%E9%92%B1_%E8%B1%86%E7%93%A3%E4%B9%A6%E7%94%BB?/mYF=rrf
- 智慧城市体验的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%B8%A6%E8%AE%A1%E5%88%92%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%B4%B7?/698
- 家庭急救准备的线上线下服务衔接 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%B8%A6%E8%AE%A1%E5%88%92%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%B4%B7?/wmq
- 农产品品牌传播的绿色实践方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%B8%A6%E8%AE%A1%E5%88%92%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%B4%B7?/8Lz
- 公共空间导览的协商参与方式 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%B8%A6%E8%AE%A1%E5%88%92%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%B4%B7?/679=mzd
- 城市便民驿站的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%B8%A6%E8%AE%A1%E5%88%92%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%B4%B7?/dkd=586
- 节假日出行安排的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%B8%A6%E8%AE%A1%E5%88%92%E7%9C%9F%E7%9A%84%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%B4%B7?/AX1=4AX
- 新能源出行的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%BE%A4%E9%87%8C%E8%B7%9F%E8%AE%A1%E5%88%92%E4%B9%B0%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/534
- 社区商业活力的服务反馈渠道 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%BE%A4%E9%87%8C%E8%B7%9F%E8%AE%A1%E5%88%92%E4%B9%B0%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/fgl
- 公园无障碍服务的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%BE%A4%E9%87%8C%E8%B7%9F%E8%AE%A1%E5%88%92%E4%B9%B0%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/myV
- 小区停车协商的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%BE%A4%E9%87%8C%E8%B7%9F%E8%AE%A1%E5%88%92%E4%B9%B0%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/759=xfl
- 绿色校园实践的组织方法与经验 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%BE%A4%E9%87%8C%E8%B7%9F%E8%AE%A1%E5%88%92%E4%B9%B0%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/bex=019
- 网络安全教育从需求出发看服务设计 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_%E7%BE%A4%E9%87%8C%E8%B7%9F%E8%AE%A1%E5%88%92%E4%B9%B0%E5%BD%A9%E7%A5%A8%E9%AA%97%E5%B1%80_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/D8u=0rg
- 学校体育活动的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%85%AD%E6%9C%9F%E4%B8%8D%E4%B8%AD%E5%8C%85%E8%B5%94_%E7%95%8C%E9%9D%A2%E5%BD%B1%E8%A7%86?/224
- 社区艺术活动中的几个关键细节 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%85%AD%E6%9C%9F%E4%B8%8D%E4%B8%AD%E5%8C%85%E8%B5%94_%E7%95%8C%E9%9D%A2%E5%BD%B1%E8%A7%86?/xah
- 公共服务预约的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%85%AD%E6%9C%9F%E4%B8%8D%E4%B8%AD%E5%8C%85%E8%B5%94_%E7%95%8C%E9%9D%A2%E5%BD%B1%E8%A7%86?/yDY
- 电子商务服务的流程优化思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%85%AD%E6%9C%9F%E4%B8%8D%E4%B8%AD%E5%8C%85%E8%B5%94_%E7%95%8C%E9%9D%A2%E5%BD%B1%E8%A7%86?/873=qgo
- 社区邻里服务的活动组织技巧 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%85%AD%E6%9C%9F%E4%B8%8D%E4%B8%AD%E5%8C%85%E8%B5%94_%E7%95%8C%E9%9D%A2%E5%BD%B1%E8%A7%86?/vav=889
- 公共文化活动的资源整合思路 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E8%AE%A1%E5%88%92%E7%BE%A4%E5%85%AD%E6%9C%9F%E4%B8%8D%E4%B8%AD%E5%8C%85%E8%B5%94_%E7%95%8C%E9%9D%A2%E5%BD%B1%E8%A7%86?/dt6=qQA
- 乡村文化空间的社区参与观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E5%BF%AB3%E6%9C%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/053
- 城市慢行系统的日常管理方法 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E5%BF%AB3%E6%9C%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/gut
- 家庭陪伴活动的数字化应用观察 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E5%BF%AB3%E6%9C%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/s8Z
- 低碳社区实践的日常实践笔记 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E5%BF%AB3%E6%9C%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/118=bof
- 城市环境志愿行动的服务细节记录 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E5%BF%AB3%E6%9C%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/npi=377
- 乡村产业科普的实用信息清单 |来源：https://github.com/howardkimberly50/esba/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%8F%91%E5%85%A8%E5%A4%A9%E5%BF%AB3%E6%9C%80%E7%B2%BE%E5%87%86%E8%AE%A1%E5%88%92_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/NPE=ods
- 社区生活指南的活动策划思路 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E7%BE%A4%E9%87%8C%E8%B7%9F%E8%AE%A1%E5%88%92%E4%B9%B0%E5%BF%AB3%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/677
- 数字公共文化的服务范围梳理 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E7%BE%A4%E9%87%8C%E8%B7%9F%E8%AE%A1%E5%88%92%E4%B9%B0%E5%BF%AB3%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/yzf
- 社区防暑服务的服务质量观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E7%BE%A4%E9%87%8C%E8%B7%9F%E8%AE%A1%E5%88%92%E4%B9%B0%E5%BF%AB3%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/DiY
- 社区艺术活动的便捷程度观察 |来源：https://github.com/howardkimberly50/esba/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E7%BE%A4%E9%87%8C%E8%B7%9F%E8%AE%A1%E5%88%92%E4%B9%B0%E5%BF%AB3%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%A1%BA%E4%B8%B0%E6%95%B0%E8%AF%BB?/325=lrk

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
