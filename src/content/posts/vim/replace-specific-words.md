
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]Replace quated words
'
pubDate: 2025-02-14
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---


```
Replace Search quated words
Copy and paste the below text and type some commands like below.

---
1. /saaaa <CR>   (search saaaa)
2. cwsea         (change the words)
3. /she <CR>     (search the she)
2. vwe* <CR>     (hightlight she sells)
2. cw I sell     (change the words)
3. n .           (next)
---
she sells saaaa shells by the saaaa shore
she sells saaaa ahells by the saaaa shore
```
