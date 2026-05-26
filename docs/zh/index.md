# 快速开始

AnkiNBT 是一个客户端物品、实体和数据组件编辑器。先选对版本，再把 jar 放进 `mods` 文件夹。进入游戏后，手持物品或在背包里悬停物品，按 `N` 打开编辑器。

## 先选对文件

| 你使用的加载器 | 下载文件 | Java |
|---|---|---|
| Fabric | `AnkiNBT-Fabric-mc版本-1.2.4.jar` | 1.21 系列用 Java 21，26.1 系列用 Java 25 |
| NeoForge | `AnkiNBT-NeoForge-mc版本-1.2.4.jar` | 1.21 系列用 Java 21，26.1 系列用 Java 25 |

Fabric 版本需要同时安装 Fabric API。下载时优先看文件名里的 `Fabric` 或 `NeoForge`，再看 `mc` 后面的 Minecraft 版本。

[安装指南](installation-guide.md){ .md-button .md-button--primary }
[兼容矩阵](compat-matrix.md){ .md-button }

## 1.2.4 重点功能

- 覆盖 Fabric 和 NeoForge 的 Minecraft 1.21 到 1.21.11，以及 26.1、26.1.1、26.1.2。
- 简易模式支持物品基础属性、附魔、Lore、属性修饰、外观、药水效果和 NBT 导入导出。
- 高级模式支持 NBT 树搜索、添加、删除、编辑、展开折叠和类型校验。
- Lore 与名称编辑支持 `Ctrl+A`、方向键、`Shift` 选择、鼠标拖选和选中文本上色。
- 药水编辑支持基础药水、自定义颜色、多选效果，以及每个效果独立设置时长、等级、粒子和图标。
- 附魔和属性修饰支持本地化名称、搜索、说明和单项删除。
- 村民交易编辑器支持可搜索物品选择、买入/卖出项、最大交易次数、经验和价格倍率。
- NBT 导入导出支持分类、别名和自定义保存目录。

[功能总览](feature-overview.md){ .md-button .md-button--primary }
[简易模式](simple-mode.md){ .md-button }
[高级模式](advanced-mode.md){ .md-button }

## 打开编辑器

### 编辑主手物品

1. 在主手拿着要编辑的物品。
2. 按 `N`。
3. 编辑器会打开并读取该物品。

### 编辑背包里的物品

1. 打开背包、箱子或其他容器。
2. 把鼠标悬停在目标物品上。
3. 按 `N`。
4. 编辑器会读取悬停物品。

没有手持或悬停任何物品时，AnkiNBT 会提示没有可编辑的目标。

## 保存规则

- 按 `Ctrl+S` 保存修改。
- 保存只在创造模式可用，非创造模式可以查看但不能写回。
- 按 `Esc` 关闭编辑器。
- 有未保存修改时，关闭会出现确认提示。

## 常用入口

| 你想做什么 | 去哪里 |
|---|---|
| 安装或更新 | [安装指南](installation-guide.md) |
| 查版本支持 | [兼容矩阵](compat-matrix.md) |
| 查快捷键 | [快捷键](keyboard-shortcuts.md) |
| 看 1.2.4 改了什么 | [更新记录 1.2.4](changelog-1.2.4.md) |
| 给 Modrinth 写介绍 | [Modrinth 介绍](modrinth.md) |

## 配置文件

配置文件位于 `.minecraft/config/ankinbt.json`。常用选项包括打开按键、默认模式、界面透明度、主题色、属性说明、NBT 导出目录和关闭确认。
