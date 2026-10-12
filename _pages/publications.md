---
title: "Publications"
layout: page
permalink: /publications/
---

# Publications

<input type="text" class="pub-search" id="pubSearch" placeholder="Filter by title, author, or year...">

<div class="section-card" id="pubList">

<!--
<h2>Preprints</h2>
{% bibliography --query @unpublished %}
-->

<h2>Refereed Journal Articles</h2>
{% bibliography --query @article %}

<h2>Refereed Conference Proceedings</h2>
{% bibliography --query @inproceedings %}


<h2>Refereed Conference Presentations</h2>
{% bibliography --query @misc[category=presentation] %}


<h2>Patents</h2>
{% bibliography --query @misc[category=patent] %}

<h2>Theses</h2>
{% bibliography --query @misc[category=thesis] %}

</div>
