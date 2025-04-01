
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]interface new as constructor'
pubDate: 2025-03-27
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["typescript", ]
---



```
interface addFunc {
  new(num1: number, num2: number): object;
  foo: string;
}
function tmp(func: addFunc) {
  let data = new func(1, 2);
  console.log(data)
}
// let addFunc: addFunc;
// addFunc = (n1: number, n2: number) => { return n1 + n2; }

interface Nameable {
  name: string;
  nickName?: string;
}

const nameable: Nameable = {
  name: 'Quill',
  nickName: 'Quilla',
}

interface Human extends Nameable {
  age: number;
  greeting?(message: string): void;
}

class Developer implements Human {
  sex?: string
  constructor(public name: string, public age: number, public experience: number, initSex?: string) {
    if (initSex) {
      this.sex = initSex;
    }
  }

  greeting(message: string = 'hello') {
    // greeting(message?: string) {
    if (message) {
      message.toUpperCase();
    }
    console.log(message);
  }
}

const tmpDeveloper = {
  name: 'Quill!',
  age: 38,
  experience: 3,
  greeting(message: string) {
    console.log(message);
  }
}
// const user: Human = new Developer('Quill', 38, 3);
const user: Human = tmpDeveloper;
let developer = new Developer('Quill', 38, 3);
developer.name = 'hello';

(
use ? after property
)

```
