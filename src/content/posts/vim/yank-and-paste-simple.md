
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]yank and paste simple'
pubDate: 2025-02-25
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---

```
yank and paste simple
Copy and paste the below text and type some commands like below.

---
1. /1 <CR>
2. vey                    (yank in word )
3. /4 <CR> 
4. ep                    (PASTE AFTER THE CURSOL)
5. <Esc> u
6. /4 <CR> 
7. P                     (PASTE BEFORE THE CURSONL)
---
123 456 789
