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
* M.S. in Electronics and Information Engineering, Tsinghua University, 2025
* B.S. in Automation, Beihang University, 2022

Skills
======
* Languages : Strong reading, writing and speaking competencies for English, Mandarin Chinese
* Tools 
  * Linux
  * ROS
  * LaTex
* Coding : Python,C++

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Videos
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
