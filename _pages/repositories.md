---
layout: page
permalink: /Repositories/
title: Repositories
description: The GitHub repositories contain the code associated with some published articles. Each repository provides a description of the main results along with the relevant code.
nav: true
nav_order: 3
---

{% if site.data.repositories.github_users %}


## GitHub Repositories

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}
