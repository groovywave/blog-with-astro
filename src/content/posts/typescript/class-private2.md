
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]class private 2'
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
  constructor(public name: string, private age: number) {
  }
  incrementAge() {
    this.age += 1;
  }
  greeting(this: Person) {
    console.log(`Hello! My name is ${this.name}. I am ${this.age} years old.`);
  }
}

let person2: Person;
const quill = new Person('Quill', 38);
quill.incrementAge();
quill.greeting();

```
