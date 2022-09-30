---
title: "Evolutionary Intelligence for Radiotherapy"
date: 2022-02-10 16:00:00 CET
categories: meetup 
links:
location: Online
logo: /assets/cwi-logo.png
talks:
- title: "Evolutionary Intelligent Bi-objective Treatment Planning for Prostate HDR Brachytherapy"
  speaker:
    name: "Anton Bouter"
    twitter:
    github:
  abstract: |
    The purpose of this study is to improve upon a recently introduced bi-objective treatment planning method for prostate high-dose-rate (HDR) brachytherapy (BT), both in terms of resulting plan quality and runtime requirements, to the extent that its execution time is clinically acceptable.
    
    Bi-objective treatment planning is done using a state-of-the-art multiobjective evolutionary algorithm, which produces a large number of potential treatment plans with different trade-offs between coverage of the target volumes and sparing organs at risk. A graphics processing unit (GPU) is used for large-scale parallelization of dose calculations and the calculation of the dose-volume (DV) indices of potential treatment plans. Moreover, the objectives of the previously used bi-objective optimization model are modified to produce better results.
    
    We applied the GPU-accelerated bi-objective treatment planning method to a set of 18 patients, resulting in a set containing a few hundred potential treatment plans with different trade-offs for each of these patients. Due to accelerations introduced in this article, results previously achieved after 1 hour are now achieved within 30 seconds of optimization. We found plans satisfying the clinical protocol for 15 of 18 patients, whereas this was the case for only 4 of 18 clinical plans. Higher quality treatment plans are obtained when the accuracy of DV index calculation is increased using more dose calculation points, requiring still no more than 3 minutes of optimization for 100 000 points.
    
    Large sets of high-quality treatment plans that trade-off coverage and sparing are now achievable within 30 seconds, due to the GPU-acceleration of a previously introduced bi-objective treatment planning method for prostate HDR brachytherapy. Higher quality plans can be achieved when optimizing for 3 minutes, which we still consider to be clinically acceptable. This allows for more insightful treatment plan selection in a clinical setting.


- title: "Evolutionary Intelligence for Image Registration"
  speaker:
    name: "Georgios Andreadis & Cedric Rodriguez"
    twitter:
    github:
  abstract: |


---