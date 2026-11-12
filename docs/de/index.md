---
title: Spiele
description: Installieren und spielen Sie die offiziellen ARGVUS-Spiele.
---
ARGVUS Games ist das Meta-Paket für die offiziellen ARGVUS-Spiele. Es enthält keinen eigenen Spielcode: Wird es installiert, werden alle Spielpakete des offiziellen Sets installiert, genauso wie das Meta-Paket `argvus-themes` die offiziellen Themen installiert.

Dieses Repository ist die einzige Anlaufstelle für alle ARGVUS-Spiel-Dokumentationen.

## Installation

Installiere jedes offizielle Spiel:

```sh
sudo pacman -S argvus-games
```
Ein einzelnes Spiel installieren:

```sh
sudo pacman -S argvus-game-snake
```
Die Installation eines Spielpakets ändert Ihre Sitzung, Ihr Thema oder Ihren Hintergrund nicht und erstellt auch keine Dateien in Ihrem Home-Verzeichnis.

## Verfügbare Spiele

| Spiel | Paket | Befehl | Seite |
| --- | --- | --- | --- |
| Schlange | `argvus-game-snake` | `argvus game-snake` | [Schlange](/docs/argvus-games/snake/) |

## Tastaturbasierte Steuerung

Die Spiele folgen dem ARGVUS-Tastatur-zuerst-Modell. Snake verwendet die Vi-Bewegungstasten `h`, `j`, `k` und `l`, und jede Spieleseite listet ihre Steuerung auf.

## Lokale Daten

Spiele speichern ihre Daten im XDG-Konfigurationsverzeichnis des Benutzers, zum Beispiel `$XDG_CONFIG_HOME/argvus/games/snake/` oder standardmäßig `~/.config/argvus/games/snake/`. Die Pakete schreiben während der Installation nie ins Home-Verzeichnis.
