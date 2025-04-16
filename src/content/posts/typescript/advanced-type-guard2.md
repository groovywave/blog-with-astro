
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]advanced type guard'
pubDate: 2025-04-05
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["typescript", ]
---



```
class MyDog {
  speak() {
    console.log('bow-wow')
  }
}
class MyBird {
  speak() {
    console.log('tweet-tweet')
  }
  fly() {
    console.log('flutter');
  }
}

type MyPet = MyDog | MyBird;
function havingPet(pet: MyPet) {
  pet.speak();
  if ('fly' in pet) {
    pet.fly();
  }
  if (pet instanceof MyBird) {
    pet.fly();
  }
}
havingPet({ speak() { console.log('hello') }, fly() { console.log('not fly') } });
```
