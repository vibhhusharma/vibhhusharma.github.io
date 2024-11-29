---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

\* Denotes first-authorship.


You can also find my papers on <u><a href="{https://scholar.google.com/citations?user=QyKMVQUAAAAJ}">my Google Scholar profile</a>.</u>


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
