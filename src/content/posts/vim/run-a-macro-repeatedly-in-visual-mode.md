
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]run a macro repeatedly in irregular lines'
pubDate: 2025-02-11
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---


```
run macro repeatedly in irregular lines
Copy and paste the below text and type some commands like below.

---
1. /1. <CR>    (search 1.)
2. qq 0 f.     (register macro q)
3. 0 f.        (search . from left)
4. r) w~       (replace with ) and convert next word to uppercase)
5. q           (stop registration macro q)
6. jVjjj       (change mode to visual and slect some lines)
7. :normal @q  (run macro q in noramal mode)
---
1. one
2. two
// break up the monotony
3. three
4. four
tip672
```
