
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[SQL]SELECT'
pubDate: 2025-03-29
description: 'Git practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["SQL", ]
---



```


**SELECT**

DROP TABLE IF EXISTS posts;
CREATE TABLE posts (
  id INT NOT NULL AUTO_INCREMENT,
  message VARCHAR(140),
  likes INT,
  PRIMARY KEY (id)
);

INSERT INTO posts (message, likes) VALUES
  ('Thanks', 12),
  ('Arigato', 4),
  ('Merci', 4),
  ('Gracias', 15),
  ('Danke', 23);

SELECT id, message
 FROM posts;
SELECT * FROM posts WHERE likes >= 10;
SELECT * FROM posts WHERE message = "Danke";
SELECT * FROM posts WHERE message != "Danke";
SELECT * FROM posts WHERE message <> "Danke";
```
