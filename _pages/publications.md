---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


You can also find my articles on <u><a href="https://scholar.google.com/citations?user=jSm1IwUAAAAJ&hl=en">my Google Scholar profile</a>.</u>


{% include base_path %}
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

# 2020
{% for post in site.publications20 reversed %}
  {% include archive-single.html %}
{% endfor %}

# 2019
{% for post in site.publications19 reversed %}
  {% include archive-single.html %}
{% endfor %}

