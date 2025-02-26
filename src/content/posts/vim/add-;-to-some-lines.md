
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]change-some-words-with-visual-mode'
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
1. /TIP 2 6 1 <CR> <Esc>
2. j <C-q> j$ (select with visual mode <C-q> or <C-v>)
3. A; <Esc>  (add ;)
---
const foo = TIP261;
const bar = "a"
const footer = foo + bar
