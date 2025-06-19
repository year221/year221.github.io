---
layout: page
title: Blog
permalink: /blog/
---

# Blog

Welcome to my blog! Here I share my thoughts on technology, development, and life.

---

## Recent Posts

### Getting Started with GitHub Pages
*January 15, 2025*

Setting up a personal website with GitHub Pages is easier than you might think. In this post, I'll walk you through the process of creating your own site using Jekyll and markdown.

[Read more →]({% post_url 2025-01-15-getting-started-github-pages %})

---

### My Journey into Web Development
*January 10, 2025*

Reflecting on how I got started in web development and the technologies that have shaped my career so far.

[Read more →]({% post_url 2025-01-10-web-development-journey %})

---

### Why I Love Open Source
*January 5, 2025*

Open source software has been instrumental in my learning journey. Here's why I believe in contributing back to the community.

[Read more →]({% post_url 2025-01-05-why-i-love-open-source %})

---

## All Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}