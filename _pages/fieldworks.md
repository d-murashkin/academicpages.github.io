---
permalink: /fieldworks/
title: "Field experience"
excerpt: "Field experience"
author_profile: true
---

{% include base_path %}

{% for post in site.fieldworks reversed %}
  {% include archive-single.html %}
{% endfor %}