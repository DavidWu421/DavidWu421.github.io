---
layout: page
title: notes & writings
permalink: /writings/
description: Informal write-ups, notes, and other works.
nav: true
nav_order: 4
---

{% assign writings = site.writings | sort: "date" | reverse %}
{% for writing in writings %}
<div class="writing-entry mb-4">
  <h4>{{ writing.title }}</h4>
  <p class="text-muted" style="font-size: 0.9em;">{{ writing.date | date: "%B %Y" }}</p>
  <p>{{ writing.description }}</p>
  <a href="{{ writing.pdf }}" target="_blank" class="btn btn-sm btn-outline-primary">View PDF</a>
</div>
<hr>
{% endfor %}
