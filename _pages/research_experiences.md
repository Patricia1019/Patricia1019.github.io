---
layout: archive
title: "Research Experiences"
permalink: /research_experiences/
author_profile: true
---

<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} -->

{% include base_path %}

{% for post in site.reseach_experiences reversed %}
  {% include archive-single-research.html %}
{% endfor %}
