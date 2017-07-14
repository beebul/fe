---
layout: page
show_meta: false
title: "Nintendo"
subheadline: "Layouts of Feeling Responsive"
header:
   image_fullwidth: "snes_header.jpg"
   #pattern: pattern_concrete.jpg
   title: 'SNES'
permalink: "/snes/"
---
<ul>
    {% for post in site.categories.SNES %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
