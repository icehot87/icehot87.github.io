---
layout: archive
permalink: /blog/
title: "Blogs"
author_profile: true
---
<div>
  {% for post in site.categories.blogs %}
      {% include archive-single.html type=page.entries_layout %}
  {% endfor %}
</div>