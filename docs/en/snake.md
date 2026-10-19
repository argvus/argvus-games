---
title: Snake
description: Play the retro ARGVUS terminal Snake game.
---

`argvus-game-snake` is a retro Snake game for the terminal. It is part of the
[ARGVUS Games](/docs/argvus-games/) meta-package.

## Installation

```sh
sudo pacman -S argvus-game-snake
```

Installing `argvus-games` installs this game as well.

## Opening the game

Open it from a terminal with:

```sh
argvus game-snake
```

The application menu also contains an `ARGVUS Snake` launcher. The launcher
opens the game through the standard ARGVUS Kitty profile in a centered floating
window sized `1380x840`, matching the Control Center.

## Controls

Movement deliberately uses the standard Vi keys:

- `h`: left;
- `j`: down;
- `k`: up;
- `l`: right.

When the game opens, press `Enter` to start moving right, or press `h`, `j`,
`k` or `l` to start immediately in that direction.

- `p` or Space: pause and resume;
- `r`: restart after Game Over;
- `q` or Esc: quit.

## Rules

The snake grows when it eats food. Touching the wall or the snake's own body
ends the round.

## Ranking

The local top-ten ranking is stored in
`$XDG_CONFIG_HOME/argvus/games/snake/ranking.json`, or
`~/.config/argvus/games/snake/ranking.json` by default. Package installation
does not create files in the home directory; the file is created the first time
a score is saved.
