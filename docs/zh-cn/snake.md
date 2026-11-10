---
title: 蛇
description: 玩复古 ARGVUS 终端贪吃蛇游戏。
---
`argvus-game-snake` 是一个用于终端的复古贪吃蛇游戏。它是 [ARGVUS Games](/docs/argvus-games/) 元包的一部分。

## 安装

```sh
sudo pacman -S argvus-game-snake
```
安装 `argvus-games` 也会安装这个游戏。

## 打开游戏

从终端打开它，使用:

```sh
argvus game-snake
```
The application menu also contains an `ARGVUS Snake` launcher.发射器
opens the game through the standard ARGVUS Kitty profile in a centered floating
window sized `1380x840`, matching the Control Center.

## 控制

动作特意使用标准 Vi 键：

- `h`：左；
- `j`：向下；
- `k`：向上；
- `l`：对。

When the game opens, press `Enter` to start moving right, or press `h`, `j`,
`k` or `l` to start immediately in that direction.

- `p` 或空格：暂停和恢复；
- `r`：游戏结束后重新启动；
- `q` 或 Esc：退出。

## 规则

蛇吃食物后就会长大。触摸墙壁或蛇自己的身体
结束本轮比赛。

## 排名

本地前十名排名存储在
`$XDG_CONFIG_HOME/argvus/games/snake/ranking.json`，或
默认为 `~/.config/argvus/games/snake/ranking.json`。包安装
不在主目录中创建文件；该文件是第一次创建的
分数已保存。
