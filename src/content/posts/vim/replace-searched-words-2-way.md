
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]Replace searched words'
pubDate: 2025-02-23
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
1. /saa <CR> <Esc>        (search saaaa)
2. cwsea <Esc>            (change the word)
3. n . n . n . <Esc>      (jump to next words and change the words)
4. /I <CR><Esc>           (search the she)
5. ve* <CR><Esc>          (hightlight she sells)
6. <C-o>                  (jump to previous position)
6. ve c She sells <Esc>   (change the words)
8. n . n . n .            (next)
---
I sell saaaa shells by the saaaa shore
I sell saaaa ahells by the saaaa shore
```
