---
layout: archive
title: "Students"
permalink: /students/
author_profile: true
excerpt: "Research and Honors students advised by Emily."
---

{% include base_path %}

{% for post in site.students reversed %}
  {% include archive-single-student-cv.html %}
{% endfor %}
