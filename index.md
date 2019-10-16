---
title: Home
---
# Marteinns Blog
Welcome back to Marteinns blog. Here you can read about bananas, apples and math. Feel free to check out our most recent posts:
<br>
<br>
<ul class="blog-list">
    {% for post in site.posts %}
    <li>
        <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
        {{ post.excerpt }}
    </li>
    {% endfor %}
</ul>