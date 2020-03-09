---
layout: page
title: Books
permalink: "/books/"
---

The books I translated:

<ul>
{% for c in site.collections -%}
    {% if c.label == 'books' or c.label == 'posts' %}
    {% else %}
    <li><a href="/books/{{ c.label }}/">{{ c.book_name }}</a></li>
    {% endif %}
{% endfor -%}
</ul>