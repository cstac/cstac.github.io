---
layout: page-fullwidth
title: "週邊設備"
meta_title: "週邊設備"
show_meta: false
header: no
permalink: "/distributor/equipment"
---
<ul>
    {% for post in site.categories.equipment %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
