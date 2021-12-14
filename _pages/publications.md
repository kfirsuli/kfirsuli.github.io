---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

  You can also find my articles on <u><a href="{{https://kfirsuli.github.io/publications/}}">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
