---
title: Knitting and Crochet
layout: archive
permalink: /yarn/
author: Creative

collection: yarn
entries_layout: grid
classes: wide
sort_order: reverse
sort_by: date
---
## Coming soon!




<div class="entries-{{ page.entries_layout }}">
    ## Patterns  
    This is some text about the patterns.

    {% for post in site.yarn reversed %}
        {% if post.tags contains 'pattern' %}
          {% include archive-single-costume.html sort_by=page.sort_by sort_order=page.sort_order type=page.entries_layout %}
        {% endif %}
    {% endfor %}
</div>



<div class="entries-{{ page.entries_layout }}">
    ## Selected Projects  
    This is some text about the projects.

    {% for post in site.yarn reversed %}
        {% if post.tags contains 'project' %}
          {% include archive-single-costume.html sort_by=page.sort_by sort_order=page.sort_order type=page.entries_layout %}
        {% endif %}
    {% endfor %}
</div>
