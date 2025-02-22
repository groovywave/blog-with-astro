
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]Convert a specific word to uppercase'
pubDate: 2025-02-14
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---


```
Convert a specific word to uppercase
Copy and paste the below text and type some commands like below.

---
1. /\v X(ht)?ml \C (Search for a specific pattern using very magic mode and case sensitivity)
2. gU//e <CR>      (Convert the only matching parts of the previous search pattern to uppercase)
3. // <CR>         (search again)
4. .  <CR>         (convert again)
---

XhtmlDoc
XmlDoc
XhtmlLTag
XmlTag

XHTMLDoc
XMLDoc
XHTMLTag
XHTMLTag
```
