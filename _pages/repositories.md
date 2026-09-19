---
layout: page
permalink: /repositories/
title: repositories
description: 
nav: true
nav_order: 4
---

<div style="text-align: center; margin: 2rem 0;">
  <a href="https://github.com/zdellaert">
    <img src="https://github-stats-extended.vercel.app/api?username=zdellaert&rank_icon=github&show_icons=true&include_all_commits=true&theme=shadow_green"
         alt="Zoe's GitHub Stats"
         style="max-width: 100%; height: auto;">
  </a>
</div>

{% if site.data.repositories.github_repos %}

## GitHub Repositories

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}
