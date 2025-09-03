---
layout: default 
title: Proposed Experiments
---


### A Call for Radical Collaboration

The Fractality Institute believes that progress is accelerated through open inquiry. We are not defined by the answers we have, but by the quality of the questions we ask.

Below is a living repository of proposed experiments designed to test our core frameworks and explore the frontiers of integrative science. We offer these ideas to the global community—to students, researchers, citizen scientists, and other institutions. We invite you to adopt, adapt, critique, and build upon them.

Progress belongs to everyone.

<div class="cards">
{% for experiment in site.experiments %}
<div class="card">
<h3>{{ experiment.title }}</h3>
<p>{{ experiment.summary }}</p>
<p><a href="{{ experiment.url | relative_url }}">View Full Proposal &rarr;</a></p>
</div>
{% endfor %}
</div>
