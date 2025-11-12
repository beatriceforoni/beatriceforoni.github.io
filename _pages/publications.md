---
layout: page
permalink: /publications/
title: publications
description: Pre-prints, conference, journal, and workshop papers.
nav: true
nav_order: 2
---

**Disclaimer:** This material is presented to ensure the timely dissemination of scholarly works. Copyright and all rights therein are retained by authors or by other copyright holders. All persons copying this information are expected to adhere to the terms invoked by each author's copyright.

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography -f "{{ site.scholar.bibliography }}" %}

</div>
