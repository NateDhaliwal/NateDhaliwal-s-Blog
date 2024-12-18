<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.tags }}
      {{ post.excerpt | strip_html | truncatewords: 50 }}
    </li>
  {% endfor %}
</ul>
