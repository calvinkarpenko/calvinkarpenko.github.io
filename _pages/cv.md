---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

##Education##

- **BSc. in Physics**, *The University of Sheffield, 2020*
- **MSc. in Data Analytics**, *The University of Sheffield, 2021*
	- Dissertation Title: *Can sentiment analysis of Twitter be used to predict the results of the 2020 US Presidential Election*

##Skills##
- Python: *Natural Language Processing, Machine learning, statistical computing*
- Web Development: *HTML5, CSS, Javascript and PHP*
- Databases: *MySQL*

##Publications##
<ul>{% for post in site.publications %}
{% include archive-single-cv.html %}
{% endfor %}</ul>

