---
title: 游戏
description: 安装并玩官方的 ARGVUS 游戏。
---
ARGVUS 游戏是官方 ARGVUS 游戏的元包。它自身不包含任何游戏代码：安装它会安装官方套装中的每一个游戏包，就像 `argvus-themes` 元包安装官方主题一样。

此仓库是所有 ARGVUS 游戏文档的唯一归宿。

## 安装

安装所有官方游戏：

```sh
sudo pacman -S argvus-games
```
安装单个游戏：

```sh
sudo pacman -S argvus-game-snake
```
安装游戏包不会更改您的会话、主题或桌面壁纸，也不会在您的主目录中创建文件。

## 可用游戏

| 游戏 | 包 | 命令 | 页面 |
| --- | --- | --- | --- |
| 贪吃蛇 | `argvus-game-snake` | `argvus game-snake` | [贪吃蛇](/docs/argvus-games/snake/) |

## 键盘优先控制

这些游戏遵循 ARGVUS 键盘优先模型。贪吃蛇使用 Vi 移动键 `h`、`j`、`k` 和 `l`，每个游戏页面都列出了其控制方式。

## 本地数据

游戏会将数据保存在用户的 XDG 配置目录中，例如默认情况下是 `$XDG_CONFIG_HOME/argvus/games/snake/` 或 `~/.config/argvus/games/snake/`。安装过程中，软件包绝不会写入主目录。
