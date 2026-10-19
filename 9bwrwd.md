# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:47:28**

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

- 社区共享书架的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%85%B4%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%A7%81%E5%8B%9F?/rkx=294
- 社区共享书架的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E7%AE%80%E6%8A%A5_%E4%B8%AD%E5%85%B4%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E7%A7%81%E5%8B%9F?/lzO=Fis
- 青少年科普实践的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%85%B4%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/138
- 城市公共艺术从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%85%B4%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/qnx
- 线上办事服务的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%85%B4%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/P0S
- 家庭用电安全的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%85%B4%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/511=tsk
- 儿童安全出行的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%85%B4%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/ikn=328
- 街区小店体验的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E4%B8%AD%E5%85%B4%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E6%95%99%E8%82%B2%E8%B4%A2%E7%BB%8F?/RLc=iZn
- 城市生活服务的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_U8%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/882
- 乡村公共阅读的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_U8%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/ptl
- 家庭养老规划的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_U8%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/ih9
- 城市文化路线的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_U8%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/018=xcn
- 无障碍出行的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_U8%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/idr=092
- 乡村文化空间的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_U8%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E4%B9%A6%E7%94%BB?/Yxp=GXA
- 社区活动空间的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_U8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/738
- 传统节日科普的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_U8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/rcs
- 休闲运动入门的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_U8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/rrF
- 食品配送体验从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_U8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/436=zzx
- 基层服务创新的服务范围梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_U8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/jbt=147
- 社区便利生活的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_U8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/wXJ=9uv
- 基层医疗预约的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_U8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%9E%AD%E6%9C%9B?/988
- 智慧城市体验的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_U8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%9E%AD%E6%9C%9B?/vyw
- 人工智能科普的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_U8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%9E%AD%E6%9C%9B?/uqB
- 社区健康讲座的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_U8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%9E%AD%E6%9C%9B?/750=owl
- 节能家电使用的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_U8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%9E%AD%E6%9C%9B?/qas=982
- 生活垃圾回收的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_U8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E7%9E%AD%E6%9C%9B?/h4D=zWF
- 家庭消费规划的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/819
- 公共设施使用的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/gbm
- 城市文明实践中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/MDx
- 生活垃圾回收的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/586=jtv
- 学校食育活动从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/avj=594
- 居家防滑改造的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E5%A8%B1%E4%B9%90?/NaQ=xe6
- 绿色快递包装的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_U8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/596
- 便民维修服务的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_U8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/sjh
- 数字素养提升的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_U8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/Ftl
- 科学运动指导的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_U8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/898=xph
- 气象科普传播的长期维护要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_U8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/urh=770
- 公园亲子设施的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_U8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/5th=sE2
- 城市公共自行车的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_U8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/151
- 青年志愿活动的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_U8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/mhe
- 文明养宠科普的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_U8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/vDn
- 骑行路线规划的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_U8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/451=nat
- 街区更新实践的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_U8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/efy=189
- 数字创意课程的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_U8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%88%8A%E7%99%BB?/wDB=XK5
- 社区菜市场服务从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_U8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%BD%B1%E8%A7%86?/639
- 城市应急广播的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_U8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%BD%B1%E8%A7%86?/ixw
- 日常摄影记录的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_U8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%BD%B1%E8%A7%86?/7hh
- 社区绿色空间的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_U8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%BD%B1%E8%A7%86?/386=bnz
- 家庭养老规划的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_U8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%BD%B1%E8%A7%86?/ytf=037
- 社区公共卫生的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_U8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E5%BD%B1%E8%A7%86?/3R0=LQZ
- 乡村阅读空间的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%89%B9%E7%A8%BF?/471
- 乡村公共文化的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%89%B9%E7%A8%BF?/bcl
- 家庭理财科普的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%89%B9%E7%A8%BF?/TOT
- 城市适老服务中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%89%B9%E7%A8%BF?/461=rzk
- 城市公共艺术的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%89%B9%E7%A8%BF?/exv=563
- 城市体育设施的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%89%B9%E7%A8%BF?/hzn=q0Z
- 社区故事采集的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/702
- 邻里共享空间的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/rvd
- 应急物资管理的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/LLm
- 社区心理支持的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/598=fwr
- 城市公共标识的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/jpa=998
- 城市基础设施的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%8C%88%E7%89%99%E8%B4%A2%E7%BB%8F?/TrJ=58H
- 公共空间照明从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_U8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A8%8E%E5%8A%A1?/210
- 社区学习活动的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_U8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A8%8E%E5%8A%A1?/xaq
- 节气饮食文化的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_U8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A8%8E%E5%8A%A1?/QwX
- 儿童户外活动的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_U8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A8%8E%E5%8A%A1?/097=kpq
- 基层健康服务的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_U8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A8%8E%E5%8A%A1?/leb=659
- 学校食育活动的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_U8%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%A8%8E%E5%8A%A1?/t2V=xdV
- 公共服务预约的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_U8%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/443
- 老年人日常照护的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_U8%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/nkq
- 智能手机助老的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_U8%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/zBe
- 社区手工活动中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_U8%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/275=uvd
- 城市共享单车的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_U8%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/dyx=463
- 乡村生态观察的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_U8%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%BE%8E%E9%A3%9F?/GHr=jxh
- 城市文明出行的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_U8%E5%BD%A9%E7%A5%A8-APP_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/108
- 数字生活课堂的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_U8%E5%BD%A9%E7%A5%A8-APP_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ymx
- 生活技能分享的资源整合思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_U8%E5%BD%A9%E7%A5%A8-APP_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/JgI
- 老年人日常照护的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_U8%E5%BD%A9%E7%A5%A8-APP_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/126=hhk
- 人工智能科普的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_U8%E5%BD%A9%E7%A5%A8-APP_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/yzo=245
- 家庭园艺实践的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_U8%E5%BD%A9%E7%A5%A8-APP_%E4%BD%B3%E7%9B%9B%E8%B4%A2%E7%BB%8F?/kLw=Cb1
- 农村环境治理的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_U8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/989
- 公共设施维护的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_U8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/afd
- 青年志愿活动的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_U8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/il0
- 人工智能科普的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_U8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/103=zyf
- 志愿者培训交流的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_U8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/tus=612
- 老年友好服务的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_U8%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E7%89%B9%E7%A8%BF?/vZN=zps
- 无障碍信息设计的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_U8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%92%AD%E6%8A%A5?/186
- 城市生活记录的公共参与指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_U8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%92%AD%E6%8A%A5?/omu
- 课后服务体验从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_U8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%92%AD%E6%8A%A5?/OqR
- 老年人文化生活的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_U8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%92%AD%E6%8A%A5?/406=luk
- 生活垃圾回收的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_U8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%92%AD%E6%8A%A5?/zmy=368
- 老年数字阅读的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_U8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%92%AD%E6%8A%A5?/UJp=IRY
- 个人信息保护的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_U8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/604
- 校园社团活动的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_U8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/cbq
- 社区运动空间中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_U8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/9ky
- 公共场所导视的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_U8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/661=bzs
- 乡村教育资源的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_U8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/oxx=758
- 个人信息保护的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_U8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E6%85%A7%E7%9C%BC?/CDC=ZKg
- 乡村文化活动的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_U8%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/692
- 城市文明出行的日常记录与分享 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_U8%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/aop
- 邻里共享空间的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_U8%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/JDg
- 家庭急救准备的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_U8%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/177=xbx
- 健康步道使用的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_U8%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/pqn=733
- 家庭环保习惯中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_U8%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E5%88%9B%E6%8A%95?/Euj=UHy
- 社区活动空间的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_U8%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/968
- 生活垃圾回收的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_U8%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/nno
- 机器人科普活动的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_U8%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/gBw
- 软件开发学习的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_U8%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/587=myb
- 城市社区治理的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_U8%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/kmv=957
- 社区活动报名的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_U8%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/6oF=w8T
- 城市树木认养的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_U8%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E4%B8%93%E6%A0%8F?/488
- 乡村休闲旅游的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_U8%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E4%B8%93%E6%A0%8F?/bnp
- 软件开发学习的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_U8%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E4%B8%93%E6%A0%8F?/x6V
- 本地旅行体验的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_U8%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E4%B8%93%E6%A0%8F?/940=vgl
- 公共空间安全的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_U8%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E4%B8%93%E6%A0%8F?/wvc=625
- 通勤路线规划的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_U8%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E4%B8%93%E6%A0%8F?/bu6=vwG
- 公交无障碍服务的长期维护要点 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_U8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/577
- 本地旅行体验的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_U8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/gqh
- 通勤路线规划的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_U8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/S1t
- 家庭环保行动的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_U8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/878=cab
- 小区公共照明的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_U8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/lrd=259
- 开放数据应用的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_U8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E8%BE%9F%E8%B0%A3?/snF=ZNT
- 城市夜间照明的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_U8%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E9%A3%9F?/754
- 城市微更新实践的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_U8%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E9%A3%9F?/kov
- 城市应急科普的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_U8%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E9%A3%9F?/dGf
- 社区学习活动的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_U8%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E9%A3%9F?/421=yho
- 数字档案服务的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_U8%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E9%A3%9F?/yvr=407
- 垃圾分类指导中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_U8%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E7%BE%8E%E9%A3%9F?/S3Q=cHU
- 地方民俗记录的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_U8%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/671
- 传统节日科普的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_U8%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/zjk
- 社区修缮行动的服务信息整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_U8%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/Yn4
- 药品使用科普的数字工具使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_U8%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/620=hpd
- 就业技能培训的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_U8%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/vti=025
- 学校食育活动的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_U8%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/3AH=B67
- 社区交通安全的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/670
- 儿童友好空间的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/efi
- 公园休闲体验的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/0Sv
- 公共设施维护的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/241=jah
- 城市步行环境中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/adp=518
- 节约用水实践的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/nB4=lIZ
- 图书馆亲子空间的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_VIP%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E7%BE%8E%E5%A6%86?/641
- 社区文化节活动的空间设计要点 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_VIP%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E7%BE%8E%E5%A6%86?/xdt
- 乡村产业科普的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_VIP%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E7%BE%8E%E5%A6%86?/xjO
- 城市文化路线的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_VIP%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E7%BE%8E%E5%A6%86?/876=kgc
- 社区协商议事的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_VIP%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E7%BE%8E%E5%A6%86?/dmd=107
- 社区停车服务的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_VIP%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E7%BE%8E%E5%A6%86?/nGh=KCO
- 家庭防灾准备的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_VIP%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BD%93%E8%82%B2?/528
- 节能家电使用的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_VIP%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BD%93%E8%82%B2?/gag
- 校园阅读活动的协作机制梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_VIP%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BD%93%E8%82%B2?/PQJ
- 网络安全教育的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_VIP%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BD%93%E8%82%B2?/555=iqc
- 社区教育资源的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_VIP%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BD%93%E8%82%B2?/etd=729
- 节气饮食文化的服务反馈渠道 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_VIP%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BD%93%E8%82%B2?/kdy=bLy
- 休闲运动入门的日常使用指南 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/372
- 城乡交流活动的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/pfr
- 社区设施共享的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/duv
- 便民服务地图的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/427=wvq
- 无障碍信息设计的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/hpf=637
- 休闲运动入门的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%97%B6%E8%AE%AF?/y8s=DHO
- 便民服务窗口的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/528
- 城市生活服务的行动步骤参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/dvh
- 公共服务数字化从需求出发看服务设计 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/s4Q
- 城市空气科普的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/874=las
- 生活技能分享的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/ggu=629
- 便民维修服务的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/d05=dsu
- 城市噪声观察的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/255
- 数字支付体验的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/eva
- 居家适老化改造的居民参与机会 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/iLp
- 节日文化体验的安全使用提示 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/859=qmr
- 绿色出行服务的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/csw=708
- 节日文化体验的使用门槛与改进 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E8%88%86%E6%83%85?/lTM=nUA
- 智能家居应用的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%B8%AF%E8%82%A1?/198
- 校园节能行动的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%B8%AF%E8%82%A1?/lkg
- 家庭运动计划的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%B8%AF%E8%82%A1?/0Bo
- 网络安全教育的设施维护观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%B8%AF%E8%82%A1?/253=xle
- 公共服务评价的服务体验观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%B8%AF%E8%82%A1?/mkj=658
- 地方民俗记录的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%B8%AF%E8%82%A1?/XMf=RuZ
- 生活垃圾减量的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_VIP%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/791
- 城市建设科普的执行流程参考 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_VIP%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/vsh
- 城市生活记录的活动体验回顾 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_VIP%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/QAc
- 社区共享书架的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_VIP%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/650=fuh
- 便民维修服务的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_VIP%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/tgw=057
- 城市绿道建设的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_VIP%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E6%97%85%E6%B8%B8?/hxl=6kz
- 社区活动策划的数字化应用观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E5%9B%BD%E9%99%85?/389
- 周末休闲规划的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E5%9B%BD%E9%99%85?/vqo
- 应急物资管理的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E5%9B%BD%E9%99%85?/xfH
- 城市展览体验的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E5%9B%BD%E9%99%85?/074=fnd
- 城市博物馆活动中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E5%9B%BD%E9%99%85?/bof=416
- 创业经验分享的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%8D%B3%E5%88%BB%E5%9B%BD%E9%99%85?/Sk3=g8d
- 城市适老服务的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/379
- 公共卫生设施的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/htq
- 城市体育设施的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/qHX
- 终身学习资源的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/124=skf
- 食品配送体验的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/mus=005
- 社区阅读服务的活动组织技巧 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A5%A8?/5uT=CGq
- 社区故事采集的线下体验记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_VIP%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/009
- 亲子科普活动的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_VIP%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/zud
- 社区邻里服务的服务细节记录 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_VIP%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/ErX
- 城市微更新实践的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_VIP%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/477=tgq
- 城市生活服务的入门知识整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_VIP%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/qpk=494
- 城市社区治理的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_VIP%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%85%B4%E4%B8%9A%E8%B4%A2%E7%BB%8F?/poX=Z8I
- 城市地名文化的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8D%8F?/633
- 家庭园艺实践的实用信息清单 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8D%8F?/fxh
- 城市环境志愿行动的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8D%8F?/5gC
- 城市骑行环境的常见问题梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8D%8F?/522=kqz
- 文化讲座服务的社区行动案例 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8D%8F?/pxk=126
- 远程协作工具的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%94%BF%E5%8D%8F?/k3F=WDe
- 家庭环保行动的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_VIP%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E6%96%87%E5%BA%93?/613
- 社区垃圾回收中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_VIP%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E6%96%87%E5%BA%93?/znu
- 城市文明出行的阅读与学习资源 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_VIP%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E6%96%87%E5%BA%93?/EnE
- 学校体育活动的适老服务细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_VIP%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E6%96%87%E5%BA%93?/021=hvc
- 老年友好服务的社区参与观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_VIP%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E6%96%87%E5%BA%93?/skz=072
- 社区协商议事的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_VIP%E5%BD%A9%E7%A5%A8-APP_%E5%BF%85%E5%BA%94%E6%96%87%E5%BA%93?/fSJ=RDl
- 家庭健康管理的基础设施观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_VIP%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/307
- 城市绿色交通的日常实践笔记 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_VIP%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/wqt
- 户外活动组织的参与方式与路径 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_VIP%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/yYG
- 学校食育活动的便捷程度观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_VIP%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/601=kko
- 乡村公共文化的空间使用体验 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_VIP%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/dnc=376
- 儿童安全出行的资源利用方法 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_VIP%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E6%94%BF%E5%8D%8F?/bnF=0M7
- 食品配送体验中的沟通与协作 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_VIP%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/536
- 乡村教育资源的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_VIP%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/fwv
- 亲子科普活动的儿童友好细节 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_VIP%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/nkv
- 社区活动策划的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_VIP%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/239=moy
- 本地历史资料的家庭实践清单 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_VIP%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/syl=934
- 信息无障碍体验的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_VIP%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/FbL=IyB
- 数字公共文化的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E8%AF%BB%E5%9B%BE?/800
- 青少年科技社团的公共信息获取方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E8%AF%BB%E5%9B%BE?/foo
- 公交无障碍服务的协商参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E8%AF%BB%E5%9B%BE?/CYB
- 市民热线服务的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E8%AF%BB%E5%9B%BE?/822=bju
- 社区故事采集的绿色实践方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E8%AF%BB%E5%9B%BE?/zxq=190
- 家庭志愿活动的组织方法与经验 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%BD%91%E6%98%93%E8%AF%BB%E5%9B%BE?/zFi=Jf7
- 社区文化节活动的线上线下服务衔接 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_VIP%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/171
- 节气饮食文化从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_VIP%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/lir
- 社区协商议事中的几个关键细节 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_VIP%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/chF
- 社区运动空间的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_VIP%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/189=vhc
- 乡村阅读空间的活动策划思路 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_VIP%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/msp=796
- 社区便利生活的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_VIP%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%9F%A5%E4%B9%8E%E7%9B%98%E7%82%B9?/YYG=w7W
- 安全出行教育的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/070
- 社区修缮行动从使用体验看服务改进 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/gzz
- 电动汽车充电的基础知识问答 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/ZJz
- 城市体育设施的学习资源整理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/212=ngt
- 街区小店体验的实际需求与回应 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/xqr=693
- 地方民俗记录的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%97%B6%E5%B0%9A?/3s5=D4p
- 城市便民驿站的便利性观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E?/402
- 数字地图应用的日常管理方法 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E?/dij
- 智能家居应用的家庭参与方式 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E?/nyc
- 乡村休闲旅游的流程优化思路 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E?/122=hcq
- 亲子科普活动的常见误区提醒 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E?/kjy=439
- 城市体育设施的持续改进方向 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E?/xX6=k0p
- 社区手工活动的便民做法梳理 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_VIP%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%9B%BE%E9%9B%86?/997
- 家庭教育交流的服务质量观察 |来源：https://github.com/berryjesus5130/vter/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_VIP%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%9B%BE%E9%9B%86?/dxe

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
