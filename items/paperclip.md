---
title: "Paperclip"
slug: "paperclip"
info_type: "awesome-ai-for-everything-in-life"
entity_type: "tool"
category: "Operations"
featured: false
last_reviewed_at: "2026-04-11T00:00:00+00:00"
---

# Paperclip

## 一句话总结

一个把多代理团队当成“公司”来管理的开源编排平台，用 org chart、goals、budgets、heartbeats 和治理机制来运行持续性业务工作。

## 它解决什么问题

- 当一个团队同时跑很多个 Claude Code、Codex、Cursor 或 OpenClaw 代理时，很容易失去任务、上下文和成本控制。
- 普通任务看板能管人，但不一定适合管理会心跳唤醒、长期自治和持续花费 token 的 agents。
- 多代理长期协作需要目标传递、审批、审计和预算边界，单靠 prompt 或脚本很难稳定维持。

## 适合谁

- 想长期运营多代理业务流程的个人创业者和团队
- 需要跟踪 agent 成本、任务、审批和审计记录的运营负责人
- 想把多种 agent runtime 组织成一个“可管理公司”的构建者

## 核心能力

- 组织化编排：支持 org chart、角色分工、汇报关系和目标对齐。
- 心跳与自治：agent 可按 heartbeat 周期醒来处理任务，也能响应事件触发。
- 成本与治理：支持预算上限、审批、暂停、回滚和审计日志。
- 多公司控制面：一个部署可管理多个 company，并保持数据隔离。

## 典型使用场景

- 同时运行多个 coding、marketing、ops agent，并在一个界面里统一追踪任务与花费。
- 让 agent 根据公司目标分层委派工作，而不是只在一个聊天窗口里单线程执行。
- 为长期自治业务建立预算、审批和回滚机制，避免成本失控。

## 为什么值得关注

- 它强调的不是“再造一个 agent”，而是“怎么把很多 agent 组织成一个业务系统”。
- README 对不是什么、适合什么边界写得很清楚，不容易和 workflow builder 或 prompt manager 混淆。
- 对 `Operations` 分类来说，它是很典型的“AI 组织运行层”工具，而不是单个应用。

## 类似项目

- [Flowise](flowise.md) - 更偏可视化搭建 agent 和工作流，而 `Paperclip` 更偏公司治理、预算和组织编排。
- [Dify](dify.md) - 更偏 AI 应用与工作流平台，而 `Paperclip` 更强调多代理团队的长期运营与管理。

## 官方链接

- **官网:** https://paperclip.ing
- **GitHub:** https://github.com/paperclipai/paperclip
- **文档:** https://paperclip.ing/docs
- **更新记录:** https://github.com/paperclipai/paperclip/releases

## 标签

- `Operations`, `Multi-Agent`, `Governance`, `Automation`, `Agent Orchestration`

## 更新观察点

- 后续重点看 heartbeat、governance、budget enforcement 和 multi-company 能力是否继续成熟。
- 持续观察与 OpenClaw、Claude Code、Codex、Cursor 等宿主的集成边界如何演进。
- 优先重抓 README、AGENTS、docs 和 releases，确认“company OS”这条路线是否继续深化。
