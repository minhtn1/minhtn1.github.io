---
layout:   page
title:    About me
subtitle: Why you'd want to go on a date with me
---


{% include career-profile.html %}

{% unless site.data.data.sidebar.education %}
  {% include education.html %}
{% endunless %}

{% include experiences.html %}

{% include projects.html %}

{% include publications.html %}

{% include skills.html %}


