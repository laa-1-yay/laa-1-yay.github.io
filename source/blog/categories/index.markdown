---
layout: page
title: "Categories"
date: 2014-06-21 07:34
comments: true
sharing: true
footer: true
---

<ul>
{% for item in site.categories %}
    <li><a href="/blog/categories/{{ item[0] }}/">{{ item[0] | capitalize }}</a> [ {{ item[1].size }} ]</li>
{% endfor %}
</ul>

