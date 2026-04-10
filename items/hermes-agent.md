---
title: "Hermes Agent"
slug: "hermes-agent"
info_type: "awesome-ai-for-everything-in-life"
entity_type: "tool"
category: "Personal Productivity"
featured: true
last_reviewed_at: "2026-04-10T12:27:00+00:00"
---

# Hermes Agent

## 一句话总结

一个可运行在 CLI、Telegram、Discord、Slack 等多入口的自进化 AI 助手，支持记忆、技能、定时任务和远程运行，不必绑定在单台电脑上。

## 它解决什么问题

- 不同聊天入口、命令行和自动化任务之间常常各自割裂，难以共享同一个 AI 助手的上下文与能力
- 很多 AI 助手只会一次性对话，难以把经验沉淀成可复用技能和长期记忆
- 想让 Agent 长时间在云端或服务器上持续工作时，常常需要自己拼装运行环境、消息入口和调度能力

## 适合谁

- 想把 AI 助手放到 Telegram、Slack、Discord 等入口长期使用的人
- 希望 Agent 具备记忆、技能和自动化能力的个人效率重度用户
- 需要远程运行 Agent、并在多终端持续接力的人

## 核心能力

- 多入口接入：同一个 Agent 可以同时通过 CLI 和多种消息平台工作
- 学习与记忆闭环：支持技能沉淀、记忆管理、历史会话搜索和用户画像累积
- 自动化执行：内建定时任务、子代理并行和多种终端后端，方便长期运行

## 典型使用场景

- 把个人 AI 助手部署在云端，用 Telegram 或 Slack 随时交办任务
- 让 Agent 定期生成日报、做夜间备份或执行固定巡检
- 在命令行里调试任务，在聊天入口里继续跟进同一条工作流

## 为什么值得关注

- 不只是一层聊天壳，而是把记忆、技能、调度和多入口整合成一个长期助手系统
- 明确支持远程运行，不强依赖本地开发机常驻在线
- 文档覆盖安装、配置、消息网关、MCP、技能、记忆和安全边界，落地门槛相对清晰

## 类似项目

- [CodePilot](https://github.com/op7418/CodePilot) - 更偏桌面端的多模型 Agent 工作台，而 Hermes Agent 更强调长期运行、多入口和自进化能力。
- [小龙 OpenClaw 语音助手](../../awesome-ai-for-coding/items/xiaolong-openclaw.md) - 都能把 Agent 入口扩展到非纯命令行场景，但 OpenClaw 语音助手更偏编码 Agent 的语音交互扩展。

## 官方链接

- **GitHub:** https://github.com/NousResearch/hermes-agent
- **文档:** https://hermes-agent.nousresearch.com/docs/
- **更新记录:** https://github.com/NousResearch/hermes-agent/releases

## 标签

- `AI Agent`, `Personal Productivity`, `Telegram`, `Slack`, `Memory`, `Automation`

## 更新观察点

- 继续观察多平台消息网关的支持范围和稳定性是否扩展
- 关注技能系统、记忆系统和用户建模相关文档是否持续增强
- 后续优先重新抓取 release 与 docs，确认自动化、远程运行和安全边界有没有明显变化
