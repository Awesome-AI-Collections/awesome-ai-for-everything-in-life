---
title: "eBay MCP"
slug: "ebay-mcp"
info_type: "awesome-ai-for-everything-in-life"
entity_type: "tool"
category: "Operations"
featured: false
last_reviewed_at: "2026-04-10T00:00:00+00:00"
---

# eBay MCP

## 一句话总结

一个面向 eBay Sell APIs 的本地 MCP server，覆盖库存、订单、营销、分析和更多卖家操作，适合跨境卖家用 AI 辅助后台运营。

## 它解决什么问题

- eBay 卖家后台功能多、入口散，人工切换和操作效率低。
- 团队想让 AI 直接协助 listing、订单和营销任务，但没有现成 MCP 层。
- 做跨境电商时，很多动作需要接 Sell API，自己封装成本很高。

## 适合谁

- eBay 卖家运营团队
- 做跨境电商后台管理的人
- 想把 AI 接进 eBay Sell API 的团队

## 核心能力

- 大范围 Sell API 覆盖：README 宣称提供 325 个 eBay API tools。
- 卖家后台能力：覆盖库存、订单、营销和分析等常见运营能力。
- MCP 集成：可直接接到 Claude Desktop 等客户端。

## 典型使用场景

- 查询 listing、库存和订单状态。
- 用 AI 协助创建 offer、调整价格和促销活动。
- 把 eBay 卖家后台接进日常运营 AI 助手。

## 为什么值得关注

- 覆盖面明显比很多单点电商 MCP 更大。
- 文档里对 OAuth、限流和 API 状态都给了比较完整的说明。
- 很适合跨境卖家把重复后台工作交给 AI 辅助。

## 类似项目

- [shopify-mcp](./shopify-mcp.md) - 更偏 Shopify 独立站管理，`eBay MCP` 更偏 Sell API 后台运营。
- [ShipStation MCP Server](./mcp-shipstation-api.md) - 更偏发货履约，不像 `eBay MCP` 这样覆盖 listing 与营销。

## 官方链接

- **GitHub:** https://github.com/YosefHayim/ebay-mcp
- **文档:** https://developer.ebay.com/docs
- **更新记录:** https://github.com/YosefHayim/ebay-mcp/releases

## 标签

- `eBay`, `MCP`, `Sell API`, `跨境电商`, `卖家运营`

## 更新观察点

- 重点看高覆盖工具集是否持续跟进 eBay 新接口。
- 持续观察 OAuth 配置和限流处理的稳定性。
- 后续维护时优先重抓 changelog、README 和 releases。
