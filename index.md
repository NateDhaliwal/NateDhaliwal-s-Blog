---
title: Blog Home
---

This is NateDhaliwal's Blog, where he is doing this using Jekyll and Github Pages. He's pretty new to this, and he tries to write blog posts frequently.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
