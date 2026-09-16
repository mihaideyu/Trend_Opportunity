# 创业机会情报日报 2026-09-16
> 采集时间：2026-09-16 08:05 (Asia/Shanghai)
> 覆盖渠道：Hacker News / Product Hunt / Reddit(r/SaaS、r/SomebodyMakeThis、r/Entrepreneur) / Exploding Topics / G2/Capterra / Killed by Google / ideaSearch / 中文互联网(QuestMobile 等) / 补充搜索(GEO、AI 成本、Agent 安全)
---

## 一、今日热门趋势（4 条）

### 1. AI 从"降本工具"变成"成本黑洞"：SAP 冻结全部非 AI 招聘与差旅，Token 消耗成为企业新财务科目
- **信号强度**：★★★★★（巨头级财务信号 + 头部厂商集体动作）
- **发生了什么**：德国软件巨头 SAP（年收入超 300 亿欧元，服务全球 40 万家企业 ERP）据彭博社报道，正式冻结非 AI 相关的新员工招聘，并削减非 AI 商务差旅，将省下的钱全部投入"大规模 AI 战略"。SAP 首席控制官 Lukas Deutsch 公开撰文称"AI token 消耗"已成为财务部"不习惯管理的全新成本科目"，并披露 SAP 内部通过 token 上限（token capping）、模型路由（model routing）、工具收敛（tool rationalization）三大杠杆，才"遏制住数亿美元（triple-digit-million-dollar）级别的财务风险"。
- **为什么重要**：当全球 ERP 龙头都扛不住 AI 推理成本、需要冻结招聘来输血时，说明 AI 的边际成本问题已从科技巨头蔓延到所有拥抱 AI 的传统企业。AI 不再是"免费/便宜的生产力"，而是一个会随用户量线性/指数增长的可变成本。
- **底层原因**：推理成本按 token 计费、随调用量持续增长；企业普遍"只看到 AI 总账单、看不到哪个团队/功能在烧钱"；多数团队从不设 token 上限，demo 阶段便宜、上生产后失控。
- **数据支撑**：42% 的组织把"优化 AI 工作流与成本"列为 2026 年首要支出优先级（Deloitte《State of AI in the Enterprise 2026》）；首次 FinOps 优化通常可回收 30–45% 的 AI/云支出；SAP 自曝推出 AI 开发工具后 PR 合并率提升"中双位数百分比"，但 token 成本也随之暴涨；MIT 研究显示 95% 的企业 AI 试点停滞或未证明可量化收益。
- **创业机会方向**：AI Token 治理与 FinOps 平台——按团队/功能/客户归因 AI 成本、模型路由（小模型做简单任务）、缓存/批处理、token 上限与预算告警、Agent 级成本审计。
- **谁已经在做了**：Amnic（token+云+K8s 一体视图）、TrueFoundry（LLM 网关/缓存/路由）、Helicone（开源 LLM 可观测）、Mavvrik（按 feature/customer/agent 归因）、CloudZero（单位经济学）、Cast AI / nOps / Usage.ai（云/基础设施侧）。
- **来源**：彭博社(SAP 冻结招聘)、SAP News Center《Managing AI Token Spend Without Slowing Innovation》、Thinklytics/Deloitte 2026 FinOps 报告。

