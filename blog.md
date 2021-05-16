---
layout: default
---
# Blog
<ul>
  {% for post in site.posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        {{ post.excerpt }}
        *{{ post.category}}*
    </li>
  {% endfor %}
</ul>