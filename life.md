---
layout: page
title: Life
---
<hr class="life">
<body class="life">
<p>Here are some posts about Becki's personal life:</p>

<ul>
  {% for post in site.tags.life %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

Thanks for reading!

</body>