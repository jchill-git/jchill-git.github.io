---
title: Suspicious Behavior at the Lekagul Preserve
description: VAST 2017 Mini Challenge
link: https://github.com/gabrielsessions/VASTly-Hyperbolical
date: 2023-05-07
image: /assets/images/bird_10172850.png
order: 7
---

The VAST challenge is an annual competition in the Visual Analytics community that accompanies the VIS conference. Each year, it consists of a series of related mini-challenges that participants must solve by creating original visual analysis systems. As a final class project, my partners and I tackled a mini-challenge from the 2017 iteration, in which mysterious behaviors are impacting the population of Rose Crested Pippets at the Lekagul Preserve.

The code for our system and our final presentation slides can be found [here](https://github.com/gabrielsessions/VASTly-Hyperbolical/blob/main/Data%20Exploration/VAST%20Clustering.ipynb).

## Topics
- Visual Analytics
- Clustering
- High-dimensional projection

## Technologies Used
- D3
- Node
- React
- Scikit-learn
- PostgreSQL

## Challenges & Learnings
This was my first time working with JavaScript frameworks and building a web-app from the ground up. In terms of our actual approach, one of my key contributions was to incorporate machine learning into the task. We transformed the data into vectors representing itineraries of different vehicles in the park and then used DBSCAN to cluster similiar itineraries and identify unusual ones. The other linked visuals in our system were all means of unpacking and exploring the contents of those itineraries.