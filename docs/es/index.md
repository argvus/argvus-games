---
title: Juegos
description: Instala y juega los juegos oficiales de ARGVUS.
---
ARGVUS Games es el meta-paquete para los juegos oficiales de ARGVUS. No incluye código de juego propio: al instalarlo se instalan todos los paquetes de juegos del conjunto oficial, de la misma manera que el meta-paquete `argvus-themes` instala los temas oficiales.

Este repositorio es el único hogar para toda la documentación de los juegos de ARGVUS.

## Instalación

Instala todos los juegos oficiales:

```sh
sudo pacman -S argvus-games
```
Instalar un solo juego:

```sh
sudo pacman -S argvus-game-snake
```
Instalar un paquete de juego no cambia tu sesión, tu tema ni tu fondo de pantalla, y no crea archivos en tu directorio personal.

## Juegos disponibles

| Juego | Paquete | Comando | Página |
| --- | --- | --- | --- |
| Serpiente | `argvus-game-snake` | `argvus game-snake` | [Serpiente](/docs/argvus-games/snake/) |

## Controles centrados en el teclado

Los juegos siguen el modelo de teclado primero ARGVUS. Snake utiliza las teclas de movimiento de Vi `h`, `j`, `k` y `l`, y cada página de juego lista sus controles.

## Datos locales

Los juegos guardan sus datos en el directorio de configuración XDG del usuario, por ejemplo `$XDG_CONFIG_HOME/argvus/games/snake/`, o `~/.config/argvus/games/snake/` por defecto. Los paquetes nunca escriben en el directorio personal durante la instalación.
