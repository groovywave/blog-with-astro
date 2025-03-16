
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]argdo Write multipul files'
pubDate: 2025-02-14
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---


```
Write multipul files
Copy and paste the below text and type some commands like below.

---
1. $ mkdir test
2. $ touch test{1..4}.txt
3. $ nvim test1.txt
4. :args test*.txt
5. :argdo normal ggoAdd some words.
6. :argdo update
7. :wq
8. cat test*.txt
```
