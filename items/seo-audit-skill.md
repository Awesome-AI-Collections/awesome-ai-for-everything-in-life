---
title: "SEO Audit Skill"
slug: "seo-audit-skill"
info_type: "awesome-ai-for-everything-in-life"
entity_type: "tool"
category: "Marketing / Growth"
featured: false
last_reviewed_at: "2026-04-11T00:00:00+00:00"
---

# SEO Audit Skill

## 一句话总结

一个把单页 SEO 体检做成可复用 agent skill 的项目，输入 URL 就能输出结构化 HTML 审计报告，并把确定性检查与语义判断拆成脚本层和 LLM 层来完成。

## 它解决什么问题

- 市场团队或独立站运营者想快速知道页面 SEO 是否达标，但手工逐项检查太慢。
- 只靠大模型做 SEO 审计容易把确定性问题和主观判断混在一起，报告不稳定。
- 团队希望把 SEO 体检变成可重复执行的技能，而不是每次重新写 prompt。

## 适合谁

- 需要快速审计官网、落地页或产品页 SEO 的增长团队
- 想把站点 SEO 诊断流程交给 agent 执行的顾问和独立开发者
- 希望获得结构化 HTML 报告，而不是零散聊天结论的人

## 核心能力

- 双层审计架构：Python 脚本负责状态码、robots、sitemap、schema、PageSpeed 等确定性检查，LLM 只补语义判断。
- 结构化报告输出：每次审计都会生成独立 HTML 报告，按摘要、站点检查、页面检查和优先行动项组织结果。
- 多档位技能：提供基础版和完整版 skill，便于按深度切换检查范围。
- 兼容多种 agent runtime：README 明确面向 OpenClaw、Claude Code、Cursor 以及支持 `SKILL.md` 的宿主。

## 典型使用场景

- 给产品官网做上线前 SEO 体检，快速找出 title、meta、H1、canonical 和内部链接问题。
- 在增长团队里把周期性 SEO 检查做成固定技能，减少人工审计时间。
- 给客户交付可读性更强的 HTML 审计报告，而不是一段无法复用的聊天记录。

## 为什么值得关注

- 它把“脚本做事实、模型做判断”的边界分得很清楚，报告可信度更高。
- 相比泛化的 SEO prompt，这种 skill 形态更适合被团队长期复用。
- 对 `Marketing / Growth` 分类来说，它代表了一类很实用的 agent 化网站审计工具。

## 类似项目

- [geo-seo-claude](geo-seo-claude.md) - 更偏 GEO / SEO 内容与策略方向，而这个项目更强调结构化页面审计。
- [rustyseo](rustyseo.md) - 同样关注 SEO 工作流，但 `SEO Audit Skill` 更明显地把 agent skill 和 HTML 报告打通。

## 官方链接

- **GitHub:** https://github.com/JeffLi1993/seo-audit-skill
- **说明文档:** https://github.com/JeffLi1993/seo-audit-skill/blob/main/README.md
- **更新记录:** https://github.com/JeffLi1993/seo-audit-skill/releases

## 标签

- `SEO`, `Marketing`, `Agent Skill`, `Audit`, `HTML Report`

## 更新观察点

- 后续重点看基础版和完整版 skill 的边界是否继续清晰，以及检查项是否继续扩展。
- 持续观察脚本层与 LLM 层的职责划分有没有新增更严格的 `llm_review_required` 规则。
- 优先重抓 README、report template 和 releases，确认输出结构与安装方式是否变化。
