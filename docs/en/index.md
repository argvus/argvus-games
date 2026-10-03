---
title: Games
description: Install and play the official ARGVUS games.
---

ARGVUS Games is the meta-package for the official ARGVUS games. It ships no game
code of its own: installing it installs every game package in the official set,
the same way the `argvus-themes` meta-package installs the official themes.

This repository is the single home for all ARGVUS game documentation.

## Installation

Install every official game:

```sh
sudo pacman -S argvus-games
```

Install a single game:

```sh
sudo pacman -S argvus-game-snake
```

Installing a game package does not change your session, your theme or your
wallpaper, and does not create files in your home directory.

## Available games

| Game | Package | Command | Page |
| --- | --- | --- | --- |
| Snake | `argvus-game-snake` | `argvus game-snake` | [Snake](/docs/argvus-games/snake/) |

## Keyboard-first controls

The games follow the ARGVUS keyboard-first model. Snake uses the Vi movement
keys `h`, `j`, `k` and `l`, and every game page lists its controls.

## Local data

Games keep their data in the user's XDG configuration directory, for example
`$XDG_CONFIG_HOME/argvus/games/snake/`, or `~/.config/argvus/games/snake/` by
default. The packages never write to the home directory during installation.
