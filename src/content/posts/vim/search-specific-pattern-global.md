
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]Search specific pattern global'
pubDate: 2025-02-11
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---


```
Search specific pattern global
Copy and paste the below text and type some commands like below.

---
1. :g/{/.+1,/}/-1>

  (:g/{/   global search {  search every {)
  (.+1     from current line +1 )
  (,/}/-1  to line include } -1 )
  (>       run command > {do indent} )
---
function sum(a, b){
//add parameter
return a + b;
}

function sum(a, b)@
  //add parameter
  return a + b;
!
```
