---
layout: default
---
# Blog
<ul>
  {% for post in site.posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        {{ post.excerpt }}
        <em>Posted in <Strong>{{ post.category}}</Strong></em>
    </li>
  {% endfor %}
</ul>