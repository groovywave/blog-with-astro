
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
1l /123 <CR>
2. vey                    (yank in word )
3. /456 <CR> 
3. pu                     (paste after the cursol)
3. PU                     (paste before the cursonl)
---
123 456 789
