---
title: Knitting and Crochet
layout: archive
permalink: /yarn/
author: Creative

---

## Designs  
This is some text about the patterns.  

{% for post in site.yarn reversed %}
    {% if post.tags contains 'pattern' %}
      {% include archive-single.html %}
    {% endif %}
{% endfor %}


## Selected Projects  
This is some text about the projects.

{% for post in site.yarn reversed %}
    {% if post.tags contains 'project' %}
      {% include archive-single.html%}
    {% endif %}
{% endfor %}
