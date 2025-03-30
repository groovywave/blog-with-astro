
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[SQL]UNIQUE CHECK'
pubDate: 2025-03-29
description: 'Git practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["SQL", ]
---



```

**UNIQUE**
**CHECK**

DROP TABLE IF EXISTS posts;
CREATE TABLE posts (
message VARCHAR(140) UNIQUE,
like INT (likes >= 0 AND likes <= 100)
);

INSERT INTO posts (message, likes) VALUES
('Thanks', 12),
('Arigato', 4),
('Merci', 4);

INSERT INTO posts (message) VALUES ('Gracias');

SELECT * FROM posts;
```
