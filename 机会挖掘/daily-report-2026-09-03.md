# 创业机会情报日报 2026-09-03

> 采集时间：2026-09-03 20:08 (Asia/Shanghai)
> 覆盖渠道：Hacker News / Product Hunt / Reddit (r/Entrepreneur, r/SaaS, r/SomebodyMakeThis) / Exploding Topics / G2 & Capterra 差评挖掘 / Killed by Google / 中文互联网（新华社、QuestMobile、语雀 AI 日报）

---

## 一、今日热门趋势（5 条）

### 1. AI 智能体从"被动问答"转向"主动协作者"，Agent 进入生产工作流
- **信号强度**：★★★★★（极强，多平台共振）
- **发生了什么**：Product Hunt 今日榜单第一名梯队被"会主动干活的 AI 同事"占据。Viktor.com（"an AI coworker that actually does the work"）位居今日 Top 10，其卖点是不等用户提问、观察团队工作方式后主动介入并建议自动化流程，直接生活在 Slack 里；Interactive Sessions（用 AI 智能体驱动完整 SDLC）；Skydive（构建跨工具的云端智能体）。Hacker News 同日的 "Understanding ChatGPT Work"（177 points）也在讨论智能体工作模式。
- **为什么重要**：过去一年"AI 助手"本质是"人提问、模型回答"的线性模式；现在产品叙事正在转向"Agent 主动观察→发现关联→建议/执行自动化"。这意味着"最后一个需要打开的新 Tab"将被"住在已有沟通工具里的同事"取代，是一次产品交互范式的迁移。
- **底层原因**：大模型从 L1（基础对话）→ L2（推理）→ L3（Agent 行为执行）的跃迁；吴恩达多次强调 Agentic AI 是当前最重要的技术趋势，从"预测下一个 token"走向"执行动作"。上下文/记忆/工具调用的工程化成熟，让 Agent 得以长期驻留并主动行动。
- **数据支撑**：Exploding Topics 上 Workflow Automation Platform 搜索 5 年增长 +2400%，AI Observability +9300%，Prompt Engineering +5600%；Product Hunt "Trending categories" 中 Vibe Coding Tools、AI Coding Agents 稳居前列；中文侧"AI 厂商日报"报道 2026 年 1 月行业共识"Chat 范式已终结，AI 竞争转向能办事的智能体时代"。
- **创业机会方向**：① 垂直场景的"驻留式 Agent"（住在钉钉/Slack/企业微信里，主动建议而非被动问答）；② Agent 的护栏、审计与回滚层（见"AI 可观测性"趋势）。
- **谁已经在做了**：Viktor（Zeta Labs 团队，前作 Jace AI 邮件助手）、Interactive Sessions、Skydive、OpenAI/Anthropic 的 agent 产品线、字节豆包/千问等国产 Agent。
- **来源**：Product Hunt 今日榜单、Hacker News、Exploding Topics、吴恩达演讲（语雀）

