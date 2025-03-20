
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]type alias'
pubDate: 2025-02-11
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["typescript", ]
---



```
type ClothSize = 'small' | 'medium' | 'large';
const clothSize: ClothSize = 'large';
const cloth: {
  color: string;
  size: ClothSize;
} = {
  color: 'white',
  size: 'medium',
}


```
