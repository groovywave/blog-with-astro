
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]Convert to uppercase lowercase in tag.md
'
pubDate: 2025-02-25
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---

```
Change some wordshange some words
Copy and paste the below text and type some commands like below.

---
1. /you <CR> <Esc>       (search the you)
2. v i t u               (CONVERT TO LOWER CASE IN TAG)
2. v i t U               (CONVERT TO UPPER CASE IN TAG)
1. j .
5. k qq vitU <Esc> q     (register macro to q)
6. j @q                  (run macro q)
---
<a href="#">you</a>
<p>you practice tip231 and then <a href="#">you</a> will be better!</p>
TIP23
```
