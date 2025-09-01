---
layout: default
title: Publications
---

## Publications

<div class="cards">
{% assign pubs = site.publications | sort: "year" | reverse %}
{% for pub in pubs %}
  {% include pub-card.html pub=pub %}
{% endfor %}
</div>
