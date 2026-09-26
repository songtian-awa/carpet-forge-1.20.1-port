# Carpet Mod — Forge 1.20.1 移植版

官方 **fabric-carpet**（gnembon）的 **Forge 1.20.1** 移植版，基于社区项目 **Carpet: NeoForged 1.0.8**（chililisoup）构建。功能与官方 fabric-carpet 完全一致。

- **Minecraft 版本**：1.20.1（Forge 47.x，兼容 47.4.x）
- **核心版本**：官方 carpet 1.4.112 / 1.4.147
- **Mod Loader**：Forge（纯 Forge，无需任何前置 mod）
- **加载器要求**：FML loaderVersion `[47,)`

## 功能

与官方 fabric-carpet 完全一致，包含：
- 假人命令（`commandPlayer`）
- 可移动方块实体（`movableBlockEntities`）
- 堆叠潜影盒（`stackableShulkers`）
- 漏斗计数器（`hopperCounters`）
- 创造模式无碰撞（`creativeNoClip`）
- 完整 Scarpet 脚本语言
- 以及官方全部可配置规则

## 使用

1. 将 `forge-carpet-1.20.1-1.0.8+v251027.jar` 放入 Forge 1.20.1 整合包的 `mods` 文件夹
2. 服务端与客户端均需安装（服务端必需）
3. 进游戏后使用：
   - `/carpet list` 查看所有规则
   - `/carpet <规则名> <值>` 设置规则，例如 `/carpet commandPlayer true`

## 文件

| 文件 | MD5 |
|---|---|
| `forge-carpet-1.20.1-1.0.8+v251027.jar` | `171814ed8c3b6f78ff0609f6e295d8ed` |

## 协议与致谢

- 本移植基于 **MIT 协议** 发布
- 原始 Mod：gnembon 的 [fabric-carpet](https://github.com/gnembon/fabric-carpet)
- Forge 移植：chililisoup 的 [neoforge-carpet](https://github.com/chililisoup/neoforge-carpet)

> 本项目仅为分发官方/社区已开源的移植成果，不包含第三方未授权代码。
