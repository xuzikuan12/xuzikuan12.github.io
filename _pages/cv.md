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
* B.S. in Material Science and Engineering, Xi'an Jiaotong University, 2016
* PhD in Material Science and Engineering, University of Science and Technology of China, 2022 (expected)

Work experience
======
* None
  
Skills
======
* Fatigue and fracture of materials
* Microstructure characterization
* Mechanical testing
* Python, PHP, MySQL, HTML and CSS

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
