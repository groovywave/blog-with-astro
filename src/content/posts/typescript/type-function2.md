
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]type function'
pubDate: 2025-02-11
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["typescript", ]
---



```
function add(num1: number, num2: number) {
  return num1 + num2;
}

const secondAdd: (n1: number, n2: number) => number = add;

const thirdAdd: (n1: number, n2: number) => number =
  function (num1: number, num2: number) {
    return num1 + num2;
  };

const fourthAdd =
  function (num1: number, num2: number) {
    return num1 + num2;
  };

const fifthAdd: (n1: number, n2: number) => number =
  function (num1, num2) {
    return num1 + num2;
  };


```
