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
* Bachelor of Science, Tsukuba University, 2013
* Master of Engineering, Tokyo Institute of Technology, 2015
* Doctor of Engineering, Tokyo Institute of Technology, 2022(expected)

Work experience
======
* 2015- : Researcher
  * Pasco Corporation
    * 2015
        * Traffic sign detection by rule-based algorithm. 
        * Develop SfM software.
    * 2016-2017
      * Image classification and image segmentation using deep learning.
          * Pavement Crack Estimation
          * Road Sign Segmentation
          * Semi-supervised learning for disaster damage detection using GANs
          * Domain Adaptation for sem.seg.
          * Landslide estimation
    * 2018
        * RPA system development for OCR using win32 APIs.
    * 2019
        * 3D point cloud labeling using deep learnig
        * Vehicle segmentation from aerial image
    * 2020
        * 3D point cloud labeling using deep learning
        * Image colonization using deep learning
        * Super resolution using deep learning
        
Skills
======
* Programming 
  * C++
  * C#
  * Python
  
* Computer Vision
  * Image 
      * Classification 
      * Segmentation 
  * Point Cloud  
      * Segmentation 
      
* Neural Network
  * GAN 
    * Domain Adaptation 
    * Semi-supervised learning      
    
Awards and honors
======
* 令和3年度(2021)測量・地理空間情報技術奨励賞
* 平成29年度 日本地震工学会大会優秀発表賞
* 2018年 応用測量論文奨励賞


Publications
======
  <ul>{% for post in site.publications reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed%}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
<!-- 
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
-->

