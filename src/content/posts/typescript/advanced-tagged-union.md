
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]advanced tagged union'
pubDate: 2025-04-16
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["typescript", ]
---



```
class TaggedMyDog {
  kind: 'dog' = 'dog'
  speak() {
    console.log('bow-wow')
  }
}
class TaggedMyBird {
  kind: 'bird' = 'bird'
  speak() {
    console.log('tweet-tweet')
  }
  fly() {
    console.log('flutter');
  }
}

type TaggedMyPet = TaggedMyDog | TaggedMyBird;
function TaggedhavingPet(pet: TaggedMyPet) {
  pet.speak();
  switch (pet.kind) {
    case 'bird':
      pet.fly();
  }
  if ('fly' in pet) {
    pet.fly();
  }
}

TaggedhavingPet({ kind: 'bird', speak() { console.log('hello') }, fly() { console.log('not fly') } });
```
