---
title: "Cel.ai"
entity_type: "tool"
category: "Sales / CRM"
last_reviewed_at: "2026-04-10"
---

# Cel.ai

## 一句话总结

一个支持 WhatsApp、Telegram、Chatwoot 和 VAPI 的开源全渠道 AI 助手框架，适合搭建多助手路由和消息自动化。

## 它解决什么问题

- 很多团队想做全渠道助手，但每接一个渠道就得重写一套消息和路由逻辑。
- 业务一复杂，就会遇到售前、售后、预约、通知等多个助手之间如何协同的问题。
- 托管式平台虽然快，但往往限制自定义和数据控制，不适合深入业务集成。

## 适合谁

- 做客服、销售、预约或多渠道消息自动化的业务团队
- 想把 WhatsApp、Telegram 和 Chatwoot 统一编排的互联网产品团队
- 需要自托管、可控消息助手框架的自动化开发者

## 核心能力

- 全渠道连接器：开箱支持 WhatsApp、Telegram、VAPI.ai、Chatwoot。
- 多助手路由：支持基于状态、意图和上下文的多助手分流。
- 中间件与可观测：支持 moderation、blacklist、events 和 LangSmith tracing。

## 典型使用场景

- 把售前咨询、售后服务和预约提醒拆成多个助手，由路由层自动分发
- 给 WhatsApp 和 Telegram 做统一的客户沟通底座
- 在 Chatwoot 或 VoIP 场景里快速接入自定义 AI 助手

## 为什么值得关注

- 它的重点不是单个 bot，而是“多助手 + 多渠道 + 共享上下文”的架构能力。
- GitHub 页面显示 2026 年 3 月 10 日仍有 commit，最新 release `v0.7.1` 同样发布于 2026 年 3 月 10 日。
- 对外贸和互联网团队来说，WhatsApp、Telegram、Chatwoot 同时支持这一点非常实用。

## 类似项目

- [Evolution API](evolution-api.md) - 更偏 WhatsApp 集成编排层，不强调多助手路由。
- [MCP WaliChat](mcp-walichat.md) - 更偏把 WhatsApp 业务能力暴露给 MCP 客户端，不是全渠道助手框架。

## 官方链接

- **GitHub:** https://github.com/cel-ai/celai
- **文档:** https://cel-ai.github.io/celai/
- **更新记录:** https://github.com/cel-ai/celai/releases

## 标签

- `全渠道`, `WhatsApp`, `Telegram`, `Chatwoot`, `多助手路由`

## 更新观察点

- 看更多连接器是否继续补进来，尤其是更贴业务的 CRM 或工单系统。
- 关注 Agentic Router 和状态路由的配置体验是否进一步降低门槛。
- 继续观察自托管部署和 tracing 能力是否更适合生产环境。
