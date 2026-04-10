---
title: "Amazon MCP"
slug: "amazon-mcp"
info_type: "awesome-ai-for-everything-in-life"
entity_type: "tool"
category: "Operations"
featured: false
last_reviewed_at: "2026-04-10T00:00:00+00:00"
---

# Amazon MCP

## 一句话总结

一个让 Claude 通过 MCP 搜索并购买 Amazon 商品的开源连接器，适合采购辅助、商品比较和购物自动化场景。

## 它解决什么问题

- 采购或运营人员想用 AI 帮忙比价、找货和下单，但没有现成连接层。
- 纯聊天模型不能直接检索 Amazon 商品并完成动作。
- 做轻量采购自动化时，手工在 Amazon 和 AI 之间切换很低效。

## 适合谁

- 做采购和物料比价的人
- 需要 AI 辅助购物或选品的运营团队
- 想把 Amazon 搜索购买流程接进 AI 助手的人

## 核心能力

- Amazon 搜索：通过对话方式检索商品。
- 购买动作：支持把购买流程接给 AI 助手。
- AI 友好接入：基于 MCP 接到 Claude 等客户端。

## 典型使用场景

- 用 AI 快速比较采购候选商品。
- 做办公室或项目物料的智能采购辅助。
- 让 AI 协助生成购物决策和下单流程。

## 为什么值得关注

- 2026 年 2 月仍有 commit，不是完全停更的 demo。
- 它走的是“AI 直接完成 Amazon 动作”的路线，而不只是读数据。
- 对采购类自动化比单纯商品搜索更进一步。

## 类似项目

- [Amazon Marketplace MCP Server by CData](./amazon-marketplace-mcp-server-by-cdata.md) - 更偏卖家数据查询，不负责购物购买动作。
- [shopify-mcp](./shopify-mcp.md) - 更偏独立站后台运营，不是 Amazon 购物入口。

## 官方链接

- **GitHub:** https://github.com/Fewsats/amazon-mcp
- **更新记录:** https://github.com/Fewsats/amazon-mcp/releases

## 标签

- `Amazon`, `MCP`, `采购辅助`, `购物自动化`, `选品`

## 更新观察点

- 重点看购买动作的稳定性和支付链路是否继续完善。
- 持续观察是否扩展到更强的商品比较和筛选能力。
- 后续维护时优先重抓 README 和 releases。
