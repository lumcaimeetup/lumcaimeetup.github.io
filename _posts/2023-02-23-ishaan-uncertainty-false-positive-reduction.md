---
title: "Uncertainty for false-positive reduction"
date: 2023-02-23 16:00:00 CET
categories: meetup 
links:
location: V-01-022
logo: /assets/logo-default.png
talks:
- title: "Influence of uncertainty estimation techniques on false-positive reduction in liver lesion detection"
  speaker:
    name: "Ishaan Bhat"
    organization: UMC Utrecht/TU Eindhoven
    twitter: 
    github: ishaanb92
    scholar: NzpPmMYAAAAJ
    linkedin: ibhat
  abstract: |
    A radiomics-based pipeline was developed to investigate whether we can use uncertainty estimates computed by the segmentation model to filter false positives. We compared popular uncertainty estimation techniques in the medical image analysis field on their ability to filter false positives. Although we found our classifier could effectively reduce false-positives, we found that the classifier relied on shape-based radiomics features (that are computed using the binary mask) rather than intensity/texture features (that are computed using the uncertainty estimates).
    
---