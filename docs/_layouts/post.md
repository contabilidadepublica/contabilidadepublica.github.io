---
layout: base
---

<h1 class="teste">{{ page.title }}</h1>
<p>{{ page.author }}</p>
<p>{{ page.date | date_to_string }}</p>
<hr>

{{ content }}