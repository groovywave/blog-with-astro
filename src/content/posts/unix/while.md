
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[unix]while'
pubDate: 2025-05-13
description: 'unix'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["unix"]
---



```
while test $a -lt 3
do
echo $a
a=`expr $a + 1`
done
```
