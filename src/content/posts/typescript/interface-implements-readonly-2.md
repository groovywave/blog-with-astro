
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]interface implements readonly 2'
pubDate: 2025-03-27
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["typescript", ]
---



```
interface Human {
  readonly name: string;
  age: number;
  greeting(message: string): void;
}

class Developer implements Human {
  constructor(public name: string, public age: number, public experience: number) { }
  greeting(message: string) { console.log(message); }
}

const tmpDeveloper = {
  name: 'Quill!',
  age: 38,
  experience: 3,
  greeting(message: string) {
    console.log(message);
  }
}
const user: Human = tmpDeveloper;
let developer = new Developer('Quill', 38, 3);
developer.name = 'hello';
(you can use depeloper.name = "xxx";)

```
