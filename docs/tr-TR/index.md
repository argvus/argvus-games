---
title: Games
description: Resmi ARGVUS oyunlarını yükleyin ve oynayın.
---

ARGVUS Oyunları, resmi ARGVUS oyunları için meta-pakettir. Kendi oyunu yoktur
: onu yüklemek, resmi setteki her oyun paketini yükler,
`argvus-themes` meta paketi resmi temaları kurduğu şekilde.

Bu depo, tüm ARGVUS oyun dokümantasyonunun tek adresidir.

## Installation

Her resmi oyunu yükleyin:

```sh
sudo pacman -S argvus-games
```

Install a single game:

```sh
sudo pacman -S argvus-game-snake
```

Bir oyun paketinin kurulması, oturumunuzu, temanızı veya
duvar kağıdınızı değiştirmez ve ev dizininizde dosya oluşturmaz.

## Mevcut oyunlar

| Game | Package | Command | Page |
| --- | --- | --- | --- |
 for the installed and user paths.[Snake](/docs/argvus-games/snake/) |

## Klavye öncelikli kontroller

Oyunlar ARGVUS klavye öncelikli modelini takip eder. Snake, Vi hareket
tuşlarını  `argvus-game-snake`  `argvus game-snake` `h`, `j`, `k` ve `l` kullanır ve her oyun sayfası kontrol tuşlarını listeler.

## Yerel veriler

Oyunlar, verilerini kullanıcının XDG yapılandırma dizininde saklar, örneğin
`$XDG_CONFIG_HOME/argvus/games/snake/` veya `~/.config/argvus/games/snake/`,
varsayılan olarak. Paketler kurulurken asla ev dizinine yazmaz.
