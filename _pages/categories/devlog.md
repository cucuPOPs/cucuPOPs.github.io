---
layout: archive
permalink: devlog
title: "Devlog"
author_profile: true
sidebar:
  nav: "docs"
---

{% assign posts = site.categories['devlog']%}
{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}
