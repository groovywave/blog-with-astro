
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]class this'
pubDate: 2025-03-24
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["typescript", ]
---



```
class Person {
  name: string;
  constructor(initName: string) {
    this.name = initName;
  }

  greeting(this: { name: string }) {
    console.log(`Hello! My name is ${this.name}`);
  }
}

const quill = new Person('Quill');
quill.greeting();
const anotherQuill = {
  name: 'anotherQuill',
  anotherGreeting: quill.greeting
}
anotherQuill.anotherGreeting();

```
