---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
nav_order: 2
---

<!-- TODO: add filters for entry types-->

<!-- _pages/publications.md -->

<h3 class="year">Theses</h3>
{% bibliography -f {{ theses }}  %}


<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} %}

</div>
