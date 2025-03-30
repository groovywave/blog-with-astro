
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[SQL]SET'
pubDate: 2025-03-29
description: 'Git practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["SQL", ]
---



```
**SET**

DROP TABLEIF EXISTS posts;
CREATE TABLE posts (
message VARCHAR(140),
likes INT,
categories SET("Gadget", "Game", "Business")
--categories SET("Gadget", "Game", "Business")  2^0, 2^1, 2^2
);

--INSERT INTO posts (message, likes, category) VALUES
--('Thanks', 12, "Gadget,Game"),    2^0+2^1 
--('Arigato', 14, "Game"),              2^1
--('Merci', 10, "Business,Gadget"); 2^0    +2^2

INSERT INTO posts (message, likes, category) VALUES
('Thanks', 12, 3),
('Arigato', 14, 2),
('Merci', 10, 5);

SELECT * FROM posts;
```
