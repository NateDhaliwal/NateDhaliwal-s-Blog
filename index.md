---
layout: homepage
title: Blog Home
---

This is NateDhaliwal's Blog, where he is doing this using Jekyll and Github Pages. He's pretty new to this, and he tries to write blog posts frequently.

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="/blog/{{ post.url }}">{{ post.title }}</a></h2>
      Tags: {{ post.tags }}
      {{ post.excerpt | strip_html | truncatewords: 50 }}
    </li>
  {% endfor %}
</ul>
