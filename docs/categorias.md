---
title: Categorias
layout: base
---

<h1 class="ui header">Categorias</h1>

<div>
    {% for category in site.categories %}
        <h3>{{ category[0] }}</h3>
        {% for post in category[1] %}
            <p>{{ post.title }}</p>
        {% endfor %}
    {% endfor %}
</div>