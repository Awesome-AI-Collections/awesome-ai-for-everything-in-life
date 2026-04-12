---
title: "Xero MCP Server"
entity_type: "tool"
category: "Operations"
last_reviewed_at: "2026-04-10"
---

# Xero MCP Server

## 一句话总结

一个把 Xero 会计和财务报表能力接入 AI 助手的 MCP server，支持发票、付款、银行流水和财务报表查询。

## 它解决什么问题

- 外贸财务团队常常要在 Xero 里手工查发票、付款和银行流水。
- 管理层要快速问利润、回款和应收情况时，传统报表流程太慢。
- 想让 AI 助手直接读 Xero 数据，但缺稳定的标准接口层。

## 适合谁

- 外贸财务
- 跨境电商财务团队
- 需要 AI 查账和经营报表的人

## 核心能力

- 发票与付款：支持发票和付款相关命令。
- 银行流水：支持银行账户交易查询。
- 财务报表：支持资产负债表、利润表、试算平衡等。
- 联系人与设置：支持联系人和部分会计设置访问。

## 典型使用场景

- 让 AI 快速查某客户最近的发票和付款情况。
- 让财务助手汇总某段时间的银行交易。
- 管理层直接问本月利润表或应收情况。

## 为什么值得关注

- 这是 XeroAPI 官方组织下的仓库。
- README 列出的 MCP scopes 和命令已经覆盖了真实财务工作最常用的一批动作。
- 对跨境业务常见的回款、发票和报表场景很贴近。

## 类似项目

- [QuickBooks Online MCP Server](./quickbooks-online-mcp-server.md) - 面向 QuickBooks Online 用户，`Xero MCP Server` 更适合 Xero 财务体系。
- [CData JDBC MCP Server](./cdata-jdbc-mcp-server.md) - 更偏统一数据查询，`Xero MCP Server` 更偏单系统会计动作。

## 官方链接

- **GitHub:** https://github.com/XeroAPI/xero-mcp-server
- **文档:** https://developer.xero.com/documentation/

## 标签

- `Xero`, `会计`, `发票`, `付款`, `MCP`

## 更新观察点

- 继续观察 invoices、payments 和 reports 相关命令是否扩展到更多写操作。
- 后续维护时优先重抓 README 和 releases 页面。

