
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]Search for repeated consecutive words.'
pubDate: 2025-02-13
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---


```
Search for repeated consecutive words.
copy and paste the below text and type some commands like below.

---
1. /\v<(\w+)\_s+\1> <CR>    (search like so so)
2. n n n 

  ( /\v search with very macig mode that ignore escape sequance)
  ( < means the start of a word, and > means the end of a word )
  ( \w+ matches one or more consecutive word characters (no spaces))
  ( \_s+ matches one or more whitespace characters, including newlines)
  ( \1 matches captured value)
---

love love love
I I
You 
You

```

