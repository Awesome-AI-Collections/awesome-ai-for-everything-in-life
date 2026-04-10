---
title: "ExpenseBot"
slug: "expense-bot"
info_type: "awesome-ai-for-everything-in-life"
entity_type: "tool"
category: "Operations"
featured: false
last_reviewed_at: "2026-04-10T00:00:00+00:00"
---

# ExpenseBot

## 一句话总结

一个面向费用和票据整理的开源 AI 自动化系统，可从收据图片、WhatsApp 消息和 Drive 文件夹中提取数据并自动归档到 Google Drive 与 Sheets。

## 它解决什么问题

- 财务、行政和运营团队整理报销票据时，经常要手工分类、录入和归档。
- 票据来自图片、PDF、聊天记录和网盘文件夹，来源分散且格式不统一。
- 许多 OCR 工具只能抽字段，不能把后续归档、检索和自动化流程接起来。

## 适合谁

- 负责报销、费用整理和票据归档的财务与行政团队
- 需要批量处理收据和费用凭证的运营岗位
- 想把票据识别和归档流程产品化的内部工具团队

## 核心能力

- 收据抽取：可处理收据图片并提取金额、日期、商户等结构化字段。
- 多入口接入：支持 UI 上传、WhatsApp 收据流入和读取指定 Drive 文件夹。
- 自动归档：把识别结果同步到 Google Drive 与 Google Sheets，便于后续对账和检索。

## 典型使用场景

- 财务团队批量整理员工报销票据并做台账沉淀。
- 运营团队处理线下采购、出差或门店费用凭证。
- 小团队把聊天里收到的票据自动归档到共享网盘和表格。

## 为什么值得关注

- 不只做 OCR，而是更贴近真实费用整理和归档流程。
- WhatsApp 与 Drive 的接入方式很适合跨境和分布式团队。
- 项目展示了较完整的 AI 票据自动化基础设施思路。

## 类似项目

- [Invoiceable](./invoiceable.md) - 更偏发票字段解析。
- [Invoiscope](./invoiscope.md) - 更偏票据识别和字段抽取方案。

## 官方链接

- **GitHub:** https://github.com/babdulhakim2/expense-bot
- **更新记录:** https://github.com/babdulhakim2/expense-bot/releases

## 标签

- `expense-management`, `receipts`, `finance-ops`, `google-drive`, `whatsapp`

## 更新观察点

- 继续观察票据分类、币种处理和字段抽取准确率是否提升。
- 重点看 Google Drive / Sheets 工作流是否更稳定、更易部署。
- 如果后续补报销审批或对账链路，财务落地价值会更强。
