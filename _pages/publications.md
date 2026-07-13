---
layout: page
permalink: /publications/
title: Publications
description: Publications by categories in reversed chronological order.
nav: true
nav_order: 2
_styles: |
  .container.mt-5 {
    max-width: 1120px;
  }
---

<!-- _pages/publications.md -->

<div class="publications-index">
  <!-- Bibsearch Feature -->
  {% include bib_search.liquid %}
  <div class="publications">
    {% bibliography %}
  </div>
</div>
