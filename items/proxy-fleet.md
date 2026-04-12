---
title: "proxy-fleet"
slug: "proxy-fleet"
info_type: "awesome-ai-for-everything-in-life"
entity_type: "tool"
category: "Operations"
featured: false
last_reviewed_at: "2026-04-13T00:00:00+00:00"
---

# proxy-fleet

## 一句话总结

一个用单条命令管理多台 VPS 代理节点的工具，可部署 3x-ui + VLESS+Reality 并自动生成 Clash/Mihomo 订阅。

## 它解决什么问题

- 多台 VPS 代理节点的部署、端口配置、防火墙放行和订阅更新通常很碎片化
- 个人或小团队维护 AI 服务代理、流媒体代理和通用代理时，节点状态容易失真
- 手工改 Clash / Mihomo 配置在增删节点后很容易过时

## 适合谁

- 需要统一管理多台 VPS 代理节点的人
- 想为 AI 服务、流媒体和通用代理维护自动更新订阅的个人或小团队
- 熟悉 SSH 和自建代理基础设施的运维型用户

## 核心能力

- 一键部署：可自动安装 3x-ui、选择空闲端口、配置 VLESS+Reality 并开放防火墙
- 节点编队管理：统一维护多台 VPS 的部署、移除、状态检查和订阅同步
- 订阅自动生成：从节点实际 API 状态生成 Clash / Mihomo 配置，降低手工维护成本
- NAT 支持：可指定端口范围，在受限环境中挑选可用端口
- 规则模板化：把 AI 服务、流媒体、通用代理和直连规则拆成独立模板文件

## 典型使用场景

- 给自己或小团队维护一套可持续更新的代理订阅
- 批量部署多个地区的代理节点，并统一检查存活和流量状态
- 调整 AI 服务路由规则后，快速同步到订阅下发链路

## 为什么值得关注

- 它把节点部署、端口冲突检查、3x-ui 配置和订阅生成整合成了一条连续工作流
- 对自建代理基础设施的人来说，README 的操作路径已经足够直接
- 虽然表面是 CLI，但主价值更偏多节点运维与配置管理，而不是终端交互本身

## 类似项目

- [CC-Switch CLI](../../awesome-ai-for-coding/items/cc-switch-cli.md) - 更偏本地 AI 工具链和 provider 切换；`proxy-fleet` 更偏远程代理节点运维

## 官方链接

- **GitHub:** https://github.com/oaker-io/proxy-fleet
- **更新记录:** https://github.com/oaker-io/proxy-fleet/releases

## 标签

- `VPS`, `Proxy`, `Clash`, `Mihomo`, `3x-ui`, `Operations`

## 更新观察点

- 后续重点看节点管理命令、规则模板和订阅同步逻辑是否继续扩展
- 优先关注 README 和 releases 页面
- 如果后续加入更强的 agent-native CLI/tooling 设计，可以重新评估是否更适合放进 `awesome-cli-for-ai`
