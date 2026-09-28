---
layout: page
permalink: /repositories/
title: Repositories
nav: true
nav_order: 4
---

<section class="tl55-feature" aria-labelledby="tl55-feature-title">
  <div class="tl55-feature__content">
    <span class="tl55-feature__badge">
      <span aria-hidden="true"></span>
      Live interactive model
    </span>

    <h2 id="tl55-feature-title">Explore the TL55 Arterial Tree</h2>

    <p>
      Change cardiovascular parameters and watch pressure, flow, and
      ballistocardiogram waveforms propagate through 55 arterial segments.
    </p>

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
        Launch the simulator →
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

    <svg class="tl55-feature__pulse" viewBox="0 0 500 90">
      <path d="M0 48 H90 L112 47 L128 18 L145 75 L164 32 L182 48 H260 L279 46 L295 25 L311 66 L330 37 L348 48 H500"></path>
    </svg>
  </div>
</section>

## GitHub Repositories

<ul>
  {% for repo in site.data.repositories.github_repos %}
    <li>
      <a href="https://github.com/{{ repo }}">{{ repo }}</a>
    </li>
  {% endfor %}
</ul>
