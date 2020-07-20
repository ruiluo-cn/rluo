---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
# Luo, R., Pen, T., Wang, S., & Li, L. (2019). A Novel Method for High Frequency-Resolution Group Delay Acquisition Based on Tikhonov Regularization, Frequenz, 73(7-8), 281-285. doi: https://doi.org/10.1515/freq-2019-0011

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?hl=en&user=UDiiT_wAAAAJ}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
