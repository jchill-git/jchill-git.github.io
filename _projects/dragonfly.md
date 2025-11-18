---
title: Dragonfly
description: A game in C for a STM32L152C Discovery Board.
link: https://github.com/jchill-git/Game_for_STM32L152C
date: 2022-04-20
image: assets/images/dragonfly_2907246.png
order: 11
---
A Discovery Board has very limited memory, a couple LEDS, and a tiny screen. We were tasked with designing a game of any sort that could be played on one. My game, Dragonfly, takes inspiration from side scrollers and Space Arcade. Your goal is to position the dragonfly at the right level to catch on-coming flies. The location of the flies is signalled in advance by the LEDs and holding the botton moves the dragonfly up, while releasing the button causes it to drop. If by some chance you have a STM32L152C Discovery Board, you can use this [code](https://github.com/jchill-git/Game_for_STM32L152C) to play it!

## Topics
- Game design

## Technologies Used
- C

## Challenges & Learnings
This program was the final project for a computer architecture course I took at the University of Southern Maine when I was pursuing a self-directed post-grad minor in preparation for going back to do my master's. It's definitely the lowest level program I've ever written from scratch, since the whole goal of the course was to work our way up from logic circuits to C. 