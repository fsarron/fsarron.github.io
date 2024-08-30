---
layout: page
title: research
permalink: /projects/
description: A selection of research projects I have worked on in the past and present
nav: true
nav_order: 1
display_categories: [Imaging, Astrophysics]
horizontal: false
---

{%- if site.enable_project_categories and page.display_categories %} {%- for category in page.display_categories %}
{{ category }}
{%- assign categorized_projects = site.projects | where: "category", category -%} {%- assign sorted_projects = categorized_projects | sort: "importance" %} {% if page.horizontal -%}
{%- for project in sorted_projects -%} {% include projects_horizontal.html %} {%- endfor %}
{%- else -%}
{%- for project in sorted_projects -%} {% include projects.html %} {%- endfor %}
{%- endif -%} {% endfor %}
{%- else -%}

{%- assign sorted_projects = site.projects | sort: "importance" -%}

{% if page.horizontal -%}

{%- for project in sorted_projects -%} {% include projects_horizontal.html %} {%- endfor %}
{%- else -%}
{%- for project in sorted_projects -%} {% include projects.html %} {%- endfor %}
{%- endif -%} {%- endif -%}
