
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]Convert a specific word to uppercase with regExp'
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
1. /\vX(ht)?ml\C <CR>  (SEARCH FOR A SPECIFIC PATTERN USING VERY MAGIC MODE AND CASE SENSITIVITY)
2. gU//e <CR>          (CONVERT THE ONLY MATCHING PARTS OF THE PREVIOUS SEARCH PATTERN TO UPPERCASE)
3. // <CR>             (search again with same pattern)
4. .                   (convert again)
5. // <CR>             (search again with same pattern)
6. .                   (convert again)
7. // <CR>             (search again with same pattern)
8. .                   (convert again)
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
