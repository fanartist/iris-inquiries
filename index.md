---
layout: home
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ iris-inquiries/_posts/post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>