---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% if site.publications.size > 0 %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
  <sup>*</sup> Equal authorship statement
{% else %}
  Nothing to see here yet. Check back soon!
{% endif %}