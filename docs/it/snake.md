---
title: Serpente
description: Gioca al gioco Snake del terminale retro ARGVUS.
---
`argvus-game-snake` è un gioco Snake retrò per il terminale. Fa parte del
[ARGVUS Games](/docs/argvus-games/) meta-package.

## Installazione

```sh
sudo pacman -S argvus-game-snake
```
L'installazione di `argvus-games` installa anche questo gioco.

## Apertura del gioco

Aprilo da un terminale con:

```sh
argvus game-snake
```
Il menu dell'applicazione contiene anche un launcher `ARGVUS Snake`. The launcher
apre il gioco attraverso il profilo standard ARGVUS Kitty in un movimento centrato
finestra di dimensioni `1380x840`, corrispondente al Centro di controllo.

## Controls

Il movimento utilizza deliberatamente i tasti Vi standard:

- `h`: left;
- `j`: down;
- `k`: up;
- `l`: giusto.

Quando il gioco si apre, premi `Enter` per iniziare a muoverti verso destra, oppure premi `h`, `j`,
`k` o `l` per iniziare subito in quella direzione.

- `p` o Spazio: pausa e ripresa;
- `r`: riavvio dopo Game Over;
- `q` o Esc: esci.

## Rules

Il serpente cresce quando mangia il cibo. Toccando il muro o il corpo stesso del serpente
ends the round.

## Ranking

La classifica dei primi dieci locali è archiviata
`$XDG_CONFIG_HOME/argvus/games/snake/ranking.json`, or
`~/.config/argvus/games/snake/ranking.json` per impostazione predefinita. Package installation
non crea file nella directory home; il file viene creato la prima volta
a score is saved.
