
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
1. /TIP2 4 1 <CR> <Esc>
2. ved         (delete a word)
3. <C-q> 3j    (delete a word or <C-v> 3j)
4. x..         (delet 3 columns)
5. gv          (select again)
6. r|          (replace with |)
7  yyp         (copy and paste a line)
8. Vr-         (replace with -)
---
id TIP241    value
a      10
b      20
c      30
