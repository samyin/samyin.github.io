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
* Ph.D in Biostatistics, Emory University, 2026 (expected)
* B.S. in Statistics, Duke University, 2017

Work experience
======
* 2017/09 to 2020/07: Associate in Research
  * Center for Cognitive Neuroscience, Duke Institute for Brain Sciences
  * Projects: 
    * modeling monkeys’ strategies in a competitive, real-time video game with dynamic mixture of Gaussian components parametrized by neural networks and variational inference
    * identifying latent structure in high-dimensional time series data with approximate Bayesian methods
  * Supervisor: John Pearson, Biostatistics and Bioinformatics, Duke University School of Medicine
  
Skills
======
* Programming
  * R (Tidyverse, Stan, JAGS)
  * Python (PyTorch, TensorFlow)
  * MATLAB
* Languages
  * Mandarin (native)
  * English (near native)

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
