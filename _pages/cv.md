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
* Ph.D in Information and Communication Engineering, Southeast University, 2027 (expected)
* B.S. in Information Engineering, Southeast University, 2018
  
Awards
======
* [Finalist, Student Paper Contest, 2020 IEEE Asilomar Conference on Signals, Systems and Computers](https://www.asilomarsscconf.org/webpage/asil20/StudentPaperAnnouncement2020.pdf)

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
  
