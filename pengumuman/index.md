---
layout: archive
title: "Pengumuman"
date: 2014-05-30T11:39:03-04:00
modified:
excerpt: "Penguman Kegiatan Gereja"
tags: []
image:
  feature:
  teaser:
---

<div class="tiles">
{% for post in site.categories.pengumuman %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->