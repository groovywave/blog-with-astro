
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]Edit a macro'
pubDate: 2025-02-11
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---


```
Edit a macro
Copy and paste the below text and type some commands like below.

---
/tip <CR>       (Serch tip)
qq yyp q   　   (Record macro yyp into register q)
u
:put q <CR>　   (PASTE REGISTERED THE MACRO)
A p <Esc>　　   (EDIT THE MACRO)
V"qy            (RERECORD THE EDITED COMMAND INTO REGISTER q  )
uu 
@q              (Run registered macro q)
---
tip71
```
