
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]interface implements readonly'
pubDate: 2025-03-24
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
(you can't use user.name = "xxx";)

```
