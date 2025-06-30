---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


Skills
======
* Programming Languages: Proficient in Python, R
* Software: ArcGIS, QGIS, ArcPro, SNAP, ERDAS IMAGINE, ENVI, Global Mapper, Google Earth Pro, Cloud Compare
* Cloud Platforms: Google Earth Engine
* Machine/Deep Learning Frameworks: TensorFlow, PyTorch
* LiDAR Tools: LAStools, FUSION, LiDAR360, Agisoft
* Version Control & Project Management: Git, Jupyter Notebooks

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
* Currently signed in to 43 different slack teams
