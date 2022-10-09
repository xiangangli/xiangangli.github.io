---
layout: archive
title: "Details in [Google scholar](https://scholar.google.com/citations?user=80YNQwMAAAAJ&hl=zh-CN), selected publications as follows:"
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
