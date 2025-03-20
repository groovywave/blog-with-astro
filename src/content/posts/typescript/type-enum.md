
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]type enum'
pubDate: 2025-02-11
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["typescript", ]
---



```
enum CoffeeSize {
  SHORT = 'SHORT',
  TALL = 'TALL',
  GRANDE = 'GRANDE',
  VENTI = 'VENTI',
};
const coffee = {
  hot: true,
  size: CoffeeSize.TALL,
}
coffee.size = CoffeeSize.SHORT;
```
