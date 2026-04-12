---
title: "DocETL"
entity_type: "tool"
category: "Operations"
last_reviewed_at: "2026-04-10"
---

# DocETL

## 一句话总结

一个把合同、发票、PDF 和批量文本处理流程做成可复用 AI 流水线的开源文档 ETL 平台。

## 它解决什么问题

- 很多外贸、财务和运营团队手里有大量半结构化文档，但人工抽取和整理非常慢。
- 传统脚本难处理复杂文档理解、字段抽取、分类和多步转换。
- 文档工作流一旦需要反复调 prompt、验证输出，就很容易变成一次性脏活。

## 适合谁

- 需要处理合同、报价单、发票、PDF 和报告的运营与财务团队
- 做文档数据提取、质检和归档自动化的业务团队
- 想把 AI 文档处理流程做成稳定流水线的内部工具团队

## 核心能力

- 文档流水线：把复杂文档处理拆成多步 ETL 流程，便于复用和批量运行。
- Playground 开发：提供 DocWrangler 交互式界面，适合边试 prompt 边调流程。
- 生产运行：既能在 UI 里试，也能通过 Python 包在命令行或代码里跑正式流程。

## 典型使用场景

- 批量提取合同条款、报价字段或财务单据中的关键数据
- 先在 Playground 里把流程调顺，再交给运营或内部系统长期跑
- 给研究、法务、财务或文档密集型岗位做 AI 文档处理工作台

## 为什么值得关注

- 它不是单点“文档问答”，而是更接近真正可落地的文档处理流水线平台。
- GitHub 页面显示 2026 年 3 月 27 日仍有最新 commit，release 页可见 `0.2.6` 发布于 2025 年 12 月 28 日。
- 官方还专门给 Claude Code 提供了 quickstart，说明它对 AI 协作式流程设计有清晰产品思路。

## 类似项目

- [Contract Analyzer](contract-analyzer.md) - 更偏合同审阅与风险识别，而不是通用文档流水线。
- [Auto-Analyst](auto-analyst.md) - 更偏数据分析和报表解释，不是文档 ETL 主平台。

## 官方链接

- **官网:** https://docetl.org
- **GitHub:** https://github.com/ucbepic/docetl
- **文档:** https://ucbepic.github.io/docetl
- **更新记录:** https://github.com/ucbepic/docetl/releases

## 标签

- `文档处理`, `ETL`, `PDF`, `数据抽取`, `运营自动化`

## 更新观察点

- 继续观察 Playground 和 Python 生产流水线之间的衔接是否更顺。
- 关注多模型支持和文档处理成本控制是否继续完善。
- 看官方 quickstart 和社区案例是否扩展到更多合同、发票和表单场景。
