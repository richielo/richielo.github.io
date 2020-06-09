---
layout: archive
title: "Publications [(Google Scholar Profile)](https://scholar.google.com/citations?user=qBM2A3kAAAAJ&hl=en)"
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
