
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]increment number'
pubDate: 2025-02-24
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---


```
increment number
Copy and paste the below text and type some commands like below.

---
1. /pos <CR> <Esc> 
2. 10 <C-a>                      (add 10)
3. w                             (move to next word) 
4. 10 <C-a>                      (ADD 10)
4. j                             (move to next row) 
5. <C-a> <C-a> <C-a> <C-a>       (ADD  4)
5. yyp                           (yank row and paste)
6. 0                             (jump to head)
7. cW .news <Esc>                (change word to .news)
8. 180<C-x>                      (SUBTRACT 180)
---
.blog, .news { background-image: url(/spritepng); }
.TIP101 { background-position: 20px 13px }
.news { background-position: 0px 0px }
.news { background-position: 0px 0px }
TIP10
```
