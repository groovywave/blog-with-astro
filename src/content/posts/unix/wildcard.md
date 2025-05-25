
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[unix]wildcard'
pubDate: 2025-05-21
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["unix"]
---



```
* : anything
? : a character
[...] : a character in []
[!...] : a character expect in [] 
[1-3a-cF-H] : [123abcFGH]

*tmp : tmpで終わるファイル名
*tmp* : tmpを含むファイル名
[a-z]* : aからzの小文字アルファベットで始まるファイル名
[a-zA-Z]* : aからZのアルファベットで始まるファイル名
*[0-9]* : 数字を含むファイル名
[!0-9]* : 数字で始まらないファイル名
?? : ２文字のファイル名
??* : ２文字以上のファイル名
tmp/* : tmp dir 配下のファイル
```
