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
* Ph.D in Mathematics, École Polytechnique Fédérale de Lausanne (EPFL), 2023–present
  * Thesis advisor: Prof. Mats Stensrud, Chair of Biostatistics
* M.Sc. in Mathematics, with distinction, ETH Zürich, 2021–2023
  * Master's thesis: *Quantile Treatment Effects*, supervised by Prof. Nicolaï Meinshausen
* B.Sc. in Mathematics, École Polytechnique Fédérale de Lausanne (EPFL), 2018–2021
  * Bachelor's thesis: *The Generalized Minimum Manhattan Network Problem*, supervised by Dr. Martina Gallato and Prof. Friedrich Eisenbrand, Chair of Discrete Optimization

Research experience
======
* Summer 2022: Summer Intern, Chair of Biostatistics, EPFL
  * Supervisor: Prof. Mats Stensrud
* 2022–2023: Research Assistant, Faculty of Macroeconomics, ETH Zürich
  * Supervisor: Prof. Hans Gersbach

Professional service
======
* Reviewer, Journal of the American Statistical Association, 2024–2026
* Reviewer, Journal of Machine Learning Research, 2024–2026

Awards
======
* Third Prize, EPFL G-Research Doctoral Prize, 2026
* Early Career Poster Competition Winner, European Causal Inference Meeting, University of Oxford, April 2026

Languages
======
* English (native), French (native), German (conversational)

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
