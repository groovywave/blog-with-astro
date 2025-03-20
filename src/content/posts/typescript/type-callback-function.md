
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]type callback function'
pubDate: 2025-02-11
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["typescript", ]
---



```
function doubleAndHundle(num: number, cb: (num: number) => number): void {
  const doubleNum = cb(num * 2);
  console.log(doubleNum);
}
doubleAndHundle(21, doubleNum => { return doubleNum });


```
