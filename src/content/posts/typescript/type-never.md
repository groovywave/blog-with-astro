
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]type never'
pubDate: 2025-02-11
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["typescript", ]
---



```
function erro(message: string): never {
  throw new Error(message);
}
console.log(erro('This is an error'));

function getSizeName(size: 's' | 'm' | 'l') {
  switch (size) {
    case 's': return 'small'
    case 'm': return 'medium'
    case 'l': return 'large'
    default: return size satisfies never
  }
}

function getSizeName2(size: 's' | 'm' | 'l' | 'xl') {
  switch (size) {
    case 's': return 'small'
    case 'm': return 'medium'
    case 'l': return 'large'
    default: return size satisfies never
  }
}


```
