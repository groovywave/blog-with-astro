
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]advanced &'
pubDate: 2025-04-05
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["typescript", ]
---



```
// type Engineer = {
//   name: string;
//   role: string;
// }
// type blogger = {
//   name: string;
//   follower: number;
// }
// type EngineerBlogger = Engineer & blogger;
// const quill: EngineerBlogger = {
//   name: 'Quill',
//   role: 'front-end',
//   follower: 1000,
// }
// type tmp = string & number;

interface Engineer {
  name: string;
  role: string;
}
interface blogger {
  name: string;
  follower: number;
}
interface EngineerBlogger extends Engineer, blogger { }
const quill: EngineerBlogger = {
  name: 'Quill',
  role: 'front-end',
  follower: 1000,
}
type tmp = string & number;
type NumberBoolean = number | boolean;
type StringNumber = string | number;
type Mix = NumberBoolean & StringNumber;

```
