---
layout: base
---

<p>Default layout.</p>
<h1>{{ page.title }}</h1>
<p>{{ page.author }}</p>
<p>{{ page.date | date_to_string }}</p>
<hr>

{{ content }}