---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research falls into two main areas: understanding patterns of disease with applied mathematics, and developing new methodology tools and software to help others in the same pursuit. One particular strand of research I've been focusing on is using networks to explore diseases from various angles.

Other than my current research I have also worked on several other projects in the past, similarly aimed at generating data-driven insight into disease: including the [NHS](https://www.nhs.uk/) response to Covid-19; rapid infection diagnostics with [DSTL](https://www.gov.uk/government/organisations/defence-science-and-technology-laboratory); and distributed computing to annotate the human genome with the [Computational Biology Facility](https://www.liverpool.ac.uk/computational-biology-facility/). See some highlighted projects I have worked on below!

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
