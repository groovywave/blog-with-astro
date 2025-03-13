
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]print(confirm)-range'
pubDate: 2025-02-25
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---

```
print(confirm)-range
Copy and paste the below text and type some commands like below.

---
1. /som <CR>
2. :.,$p <CR>   (print from current line to end line)
3. :1,$p <CR>   (print from line 1 to end line)
4. :%p <CR>     (print all)
5. :%s/Practice/Learn/gc  (replace)
6. :.,+3p       (print current line and 3 lines  )
---
<!DOCTYPE html>
<html>
  <head><title>something</title></head>
  <body><h1>Practice Vim</h1></body>
</html>
TIP28
```
