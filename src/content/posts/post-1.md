---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[WIP]Draft Vim'
pubDate: 2025-01-30
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---

## [WIP]This is just a draft.

1. **以下の練習文をメモ帳ファイル等にコピペ**
2. **ファイルに名前をつける**
3. **シェルを開く** 
4. **vim ファイル名 enter** 
5. **/の行を/から順にタイプ**

### 練習文

```

/TIP0 1 1 cr x . . <Esc>
You practice TIP011

/TIP0 1 2 <cr> :noh d d . . <Esc>
TIP012 You practice 
TIP You practice 
TIP You practice 

/TIP0 1 3 <cr> :noh >> j . . j . . . |<Esc>
TIP013 You practice 
TIP You practice 
TIP You practice 

/TIP0 2 1 <cr> :noh A ; <Esc> j . j .  <Esc>
You practice TIP021
You practice
You practice

/TIP0 2 2<cr> :noh I <Esc> A <Esc> b s <Esc> C <Esc> S  <Esc>
You practice TIP022

/TIP0 3 1 <cr> :noh <Esc> f + s <space> + <space> <Esc> ; . ; . ;   <Esc>
You practice TIP031+and+then+you+will+be+better!


/content <cr> * cwcopy <Esc> n . n . <Esc>
...We’re waiting for content before the site can go live...
...I£ you are content with this, let’s go ahead with it...
...We’ll launch as soon as we have the content…

/TIP0 4 1 <cr> :noh f P F T t P T e / T I P041 ? TIP :s / TIP0 4 1 / TIP 0 4 1! <cr>  <Esc>
You practice TIP041

/TIP0 9 1 e d b x  <Esc>
You practie TIP091

/TIP0 9 2 <cr> :noh e b d w  <Esc>
You practie TIP092

/TIP0 9 3 <cr> :noh e d a w  <Esc>
You practie TIP093


/TIP1 0 3 <cr> :noh 0 c W We <Esc> <C-a> <C-x> 100<C-x> 100<C-a>  <Esc>
You practie TIP103


/TIP1 1 1 <cr> :noh c 4 w We <Esc>
You practie TIP111 and then you will be better

/TIP1 1 2 <cr> :noh v u v U  <Esc>
You practie TIP112 and then you will be better

/P1 3 1 <cr> :noh e i <C-h> <C-w> <C-u>  <Esc>
You practie TIP113 and then you will be better

/TIP151 <cr> :noh y t , j A <C-r> 0 . <Esc> 
You practie TIP151, and then you will be better
It's better for

/TIP22 :noh v j > . <Esc>
You practice 
	You practice 
	You practice 
You practice TIP22 
You practice 
You practice 

/TIP2 3 :noh v i t U <Esc>
<p>You practice TIP23 and then <a>you</a> will be better!</p>

```
