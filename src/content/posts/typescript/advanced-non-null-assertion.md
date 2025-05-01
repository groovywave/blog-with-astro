
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]advanced non null assertion'
pubDate: 2025-04-16
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["typescript", ]
---



```
const input3 = document.getElementById('input')!;
// You can get rid of null from input3's type as HTMLInputElement | null

// if (input3){
//   const input3 = document.getElementyId('input');
// })
input3.value = 'initial input value';
(document.getElementById(('input')) as HTMLInputElement).value = 'initial input value'

// You can get rid of null from input3's value as HTMLInputElement | null

```
