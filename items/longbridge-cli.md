---
title: "Longbridge CLI"
slug: "longbridge-cli"
info_type: "awesome-ai-for-everything-in-life"
entity_type: "tool"
category: "Research / Analysis"
featured: false
last_reviewed_at: "2026-04-10T13:06:00+00:00"
---

# Longbridge CLI

## 一句话总结

Longbridge 官方的 AI-native 命令行工具，覆盖行情、基本面、账户、持仓和下单等 OpenAPI 能力，适合做金融研究、脚本化分析和终端工作流。

## 它解决什么问题

- 金融研究和账户操作常分散在网页、App 和接口文档里，难以在终端里高效串成一条分析流程
- 想把行情、持仓、账户或交易数据接入脚本和 AI agent 时，通常还要自己封装一层接口
- 非结构化的终端输出不利于自动化，而金融分析又很依赖可组合、可脚本化的数据流

## 适合谁

- 用 Longbridge 做市场研究和投资分析的用户
- 想把行情、账户和交易数据接入脚本或 AI agent 的金融场景用户
- 偏好用终端或自动化方式处理金融信息的人

## 核心能力

- 全量 CLI 覆盖：覆盖行情、衍生品、基本面、研究、账户、订单和 watchlist 等多个模块
- AI 友好输出：所有命令支持 `--format json`，便于脚本和 AI agent 消费
- 终端工作流：适合命令行查询、数据管道和日常金融分析操作
- 多市场符号支持：支持美股、港股、A 股、新加坡和部分加密标的格式

## 典型使用场景

- 在终端里快速查询实时价格、持仓、资产和账户信息
- 把 Longbridge 数据接入 `jq`、脚本或 AI agent 做进一步分析
- 为金融研究工作流搭建结构化、可复用的命令行数据入口

## 为什么值得关注

- 它不只是通用 API SDK，而是明确面向终端和 AI agent 设计的命令行层
- 在金融研究场景里，结构化 JSON 输出和命令粒度都很有实用价值
- 对把金融数据接入自动化和 agent 工作流的人来说，这是很直接的基础工具

## 类似项目

- [FinGPT](fingpt.md) - 更偏金融大模型与研究平台，而 Longbridge CLI 更偏数据与账户操作入口。
- [TradingAgents-CN](tradingagents-cn.md) - 更像多智能体金融分析学习平台，而 Longbridge CLI 更偏面向实际数据和终端操作的工具层。

## 官方链接

- **文档:** https://open.longbridge.com/docs/cli/
- **GitHub:** https://github.com/longbridge/longbridge-terminal

## 标签

- `Finance`, `Trading`, `CLI`, `Market Data`, `Longbridge`, `AI Agent`

## 更新观察点

- 后续重点看 CLI 子命令覆盖是否继续扩展到更多金融场景
- 关注 JSON 输出、AI agent 集成和终端 UX 是否持续增强
- 持续跟踪文档更新时间和 GitHub 仓库变化，判断其自动化与 agent 支持是否继续深化
