
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]advanced assertion'
pubDate: 2025-04-05
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["typescript", ]
---



```
// const input = document.getElementById('input');
// const input: HTMLElement | null
const input1 = <HTMLInputElement>document.getElementById(('input'));
input1.value = 'initial input value';

const input2 = document.getElementById('input') as HTMLInputElement;
input2.value = 'initial input value';

(<HTMLInputElement>document.getElementById('input')).value = 'initial input value';
(document.getElementById('output') as HTMLInputElement).value = 'initial input value';
```
