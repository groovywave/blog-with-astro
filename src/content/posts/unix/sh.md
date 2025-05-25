
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[unix]#!'
pubDate: 2025-05-13
description: 'unix'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["unix"]
---



```

#!/bin/sh
case $# in
1) cat >>$1 ;;
2) cat $1 >>$2 ;;
*) echo "Usage: append [fromfile] tofile" 1>&2 ;;
esac

#!/bin/sh
//declare using B shell

case $# in 
// $# 引数の数

1)  
// 引数が1つの場合

2) 
// 引数が2つの場合

*)
// 1) 2) 以外

>: update 
echo "hello" > output.txt
// over write with "hello"

echo "hello" >> output.txt
// add "hello" to end of line
```
