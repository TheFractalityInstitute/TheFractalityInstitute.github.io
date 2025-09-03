---
layout: default
title: Core Frameworks
---

## The Institute's Core Frameworks

The scientific and philosophical work of The Fractality Institute is built upon a set of core, interlocking frameworks. These documents represent our foundational contributions to the study of consciousness, complexity, and collaborative inquiry.

### The Canonical System
Our work is organized into a canonical system to clearly distinguish between different levels of validation and scope:
- **Canon I (Empirical):** Directly testable protocols and falsifiable claims.
- **Canon II (Theoretical):** Self-consistent mathematical and logical frameworks.
- **Canon III (Epistemological):** Methodologies for inquiry and validation.
- **Canon IV (Axiological):** The exploration of values, ethics, and meaning derived from our findings.

---

<div class="cards">
{% for framework in site.frameworks %}
  <div class="card">
    <h3>{{ framework.title }}</h3>
    <p>{{ framework.summary }}</p>
    <p><a href="{{ framework.url | relative_url }}">Learn More &rarr;</a></p>
  </div>
{% endfor %}
</div>
