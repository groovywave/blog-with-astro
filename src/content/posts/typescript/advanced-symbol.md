
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]advanced symbol'
pubDate: 2025-04-05
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["typescript", ]
---



```
const symbol1 = Symbol();
const symbol2: unique symbol = Symbol();

function myFunc(mySymbol: symbol) { }
myFunc(symbol1);
myFunc(symbol2);
```
