
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[SQL]SQL basic'
pubDate: 2025-03-25
description: 'Git practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["SQL", ]
---



**basic**
```
DROP TABLE IF EXISTS posts;
CREATE TABLE posts (
message VARCHAR(140),
likes INT
);

DESC posts;

SHOW TABLES;

INSERT INTO posts ( message, likes) VALUES
('Thanks', 12),
("Arigato", 12);

SELECT * FROM posts;
```
