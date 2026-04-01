---
title: Categorias
layout: base
---

<h1 class="ui header">Categorias</h1>

<div class="ui big list">
    {% for category in site.categories %}
        {% for name in category %}
            <div class="item">
            <div class="content">
                <a class="header" href="">{{ name }}</a>
                <p class="description">{{ name }}</p>
            </div>
        </div>
        {% endfor %}
    {% endfor %}
</div>