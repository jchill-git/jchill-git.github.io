---
title: Isnad Disambiguation
description: Diambiguating scholars using graphs of tradional citations in Arabic manuscripts
link: https://github.com/jchill-git/isnad_intrigue/tree/main
date: 2022-12-08
image: assets/images/quran_3858812.png
order: 9
---

_Isnads_ are a traditional form of Arabic citation found in many manuscripts. Unlike modern, Western-style citations, _isnads_ contain the full chain of transmission back to whomever is considered the original source. As a result, they are of immense interest to historians studying scholarly networks. Unfortunately, many scholars have similar names and disambiguating individuals in the reference chain is a time consuming manual task. Building very directly off the work of [Ryan Muther](http://hnr2021.historicalnetworkresearch.org/?page_id=333), who was kind enough to share her code and time, my partner and I evaluated the effectiveness of a couple different approaches to the disambiguation task. In particular, we looked at contrastive embeddings and social features based on the similarity of _isnad_ graphs.

Our code and final presentation can be found [here](https://github.com/jchill-git/isnad_intrigue/tree/main).

## Topics
- Digital Humanities
- Networks
- Word embeddings

## Technologies Used
- NetworkX
- Torch
- BERT

## Challenges & Learnings
This was the first big technical project of my master's. We were building off and comparing to published work from the folks at [KITAB](https://kitab-project.org/), so the foundation was really well laid, but ultimately our original idea of applying graph methods, just didn't work particularly well. We brought in contrastive, surface-form embeddings mostly as a supplement to the graph-based features, but it turned that approach worked way better on its own than mixed with the graph components.