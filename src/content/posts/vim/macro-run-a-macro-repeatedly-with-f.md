
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]run a macro repeatedly with f'
pubDate: 2025-02-11
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---


```
run macro repeatedly with f
Copy and paste the below text and type some commands like below.

---
1. /x <CR>
2. f+                         (search +)
3. qq                         (register macro q)
4. :normal! i <Space> <CR>    (INSERT A SPACE IN NORMAL MODE)
5. l :normal! a <Space> <CR>  (DO IT AGAIN)
5. ;                          (search next +)
6. q                          (stop registration macro q)
7. 20@q                       (RUN MACRO 20 TIMES)
---
tip661 x = "("+a+","+b+","+c+","+d+",+e+")";
```
