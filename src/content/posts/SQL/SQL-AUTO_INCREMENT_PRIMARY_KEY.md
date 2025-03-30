
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[SQL]AUTO INCREMENT, PRIMARY KEY'
pubDate: 2025-03-29
description: 'Git practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astro'
tags: ["SQL", ]
---



```


**AUTO_INCREMENT**
**PRIMARY KEY**

DROP TABLE IF EXISTS posts;
CREATE TABLE posts (
	id INT NOT NULL AUTO_INCREMENT,
	message VARCHAR(140) UNIQUE,
	like INT (likes >= 0 AND likes <= 100),
	PRIMARY KEY (id)
);

--INSERT INTO posts (message, likes) VALUES
	--(1, 'Thanks', 12),
	--(2, 'Arigato', 4),
	--(3, 'Merci', 4);

INSERT INTO posts (message, likes) VALUES
	('Thanks', 12),
	('Arigato', 4),
	('Merci', 4);

INSERT INTO posts (message) VALUES ('Gracias');

SELECT * FROM posts;
```