### 2. AI 成本焦虑全面爆发：SAP 冻结招聘与差旅为 Token 买单
- **信号强度**：★★★★★（极强，巨头信号）
- **发生了什么**：SAP 于 2026-07-01 内部备忘录宣布冻结大部分差旅与非 AI 岗位招聘，仅保留面向客户和核心 AI 岗位，官方理由直指"Token 用量和相关成本随更多 AI 场景上线而上升"。为此 SAP 自 2025 年底已投入近 10 亿美元到 AI，并重组 8000 个岗位；7 月 6 日、17 日先后完成 Dremio（数据湖仓/查询）和 Prior Labs（AI 建模）两笔收购，输掉了与施耐德电气争夺 Cognite（工业 AI，31 亿美元）的交易。
- **为什么重要**：过去两年生成式 AI 的叙事是"推理成本持续下降，企业可激进采用而无需担心账单"。SAP 这种体量的公司为了覆盖自身 Token 账单而冻结差旅和招聘，是反方向的关键数据点——AI 正从"降本工具"变成"成本黑洞"。
- **底层原因**：当 AI 场景从 demo 走向规模化生产，Token 消耗量非线性放大；模型厂商承诺的降价曲线在"用量爆发"面前被抵消。企业 CFO 开始把推理视为"运营税"。
- **数据支撑**：SAP 股价年初至今下跌约 33%（部分报道称一年跌 47%）；SAP 被 90% 以上 Fortune 500 采用；DSAG 调查显示 SAP 客户中 70% 以上的 AI 用量来自第三方、仅 3% 使用自家 Joule；Oracle 为 AI 数据中心裁员数万人、Salesforce 与微软同样承压。
- **创业机会方向**：AI 成本管控与 Token 优化平台（FinOps for AI）、推理成本预测与配额管理、多模型路由降本、企业 AI 用量审计。
- **谁已经在做了**：DepthData（Product Hunt 上"AI 支出的 system of record"）、TraceLLM（生产 AI 的 OpenTelemetry）、OpenAI/各家推出的 cost optimization 层。
- **来源**：404 Media / aiweekly.co、The Next Web、MarketScale、LinkedIn 从业者讨论、Exploding Topics

### 3. 可负担的具身智能：1688 美元双臂人形机器人 + 消费级机器人产品
- **信号强度**：★★★★☆
- **发生了什么**：Nori Robotics 在 Hacker News 引发关注——一台 1688 美元的双臂移动人形机器人，面向开发者和研究者做数据集采集与实验，把"研究级硬件"拉到了"个人可负担"区间。同日 Google 发布 Gemini Robotics 2（"下一代机器人的 AI 大脑"）进入 Product Hunt 榜单。
- **为什么重要**：机器人长期卡在"实验室太贵、个人买不起"；价格下探到 2000 美元以下，意味着开发者/个体 maker 能像买一台 Mac 一样买机器人做实验，数据集与算法迭代会被大幅加速，形成新的开发者生态。
- **底层原因**：具身智能被列为 2026 核心方向之一；世界模型（如李飞飞 World Lab）需要大量真实物理数据反哺；供应链成熟让电机/关节成本下降。
- **数据支撑**：Nori Robotics 定价 1688 美元；Hacker News 帖子讨论活跃；中文侧"2026 AI 技术趋势"将"具身智能/人形机器人+AI 迎来爆发"列为四大方向之一。
- **创业机会方向**：机器人开发者工具链、机器人数据集众包、廉价具身智能实验平台、机器人技能模型市场。
- **谁已经在做了**：Nori Robotics、Google（Gemini Robotics 2）、李飞飞 World Lab、HONOR Robot Phone（带云台的手机）。
- **来源**：StartupCorners 9/2 摘要、Hacker News、Product Hunt、语雀趋势文档

### 4. "AI 可观测性 / 护栏 / 成本治理"成为独立且高速增长的赛道
- **信号强度**：★★★★☆
- **发生了什么**：从多个来源同时涌现：Exploding Topics 显示 AI Observability 搜索 5 年增长 +9300%、AI Guardrails +8400%、Responsible AI +3500%；Product Hunt 榜单中 DepthData（AI 支出的 system of record）、TraceLLM（生产 AI 的 OpenTelemetry）集中上榜；Hacker News 出现 "Meta Security Researcher's AI Agent Accidentally Deleted Her Emails"（AI 智能体误删邮件）。
- **为什么重要**：当企业真正把 Agent 放进生产、赋予其执行权限时，一个全新的问题层被打开——如何观测、限制、回滚、审计 Agent 的行为。这与"AI 成本焦虑"同源：从"能不能生成"转向"能不能安全、可控、省钱地长期运行"。
- **底层原因**：Agent 从"只读建议"升级为"可写执行"，风险面从内容错误扩展到误操作、权限滥用、数据泄露、成本失控；监管与合规（欧盟 AI Act 等）倒逼企业建立护栏。
- **数据支撑**：AI Guardrails +8400%、AI Observability +9300%（Exploding Topics 5 年搜索增长）；Meta 安全研究员 AI 智能体误删邮件的真实事故登上 HN。
- **创业机会方向**：Agent 行为审计与回滚、AI 护栏中间件、LLM 可观测性（追踪 token/延迟/成本/质量）、合规报告自动化。
- **谁已经在做了**：TraceLLM、DepthData、LangSmith（LangChain）、各大云厂商的可观测套件。
- **来源**：Exploding Topics、Product Hunt、Hacker News

