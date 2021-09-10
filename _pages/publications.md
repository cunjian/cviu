---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

### Journal articles
#### Forthcoming
[51] **Di X**, Woelfer M, Kuhn SB, Zhang Z, Biswal BB (accepted): Estimations of the weather effects on brain functions using functional MRI: a cautionary note. Hum Brain Mapp [bioRxiv](https://doi.org/10.1101/646695)
