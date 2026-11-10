---
title: Jeux
description: Installez et jouez aux jeux officiels ARGVUS.
---
ARGVUS Games est le méta-paquet pour les jeux officiels ARGVUS. Il ne contient aucun code de jeu propre : l’installer installe tous les paquets de jeux du lot officiel, de la même manière que le méta-paquet `argvus-themes` installe les thèmes officiels.

Ce dépôt est le seul endroit pour toute la documentation des jeux ARGVUS.

## Installation

Installez tous les jeux officiels :

```sh
sudo pacman -S argvus-games
```
Installer un seul jeu :

```sh
sudo pacman -S argvus-game-snake
```
L'installation d'un package de jeu ne change pas votre session, votre thème ou votre fond d'écran, et ne crée pas de fichiers dans votre répertoire personnel.

## Jeux disponibles

| Jeu | Package | Commande | Page |
| --- | --- | --- | --- |
| Snake | `argvus-game-snake` | `argvus game-snake` | [Snake](/docs/argvus-games/snake/) |

## Contrôles prioritairement au clavier

Les jeux suivent le modèle ARGVUS axé sur le clavier. Snake utilise les touches de déplacement Vi `h`, `j`, `k` et `l`, et chaque page de jeu liste ses contrôles.

## Données locales

Les jeux conservent leurs données dans le répertoire de configuration XDG de l'utilisateur, par exemple `$XDG_CONFIG_HOME/argvus/games/snake/`, ou `~/.config/argvus/games/snake/` par défaut. Les packages n'écrivent jamais dans le répertoire personnel lors de l'installation.
