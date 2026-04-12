---
title: "ai-goofish-monitor"
entity_type: "tool"
category: "Sales / CRM"
last_reviewed_at: "2026-04-09"
---

# ai-goofish-monitor

## 一句话总结

一个基于 Playwright 和 AI 的闲鱼多任务监控系统，支持商品监控、智能筛选、通知推送和可视化后台。

## 它解决什么问题

- 手工盯闲鱼商品效率低，容易错过低价或新发布的好货
- 单纯关键词搜索噪音很大，筛选成本高
- 多账号、代理、通知和定时任务分散配置很麻烦

## 适合谁

- 想自动化捡漏的闲鱼用户
- 做二手交易监控和选品的人
- 需要把多个监控任务统一管理的副业团队

## 核心能力

- Web 管理后台：可视化管理任务、账号、提示词和日志
- AI 筛选：用自然语言标准分析商品质量与性价比
- 多任务监控：不同关键词、价格和区域条件可并发运行
- 通知推送：支持企业微信、Telegram、Webhook、Bark 等
- 账号与代理轮换：支持多账号绑定、代理池和失败重试

## 典型使用场景

- 监控某类数码商品，一有合适价格就立即推送通知
- 用 AI 判断描述和图片，过滤掉明显不靠谱的列表
- 给不同监控任务配置不同账号和提示词，做系统化捡漏

## 为什么值得关注

- 它不是简单“搜闲鱼”，而是在做一个闲鱼监控中台
- 任务、账号、通知和 AI 标准都能集中管理，适合长期运行
- 对想做 24 小时自动巡逻的人很实用

## 类似项目

- [XianyuAutoAgent](xianyu-auto-agent.md) - 更偏买家对话、议价和自动出单
- [xianyu-auto-reply-fix](xianyu-auto-reply-fix.md) - 更偏多账号店铺管理和发货后台

## 官方链接

- **GitHub:** https://github.com/Usagi-org/ai-goofish-monitor
- **更新记录:** https://github.com/Usagi-org/ai-goofish-monitor/releases

## 标签

- `闲鱼`, `商品监控`, `AI筛选`, `Playwright`, `通知推送`

## 更新观察点

- 后续重点看它在风控规避、稳定性和多账号调度上的迭代
- 优先观察 README 与 releases，跟踪 Web UI、SQLite 数据层和通知能力更新
- 如果后续补了更强的成交预测或自动操作能力，值得补进正文
