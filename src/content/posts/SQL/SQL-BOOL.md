
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[SQL]BOOL'
pubDate: 2025-03-29
description: 'Git practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["SQL", ]
---



```
**BOOL**

DROP TABLE IF EXISTS posts;
CREATE TABLE posts (
message VARCHAR(140),
likes INT,
is_draft BOOL,
created DATETIME
);

INSERT INTO posts (message, likes, is_draft, created) VALUES
('Thanks', 12, TRUE, '2025-03-29 20:00:00'),
('Arigato',4, false, '2025-03-29 '),
('Merci', 4, 0, NOW());

SELECT * FROM posts;
```
