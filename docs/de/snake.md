---
title: Schlange
description: Spiele das Retro-ARGVUS-Terminal-Snake-Spiel.
---
`argvus-game-snake` ist ein Retro-Snake-Spiel für das Terminal. Es ist Teil des [ARGVUS Games](/docs/argvus-games/) Meta-Pakets.

## Installation

```sh
sudo pacman -S argvus-game-snake
```
Die Installation von `argvus-games` installiert auch dieses Spiel.

## Das Spiel starten

Öffnen Sie es von einem Terminal mit:

```sh
argvus game-snake
```
Das Anwendungsmenü enthält auch einen `ARGVUS Snake`-Launcher. Der Launcher
Öffnet das Spiel über das Standard-ARGVUS-Kitty-Profil in einem zentrierten Floating
Fenstergröße `1380x840`, passend zum Control Center.

## Steuerelemente

Movement nutzt bewusst die Standard-Vi-Tasten:

- `h`: links;
- `j`: unten;
- `k`: oben;
- `l`: richtig.

Wenn das Spiel beginnt, drücken Sie `Enter`, um mit der Bewegung nach rechts zu beginnen, oder drücken Sie `h`, `j`,
`k` oder `l`, um sofort in diese Richtung zu starten.

- `p` oder Leertaste: Pause und Fortfahren;
- `r`: Neustart nach Game Over;
- `q` oder Esc: beenden.

## Regeln

Die Schlange wächst, wenn sie Nahrung frisst. Berühren der Wand oder des eigenen Körpers der Schlange
beendet die Runde.

## Rangliste

Die lokale Top-Ten-Rangliste wird in gespeichert
`$XDG_CONFIG_HOME/argvus/games/snake/ranking.json`, oder
`~/.config/argvus/games/snake/ranking.json` standardmäßig. Paketinstallation
erstellt keine Dateien im Home-Verzeichnis; Die Datei wird beim ersten Mal erstellt
ein Punktestand wird gespeichert.
