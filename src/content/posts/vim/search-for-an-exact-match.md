
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]Search for an exact match'
pubDate: 2025-02-16
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---


```
Search for an exact match
copy and paste the below text and type some commands like below.

---
1. /\v<and> <CR>3dd
  (/\v search very magic mode)
  (<and> searches for the exact word 'and', without matching words like 'ander'  )
---
and
ander
andoroid
```

