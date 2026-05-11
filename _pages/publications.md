---
layout: page
permalink: /publications/
title: publications
description: Publications in reverse-chronological order. First-author and co-first-author publications are listed first.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2>First-author publications</h2>

{% bibliography -f papers %}

<h2>Co-authored publications</h2>

{% bibliography -f coauthored %}

</div>
