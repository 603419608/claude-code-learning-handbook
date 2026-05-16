# Claude Code Learning Handbook / Claude Code 学习手册

> A practical Claude Code learning handbook for developers who want to move from basic usage to advanced AI coding workflows.  
> 一本面向 Claude Code 新手和 AI Agent 初学者的系统学习手册，覆盖从入门使用到高级工程化实践。

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)
[![Chinese PDF](https://img.shields.io/badge/PDF-中文学习手册-red)](./books/Claude%20Code%20%E5%AD%A6%E4%B9%A0%E6%89%8B%E5%86%8C.pdf)
[![English PDF](https://img.shields.io/badge/PDF-English%20Handbook-green)](./books/Claude%20Code%20Learning%20Handbook.pdf)

## Download / 下载

- [Claude Code 学习手册.pdf](./books/Claude%20Code%20%E5%AD%A6%E4%B9%A0%E6%89%8B%E5%86%8C.pdf) - 中文正式版，适合手机和电脑阅读
- [Claude Code Learning Handbook.pdf](./books/Claude%20Code%20Learning%20Handbook.pdf)

> This repository publishes the PDF editions only. Source drafts, intermediate task files, and generation scripts are not included.  
> 本仓库只发布 PDF 成书版本，不包含生成过程中的源稿、中间任务文件和脚本。

## About This Book / 关于本书

This handbook is designed for developers who have basic programming experience and want to learn Claude Code systematically. It starts with the basic mental model of AI coding agents, then moves through everyday development workflows, Markdown-based memory, prompt engineering, token management, Skills, SubAgents, MCP, Hooks, Plugins, automation, GitHub PR/CI workflows, security, and full project case studies.

本书面向已经具备一定编程基础、刚开始系统学习 Claude Code 和 AI Agent 的读者。内容从 AI 编码 Agent 的基本心智模型开始，逐步覆盖日常开发工作流、Markdown 记忆系统、提示词工程、Token 成本控制、Skills、SubAgents、MCP、Hooks、Plugins、自动化、GitHub PR/CI、安全权限，以及完整项目实战案例。

## Who Is It For? / 适合读者

- Developers who have installed Claude Code but only use it for simple Q&A or bug analysis.
- AI Agent beginners who want a structured learning path.
- Python, C#, or C++ developers who want practical Claude Code examples.
- Teams that want to turn Claude Code usage into repeatable engineering workflows.

- 已经安装 Claude Code，但只会做简单问答或 Bug 分析的开发者。
- 想系统学习 AI Agent 和 Claude Code 的初学者。
- 希望在 Python、C#、C++ 项目中实践 Claude Code 的开发者。
- 希望把 Claude Code 使用方式沉淀成团队工程流程的团队。

## What You Will Learn / 你将学到什么

- How Claude Code differs from a normal chatbot.
- How to use Claude Code for code reading, bug fixing, refactoring, testing, and documentation.
- How to manage `CLAUDE.md`, Markdown rules, memory, and local knowledge bases.
- How to write better prompts for Claude Code and advanced models such as Opus.
- How to reduce token usage and keep long tasks manageable.
- How to use Skills, Commands, SubAgents, Hooks, MCP, Plugins, and automation.
- How to integrate Claude Code into GitHub PR and CI workflows.
- How to design safer permission, sandbox, and security practices.

- Claude Code 和普通聊天机器人的区别。
- 如何用 Claude Code 做代码理解、Bug 修复、重构、测试和文档。
- 如何管理 `CLAUDE.md`、Markdown 规则、记忆系统和本地知识库。
- 如何为 Claude Code 和 Opus 等高级模型编写更稳定的提示词。
- 如何节省 Token，并管理长任务上下文。
- 如何使用 Skills、Commands、SubAgents、Hooks、MCP、Plugins 和自动化。
- 如何把 Claude Code 接入 GitHub PR 和 CI 工作流。
- 如何建立更安全的权限、沙箱和安全实践。

## Full Table of Contents / 完整目录

### Part 1: Getting Oriented / 第一篇：入门地图

1. Why Claude Code Is More Than a Chatbot / 为什么 Claude Code 不只是聊天机器人
2. Environment, Account, Models, and Your First Task / 环境、账号、模型和第一个任务
3. Files, Edits, Shell Commands, and Tools / Claude Code 的文件读写和工具系统
4. Preparing a Learning Project / 学习用项目准备

### Part 2: Everyday Development Workflows / 第二篇：日常开发工作流

5. Code Understanding and Project Maps / 代码理解与项目地图
6. Bug Localization and Fixing / Bug 定位与修复
7. Refactoring, Testing, and Documentation / 重构、测试和文档
8. Git Workflow and Commit Quality / Git 工作流与提交质量
9. From One-off Questions to Reusable Workflows / 从一次性问答到可复用工作流

### Part 3: Markdown, Memory, and Knowledge Bases / 第三篇：Markdown、记忆和本地知识库

10. Markdown as an Agent Control Layer / Markdown 不是文档格式，而是 Agent 控制层
11. The `CLAUDE.md` Memory System / `CLAUDE.md` 记忆系统
12. Project Rules, `AGENTS.md`, and Rule Folders / 项目规则、`AGENTS.md` 和规则文件夹
13. Local Knowledge Bases / 本地知识库
14. Memory System Anti-patterns / 记忆系统的反模式

### Part 4: Prompting and Model Control / 第四篇：提示词、Opus 和模型驾驭

15. Claude Code Prompting Fundamentals / Claude Code 提示词基本功
16. Plan Mode and Exploration Mode / 计划模式与探索模式
17. Taming Opus: Models, Effort, and Thinking Budget / 驯服 Opus：模型、努力级别和思考预算
18. Prompt Orchestration for Complex Engineering Tasks / 复杂工程任务的提示词编排

### Part 5: Context, Tokens, and Cost / 第五篇：上下文、Token 和成本控制

19. Context Windows and File Selection / 上下文窗口与文件选择
20. Compaction, Recovery, and Long-session Management / 压缩、恢复和长会话管理
21. Token Saving and Cost Optimization / Token 节省与成本优化

### Part 6: Extension Systems / 第六篇：扩展系统

22. Skills Fundamentals / Skills 基础
23. Custom Commands and Task-oriented Skills / 自定义命令与任务型 Skill
24. SubAgents Fundamentals / SubAgents 基础
25. Multi-Agent Collaboration / 多 Agent 协作
26. Hooks for Event-driven Automation / Hooks 事件驱动自动化
27. MCP Fundamentals and External Tool Integration / MCP 基础与外部工具连接
28. The Plugins System / Plugins 插件系统
29. Tools and Rules / Tools 与 Rules 体系
30. Combination Patterns for Skill, Agent, MCP, and Plugin / Skill、Agent、MCP、Plugin 的组合模式
31. Mini Project: Building an Extension System / 扩展系统实战小项目

### Part 7: Automation, GitHub, CI, and Programmable Agents / 第七篇：自动化、GitHub、CI 和可编程 Agent

32. Headless Mode and Command-line Automation / Headless 模式与命令行自动化
33. Agent SDK Introduction / Agent SDK 入门
34. Routines, Scheduled Tasks, and Automated Workflows / Routines、定时任务和自动化工作流
35. GitHub PR and CI Workflows / GitHub PR / CI 工作流
36. IDE, Browser, and External Tool Integration / IDE、浏览器和外部开发工具集成

### Part 8: Security, Permissions, Sandboxes, and Risk Control / 第八篇：安全、权限、沙箱和风险控制

37. Permissions and Safe Working Modes / 权限系统和安全工作模式
38. Sandboxes, Data Security, and Prompt Injection / 沙箱、数据安全和提示注入
39. Git, Safe Releases, and Rollbacks / Git、安全发布和回滚
40. Production-grade Claude Code Usage Guidelines / 生产级 Claude Code 使用规范

### Part 9: Advanced Harness Engineering / 第九篇：高级驾驭工程

41. Claude Code Internal Mechanics / Claude Code 内部工作机制导览
42. Context Engineering, Caching, and Cost Engineering / 上下文工程、缓存和成本工程
43. From Personal Capability to Team AI Coding Systems / 从个人能力到团队 AI 编码体系

### Part 10: Complete Case Studies / 第十篇：完整实战案例

44. Case Study 1: From Bug to PR in a Python Project / 实战一：个人 Python 项目从 Bug 到 PR
45. Case Study 2: Team Claude Code Toolkit / 实战二：团队 Claude Code 工具包

## Appendices / 附录

- Claude Code command quick reference / Claude Code 常用命令速查
- Directory and file quick reference / 目录与文件速查
- Markdown templates / Markdown 写作模板
- Prompt template library / 提示词模板库
- Skill templates / Skill 模板库
- SubAgent templates / SubAgent 模板库
- MCP configuration examples / MCP 配置示例
- Hooks examples / Hooks 示例
- Token and cost checklist / Token 与成本清单
- Security checklist / 安全清单
- Glossary / 术语表

## Repository Structure / 仓库结构

```text
.
├── README.md
├── LICENSE
└── books/
    ├── Claude Code 学习手册.pdf
    ├── Claude Code 学习手册-横版排版.pdf
    └── Claude Code Learning Handbook.pdf
```

## Notes / 说明

- The Chinese PDF is the primary edition.
- The English PDF is provided for readers who prefer English structure and terminology.
- The content is intended as a learning resource, not official Anthropic documentation.
- For the latest Claude Code behavior, always check the official documentation.

- 中文 PDF 是主要版本。
- 英文 PDF 方便偏好英文术语和结构的读者阅读。
- 本书是学习资源，不是 Anthropic 官方文档。
- Claude Code 功能和命令可能更新，最新行为请以官方文档为准。

## License / 许可证

This repository currently uses the [MIT License](./LICENSE).

本仓库当前使用 [MIT License](./LICENSE)。
