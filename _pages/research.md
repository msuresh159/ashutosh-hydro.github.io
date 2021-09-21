---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research aims at advancing the understanding of hydro-climatology and its interaction with other natural-human systems. 
Specifically, my research work has focused on the resilience analysis of ecohydrological systems at different spatial scales, 
hydrological modeling, and climate change impact assessment. 
I utilize remote sensing dataset and machine learning tools to solve the hydrological problems such as risk and resilience analysis, 
hydrologic predictions. Presently, I am focusing on interdisciplinary research to identify the 
connections between different natural and human-made systems to understand 
how hydrologic risk to propagate to other domains such as ecology and agriculture. 

## My research interests are:

* Eco-hydrological resilience analysis 
* Hydrological modelling
* Climate change impact assessment
* Drought and rainfall prediction
* Applications of machine learning techniques in water resources 

## Research Outputs

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}




