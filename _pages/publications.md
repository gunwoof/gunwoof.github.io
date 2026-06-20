---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2 class="category">Preprints</h2>

{% bibliography --query @unpublished %}

<h2 class="category">Publications</h2>

{% bibliography --query @inproceedings,@article %}

</div>
