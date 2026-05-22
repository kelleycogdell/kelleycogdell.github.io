---
title: Oral Histories
layout: base
date: 2025-09-30
homepage: TRUE
position: 1
summary: ""
thumbnail: assets/images/Goat.jpg
cards: 
  - title: Jane Doe 
  - thumbnail: assets/images/mic.jpg
  - link: https://gpsa.unm.edu/funding/grants-funding/grant-scholarship.html

---

## Oral History Audio and Transcript

{% assign card_pages = page.cards %} {% assign cards = all_pages | where_exp: "p", "p.path contains 'sust-student-work/'" %}

{% include nav/card-toc.html rows = card_pages %}

