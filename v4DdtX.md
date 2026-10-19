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

- 社区邻里服务的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_758%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/IIf
- 社区知识分享的服务范围梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_758%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/113=amr
- 电动汽车充电的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_758%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/oeo=888
- 城市空气科普的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_758%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E5%9F%BA%E9%87%91?/3gn=Qzn
- 社区阅读服务的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_758%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/981
- 绿色校园实践的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_758%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/zgj
- 社区信息发布的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_758%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/0Fk
- 公交无障碍服务的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_758%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/168=xap
- 科学教育活动的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_758%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/iih=590
- 家庭阅读计划的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_758%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E5%9B%9E%E6%94%BE?/ASX=8YN
- 读书会组织的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_758%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/080
- 线上办事服务的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_758%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/gmh
- 城市展览体验的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_758%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/s7W
- 社区阅读服务的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_758%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/872=hii
- 公交无障碍服务的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_758%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/xru=980
- 校园节能行动的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_758%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E6%97%A5%E6%8A%A5?/6Od=N3C
- 城市环境志愿行动的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_758%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/297
- 文化遗产保护科普的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_758%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/ksa
- 传统节日科普的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_758%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/Gpy
- 乡村阅读空间的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_758%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/089=lhv
- 非遗课堂体验的便利性观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_758%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/rig=977
- 节能生活方式的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_758%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E6%8E%A2%E6%BA%90?/puR=eDR
- 城市步行环境的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_758%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/566
- 城市宠物友好空间的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_758%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/tje
- 青少年职业启蒙的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_758%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/Jez
- 城市人文观察的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_758%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/988=tcd
- 乡村产业科普的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_758%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/umr=195
- 儿童户外活动的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_758%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%84%8F%E5%A4%A7%E5%88%A9%E8%B4%A2%E7%BB%8F?/XLv=Eu0
- 社区防暑服务的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_758%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%BF%B0%E8%AF%84?/262
- 城市夜间照明的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_758%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%BF%B0%E8%AF%84?/jxd
- 社区知识分享的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_758%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%BF%B0%E8%AF%84?/BaG
- 通勤路线规划的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_758%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%BF%B0%E8%AF%84?/481=pxe
- 儿童运动体验的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_758%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%BF%B0%E8%AF%84?/dfm=496
- 本地历史资料的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_758%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%BF%B0%E8%AF%84?/PJ8=9tn
- 城市公共自行车的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_758%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/802
- 地方文化传播的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_758%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/bgi
- 亲子科普活动的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_758%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/TbL
- 家庭收纳实践的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_758%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/537=gxk
- 社区宣传栏更新的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_758%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/rgv=260
- 乡村生态旅游的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_758%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%A7%82%E5%AF%9F?/a7e=oFD
- 公共空间导览的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_758%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/150
- 生成式工具使用的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_758%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/qma
- 社区垃圾回收的行动步骤参考 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_758%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/3wF
- 农产品消费体验有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_758%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/043=xvq
- 家庭收纳实践的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_758%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/tub=974
- 公共健身器材的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_758%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/8GD=97E
- 社区停车服务的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_758%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E5%81%A5%E8%BA%AB?/155
- 城市社区治理的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_758%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E5%81%A5%E8%BA%AB?/uum
- 社区邻里服务有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_758%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E5%81%A5%E8%BA%AB?/1kd
- 社区科普课堂的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_758%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E5%81%A5%E8%BA%AB?/541=nsp
- 城市博物馆服务的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_758%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E5%81%A5%E8%BA%AB?/mjq=860
- 环境监测科普的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_758%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E5%81%A5%E8%BA%AB?/J1g=Ohi
- 社区环保活动的便利性观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_758%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/242
- 城市博物馆活动的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_758%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/zuy
- 城市空气科普的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_758%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/WER
- 绿色建筑理念的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_758%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/979=sub
- 社区读书角建设的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_758%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/mqp=990
- 城市微更新实践的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_758%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/8wy=rgv
- 儿童户外活动的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_758%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/607
- 智慧停车服务有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_758%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/dee
- 社区教育资源的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_758%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/Prq
- 邻里共享空间的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_758%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/826=vun
- 机器人科普活动有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_758%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/ica=121
- 绿色建筑理念的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_758%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E8%A7%82%E7%82%B9?/xPe=WMN
- 公园亲子设施的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_758%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E8%BD%AC%E8%BD%BD?/309
- 小区公共照明的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_758%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E8%BD%AC%E8%BD%BD?/daz
- 旧物循环利用中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_758%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E8%BD%AC%E8%BD%BD?/wTi
- 城市公共艺术的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_758%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E8%BD%AC%E8%BD%BD?/286=gld
- 休闲运动入门的空间设计要点 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_758%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E8%BD%AC%E8%BD%BD?/rrk=207
- 生活垃圾回收的日常管理方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_758%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E8%BD%AC%E8%BD%BD?/7j7=eic
- 绿色建筑理念从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_758%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/385
- 社区修缮行动的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_758%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/srz
- 机器人科普活动的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_758%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/kD1
- 社区花园共建的日常记录与分享 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_758%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/651=jzi
- 骑行路线规划的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_758%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/xsm=851
- 日常摄影记录的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_758%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/ZwQ=4Dh
- 城市环境志愿行动的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_758%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/054
- 乡村公共阅读的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_758%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/esk
- 家庭养老规划的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_758%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/0nt
- 城市微更新实践的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_758%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/352=zdv
- 绿色校园实践的服务质量观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_758%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/lms=426
- 学校体育活动的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_758%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%84%89%E8%84%89%E5%9C%B0%E4%BA%A7?/YtY=IJ6
- 社区设施共享的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_758%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/382
- 城市夜间照明的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_758%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/auq
- 社区健康讲座的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_758%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/6Pf
- 公共交通信息服务中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_758%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/541=ina
- 公共服务指南的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_758%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/gdy=450
- 社区慢性病防控的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_758%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E7%99%BE%E7%A7%91?/cvj=epK
- 生成式工具使用的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_758%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8D%83%E5%B8%86?/493
- 数字资源检索的流程优化思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_758%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8D%83%E5%B8%86?/fxx
- 机器人科普活动从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_758%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8D%83%E5%B8%86?/iRs
- 社区修缮行动的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_758%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8D%83%E5%B8%86?/002=qmv
- 旧物循环利用的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_758%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8D%83%E5%B8%86?/orp=876
- 社区健康讲座的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_758%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%8D%83%E5%B8%86?/wOG=1EA
- 数字便民地图的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_758%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%9F%E8%B4%A7?/115
- 公共卫生设施的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_758%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%9F%E8%B4%A7?/fce
- 劳动教育实践的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_758%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%9F%E8%B4%A7?/oyS
- 社区便利生活的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_758%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%9F%E8%B4%A7?/569=ydn
- 零废弃生活尝试的实用信息清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_758%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%9F%E8%B4%A7?/lqd=694
- 地方民俗记录的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_758%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9C%9F%E8%B4%A7?/4J4=ffu
- 人工智能科普的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_758%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/989
- 家庭志愿活动的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_758%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/woz
- 居家适老化改造的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_758%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/TLT
- 儿童友好空间的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_758%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/345=xsj
- 社区运动空间的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_758%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/fiz=725
- 数字资源检索有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_758%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E9%93%B6%E5%88%9B%E8%B4%A2%E7%BB%8F?/ryD=p6a
- 社区花园共建的执行流程参考 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_758%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/627
- 家庭急救准备的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_758%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/gaf
- 城市可持续生活的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_758%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/u7i
- 图书馆活动策划的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_758%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/912=bfv
- 社区环保活动的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_758%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/rdr=560
- 终身学习资源从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_758%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E5%B1%85?/5EB=pYr
- 公共场馆服务的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_8258.vip-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%BF%AB%E6%8A%A5?/908
- 职业技能学习的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_8258.vip-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%BF%AB%E6%8A%A5?/bqr
- 通勤路线规划的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_8258.vip-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%BF%AB%E6%8A%A5?/2jr
- 家庭收纳实践的便利性观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_8258.vip-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%BF%AB%E6%8A%A5?/173=bqw
- 乡村文化空间有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_8258.vip-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%BF%AB%E6%8A%A5?/mmb=729
- 图书馆亲子空间的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_8258.vip-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%BF%AB%E6%8A%A5?/lon=3rw
- 信息无障碍体验的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_8258.vip-welcome%E5%A4%A7%E5%8E%85_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/717
- 数字设备回收的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_8258.vip-welcome%E5%A4%A7%E5%8E%85_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/haj
- 街区小店体验从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_8258.vip-welcome%E5%A4%A7%E5%8E%85_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/o38
- 城市公共空间的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_8258.vip-welcome%E5%A4%A7%E5%8E%85_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/019=mli
- 城市展览体验中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_8258.vip-welcome%E5%A4%A7%E5%8E%85_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/skc=410
- 青少年编程学习的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_8258.vip-welcome%E5%A4%A7%E5%8E%85_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/Vna=McM
- 公共空间导览的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_8258.vip-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/557
- 城市空气科普有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_8258.vip-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/aqb
- 公共空间导览的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_8258.vip-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/z6B
- 数字地图应用的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_8258.vip-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/199=mzn
- 青少年编程学习的便利性观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_8258.vip-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/nxg=910
- 家庭网络使用的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_8258.vip-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E5%BD%B1%E8%A7%86?/MZL=lCz
- 地方旅游导览的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_8258.vip-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%BD%AC%E8%BD%BD?/074
- 数字政务体验的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_8258.vip-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%BD%AC%E8%BD%BD?/pog
- 生成式工具使用的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_8258.vip-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%BD%AC%E8%BD%BD?/iqk
- 消防知识宣传的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_8258.vip-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%BD%AC%E8%BD%BD?/447=qkq
- 邻里互助活动的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_8258.vip-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%BD%AC%E8%BD%BD?/wff=882
- 公共卫生宣传的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_8258.vip-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%BD%AC%E8%BD%BD?/Ezb=PU0
- 公共服务评价的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_8258.vip-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/837
- 公共卫生设施从使用体验看服务改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_8258.vip-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/kth
- 城市文化路线的持续改进方向 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_8258.vip-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/IYF
- 音乐欣赏活动的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_8258.vip-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/499=gzn
- 城市微更新实践的儿童友好细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_8258.vip-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/zxb=000
- 图书借阅体验的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_8258.vip-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%B0%91%E7%94%9F%E8%B4%A2%E7%BB%8F?/sbk=2rX
- 社区环保活动的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_8258.vip-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E6%8A%A5?/031
- 公共设施使用的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_8258.vip-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E6%8A%A5?/pdb
- 学校体育活动的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_8258.vip-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E6%8A%A5?/EBh
- 家庭节能设备的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_8258.vip-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E6%8A%A5?/287=phh
- 公交无障碍服务的日常实践笔记 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_8258.vip-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E6%8A%A5?/fcz=895
- 生活垃圾减量的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_8258.vip-%E7%99%BB%E5%BD%95welcome_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E6%8A%A5?/r8u=ySH
- 智慧城市体验的线下体验记录 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_8258.vip-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/976
- 城市文明出行的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_8258.vip-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/swv
- 本地消费场景的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_8258.vip-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/hW8
- 远程协作工具的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_8258.vip-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/863=qth
- 社区法律科普的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_8258.vip-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/llw=567
- 数字公共文化的使用门槛与改进 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_8258.vip-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/kUD=WE1
- 生活技能分享的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_8258.vip-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E9%80%9F%E8%A7%88?/306
- 社区信息发布的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_8258.vip-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E9%80%9F%E8%A7%88?/jlw
- 青少年科普实践的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_8258.vip-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E9%80%9F%E8%A7%88?/xqn
- 城市公共标识的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_8258.vip-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E9%80%9F%E8%A7%88?/506=emn
- 社区生活指南的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_8258.vip-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E9%80%9F%E8%A7%88?/oqi=023
- 物业服务沟通中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_8258.vip-%E5%AE%98%E6%96%B9app_%E7%BD%91%E6%98%93%E9%80%9F%E8%A7%88?/2gi=pLr
- 城市应急广播有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_8258.vip-%E5%AE%98%E7%BD%91_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/766
- 科学信息获取的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_8258.vip-%E5%AE%98%E7%BD%91_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/tnl
- 小区停车协商有哪些值得关注的细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_8258.vip-%E5%AE%98%E7%BD%91_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/jGl
- 街头绿植养护的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_8258.vip-%E5%AE%98%E7%BD%91_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/313=upw
- 城市宠物友好空间的参与方式与路径 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_8258.vip-%E5%AE%98%E7%BD%91_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/mfp=245
- 人工智能科普的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_8258.vip-%E5%AE%98%E7%BD%91_%E5%8D%B0%E5%BA%A6%E8%B4%A2%E7%BB%8F?/r6W=IrO
- 老年学习活动的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_8258.vip-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/084
- 文化讲座服务的公共参与指南 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_8258.vip-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/yxv
- 公共服务评价的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_8258.vip-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/cOn
- 公交站点体验的便民做法梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_8258.vip-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/153=bit
- 灵活就业交流的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_8258.vip-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/vwb=085
- 开源技术交流的设施维护观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_8258.vip-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E6%97%B6%E8%AE%AF?/dOU=Ra1
- 公共图书馆服务的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258.vip-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/960
- 老年人出行服务的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258.vip-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/zqy
- 学校体育活动的适老服务细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258.vip-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/Ml5
- 家庭安全提示的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258.vip-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/656=cca
- 农村环境治理的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258.vip-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/qof=297
- 绿色消费选择的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258.vip-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%BF%B0%E8%AF%84?/8Zl=uSw
- 老年学习活动的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258.vip-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%91%E6%8A%80?/801
- 社区科普课堂的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258.vip-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%91%E6%8A%80?/ryh
- 社区共享书架的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258.vip-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%91%E6%8A%80?/XP4
- 劳动教育实践从需求出发看服务设计 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258.vip-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%91%E6%8A%80?/244=axg
- 城市博物馆活动的基础知识问答 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258.vip-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%91%E6%8A%80?/flo=701
- 数字公共文化中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258.vip-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%91%E6%8A%80?/tL2=oFe
- 城市地名文化的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_8258.vip-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%B1%BD%E8%BD%A6?/130
- 城市文化路线的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_8258.vip-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%B1%BD%E8%BD%A6?/osr
- 图书馆数字服务中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_8258.vip-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%B1%BD%E8%BD%A6?/gfc
- 公共交通接驳中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_8258.vip-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%B1%BD%E8%BD%A6?/939=ckn
- 生活垃圾回收的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_8258.vip-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%B1%BD%E8%BD%A6?/agh=100
- 绿色出行服务的社区参与观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_8258.vip-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%B1%BD%E8%BD%A6?/GRO=XvW
- 网络安全教育的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258.vip-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%A7%A3%E5%AF%86?/685
- 文化讲座服务的常见误区提醒 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258.vip-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%A7%A3%E5%AF%86?/gqd
- 药品使用科普的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258.vip-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%A7%A3%E5%AF%86?/rS8
- 城市公共空间的服务细节记录 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258.vip-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%A7%A3%E5%AF%86?/271=ucp
- 邻里互助活动的服务反馈渠道 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258.vip-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%A7%A3%E5%AF%86?/dub=316
- 家庭环保行动的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258.vip-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%A7%A3%E5%AF%86?/p7W=Msm
- 公共服务评价的实际需求与回应 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_8258.vip-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E8%AF%84%E8%AE%BA?/013
- 医院导诊服务的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_8258.vip-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E8%AF%84%E8%AE%BA?/pyu
- 城乡交流活动中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_8258.vip-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E8%AF%84%E8%AE%BA?/54G
- 全民健身活动的入门知识整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_8258.vip-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E8%AF%84%E8%AE%BA?/519=exg
- 租房信息服务中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_8258.vip-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E8%AF%84%E8%AE%BA?/aah=185
- 骑行路线规划的数字工具使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_8258.vip-%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E8%AF%84%E8%AE%BA?/I2Y=3LG
- 家庭陪伴活动的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_8258.vip-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/534
- 个人时间管理的流程优化思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_8258.vip-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/rzb
- 节约用水实践的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_8258.vip-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/GTr
- 绿色办公实践的居民参与机会 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_8258.vip-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/349=wxo
- 青年志愿活动的空间使用体验 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_8258.vip-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/qmg=790
- 社区环保活动的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_8258.vip-%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%A1%A3%E6%A1%88?/RL4=oLx
- 个人信息保护的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_8258.vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/285
- 社区托育服务的流程优化思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_8258.vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/jfc
- 公共空间休憩的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_8258.vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/ToA
- 地方民俗记录的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_8258.vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/332=hso
- 在线学习体验的长期维护要点 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_8258.vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/sji=329
- 数字公共文化的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_8258.vip-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F?/Agm=T40
- 青少年户外教育的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_8258.vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E7%A7%81%E5%8B%9F?/485
- 非遗体验活动的公共信息获取方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_8258.vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E7%A7%81%E5%8B%9F?/xfn
- 绿色出行服务的服务体验观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_8258.vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E7%A7%81%E5%8B%9F?/Y4C
- 城市公共饮水的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_8258.vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E7%A7%81%E5%8B%9F?/845=zbv
- 气象科普传播的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_8258.vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E7%A7%81%E5%8B%9F?/jph=038
- 健康饮食教育的便捷程度观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_8258.vip-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E7%A7%81%E5%8B%9F?/D00=KOx
- 社区庭院绿化的绿色实践方法 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_8258.vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%9B%B2%E8%89%BA?/156
- 食品安全科普的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_8258.vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%9B%B2%E8%89%BA?/hsw
- 农村环境治理的活动组织技巧 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_8258.vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%9B%B2%E8%89%BA?/ksY
- 校园安全教育的流程优化思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_8258.vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%9B%B2%E8%89%BA?/177=rns
- 文明养宠科普的活动策划思路 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_8258.vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%9B%B2%E8%89%BA?/dal=371
- 社区共享书架的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_8258.vip-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%9B%B2%E8%89%BA?/tNN=zWu
- 急救知识普及的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_8258.vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/736
- 城市生活记录的社区行动案例 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_8258.vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/pma
- 本地旅行体验的组织方法与经验 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_8258.vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/roh
- 城市慢行系统的资源整合思路 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_8258.vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/156=jht
- 校园社团活动中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_8258.vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/vsq=713
- 食品安全科普的学习资源整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_8258.vip-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/iii=fdB
- 城市公共自行车的常见问题梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_8258.vip-%E9%A6%96%E9%A1%B5_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/919
- 城市应急广播中的几个关键细节 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_8258.vip-%E9%A6%96%E9%A1%B5_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/ome
- 家庭用电安全的阅读与学习资源 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_8258.vip-%E9%A6%96%E9%A1%B5_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/hly
- 乡村生态观察中的沟通与协作 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_8258.vip-%E9%A6%96%E9%A1%B5_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/539=hjg
- 数字生活课堂的基础设施观察 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_8258.vip-%E9%A6%96%E9%A1%B5_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/dzp=994
- 急救知识普及的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_8258.vip-%E9%A6%96%E9%A1%B5_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/v08=vi4
- 街区小店体验的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_8258.vip-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/203
- 乡村电商实践的协商参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_8258.vip-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/tnm
- 乡村文化活动的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_8258.vip-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/v57
- 居家防滑改造的数字化应用观察 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_8258.vip-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/921=rxz
- 城乡交流活动的家庭参与方式 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_8258.vip-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/dep=565
- 老年运动活动的安全使用提示 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_8258.vip-%E5%AE%98%E6%96%B9_%E8%B4%A2%E7%BB%8F%E6%94%BF%E5%8A%A1?/a2K=O1e
- 家庭健康科普的活动体验回顾 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_8258cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/285
- 街道综合服务的家庭实践清单 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_8258cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/kmx
- 社区共享书架的服务信息整理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_8258cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/Sjr
- 绿色办公实践的协作机制梳理 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_8258cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/693=ewu
- 城市地名文化的资源利用方法 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_8258cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/rqx=592
- 家庭节能设备的线上线下服务衔接 |来源：https://github.com/boydcathy2513/witd/wiki/2027%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_8258cc-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/STU=qB8

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
