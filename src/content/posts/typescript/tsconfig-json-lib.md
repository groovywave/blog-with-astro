
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[typescript]tsconfig lib[]'
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
  //"lib": [],                  (default, typescript can recognize toUpperCase, console, etc... with target)
  "lib": [],                    (typescript can't recognize toUpperCase, console, etc...)
  "lib": ["es2016","DOM", "DOM.Iterable", "ScriptHost"],      (typescript can recognize toUpperCase, console, etc...)
}

```
