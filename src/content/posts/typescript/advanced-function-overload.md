
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]advanced function overload'
pubDate: 2025-04-16
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["typescript", ]
---



```
function toUppeCase(x: string): string
function toUppeCase(x: number): number
function toUppeCase(x: string | number): string | number {
  if (typeof x === 'string') {
    return x.toUpperCase()
  }
  return x;
}
const upperHello = toUppeCase('hello');

```
