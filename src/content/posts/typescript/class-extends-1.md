
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]class  extends 1'
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
  }
  incrementAge() {
    this.age += 1;
  }
  greeting(this: Person) {
    console.log(`Hello! My name is ${this.name}. I am ${this.age} years old.`);
  }
}

class Teacher extends Person {
}
const teacher = new Teacher('Quill', 38);
teacher.greeting();

```
