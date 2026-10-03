---
title: Jogos
description: Instale e jogue os jogos oficiais do ARGVUS.
---

O ARGVUS Games é o metapacote dos jogos oficiais do ARGVUS. Ele não traz código
de jogo próprio: ao instalá-lo, são instalados todos os pacotes de jogos do
conjunto oficial, da mesma forma que o metapacote `argvus-themes` instala os
temas oficiais.

Este repositório é o local único de toda a documentação de jogos do ARGVUS.

## Instalação

Instale todos os jogos oficiais:

```sh
sudo pacman -S argvus-games
```

Instale um único jogo:

```sh
sudo pacman -S argvus-game-snake
```

Instalar um pacote de jogo não altera a sua sessão, o seu tema nem o seu
wallpaper, e não cria arquivos na sua pasta pessoal.

## Jogos disponíveis

| Jogo | Pacote | Comando | Página |
| --- | --- | --- | --- |
| Snake | `argvus-game-snake` | `argvus game-snake` | [Snake](/pt/docs/argvus-games/snake/) |

## Controles pelo teclado

Os jogos seguem o modelo do ARGVUS, em que tudo funciona pelo teclado. O Snake
usa as teclas de movimentação do Vi `h`, `j`, `k` e `l`, e cada página de jogo
lista os seus controles.

## Dados locais

Os jogos guardam os seus dados no diretório de configuração XDG do usuário, por
exemplo `$XDG_CONFIG_HOME/argvus/games/snake/`, ou
`~/.config/argvus/games/snake/` por padrão. Os pacotes nunca gravam na pasta
pessoal durante a instalação.
