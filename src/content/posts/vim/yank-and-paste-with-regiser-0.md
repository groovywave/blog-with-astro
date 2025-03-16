
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]Yank and paste simple'
pubDate: 2025-02-25
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---

```
Yank and paste with register 0
Copy and paste the below text and type some commands like below.

---
1. /col <CR>
2. yiw <Esc>
3. /som <CR>
4. ciw
5 <C-r> 0
---
collection = getCollection();
process(somethingInTheWay, target);
