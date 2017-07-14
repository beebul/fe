---
layout: page
show_meta: false
title: "Sinclair"
subheadline: "Thanks for the (48k) Memories Sir Clive"
header:
   image_fullwidth: "spectrum_header.jpg"
permalink: "/spectrum/"
---
<ul>
    {% for post in site.categories.spectrum %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>