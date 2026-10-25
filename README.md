# Weekly AI Trending —— 每周 AI 趋势项目 Top 10

> **数据口径：** 本清单基于 GitHub Trending 的 **本周（weekly）** 页面于 **2026-10-25** 抓取到的项目，并筛选 AI、AI Agent、LLM、MCP 或与 AI 开发流程密切相关的条目。GitHub Trending 并没有"AI 分类的官方全站前十"接口；下面的编号仅为本次筛选后的展示顺序，并非全站精确排名。
>
> **视频说明：** 只有能够直接确认与项目对应的官方或热门视频才应当列入；本次抓取未逐项验证到可靠的直接视频地址，因此不附加 YouTube 链接，以避免误导。

---

## 本周排名快照

| 排名 | 项目 | Star 数 |
| --- | --- | ---: |
| 1 | [mattpocock/skills](https://github.com/mattpocock/skills) | 302,841 |
| 2 | [affaan-m/ECC](https://github.com/affaan-m/ECC) | 288,402 |
| 3 | [anthropics/claude-code](https://github.com/anthropics/claude-code) | 153,337 |
| 4 | [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | 110,341 |
| 5 | [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem) | 102,951 |
| 6 | [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) | 71,789 |
| 7 | [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight) | 53,562 |
| 8 | [Tencent/WeKnora](https://github.com/Tencent/WeKnora) | 35,354 |
| 9 | [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad) | 23,020 |
| 10 | [mvschwarz/openrig](https://github.com/mvschwarz/openrig) | 8,175 |

---

## 项目详情

### 1. Skills for Real Engineers

**项目链接：** [mattpocock/skills](https://github.com/mattpocock/skills)

Skills for Real Engineers 是由知名开发者 Matt Pocock 维护的 AI 编程技能库。项目收录了经过实践验证的技能定义，涵盖需求澄清、架构设计、代码审查、测试编写、文档生成等软件开发全流程。这些技能可直接导入 Claude Code、Cursor、Codex 等 AI 编码助手，帮助开发者将最佳工程实践转化为可复用的 Agent 能力，减少重复指令输入，提升协作效率。

---

### 2. ECC

**项目链接：** [affaan-m/ECC](https://github.com/affaan-m/ECC)

ECC 是一个面向 AI 编程 Agent 的性能优化与工程工作流系统。它将技能、记忆、安全约束和"先研究、后实现"的开发方法组织起来，可用于 Claude Code、Codex、OpenCode、Cursor 等不同智能体环境，帮助团队把复杂开发任务拆解为更可重复、可审查的流程。该项目支持多种编码智能体，目标是提高 Agent 在长期开发任务中的稳定性与效率。

---

### 3. Claude Code

**项目链接：** [anthropics/claude-code](https://github.com/anthropics/claude-code)

Claude Code 是 Anthropic 推出的终端型编码助手。它可理解代码库结构，并通过自然语言指令执行代码修改、调试、解释和 Git 工作流操作。项目适合希望在命令行中快速交互、减少重复操作的开发者，可作为日常编程的辅助工具。支持多种语言和框架，能够与现有开发环境无缝集成。

---

### 4. Claude Memory (claude-mem)

**项目链接：** [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)

Claude Memory 是一个为 AI Agent 提供持久化上下文的能力。它会在会话期间捕获 Agent 的所有操作，利用 AI 压缩并存储关键信息，在后续会话中注入相关上下文。该工具解决了 AI 编程助手无法跨会话记忆的问题，适合需要长期项目跟踪、多轮迭代的开发场景，让 Agent 真正具备"记住"项目上下文的能力。

---

### 5. Agent Skills

**项目链接：** [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)

Agent Skills 是 Google Chrome 工程师 addyosmani 开源的 AI 编程技能库。内容覆盖 Code Review、需求澄清、测试编写、Git 提交等多个阶段，为 Codex、Claude Code 等智能体提供可复用的工程能力模块，帮助团队建立更规范的开发流程。项目强调生产级质量标准和团队协作实践。

---

### 6. Hyperframes

**项目链接：** [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes)

Hyperframes 是一个面向 Agent 的视频渲染框架，支持通过编写 HTML 直接生成视频。项目结合网页技术、动画与视频处理能力，为 AI Agent 自动生成演示视频、动态内容或可编程视觉素材提供了基础，适合需要批量生成视频内容的场景。采用 Puppeteer 渲染，兼容主流浏览器特性。

---

### 7. Hindsight

**项目链接：** [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight)

Hindsight 是一个专注于"可学习的 Agent 记忆"的项目，关注如何让 AI 智能体跨任务保存经验、检索历史上下文并从中学习。项目适合研究长期记忆、上下文恢复和连续任务执行的开发者，可为多轮对话、复杂工作流提供记忆能力支持。采用向量数据库实现高效检索。

---

### 8. WeKnora

**项目链接：** [Tencent/WeKnora](https://github.com/Tencent/WeKnora)

WeKnora 是腾讯开源的 LLM 知识平台，可将原始文档转化为可查询的 RAG、具备推理能力的 Agent 和可维护的 Wiki。它覆盖文档解析、检索、重排序、问答等知识服务链路，适合构建企业内部知识问答、文档检索和智能助手应用。支持多格式文档处理和自动化知识库维护。

---

### 9. Text to CAD

**项目链接：** [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad)

Text to CAD 为 AI Agent 赋予了 CAD 建模能力。用户通过自然语言描述即可生成机械设计图纸和 3D 模型，支持 STEP、STL 等标准格式。项目适合需要 AI 辅助工程设计、快速原型生成或参数化建模的机械工程师和开发者，填补了语言模型与工业设计工具之间的鸿沟。

---

### 10. Openrig

**项目链接：** [mvschwarz/openrig](https://github.com/mvschwarz/openrig)

Openrig 是一个 Agent 编排框架，支持用 Claude Code、Codex 和 Pi 构建持久化的多 Agent 协作网络。它为每个 Agent 分配角色、共享上下文，并支持任务分解与结果整合。项目适合需要复杂工作流自动化、分布式任务处理和多角色协作的工程场景，提供了灵活的可扩展架构。

---

### 说明

- 内容依据 2026-10-25 的 GitHub Trending 本周页面及各仓库公开描述整理；趋势榜单与仓库内容会快速变化。
- 每项均提供 20–500 字中文概述、项目 GitHub 链接及 Star 数。
- 未经可靠逐项核验的 YouTube 链接已省略；欢迎通过 Issue 或 Pull Request 补充经验证的官方演示或热门视频。

---

<div align="center">

Made with ❤️ by **de-nova** | Powered by GitHub & AI

</div>
