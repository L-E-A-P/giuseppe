---
title: documenti di ricerca
layout: page
permalink: /ricerca/
show_excerpts: true
entries_layout: list
# image: /images/IMG_0305.jpeg
---

<style>
  .doc-meta h2 {
    margin-bottom: 0.5rem; /* più compatti (invece di 1.5rem) */
  }

  .doc-meta p {
    padding-left: 1.5rem; /* indentazione */
    margin-bottom: 0rem; /* più compatti (invece di 1.5rem) */
  }

  .doc-meta p:last-child {
    padding-left: 1.5rem; /* indentazione */
    margin-top: 1rem; /* spazio normale dopo l'ultimo paragrafo del blocco */
    margin-bottom: 1rem; /* spazio normale dopo l'ultimo paragrafo del blocco */
  }
</style>

{% for doc in site.docs %}
<div class="doc-meta">
  <h2><em><a href="{{ doc.pdf }}">{{ doc.title }}</a></em></h2>
  <p><em>{{ doc.location }}</em> – {{ doc.date | date: "%Y" }}</p>
  <p>{{ doc.context }}</p>
  <p>{{ doc.abstract }}</p>
</div>
{% endfor %}
