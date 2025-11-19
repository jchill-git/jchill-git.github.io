---
title: Predicting Boston Construction
description: A geographically-weighted neural network
link: 
date: 2023-12-13
image: assets/images/tower_16443041.png
order: 3
---

The Boston area, like most major US cities, suffers from a shortage of housing. We wnated to better understand how location impacts the kind of projects that get built, so we turned to Boston building permit data. We then evaluated the usefulness of a geographically-weighted neural network for predicting the type of new construction on a lot given its location. Our model was trained on two sets of geographically-linked features, one based on demographic data from the Boston Area Research Initiative and the other, representational embeddings of satellite images from Google Maps generated using Tile2Vec. 

## Topics
- Urban Data Science
- Neural Networks
- Geospatial Data

## Technologies Used
- Torch
- Tile2Vec
- Google Maps API

## Challenges & Learnings
The trickiest part about this project was figuring out how to implement a GWANN. We were basing the architecture on a paper, but had a heck of time getting it set up in Torch.