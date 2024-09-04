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
* Master of Engineering (M.Eng.) in Electronic Information, University of the Chinese Academy of Sciences, 2022-2025 (currently enrolled)
* Bachelor of Engineering (B.Eng.) in Computer Science and Technology, Xi'an University of Technology, 2016-2020

Work experience
======
* Autumn 2021: C++ Engineer
  * Fengyou, China Electronic Corporation
  * Duties includes: Simple algorithm construction, system testing and related document writing.
  * Supervisor: The Users
  
Skills
======
* Programming
  * C++
  * Python
* AI framework
  * Pytorch
* English
  * CET6

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
