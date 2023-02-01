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

2022
Chase, A., E. Boss, N. Haëntjens, E. Culhane, C. Roesler, and L. Karp-Boss (2022), Plankton imagery data inform satellite-based estimates of diatom carbon. Geophysical Research Letters, doi: 10.1029/2022GL098076.
