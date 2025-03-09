
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
1. /foo             (search foo)
2. A; <Esc>         (add ;)
2. jVG              (select the others)
3. :normal . <CR>   (add ; again in normal mode)
---
const foo = "foo"
const bar = "a"
const foo = foo 
const foobar = foo + bar
const footer = foo + ter
TIP26
