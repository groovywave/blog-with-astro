
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]advanced index signature'
pubDate: 2025-04-16
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["typescript", ]
---



```
interface Designer {
  name: string;
  [index: string]: string;
}
const designer: Designer = {
  name: 'Quil',
  role: 'designer',
  sex: 'man',
  region: 'Japan',
}
designer.regison = 'USA';
//You can set key's type and vlue's type when you can define these names.

```
