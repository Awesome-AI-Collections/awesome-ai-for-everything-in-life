---
title: "GBrain"
slug: "gbrain"
info_type: "awesome-ai-for-everything-in-life"
entity_type: "tool"
category: "Personal Productivity"
featured: false
last_reviewed_at: "2026-04-10T00:00:00+00:00"
---

# GBrain

## 一句话总结

一个面向 AI Agent 的开源长期记忆系统，用 Markdown repo 做知识源，用 Postgres + pgvector 做检索，适合把人物档案、会议记录、笔记和日历沉淀成可搜索的个人大脑。

## 它解决什么问题

- 很多人的笔记、会议纪要、人物关系、日历和灵感分散在多个地方，AI 助手拿不到长期上下文。
- 普通 RAG 更像“临时查资料”，很难形成会随时间变聪明的个人知识系统。
- 当资料规模上到几千到上万份 Markdown 时，单靠 `grep` 和文件夹搜索已经不够用了。

## 适合谁

- 知识工作者
- 创始人、投资人、研究者
- 产品、运营和内容团队
- 想给 AI 助手接长期记忆的人

## 核心能力

- Markdown-first：把 markdown repo 当作真实知识源，而不是被平台锁住。
- Agent memory loop：让 Agent 形成“读脑子、回问题、写回脑子、继续同步”的长期记忆闭环。
- Hybrid search：用 Postgres + pgvector 做关键词 + 向量混合检索。
- 生产级 schema：提供 `GBRAIN_SKILLPACK` 和推荐目录结构，覆盖人物、公司、会议、原创想法等长期知识沉淀。
- MCP / CLI：既能给 Agent 调，也能给人手动操作。

## 典型使用场景

- 把会议记录、Apple Notes、日历和人物档案统一进一个 AI 可调用的大脑。
- 在开会前让 Agent 自动生成某人的 dossier 和你们的历史互动摘要。
- 让 AI 搜索“我过去怎么想这个问题”“这家公司最近发生了什么变化”。
- 用 nightly job 持续修正引用、补全实体、沉淀新的关系和认知。

## 为什么值得关注

- 这不是概念 demo，README 直接给了 Garry Tan 自己的真实生产数据规模。
- 它强调的是“知识会复利”，不是一次性问答，这点和普通知识库工具差别很大。
- 最新提交就在 2026-04-10，CHANGELOG 也在持续更新，说明项目还在快速迭代。
- 同时给了工具层、skillpack 和推荐 schema，比较适合直接抄作业搭自己的 agent memory。

## 类似项目

- [Khoj](./khoj.md) - 更像通用 AI 第二大脑与研究助手，`GBrain` 更强调 agent long-term memory、compiled truth + timeline 和生产级知识维护流程。
- [AnythingLLM](./anythingllm.md) - 更偏通用知识库与聊天工作台，`GBrain` 更偏个人长期知识沉淀和 agent write-back loop。

## 官方链接

- **GitHub:** https://github.com/garrytan/gbrain
- **更新记录:** https://github.com/garrytan/gbrain/blob/master/CHANGELOG.md
- **Skillpack:** https://github.com/garrytan/gbrain/blob/master/docs/GBRAIN_SKILLPACK.md
- **推荐 Schema:** https://github.com/garrytan/gbrain/blob/master/docs/GBRAIN_RECOMMENDED_SCHEMA.md

## 标签

- `AI 记忆系统`, `第二大脑`, `Agent`, `Markdown`, `Personal Productivity`

## 更新观察点

- 继续观察 OpenClaw / Hermes 之外的通用 Agent 适配是否增强。
- 看 `GBRAIN_SKILLPACK` 和推荐 schema 会不会继续成为这类项目的事实标准。
- 后续维护时优先重抓 README、CHANGELOG 和 docs 下的 skillpack/schema 文档。
