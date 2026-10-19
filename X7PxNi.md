# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:23**

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

- 城市应急广播的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_168%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/smg=261
- 乡村文化空间的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_168%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E7%BB%9C%E8%B4%A2%E7%BB%8F?/N03=3A6
- 本地旅行体验的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_168%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/587
- 科学运动指导的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_168%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/lrb
- 社区防暑服务的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_168%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/HFK
- 乡村文化活动的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_168%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/474=hxa
- 儿童阅读角中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_168%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/mgb=580
- 环境监测科普的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_168%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/qCP=S2g
- 亲子科普活动的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_18%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%8E%86%E5%8F%B2?/777
- 城市基础设施的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_18%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%8E%86%E5%8F%B2?/hrr
- 在线教育体验的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_18%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%8E%86%E5%8F%B2?/cFS
- 家庭急救准备的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_18%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%8E%86%E5%8F%B2?/388=rlw
- 社区便民服务的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_18%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%8E%86%E5%8F%B2?/rsj=424
- 数字艺术创作的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_18%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%8E%86%E5%8F%B2?/Z9P=UJo
- 社区垃圾分类的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_18%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/291
- 乡村公共服务的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_18%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/oqy
- 网络安全教育的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_18%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/hpO
- 图书馆活动策划的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_18%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/832=tjj
- 公交站点体验的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_18%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/jfe=226
- 公共交通接驳的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_18%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/uQp=oOe
- 社区宠物管理的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_18%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E4%BF%9D%E9%99%A9?/242
- 城市文明出行的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_18%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E4%BF%9D%E9%99%A9?/lhk
- 家庭志愿活动有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_18%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E4%BF%9D%E9%99%A9?/OUF
- 基层服务创新的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_18%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E4%BF%9D%E9%99%A9?/667=ooj
- 节约用水实践的家庭实践清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_18%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E4%BF%9D%E9%99%A9?/qnj=189
- 地方民俗记录的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_18%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E4%BF%9D%E9%99%A9?/E0O=OBr
- 乡村电商实践从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_18%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/817
- 节气饮食文化的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_18%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/gag
- 公共空间导览的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_18%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/E98
- 地方文化传播的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_18%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/169=jzd
- 数字支付体验的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_18%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/ilp=803
- 节假日出行安排的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_18%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/e79=WKW
- 老年智能设备的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_18%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E5%88%B8%E5%95%86?/901
- 居家适老化改造的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_18%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E5%88%B8%E5%95%86?/efu
- 数字支付体验的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_18%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E5%88%B8%E5%95%86?/GSp
- 校园节能行动的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_18%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E5%88%B8%E5%95%86?/550=omr
- 公共场所导视的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_18%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E5%88%B8%E5%95%86?/ynr=034
- 小微企业服务的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_18%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%84%89%E8%84%89%E5%88%B8%E5%95%86?/zi8=f4S
- 公共场所导视的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_18%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E5%80%BA%E5%B8%82?/745
- 乡村公共文化的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_18%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E5%80%BA%E5%B8%82?/bxo
- 社区修缮行动的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_18%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E5%80%BA%E5%B8%82?/Jet
- 读书会组织的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_18%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E5%80%BA%E5%B8%82?/586=mda
- 基层健康档案的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_18%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E5%80%BA%E5%B8%82?/djo=772
- 数字阅读服务的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_18%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_360%E5%80%BA%E5%B8%82?/Uhc=WMo
- 青年志愿活动的空间使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_18%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/023
- 电动汽车充电的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_18%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/dny
- 小微企业服务的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_18%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/APt
- 网络信息辨识的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_18%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/811=stw
- 城市适老服务的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_18%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/rse=011
- 音乐欣赏活动的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_18%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%84%89%E8%84%89%E7%9B%B4%E6%92%AD?/7hH=inx
- 地方戏曲体验的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_18%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/731
- 数字创意课程的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_18%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/xzv
- 家庭环保行动的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_18%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/m5S
- 数字支付体验的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_18%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/787=rio
- 城市展览体验中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_18%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/zac=748
- 城市应急科普的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_18%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/ljC=FWB
- 乡村教育资源的实际需求与回应 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_18%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/174
- 社区绿色空间的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_18%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/hfg
- 城市博物馆活动的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_18%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/QWR
- 绿色出行服务的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_18%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/683=ckh
- 社区便民服务的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_18%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/qvf=655
- 社区运动空间的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_18%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E6%96%B0%E9%97%BB?/oHz=wut
- 科普展览体验的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_18%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/495
- 基层服务创新的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_18%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/rrw
- 科学健身方法的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_18%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/sdo
- 街区更新实践的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_18%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/881=osm
- 生活垃圾回收的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_18%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/tfk=373
- 消防知识宣传有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_18%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%A4%BE%E8%AE%BA?/rSp=NQH
- 数据分析入门的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_18%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E7%83%AD%E6%A6%9C?/570
- 老年运动活动的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_18%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E7%83%AD%E6%A6%9C?/nfq
- 公共空间照明的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_18%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E7%83%AD%E6%A6%9C?/XiL
- 邻里共享空间从需求出发看服务设计 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_18%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E7%83%AD%E6%A6%9C?/757=dxl
- 公共文化活动的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_18%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E7%83%AD%E6%A6%9C?/nej=584
- 物业服务沟通的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_18%E5%BD%A9%E7%A5%A8-APP_%E8%B4%A2%E7%BB%8F%E7%83%AD%E6%A6%9C?/w18=XoX
- 家庭照护支持的协作机制梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_18%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/374
- 街区小店体验的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_18%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/nis
- 节约用水实践的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_18%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/S0M
- 老年人出行服务的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_18%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/361=rlg
- 社区安全巡查的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_18%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/jhk=189
- 乡村阅读活动的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_18%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/ilQ=Lac
- 数字生活课堂有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_18%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AF%84?/043
- 家庭用电安全的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_18%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AF%84?/mna
- 公共服务咨询的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_18%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AF%84?/k4g
- 乡村阅读活动的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_18%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AF%84?/273=hxs
- 青年志愿活动的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_18%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AF%84?/lex=562
- 无障碍出行的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_18%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AF%84?/ZPL=QJi
- 环境监测科普的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_18%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/144
- 基层健康服务的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_18%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/vip
- 线上办事服务的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_18%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/ddH
- 家庭消费规划的持续改进方向 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_18%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/311=vbq
- 家庭安全提示的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_18%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/zsi=529
- 创业经验分享的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_18%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E9%A3%9F%E5%93%81?/Tqk=9CK
- 社区快递服务的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_18%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E7%A7%91%E6%8A%80?/919
- 在线教育体验的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_18%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E7%A7%91%E6%8A%80?/djf
- 消防知识宣传的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_18%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E7%A7%91%E6%8A%80?/BkJ
- 公共服务评价的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_18%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E7%A7%91%E6%8A%80?/889=kxu
- 城市文明出行的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_18%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E7%A7%91%E6%8A%80?/acs=865
- 社区老年食堂的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_18%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E7%A7%91%E6%8A%80?/0EI=h78
- 公共卫生宣传的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_18%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%A0%94%E5%88%A4%E8%B4%A2%E7%BB%8F?/964
- 开放式学习空间中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_18%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%A0%94%E5%88%A4%E8%B4%A2%E7%BB%8F?/tho
- 农村环境治理的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_18%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%A0%94%E5%88%A4%E8%B4%A2%E7%BB%8F?/QuH
- 数字便民地图的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_18%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%A0%94%E5%88%A4%E8%B4%A2%E7%BB%8F?/658=zjj
- 农村环境治理中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_18%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%A0%94%E5%88%A4%E8%B4%A2%E7%BB%8F?/fju=337
- 公共场馆服务的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_18%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%A0%94%E5%88%A4%E8%B4%A2%E7%BB%8F?/UX7=cAx
- 社区消防演练的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_18%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C?/813
- 电动汽车充电的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_18%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C?/bvy
- 城市生活服务的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_18%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C?/txj
- 社区教育资源的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_18%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C?/049=qmg
- 家庭饮食安排的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_18%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C?/vqp=553
- 家庭陪伴活动的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_18%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C?/n2Q=8b4
- 城市微更新实践的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_18%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E4%BD%93%E8%82%B2?/109
- 城市应急广播的服务体验观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_18%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E4%BD%93%E8%82%B2?/mqe
- 公共空间休憩的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_18%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E4%BD%93%E8%82%B2?/8O2
- 老年数字阅读的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_18%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E4%BD%93%E8%82%B2?/813=cuw
- 城市公共自行车的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_18%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E4%BD%93%E8%82%B2?/smy=195
- 文化讲座服务的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_18%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%84%89%E8%84%89%E4%BD%93%E8%82%B2?/xHH=uAX
- 生活技能分享的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_18%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/222
- 城市公共饮水的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_18%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/egy
- 社区慢性病防控的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_18%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/L90
- 校园社团活动的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_18%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/528=tba
- 社区公共餐饮的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_18%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/xlt=272
- 老年人日常照护的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_18%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/b6V=9bR
- 社区教育资源的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_18%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%AF%BB%E6%8A%A5?/140
- 乡村公共文化的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_18%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%AF%BB%E6%8A%A5?/bar
- 乡村电商实践的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_18%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%AF%BB%E6%8A%A5?/wJM
- 食品安全科普的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_18%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%AF%BB%E6%8A%A5?/869=ipy
- 公共文化活动的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_18%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%AF%BB%E6%8A%A5?/cxv=035
- 零废弃生活尝试有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_18%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%AF%BB%E6%8A%A5?/vly=9Yc
- 线上阅读资源的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_18%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/032
- 绿色建筑理念从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_18%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/qhn
- 数字便民地图的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_18%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/8SY
- 图书馆数字服务的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_18%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/608=cji
- 数字支付体验的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_18%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/wgl=803
- 城市游园体验的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_18%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/uv7=T5H
- 街区绿化养护的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_18%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%89%B4?/783
- 地方美食文化的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_18%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%89%B4?/gsv
- 家庭运动计划的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_18%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%89%B4?/zFh
- 老年人日常照护的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_18%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%89%B4?/569=tud
- 图书馆亲子空间有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_18%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%89%B4?/bjh=873
- 城市游园体验的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_18%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%9B%BE%E9%89%B4?/QKk=PY6
- 儿童户外活动的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_18%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/056
- 科学教育活动的实用信息清单 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_18%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/ual
- 药品使用科普的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_18%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/IvR
- 环境教育课程的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_18%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/910=yew
- 健康步道使用的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_18%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/lnc=964
- 社区休闲设施的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_18%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E4%BF%A1%E8%AE%BF?/iUK=7D4
- 街区道路维护的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_18%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%88%B8%E5%95%86?/455
- 乡村文化活动的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_18%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%88%B8%E5%95%86?/ljf
- 开放数据应用的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_18%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%88%B8%E5%95%86?/WDC
- 市民热线服务的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_18%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%88%B8%E5%95%86?/772=puu
- 社区教育资源的便民做法梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_18%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%88%B8%E5%95%86?/dld=489
- 城市农夫市集的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_18%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%88%B8%E5%95%86?/XWo=mbT
- 城市生活记录的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_18%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/463
- 乡村休闲旅游的学习资源整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_18%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/liy
- 社区读书角建设的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_18%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/0mn
- 城市生活记录有哪些值得关注的细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_18%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/811=tdu
- 家庭网络使用的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_18%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/lks=871
- 社区绿色空间的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_18%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/D34=XLi
- 软件开发学习的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_18%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/250
- 乡村公共文化的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_18%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/wus
- 公益活动组织的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_18%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/mjF
- 公共空间导览的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_18%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/861=img
- 科学睡眠习惯的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_18%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/nyi=316
- 小区电梯维护的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_18%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%AE%BF?/RDt=VjY
- 社区消防演练的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_18%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/455
- 城市人文观察的公共参与指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_18%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/yop
- 休闲运动入门的空间设计要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_18%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/DNm
- 公共设施使用的流程优化思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_18%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/630=glq
- 文化场馆预约的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_18%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/rcx=409
- 数字档案服务的居民参与机会 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_18%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/1Fw=2SB
- 社区设施共享的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_18%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%9B%BE%E9%89%B4?/176
- 社区知识分享的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_18%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%9B%BE%E9%89%B4?/btv
- 青少年户外教育从需求出发看服务设计 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_18%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%9B%BE%E9%89%B4?/hhX
- 机器人科普活动的日常管理方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_18%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%9B%BE%E9%89%B4?/171=vum
- 数字生活课堂的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_18%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%9B%BE%E9%89%B4?/rah=244
- 地方旅游导览的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%8E%A9%E5%AE%B6%E7%88%86%E6%96%99_18%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%9B%BE%E9%89%B4?/PeO=LBF
- 终身学习资源的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_18%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/945
- 生成式工具使用的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_18%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/evh
- 社区安全巡查的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_18%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/yKt
- 社区家校合作的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_18%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/189=aiq
- 周末休闲规划的基础设施观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_18%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/uyx=217
- 社区休闲设施的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_18%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%99%A8%E6%8A%A5?/shb=SVg
- 气象科普传播的社区参与观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_18%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/171
- 科学教育活动的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_18%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/rln
- 传统节日科普的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_18%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/bvo
- 绿色建筑理念的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_18%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/369=ggk
- 社区商业活力中的几个关键细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_18%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/jem=990
- 乡村公共阅读的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_18%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%91%A8%E6%8A%A5?/Zd7=0rO
- 社区艺术活动的便捷程度观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_18%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E9%94%90%E8%AF%84?/112
- 图书馆数字服务的服务范围梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_18%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E9%94%90%E8%AF%84?/ggo
- 基层医疗预约从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_18%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E9%94%90%E8%AF%84?/PnK
- 劳动教育实践的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_18%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E9%94%90%E8%AF%84?/465=ezf
- 急救知识普及的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_18%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E9%94%90%E8%AF%84?/mhk=318
- 社区手工活动的线上线下服务衔接 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_18%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E9%94%90%E8%AF%84?/air=KJ6
- 数字阅读服务的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_18%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA?/124
- 社区共享书架的公共信息获取方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_18%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA?/iye
- 城市环境志愿行动的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_18%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA?/3ff
- 社区运动空间的常见问题梳理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_18%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA?/900=rgs
- 社区心理支持的服务细节记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_18%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA?/yes=439
- 青少年户外教育的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_18%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_36%E6%B0%AA?/vqw=BZs
- 城市骑行环境的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_18%E5%A8%B1%E4%B9%90-APP_%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/121
- 个人数据管理的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_18%E5%A8%B1%E4%B9%90-APP_%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/azl
- 家庭环保行动的社区行动案例 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_18%E5%A8%B1%E4%B9%90-APP_%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/385
- 城市应急科普的使用门槛与改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_18%E5%A8%B1%E4%B9%90-APP_%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/179=yfr
- 社区慢性病防控的协商参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_18%E5%A8%B1%E4%B9%90-APP_%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/wjc=634
- 开放数据应用的活动体验回顾 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_18%E5%A8%B1%E4%B9%90-APP_%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/hND=aCS
- 城市基础设施的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_18%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/836
- 城市建设科普的服务信息整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_18%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/wqs
- 社区信息发布中的沟通与协作 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_18%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/z6t
- 智慧城市体验的入门知识整理 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_18%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/877=mnc
- 安全出行教育的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_18%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/rzk=009
- 开放数据应用的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_18%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%BF%AB%E8%AE%AF?/S87=lup
- 社区宠物管理的活动策划思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_18%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/918
- 城市水环境观察的基础知识问答 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_18%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/shn
- 图书借阅体验的资源利用方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_18%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/b2d
- 乡村公共服务的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_18%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/226=qmp
- 绿色出行服务的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_18%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/whh=044
- 数字政务体验的数字化应用观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_18%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/WOR=Ez0
- 老年运动活动的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_18%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E9%80%9F%E8%A7%88?/300
- 公共服务咨询的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_18%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E9%80%9F%E8%A7%88?/ywo
- 市民热线服务的阅读与学习资源 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_18%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E9%80%9F%E8%A7%88?/EwT
- 乡村阅读空间的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_18%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E9%80%9F%E8%A7%88?/606=hya
- 传统节日科普的设施维护观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_18%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E9%80%9F%E8%A7%88?/xtm=366
- 传统节日科普的参与方式与路径 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_18%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E9%80%9F%E8%A7%88?/Ayi=hGS
- 节日文化体验的儿童友好细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_18%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/440
- 城市公共空间的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_18%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/xrd
- 节假日出行安排的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_18%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/LOP
- 公共交通信息服务的活动组织技巧 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_18%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/927=ncp
- 社区环保活动的便利性观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_18%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/gml=690
- 城市地名文化的日常使用指南 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_18%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E6%A5%BC%E5%B8%82?/oaQ=qVX
- 节假日出行安排的绿色实践方法 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_18%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%9C%B0%E4%BA%A7?/298
- 城市慢行系统的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_18%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%9C%B0%E4%BA%A7?/wfj
- 劳动教育实践从需求出发看服务设计 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_18%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%9C%B0%E4%BA%A7?/tr5
- 个人信息保护的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_18%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%9C%B0%E4%BA%A7?/178=xod
- 青年就业服务的适老服务细节 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_18%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%9C%B0%E4%BA%A7?/qfq=822
- 读书会组织从使用体验看服务改进 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_18%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E5%9C%B0%E4%BA%A7?/SKe=h85
- 城市运动公园的数字工具使用体验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_18%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/848
- 街道综合服务的执行流程参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_18%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/pct
- 绿色校园实践的安全使用提示 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_18%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/22J
- 基层服务创新的日常记录与分享 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_18%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/034=lcp
- 社区体育组织的日常实践笔记 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_18%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/leo=178
- 生活服务数字化的服务反馈渠道 |来源：https://github.com/bennettcourtney1/pvek/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_18%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/VU1=Aw5
- 社区手工活动的服务质量观察 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_18%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/998
- 科学信息获取的行动步骤参考 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_18%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/zoc
- 绿色生活实践的家庭参与方式 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_18%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/OyO
- 城市运动公园的常见误区提醒 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_18%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/837=svs
- 科学教育活动的资源整合思路 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_18%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/lej=650
- 家庭陪伴活动的长期维护要点 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_18%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%9C%AC%E5%9C%B0%E8%B4%A2%E7%BB%8F?/zkf=KxK
- 地方美食文化的线下体验记录 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_18%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/510
- 家庭食品保存的组织方法与经验 |来源：https://github.com/bennettcourtney1/pvek/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_18%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E6%92%AD%E6%8A%A5?/ajn

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
