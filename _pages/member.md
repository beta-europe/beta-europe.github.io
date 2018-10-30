---
layout: archive
title: "Our Members"
permalink: /member/
author_profile: true
---

The network of BETA Europe is strong thanks to its members.

{% include map.html geojson="/members.geojson" %}

{% include base_path %}

<div class="grid__wrapper grid__partners">
  {% for post in site.members %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>