### 5. 开源替代与"反封闭工具"浪潮：OpenSEO、开源 GPU 价格指数、开源 JetBrains 编码 Agent
- **信号强度**：★★★☆☆
- **发生了什么**：Product Hunt 上月榜单出现 OpenSEO（"开源版 Ahrefs"）；9/2 榜单出现 Computable GPU Index（CGI，首个开源 GPU 算力价格指数）、Kilo Code for JetBrains（原生开源编码 Agent）、Nodeterm（开源终端管理器）；Hacker News 有 "SM750（Silicon Motion GPU）开源 HDMI 驱动"（107 points）。
- **为什么重要**：开发者社区持续用"开源"对冲"封闭、不透明的工具定价"。从 SEO 分析、GPU 价格到编码 Agent，每个高价位商业工具背后都有人在推开源替代，这是低成本创业者的持续切入窗口。
- **底层原因**：商业工具价格随 AI 功能捆绑上涨，独立开发者与中小团队对成本敏感；开源+托管（open core）模式成为可持续变现路径。
- **数据支撑**：OpenSEO 上月 PH 第一、Ahrefs 相关搜索 5 年 +1150%；CGI 目标提供透明 GPU 成本基准；Payload CMS +3100%、Penpot +6800% 等开源工具趋势持续上行。
- **创业机会方向**：高价商业 SaaS 的开源替代 + 托管变现；GPU/算力价格透明度工具；开发者工具 open core。
- **谁已经在做了**：OpenSEO、Computable GPU Index、Kilo Code、Nodeterm、Penpot、Payload。
- **来源**：Product Hunt、StartupCorners、Exploding Topics

---

## 二、用户痛点（9 条）

### 1. AI 成本失控、Token 账单无法预测
- **痛点一句话**：企业上线 AI 后，Token 账单像水龙头没关，谁在花、花在哪、下个月多少，完全看不见。
- **典型用户画像**：CIO/CFO、AI 平台负责人、SaaS 公司的增长负责人。
- **具体场景**：SAP 为覆盖自身 Token 账单冻结差旅与非 AI 招聘；企业内部 AI 工具全量推广后"疑似大幅推高成本"。
- **为什么现有方案不行**：云厂商只给账单不给洞察；各模型价格体系割裂；缺乏跨模型的用量归因与预测。
- **情绪强度**：★★★★★（直接触发巨头级成本管控动作）
- **付费意愿信号**：企业已用"冻结招聘/差旅"这种极端方式买单，第三方 FinOps for AI 有明确预算转移空间。
- **来源**：404 Media、The Next Web、Product Hunt（DepthData）

### 2. 移动端项目管理工具功能缺失
- **痛点一句话**：团队移动办公时，主流的项目管理 App 是"桌面版的阉割移植"，加载慢、功能缺、体验差。
- **典型用户画像**：远程/混合办公团队、现场项目经理、高频差旅的管理者。
- **具体场景**：G2/Capterra 差评聚合显示"Absence of Mobile Functionality"严重度 4.5/5，横跨多个 PM 工具。
- **为什么现有方案不行**：主流 PM 工具把移动端当附属品，先做桌面再"降级"到手机。
- **情绪强度**：★★★★☆
- **付费意愿信号**：严重度接近 deal-breaker（4.5/5），属于"churn 级"痛点。
- **来源**：BigIdeasDB 对 G2/Capterra 差评聚合

