---
layout: page
permalink: /repositories/
title: Repositories
nav: true
nav_order: 4
---

## GitHub Repositories

<ul>
  {% for repo in site.data.repositories.github_repos %}
    <li>
      <a href="https://github.com/{{ repo }}">{{ repo }}</a>
    </li>
  {% endfor %}
</ul>
