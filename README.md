# aicoder2048 · 语音目录

> **给 AI 助手（Grok 等）的说明**：用户通常在开车时用语音跟你交流，会用「编号」或「中文昵称」指代下面的 repo、应用和文件，比如「1 号第 3 课」「2 号象棋的白皮书」「五子棋第 2 篇」。
> 请直接用表里的 **raw 链接** 读取内容，不要再让用户拼写 repo 名或目录路径。
> 语音识别可能把英文名听错：例如「Teardown / 提了顿」指的是 **TillDone**，「py / 派」指的是 **Pi**。
> 本页的纯文本版：https://raw.githubusercontent.com/aicoder2048/aicoder2048/main/README.md

## Repo 总目录

| 编号 | 中文昵称 | Repo | 简介 |
|---|---|---|---|
| 1 号 | 超级智能体课 | [learn-deepseek-super-agent](https://github.com/aicoder2048/learn-deepseek-super-agent) | 精读 DeepSeek《Super-agent 设计探索》的中文互动课，共 9 课 |
| 2 号 | Pi 应用集 | [pi-vs-claude-code](https://github.com/aicoder2048/pi-vs-claude-code) | 基于 Pi Agent Harness 的几个应用：TillDone、中国象棋、五子棋 |

---

## 1 号 · 超级智能体课（learn-deepseek-super-agent）

| 课 | 标题 | raw 链接 |
|---|---|---|
| 目录 | Super-agent 设计课总目录 | https://raw.githubusercontent.com/aicoder2048/learn-deepseek-super-agent/main/lessons/index.html |
| 第 1 课 | 为什么需要 Super-agent | https://raw.githubusercontent.com/aicoder2048/learn-deepseek-super-agent/main/lessons/SA01-why-super-agent.html |
| 第 2 课 | 双层架构 | https://raw.githubusercontent.com/aicoder2048/learn-deepseek-super-agent/main/lessons/SA02-two-layer.html |
| 第 3 课 | 事件过滤与路由 | https://raw.githubusercontent.com/aicoder2048/learn-deepseek-super-agent/main/lessons/SA03-event-filter-route.html |
| 第 4 课 | 上下文组织与提前行动 | https://raw.githubusercontent.com/aicoder2048/learn-deepseek-super-agent/main/lessons/SA04-context-speculation.html |
| 第 5 课 | 面向人的交互 | https://raw.githubusercontent.com/aicoder2048/learn-deepseek-super-agent/main/lessons/SA05-human-interaction.html |
| 第 6 课 | 存算分离与 Watchdog | https://raw.githubusercontent.com/aicoder2048/learn-deepseek-super-agent/main/lessons/SA06-separation-watchdog.html |
| 第 7 课 | 读懂实验：消融与批处理 | https://raw.githubusercontent.com/aicoder2048/learn-deepseek-super-agent/main/lessons/SA07-experiments.html |
| 第 8 课 | 开源原型 dsh-superagent 拆解 | https://raw.githubusercontent.com/aicoder2048/learn-deepseek-super-agent/main/lessons/SA08-prototype.html |
| 第 9 课 | 开放问题与全课总结 | https://raw.githubusercontent.com/aicoder2048/learn-deepseek-super-agent/main/lessons/SA09-open-problems.html |
| 术语表 | 全课术语表 | https://raw.githubusercontent.com/aicoder2048/learn-deepseek-super-agent/main/lessons/glossary.html |

---

## 2 号 · Pi 应用集（pi-vs-claude-code）

应用都在 `apps/` 目录下，每个应用的文档在它自己的 `docs/` 目录里。

| 应用编号 | 中文昵称 | 应用目录 |
|---|---|---|
| 2-1 | 边牧 · TillDone（也可能被听成 Teardown） | apps/tilldone |
| 2-2 | 楚河 · 中国象棋 | apps/chinese-chess |
| 2-3 | 弈境 · 五子棋（Five LLM） | apps/five-llm |

### 2-1 · 边牧 TillDone 的文档

| 篇 | 标题 | raw 链接 |
|---|---|---|
| 白皮书 | 边牧 · TillDone Desk 技术白皮书：两套四层结构、RPC 驱动的双循环、任务门禁 | https://raw.githubusercontent.com/aicoder2048/pi-vs-claude-code/main/apps/tilldone/docs/tilldone-desk-whitepaper.md |

### 2-2 · 楚河 中国象棋的文档

| 篇 | 标题 | raw 链接 |
|---|---|---|
| 白皮书 | 楚河 · Chinese Chess LLM 技术白皮书：四层 Agent Harness、双循环接入点、Pi 原生技能组与上下文工程 | https://raw.githubusercontent.com/aicoder2048/pi-vs-claude-code/main/apps/chinese-chess/docs/chinese-chess-whitepaper.md |
| 白皮书简明版 | 同一份白皮书的 ASD-STE100 简明写法 | https://raw.githubusercontent.com/aicoder2048/pi-vs-claude-code/main/apps/chinese-chess/docs/ASD-STE100/chinese-chess-whitepaper-ste.md |
| 第 1 篇 | 原生 Skill 与内置工具（v3） | https://raw.githubusercontent.com/aicoder2048/pi-vs-claude-code/main/apps/chinese-chess/docs/native-skills.md |
| 第 2 篇 | L3 技能组重构实施与验收 | https://raw.githubusercontent.com/aicoder2048/pi-vs-claude-code/main/apps/chinese-chess/docs/l3-skills-refactor.md |
| 第 3 篇 | 调用证据：判断重读、重算和计划推进 | https://raw.githubusercontent.com/aicoder2048/pi-vs-claude-code/main/apps/chinese-chess/docs/call-audit.md |
| 第 4 篇 | 回合耗时诊断（不催促模型） | https://raw.githubusercontent.com/aicoder2048/pi-vs-claude-code/main/apps/chinese-chess/docs/turn-latency.md |
| 第 5 篇 | 实战复盘：调炮困车与机器认输（2026-10-31） | https://raw.githubusercontent.com/aicoder2048/pi-vs-claude-code/main/apps/chinese-chess/docs/2026-10-31-cannon-trap-review.md |
| 第 6 篇 | 第 33 手后黑方耗尽棋钟：请求预算耗尽（2026-10-31） | https://raw.githubusercontent.com/aicoder2048/pi-vs-claude-code/main/apps/chinese-chess/docs/2026-10-31-request-budget-review.md |

### 2-3 · 弈境 五子棋（Five LLM）的文档

| 篇 | 标题 | raw 链接 |
|---|---|---|
| 白皮书 | 弈境 · Five LLM 技术白皮书：真由 LLM 落子的五子棋应用的四层 Harness、双循环接入与上下文工程 | https://raw.githubusercontent.com/aicoder2048/pi-vs-claude-code/main/apps/five-llm/docs/five-llm-whitepaper.md |
| 第 1 篇 | L3 知识与决策信号重构 | https://raw.githubusercontent.com/aicoder2048/pi-vs-claude-code/main/apps/five-llm/docs/l3-knowledge-refactor.md |
| 第 2 篇 | L3 v2：候选的连续先手反证与提交前反馈 | https://raw.githubusercontent.com/aicoder2048/pi-vs-claude-code/main/apps/five-llm/docs/forcing-review.md |
| 第 3 篇 | L3 v3：己方强杀发现与提交前漏胜反馈 | https://raw.githubusercontent.com/aicoder2048/pi-vs-claude-code/main/apps/five-llm/docs/own-forcing-win.md |
