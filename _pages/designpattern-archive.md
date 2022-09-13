---
title: "DesignPattern"
layout: archive
permalink: /DesignPattern/
author_profile: true
sidebar_main: true
---

{% assign posts = site.categories.Database %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}