
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]tsconfig sourcemaps'
pubDate: 2025-03-24
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["typescript", ]
---



```
{
  JavaScript Support */
    "declarationMap": true,
    "sourceMap": true,                                /* Create source map files for emitted JavaScript files. */
    (make sourcemap files and browser can recognize ts files)
    /* Create sourcemaps for d.ts files. */
}

```
