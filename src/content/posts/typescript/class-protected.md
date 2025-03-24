
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]class protected'
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
  // constructor(public name: string, protected age: number) {
  constructor(readonly name: string, protected age: number) {
  }
  incrementAge() {
    this.age += 1;
  }
  greeting(this: Person) {
    console.log(`Hello! My name is ${this.name}. I am ${this.age} years old.`);
  }
}

class Teacher extends Person {
  constructor(name: string, age: number, public sbuject: string) {
    super(name, age);
    // super.greeting();
  }
  greeting() {
    console.log(`Hello! My name is ${this.name}. I am ${this.age} years old. I teach ${this.sbuject}.`)
  }
}
const teacher = new Teacher('Quill', 38, 'Math');
teacher.greeting();

```
