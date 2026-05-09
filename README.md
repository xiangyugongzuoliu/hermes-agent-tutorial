<div align="center">

# 🪽 Hermes Agent 教程中文版

### 让中文开发者把 Hermes Agent 跑通从单 Agent 到自动化消息流的稳定闭环

> 💎 **不是 API 列表，而是为中文新手重写的双路径教程：理解篇负责心智模型，官方篇负责事实基准——两条路径同时跑，不替代彼此。**

[![类型](https://img.shields.io/badge/类型-Tutorial-blue?style=for-the-badge)](https://aiworkflowtutorials.com/docs/hermes)
[![章节](https://img.shields.io/badge/章节-16_篇-brightgreen?style=for-the-badge)](https://aiworkflowtutorials.com/docs/hermes)
[![语言](https://img.shields.io/badge/语言-简体中文-DC322F?style=for-the-badge)](#)
[![事实基准](https://img.shields.io/badge/事实基准-Hermes_Agent_官方仓-2D3748?style=for-the-badge)](https://aiworkflowtutorials.com/docs/hermes)
[![繁体](https://img.shields.io/badge/繁体-zh--Hant-9b59b6?style=for-the-badge)](https://aiworkflowtutorials.com/docs/hermes)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-orange?style=for-the-badge)](CONTRIBUTING.md)

</div>

---

> 🎯 **Agent 框架不缺，缺的是「能让中文开发者真的从单 Agent 起步、走到生产消息流」的版本。**
>
> 这份教程基于 Hermes Agent 官方仓库源码、配置文档和真实生产实践重写，按「中文新手 → 第一性原理 → 循序渐进」组织。
> 8 篇 **从原理到实战** 帮你建立心智模型，2 个分组的 **官方教程中文版** 覆盖入门与使用手册。
>
> 完整教程托管在翔宇工作流的中文教程站，本仓库是公开门面入口，负责发现、反馈和样章预览。

<div align="center">

[🚀 立刻开始阅读](https://aiworkflowtutorials.com/docs/hermes) · [🧠 从原理到实战](https://aiworkflowtutorials.com/docs/hermes/understanding) · [📚 官方教程中文版](https://aiworkflowtutorials.com/docs/hermes/official) · [🐛 反馈问题](https://github.com/xiangyugongzuoliu/hermes-agent-tutorial/issues)

</div>

---

## 📖 这是什么 (What)

> 💡 **核心定位**：中文开发者的 Hermes Agent 学习入口 —— 一站把单 Agent 闭环 × 工具系统 × 记忆 × 消息网关 × 自动化边界全讲透。

这是《AI 编程教程中文版》里的 Hermes Agent 主题，由 [aiworkflowtutorials.com](https://aiworkflowtutorials.com/docs/hermes) 发布完整内容。本 GitHub 仓库只放门面入口、学习路线和样章摘录。

### 📐 双路径结构

| 路径 | 适合谁 | 章节数 | 入口 |
|------|--------|:------:|------|
| 🧠 **从原理到实战** | 想理解 Hermes 为什么这样设计稳定闭环、记忆与消息网关 | **8 篇** | [开始 →](https://aiworkflowtutorials.com/docs/hermes/understanding) |
| 📚 **官方教程中文版** | 想直接查安装、配置、Provider、工具、Skills 用法 | **8 篇** | [开始 →](https://aiworkflowtutorials.com/docs/hermes/official) |

两条路径**结构对称、互相引用**：理解篇遇到「具体怎么配」时跳官方篇，官方篇遇到「为什么要这样」时跳理解篇。

### 🎯 这份教程的不同

- 🇨🇳 **为中文新手重写**：每篇按"先讲场景再讲原理"的顺序，避免源码 + 英文文档双重门槛
- 🪽 **从最小稳定闭环起步**：不一上来就讲消息网关，先让你跑通一个能独立闭环的 Hermes Agent
- 📐 **生产边界意识**：从单机调试到接入消息平台，每一步都标注"这一步加什么、能扛多大流量"
- 🔁 **简繁双语**：简体 + 繁体同时维护，海外华人开发者直接可用

---

## 🚀 怎么用 (How to Use)

> 💡 **最佳用法 · 交给 AI Agent 讲给你听**
>
> 把本仓库 clone 下来或整段贴给 **Claude Code / OpenAI Codex** 这类 AI 编程 Agent，让它读完 README 后**按你的节奏一篇一篇讲**——不懂的随时打断追问，比自己埋头通读高效得多。

### 推荐阅读顺序

1. 先读从原理到实战 **01-02**，理解 Hermes 是什么、第一个稳定闭环长什么样
2. 再读官方教程中文版的「**入门**」，跑通最小可工作的 Hermes Agent
3. 回到真实场景，用一个最小用例练习"工具调用 → 记忆召回 → 持续 session"的闭环
4. 最后进入 **Skills / 消息网关 / 自动化边界**，把单 Agent 升级成长期运行的消息流

### 🧠 从原理到实战（8 篇）

| # | 章节 | 链接 |
|:-:|------|------|
| 01 | Hermes Agent 是什么 | [阅读 →](https://aiworkflowtutorials.com/docs/hermes/understanding/01-what-is-hermes-agent) |
| 02 | 先跑通第一个稳定闭环 | [阅读 →](https://aiworkflowtutorials.com/docs/hermes/understanding/02-first-stable-loop) |
| 03 | 配置、Provider 与目录结构 | [阅读 →](https://aiworkflowtutorials.com/docs/hermes/understanding/03-configuration-provider) |
| 04 | 工具系统与终端后端 | [阅读 →](https://aiworkflowtutorials.com/docs/hermes/understanding/04-tools-terminal-backends) |
| 05 | 记忆与召回 | [阅读 →](https://aiworkflowtutorials.com/docs/hermes/understanding/05-memory-and-recall) |
| 06 | Skills 系统 | [阅读 →](https://aiworkflowtutorials.com/docs/hermes/understanding/06-skills-system) |
| 07 | 消息网关 | [阅读 →](https://aiworkflowtutorials.com/docs/hermes/understanding/07-messaging-gateway) |
| 08 | 自动化边界 | [阅读 →](https://aiworkflowtutorials.com/docs/hermes/understanding/08-automation-boundaries) |

### 📚 官方教程中文版（2 个分组 · 8 篇）

| 分组 | 主题 | 篇数 | 入口 |
|------|------|:----:|------|
| 🟢 **入门** | 安装、配置、第一次启动 Hermes Agent | 3 | [开始 →](https://aiworkflowtutorials.com/docs/hermes/official/00-getting-started) |
| 📖 **使用手册** | Provider / 工具 / Skills / 记忆 / 消息网关 | 5 | [开始 →](https://aiworkflowtutorials.com/docs/hermes/official/01-user-guide) |

### 💡 第一次启动一个 Hermes Agent

```text
你（在 Hermes 项目里对 Claude Code / Codex）：

  我想用 Hermes 跑通最小稳定闭环：一个 Agent 收到自然语言指令后
  调用一个本地工具（比如 ls、cat），把结果总结后回复，
  并在下一次对话还能记得上一轮的上下文。
  先帮我列出最小可工作的目录结构 + 配置文件，
  再告诉我每一个文件该写什么、为什么这样写。
```

> 🎯 **Hermes 的关键是「先把单 Agent 闭环跑稳再扩展」**——很多 Agent 项目挂在工具调用、记忆召回这种基础环节上，先稳住这两条线再接消息网关。

---

## 🤝 怎么贡献 (Contribute)

本仓库**只接受 issue 反馈**，不接受完整教程正文 PR（完整内容在私有生产仓维护）。

适合提交的 issue：

- 🐛 **错别字 / 死链 / 事实错误**：教程站任意章节
- 🔗 **官方资料链接更新**：Hermes Agent 仓发布或文档结构调整的同步
- ✨ **样章表达问题**：本仓 `samples/` 里的样章
- 💡 **学习路径建议**：哪一章顺序应该调整、哪一篇应该补案例

[🐛 提交 Issue](https://github.com/xiangyugongzuoliu/hermes-agent-tutorial/issues) · [📜 完整贡献指南](CONTRIBUTING.md) · [🔒 版权说明](COPYRIGHT.md)

如果这份教程帮到你，给本仓库一个 ⭐ 是最直接的鼓励——也方便其他中文开发者发现它。

---

## 👋 关于翔宇 (About)

> 🚀 **翔宇 — AI Agent 工作流研究者。**
>
> 把 AI 工具变成能持续运转的生产系统，专注 Claude Code / Codex 等 AI 编程 Agent 的真实工程化用法，把「AI 怎么帮普通人解决真实问题」作为长期方向。

### 📚 公开内容矩阵

| 平台 | 内容 | 链接 |
|------|------|------|
| 🌐 **翔宇工作流官网** | AI 编程 / Agent / 自动化深度教程 | [xiangyugongzuoliu.com](https://xiangyugongzuoliu.com) |
| 📺 **YouTube 频道** | AI 编程实战、Agent 知识库实战、视频教程 | [@xiangyugongzuoliu](https://www.youtube.com/@xiangyugongzuoliu) |
| 💻 **GitHub Profile** | 公开仓库 + 个人简介 | [@xiangyugongzuoliu](https://github.com/xiangyugongzuoliu) |
| 𝕏 **X / Twitter** | 工作流碎片 + 实战记录 | [@xiangyuworkflow](https://x.com/xiangyuworkflow) |
| 💬 **微信公众号** | 应用场景引流文 + 工作流案例 | 翔宇工作流 |

### 🎯 推荐先看

- 🤖 [**AI 编程教程中文版**](https://aiworkflowtutorials.com) — 本仓库所属的教程站全集
- 🎬 [**YouTube · Agent 知识库实战**](https://www.youtube.com/@xiangyugongzuoliu) — Claude Code / Codex 真实项目录屏
- 🌐 [**翔宇工作流官网**](https://xiangyugongzuoliu.com) — 项目复盘、踩坑记录、长文工作流

### 🎓 AI 编程实操课

想系统学习 AI 编程 / Agent 工作流（Claude Code / Codex 实战），可以看翔宇的 AI 编程实操课：

- 🇨🇳 **国内版（FlowUS）**：https://flowus.cn/xiangyugongzuoliu/share/d392dcad-b537-44ee-a3e2-56ff5af02bce
- 🌍 **国际版（Buy Me a Coffee）**：[buymeacoffee.com/xiangyu](https://buymeacoffee.com/xiangyu)

> 🎁 **会员附赠**：跟着课程一起交付的实战脚手架 + Agent 长任务模板，把"读懂"变成"装进自己的工作流"。

---

<div align="center">

### ⭐ 如果这个教程对你有用，给一个 Star 让翔宇知道

[![翔宇官网](https://img.shields.io/badge/🌐_官网-xiangyugongzuoliu.com-FF6B35?style=for-the-badge)](https://xiangyugongzuoliu.com)
[![YouTube](https://img.shields.io/badge/📺_YouTube-频道-FF0000?style=for-the-badge)](https://www.youtube.com/@xiangyugongzuoliu)
[![GitHub](https://img.shields.io/badge/💻_GitHub-Profile-181717?style=for-the-badge)](https://github.com/xiangyugongzuoliu)

> 🎯 **工具一直在变，工作流不变。**
>
> 🛠️ **普通人对抗专业壁垒的唯一武器，就是工具。**

</div>