### 2. GEO（生成式引擎优化）赛道 18 个月从"不存在"到"过饱和"：Adobe 1.9B 美元买 Semrush，资本涌入超 2.55 亿美元
- **信号强度**：★★★★★（资本密集 + 巨头并购 + 结构性流量迁移）
- **发生了什么**：传统搜索正被 AI 搜索系统性替代——ChatGPT 周活超 8 亿，60% 以上信息检索经 AI 平台完成，Gartner 预测 2026 年传统搜索量下降 25%。"被 AI 引用"取代"被搜索到"成为品牌新的分发命脉。这一品类两年内从无到有、再到过饱和：Profound 成立 18 个月即达 10 亿美元独角兽估值；Adobe 以 19 亿美元收购 Semrush（部分为 GEO 能力）；纯 GEO 初创累计融资超 2.55 亿美元，投资人包括 Sequoia、Lightspeed、Kleiner Perkins、NVIDIA NVentures。
- **为什么重要**：AI 回答里"品牌是否被提及"正在取代传统 SEO 排名成为获客入口，而 AI 答案引用的信源"最高 90% 会随时间漂移"，这是一个全新的、必须持续运营的分发战场，也意味着大量内容型企业的流量正在被重新洗牌。
- **底层原因**：AI 搜索用一段生成式段落替代十页链接，优化目标从"关键词+外链"变成"引用、情感、心智份额"，测量对象从确定性排名变成概率性回答。
- **数据支撑**：2026 Q1 全球风投 3000 亿美元中 AI 拿走 2420 亿（80%）；GEO 纯玩家融资超 2.55 亿美元；Profound 独占 1.55 亿美元；Peec AI 一年 1300+ 客户、月增 300+。
- **创业机会方向**：面向中小企业/出海品牌的"轻量级 GEO 监测+优化"工具；面向垂直行业（法律、医疗、金融）的"防 AI 幻觉/错误引用"监测（Scrunch AI 已切入监管行业）；GEO 与程序化广告打通（Evertune 路径）。
- **谁已经在做了**：Evertune($19M)、Peec AI($29.1M)、AirOps($60M)、Bluefish($24M)、Scrunch AI($19M)、AthenaHQ($2.7M)、Otterly AI/Knowatoa/Rankscale(自举)。产品价格带从 $29/月到 $15,000/月。
- **来源**：Evertune《Top 15 GEO Platforms 2026》、Higashi/CloudAnalyst《GEO Tools: The Competitive Landscape 2026》、Product Hunt（Visiby 今日上榜）。

### 3. AI Agent 安全成为独立赛道：白帽 25 分钟拿到 Baseten 生产 GitHub 管理权，MCP 提示注入攻击 84% 成功率
- **信号强度**：★★★★★（技术漏洞实证 + 基础设施新攻击面）
- **发生了什么**：安全研究团队 strix.ai 在 HN 发帖称"25 分钟拿到 Baseten（AI 推理平台）生产环境 GitHub 的管理员权限"（191 分热帖）。此前 GitHub MCP 已曝出高危漏洞：攻击者在公开仓库提交恶意 Issue，诱导有权限的 AI Agent 把私有仓库的 .env/密钥聚合后提交到公开 README，实现数据外泄（"致死三要素"：不可信输入 + 敏感数据访问 + 外泄通道）。据 Invariant Labs，84% 针对代码 Agent 的注入攻击成功。
- **为什么重要**：Agent 正在被赋予越来越高的生产权限，但"提示注入无法根治（是 Transformer 架构的副作用）"。这意味着 AI Agent 安全护栏（guardrails）、MCP 网关、Agent 运行时治理是一个刚需且几乎空白的新基础设施层。
- **底层原因**：Agent 无法区分"系统指令"与"外部不可信内容"，越多的上下文 token 意味着越大的攻击面；传统 IAM/PKI 的人为信任模型不适用于"被自然语言诱导的 Agent"。
- **数据支撑**：GitHub 上 mcp-security 主题已有 255 个仓库；84% 注入攻击成功；GitHub Copilot 曾曝 9.6/10 严重度提示注入漏洞。
- **创业机会方向**：MCP 网关/企业 AI bastion host（统一代理+RBAC+审计+限流+成本追踪）；Agent 运行时防火墙（扫描 egress 防外泄/SSRF/提示注入）；"敏感操作强制人工审批"网关；Agent 输出扫描与凭据脱敏。
- **谁已经在做了**：Runlayer、Lunar.dev（Agent native MCP Gateway）、ToolHive（企业级 MCP server 管理）、多款开源 Agent 防火墙（Go/Rust/Python）、YC W23 的合规 Agent 平台。
- **来源**：Hacker News（Baseten 帖）、Runlayer《GitHub MCP Vulnerability》、GitHub mcp-security 主题、Invariant Labs/LinkedIn 分析。

