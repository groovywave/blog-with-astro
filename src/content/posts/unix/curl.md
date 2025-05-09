
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[unix]curl'
pubDate: 2025-05-08
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["unix"]
---



```


curl -L -O https://github.com/zellij-org/zellij/releases/download/v0.39.2/zellij-x86_64-unknown-linux-musl.tar.gz

curl : Client for URLs send and recieve data using URL
L    : location, when you get redirect as response, request to redirect location again
O    : remote name Output, using the file name on server, 


curl -L -o myzellij.tar.gz https://…/zellij-x86_64-unknown-linux-musl.tar.gz
save the file named myzellij.tar.gz 

```
