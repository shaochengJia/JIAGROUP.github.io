---
title: "Home"
layout: homelay
permalink: /
---

<h1 class="home-hero">{{ site.group }}</h1> 

<p class="home-hero-sub">Do what really matters and is interesting.</p>

<div class="chip-container" markdown="0">
<a href="{{ '/research' | relative_url }}" class="chip">Connected and automated vehicles</a>
<a href="{{ '/research' | relative_url }}" class="chip">Drones & eVTOLs</a>
<a href="{{ '/research' | relative_url }}" class="chip">Artificial intelligence</a>
<a href="{{ '/research' | relative_url }}" class="chip">Mathematical modeling and optimization</a>
<a href="{{ '/research' | relative_url }}" class="chip">Stochastic modeling and optimization</a>
<a href="{{ '/research' | relative_url }}" class="chip">Uncertainty quantification</a>
<a href="{{ '/research' | relative_url }}" class="chip">Machine & deep learning</a>
<a href="{{ '/research' | relative_url }}" class="chip">Computer vision</a>
</div>

We are a research group at the Institute of Intelligent Transportation Systems, Zhejiang University, led by Prof. Shaocheng Jia and dedicated to advancing Intelligent Transportation Systems (ITS) through interdisciplinary research at the intersection of **transportation, optimization, computer science, control theory, and artificial intelligence**. Our research focuses on the development of next-generation transportation systems that are safer, more efficient, intelligent, and sustainable. We study **connected and automated transportation systems**, **air-ground cooperative transportation systems**, and **AI for transportation**, emphasizing both fundamental theory and practical applications, with a particular interest in **modeling uncertainty in complex systems**.

Our work brings together mathematical modeling, optimization, intelligent algorithms, data-driven methods, and control techniques to address complex transportation problems across vehicles, infrastructure, and networks. By combining perspectives from multiple disciplines, we aim to develop new computational and theoretical approaches for understanding, designing, and managing increasingly comprehensive, unified transportation systems. Ultimately, we seek to contribute to the transformation of transportation through **intelligence, connectivity, integration, and interdisciplinary innovation**.


<div class="callout callout-success" markdown="0">
<div class="callout-title">{% include icon.html name="award" class="callout-icon" %} Highlights</div>
<p>Prof. Jia attended the IEEE ITSC2026 and successfully held the workshop "Low-altitude Transportation Systems: Modeling, Operations, and Policy".</p>
</div>

<div class="banner-frame" markdown="0">
<img src="{{ '/images/highlight.png' | relative_url }}" alt="Feynman diagrams" width="1400" height="449" loading="lazy">
<div class="banner-caption">Golden moments</div>
</div>

{% capture selected %}{% bibliography --query @*[selected=true] %}{% endcapture %}
{% if selected contains "pub-entry" %}
## Selected publications

<div class="section-card selected-pubs" markdown="0">
{{ selected }}
<p style="margin: var(--space-4) 0 0;"><a href="{{ '/publications' | relative_url }}">All publications &rarr;</a></p>
</div>
{% endif %}

<!--
Command out this part
## About PI

I am a physicist working in the field of quantum mechanics and quantum electrodynamics.
I received my undergraduate degree in physics from the Massachusetts Institute of Technology (MIT) in 1939 and went on to earn my PhD from Princeton University in 1942.
After completing my doctoral studies, I worked on the Manhattan Project, where I helped develop the first atomic bombs.
After the war, I returned to academia, holding teaching and research positions at Cornell and now at the California Institute of Technology.
-->
