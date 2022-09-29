---
title: "Out-Of-Distribution detection on tabular medical data"
date: 2022-05-19 16:00:00 CET
categories: meetup 
links:
location: V-01-020
picture: /assets/pacmed-logo.png
talks:
- title: "Out-Of-Distribution detection on tabular medical data."
  speaker:
    name: " Giovanni Cinà"
    twitter: 
    github: 
  abstract: |
    The data that a model receives in production can differ from the data the model was trained on, leading to unreliable predictions. How can we spot these Out-Of-Distribution (OOD) samples and prevent this from happening? This problem is particularly acute for healthcare applications, due to the variability of data-generating processes and the potential implications for patients' health. In this talk I will present a line of work aimed at addressing this issue for Electronic Health records, which have been relatively understudied so far. I will review experimental results showing that many recent proposals in fact fail at this task, present some theoretical findings supporting the idea that certain classes of Neural Networks are poorly equipped for OOD detection, and finally offer some considerations on how to implement OOD detection in a practical use case.
---