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

{% assign counter = 1%} {% for post in site.grouppast %} {% assign counter=counter | plus:1 %} {% endfor %}
{% for post in site.grouppast reversed %}
{% assign label=counter | minus:1 %}
{% include archive-single-group.html %}
{% assign counter=label %}
{% endfor %}
 


