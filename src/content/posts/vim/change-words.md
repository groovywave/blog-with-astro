
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]Change words'
pubDate: 2025-02-25
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---

```
change words
Copy and paste the below text and type some commands like below.

---
1. /tip <CR> <Esc>     (search tip)
2. <C-q> jje           (select with visual block mode)
3. c components <Esc>  (CHANGE WORDS)
---
li.one   a{ background-image: url('/TIPTIP/sprite.png'); }
li.two   a{ background-image: url('/images/sprite.png'); }
li.three a{ background-image: url('/images/sprite.png'); }
TIP25
