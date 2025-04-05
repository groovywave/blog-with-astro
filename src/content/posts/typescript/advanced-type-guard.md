
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
class Dog {
  speak() {
    console.log('bow-wow');
  }
}

class Bird {
  speak() {
    console.log('tweet-tweet');
  }
  fly() {
    console.log('flutter');
  }
}

type Pet = Dog | Bird;
function havePet(pet: Pet) {
  pet.speak();
  if (pet instanceof Bird) {
    pet.fly();
  }
}

havePet(new Bird())
havePet(new Dog())
havePet({
  speak() {
    console.log('hello'), console.log('world');
  }
});

// havePet({
//   speak() {
//     console.log('hello'),
//       fly(){
//       console.log('not fly'); //it can't works.
//     }
//   }
// });
```
