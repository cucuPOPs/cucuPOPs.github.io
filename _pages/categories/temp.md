---
layout: archive
permalink: temp
title: "미분류"
author_profile: true
sidebar:
  nav: "docs"
---

{% assign posts = site.categories['temp']%}
{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}
