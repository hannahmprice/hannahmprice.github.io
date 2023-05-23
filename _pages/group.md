---
layout: archive
title: "Group"
permalink: /group/
author_profile: true
---

## Current Group Members 

{% for post in site.group  %}
  {% include archive-single-group.html %}
{% endfor %}

## Past Group Members

{% for post in site.grouppast  %}
  {% include archive-single-group.html %}
{% endfor %}