### 3. 邮件模板编辑器难用、跨客户端渲染不一致
- **痛点一句话**：拖拽式邮件模板编辑器在复杂布局下会坏，不同邮箱客户端渲染不一致。
- **典型用户画像**：市场运营、EDM 负责人、电商卖家。
- **具体场景**：Mailchimp、Constant Contact、ActiveCampaign 的用户都在抱怨模板构建流程低效（严重度 4.5/5）。
- **为什么现有方案不行**：主流 EDM 平台模板构建器老旧，跨客户端兼容性差。
- **情绪强度**：★★★★☆
- **付费意愿信号**：营销团队已为 EDM 付费，愿为"能稳定渲染的独立模板构建器"单独买单。
- **来源**：BigIdeasDB G2/Capterra 聚合

### 4. 分析/BI 工具数据加载慢
- **痛点一句话**：看个数据要等 30-60 秒，大表一打开就转圈。
- **典型用户画像**：数据团队、运营分析、BI 使用者。
- **具体场景**：主流 BI/分析工具在数据量上来后加载缓慢，严重度 4.5/5。
- **为什么现有方案不行**：通用 BI 追求全功能，性能在规模化数据上妥协；轻量替代（Plausible、Fathom）已证明"快"本身有市场。
- **情绪强度**：★★★★☆
- **付费意愿信号**：已有 Plausible/Fathom 等速度型工具验证了需求。
- **来源**：BigIdeasDB G2/Capterra 聚合

### 5. 智能家居过度依赖云：门铃要 5 个云服务才能响
- **痛点一句话**：一个门铃要串 5 个云服务，断网或服务宕机就失灵，还交着订阅费。
- **典型用户画像**：隐私敏感、追求本地可控的智能家居用户。
- **具体场景**：Hacker News 热帖 "It takes 5 cloud services to hear my doorbell"（148 points）。
- **为什么现有方案不行**：厂商为锁订阅把简单功能云端化，隐私和可靠性都牺牲。
- **情绪强度**：★★★★☆
- **付费意愿信号**：帖子高热度反映普遍反感；本地优先（local-first）是明确的差异化方向。
- **来源**：Hacker News

### 6. 火箭发射提醒服务（已存在但失效）
- **痛点一句话**：想看发射却总错过，之前有人做过提醒服务但已停运。
- **典型用户画像**：航天爱好者、加州 Vandenberg 附近居民。
- **具体场景**：Reddit r/SomebodyMakeThis 用户明确"希望有个 App/服务在发射前提醒，已错过两次 SpaceX 发射"。
- **为什么现有方案不行**：曾有热心人做的服务已下线，无持续运营方。
- **情绪强度**：★★★☆☆
- **付费意愿信号**：明确的需求表达，但付费能力存疑（适合低成本侧项目）。
- **来源**：Reddit r/SomebodyMakeThis

### 7. 垂直俱乐部（骑行等）缺专用网站模板
- **痛点一句话**：骑行/运动俱乐部要博客+相册+路线地图+活动日历，找不到合用的模板，定制又贵。
- **典型用户画像**：非技术背景的俱乐部管理员。
- **具体场景**：Reddit 用户求"德国骑行俱乐部"网站模板，含分栏目博客、Garmin/Strava 路线嵌入、日历。
- **为什么现有方案不行**：通用 CMS 模板不覆盖垂直需求；定制开发成本高。
- **情绪强度**：★★★☆☆
- **付费意愿信号**：明确"定制很贵、想要模板"，是垂直 SaaS 的经典切入点。
- **来源**：Reddit r/SomebodyMakeThis

