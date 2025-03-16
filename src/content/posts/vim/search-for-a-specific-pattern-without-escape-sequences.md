
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]Search for a specific pattern without escape sequences'
pubDate: 2025-02-13
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---


```
Search for a specific pattern
copy and paste the below text and type some commands like below.

---
1. /\v#(\x{6}|\x{3}) <CR> (Search with very magic mode. You can serch without escape sequences.)
2. n n n

  ( In /\v search (very magic mode), you don't need to escape meta characters like |, so you can use them without \)
  (  #  search #)
  (  #  search #)
  ( (\x{6}|\x{3})   \x means hexadecimal, {6} means 6 characters, | means "or")
---
body   { color: #3c3c3c;}
a      { color: #0000EE;}
strong { color: #000;}

```

