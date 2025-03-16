
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]:Set some numbers'
pubDate: 2025-02-25
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---

```
Set some numbers
Copy and paste the below text and type some commands like below.

---
1. /par <CR>                      (search par)
2. :let i = 1 <CR>                (DEFINE i)
3. qq                             (register macro q)
4. I                              (change to insert mode)
5. <C-r>                          (ENABLE TO PASTE REGISTERED VALUE)
6. =                              (YOU CAN PASETE THE RESULT OF A CALCULATION)
7. i<CR> <Space> <Esc>            (you can set let i)
6. :let i += 1 <CR>               (YOU CAN SET LET i += 1)
7. q                              (stop registration macro q)
8. jVjj                           (select some lines)
9. :normal @q                     (run macro q in normal mode)
---
partridge in a pear tree
partridge in a pear tree
partridge in a pear tree
tip70

