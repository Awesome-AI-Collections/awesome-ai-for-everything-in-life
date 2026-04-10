---
title: "QuickBooks Online MCP Server"
slug: "quickbooks-online-mcp-server"
info_type: "awesome-ai-for-everything-in-life"
entity_type: "tool"
category: "Operations"
featured: false
last_reviewed_at: "2026-04-10T00:00:00+00:00"
---

# QuickBooks Online MCP Server

## 一句话总结

一个把 QuickBooks Online 数据和财务操作开放给 AI 助手的 MCP server，覆盖客户、发票、付款、账单和多种财务报表。

## 它解决什么问题

- 财务和运营常常要在 QuickBooks 里反复查客户、发票、账单和报表。
- 外贸和跨境业务对账时，信息分散在多个实体和报表里，查起来费时。
- 想让 AI 直接接 QuickBooks，但普通聊天模型拿不到结构化账务动作。

## 适合谁

- 外贸财务团队
- 跨境电商财务与运营
- 需要 AI 对账和报表分析的人

## 核心能力

- 财务实体：覆盖客户、发票、付款、账单等多类 CRUD。
- 财务报表：支持利润表、总账、应收应付等 11 类报表。
- 经营分析：适合直接问客户余额、供应商费用、账龄等问题。

## 典型使用场景

- 让 AI 查询某客户当前余额和历史发票。
- 财务让 AI 拉取本月应收、应付和供应商支出。
- 管理层直接问总账、利润表或某时间段现金流情况。

## 为什么值得关注

- 这是 Intuit 官方组织下的仓库。
- README 明确写到 29 类实体、11 类财务报告，覆盖度很高。
- 抓取页显示 2026 年 1 月有大幅功能扩展提交，成熟度明显高于很多早期 MCP 样板仓库。

## 类似项目

- [Xero MCP Server](./xero-mcp-server.md) - 面向 Xero 用户，`QuickBooks Online MCP Server` 更贴 QuickBooks 生态。
- [CData JDBC MCP Server](./cdata-jdbc-mcp-server.md) - 更偏统一数据库/BI 查询层，`QuickBooks Online MCP Server` 更偏原生财务业务动作。

## 官方链接

- **GitHub:** https://github.com/intuit/quickbooks-online-mcp-server
- **文档:** https://developer.intuit.com/app/developer/qbo/docs/learn/explore-the-quickbooks-online-api
- **更新记录:** https://github.com/intuit/quickbooks-online-mcp-server/blob/main/CHANGELOG.md

## 标签

- `QuickBooks`, `财务报表`, `发票`, `对账`, `MCP`

## 更新观察点

- 重点关注报表类 tools 和写操作类 tools 是否继续完善。
- 后续维护时优先重抓 CHANGELOG、README 和 docs。

