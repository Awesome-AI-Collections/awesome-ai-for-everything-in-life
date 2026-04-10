---
title: "MarineTraffic MCP Server"
slug: "marinetraffic-mcp-server"
info_type: "awesome-ai-for-everything-in-life"
entity_type: "tool"
category: "Operations"
featured: false
last_reviewed_at: "2026-04-10T00:00:00+00:00"
---

# MarineTraffic MCP Server

## 一句话总结

一个把 MarineTraffic 船舶追踪数据接给 AI 的 MCP server，适合查询船位、船舶详情和指定海域内的船只情况。

## 它解决什么问题

- 海运场景下，业务和跟单经常需要知道船现在在哪里、是否接近港口。
- 手工在船舶追踪网站查船很碎，AI 也拿不到实时海运数据。
- 货物在海上时，客户和内部团队都想快速知道运输动态。

## 适合谁

- 外贸跟单员
- 海运与供应链团队
- 需要 AI 查询船舶动态的人

## 核心能力

- 船位查询：支持按 MMSI 或 IMO 查询实时位置。
- 船舶详情：支持拿到船舶更完整的基础信息。
- 区域检索：支持看某海域里有哪些船只。

## 典型使用场景

- 跟客户同步在途海运货物的大致位置。
- 监控靠港前后的船舶动态。
- 用 AI 辅助分析某区域内的船舶情况。

## 为什么值得关注

- 和外贸海运的实际问题很贴。
- 不是泛物流工具，而是直接连接船舶追踪数据。
- 对“国外货物现在到哪了”这种问题特别有帮助。

## 类似项目

- [UPS MCP](./ups-mcp.md) - 更偏快递包裹追踪，`MarineTraffic MCP Server` 更偏海运船舶动态。
- [CustomsInfo](./customsinfo.md) - 更偏税则与关务信息，不负责运输过程追踪。

## 官方链接

- **GitHub:** https://github.com/Cyreslab-AI/marinetraffic-mcp-server
- **更新记录:** https://github.com/Cyreslab-AI/marinetraffic-mcp-server/releases

## 标签

- `海运`, `船舶追踪`, `MCP`, `供应链`, `外贸物流`

## 更新观察点

- 重点看 MarineTraffic API key 使用限制和重试机制是否继续优化。
- 持续观察是否增加靠港、航线或更多区域查询能力。
- 后续维护时优先重抓 README 和 release 页面。
