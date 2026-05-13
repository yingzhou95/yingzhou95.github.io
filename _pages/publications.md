---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
nav_order: 2
---

{% include bib_search.liquid %}

<div class="publications">

<h2 style="text-align:center; color: var(--global-theme-color); margin-top: 3rem; margin-bottom: 2rem;">
Journal Articles
</h2>

{% bibliography --query @article %}

<h2 style="text-align:center; color: var(--global-theme-color); margin-top: 4rem; margin-bottom: 2rem;">
Conference Papers
</h2>

{% bibliography --query @inproceedings %}

<h2 style="text-align:center; color: var(--global-theme-color); margin-top: 4rem; margin-bottom: 2rem;">
Theses
</h2>

{% bibliography --query @mastersthesis %}

</div>
