
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]insert some letters to all rows'
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
1. :%normal A;         (INSERT  ; to all rows IN NORMAL MODE)
2. :%normal i//        (INSERT // to all rows IN NORMAL MODE)

---
const foo = "foo"
const bar = "a"
const ter = foo 
const foobar = foo + bar
const footer = foo + ter