### 8. 消费收据无法按品类拆分
- **痛点一句话**：Walmart 账单只告诉你在 Walmart 花了多少钱，不告诉花在什么品类上。
- **典型用户画像**：精打细算的消费者、做预算的用户。
- **具体场景**：Reddit 用户求"扫描 Walmart 收据按品类拆分支出的软件"。
- **为什么现有方案不行**：通用记账工具无法自动识别收据行项目品类。
- **情绪强度**：★★☆☆☆
- **付费意愿信号**：付费意愿弱，适合作为大记账产品的功能而非独立创业。
- **来源**：Reddit r/SomebodyMakeThis

### 9. 面试/公开演讲缺乏陪练
- **痛点一句话**：面试、销售路演、演讲前焦虑没处练，没人陪练。
- **典型用户画像**：求职者、销售新人、需要公开表达的人群。
- **具体场景**：Reddit 用户自建"连接陌生人做视频陪练"的 Web App 并征集反馈。
- **为什么现有方案不行**：真人陪练贵、AI 陪练缺真实感与即时反馈闭环。
- **情绪强度**：★★★☆☆
- **付费意愿信号**：已有创业者入场做视频陪练，AI 陪练是热门方向（PH 上 Orato"用 AI 练习口语"）。
- **来源**：Reddit r/SomebodyMakeThis、Product Hunt（Orato）

---

## 三、创意点子（6 条）

### 1. AI FinOps 平台：Token 账单的"分账 + 预测 + 降本"
- **触发点**：SAP 冻结招聘为 Token 买单；DepthData、TraceLLM 上榜。
- **目标用户**：已经规模化用 AI 的中型企业（有真实 AI 账单的团队）。
- **冷启动策略**：先做一个免费的开源 token 用量探针/聚合器，接主流 LLM API，靠"你的 AI 账单可视化"获客，再上企业配额与降本功能。
- **差异化**：跨模型（OpenAI/Anthropic/国产模型）统一归因 + 多模型路由降本 + 成本预测，而非单一云厂商的账单页。
- **风险**：云厂商与模型厂商可能原生提供；定价天花板取决于客户 AI 支出规模。

### 2. 移动优先的项目管理工具
- **触发点**：G2 差评"移动功能缺失"严重度 4.5/5。
- **目标用户**：现场型/混合办公团队（建筑、零售、活动执行、外勤）。
- **冷启动策略**：从单一垂直（如活动执行或外勤巡检）切入，主打"手机上能完成 90% 操作"，在 Reddit r/SomebodyMakeThis 与 r/productivity 造声量。
- **差异化**：先做移动端而非桌面降级移植；离线优先。
- **风险**：大厂补移动端后挤压；垂直太窄则天花板低。

### 3. 独立邮件模板构建器（跨客户端可靠渲染）
- **触发点**：EDM 平台模板构建器差评严重度 4.5/5。
- **目标用户**：市场/运营/电商团队。
- **冷启动策略**：做"所见即所得 + 跨客户端预览 + 一键导出到 Mailchimp/ActiveCampaign"的独立工具，靠 SEO 内容（"邮件客户端兼容性"）获客。
- **差异化**：专注渲染可靠性与跨客户端预览，而非再做一个 EDM 平台。
- **风险**：EDM 平台原生改进后需求萎缩；获客依赖 SEO，见效慢。

### 4. 轻量快速分析/BI（"打开就出数"）
- **触发点**：BI 工具"加载慢 30-60 秒"差评严重度 4.5/5。
- **目标用户**：被重 BI 拖累的运营/数据团队。
- **冷启动策略**：开源 + 单机部署，主打"小团队 5 分钟跑起来、秒开报表"，对标 Plausible 的路径。
- **差异化**：速度与部署简单为第一性，砍掉重 BI 的复杂建模层。
- **风险**：功能天花板与商业化难度（开源变现在国内尤其难）。

