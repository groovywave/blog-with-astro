
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
run macro repeatedly simple
Copy and paste the below text and type some commands like below.

---
1. /1. <CR>  (search 1.)
2. qq        (register macro q)
3. 0 f. r)   (search . and replace it with ))
4. w~ j      (jump to next word and convert to uppercase)
5. j         (move to next line)
6. q         (stop registration macro q)
7. 3@q       (run the macro 3 times)
---
1. one
2. two
3. three
4. four
tip671
```
