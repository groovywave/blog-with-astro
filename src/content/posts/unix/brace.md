
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[unix]brace'
pubDate: 2025-05-13
description: 'unix'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["unix"]
---



```
(mkdir brace; cd ./barace; touch brace) 
//run command with sub-shell, pwd remains

{mkdir brace; cd ./barace; touch brace} 
//run command with main-shell, pwd changes

```
