
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]visual block'
pubDate: 2025-02-25
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---

```
change-some-words-with-visual-mode
Copy and paste the below text and type some commands like below.

---
1. /foo <CR> <Esc>  (search foo)
2. **<C-q>** $G     (select all with <C-q> or <C-v>)
3. A; <Esc>         (add ;)
---
const foo = "foo"
const bar = "a"
const footer = foo + bar
TIP26
