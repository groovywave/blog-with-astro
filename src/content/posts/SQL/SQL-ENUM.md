
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[SQL]SQL data type'
pubDate: 2025-03-29
description: 'Git practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["SQL", ]
---



```
**ENUM**

DROP TABLEIF EXISTS posts;
CREATE TABLE posts (
message VARCHAR(140),
likes INT,
category ENUM("Gadget", "Game", "Business")
);

--INSERT INTO posts (message, likes, category) VALUES
--('Thanks', 12, "Gadget"),
--('Arigato', 14, "Game"),
--('Merci', 10, "Business");

INSERT INTO posts (message, likes, category) VALUES
('Thanks', 12, 1),
('Arigato', 14, 2),
('Merci', 10, 3);

SELECT * FROM posts;
```
