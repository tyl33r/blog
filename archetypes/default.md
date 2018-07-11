---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
tags: ["tag1", "tag2"]
description: "Descripción del artículo"
cover: https://example.com/img/1/image.jpg
lua:
  image:
    url: "/img/hugo/schema-markup.jpg"
    width: 800
    height: 600
  author: "Arturo C."
---

