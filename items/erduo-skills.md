---
title: "Erduo Skills"
slug: "erduo-skills"
info_type: "awesome-ai-for-everything-in-life"
entity_type: "tool"
category: "Writing / Content"
featured: false
last_reviewed_at: "2026-04-10T00:00:00+00:00"
---

# Erduo Skills

## 一句话总结

一个面向 AI Agent 的内容工作流技能库，把日报生成、RSS 摘要、转录精修、翻译和网页转 Markdown 等常见任务做成可直接调用的结构化技能。

## 它解决什么问题

- 很多 Agent 能聊天但缺少可复用、可组合的具体工作流单元
- 信息抓取、翻译、转录和内容清洗常要临时拼脚本，维护成本高
- 同一类内容处理任务容易重复搭链路，难以沉淀成团队可复用能力

## 适合谁

- 想给 AI Agent 增加现成技能包的个人和小团队
- 做信息抓取、翻译、本地化、转录整理的人
- 希望把内容处理流程产品化或标准化的工作流设计者

## 核心能力

- 技能库结构：把不同任务封装为独立 `SKILL.md` 单元，便于安装和组合
- 内容情报工作流：提供技术日报和 RSS 精选摘要两类多源抓取与筛选流程
- 内容处理能力：覆盖转录精修、翻译精修和网页正文转 Markdown
- CLI 与 Agent 双入口：部分技能既可由 Agent 调用，也支持脚本或命令行运行
- Plugin 安装方式：可通过 `npx skills add` 安装，也补充了 Claude Code plugin marketplace 的接入方式

## 技能拆解

### daily-news-report

- 作用：从多个技术信源抓取、筛选并生成结构化技术日报
- 特点：采用 Master-Worker 架构，支持子 Agent 并行抓取和无头浏览器处理 JS 页面
- 适用场景：做固定的 AI / 技术情报流，减少手工刷站点的时间

### ak-rss-digest

- 作用：从预设 RSS / Atom 源中筛出高质量文章，生成中文日报式摘要
- 特点：按分数过滤内容，可直接用脚本抓最近几天 feed
- 适用场景：想稳定跟踪 AI agent、深度访谈和高信息密度内容的人

### transcript-polisher

- 作用：把访谈、播客、演讲或会议的转录文本整理成更可读的文章
- 特点：强调保留原意和原表达，不走“高度概括”路线，支持长文本分块处理
- 适用场景：整理录音纪要、访谈实录和播客文字稿

### translate-polisher

- 作用：做高质量文章翻译与本地化，支持中英和中日双向翻译
- 特点：采用分析、初译、审校、终稿四步流程，支持术语表和风格参数
- 适用场景：技术文章、说明文档和多语内容的精修翻译

### web-to-markdown

- 作用：把不同站点的 URL 抓取并清洗成适合后续处理的 Markdown
- 特点：会按站点类型选择抓取策略，并提供多层回退链路
- 适用场景：给后续的摘要、翻译、知识整理流程提供干净正文输入

### gemini-watermark-remover

- 作用：去除 Gemini 生成图片右下角的水印
- 特点：用 Python 和 Pillow 实现像素级还原，提供不同尺寸的预制遮罩
- 适用场景：处理带 Gemini 水印的图片素材

## 典型使用场景

- 给团队的 Agent 增加“日报生成”或“RSS 精选摘要”能力，做固定情报流
- 把访谈、播客或会议转录文本整理成更适合阅读和归档的文章
- 抓取网页正文后转成干净 Markdown，继续做分析、翻译或摘要
- 为多语内容流程补上术语分析、翻译审校和结构化输出链路
- 把几个独立 skill 组合起来，串成“抓取 -> 转 Markdown -> 翻译 / 精修 -> 输出”的内容流水线

## 为什么值得关注

- 它提供的不是单点工具，而是一组可复用的 Agent 技能资产
- README 对每个技能的输入、输出和使用方式写得比较明确，落地门槛低
- 同时覆盖采集、清洗、翻译、转录和内容生产，适合做通用内容工作流底座
- 每个 skill 都有比较明确的职责边界，适合按任务拆装，而不是一次接入整套大系统

## 类似项目

- [AutoGen](autogen.md) - 更偏多智能体应用框架；Erduo Skills 更偏可直接安装和调用的技能集合
- [x-tweet-fetcher](x-tweet-fetcher.md) - 更聚焦内容抓取；Erduo Skills 还覆盖翻译、转录和日报等后续处理流程

## 官方链接

- **GitHub:** https://github.com/rookie-ricardo/erduo-skills
- **更新记录:** https://github.com/rookie-ricardo/erduo-skills/releases

## 标签

- `AI Agent`, `技能库`, `工作流`, `翻译`, `转录`, `网页抓取`, `Markdown`

## 更新观察点

- 后续重点看它是否继续扩充更多可安装技能，以及技能 bundle 的组织方式
- 优先观察 README 与 releases，跟踪安装入口、技能列表和运行脚本的变化
- 如果后续补了更完整的 marketplace 文档、版本发布节奏或更多内容工作流，值得更新正文
