---
title: Giochi
description: Installa e gioca ai giochi ufficiali di ARGVUS.
---
ARGVUS Games è il meta-pacchetto per i giochi ufficiali ARGVUS. Non include alcun codice di gioco proprio: installandolo si installano tutti i pacchetti di giochi del set ufficiale, nello stesso modo in cui il meta-pacchetto `argvus-themes` installa i temi ufficiali.

Questo repository è l'unica sede per tutta la documentazione dei giochi ARGVUS.

## Installazione

Installa ogni gioco ufficiale:

```sh
sudo pacman -S argvus-games
```
Installa un singolo gioco:

```sh
sudo pacman -S argvus-game-snake
```
L'installazione di un pacchetto di gioco non modifica la tua sessione, il tuo tema o il tuo sfondo, e non crea file nella tua directory home.

## Giochi disponibili

| Gioco | Pacchetto | Comando | Pagina |
| --- | --- | --- | --- |
| Snake | `argvus-game-snake` | `argvus game-snake` | [Snake](/docs/argvus-games/snake/) |

## Controlli da tastiera prioritari

I giochi seguono il modello da tastiera-prima ARGVUS. Snake usa i tasti di movimento Vi `h`, `j`, `k` e `l`, e ogni pagina del gioco elenca i suoi comandi.

## Dati locali

I giochi conservano i loro dati nella directory di configurazione XDG dell'utente, per esempio `$XDG_CONFIG_HOME/argvus/games/snake/`, o `~/.config/argvus/games/snake/` per impostazione predefinita. I pacchetti non scrivono mai nella directory home durante l'installazione.
