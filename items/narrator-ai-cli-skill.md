---
title: "Narrator AI CLI Skill"
entity_type: "tool"
category: "Design / Creative"
last_reviewed_at: "2026-04-13"
---

# Narrator AI CLI Skill

## 一句话总结

一个把电影解说、短剧旁白和配音视频生产流程写进 `SKILL.md` 的开源 AI agent skill，让 OpenClaw、Claude Code、Cursor、Windsurf 一类 agent 能直接调用 `narrator-ai-cli`，完成选素材、写文案、配音、配乐和视频合成。

## 快速判断

- 如果你想让 AI agent 直接产出“电影解说 / 短剧旁白视频”，它很值得看
- 如果你更需要通用视频编辑器或本地离线工作流，先看别的方案
- 它更像一个“AI 工作流技能包 + 专用 CLI 接口层”，不是独立的成品视频平台前端

## 你会怎么用它

- 接进 AI 开发流：把 `SKILL.md` 装进支持 markdown skill 的 agent，让 agent 按自然语言调用 `narrator-ai-cli`
- 接进日常工作流：用它把电影解说、剧情旁白、短剧混剪这类内容生产流程标准化
- 最小落地方式：先装好 CLI 和 API key，再让 agent 执行一次“指定电影 + 指定风格”的旁白视频生成

## 它解决什么问题

- 很多内容团队想批量做解说视频，但素材选择、脚本生成、配音和合成分散在多个工具里
- AI 虽然会写文案，但如果没有明确的 CLI 命令链和资源选择规则，很难稳定跑完整视频工作流
- 电影解说和短剧旁白类内容通常参数很多，人工来回切换模板、BGM、声音和任务状态很耗时间

## 适合谁

- 做电影解说、影视混剪、短剧旁白的内容团队
- 使用 OpenClaw、Claude Code、Cursor、Windsurf 等平台的 AI 创作者
- 想把视频内容生产标准化成 agent workflow 的运营团队

## 核心能力

- Skill + CLI 分层：`SKILL.md` 负责教 agent 怎么走流程，`narrator-ai-cli` 负责真实执行命令
- 双工作流路径：支持标准二创旁白和更快的原创旁白两条路径
- 资源编排：可调用电影素材、BGM、配音声线、旁白模板等资源做组合生产
- 全链路任务：覆盖写稿、片段数据生成、视频合成、可选的 magic-video 强化
- Agent 友好：大量命令支持 `--json`，适合被 agent 解析和串联

## 能力边界

- 它强在“把现成 Narrator AI 视频旁白能力接进 agent”，不是通用视频剪辑软件
- 它依赖 `narrator-ai-cli` 和远端 Narrator AI API，不是纯本地离线方案
- 需要 API key 和云端服务支持，不能把它当成零依赖开源视频生成引擎

## 集成方式

- 作为单独工具：手动安装 `narrator-ai-cli`，直接在终端跑生成和查询命令
- 作为 AI 工作流组件：适合放在内容生成链路里的“脚本生成 / 资源选择 / 合成执行”层
- 作为团队流程节点：可以把电影解说、短剧旁白视频做成标准 SOP，减少人工点点点

## 上手建议

- 第一步先确认你能拿到 `NARRATOR_APP_KEY`，并把 CLI 跑通
- 最值得先试的场景是：拿一个已有电影素材，走一次最短路径生成标准解说视频
- 如果你只是想验证值不值，先试单条视频，不要一开始就上批量生产

## 选型建议

- 如果你的目标是让 agent 直接“从自然语言到旁白视频”，它很合适
- 如果你的目标是做通用视频剪辑、复杂时间线编辑或完全自建引擎，更适合看别的工具
- 如果你需要的是“专用内容生产技能包”，而不是通用多场景 agent skill，它的定位很清楚

## 典型使用场景

- 让 agent 根据电影名和风格自动生成一条电影解说视频
- 为短剧素材快速做原创旁白、配音和配乐合成
- 批量测试不同模板、BGM 和声线组合，找更适合内容账号的生产方式

## 为什么值得关注

- 它把视频旁白生产从“会写提示词”推进到“会跑完整命令链”
- Skill 文档写得很细，覆盖资源选择、任务依赖、错误码和数据流，明显是给 agent 真正执行用的
- 对支持 markdown skill 的 agent 平台兼容面广，不只绑定单一产品

## 类似项目

- [Pixelle-Video](./pixelle-video.md) - 更像全自动短视频引擎，而 `Narrator AI CLI Skill` 更强调 agent 调度专用 CLI
- [Huobao Drama](./huobao-drama.md) - 更偏一站式短剧生产平台，而这里更偏“技能包 + API/CLI 工作流”

## 官方链接

- **GitHub:** https://github.com/GridLtd-ProductDev/narrator-ai-cli-skill
- **CLI Repo:** https://github.com/GridLtd-ProductDev/narrator-ai-cli
- **资源预览:** https://ceex7z9m67.feishu.cn/wiki/WLPnwBysairenFkZDbicZOfKnbc

## 标签

- `Video Narration`, `Film Commentary`, `Short Drama`, `AI Agent Skill`, `Dubbing`, `TTS`

## 参考依据

- 这条说明主要依据项目 README、`SKILL.md`、`plugin.json` 和公开仓库描述整理
- 其中关于双路径工作流、资源规模、支持平台和依赖要求，来自仓库当前公开文档

## 更新观察点

- 后续优先看 `SKILL.md` 是否继续扩展 workflow、错误处理和 agent 平台适配
- 持续关注 `narrator-ai-cli` 的版本更新和 API key 获取方式是否变化
- 如果后续新增更多模板、语言或更便宜的快路径模式，这个条目的选型判断需要跟着更新
