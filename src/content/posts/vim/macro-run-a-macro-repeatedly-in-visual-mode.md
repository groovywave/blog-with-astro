
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]run a macro repeatedly on irregular lines'
pubDate: 2025-02-11
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---


```
run a macro repeatedly on irregular lines
Copy and paste the below text and type some commands like below.

---
1. /1. <CR>    (search 1.)
2. qq 0 f.     (REGISTER MACRO Q)
3. 0 f.        (search . from left)
4. r) w~       (replace with ) and convert next word to uppercase)
5. q           (stop registration macro q)
6. jVjjj       (change mode to visual and slect some lines)
7. :normal @q  (RUN MACRO q ON NORAMAL MODE)
---
1. one
2. two
// break up the monotony
3. three
4. four
tip67
```
