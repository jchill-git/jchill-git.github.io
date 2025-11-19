---
title: UD Tree Alignment
description: An automated appraoch to translation aligment using syntax trees
link: https://www.proquest.com/docview/3058409134?sourcetype=Dissertations%20&%20Theses
date: 2024-05-3
image: assets/images/chain_14763934.png
order: 4
---
This project started as a class final and evolved into a section of my master's thesis. During my work at the Perseus Project, I'd come up against the limits of automated translation alignment models for low-resource languages. Most state-of-the-art alignment models demanded large parallel training copora between the languages being aligned, something that simply doesn't exist for many low-resource language pairs. At the same time, coverage of some of those languages was expanding for Universal Dependencies (UD) parsing models. 

The central thesis of UD is that there is universal parallelism between all human languages, which can be modelled using a finite set of tags and dependency relationships. So I figured, if we took that assumption at face value, we would expect the dependency trees for the same sentence in two languages to have some amount of structural parallelism, given a fairly literal translation. They wouldn't be identical, of course, but if the UD assumption were true, there ought to be something that could be exploited to map tokens from one language onto the other. This approach was both a means of testing the UD hypothesis, and also, if it worked, a potentially new method to support the automated alignment of low-resource language pairs, since UD parsers can be trained on monolingual data sets.

My algorithm was ultimately fairly simple. I created two trees from parallel sentences then recursively mapped the nodes in each tree based on topographical similarity. I then tested the algorithm on a gold-standard aligned English translation of the first book of the _Iliad_. You can read all about my findings in the second chapter of my [thesis](https://www.proquest.com/docview/3058409134?sourcetype=Dissertations%20&%20Theses) and examine the code [here](https://github.com/jchill-git/translation_alignment)

## Topics
- Syntax Trees
- Translation Alignment
- Low Resource Languages

## Technologies Used
- Stanza
- NLTK
- NetworkX

## Challenges & Learnings
While the version of the algorithm I tested wasn't accurate enough to be really useful, it did match the performance of the state-of-the-art language-agnostic model, despite being much less complex. This finding suggests that a more sophisticated iteration, perhaps involving a more nuanced measure of node similarity could potentially improve upon its results. Additionally, that fact that it worked at all suggests that some amount of structural parallelism was exploitable in the UD trees, though admittedly further testing should be done on language pairs more distantly related then Ancient Greek and English.