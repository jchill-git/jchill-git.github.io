---
title: Translation Alignment User Study
description: Evaluation of the impact of word-level alignments on reader comprehension
link: https://www.proquest.com/docview/3058409134?sourcetype=Dissertations%20&%20Theses
date: 2024-05-4
image: assets/images/wolf_6018058.png
order: 1
---

Translation alignments used to be an unavoidable artifact of machine translation, but with the shift to neural networks and longer tokens, they were left behind. So, when I was a kid and used Google Translate you could hover over a word and see it aligned, but now you can only see section-level alignments. This interface change struck me as a loss for the user. Intuitively, the more fine-grained the visualization the more recourse the user has to diagnose a poor translation, but I found very little work had actually been done to measure the scale of that loss.

In my experiment, I presented users who had taken at least one semester of a college-level language course, but who had no exposure to Finno-Ugric languages, with a passage from _Libahunt_, a classic Estonian play about werewolves, that was -- not coincidently -- the only Estonian text on Project Gutenberg. One group had automated alignments visualized at the word level, the other, the section level. Both were then asked to complete a cloze-task in Estonian where the sentences were about, but not from, the passage and used only vocabulary and grammatical structures found within it. The results showed significant benefits for the users receiving the word-level alignments, not only for their understanding of vocabulary, but also for how Estonian functions syntactically. If you want more detail, you can check out my [master's thesis](https://www.proquest.com/docview/3058409134?sourcetype=Dissertations%20&%20Theses).


## Topics
- User Study
- Human-Computer Interaction
- Translation Alignment
- Digital Libraries

## Technologies Used
- Beyond Translation
- ChatGPT (as an alignment model)

## Challenges & Learnings
This was my first human-subject study and the first time navigating all the IRB-related paperwork that goes along with that -- definitely an educational process.