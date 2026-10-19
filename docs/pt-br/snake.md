---
title: Snake
description: Jogue o Snake retro do ARGVUS no terminal.
---

O `argvus-game-snake` é um jogo Snake retro para o terminal. Ele faz parte do
metapacote [Jogos do ARGVUS](/pt/docs/argvus-games/).

## Instalação

```sh
sudo pacman -S argvus-game-snake
```

Instalar o `argvus-games` instala este jogo também.

## Abrindo o jogo

Abra-o em um terminal com:

```sh
argvus game-snake
```

O menu de aplicativos também contém o lançador `Snake ARGVUS`. O lançador abre
o jogo pelo perfil padrão do Kitty do ARGVUS em uma janela flutuante centralizada
de `1380x840`, igual à Central de Controle.

## Controles

A movimentação usa de propósito as teclas padrão do Vi:

* `h`: esquerda;
* `j`: baixo;
* `k`: cima;
* `l`: direita.

Quando o jogo abrir, pressione `Enter` para começar movendo para a direita, ou
pressione `h`, `j`, `k` ou `l` para começar imediatamente nessa direção.

* `p` ou Espaço: pausar e retomar;
* `r`: reiniciar após o fim de jogo;
* `q` ou Esc: sair.

## Regras

A minhoca cresce ao comer a comida. Encostar na parede ou no próprio corpo
encerra a rodada.

## Ranking

O ranking local com as dez melhores pontuações fica em
`$XDG_CONFIG_HOME/argvus/games/snake/ranking.json`, ou em
`~/.config/argvus/games/snake/ranking.json` por padrão. A instalação do pacote
não cria arquivos na pasta pessoal; o arquivo é criado na primeira vez em que
uma pontuação é salva.
