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
    Deep learning techniques show success in detecting objects in medical images, but still suffer from false-positive predictions that may hinder accurate diagnosis. The estimated uncertainty of the neural network output has been used to flag incorrect predictions. We study the role played by features computed from neural network uncertainty estimates and shape-based features computed from binary predictions in reducing false positives in liver lesion detection by developing a classification-based post-processing step for different uncertainty estimation methods. We demonstrate an improvement in the lesion detection performance of the neural network (with respect to F1-score) for all uncertainty estimation methods on two datasets, comprising abdominal MR and CT images, respectively. We show that features computed from neural network uncertainty estimates tend not to contribute much toward reducing false positives. Our results show that factors like class imbalance (true over false positive ratio) and shape-based features extracted from uncertainty maps play an important role in distinguishing false positive from true positive predictions. 
    <br/><br/>

    Our code can be found [https://github.com/ishaanb92/FPCPipeline](https://github.com/ishaanb92/FPCPipeline).
    
---