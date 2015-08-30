---
layout: page
show_meta: false
title: "Blog Entries on Videos"
subheadline: "These entries have the category name of Video"
permalink: "/Video/"
---
<ul>
    {% for post in site.categories.Video %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
