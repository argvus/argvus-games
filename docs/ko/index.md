---
title: 게임
description: 공식 ARGVUS 게임을 설치하고 플레이하세요.
---
ARGVUS 게임은 공식 ARGVUS 게임의 메타 패키지입니다. 자체 게임 코드는 포함되어 있지 않으며, 설치 시 공식 세트의 모든 게임 패키지가 설치됩니다. 이는 `argvus-themes` 메타 패키지가 공식 테마를 설치하는 방식과 동일합니다.

이 저장소는 모든 ARGVUS 게임 문서의 단일 홈입니다.

## 설치

모든 공식 게임을 설치하세요:

```sh
sudo pacman -S argvus-games
```
단일 게임 설치:

```sh
sudo pacman -S argvus-game-snake
```
게임 패키지를 설치해도 세션, 테마 또는 배경화면은 변경되지 않으며, 홈 디렉토리에 파일이 생성되지 않습니다.

## 사용 가능한 게임

| 게임 | 패키지 | 명령 | 페이지 |
| --- | --- | --- | --- |
| 스네이크 | `argvus-game-snake` | `argvus game-snake` | [스네이크 ](/docs/argvus-games/snake/) |

## 키보드 우선 조작

게임은 ARGVUS 키보드 우선 모델을 따릅니다. 스네이크는 Vi 이동 키 `h`, `j`, `k`, `l`를 사용하며, 모든 게임 페이지에는 조작법이 나와 있습니다.

## 로컬 데이터

게임은 사용자의 XDG 설정 디렉토리에 데이터를 저장하며, 예를 들어 `$XDG_CONFIG_HOME/argvus/games/snake/` 또는 기본적으로 `~/.config/argvus/games/snake/`에 저장됩니다. 패키지는 설치 중에 홈 디렉토리에 절대 쓰기를 하지 않습니다.
