---
layout: default
title: Home
---

# Welcome

Here is where we'll tell our story, and keep notes, and such. Each story arc is organized into chapters, listed below

{% for chapter in site.chapters %}
<h2><a href="{{ chapter.url }}">{{ chapter.title }}</a></h2>
<p>{{ chapter.summary }}</p>
{% endfor %}
