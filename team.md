---
layout: page
title: Team
---

{% for team in site.team %}
  <h2>{{ team.name }} - {{ team.position }}</h2>
  <p>{{ team.content }}</p>
{% endfor %}