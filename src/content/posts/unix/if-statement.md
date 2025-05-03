
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[unix]if'
pubDate: 2025-05-02
description: 'unix'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["unix"]
---



```
id | sed -e 's/uid=//' -e 's/(.*//'
if [ "$USERID" -ne 0]; then echo "user is noto root"; else echo "user is root"; fi

chmod *x if-statement
./if-statement
sudo ./if-statement



```
