---
layout: default
title: "PVP Case Files"
permalink: /case-files/
---

## PVP Case Files

This is a living archive of our analyses of cutting-edge research from the broader scientific community. Each document is a "worked example" of our **Pattern Validation Protocol (PVP)**, demonstrating how the Institute's framework can be used to validate, critique, and synthesize new scientific findings.

---

<div class="post-list">
  {% for item in site.case_files reversed %}
    <div class="post-item">
      <h3><a href="{{ item.url | relative_url }}">{{ item.title }}</a></h3>
      <p class="post-meta">{{ item.date | date: "%B %-d, %Y" }} • {{ item.canonical_id }}</p>
      <p>{{ item.summary }}</p>
    </div>
  {% endfor %}
</div>
