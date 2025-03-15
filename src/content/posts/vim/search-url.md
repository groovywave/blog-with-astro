

---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]Search and replace URL'
pubDate: 2025-02-14
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---


```
Search and replace URL
Copy and paste the below text and type some commands like below.

---
1. /htt  <CR> j 
2. "uyi[ (yank in [ value to "u indicates register u)
3. /\V<C-r>u <CR> (swap lines)
4. n n n n n 
5. /tip7 8 1 <CR> j
6. V*ci[
7. https://www.google.com <CR> <Esc>
8. n . n . n .
  (this search can search only http )
---
[http://vimdoc.net/]
[http://vimdoc.net/]
[http://vimdoc.net/]
[http://vimdoc.net/]
[http://emacsdoc.net/]
[http://tmuxdoc.net/]
tip78
```
