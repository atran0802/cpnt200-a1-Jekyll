---
layout: page
title: Blog
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p><strong>{{ post.date | date_to_string }} - {{ post.author }}</strong></p>
      <p>{{ post.excerpt }}</p>
    </li>  
  {% endfor %}
</ul>