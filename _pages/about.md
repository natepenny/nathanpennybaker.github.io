---
permalink: /
title: "Electrical Engineering Portfolio"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to my portfolio. I am a junior Electrical Engineering student at the University of Oklahoma with a focus on power systems, industrial controls, and aerospace avionics.

Below are my featured projects. You can view the full details for each in the [Portfolio](/portfolio/) section.

{% for post in site.portfolio limit:3 %}
  {% include archive-single.html %}
{% endfor %}
