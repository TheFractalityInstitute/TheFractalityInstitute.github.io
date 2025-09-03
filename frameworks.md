---
layout: default
title: Core Frameworks
---
## The Institute's Core Frameworks

An introduction to our science...

{% for framework in site.frameworks %}
  <div class="card">
    <h3>{{ framework.title }}</h3>
    <p>{{ framework.excerpt }}</p>
    <p><a href="{{ framework.url | relative_url }}">Learn More &rarr;</a></p>
  </div>
{% endfor %}
