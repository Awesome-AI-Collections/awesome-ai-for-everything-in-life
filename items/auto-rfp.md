---
title: "AutoRFP"
entity_type: "tool"
category: "Operations"
last_reviewed_at: "2026-04-10"
---

# AutoRFP

## 一句话总结

一个面向投标和售前团队的开源 AI RFP 平台，可从 PDF、Word、Excel、PPT 中抽取问题，并基于知识库生成带来源的应答草稿。

## 它解决什么问题

- 售前和投标团队处理 RFP 时，经常要从长文档里手工抽问题、找资料、拼答案，工作量很大。
- 多部门协作写标书时，知识分散在过往方案、文档和项目材料里，检索成本高。
- 生成式 AI 如果不给来源，投标内容很容易失真，团队也不敢直接拿来用。

## 适合谁

- 做招投标、售前解决方案和合作申请的团队
- 需要频繁响应采购问卷和安全问卷的 B2B 公司
- 想搭建内部应标知识库和 RFP 协作流程的运营团队

## 核心能力

- 问题抽取：自动从多种办公文档中提取结构化 RFP 问题。
- 知识检索：接入 LlamaCloud 和文档索引，在资料库中查找相关答案依据。
- 应答生成：输出可编辑的 AI 草稿，并附带来源信息方便人工复核。

## 典型使用场景

- SaaS 公司快速生成客户招标书和安全问卷的首版回答。
- 外贸和 B2B 团队统一复用过往成功案例、资质材料和方案模板。
- 方案团队把重复性的 RFP 应答工作标准化，减少重复搜索和抄写。

## 为什么值得关注

- 这个场景本身就很高价值，能直接影响成交效率和方案团队产能。
- 文档解析、知识库检索、来源引用和多人协作被整合成了一套完整流程。
- 从 2025 年末的 commit 信号看，项目近期还有实质开发，不像只停在概念阶段。

## 类似项目

- [Contract Analyzer](./contract-analyzer.md) - 更偏合同问答与条款分析，不是投标应答工作流。
- [OpenContracts](./opencontracts.md) - 更偏法律文档结构化处理，可作为文档理解方向的对照。

## 官方链接

- **GitHub:** https://github.com/run-llama/auto_rfp
- **更新记录:** https://github.com/run-llama/auto_rfp/commits/main

## 标签

- `rfp`, `bidding`, `proposal-writing`, `knowledge-base`, `operations`

## 更新观察点

- 继续观察多文档、多项目协作和权限体系是否进一步完善。
- 重点看问答来源引用、答案可编辑性和抽题准确率是否提升。
- 后续维护时优先重抓 commits 与 README，确认 LlamaCloud 依赖和部署门槛变化。
