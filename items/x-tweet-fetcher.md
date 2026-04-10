---
title: "x-tweet-fetcher"
slug: "x-tweet-fetcher"
info_type: "awesome-ai-for-everything-in-life"
entity_type: "tool"
category: "Research / Analysis"
featured: true
last_reviewed_at: "2026-04-09T00:00:00+00:00"
---

# x-tweet-fetcher

## 一句话总结

一个面向 X、列表、长文与微信内容抓取的多后端采集工具，支持 Nitter、Playwright 与自动回退。

## 它解决什么问题

- X 没有稳定的免费 API，直接抓取又容易失效
- 单一抓取方案容易因为环境差异或风控而挂掉
- 想把推文、列表、长文和微信文章统一拉进采集流程并不容易

## 适合谁

- 做舆情监控和资讯巡逻的人
- 需要自动抓取 X 与微信内容的研究团队
- 在 Claude Code、OpenClaw 或服务器环境里跑内容采集的人

## 核心能力

- 多后端抓取：支持 Nitter、Playwright 和自动回退
- 多内容类型：支持单条推文、回复、时间线、列表、长文和微信文章
- JSON 输出：适合接入 AI Agent 与自动化脚本
- 环境适配：支持 VPS、Mac、Windows、CI、Claude Code、OpenClaw
- 增量监控：适合用在 mentions 监听与定时巡逻场景

## 典型使用场景

- 巡逻重点 X 账号，筛选值得跟踪的新内容
- 抓取推文列表和长文，交给 LLM 做后续摘要或分类
- 统一抓取 X 和微信文章，为 AI 资讯流或研究库供料

## 为什么值得关注

- 它的价值不只是“抓推文”，而是做了多后端容错
- 对 AI Agent 来说，结构化 JSON 输出很友好
- 如果你经常在受限环境下抓内容，这种自动回退非常实用

## 官方链接

- **GitHub:** https://github.com/ythx-101/x-tweet-fetcher
- **更新记录:** https://github.com/ythx-101/x-tweet-fetcher/releases

## 标签

- `X抓取`, `Nitter`, `Playwright`, `微信文章`, `内容采集`

## 更新观察点

- 后续重点看它在 Lists、Articles 和中国平台抓取上的稳定性迭代
- 优先观察 README 与 releases，跟踪后端回退逻辑和环境兼容性变化
- 如果后续补了更强的分析或调度能力，值得补进正文
