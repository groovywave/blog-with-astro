
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]Edit a macro simple'
pubDate: 2025-02-11
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---


```
Edit a macro simple
Copy and paste the below text and type some commands like below.

---
qq yyp q  　   (Record yyp into register q)
:reg q <CR>    (SHOW MACRO q)
qQ ppp q       (ADD PPP ON MACRO q)
:reg q <CR>    (SHOW MACRO q)
---
```
