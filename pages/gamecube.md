---
layout: page
show_meta: false
title: "Nintendo"
subheadline: "Layouts of Feeling Responsive"
header:
   #image_fullwidth: "gamecube_header.jpg"
   pattern: pattern_concrete.jpg
   title: 'Gamecube'
permalink: "/gamecube/"
---
<ul>
    {% for post in site.categories.Gamecube %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>