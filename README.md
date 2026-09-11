# 你好，我是 mowenQWQ 👋

**独立开发者。做 Windows 安全工具，也把 AI agent 一起干活踩过的坑整理成开源经验库。**

**Indie developer. I build Windows security tooling and turn hard-won AI-agent lessons into open-source skill libraries.**

---

## 中文

### 🧰 AI Agent Skill 经验库（十五件套）

全部来自真实项目实战——银狐工具开发、网站安全测试、agent 无人值守运维、同人写作、中文写作、AI 声明规范与 MC 服务器安全。每条经验都带事故现场与修复动作，不是理论清单。

| 仓库 | 一句话 |
|------|--------|
| [win-dev-pitfalls](https://github.com/mowenQWQ/win-dev-pitfalls) | Windows 开发踩坑全量主线：bat/cmd、PowerShell 5.1/7、Win32 GUI、Flutter 桌面端（41 章） |
| [bat-ps1-dev](https://github.com/mowenQWQ/bat-ps1-dev) | bat / PowerShell 脚本开发专项经验库（39 章） |
| [Web-Security-Test-Rules](https://github.com/mowenQWQ/Web-Security-Test-Rules) | 已授权网站安全测试规则库：先授权、后测试、最小影响、规范留痕 |
| [security-testing](https://github.com/mowenQWQ/security-testing) | 已授权网站的系统性渗透测试手册：漏洞发现、提权尝试、隐蔽纪律、报告生成 |
| [web-api-security-testing](https://github.com/mowenQWQ/web-api-security-testing) | Web API 安全测试轮次化流程：测试前 3 件事、测试中手段手册、测试后 5 件事闭环 |
| [site-health-diagnosis](https://github.com/mowenQWQ/site-health-diagnosis) | 网站健康分层体检法：区分 CDN/源站层故障、瞬时/持续问题，输出可转给运维的证据链 |
| [unattended-task-pitfalls](https://github.com/mowenQWQ/unattended-task-pitfalls) | 无人值守自动任务加固：操作纪律会失效，只有代码能兜底 |
| [agent-mistake-patterns](https://github.com/mowenQWQ/agent-mistake-patterns) | AI 智能体犯错模式库：翻车主力不是能力问题，是"库里有的知识没用上" |
| [grounded-summaries-skill](https://github.com/mowenQWQ/grounded-summaries-skill) | 防止 AI 在总结类任务中编造内容（源自一次真实的线上幻觉事故） |
| [fanfic-game-lore-writer](https://github.com/mowenQWQ/fanfic-game-lore-writer) | 基于游戏内文本素材的同人写作方法论：原作考据、角色反推、道具碎片化嵌入、信息差叙事 |
| [skill-open-source-publish](https://github.com/mowenQWQ/skill-open-source-publish) | 把任务成果/事故复盘做成可开源 skill 并发布双平台：脱敏、双语、建仓、推送、验证全流程 |
| [mc-server-plugin-security](https://github.com/mowenQWQ/mc-server-plugin-security) | 我的世界服务器插件安全经验库：AuthMe 0day、登录绕过、session 劫持、ForceOp、jar 静态检查与版本选型 |
| [article-writing](https://github.com/mowenQWQ/article-writing) | 中文文章/软文/长文写作经验库：读者意识、事实先行、对比论证、深度优先与发布前自查清单 |
| [ai-usage-notice](https://github.com/mowenQWQ/ai-usage-notice) | 为 AI 直接输出的成品默认添加 AI 使用说明（项目 README 开头 + 文章文末），法律依据与例外边界完整 |
| [agent-self-rollback](https://github.com/mowenQWQ/agent-self-rollback) | 为 AI agent 建立自身误操作回滚机制：三层防线（自律规则+时间戳快照+双兜底恢复）+ 可移植 rollback.ps1（snapshot/list/restore/verify） |

> 以上十五库同步开源于 [Gitee](https://gitee.com/mowenqwq)，README 均为中英双语。

### 🎮 Minecraft 模组

- **[Bountiful-Fares-Fixed](https://github.com/mowenQWQ/Bountiful-Fares-Fixed)** — Bountiful Fares 1.20.1 狼乞食 NPE 崩溃修复构建（手动构建 / Fabric，Sinytra Connector 可跑 Forge）｜ Gitee：[Bountiful-Fares-Fixed](https://gitee.com/mowenqwq/Bountiful-Fares-Fixed)
- **[Weather-Effect-](https://github.com/mowenQWQ/Weather-Effect-)** — 天气药水模组：晴天增益、雨天与雷暴触发随机正负效果（雷暴可一次叠加多个），无需合成、自动运行 ｜ Gitee：[weather-effect](https://gitee.com/mowenqwq/weather-effect)
- **[tp_permission_mod](https://github.com/mowenQWQ/tp_permission_mod)** — 传送指令权限管理：管理员一键开关全服或指定玩家的 /tp，配置按世界独立保存，单机联机通用 ｜ Gitee：[tp_permission_mod](https://gitee.com/mowenqwq/tp_permission_mod)
- **[ImmersiveOptimization-DeadlockFix](https://github.com/mowenQWQ/ImmersiveOptimization-DeadlockFix)** — Immersive Optimization 1.20.1 Forge 版 ServerHangWatchdog 死锁字节码级修复（Worker 线程改只读内存强制区块，避免与主线程抢存储锁）｜ Gitee：[ImmersiveOptimization-DeadlockFix](https://gitee.com/mowenqwq/ImmersiveOptimization-DeadlockFix)

### 🛠️ 工具

- **[SilverFox-Detector](https://github.com/mowenQWQ/SilverFox-Detector)** — 银狐木马专杀工具（银狐特攻），Go + PowerShell 双层架构，已通过 360 软件开放平台过白 ｜ Gitee：[silver-fox_-detector_fixed](https://gitee.com/mowenqwq/silver-fox_-detector_fixed)
- **[CherryStudio-Workspace-Fixer](https://github.com/mowenQWQ/CherryStudio-Workspace-Fixer)** — Cherry Studio 数据搬迁后旧 Agent 对话报错「workspace path is outside the managed workspace root」的一站式修复：三处路径残留全覆盖（.claude.json / projects 目录名 / 数据库 agent_workspace.path），预览→自动备份→修复→复查 ｜ Gitee：[CherryStudio-Workspace-Fixer](https://gitee.com/mowenqwq/CherryStudio-Workspace-Fixer)

### 🌐 个人项目

- **[mowen.vip](https://mowen.vip)** — Oreacle · 我的世界赛博算卦所（nginx + 零依赖 Node.js，源码开源）

---

## English

### 🧰 AI Agent Skill Libraries (×15)

All distilled from real projects — building the security tool itself, authorized web security testing, unattended agent operations, fanfiction and Chinese writing, AI-usage-notice compliance, and MC server plugin security. Every entry carries the incident, the wrong guesses, and the fix. Not theory checklists.

| Repo | What it does |
|------|--------------|
| [win-dev-pitfalls](https://github.com/mowenQWQ/win-dev-pitfalls) | Windows dev pitfalls, full line: bat/cmd, PowerShell 5.1/7, Win32 GUI, Flutter desktop (41 chapters) |
| [bat-ps1-dev](https://github.com/mowenQWQ/bat-ps1-dev) | Batch & PowerShell scripting vault (39 chapters) |
| [Web-Security-Test-Rules](https://github.com/mowenQWQ/Web-Security-Test-Rules) | Authorized web security testing rules: authorize first, minimal impact, documented evidence |
| [security-testing](https://github.com/mowenQWQ/security-testing) | Systematic pentest playbook for authorized targets: discovery, privilege escalation, stealth, reporting |
| [web-api-security-testing](https://github.com/mowenQWQ/web-api-security-testing) | Round-based Web API security testing: 3 pre-flight checks, technique handbook, 5-step closure |
| [site-health-diagnosis](https://github.com/mowenQWQ/site-health-diagnosis) | Layered website health diagnosis: CDN vs origin, transient vs persistent, ops-ready evidence chain |
| [unattended-task-pitfalls](https://github.com/mowenQWQ/unattended-task-pitfalls) | Hardening for unattended agent tasks: discipline fails unattended; only code has your back |
| [agent-mistake-patterns](https://github.com/mowenQWQ/agent-mistake-patterns) | AI-agent mistake patterns: failures come from unused knowledge, not missing ability |
| [grounded-summaries-skill](https://github.com/mowenQWQ/grounded-summaries-skill) | Stop AI agents from fabricating summaries (born from a real incident) |
| [fanfic-game-lore-writer](https://github.com/mowenQWQ/fanfic-game-lore-writer) | Fanfiction-writing methodology built on in-game text artifacts: canon research, character building, info-gap narration |
| [skill-open-source-publish](https://github.com/mowenQWQ/skill-open-source-publish) | Turn task outcomes & postmortems into open-source skills: desensitization, bilingual docs, dual-platform publishing |
| [mc-server-plugin-security](https://github.com/mowenQWQ/mc-server-plugin-security) | Minecraft server plugin security vault: AuthMe 0-days, login bypasses, session takeover, ForceOp, jar static checks |
| [article-writing](https://github.com/mowenQWQ/article-writing) | Chinese article-writing vault: reader-first, facts first, contrast argumentation, depth over length, pre-publish checklist |
| [ai-usage-notice](https://github.com/mowenQWQ/ai-usage-notice) | Mandate an AI usage notice on AI-produced deliverables — project README or article end, legally grounded, with exceptions |
| [agent-self-rollback](https://github.com/mowenQWQ/agent-self-rollback) | Self-rollback mechanism for AI agents: three layers (self-discipline rules + timestamped snapshots + double-buffered restore) + portable rollback.ps1 (snapshot/list/restore/verify) |

> All fifteen are mirrored on [Gitee](https://gitee.com/mowenqwq) with bilingual (Chinese-first) READMEs.

### 🎮 Minecraft Mods

- **[Bountiful-Fares-Fixed](https://github.com/mowenQWQ/Bountiful-Fares-Fixed)** — Fixed build of Bountiful Fares 1.20.1 (wolf begging NPE crash; hand-built / Fabric, Sinytra Connector for Forge) | Gitee: [mirror](https://gitee.com/mowenqwq/Bountiful-Fares-Fixed)
- **[Weather-Effect-](https://github.com/mowenQWQ/Weather-Effect-)** — Weather potion mod: sunny buffs, rain and thunderstorms trigger random positive or negative effects (thunderstorms can stack several at once); no crafting, fully automatic | Gitee: [weather-effect](https://gitee.com/mowenqwq/weather-effect)
- **[tp_permission_mod](https://github.com/mowenQWQ/tp_permission_mod)** — /tp permission manager: admins can toggle teleport for the whole server or specific players; per-world config, works in both singleplayer and servers | Gitee: [tp_permission_mod](https://gitee.com/mowenqwq/tp_permission_mod)
- **[ImmersiveOptimization-DeadlockFix](https://github.com/mowenQWQ/ImmersiveOptimization-DeadlockFix)** — Bytecode-level fix for the Immersive Optimization 1.20.1 Forge ServerHangWatchdog deadlock (worker thread now reads only the in-memory forced-chunk set, avoiding storage-lock contention with the main thread) | Gitee: [ImmersiveOptimization-DeadlockFix](https://gitee.com/mowenqwq/ImmersiveOptimization-DeadlockFix)

### 🛠️ Tools

- **[SilverFox-Detector](https://github.com/mowenQWQ/SilverFox-Detector)** — A remover for the "SilverFox" trojan family. Go + PowerShell dual-layer architecture, whitelisted on the 360 Software Open Platform | Gitee: [silver-fox_-detector_fixed](https://gitee.com/mowenqwq/silver-fox_-detector_fixed)
- **[CherryStudio-Workspace-Fixer](https://github.com/mowenQWQ/CherryStudio-Workspace-Fixer)** — One-stop fixer for "workspace path is outside the managed workspace root" on old Agent conversations after relocating Cherry Studio data: covers all three leftover locations (.claude.json / projects dir names / DB agent_workspace.path) with preview → auto backup → fix → recheck | Gitee: [CherryStudio-Workspace-Fixer](https://gitee.com/mowenqwq/CherryStudio-Workspace-Fixer)

### 🌐 Personal Project

- **[mowen.vip](https://mowen.vip)** — Oreacle, a Minecraft-themed divination site (nginx + zero-dependency Node.js, open source)

---

## 🤖 AI 使用声明 / AI Usage Disclosure

本项目在开发与维护过程中使用了 AI 辅助编码、文档整理与问题排查；核心决策、内容审核与最终发布由维护者完成。

This project was developed and maintained with AI assistance for coding, documentation, and troubleshooting; all core decisions, reviews, and final release are made by the maintainer.

<!-- profile README · synced on Gitee (mowenqwq/mowenqwq) -->
