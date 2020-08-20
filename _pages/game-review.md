---
layout: archive
permalink: /game-reviews/
title: "Game Reviews"
author_profile: true
---
<ul>
  {% for post in site.categories.game-reviews %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>