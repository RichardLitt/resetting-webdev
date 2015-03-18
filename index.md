---
title: The Wabi Sabi of Programming
---

# The Wabi Sabi of Programming
The Wabi Sabi of Programming

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
