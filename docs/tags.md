---
title: Tags
layout: base
---

<h1 class="ui header">Tags</h1>

<div>
    {% for tag in site.tags %}
        <h3>{{ tag[0] }}</h3>
        {% for post in tag[1] %}
            <p>{{ post.title }}</p>
        {% endfor %}
    {% endfor %}
</div>