### 5. 本地优先的智能门铃/家居网关
- **触发点**：HN "门铃要 5 个云服务"（148 points）。
- **目标用户**：隐私敏感、讨厌订阅、有折腾能力的家居用户。
- **冷启动策略**：开源硬件+软件方案，先做"单设备本地运行、无订阅"的门铃，在 HN/Reddit 造势。
- **差异化**：local-first、无云依赖、数据自持，切中云订阅反感情绪。
- **风险**：硬件供应链与售后成本高；市场规模偏 niche。

### 6. 垂直俱乐部/社群网站模板平台
- **触发点**：Reddit 求"骑行俱乐部模板"。
- **目标用户**：骑行、跑步、登山等运动俱乐部管理员（非技术）。
- **冷启动策略**：先做"骑行俱乐部"一个模板（博客+相册+Strava 路线嵌入+活动日历），收费定制化，验证后复制到其他运动。
- **差异化**：垂直模板 + 运动数据（Strava/Garmin）原生集成，而非通用建站。
- **风险**：单垂直付费能力弱，需多垂直复制；通用建站平台可能下沉覆盖。

---

## 四、潜在创业方向（3 个）

### 1. AI 成本管控与 Token 优化平台（FinOps for AI）
- **市场规模**：企业 AI 支出正以非线性速度增长，SAP 单家已投入近 10 亿美元；中文侧"中国日均 Token 消耗一年半增长 300 倍"级增速；AI Observability 搜索 5 年 +9300% 佐证需求爆发。保守估计这是下一个十亿美元级的中间件赛道。
- **竞争格局**：早期且碎片化——云厂商只给账单、无洞察；DepthData、TraceLLM 等创业公司刚起步；LangSmith 偏开发侧。尚无跨模型、面向 CFO 的统一"AI 成本管理"成熟玩家。
- **验证路径**：先做开源 token 用量聚合器，找 10 家有真实 AI 账单的团队访谈，确认他们是否愿为"分账+预测+降本"付费；用一两个高耗能客户跑通降本 ROI 再放大。
- **商业模式**：SaaS 订阅（按 token 用量/席位）+ 降本效果分成。
- **风险与护城河**：风险是云厂商/模型厂商原生下沉。护城河在于跨模型中立性与用量归因数据沉淀。

### 2. AI 可观测性与护栏（Agent Observability & Guardrails）
- **市场规模**：Agent 进入生产是确定性趋势（Viktor、Interactive Sessions 等），每个生产 Agent 都需要观测/审计/回滚层；AI Guardrails 搜索 5 年 +8400%、AI Observability +9300%。
- **竞争格局**：OpenTelemetry 生态在向 AI 延伸（TraceLLM 即为"生产 AI 的 OpenTelemetry"）；LangSmith、大厂套件并存，但"Agent 行为审计+回滚+护栏"这一层尚无统治者。
- **验证路径**：从"Agent 误删邮件"这类事故切入，做一个轻量 Agent 权限/回滚 SDK，找早期用 Agent 的团队试点。
- **商业模式**：开源 SDK + 托管 SaaS；按 Agent 数量/事件量计费。
- **风险与护城河**：风险是大厂标准（如 OpenTelemetry）快速覆盖。护城河在于 Agent 行为语义库与护栏规则生态。

### 3. 高价商业 SaaS 的开源替代 + 托管变现（open core）
- **市场规模**：SEO 分析（Ahrefs 相关搜索 +1150%）、设计协作（Penpot +6800%）、无头 CMS（Payload +3100%）等，都是数亿到数十亿美元规模的被替代市场。
- **竞争格局**：每个方向有 1-2 个开源挑战者（OpenSEO、Penpot、Payload），但商业化多未跑通，留出"托管+企业版"空间。
- **验证路径**：选一个高频高价的商业工具（如 Ahrefs），先开源核心功能，用 GitHub 增长验证开发者需求，再上托管与企业功能。
- **商业模式**：开源免费 + 云托管订阅 + 企业私有化授权。
- **风险与护城河**：风险是变现周期长、开源被大厂白嫖。护城河在于社区与品牌，以及托管服务的规模效应。

---

