
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]class type class'
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

  greeting(this: Person) {
    console.log(`Hello! My name is ${this.name}`);
  }
}

let person2: Person;
const quill = new Person('Quill');
quill.greeting();
const anotherQuill = {
  name: 'anotherQuill',
  greeting: quill.greeting
}
anotherQuill.greeting();

```
