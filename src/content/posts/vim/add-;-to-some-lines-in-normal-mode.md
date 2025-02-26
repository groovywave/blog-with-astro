
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]change-some-words-with-visual-mode-in-normal-mode'
pubDate: 2025-02-25
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---

```
change-some-words-with-visual-mode-in-normal-mode
Copy and paste the below text and type some commands like below.

---
1. /TIP 2 6 1 <CR> <Esc>
2. A; <Esc>
2. jVG              (select with visual mode)
3. :normal . <CR>   (add ;)
---
const foo = TIP261
const bar = "a"
const foo = foo 
const foobar = foo + bar
const footer = foo + ter
