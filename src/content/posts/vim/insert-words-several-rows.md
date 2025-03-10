
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]insert // to several rows'
pubDate: 2025-02-25
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---

```
insert // to several rows
Copy and paste the below text and type some commands like below.

---
1. /foo <CR> <Esc>               (search foo)
2. vjj                           (select some rows)
3. :normal i// <CR> <Esc>        (INSERT // IN NORMAL MODE)
4. vkk                           (select some rows)
5. :normal A;  <CR> <Esc>        (INSERT ; IN NORMAL MODE)
---
const foo = "foo"
const bar = "a"
const ter = "foo"
const foobar = foo + bar
const footer = foo + ter
tip26
