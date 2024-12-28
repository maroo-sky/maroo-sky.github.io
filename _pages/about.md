---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# About me
I am Hee-Jun Jung, Ph.D. candidate in Artificial Intelligence at AI Graduate School of the Gwangju Institute of Science and Techonology (GIST), advised by Professor Kangil Kim. 
My interests are Disentanglement Learning, Visual Reasoning, Representation Learning (symmetry) in Computer Vision, and Knowledge Distillation in Natural Launguage Processing.
For more details, see my [CV](https://maroo-sky.github.io/files/CV_HeeJun_Jung.pdf).


# News
* [2024.12.] RA Student Research Achievement Scholarship, AI Graduate School, GIST, 2024.
* [2024.11.] CFASL: Composite Factor-Aligned Symmetry Learning for Disentanglement in Variational AutoEncoder was accepted at Transactions on Machine Learning Research (TMLR).
* [2023.07.] Feature Structure Distillation with Centered Kernel Alignment in BERT Transferring was accepted in Expert Systems with Applications.


# Education
* Gwanju Institute of Science and Technology (GIST), Gwanju, Korea
    * Ph.D., Artificial Intelligence (2020 - present)
    * Advisor: Kangil Kim
* Kyung Hee University, Suwon, Korea
    * B.S., Mechanical Engineering (2012 - 2020)


# Research Experience
* Kyung Hee University, Suwon, Korea
    * Undergraduate Researcher, Intelligent Robotic Mechatronics System Lab (Mar. 2019 - Dec. 2019)
    * Advisor: Soon Geul Lee 


# Publications
{% if site.publication_category %}
  {% for category in site.publication_category %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        {% capture category_title %}
## {{ category[1].title }}
        {% endcapture %}
        {{ category_title | markdownify }}
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}

# Honor & Awards
* RA Student Research Achievement Scholarship, AI Graduate School, GIST, 2024.
* Superiority Scholarship, Kyung Hee University, 2019.
* Superiority Scholarship, Kyung Hee University, 2017.
* Mentor Scholarship, Kyung Hee University, 2015.

