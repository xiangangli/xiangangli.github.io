---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

## You can find my articles in detail on [Google scholar](https://scholar.google.com/citations?user=80YNQwMAAAAJ&hl=zh-CN)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
