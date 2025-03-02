
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]search and change words in tag'
pubDate: 2025-02-24
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---


```
search and change words
Copy and paste the below text and type some commands like below.

---
1. /origin <CR> /jump <CR> <Esc>
2. ''                      (jump to origin)
3. /change <CR> V U <Esc>
4. /jump <CR> '.               (jump and return to changed word)
5. /insert <CR> I insert <Esc>' 
6. /jump <CR> '^               (jump to changed word) 
5. /insert I insert /jump <CR> '^ <Esc>
6. /yank <CR> yy <Esc>
7. /jump <CR> '[ 　<Esc> '] <Esc>
8. /visual <CR> V
9. /jump <Esc> '> <Esc> '>
---
origin/
change
insertinsertinsert 
yank or change
visual
jump
jump again
```
