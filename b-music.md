---
layout: page
title: Music
---
<hr class="music">
<body class="music">
<p>Here are some posts about music:</p>

<ul>
  {% for post in site.tags.music %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>





Thanks for reading!

</body>