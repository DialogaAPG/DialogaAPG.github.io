---
layout: page
show_meta: false
title: "Nossas propostas"
subheadline: ""
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/propostas/"
---
<ul>
    {% for post in site.categories.propostas %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
