
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]interface extends'
pubDate: 2025-03-27
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["typescript", ]
---



```

//type addFunc = (num1: number, num2: number) => numger;
interface addFunc {
  (num1: number, num2: number): number;
}
let addFunc: addFunc;
addFunc = (n1: number, n2: number) => {
  return n1 + n2;
}
 (
 use interface as type alias 
 and then 
 define the type of addFunc
 and then
 define addFunc
 )

```
