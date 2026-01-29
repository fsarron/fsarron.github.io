---
layout: page
permalink: /repositories/
title: repositories
description: Repositories I have worked on or contributed to
nav: true
nav_order: 4
---

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-stretch">
  {% for repo in site.data.repositories.repositories %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
