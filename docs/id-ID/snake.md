---
title: Ular
description: Mainkan permainan Snake terminal ARGVUS retro.
---

`argvus-game-snake` adalah permainan Snake retro untuk terminal. Ini adalah bagian dari paket meta
[ARGVUS Games](/docs/argvus-games/).

## Instalasi

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

## Kontrol

Gerakan sengaja menggunakan tombol Vi standar:

- `h`: kiri;
- `j`: turun;
- `k`: naik;
- `l`: benar.

Saat permainan terbuka, tekan `Enter` untuk mulai bergerak ke kanan, atau tekan `h`, `j`,
`k` atau `l` untuk langsung memulai ke arah itu.

- `p` atau Spasi: jeda dan lanjutkan;
- `r`: mulai ulang setelah Permainan Berakhir;
- `q` atau Esc: keluar.

## Aturan

Ular akan tumbuh saat makan makanan. Menyentuh dinding atau tubuh ular itu sendiri
mengakhiri putaran.

## Peringkat

Peringkat sepuluh besar lokal disimpan dalam
`$XDG_CONFIG_HOME/argvus/games/snake/ranking.json`, atau
`~/.config/argvus/games/snake/ranking.json` secara default. Instalasi paket
tidak membuat file di direktori home; file dibuat pertama kali
skor disimpan.
