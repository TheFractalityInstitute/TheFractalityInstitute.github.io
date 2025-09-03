---
layout: default
title: Resources
---

## Keystone Protocols & Integrative Primers

A core part of the Fractality Institute's mission is to translate our theoretical frameworks into practical, actionable knowledge. This section serves as a resource hub for applying the principles of resonance, crystallization, and information geometry to enhance well-being and deepen understanding.

### Keystone Protocols
These are practical, evidence-informed guides for personal health and lifestyle optimization, viewed through the lens of our core scientific principles. They are designed to help individuals consciously guide the crystallization of healthier patterns in their own lives.

<div class="cards">
{% for protocol in site.protocols %}
  <div class="card">
    <h3>{{ protocol.title }}</h3>
    <p>{{ protocol.summary }}</p>
    <p><a href="{{ protocol.url | relative_url }}">View Protocol &rarr;</a></p>
  </div>
{% endfor %}
</div>

---

### Integrative Primers *(Coming Soon)*
Here we will break down complex, interdisciplinary topics from our research into clear, accessible articles for a general audience.
