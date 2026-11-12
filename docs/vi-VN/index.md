---
title: Trò chơi
description: Cài đặt và chơi các trò chơi ARGVUS chính thức.
---

ARGVUS Games là gói tổng hợp cho các trò chơi ARGVUS chính thức. Nó không cung cấp mã trò chơi
riêng: việc cài đặt nó sẽ cài đặt tất cả các gói trò chơi trong bộ chính thức,
cùng cách mà gói meta `argvus-themes` cài đặt các chủ đề chính thức.

Kho lưu trữ này là nơi duy nhất cho tất cả tài liệu trò chơi ARGVUS.

## Cài đặt

Cài đặt mọi trò chơi chính thức:

```sh
sudo pacman -S argvus-games
```

Cài đặt một trò chơi duy nhất:

```sh
sudo pacman -S argvus-game-snake
```

Việc cài đặt một gói trò chơi không thay đổi phiên làm việc, chủ đề hoặc
hình nền của bạn, và không tạo tệp trong thư mục chính của bạn.

## Các trò chơi có sẵn

| Trò chơi | Trọn gói | Lệnh | Trang |
| --- | --- | --- | --- |
 for the installed and user paths.[Snake](/docs/argvus-games/snake/) |

## Điều khiển bằng bàn phím

Các trò chơi tuân theo mô hình bàn phím trước ARGVUS. Snake sử dụng các phím di chuyển Vi
 `argvus-game-snake`  `argvus game-snake` `h`, `j`, `k` và `l`, và mỗi trang trò chơi liệt kê các điều khiển của nó.

## Dữ liệu cục bộ

Các trò chơi lưu dữ liệu của chúng trong thư mục cấu hình XDG của người dùng, ví dụ
`$XDG_CONFIG_HOME/argvus/games/snake/`, hoặc `~/.config/argvus/games/snake/` theo
mặc định. Các gói phần mềm không bao giờ ghi vào thư mục chính trong quá trình cài đặt.
