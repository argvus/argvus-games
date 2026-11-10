---
title: Serpent
description: Jouez au jeu de serpent rétro du terminal ARGVUS.
---
`argvus-game-snake` est un jeu Snake rétro pour le terminal. Il fait partie du
[ARGVUS Games](/docs/argvus-games/) méta-package.

## Installation

```sh
sudo pacman -S argvus-game-snake
```
L'installation de `argvus-games` installe également ce jeu.

## Ouverture du jeu

Ouvrez-le depuis un terminal avec :

```sh
argvus game-snake
```
Le menu de l'application contient également un lanceur `ARGVUS Snake`. Le lanceur
ouvre le jeu via le profil standard ARGVUS Kitty dans un flottant centré
taille de fenêtre `1380x840`, correspondant au centre de contrôle.

## Contrôles

Le mouvement utilise délibérément les touches Vi standards :

- `h` : gauche ;
- `j` : vers le bas ;
- `k` : vers le haut ;
- `l` : à droite.

Lorsque le jeu s'ouvre, appuyez sur `Enter` pour commencer à vous déplacer vers la droite, ou appuyez sur `h`, `j`,
`k` ou `l` pour démarrer immédiatement dans cette direction.

- `p` ou Espace : pause et reprise ;
- `r` : redémarrage après Game Over ;
- `q` ou Esc : quitter.

## Règles

Le serpent grandit lorsqu’il mange de la nourriture. Toucher le mur ou le corps du serpent
termine le tour.

## Classement

Le classement local des dix premiers est stocké dans
`$XDG_CONFIG_HOME/argvus/games/snake/ranking.json`, ou
`~/.config/argvus/games/snake/ranking.json` par défaut. Installation du paquet
ne crée pas de fichiers dans le répertoire personnel ; le fichier est créé la première fois
une partition est enregistrée.
