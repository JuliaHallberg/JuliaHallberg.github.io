---
layout: page
title: Project Rainbow
permalink: /projects/rainbows
---

{% if site.tags.rainbow %}
  <ul>
    {% for post in site.tags.rainbow %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
    {% endfor %}
  </ul>
{% else %}
  <p>No rainbow-tagged posts found.</p>
{% endif %}