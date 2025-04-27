
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]advanced type guard'
pubDate: 2025-04-27
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["typescript", ]
---



```
function advancedFn(...args: [age: number, name: string, hasPet?: boolean, ...scores: number[]]) {

}


advancedFn(0, 'hi', true, 3, 3, 3);


function advancedFn2(args: [age: number, name: string, hasPet?: boolean, ...scores: number[]]) {

}

advancedFn2([0, 'hi', true, 3, 3, 3]);
```
