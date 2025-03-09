
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]run a macro repeatedly'
pubDate: 2025-02-11
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---


```
run macro repeatedly
Copy and paste the below text and type some commands like below.

---
1. /some <CR>
2. qq           (register macro q)
3. n            (search next)
4. dtb          (delete till b)
5. I            (insert mode)
6. every
7. <Esc> q      (stop register macro q)
8. 10@q         (run macro 10 times)
---
somebody
somebody
somebody
somebody
somebody
somebody
tip651
```
