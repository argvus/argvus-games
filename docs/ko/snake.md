---
title: 뱀
description: 레트로 ARGVUS 터미널 스네이크 게임을 플레이하세요.
---
`argvus-game-snake`는 터미널용 레트로 스네이크 게임입니다. 이 게임은 [ARGVUS Games](/docs/argvus-games/) 메타 패키지의 일부입니다.

## 설치

```sh
sudo pacman -S argvus-game-snake
```
`argvus-games`를 설치하면 이 게임도 설치됩니다.

## 게임 실행

터미널에서 다음 명령어로 실행하세요:

```sh
argvus game-snake
```
응용 프로그램 메뉴에는 `ARGVUS Snake` 실행 프로그램도 포함되어 있습니다. 런처
중앙에 떠 있는 표준 ARGVUS Kitty 프로필을 통해 게임을 엽니다.
창 크기는 `1380x840`이며 제어 센터와 일치합니다.

## 컨트롤

움직임은 의도적으로 표준 Vi 키를 사용합니다.

- `h`: 왼쪽;
- `j`: 다운;
- `k`: 위로;
- `l`: 그렇죠.

게임이 열리면 `Enter`를 눌러 오른쪽으로 이동하거나 `h`, `j`를 누르세요.
`k` 또는 `l` 해당 방향으로 즉시 시작합니다.

- `p` 또는 스페이스바: 일시 정지 및 재개;
- `r`: 게임 오버 후 다시 시작;
- `q` 또는 Esc: 종료합니다.

## 규칙

뱀은 음식을 먹으면 성장합니다. 벽이나 뱀의 몸을 만지는 행위
라운드를 종료합니다.

##랭킹

지역 상위 10위 순위는 다음 위치에 저장됩니다.
`$XDG_CONFIG_HOME/argvus/games/snake/ranking.json` 또는
기본적으로 `~/.config/argvus/games/snake/ranking.json`입니다. 패키지 설치
홈 디렉토리에 파일을 생성하지 않습니다. 파일이 처음 생성되었을 때
점수가 저장됩니다.
