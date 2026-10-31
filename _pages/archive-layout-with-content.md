---
title: "Archive Layout with Content"
layout: archive
permalink: /archive-layout-with-content/
---

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.date | date: "%B %d, %Y" }}</p>
{% endfor %}
