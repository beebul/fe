---
layout: page
show_meta: false
title: "Super Nintendo"
subheadline: ""
header:
   image_fullwidth: "minines_04.jpg"
permalink: "/snes/"
---
<ul>
    {% for post in site.categories.SNES %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
