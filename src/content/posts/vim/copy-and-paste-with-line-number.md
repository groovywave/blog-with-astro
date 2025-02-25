
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]replace simple'
pubDate: 2025-02-25
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---

```
replace simple
Copy and paste the below text and type some commands like below.

---
1. /TIP2 9 1 <CR> <Esc>
2. :.m+2 <CR>  (move current line to below 2 lines)
3. :m+3 <CR>  (move current line to below 3 lines)
4. :1m3 <CR>  (move line 1 to line 3)
5. :.t+2      (copy current line and pasete below 2lines)
6. :t+2      (copy current line and pasete below 2lines)
7. :$t.      (cpoy end line and paste to current line)
8. :1t3      (cpoy line 1 and paste to under line 3)
---
Shoping list
	Hardware Store
		TIP291 Buy new hammer
	Beauty Parlor
		Buy nail poish remover
		Buy nails
```
