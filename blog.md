---
layout: default
---
# Blog
<ul>
  {% for post in site.posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        {{ post.excerpt }}
        <em>Posted in{{ post.category}}</em>
    </li>
  {% endfor %}
</ul>