---
title: How Old is My Bus Route?
description: Map of MBTA bus routes by earliest year in which a bus ran on a direct precusor route.
link: https://bsky.app/profile/urban-data.bsky.social/post/3m7kziwtq7s24
date: 2024-12-9
image: assets/images/bus_1824553.png
tags: [urban data science, visualization, transportation]
---

This project was part of the [EAAMO Urban Data Science](https://urban-data-science-eaamo.github.io/) working group's response to the 2025 #30DayMapChallenge on Bluesky. 

I'd been interested for a while in doing some kind of public project about the MBTA, since most of my day-to-day work is strictly internal. As one of the oldest and largest transit systems in the country, the T has a fascinating and somewhat tangled history. In particular, its bus routes have been inherited from various older private and public bus companies, converted from street cars or trackless trollies, and created whole cloth based on arising needs. In this visualization, I tried to show how old various part of our bus network are, by identifying the first atested year in which a bus ran on a direct precusor to an existing 2025 route. Most of the data for this project came from the [record of changes](roster.transithistory.org/MBTARouteHistory.pdf) from 1964-2025 maintained by Jonathan Belcher and Thomas Humphrey's [book](roster.transithistory.org/MBTABUSDEV.pdf) on the development of the MBTA's bus network, wich I manually organized into a tabular dataset.


## Topics
- Transportation
- Urban Data Science

## Technologies Used
- R
- ggplot2

## Challenges & Learnings
I decided to tackle this project in R, largely to knock off some of the rust from doing most of my recent data work in Python, so getting back into that took a little bit, and it's still not as pretty as I'd like.