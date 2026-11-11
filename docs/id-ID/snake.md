---
title: Snake
description: Mainkan permainan Snake terminal ARGVUS retro.
---

`argvus-game-snake` adalah permainan Snake retro untuk terminal. Ini adalah bagian dari paket meta
[ARGVUS Games](/docs/argvus-games/).

## Installation

```sh
sudo pacman -S argvus-game-snake
```

Menginstal `argvus-games` juga menginstal game ini.

## Membuka game

Buka dari terminal dengan:

```sh
argvus game-snake
```

Menu aplikasi juga berisi peluncur `ARGVUS Snake`. Peluncur
membuka game melalui profil Kitty ARGVUS standar dalam
jendela berukuran `1380x840`, sesuai dengan Pusat Kontrol.

## Controls

Gerakan sengaja menggunakan tombol Vi standar:

- `h`: left;
- `j`: down;
- `k`: up;
- `l`: right.

Saat permainan terbuka, tekan `Enter` untuk mulai bergerak ke kanan, atau tekan `h`, `j`,
`k` atau `l` untuk langsung memulai ke arah itu.

- `p` atau Spasi: jeda dan lanjutkan;
- `r`: mulai ulang setelah Permainan Berakhir;
- `q` or Esc: quit.

## Rules

Ular akan tumbuh saat makan makanan. Menyentuh dinding atau tubuh ular itu sendiri
ends the round.

## Ranking

Peringkat sepuluh besar lokal disimpan dalam
`$XDG_CONFIG_HOME/argvus/games/snake/ranking.json`, atau
`~/.config/argvus/games/snake/ranking.json` secara default. Instalasi paket
tidak membuat file di direktori home; file dibuat pertama kali
a score is saved.
