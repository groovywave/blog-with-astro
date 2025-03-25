
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Git]git rebase'
pubDate: 2025-03-25
description: 'Git practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["Lazygit", "LazyVim"]
---



**git rebase**
```
git switch -c feat
insert "add to feat"
git commit -a --no-edit
git rebase main           (resolve the conflict in ghe feat branch)
git commit -a --no-edit
git rebase --continue
git switch main
git merge feat --no-ff --no-edit


```
