---
layout: page
permalink: /repositories/
title: Repositories
nav: true
nav_order: 4
---

<section class="repository-section" aria-labelledby="github-repositories">
  <h2 id="github-repositories">GitHub Repositories</h2>

  <article class="tl55-feature" aria-labelledby="tl55-feature-title">
  <div class="tl55-feature__content">
    <span class="tl55-feature__badge">
      <span aria-hidden="true"></span>
      Interactive model
    </span>

    <h2 id="tl55-feature-title">TL55 Arterial Tree</h2>

    <p>See how pressure and flow look across the circulation. The BCG is calculated from conservation of blood momentum.</p>

    <div class="tl55-feature__tags" aria-label="Model features">
      <span>55 arteries</span>
      <span>Pressure</span>
      <span>Flow</span>
      <span>BCG</span>
    </div>

    <div class="tl55-feature__actions">
      <a
        class="btn btn-primary"
        href="https://sinama1999.github.io/tl55-arterial-explorer/"
        target="_blank"
        rel="noopener"
      >
        Open interactive model →
      </a>

      <a
        class="tl55-feature__source"
        href="https://github.com/sinama1999/tl55-arterial-explorer"
        target="_blank"
        rel="noopener"
      >
        <i class="fa-brands fa-github" aria-hidden="true"></i>
        View source
      </a>
    </div>
  </div>

  <div class="tl55-feature__visual" aria-hidden="true">
    <img src="{{ '/assets/img/tl55-arterial-tree.svg' | relative_url }}" alt="">
  </div>
  </article>

  <div class="repository-list" aria-label="Source repositories">
  {% for repo in site.data.repositories.github_repos %}
    <a class="repository-list__item" href="https://github.com/{{ repo }}" target="_blank" rel="noopener">
      <i class="fa-brands fa-github" aria-hidden="true"></i>
      <span>
        <strong>{{ repo }}</strong>
        <small>Model source code and files</small>
      </span>
      <span class="repository-list__arrow" aria-hidden="true">→</span>
    </a>
  {% endfor %}
  </div>
</section>
