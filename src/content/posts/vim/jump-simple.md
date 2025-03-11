
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]jump simple'
pubDate: 2025-02-24
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---


```
jump simple
Copy and paste the below text and type some commands like below.

---
function add(a, b){]
  return a + b;
}
let i = 0;
3G   (jump to line 3)
/TIP　(search TIP)
?TIP　(search TIP)
(     (jump to previous sentence)
)
{    (jump to previous paragraph)
}
H,M,L　jump to high, middle, or low in window.
gf　　　カーソル位置の単語名称に合致する名称のファイルを開く
<C-]>　定義された単語位置から　function countNumber(){}等で定義した定義箇所にジャンプ
i += 1;
add(1, 2);
---
```
