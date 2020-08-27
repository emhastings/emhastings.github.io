---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
excerpt: "Emily's peer-reviewed publications, from conferences, journals, etc."
---

You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=9nZlUHkAAAAJ&hl=en). See [my Kudos page](https://www.growkudos.com/profile/emily_hastings) for non-technical descriptions of some of my papers.

{% include base_path %}

## Conferences and Journals
{% for post in site.publications reversed %}
    {% unless post.tags contains 'other' %}
      {% include archive-single.html %}
	{% endunless %}
{% endfor %}

## Other Peer-Reviewed Publications
{% for post in site.publications reversed %}
    {% if post.tags contains 'other' %}
      {% include archive-single.html %}
	{% endif %}
{% endfor %}
