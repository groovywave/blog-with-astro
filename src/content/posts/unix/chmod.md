
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
chmod //change mode
chmod 755 myfile.sh
chmod user-group-others fineName
7: 4+2+1 read 4 + write 2 + execute 1 
6: 4+2+0 read 4 + write 2 + execute 0 

```
```
chmod //change mode
chmod 755 myfile.sh
chmod user-group-others fineName
7: 4+2+1 read 4 + write 2 + execute 1 
6
: 4+2+0 read 4 + write 2 + execute 0 
5: 4+0+1 read 4 + write 0 + execute 1 
4: 4+0+0 read 4 + write 0 + execute 0 
0: 0+0+0 read 0 + write 0 + execute 0 

u: user
g: group
o: others
 
+: add
-: delete
=: update

chmod u-x myfile.sh // user can not execute myfile.sh
chmod o=r myfile.xh // others can not read myfile.sh

chmod 755 script.sh
chmod +x script.sh // anyone can execute script.sh
chmod u+x script.sh // user can execute script.sh
chmod -x script.sh //noone can execute script.sh

ls -l script.sh // you can see permision about script.sh
```
