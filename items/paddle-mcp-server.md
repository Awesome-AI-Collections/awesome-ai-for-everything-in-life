---
title: "Paddle MCP Server"
slug: "paddle-mcp-server"
info_type: "awesome-ai-for-everything-in-life"
entity_type: "tool"
category: "Operations"
featured: false
last_reviewed_at: "2026-04-10T00:00:00+00:00"
---

# Paddle MCP Server

## 一句话总结

一个把 Paddle Billing API 暴露给 AI 助手的 MCP server，适合订阅、支付、退款、税务和商家报表场景。

## 它解决什么问题

- 互联网商业团队经常要查订阅、交易、退款和客户信息。
- merchant of record 体系下，税务、支付和订阅动作分散，普通 AI 无法直接操作。
- 需要让 AI 助手协助处理账务和订阅问题时，缺一个原生工具层。

## 适合谁

- 互联网商业化团队
- 订阅与支付运营
- 财务与客服团队

## 核心能力

- 客户与企业：支持客户、地址、企业信息查询和创建。
- 订阅与交易：支持 subscriptions、transactions 和 refunds 相关动作。
- 支付和税务：贴合 Paddle merchant of record 模式下的支付与税务流程。
- 报表与排查：适合用 AI 查账单、查订单和排查 billing 问题。

## 典型使用场景

- 让 AI 帮运营查询某客户的订阅和交易状态。
- 客服快速核对一笔退款或支付问题。
- 财务让 AI 拉取交易和客户信息做初步排查。

## 为什么值得关注

- Paddle 的定位本身就很适合出海 SaaS 和互联网商业团队。
- README 写得很实，明确列出可用的 customers、businesses、transactions 等工具。
- 对订阅收费、税务托管和退款场景很有实际价值。

## 类似项目

- [PayPal MCP Server](./paypal-mcp-server.md) - 更偏 PayPal 订单和支付链路，`Paddle MCP Server` 更偏订阅和 merchant of record。
- [Global AlipayPlus MCP](./global-alipayplus-mcp.md) - 更偏跨境支付与 customs declare，`Paddle MCP Server` 更偏互联网订阅商业化。

## 官方链接

- **GitHub:** https://github.com/PaddleHQ/paddle-mcp-server
- **文档:** https://developer.paddle.com/

## 标签

- `Paddle`, `订阅`, `支付`, `税务`, `MCP`

## 更新观察点

- 重点关注 transactions、refunds 和 subscription tools 是否继续增强。
- 后续维护时优先重抓 README 和 releases 页面。

