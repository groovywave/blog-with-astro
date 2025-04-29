
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[unix]basic'
pubDate: 2025-04-22
description: 'typescript'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["unix"]
---



```
echo $SHELL // show using SHELL
lsblk       // show block device
tar cvf /media/hasenori/Trancend/backup.tar . //cp current directory files to usb
ls /media/hasenori/Trancend
id // show user's information
id | sed -e 's/uid=//' -e 's/(.*//' //show user's id number
if [ "USERID" -ne 0 ]; then echo "user is not root"; else echo "user is root"; files



```
