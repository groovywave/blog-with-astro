
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]edit several files with argdo'
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
3. nvim test*.txt             (OPEN ALL FILES NAMED test)
4. qq i1 <Esc> q              (register macro q)
5. :edit! <CR>                (IGNORE CHANGES)
6. qQ :bn! <CR> q             (ADD COMMAND THAT FORCE SWITCH TO NEXT BUFFER TO MACRO q)
7. :argdo normal @q | update  (RUN MACRO q ON ALL BUFFERS IN NORMAL MODE AND SAVE THEM)
8. :wall                      (SAVE ALL)
9. :qall                      (QUIT ALL)
10. cat test*                 (show all test files)
---
tip69
