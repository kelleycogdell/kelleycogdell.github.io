---
title: Farmer Profiles
layout: base
date: 2025-09-30
homepage: TRUE
position: 2
summary: ""
header-image: assets/images/Bunny.jpg
thumbnail: assets/images/casa-fresco-tomatoes.jpeg
---

# Farmer Profiles
---


{% assign all_pages = site.pages %} {% assign cards = all_pages | where_exp: "p", "p.path contains 'sust-student-work/'" %}

{% include nav/card-grid.html cards=cards %}
