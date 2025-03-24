
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]class singleton pattern'
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
  private static instance: Teacher;
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
  private constructor(name: string, age: number, private _subject: string) {
    super(name, age);
  }
  static getInstance() {
    if (Teacher.instance) return Teacher.instance;
    Teacher.instance = new Teacher('Quill', 38, 'Math');
    return Teacher.instance;
  }
}
const teacher = Teacher.getInstance();
const teacher2 = Teacher.getInstance();
console.log(teacher, teacher2);
```
