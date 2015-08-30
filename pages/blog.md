---
layout: page
show_meta: false
title: "Blog Entries on Blog"
subheadline: "These entries have the category name of Blog"
permalink: "/Blog/"
---
<ul>
    {% for post in site.categories.Blog %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
