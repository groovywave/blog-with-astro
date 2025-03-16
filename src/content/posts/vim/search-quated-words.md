
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]Search quated words like "word"'
pubDate: 2025-02-14
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---


```
Search quated words
Copy and paste the below text and type some commands like below.

---
1. /\v'([^']|'\w)+'

  (/\v search very magic mode)
  (/\v search single quated word include like 'it's me')
 
'quated' andoroid
'two' quated 'words'
'two'quated'words'
'it's me'
TIP85
```
