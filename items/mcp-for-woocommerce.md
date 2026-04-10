---
title: "MCP for WooCommerce"
slug: "mcp-for-woocommerce"
info_type: "awesome-ai-for-everything-in-life"
entity_type: "tool"
category: "Operations"
featured: false
last_reviewed_at: "2026-04-10T00:00:00+00:00"
---

# MCP for WooCommerce

## 一句话总结

一个把 WooCommerce 与 WordPress 数据通过 MCP 暴露给 Claude、VS Code MCP 等客户端的社区插件，适合独立站和内容电商团队。

## 它解决什么问题

- 很多 WooCommerce 店铺想接 AI，但 WordPress 生态里缺少标准化接口层。
- 业务团队希望 AI 能读取店铺和站点数据，而不是只会聊天。
- 独立站常常同时要管内容与商品，没有统一 MCP 接口会很割裂。

## 适合谁

- WooCommerce 店铺团队
- WordPress 运营团队
- 想把 AI 接入独立站后台的人

## 核心能力

- WooCommerce 数据接入：把店铺数据暴露给 MCP 客户端。
- 多传输支持：支持 STDIO 和 HTTP streamable transport。
- 安全与鉴权：提供 JWT 与 OAuth 相关方案。

## 典型使用场景

- 让 AI 读取 WooCommerce 商品和订单数据。
- 给站内客服或运营助手提供店铺后台上下文。
- 把内容站和电商站数据统一接给 AI 客户端。

## 为什么值得关注

- 2025 年 12 月仍有 commit，维护状态还可以。
- 对 WordPress/WooCommerce 这类大量中小站点很有现实意义。
- 同时兼顾了 WooCommerce 数据和现代 MCP 接入方式。

## 类似项目

- [shopify-mcp](./shopify-mcp.md) - 更偏 Shopify 生态，`MCP for WooCommerce` 更适合 WordPress 独立站。
- [eBay MCP](./ebay-mcp.md) - 更偏平台卖家后台，而不是自建站后台。

## 官方链接

- **GitHub:** https://github.com/iOSDevSK/mcp-for-woocommerce
- **更新记录:** https://github.com/iOSDevSK/mcp-for-woocommerce/releases

## 标签

- `WooCommerce`, `WordPress`, `MCP`, `独立站`, `JWT`

## 更新观察点

- 持续观察 JWT、OAuth 和 streamable transport 的兼容性更新。
- 重点看 WooCommerce 数据对象覆盖是否继续扩展。
- 后续维护时优先重抓 AGENTS、README 和 releases。
