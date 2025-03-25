
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Git]git merge2'
pubDate: 2025-03-25
description: 'Git practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["Lazygit", "LazyVim"]
---



**git merge2**
```
git branch
git switch -c feat
insert "add to feat"
git commit -am "add to feat"
git switch main
git branch
git log --oneline --all
git merge feat --no-ff
git merge feat --no-ff --no-edit
git merge feat
git log --oneline --graph
git switch main
git branch
git btanch -d feat

```
