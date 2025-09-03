---
layout: default
title: Institute Governance
---

## Institute Governance & Policies

The Fractality Institute is committed to transparency and ethical operation in pursuit of our mission. This repository contains the foundational, ethical, and operational documents that govern our work.

---

{% assign documents_by_category = site.governance | group_by: "category" %}
{% for category in documents_by_category %}
  ### {{ category.name }}

  <div class="cards">
  {% for doc in category.items %}
    <div class="card">
      <h4>{{ doc.title }}</h4>
      <p>{{ doc.summary }}</p>
      <p><a href="{{ doc.url | relative_url }}">Read Document &rarr;</a></p>
    </div>
  {% endfor %}
  </div>
{% endfor %}
