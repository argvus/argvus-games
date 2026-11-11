---
title: Snake
description: Chơi trò chơi rắn trên terminal ARGVUS cổ điển.
---

`argvus-game-snake` là một trò chơi Rắn cổ điển cho terminal. Nó là một phần của
[ARGVUS Games](/docs/argvus-games/) gói siêu dữ liệu.

## Installation

```sh
sudo pacman -S argvus-game-snake
```

Cài đặt `argvus-games` cũng cài đặt trò chơi này.

## Mở trò chơi

Mở nó từ một terminal với:

```sh
argvus game-snake
```

Menu ứng dụng cũng chứa một trình khởi chạy `ARGVUS Snake`. Trình khởi chạy
mở trò chơi thông qua hồ sơ ARGVUS Kitty tiêu chuẩn trong một cửa sổ nổi ở giữa
cửa sổ kích thước `1380x840`, phù hợp với Trung tâm Điều khiển.

## Controls

Di chuyển cố ý sử dụng các phím Vi tiêu chuẩn:

- `h`: left;
- `j`: down;
- `k`: up;
- `l`: right.

Khi trò chơi mở, nhấn `Enter` để bắt đầu di chuyển sang phải, hoặc nhấn `h`, `j`,
`k` hoặc `l` để bắt đầu ngay lập tức theo hướng đó.

- `p` hoặc Dấu cách: tạm dừng và tiếp tục;
- `r`: khởi động lại sau khi Kết thúc Trò chơi;
- `q` or Esc: quit.

## Rules

Con rắn sẽ lớn lên khi nó ăn thức ăn. Chạm vào tường hoặc vào cơ thể của chính con rắn
ends the round.

## Ranking

Bảng xếp hạng mười người chơi hàng đầu cục bộ được lưu trong
`$XDG_CONFIG_HOME/argvus/games/snake/ranking.json`, hoặc
`~/.config/argvus/games/snake/ranking.json` theo mặc định. Cài đặt gói
không tạo tệp trong thư mục chính; tệp được tạo lần đầu tiên
a score is saved.
