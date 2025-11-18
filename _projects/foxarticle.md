---
title: Reverse Engineering Fox Data Journalism
description: Examining how data and data visualization can mislead
link: https://github.com/jchill-git/gun_violence_proj
date: 2022-11-15
image: /assets/images/analysis_1743054.png
order: 8
---

This project came out of my NSF Research Traineeship. Along with other fellows, I spent a year exploring "The Dark Arts of Data Science," essentially how people manipulate data and data visualization to mislead. Toward the end of the first semester, our PI tossed us this article, in which Fox comes to some rather surprising conclusions about gun violence that are contrary to much of the established research on the subject. All of their data came from reputable and public sources, so we wanted to see if we could recreate their work and determine which, if any, of the techniques we'd studied were involved.

The code and data for recreating the chart from the article, along with what I believe to be a better version of the same vis can be found [here](https://github.com/jchill-git/gun_violence_proj).

## Topics
- Data Journalism
- Data Vis
- Misinformation

## Technologies Used
- Matplotlib
- Pandas

## Challenges & Learnings
There were a few, neglible differences between the data we saw in the sources and the data in Fox's chart, but none that changed the general take-away of the plot. Instead, their chart made an essentially true, but measured claim -- gun murders are not strongly correlated at the state level with estimates of the proportion of homes with a gun in them. That was not the way the the chart was then contextualized in the body of the article. This finding kicked off a whole new avenue of inquiry where we started studying disconnect between the plots in data journalism articles and the narratives that frame them.