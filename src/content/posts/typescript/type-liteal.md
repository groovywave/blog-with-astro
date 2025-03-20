
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]type literal union'
pubDate: 2025-02-11
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["typescript", ]
---



```
let clothSize: 'small' | 'medium' | 'large' = 'large';
const cloth: {
  color: string;
  size: 'small' | 'medium' | 'large';
} = {
  color: 'white',
  size: 'medium',
}


```
