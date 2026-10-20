# Obsidian + Claude Code：用AI重建你的第二大脑

> 从零搭建AI驱动的个人知识管理系统。免费、开源、持续更新。
>
> 中文版最新：**v261020**（2026-10-20），基于 Obsidian 1.14.4、Claude Code 2.1.287 实测更新，新增约 30 张实测截图。

<p align="center">
  <img src="assets/hero.gif" alt="obsidian-ai-orange-book Hero Animation" />
  <br/>
  <sub>动画由 <a href="https://github.com/alchaincyf/huashu-design">huashu-design</a> skill 制作</sub>
</p>

![封面](screenshots/cover.png)

## 内容概览

这不是又一本 Obsidian 教程，而是「AI 时代的知识管理方法论 + 落地工具」：

- **问题篇** -- 为什么你的笔记软件是「信息坟场」，以及为什么只有 AI 能解决这个问题
- **选择篇** -- 三个完全独立的十亿级项目，不约而同选了 Markdown 存储 AI 的记忆，这不是巧合
- **上手篇** -- 40 分钟内搞定 Obsidian 安装 + Claude Code 接入
- **架构篇** -- 设计你的 vault，让 AI 能高效地理解和操作它
- **知识库篇** -- Karpathy 的 LLM Wiki 模式：让 AI 维护你的知识库，而不是建 RAG
- **实战篇** -- 7 个可以直接抄的工作流，每个都有具体步骤和 prompt
- **生态篇** -- 1000+ 插件中你真正需要的 4 个
- **进阶篇** -- Git 版本控制、自定义 Skills、本地 AI、多 Vault 策略

## 核心洞察

**洞察1：Markdown 是 AI Agent 的原生接口**

Manus、OpenClaw、Claude Code 都选了 Markdown 文件存储 AI 的记忆，不是向量数据库。Obsidian vault 就是一堆 Markdown 文件。

**洞察2：LLM 应该是「编译器」而非「检索器」**

Karpathy 的核心论点：与其建 RAG 让 LLM 检索你的笔记，不如让 LLM 直接维护你的知识库。在 40 万字规模下验证有效。

**洞察3：CLAUDE.md + index.md 做了 80% 的工作**

不需要复杂的 MCP 设置。一个 CLAUDE.md + 每个文件夹一个 index.md，就足以让 Claude Code 高效导航整个知识库。

## 下载

| 格式 | 链接 |
|------|------|
| PDF（中文，v261020） | [Obsidian-AI-v261020.pdf](Obsidian-AI-v261020.pdf) |
| PDF (English, v1.0.0) | [Obsidian-AI-The-Complete-Guide-v1.0.0.pdf](Obsidian-AI-The-Complete-Guide-v1.0.0.pdf) |

> 英文版仍是 4 月的 v1.0.0，还没有跟进 10 月修订。

> 💡 PDF 文件建议下载后阅读，体验更佳。GitHub 在线预览可能无法完整渲染。

## 目录

| 章节 | 标题 |
|------|------|
| 自序 | 我的笔记从来不是我整理的 |
| §01 | 信息坟场 |
| §02 | 为什么是 Obsidian |
| §03 | 30 分钟上手 Obsidian |
| §04 | Claude Code 进场 |
| §05 | 设计你的 Vault 架构 |
| §06 | 让 AI 维护你的知识库 |
| §07 | 7 个真实工作流 |
| §08 | 插件和工具生态 |
| §09 | 进阶 |

## 关于作者

**花叔** -- AI Native Coder，独立开发者，AI自媒体博主，30万+粉丝。代表作：小猫补光灯（App Store 付费榜 Top 1）、「AI编程橙皮书」系列。

- X/Twitter: [@AlchainHust](https://x.com/AlchainHust)
- YouTube: [@Alchain](https://www.youtube.com/@Alchain)
- B站: [花叔](https://space.bilibili.com/14097567/)
- 公众号: 花叔（微信搜索）
- 官网: [huasheng.ai](https://www.huasheng.ai/)

## 橙皮书系列

本书是**橙皮书系列**的一部分 -- 免费、深入的 AI 工具与新兴技术指南：

| 书名 | 仓库 |
|------|------|
| Claude Code 从入门到精通 | [claude-code-orange-book](https://github.com/alchaincyf/claude-code-orange-book) |
| Claude Code 源码解析 | [claude-code-source-analysis-orange-book](https://github.com/alchaincyf/claude-code-source-analysis-orange-book) |
| Agent Skills | [agent-skills-orange-book](https://github.com/alchaincyf/agent-skills-orange-book) |
| Harness Engineering | [harness-engineering-orange-book](https://github.com/alchaincyf/harness-engineering-orange-book) |
| OpenClaw | [openclaw-orange-book](https://github.com/alchaincyf/openclaw-orange-book) |
| Polymarket 完全指南 | [polymarket-orange-book](https://github.com/alchaincyf/polymarket-orange-book) |
| **Obsidian + Claude Code** | **本仓库** |

## 更新记录

- **v261020（2026-10-20）**：基于 Obsidian 1.14.4、Claude Code 2.1.287 实测更新。新增约 30 张截图（设置、核心插件、属性、数据库 Bases 的表格和看板、图谱、CLI，Claude Code 的信任提示、权限确认、先审计后执行的整理过程、插件市场装 obsidian-skills、LLM Wiki 的 ingest/log/lint）；第 4 章重写，第 5 章新增数据库（Bases），第 6 章补齐 Karpathy 原文的三个动作，第 8、9 章更新插件与 Skills 现状。勘误集中写在前言「10月补记」。
- **v1.0.0（2026-04-11）**：初版。

## 关注花叔

<p align="center"><img src="https://raw.githubusercontent.com/alchaincyf/alchaincyf/main/assets/follow.svg" width="720" alt="关注花叔：公众号「花叔」、B站「花叔v」、小红书「花叔」" /></p>

## 📚 在线阅读（WorkBuddy）

本书已同步到 WorkBuddy 资料库：每章一个网页，也可以直接把链接丢给你的 Agent 当上下文。

https://www.workbuddy.cn/space/d/g5E78ejX962o977geKeOjj

全部橙皮书入口：https://www.workbuddy.cn/space/d/YcllWXknAUoMk6lFSWdfbI
## 许可

本作品免费分享，用于学习交流。欢迎转载和引用，请注明出处。
