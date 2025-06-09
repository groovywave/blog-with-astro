
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[unix]if'
pubDate: 2025-05-13
description: 'unix'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["unix"]
---



```
if test -f test.txt
then
  echo "The file is exists"
else 
  echo "The file is not exists"
fi

-f 通常のファイルかどうか
-d ディレクトリかどうか
-e 存在するか
-r 読み込み可能か
-w 書き込み可能化
-x 実行可能か
```
