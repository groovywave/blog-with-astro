
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]copy with register'
pubDate: 2025-02-25
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---

```
with register
Copy and paste the below text and type some commands like below.

---
1. /coll <CR> 
2. "ayiw        (yank in word to register a)
3. /targ        (search targ) 
4. diw          (delete in word)
5. "aP          (pasete before register a)
---
TIP595 collection = getCollection();
process(somethingInTheWay, target)
