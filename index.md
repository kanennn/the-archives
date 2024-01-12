---
layout: default
title: "index"
author: "kanen stephens"
domain: "the archives"
---

<ol class="list">
    {% for item in site['indexes'] %}
    <li><a href="{{item.url}}">{{item.domain}}</a></li>
    {% endfor %}
</ol>
