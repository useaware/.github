# useaware

Building Git-native, Markdown-native tools for personal knowledge management and AI agent collaboration.

构建面向个人知识管理与 AI Agent 协作的 Git-native、Markdown-native 工具。

## About

**Aware CLI** is a command-line knowledge operating system for personal knowledge management and AI agent collaboration.

Aware CLI 是一个面向个人知识管理与 AI Agent 协作的命令行知识操作系统。

It is designed around a few simple ideas:

- **Git-native**: knowledge should be versionable, reviewable, and easy to sync
- **Markdown-native**: knowledge should live in open, portable text files
- **Local-first**: your workflow should work on your machine first
- **Agent-ready**: knowledge should be understandable and reusable by AI agents
- **Extensible**: connectors, shared libraries, hooks, and agent runtimes should compose cleanly

它围绕几个简单原则构建：

- **Git-native**：知识应该可版本化、可审阅、可同步
- **Markdown-native**：知识应该存放在开放、可迁移的文本文件中
- **Local-first**：工作流应首先在本地稳定运行
- **Agent-ready**：知识应可被 AI Agent 理解与复用
- **Extensible**：Connector、Shared 知识库、Hooks 与 Agent Runtime 应能自然扩展

## What we are building

We are building tools for a new kind of knowledge workflow:

- capture ideas quickly
- write long-form documents in plain text
- import content from the web and documents
- organize knowledge with Git and file structure
- connect external systems through connectors
- reuse shared knowledge libraries
- automate workflows with hooks
- collaborate with AI agents through structured knowledge and runtime integrations

我们正在构建一套新的知识工作流工具：

- 快速记录想法
- 用纯文本完成正式写作
- 导入网页与文档内容
- 用 Git 和文件结构组织知识
- 通过 Connector 连接外部系统
- 复用 Shared 知识库
- 用 Hooks 自动化工作流
- 通过结构化知识与运行时集成与 AI Agent 协作

## Core ideas behind Aware CLI

Aware CLI is built around these core building blocks:

### 1. Personal knowledge workflows
A simple command-line workflow centered on:

- `aware note` for quick capture
- `aware write` for long-form writing
- `aware daily` for daily notes
- `aware import` for external content

### 2. Agent Runtime integrations
Aware CLI delegates advanced content processing to external **Agent Runtimes**, such as:

- Claude Code
- Codex
- Copilot
- OpenCode

### 3. Skills
Skills package reusable capabilities for agent execution, such as:

- HTML extraction
- PDF extraction
- summarization
- review
- context assembly

### 4. Connectors
Connectors link Aware with external systems like:

- Obsidian
- GitHub
- local files
- RSS
- more systems in the future

### 5. Shared knowledge libraries
Shared knowledge libraries make it possible to bring external knowledge repositories into your workspace through Git submodules.

### 6. Hooks
Hooks enable event-driven automation, such as:

- auto commit and push after editing
- auto summary after import
- auto map refresh after knowledge updates

## Why this matters

We believe knowledge tools should be:

- open instead of locked-in
- durable instead of disposable
- inspectable instead of opaque
- agent-compatible instead of agent-hostile
- composable instead of monolithic

我们相信知识工具应该是：

- 开放的，而不是封闭锁定的
- 可持续沉淀的，而不是一次性的
- 可检查的，而不是黑盒的
- 对 Agent 友好的，而不是排斥 Agent 的
- 可组合的，而不是单体封闭的

## Projects

Current and planned projects in this organization may include:

- **Aware CLI** — the core command-line knowledge operating system
- runtime integrations
- official skills
- connectors
- shared library conventions
- automation hooks
- documentation and examples

## Status

Aware is currently in an early design and building phase.

We are actively shaping:

- product scope
- architecture
- file protocols
- command design
- runtime abstractions
- connector and hooks systems

Aware 目前处于早期设计与构建阶段，正在持续完善：

- 产品范围
- 系统架构
- 文件协议
- 命令设计
- Agent Runtime 抽象
- Connector 与 Hooks 系统

## Philosophy

Use simple tools.  
Keep knowledge in files.  
Version everything important.  
Design for humans first, then for agents.  
Make the system extensible without making it opaque.

## Get involved

If you are interested in:

- personal knowledge management
- Git-native workflows
- Markdown-based systems
- AI agent collaboration
- local-first tools
- developer-oriented knowledge infrastructure

you are in the right place.

## Follow the journey

This organization will host the repositories, documentation, and experiments around Aware.

Stay tuned.
