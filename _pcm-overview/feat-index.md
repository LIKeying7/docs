---
layout: base
title:  'Features'
generated: 'true'
permalink: pcm/feat/index.html
udver: '2'
---

# Features

{% include pcm-feat-table.html %}

----------

Alphabetical listing

{% assign sorted = site.pcm-feat | sort: 'title' %}{% for p in sorted %}
* [{{ p.title }}](): {{ p.shortdef }}{% endfor %}
