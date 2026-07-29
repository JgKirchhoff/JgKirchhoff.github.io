---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D., Mechanical Engineering, The University of Texas at Austin
  * Co-advised by Prof. Omar Ghattas and Prof. Mehran Tehrani
  * Affiliated with the Oden Institute for Computational Engineering and Sciences

Work experience
======
* Postdoctoral Researcher, NASA Langley Research Center
  * Working with Tyler Hudson on OATMEAL and energy-efficient thermoplastic composite processing
* Incoming Assistant Professor, University of Utah Department of Mechanical Engineering, starting Fall 2027
  * Preparing to launch a research group in digitally integrated composite manufacturing
  
Skills
======
* Thermoplastic composite manufacturing
* Fusion bonding, crystallization, and sub-melt consolidation
* Inverse problems, digital twins, optimal control, and PDE-constrained optimization
* Full-field experimental mechanics and scientific computing

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Research communication, mentorship, and outdoor education
