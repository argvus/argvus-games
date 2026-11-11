---
title: Snake
description: রেট্রো ARGVUS টার্মিনাল স্নেক গেম খেলুন।
---

`argvus-game-snake` হল টার্মিনালের জন্য একটি রেট্রো স্নেক গেম। এটি
[ARGVUS Games](/docs/argvus-games/) মেটা-প্যাকেজের অংশ।

## Installation

```sh
sudo pacman -S argvus-game-snake
```

`argvus-games` ইনস্টল করা এই খেলাটিও ইনস্টল করে।

## খেলা খোলা

একটি টার্মিনাল থেকে এটি খুলুন:

```sh
argvus game-snake
```

অ্যাপ্লিকেশন মেনুতেও একটি `ARGVUS Snake` লঞ্চার রয়েছে। লঞ্চার
মানক ARGVUS Kitty প্রোফাইলের মাধ্যমে কেন্দ্রীভূত ফ্লোটিং-এ
উইন্ডো আকারের `1380x840`, কন্ট্রোল সেন্টারের সাথে মিল রেখে।

## Controls

মোশন ইচ্ছাকৃতভাবে স্ট্যান্ডার্ড Vi কী ব্যবহার করে:

- `h`: left;
- `j`: down;
- `k`: up;
- `l`: right.

When the game opens, press 

 to start moving right, or press 

, `Enter`,
`h` k  `j`  অথবা  `k` `l` নির্দিষ্ট দিক থেকে অবিলম্বে শুরু করতে।

- `p` অথবা স্পেস: বিরতি এবং পুনরায় শুরু;
- `r`: গেম ওভার-এর পর পুনরায় শুরু;
- `q` or Esc: quit.

## Rules

সাপ খাবার খেলে বাড়ে। দেয়াল বা সাপের নিজস্ব দেহ স্পর্শ করা
ends the round.

## Ranking

স্থানীয় শীর্ষ দশ র‌্যাঙ্কিং সংরক্ষণ করা হয়
`$XDG_CONFIG_HOME/argvus/games/snake/ranking.json`, অথবা
ডিফল্টভাবে `~/.config/argvus/games/snake/ranking.json`। প্যাকেজ ইনস্টলেশন
হোম ডিরেক্টরিতে ফাইল তৈরি করে না; ফাইলটি প্রথমবার তৈরি হয়
a score is saved.
