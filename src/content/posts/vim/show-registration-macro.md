
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]show registration macro
'
pubDate: 2025-02-11
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---


```
show registration macro
Copy and paste the below text and type some commands like below.

---
1. qq o <Esc> q
2. :reg q <CR>
2. qq         (register macro q)
3. A;         (execute command)
4. <Esc> q    (stop register macro)
5. jVj        (select sentence)
6. @q         (execute the macro)
---
foo = 1
var = 'a'
foobar = foo + bar
tip641 
```