## 五、中文渠道观察（3 条）

### 1. 中国 AI 产业进入"价值收割"期，头部扎堆上市
- 新华社《2026 年中国 AI 发展趋势前瞻》数据：AI 企业超 6000 家，AI 核心产业规模预计突破 1.2 万亿元、同比增长近 30%；国产开源大模型全球累计下载量突破 100 亿次；中国 AI 专利全球占比达 60%。2026 年 1 月以来智谱、天数智芯、MiniMax 等国内 AI 企业扎堆上市；清华大学 AGI-Next 峰会形成共识——以对话为核心的"Chat"范式终结，竞争转向"能办事"的智能体时代。**来源**：新华社 / 语雀 AI 厂商日报。

### 2. 流量红利转向"服务红利"，平台从掠夺式增长转向用户价值深耕
- QuestMobile《2025-2026 年度核心趋势报告》提出"智变重构用户价值，流量红利跃迁为服务红利"，AI 从单点突破走向系统化赋能，智能终端从"设备中心"转向"用户中心"，平台运营从"流量掠夺"转向"用户价值深耕"。这对应创业逻辑从"买流量"转向"做留存与深度服务"。**来源**：QuestMobile 报告（uone.alibaba-inc.com）。

### 3. 融资逻辑从"模型竞赛"转向"价值收割"，国产大模型向头部集中
- ATA《AI 下半场》深度拆解指出：2026 年全球 AI 融资从"大炼模型"转向"价值收割"，美国聚焦 AGI 超级独角兽与垂直工具高估值，中国回归理性、向"技术壁垒+商业闭环"双驱动的头部国产大模型集中。智谱 GLM-5（256K 上下文）于 4 月发布，2026 Q1 完成 5 亿美元 C 轮、估值约 50 亿美元，成国产第一梯队代表；千问、Kimi、豆包同步向"语言到 action"的 Agent 方向跃迁。**来源**：ATA 文章 / 语雀 AI 厂商日报。

---

## 六、采集元数据

| 渠道 | 状态 | 关键信号 |
| --- | --- | --- |
| Hacker News | ✅ 已采集 | 顶部 30 帖：Creepy Crawlies 1139、IKEA Hacking 313、Haiku R1/beta6 315、门铃需 5 云服务 148、Meta AI 误删邮件 |
| Product Hunt | ✅ 已采集 | 今日 Top：Video Agent by Fotor、BrandJet、Viktor AI coworker、Interactive Sessions；上月：OpenSEO、DepthData、TraceLLM |
| Reddit | ✅ 已采集 | r/SomebodyMakeThis 痛点：火箭发射提醒、骑行俱乐部模板、收据分类、面试陪练 |
| Exploding Topics | ✅ 已采集 | AI Observability +9300%、AI Guardrails +8400%、AEO +7500%、Workflow Automation +2400% |
| G2/Capterra 差评 | ✅ 已采集 | 移动功能缺失 4.5/5、邮件模板 4.5/5、数据加载慢 4.5/5（BigIdeasDB 聚合） |
| Killed by Google | ✅ 已采集 | Google Tables（Airtable 竞品）判死、Jamboard/Chromecast/Google Domains 等已关停，累计 298 个 |
| ideaSearch | ⚠️ 间接覆盖 | 通过 BigIdeasDB/G2 差评挖掘方法论与 idea 验证框架覆盖（ideaSearch 站点未直接可检索） |
| 中文互联网 | ✅ 已采集 | 新华社 1.2 万亿产业规模、QuestMobile 服务红利、智谱 GLM-5 融资 |

**采集说明**：killedbygoogle 首次直搜失败后改用 "killed by google 2026 list" 成功；Meta AI 误删邮件细节直搜失败，采用 HN 标题信号（24 points）；ideaSearch 站点直搜未命中，以其方法论等价来源（BigIdeasDB 差评挖掘 + First Round/Medium 验证框架）替代。
