---
title: Documenti
layout: page
permalink: /ricerca/
show_excerpts: true
entries_layout: list
# image: /images/IMG_0305.jpeg
---

{% for doc in site.docs %}
  <h3>{{ doc.title }}</h3>
  <p><em>{{ doc.venue }}</em> – {{ doc.date | date: "%Y" }}</p>
  <p>{{ doc.abstract }}</p>
  <p><a href="{{ doc.pdf }}">Scarica PDF</a></p>
{% endfor %}
