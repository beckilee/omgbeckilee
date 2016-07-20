---
layout: page
title: Books
---
<hr class="books">
<body class="books">
<p>Here are some posts about books:</p>

<ul>
  {% for post in site.tags.books %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

Thanks for reading!

</body>