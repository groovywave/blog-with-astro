
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]interface new as constructor'
pubDate: 2025-03-27
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["typescript", ]
---



```
interface addFunc {
  new(num1: number, num2: number): object;
  foo: string;
}
function tmp(func: addFunc) {
  let data = new func(1, 2);
  console.log(data)
}

(
use new as constructor
and then
define function using new as constructor
)

```
