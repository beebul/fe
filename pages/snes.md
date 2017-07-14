---
layout: page
show_meta: false
title: Super Nintendo
header:
  image_fullwidth: worse-things-happen-at-sea.jpg
permalink: /snes/
published: true
---
<ul>
    {% for post in site.categories.SNES %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
