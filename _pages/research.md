---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} -->
**Journal Publications**

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

**Presentations**

{% for post in site.talks reversed %}
  {% include archive-single.html %}
{% endfor %}
