
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]class readonly'
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
  readonly id: number = 32;
  constructor(public name: string, private age: number) {
    this.id = 31;
    this.name = "kygo"
    this.id = 30;
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
console.log(quill.id);

```
