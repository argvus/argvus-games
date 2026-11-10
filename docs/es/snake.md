---
title: Serpiente
description: Juega al juego de la serpiente en el terminal retro ARGVUS.
---
`argvus-game-snake` es un juego retro de Snake para el terminal. Es parte del paquete meta [ARGVUS Games](/docs/argvus-games/).

## Instalación

```sh
sudo pacman -S argvus-game-snake
```
Instalar `argvus-games` también instala este juego.

## Abrir el juego

Ábrelo desde un terminal con:

```sh
argvus game-snake
```
El menú de la aplicación también contiene un iniciador `ARGVUS Snake`. el lanzador
abre el juego a través del perfil estándar de ARGVUS Kitty en un flotante centrado
tamaño de ventana `1380x840`, que coincide con el Centro de control.

## Controles

El movimiento utiliza deliberadamente las teclas Vi estándar:

- `h`: izquierda;
- `j`: abajo;
- `k`: arriba;
- `l`: derecha.

Cuando se abra el juego, presiona `Enter` para comenzar a moverte hacia la derecha, o presiona `h`, `j`,
`k` o `l` para comenzar inmediatamente en esa dirección.

- `p` o Espacio: pausar y reanudar;
- `r`: reinicio después del fin del juego;
- `q` o Esc: salir.

## Reglas

La serpiente crece cuando come. Tocar la pared o el propio cuerpo de la serpiente.
termina la ronda.

## Clasificación

El ranking local de los diez primeros se almacena en
`$XDG_CONFIG_HOME/argvus/games/snake/ranking.json`, o
`~/.config/argvus/games/snake/ranking.json` de forma predeterminada. Instalación del paquete
no crea archivos en el directorio de inicio; el archivo se crea la primera vez
se guarda una puntuación.
