---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<a href="https://github.com/akfraik/akfraik.github.io/blob/gh-pages/files/Fraik_Grad_CV_1020_Updated.pdf" target="_blank">Download my CV here.</a>

Education
======
* B.S. in Zoology, North Carolina State University, Raleigh, NC,  2015
* Ph.D in Biology, Washington State University, Pullman, WA, 2021 (expected)

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
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Outreach
======
  <ul>{% for post in site.outreach %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
