---
layout: home
title: Benvenuto nel mio sito
---

# Benvenuto sul mio blog in stile terminale!

## Ultimi articoli

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
