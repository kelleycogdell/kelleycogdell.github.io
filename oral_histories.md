---
title: Oral Histories
layout: base
date: 2025-09-30
homepage: TRUE
position: 1
summary: ""
thumbnail: assets/images/Goat.jpg

---

# Oral History Audio and Transcripts
---
{% assign card_pages = page.cards %} {% assign cards = all_pages | where_exp: "p", "p.path contains 'sust-student-work/'" %}

{% include nav/card-toc.html rows = card_pages %}

