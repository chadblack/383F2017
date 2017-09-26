---
layout: default 
---

# Welcome to HILA 383: Colonial Latin America through Film {#history}

### recent posts {#history}

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/383F2017{{ post.url }}">{{ post.title }}</a>, {{ post.date }}
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
