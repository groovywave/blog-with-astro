
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]type enum2'
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
  SHORT,
  TALL,
  GRANDE,
  VENTI,
};
const coffee = {
  hot: true,
  size: CoffeeSize.TALL,
}
coffee.size = CoffeeSize.SHORT;
coffee.size = 3;
```
