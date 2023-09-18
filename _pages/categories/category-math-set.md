---
title: "Set theory"
layout: archive
permalink: categories/set
author_profile: true
sidebar_main: true
---

{% assign posts = site.categories.['Set theory'] %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}