### 4. 推理硬件与端侧 AI 拐点：Perplexity 推"云研究+Mac 隐私"混合计算，Google 发布 Gemini 3.8 Live
- **信号强度**：★★★★☆
- **发生了什么**：Product Hunt 今日榜首 Perplexity Hybrid Compute 把 AI 任务拆成"云端做研究、Mac 本地跑隐私"，标志"端云混合推理"成为消费级产品显学。同期 Google 发布 Gemini 3.8 Live 及 Live Extended Thinking（HN 262 分）；IEEE 发布《The Inference Hardware Revolution of 2026》指出专用推理芯片正重构硬件格局；社区热议为 M4 Mac mini 一个月写出 Linux GPU 驱动（120 分）。
- **为什么重要**：推理正在从"全都上云"走向"按隐私/成本/时延拆分到端侧"，这给本地推理工具、端侧模型优化、隐私优先型 AI 应用创造了新空间，也意味着大模型 API 中心化的叙事正在被稀释。
- **底层原因**：隐私焦虑（"25 年大规模监控够久了"770 分、OpenAI 反复重开"允许训练"开关的 HN 帖）+ token 成本 + 端侧芯片算力跃升。
- **数据支撑**：Gemini 3.8 Live 262 分；Inference Hardware Revolution 98 分；Perplexity Hybrid Compute 为 PH 今日榜首。
- **创业机会方向**：隐私优先/本地优先的 AI 应用（会议纪要、个人上下文、敏感数据处理）；端云路由决策层（哪些任务走本地小模型、哪些走云端大模型）。
- **谁已经在做了**：Perplexity Hybrid Compute、Apple(本地 Apple Intelligence)、Product Hunt 今日 Epilude Notetaker（100% 本地会议纪要）、Resurf（个人上下文 App）。
- **来源**：Product Hunt、Hacker News、IEEE。

---

## 二、用户痛点（7 条）

### 1. 员工离职后仍能访问一堆系统，IT 手动吊销账号要花半天
- **典型用户画像**：中小公司 IT 管理员/运维（M365、Google Workspace 环境）
- **具体场景**：员工离职后一个月才发现其仍能访问 SharePoint、Teams 和 3 个第三方 SaaS；无自动化一键吊销所有权限的工具，逐账号排查耗时半天。
- **为什么现有方案不行**：M365/Google Workspace 原生能力覆盖不全，第三方 SaaS 权限割裂，缺统一 offboarding 编排。
- **情绪强度**：高（"必须今天解决"的安全紧迫感 + 数据泄露风险）
- **付费意愿信号**：安全类工具享溢价定价，做错 offboarding 的代价是数据泄露，采购意愿强；r/office365 高频投诉。
- **来源**：Reddit r/office365（经 BigIdeasDB 挖掘）

### 2. 护士/NP（执业护士）被 EHR 的医生工作流拖垮，文档与预授权占满时间
- **典型用户画像**：执业护士（Nurse Practitioner）、中基层医疗提供者
- **具体场景**：花在文档记录和预授权（prior auth）上的时间比看病人还多；现有 EHR 完全按医生工作流设计，NP 流程无处安放，只能靠手工绕过。
- **为什么现有方案不行**：主流 EHR（Epic 等）面向医生，NP 的文档模板、预授权追踪、随访序列被忽略。
- **情绪强度**：高（"被行政任务淹没"）
- **付费意愿信号**：BigIdeasDB 显示医疗健康初创平均 MRR $1,449；NP 面板持续扩大，垂直工具稀缺。
- **来源**：Reddit r/NursePractitioner（经 BigIdeasDB 挖掘）

### 3. 租客被房东扣押金、不知道权利、来回扯皮邮件几周
- **典型用户画像**：租客/房东、物业管理公司
- **具体场景**：房东不退押金，租客不知道本地法律权利，靠邮件拉锯数周无果；争议解决流程完全碎片化。
- **为什么现有方案不行**：无按司法辖区自动查权利、模板信函、证据收集、时间线追踪的一站式工具。
- **情绪强度**：高（"必须有人管管这个"）
- **付费意愿信号**：法律科技是增长最快的 SaaS 品类之一；平台模式可同时做 C 端租客与 B 端物业公司。
- **来源**：Reddit r/LegalAdviceUK（经 BigIdeasDB 挖掘）

### 4. M365 环境 500 个账号里 80 个僵尸账号白占许可、孤儿邮箱与过期权限无人清理
- **典型用户画像**：IT 管理员、M365 租户管理员
- **具体场景**：500 用户发现 80 个不活跃账号仍占用 license；没有工具能审计谁在用、哪些共享邮箱已孤儿化、哪些权限已过期。
- **为什么现有方案不行**：M365 原生报表碎片化，无跨账号/权限的清理自动化。
- **情绪强度**：中高（持续的成本浪费 + 合规风险）
- **付费意愿信号**：直接对应可量化的 license 成本节省，ROI 清晰。
- **来源**：Reddit r/office365（经 BigIdeasDB 挖掘）

