---
layout: default
title: "books"
author: "kanen stephens"
domain: "books"
---

<ol class="list">
    {% for collection in site.collections %}
    {% assign pages = site[collection.label] | where_exp: "pages", "pages.path
    != page.path" | where: "section", "books"%} {% for item in pages %}
    <li><a href="{{item.url}}">{{item.domain}}</a></li>
      {% endfor %}
    {% endfor %}
</ol>
