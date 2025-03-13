
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]Write multipul files'
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
1. $ mkdir replace-test
2. $ touch replace-test{1..4}.txt
3. $ nvim replace-test1.txt
4. :args replace-test*.txt
5. :argdo normal ggoAdd some words.
6. :argdo update
7. :wq
8. cat test*.txt
9. $ nvim replace-test1.txt
10. :vim some **/*.txt <CR>
11. :copen <CR>
12. :cdo %s/some/replace/g <CR>
13. :update
14. :cclose
```