### 5. 创业者在 G2/Capterra 上分不清真假：G2 收购 Capterra 后四个评价平台归一家
- **典型用户画像**：B2B 软件选型者、POS/餐饮软件买家
- **具体场景**：2026 年 1 月 G2 宣布收购 Capterra、Software Advice、GetApp，原本"交叉验证"的四个独立评价源变成同一家；供应商年付 $3,000–$95,000 买排名，默认排序是"Sponsored"，激励性好评（Capterra 送 $25 礼品卡、G2 最高 $100）扭曲样本，负面评价被"非对称审核"卡住。
- **为什么现有方案不行**：评价平台商业模式决定"付钱者是供应商而非买家"，可信度结构性受损。
- **情绪强度**：中高（选型决策被污染）
- **付费意愿信号**：衍生出"反激励评价"的可验证调研需求（对公条款、处理方、集成清单、续费上限）。
- **来源**：Katalystos《How to read POS reviews》、G2/Capterra 平台

### 6. 传统搜索流量持续流失，企业/内容网站"被 AI 引用"成为唯一新入口，但无人能监测
- **典型用户画像**：市场负责人、SEO/内容团队、汽车/旅游垂媒
- **具体场景**：传统搜索人均使用次数/时长同比下降，品牌是否被 ChatGPT/豆包/千问推荐完全不可见；AI 引用信源最高 90% 会漂移。
- **为什么现有方案不行**：SEO 工具优化的是链接排名，无法测量"AI 概率性回答里品牌的心智份额"。
- **情绪强度**：高（营收命脉被重构）
- **付费意愿信号**：GEO 品类资本涌入 $255M+，Peec AI 月增 300+ 客户，明确付费。
- **来源**：Evertune/Higashi GEO 报告、QuestMobile、Product Hunt

### 7. 企业 AI 支出失控：token 账单随用户量暴涨，但没人知道哪个功能在烧钱
- **典型用户画像**：CTO、平台工程师、财务/FinOps 负责人
- **具体场景**：demo 阶段 AI 功能"不贵"，上生产后每个用户都触发推理，账单四位数变意外；没有 token 上限、没有按团队/功能归因、模型全用最贵档。
- **为什么现有方案不行**：云成本工具只盯云账单，LLM 工具只盯 token 账单，少有一体视图；Agent 工作流更难归因。
- **情绪强度**：高（SAP 都因此冻结招聘）
- **付费意愿信号**：42% 组织把 AI 成本优化列为 2026 首要支出优先；FinOps 工具按消费额 0.25%–1% 或"省下的钱分成"收费，说明需求刚性。
- **来源**：SAP News、Thinklytics、Amnic/Helicone 等工具生态

---

## 三、创意点子（6 条）

### 1. Agent 成本哨兵（AgentCost Sentinel）
- **触发点**：SAP 冻结招聘 + 42% 组织把 AI 成本列首要优先 + Agent 工作流最难归因
- **目标用户**：用 AI Agent 上生产的创业公司/中小团队（无专职 FinOps）
- **冷启动策略**：开源一个"一行代码接入"的 LLM/Agent token 归因库，挂到 HN Show HN + Reddit r/SaaS；免费 Hobby 档（1 万请求/月）换取口碑
- **差异化**：聚焦"按 feature/customer/agent 归因"而非纯账单监控，补齐 Amnic/Helicone 之间的空白
- **风险**：巨头（CloudZero）下沉、Helicone 开源免费；需快速跑出"归因→省钱"的闭环案例

### 2. 离职员工一键吊销编排（OffboardOrchestrator）
- **触发点**：r/office365 高频投诉 + 安全类工具溢价
- **目标用户**：50–500 人公司的 IT/运维
- **冷启动策略**：先做 M365+Google Workspace 双目录，接 Top 20 SaaS，发 r/office365、r/sysadmin 干货帖，冷 DM 留下差评的人
- **差异化**：一键吊销所有权限 + 文件归属转移 + 合规审计日志一条龙，而非单点
- **风险**：SaaS 集成维护成本高；IT 采购周期长

### 3. AI 引用监测 lite（GEO for SMB）
- **触发点**：GEO 品类 $255M 涌入但高端工具 $500+/月起，中小企业被忽略
- **目标用户**：中小企业、本地服务、独立品牌
- **冷启动策略**：$29/月切入（对标 Otterly），主打"你的品牌在豆包/千问/ChatGPT 里是否被推荐"日报
- **差异化**：专注中文+出海双市场、轻量、无企业级复杂度
- **风险**：巨头收购（XFunnel 已被 HubSpot 收购）挤压；数据采样统计显著性弱

