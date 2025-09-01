---
layout: default
title: Publications
---

## Publications

{% assign pubs_coll = site.collections | where: "label", "publications" | first %}
{% if pubs_coll %}
  {% assign pubs = pubs_coll.docs | sort: "year" | reverse %}
  <div class="cards">
  {% for pub in pubs %}
    {% include pub-card.html pub=pub %}
  {% endfor %}
  </div>
{% else %}
  <p>No publications yet. Add Markdown files to <code>_publications/</code> and make sure the collection is declared in <code>_config.yml</code>.</p>
{% endif %}
