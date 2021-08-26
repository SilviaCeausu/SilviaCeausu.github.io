---
layout: archive_simple
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <u><a href="{{https://scholar.google.co.uk/citations?user=0_y49TEAAAAJ&hl=en}}">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
