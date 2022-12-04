---
layout: archive
title: "Scripts"
permalink: /scripts/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.scripts reversed %}
  {% include archive-single.html %}
{% endfor %}
