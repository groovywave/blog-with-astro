
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]type union'
pubDate: 2025-02-11
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["typescript", ]
---



```
let unionType: number | string = 10;
let unionTypes: (number | string)[] = [21, 'hello'];

unionType = 20;
unionType = 'hello';


```
