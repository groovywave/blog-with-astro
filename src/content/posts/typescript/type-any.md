
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]type any'
pubDate: 2025-02-11
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["typescript", ]
---



```
let anything: any = true;
anything = 'hello';
anything = ['hello', 33, true];
anything = {};
anything.apple = 'Apple';
let banana = 'banana';
banana = anything;
```
