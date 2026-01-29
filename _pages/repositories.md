---
layout: page
permalink: /repositories/
title: repositories
description: Repositories I have worked on
nav: true
nav_order: 4
---

## Main author | maintainer

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-stretch">
  {% for repo in site.data.repositories.main_repositories %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>

## Co-author | contributor

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-stretch">
  {% for repo in site.data.repositories.contrib_repositories %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>