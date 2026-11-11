---
title: Games
description: Instal dan mainkan game resmi ARGVUS.
---

ARGVUS Games adalah meta-paket untuk game resmi ARGVUS. Paket ini tidak menyertakan kode game
sendiri: menginstalnya akan menginstal setiap paket game dalam set resmi,
dengan cara yang sama paket meta `argvus-themes` menginstal tema resmi.

Repositori ini adalah satu-satunya tempat untuk semua dokumentasi game ARGVUS.

## Installation

Instal setiap game resmi:

```sh
sudo pacman -S argvus-games
```

Install a single game:

```sh
sudo pacman -S argvus-game-snake
```

Menginstal paket game tidak mengubah sesi Anda, tema Anda, atau
wallpaper Anda, dan tidak membuat file di direktori home Anda.

## Permainan yang tersedia

| Game | Package | Command | Page |
| --- | --- | --- | --- |
 for the installed and user paths.[Snake](/docs/argvus-games/snake/) |

## Kontrol berbasis keyboard

Permainan mengikuti model ARGVUS berbasis keyboard. Snake menggunakan tombol gerakan Vi
 `argvus-game-snake`  `argvus game-snake` `h`, `j`, `k`, dan `l`, dan setiap halaman permainan mencantumkan kontrolnya.

## Data lokal

Game menyimpan data mereka di direktori konfigurasi XDG pengguna, misalnya
`$XDG_CONFIG_HOME/argvus/games/snake/`, atau `~/.config/argvus/games/snake/` secara default oleh
. Paket-paket tersebut tidak pernah menulis ke direktori home selama instalasi.
