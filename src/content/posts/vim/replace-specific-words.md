
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]Replace specific words
'
pubDate: 2025-02-23
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---


```
Replace Search specific words
Copy and paste the below text and type some commands like below.

---     
1. /saaaa <CR>     (search saaaa)
2. cwsea <Esc>     (change the words)
3. n . n .         (change the words)
4. /I <CR><Esc>    (search the she)
5. vwe <CR><Esc>   (hightlight she sells)
6. c I sell <Esc>  (change the words)
7. /I <CR><Esc>    (search the she)
7. vwe*            (search the she)
8. . n .           (next)
---
I sell sea shells by the sea shore
I sell sea shells by the sea shore
I sell sea shells by the sea shore
I sell sea ahells by the sea shore
```
