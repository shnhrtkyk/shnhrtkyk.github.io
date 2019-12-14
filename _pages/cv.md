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
* B.S. in Science, Tsukuba University, 2013
* M.S. in Engineering, Tokyo Institute of Technology, 2015
* Ph.D in Engineering, Tokyo Institute of Technology, 2022(expected)

Work experience
======
* 2015- : Researcher
  * Pasco Corporation
    * 2015-2016: trafic sign detection by rule based algorithm. Develop SfM software.
    * 2016-2018: image classification and imaage segmentation using deep learning.
      * Pavement Crack Estimation
      * Road Sign Segmentation
      * Semi-supervised learning for disaster damage detection using GANs
      * Domain Adaptation for sem.seg.
      * Landslide estimation
    * 2018-2019: RPA system development for OCR using win32 APIs.
    * 2019-: 3D point cloud labeling
      


  
Skills
======
* Programming 
  * C++
  * C#
  * Python
  
* Conputer Vison
  * Image Classification 
  * Image Segmentation 
  
* Neural Network
  * GAN 
    * Domain Adaptation 
    * Semi-supervised learning      

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
  
<!-- 
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
-->

