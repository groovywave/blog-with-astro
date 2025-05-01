
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]advanced as const'
pubDate: 2025-04-05
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["typescript", ]
---



```
const array = [10, 20] as const;
const peter = {
  name: 'Peter',
  age: 38,
} as const;

//You can set const to array or object easily.
```
