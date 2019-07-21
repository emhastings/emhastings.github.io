---
title: Knitting and Crochet
layout: archive
permalink: /yarn/
author: Creative

flexgallery:
  - aspect: "1.5"
    url: http://emhastings.github.io/images/green-bird/bodice.jpg
    image_path: http://emhastings.github.io/images/green-bird/bodice-th.jpg
    alt: "The bodice"
  - aspect: "1.5"
    url: http://emhastings.github.io/images/green-bird/bodice2.jpg
    image_path: http://emhastings.github.io/images/green-bird/bodice2-th.jpg
    alt: "The bodice onstage"  
    end_row: "true"
  - aspect: "1.5"
    url: http://emhastings.github.io/images/green-bird/bodice3.jpg
    image_path: http://emhastings.github.io/images/green-bird/bodice3-th.jpg
    alt: "The bodice onstage"  
  - aspect: "1.5"
    url: http://emhastings.github.io/images/green-bird/bodice4.jpg
    image_path: http://emhastings.github.io/images/green-bird/bodice4-th.jpg
    alt: "The bodice onstage"
    
flexgallery2:
  - aspect: "1.5"
    url: http://emhastings.github.io/images/green-bird/bodice.jpg
    image_path: http://emhastings.github.io/images/green-bird/bodice-th.jpg
    alt: "The bodice"
  - aspect: "1.5"
    url: http://emhastings.github.io/images/green-bird/bodice2.jpg
    image_path: http://emhastings.github.io/images/green-bird/bodice2-th.jpg
    alt: "The bodice onstage"  
    end_row: "true"
  - aspect: "1.5"
    url: http://emhastings.github.io/images/green-bird/bodice3.jpg
    image_path: http://emhastings.github.io/images/green-bird/bodice3-th.jpg
    alt: "The bodice onstage"  
  - aspect: "1.5"
    url: http://emhastings.github.io/images/green-bird/bodice4.jpg
    image_path: http://emhastings.github.io/images/green-bird/bodice4-th.jpg
    alt: "The bodice onstage"

---

## Designs  
This is some text about the patterns.  

{% for post in site.yarn reversed %}
    {% if post.tags contains 'pattern' %}
      {% include archive-single.html %}
    {% endif %}
{% endfor %}

{% include flexgallery caption="Images 2-4 from the Knox Theatre website, linked below"%}


## Selected Projects  
This is some text about the projects.

{% for post in site.yarn reversed %}
    {% if post.tags contains 'project' %}
      {% include archive-single.html%}
    {% endif %}
{% endfor %}

{% include flexgallery2 caption="Images 2-4 from the Knox Theatre website, linked below"%}
