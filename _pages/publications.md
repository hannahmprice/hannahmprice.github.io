---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Preprints
{% assign counter = 1%} {% for post in site.preprints %} {% assign counter=counter | plus:1 %} {% endfor %}
{% for post in site.preprints reversed %}
{% assign label=counter | minus:1 %}
{% include archive-single.html %}
{% assign counter=label %}
{% endfor %}

## Published Articles
{% assign counter = 1%} {% for post in site.publications %} {% assign counter=counter | plus:1 %} {% endfor %}
{% for post in site.publications reversed %}
{% assign label=counter | minus:1 %}
{% include archive-single.html %}
{% assign counter=label %}
{% endfor %}

## Conference Proceedings
{% assign counter = 1%} {% for post in site.proceedings %} {% assign counter=counter | plus:1 %} {% endfor %}
{% for post in site.proceedings reversed %}
{% assign label=counter | minus:1 %}
{% include archive-single.html %}
{% assign counter=label %}
{% endfor %}
