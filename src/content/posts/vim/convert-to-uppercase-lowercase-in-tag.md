
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]Change some words'
pubDate: 2025-02-25
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---


```
Change some words
Copy and paste the below text and type some commands like below.

---
1. /TIP2 3 1 <CR> <Esc>  (search the word)
2. v i t u               (convert to lower case in tag)
2. v i t U               (convert to upper case in tag)
1. j .
5. k qq vitU <Esc> q     (register macro to q)
6. j @q                  (run macro q)
---
<a href="#">TIP231 you</a>
<p>you practice tip231 and then <a href="#">you</a> will be better!</p>
```
