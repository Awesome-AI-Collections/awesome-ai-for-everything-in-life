---
title: "Currency Conversion MCP"
entity_type: "tool"
category: "Operations"
last_reviewed_at: "2026-04-10"
---

# Currency Conversion MCP

## 一句话总结

一个提供实时汇率、历史汇率和货币换算能力的 MCP server，适合外贸报价、结算换算和跨币种成本测算。

## 它解决什么问题

- 外贸报价和成本核算经常要反复查汇率，手工换算很慢。
- 业务团队想让 AI 帮忙做多币种换算，但没有稳定的汇率工具层。
- 只知道当前汇率不够，很多场景还要追历史汇率做复盘。

## 适合谁

- 外贸业务员
- 跨境电商运营团队
- 做结算、报价和成本测算的人

## 核心能力

- 实时换算：支持把一种货币即时转换为另一种货币。
- 最新汇率：支持按 base currency 拉取最新汇率。
- 历史汇率：支持按日期查询历史汇率，适合对账和复盘。

## 典型使用场景

- 给客户报价前快速换算美元、欧元、人民币等价格。
- 核算采购、运费和利润时统一币种。
- 复盘历史订单时回看当时汇率区间。

## 为什么值得关注

- 功能聚焦，不是泛泛金融数据，而是直接解决汇率问题。
- 接成 MCP 后，AI 可以直接做换算和解释，不用人工切网页。
- 对外贸、跨境和多币种业务都很实用。

## 类似项目

- [Synth MCP](./synth-mcp.md) - 更偏更丰富的金融和外汇数据，`Currency Conversion MCP` 更轻更直接。
- [CData JDBC MCP Server](./cdata-jdbc-mcp-server.md) - 更偏多平台数据中台，不专门做汇率。

## 官方链接

- **GitHub:** https://github.com/wesbos/currency-conversion-mcp
- **更新记录:** https://github.com/wesbos/currency-conversion-mcp/releases

## 标签

- `汇率`, `货币换算`, `MCP`, `外贸报价`, `多币种`

## 更新观察点

- 重点看实时汇率源和历史汇率能力是否继续稳定。
- 持续观察是否增加更多货币过滤和批量换算能力。
- 后续维护时优先重抓 README 和 releases。
