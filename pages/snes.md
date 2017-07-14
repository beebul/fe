---
layout: page
show_meta: false
title: "Nintendo"
subheadline: "Layouts of Feeling Responsive"
header:
   image_fullwidth: "minines_04.jpg" 
   #pattern: pattern_concrete.jpg
   title: 'SNES'
permalink: "/snes/"
---
<ul>
    {% for post in site.categories.SNES %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
