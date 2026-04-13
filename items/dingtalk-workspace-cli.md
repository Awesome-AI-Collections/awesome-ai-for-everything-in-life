---
title: "DingTalk Workspace CLI"
entity_type: "tool"
category: "Operations"
last_reviewed_at: "2026-04-14"
---

# DingTalk Workspace CLI

## 一句话总结

钉钉官方的企业工作台 CLI，可让人类和 AI agents 以结构化方式访问企业数据、自动化工作流并保持审计边界。

## 快速判断

- 如果你的工作流深度依赖钉钉企业数据和组织能力，它值得看
- 如果你不在钉钉企业生态内，它的价值会大幅下降
- 它更像企业工作台接入层，而不是泛 AI CLI 工具

## 你会怎么用它

- 接进工作流：让 agent 或脚本读取企业数据、执行组织内操作
- 接进日常运营：通过结构化 JSON、dry-run 和 auth 流程做可审计自动化
- 最小落地方式：先完成认证，再跑一条最简单的只读查询验证权限边界

## 它解决什么问题

- 企业协作平台的数据接入常常缺少 agent 友好的 CLI
- 企业级自动化要求鉴权、审计和最小权限，不适合野生脚本直接乱调
- 人类和 agent 共用同一套工作台接口时，需要明确安全边界

## 适合谁

- 需要 CLI 或 agent 访问钉钉企业数据的管理员与团队
- 想把钉钉工作台能力接入自动化流程的企业用户
- 重视审计、鉴权和企业级边界的组织

## 核心能力

- 官方工作台 CLI：直接面向钉钉企业工作台能力
- Agent 友好：支持 JSON 输出与 skills，方便接给 agents
- 安全设计：OAuth、allowlisting、least privilege 和审计边界明确
- 升级和运维：有自升级、回滚和版本校验能力

## 能力边界

- 明显可用：钉钉企业工作台自动化与 agent 接入
- 效果一般：不在钉钉生态、或者只需要通用团队聊天机器人
- 不要误用：它不是 coding 工具，也不是通用 AI CLI 大全

## 集成方式

- 作为单独工具：直接用 dws 管理和调用钉钉工作台能力
- 作为 AI 工作流组件：放在企业数据访问和操作层，给 agents 提供结构化入口
- 作为团队流程节点：适合企业内部审批、数据读取和工作台自动化

## 上手建议

- 第一步先完成组织授权与 CLI access 开启
- 最值得先试的是只读查询和 dry-run 路径
- 如果组织权限边界复杂，先从最小范围试点，不要一开始就放大权限

## 选型建议

- 如果你的主需求是“把钉钉工作台能力接进 agent / 自动化”，适合看它
- 如果你的主需求只是“找一个 AI CLI”，它不是这类项目
- 如果你处在钉钉企业生态里，它的价值会明显高于通用工具

## 为什么值得关注

- 企业自动化最难的是权限与审计，它一开始就把这件事放在中心
- 官方背景让它比很多第三方桥接更适合企业环境
- 对 AI agent 进入企业工作台这件事很有代表性

## 官方链接

- **GitHub:** https://github.com/DingTalk-Real-AI/dingtalk-workspace-cli
- **更新记录:** https://github.com/DingTalk-Real-AI/dingtalk-workspace-cli/releases

## 标签

- `DingTalk`, `Enterprise`, `CLI`, `Operations`, `Agents`
