---
layout: page
show_meta: false
title: "Nossas propostas"
subheadline: ""
header:
   image_fullwidth: "black.png"
permalink: "/propostas/"
---
<ul>
    {% for post in site.categories.propostas %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
