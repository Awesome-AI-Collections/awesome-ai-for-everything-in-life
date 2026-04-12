---
title: "Global AlipayPlus MCP"
entity_type: "tool"
category: "Operations"
last_reviewed_at: "2026-04-10"
---

# Global AlipayPlus MCP

## 一句话总结

一个把 AlipayPlus 跨境支付 API 封装成 MCP tools 的服务器，支持支付、退款和海关申报，适合跨境收款与关务联动场景。

## 它解决什么问题

- 跨境业务不只是收款，还经常要处理退款和海关申报。
- 支付系统和业务 AI 助手之间常常是断开的，流程无法对话化。
- 团队想让 AI 帮忙查支付状态或触发关务动作，但没有标准工具层。

## 适合谁

- 跨境支付团队
- 外贸运营团队
- 需要把支付与海关联到 AI 的业务团队

## 核心能力

- 支付操作：支持创建、查询和取消支付。
- 退款操作：支持全额或部分退款。
- 海关申报：支持 `customs_declare` 和申报状态查询。

## 典型使用场景

- 用 AI 查询一笔跨境支付当前状态。
- 让运营或客服助手触发退款流程。
- 在跨境支付流程里把海关申报动作一并接入。

## 为什么值得关注

- 这是少见把支付、退款和海关申报一起打包成 MCP 的项目。
- 对跨境电商和外贸收款场景很贴近。
- changelog 到 2025 年 7 月，说明不是只做了一个静态样例。

## 类似项目

- [CustomsInfo](./customsinfo.md) - 更偏关务信息查询，`Global AlipayPlus MCP` 更偏支付动作和 customs declare。
- [CData JDBC MCP Server](./cdata-jdbc-mcp-server.md) - 更偏数据查询中台，不负责支付与退款动作。

## 官方链接

- **GitHub:** https://github.com/alipay/global-alipayplus-mcp
- **文档:** https://docs.alipayplus.com/
- **更新记录:** https://github.com/alipay/global-alipayplus-mcp/blob/main/CHANGELOG.md

## 标签

- `跨境支付`, `退款`, `海关申报`, `MCP`, `AlipayPlus`

## 更新观察点

- 重点看 customs declare 相关能力是否继续扩展。
- 持续观察支付与退款流程在 MCP 客户端中的接入体验。
- 后续维护时优先重抓 changelog、README 和官方文档。