### 4. MCP 网关/Agent 防火墙（Agent Firewall）
- **触发点**：Baseten 25 分钟被拿管理权 + 84% 注入攻击成功 + GitHub 255 个 mcp-security 仓库
- **目标用户**：已把 Agent 接进生产代码库/系统的团队
- **冷启动策略**：开源网关，扫描 Agent egress 防外泄/SSRF/提示注入，产出"可验证的 mediator 签名收据"；挂 GitHub topic + HN
- **差异化**：敏感操作强制人工审批 + 输出凭据脱敏，而非事后检测
- **风险**：大厂（Microsoft AGT、Cisco AI Defense）进场；安全合规门槛高

### 5. 端云混合推理调度层（Local-First Router）
- **触发点**：Perplexity Hybrid Compute 榜首 + 隐私焦虑 + token 成本
- **目标用户**：处理敏感数据（合同、客户信息、会议纪要）的个人/小团队
- **冷启动策略**：做一个开源路由库，自动判断"本地小模型能做就本地、复杂任务才上云"
- **差异化**：把"隐私 + 成本"两个诉求合并成一条决策规则，而非纯技术炫技
- **风险**：模型能力差距导致体验降级；苹果/大厂原生支持挤压

### 6. 反激励评价的软件选型调研服务
- **触发点**：G2 收购 Capterra 后四平台归一家、评价污染
- **目标用户**：B2B 软件选型团队（尤其 POS、垂直行业软件）
- **冷启动策略**：先做 POS 一个品类的"可验证事实对比"（处理方、终止费公式、集成清单、续费上限），内容营销获客
- **差异化**：基于公开定价、文档、备案事实而非"情绪评价"
- **风险**：市场规模窄、内容生产重、商业化难规模化

---

## 四、潜在创业方向（3 个）

### 方向 1：AI Token/Agent FinOps 平台
- **市场规模**：AI 市场 2025 年约 3900 亿美元，2030 年预计 1.8 万亿美元（CAGR 36%）；2026 Q1 仅 AI 融资 2420 亿美元。AI 成本管控是 42% 组织的头号支出优先，目标客群是"已经/正在上 AI"的所有企业。
- **竞争格局**：分化明显——Amnic（token+云一体）、TrueFoundry（网关）、Helicone（开源观测）、Mavvrik（归因）、CloudZero（单位经济学）。尚无"Agent 级全栈成本治理"的绝对赢家，窗口仍在。
- **验证路径**：先做"一行代码接入的 token 归因开源库"→ 在 HN/Reddit 冷启动 → 用 3 个真实客户跑出"省 30% 以上"的案例 → 再包装成付费 SaaS。
- **商业模式**：按被监控消费额的 0.25%–1% 收费（自举友好），或"省下的钱分成"。
- **风险与护城河**：风险=巨头下沉、开源免费替代；护城河=跨模型/跨 Agent 的归因数据积累 + 企业级合规（SOC2/ISO）+ 客户工作流锁定。

### 方向 2：GEO / AI 可见性工具（面向中文与出海品牌）
- **市场规模**：ChatGPT 周活 8 亿、60% 信息检索经 AI；Gartner 预测传统搜索 2026 降 25%；GEO 纯玩家已吸金 $255M+，Adobe $1.9B 收 Semrush 验证赛道价值。
- **竞争格局**：欧美高端市场已拥挤（Profound/Evertune/Peec/AirOps/Bluefish），但"中文 AI 生态（豆包/千问/DeepSeek）+ 出海品牌"仍是无头部玩家的蓝海。
- **验证路径**：先做豆包/千问/ChatGPT 的品牌引用监测 MVP，找 3 家出海品牌/垂媒付费试用，验证"被 AI 引用=获客"的转化数据。
- **商业模式**：订阅制（$29–$500/月分层）+ 内容/优化服务。
- **风险与护城河**：风险=AI 回答概率性导致测量不稳定、巨头收购；护城河=跨模型采样数据 + 中文语料 + 品牌级统计显著性方法。

