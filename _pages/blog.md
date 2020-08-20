---
layout: archive
permalink: /blog/
title: "Blogs"
author_profile: true
---
<ul>
  {% for post in site.categories.blogs %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>