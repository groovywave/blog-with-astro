
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]change-some-words-with-visual-mode-in-normal-mode'
pubDate: 2025-02-25
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---

```
change-some-words-with-visual-mode-in-normal-mode
Copy and paste the below text and type some commands like below.

---
1. :wq 
2. touch test{1..5}.txt       (make 5 files)
3. nvim test*.txt             (open 5 files)
4. qq i1 <Esc> q              (register macro q)
5. :edit! <CR>                (ignore changes)
6. qQ :bn! <CR> q             (add command that force switch to next buffer to macro q)
7. :argdo normal @q | update  (run macro q on all buffers in normal mode and save them)
8. :wall                      (save all)
9. :qall                      (quit all)
10. cat test*                 (show all test files)
---
tip69
