---
layout: archive
title: "News"
permalink: /news/
author_profile: true
---

Here is a selection of recent news and activities from the group:

{% for post in site.news reversed %}
  {% include archive-single-news.html %}
{% endfor %}