### 方向 3：AI Agent 安全网关（MCP Gateway / Agent Firewall）
- **市场规模**：随 Agent 进入生产而指数扩张；2026 年"企业多智能体元年"，YC 2026 冬季批次 41.5% 做 agent 基础设施；GitHub mcp-security 已有 255 仓库；安全类工具享溢价。
- **竞争格局**：早期碎片化——Runlayer、Lunar.dev、ToolHive 及多款开源网关；大厂（Microsoft AGT、Cisco AI Defense）刚入场，尚无标准赢家。
- **验证路径**：开源一个"Agent egress 扫描 + 敏感操作人工审批"网关，挂 GitHub/HN 造势，找 2–3 家已用 Claude Code/Cursor 进生产的团队做 PoC。
- **商业模式**：开源核心 + 企业版（RBAC、审计、合规、SLA）。
- **风险与护城河**：风险=提示注入无法根治、安全责任重；护城河=可验证审计证据链 + 跨 Agent 统一策略 + 企业合规认证。

---

## 五、中文渠道观察（3 条）

### 1. 中国 AI 原生 App 月活逼近 5 亿，豆包/千问/DeepSeek 第一梯队定型，付费订阅被验证可行
- QuestMobile 2026 半年报：截至 2026 年 5/6 月，AI 原生 App MAU 4.99 亿（同比 +85.4%），月人均使用 92.7 次（同比 +58.3%）、月人均时长 183 分钟。豆包 3.82 亿、千问 1.67 亿（同比 +5792.9%）、DeepSeek 1.29 亿。豆包 6 月 24 日上线付费专业版，次日 App 达历史峰值 1.78 亿，验证"普惠+增值"订阅模式不伤基本盘。
- **机会信号**：C 端 AI 商业化路径（订阅+电商）确立，AI+办公成年度红利场景。

### 2. "被 AI 引用"重塑中国内容分发：汽车垂媒靠 AI 触达逆势翻盘
- QuestMobile 显示传统搜索人均使用次数/时长同比 -19.1%/-13.5%；但汽车之家的内容经 TOP3 AI 原生 App 结构化调用，间接触达 1497 万（相当于其 App 自有流量 24.9%）；有驾、太平洋汽车的 AI 触达分别相当于自有流量的 3.8 倍和 113.8 倍；携程内容撬动 2850 万 AI 触达。头部互联网企业把核心产品"Skill 化"（阿里拆淘宝/高德/支付宝、腾讯拆微信/企微/文档）。
- **机会信号**：GEO 在国内是刚起步的蓝海，垂媒/品牌急需"AI 引用监测与优化"工具。

### 3. 办公 Agent 商业化提速：腾讯 WorkBuddy 与阿里 JVS Claw 三个月活跃用户 +115.3% / +164.4%
- QuestMobile：办公交付型 Agent 处于"技术验证→早期商业化"过渡，深度生态绑定派（WorkBuddy）、私有生态托管派、生态独立派三派分立。AI 应用已成为"新晋广告主"，千问（35.9%）+元宝（32.8%）硬广合计占 AI 应用投放 68%，说明大厂仍在重金抢用户心智。
- **机会信号**：Agent 技能层（MCP/Skill 开发、Agent 安全、跨系统业务流编排）是给大厂"卖铲子"的机会；ToB 交付 Agent 工具链存在窗口。

---

## 六、采集元数据

| 渠道 | 采集状态 | 关键收获 |
|------|---------|---------|
| Hacker News | ✅ 成功 | TOP30 标题与分数（含 Baseten 安全、Gemini 3.8、推理硬件革命、监控隐私等） |
| Product Hunt | ✅ 成功 | 今日榜首 Perplexity Hybrid Compute、SWE-2、Visiby 等 |
| Reddit | ✅ 成功 | r/SaaS $9k/月复盘、r/SomebodyMakeThis 点子、BigIdeasDB 12 痛点 |
| Exploding Topics | ✅ 成功 | Remineralizing gum +5100%、GLP-1 补充剂 +1150%、Lash Clusters 等 |
| G2/Capterra | ✅ 成功 | G2 收购 Capterra 垄断、激励性评价污染 |
| Killed by Google | ✅ 成功 | Tables（Airtable 竞品）3 个月后关停等 |
| ideaSearch/痛点 | ✅ 成功 | 找点方法论 + 多源痛点交叉 |
| 中文互联网 | ✅ 成功 | QuestMobile 半年报、AI 原生 App 4.99 亿等 |
| 补充搜索 | ✅ 成功 | GEO 市场、AI 成本 FinOps、Agent 安全 |

> 采集状态：全部渠道采集成功。数据以 WebSearch 公开检索结果为准，未做付费/内部数据核验。
