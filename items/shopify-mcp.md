---
title: "shopify-mcp"
entity_type: "tool"
category: "Operations"
last_reviewed_at: "2026-04-10"
---

# shopify-mcp

## 一句话总结

一个让 AI 直接操作 Shopify GraphQL Admin API 的 MCP server，可处理商品、订单、客户、库存和 metafields，适合跨境电商与独立站运营团队。

## 它解决什么问题

- Shopify 店铺数据分散在商品、订单、客户和库存模块里，人工切换很慢。
- 业务团队想让 AI 帮忙查店铺信息或处理基础运营动作，但缺一个可调用接口层。
- 很多 Shopify 连接工具只读不写，难以支撑实际运营流程。

## 适合谁

- Shopify 店铺运营团队
- 做独立站和跨境电商的业务人员
- 想把 AI 接到店铺管理流程的团队

## 核心能力

- 店铺核心对象操作：覆盖产品、客户、订单和库存等关键对象。
- Shopify 新版支持：README 明确跟进到 GraphQL Admin API `2026-01`。
- 元数据管理：支持 metafields 读写，更适合实际运营与扩展字段场景。

## 典型使用场景

- 用 AI 查询订单、客户和库存状态，辅助日常运营。
- 批量维护商品、标签、变体和店铺元数据。
- 让 AI 辅助处理独立站客服、发货前检查和商品整理工作。

## 为什么值得关注

- 它不是泛泛的“Shopify AI 工具”，而是真正的接口连接层。
- 对 Shopify 2026 新应用体系有说明，说明不是很旧的仓库。
- 对做跨境电商和互联网运营的人来说，实用性很强。

## 类似项目

- [CData JDBC MCP Server](./cdata-jdbc-mcp-server.md) - 更偏多平台只读数据接入，`shopify-mcp` 更偏 Shopify 单平台深度操作。
- [Evolution API](./evolution-api.md) - 更偏消息与客服入口，不负责店铺后台数据操作。

## 官方链接

- **GitHub:** https://github.com/GeLi2001/shopify-mcp
- **更新记录:** https://github.com/GeLi2001/shopify-mcp/releases

## 标签

- `Shopify`, `MCP`, `独立站`, `电商运营`, `库存管理`

## 更新观察点

- 持续观察对 Shopify 新 API 版本和认证方式的跟进速度。
- 重点看订单、库存和 metafields 相关能力是否继续扩展。
- 后续维护时优先重抓 README 和 releases。
