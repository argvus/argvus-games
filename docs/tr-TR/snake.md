---
title: Snake
description: Retro ARGVUS terminal Yılan oyununu oynayın.
---

`argvus-game-snake`, terminal için retro bir Yılan oyunudur.
[ARGVUS Games](/docs/argvus-games/) meta paketinin bir parçasıdır.

## Installation

```sh
sudo pacman -S argvus-game-snake
```

`argvus-games` yüklemek, bu oyunu da yükler.

## Oyunu açmak

Terminalden şunu kullanarak açın:

```sh
argvus game-snake
```

Uygulama menüsü ayrıca bir `ARGVUS Snake` başlatıcı içerir. Başlatıcı
oyunu standart ARGVUS Kitty profili üzerinden ortalanmış yüzen bir
pencere boyutunda `1380x840`, Kontrol Merkezi ile eşleşiyor.

## Controls

Hareket bilerek standart Vi tuşlarını kullanır:

- `h`: left;
- `j`: down;
- `k`: up;
- `l`: right.

Oyun açıldığında, sağa hareket etmeye başlamak için `Enter` tuşuna basın veya o yönde hemen başlamak için `h`, `j`,
`k` veya `l` o yönde hemen başlamak için.

- `p` veya Space: duraklat ve devam ettir;
- `r`: Oyun Bitti sonrası yeniden başlat;
- `q` or Esc: quit.

## Rules

Yılan yemek yediğinde büyür. Duvara veya yılanın kendi vücuduna dokunmak
ends the round.

## Ranking

Yerel ilk-on sıralaması şurada saklanır
`$XDG_CONFIG_HOME/argvus/games/snake/ranking.json`, veya
`~/.config/argvus/games/snake/ranking.json` varsayılan olarak. Paket kurulumu
ana dizinde dosya oluşturmaz; dosya ilk kez oluşturulduğunda
a score is saved.
