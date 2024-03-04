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
* Ph.D in Control Theory, Universite Paris Saclay, December 2019
  Thesis: *Adaptive control of time-delay systems to counteract pathological brain oscillations*
* M.Sc. in Neuroinformatics, University of Warsaw, September 2016
  Thesis: *Measurement of local field potentials generated due to charge accumulation effect*
* B.Sc. in Neuroinformatics, University of Warsaw, September 2014
  Thesis: *Parametrization of evoked potentials in data acquired from a group of ASD patients and a control group*


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
