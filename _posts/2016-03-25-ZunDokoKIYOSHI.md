---
layout: post
title: ズンドコキヨシ
tags: xDNCL PEN
---

* ズンドコキヨシまとめ - Qiita
    * [http://qiita.com/shunsugai@github/items/971a15461de29563bf90](http://qiita.com/shunsugai@github/items/971a15461de29563bf90)

少し前に流行っていたズンドコキヨシのプログラムを xDNCL で書いてみた。

## プログラム

```
整数 i, f

f ← 0

ずっと，
  | i ← random(1)
  | もし i = 0 ならば
  |   | 「ズン 」を改行なしで表示する
  |   | f ← f + 1
  | を実行し，そうでなければ
  |   | 「ドコ 」を改行なしで表示する
  |   | もし f >= 4 ならば
  |   |   | 繰り返しを抜ける
  |   | を実行し，そうでなければ
  |   |   | f ← 0
  |   | を実行する
  | を実行する
を繰り返す

「キ・ヨ・シ！」を表示する
```

## PENで実行

![ズンドコキヨシ](https://xdncl.github.io/blog/assets/img/20160325.png)