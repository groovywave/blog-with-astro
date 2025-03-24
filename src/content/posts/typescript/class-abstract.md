
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]class abstract'
pubDate: 2025-03-24
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["typescript", ]
---



```
abstract class Person {
  static species = 'Homo sapiens';
  static isAdult(age: number) {
    if (age > 17) return true;
    return false;
  }
  readonly id: number = 32;
  constructor(readonly name: string, protected age: number) {
  }
  incrementAge() {
    this.age += 1;
  }
  greeting(this: Person) {
    console.log(`Hello! My name is ${this.name}. I am ${this.age} years old.`);
    this.explainJob();
  }
  abstract explainJob(): void;
}

class Teacher extends Person {
  explainJob() {
    console.log(`I am a teacher and I teach ${this.subject}.`);
  }
  get subject() {
    if (!this._subject) {
      throw new Error('There is no subject.');
    }
    return this._subject;
  }
  set subject(value) {
    this._subject = value;
  }
  constructor(name: string, age: number, private _subject: string) {
    super(name, age);
  }
  greeting() {
    console.log(`Hello! My name is ${this.name}. I am ${this.age} years old. I teach ${this._subject}.`)
  }
}
const teacher = new Teacher('Quill', 38, 'Math');
teacher.greeting();
//
// teacher.subject = 'music';
// console.log(teacher.subject);
// teacher.greeting();
// console.log(Person.species);
// console.log(Person.isAdult(38));
// console.log(Teacher.species);
// console.log(Teacher.isAdult(10));
```
