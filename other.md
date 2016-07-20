---
layout: page
title: Misc.
---
<hr class="misc">
<body class="misc">
<p>Here are some posts about everything that doesn't fit neatly into a category:</p>

<ul>
  {% for post in site.tags.misc %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

Thanks for reading!

</body>