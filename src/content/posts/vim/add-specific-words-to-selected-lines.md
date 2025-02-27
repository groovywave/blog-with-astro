
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]Add specific word to all lines'
pubDate: 2025-02-25
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---

```
Add specific word to all lines
Copy and paste the below text and type some commands like below.

---
1. /tip 2 6 1 <CR> <Esc>
2. vjj :normal i// <CR> <Esc>
3. vkk :normal A;  <CR> <Esc>
---
const foo = TIP261
const bar = "a"
const foo = foo 
const foobar = foo + bar
const footer = foo + ter
