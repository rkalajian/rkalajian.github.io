---
layout: default
---
# Blog
<ul>
  {% for post in site.posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a> - <em>Posted in <Strong>{{ post.category}}</Strong></em>
        {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>