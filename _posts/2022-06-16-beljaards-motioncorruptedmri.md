---
title: "Motion Robustness in Deep Learning Based MRI Acceleration Approaches"
date: 2022-06-16 16:00:00 CET
categories: meetup 
links:
    "Springer": "https://link.springer.com/chapter/10.1007/978-3-031-16443-9_36"
location: V-01-022
picture: /assets/motioncorruptedmri.png
talks:
- title: "Investigation of the effect of motion on MRI reconstruction, and demostration that finetuning by training with synthetic motion corrupted data can enhance the motion robustness of existing deep learning based reconstruction approaches."
  speaker:
    name: "Laurens Beljaards"
    twitter: 
    github: 
  abstract: |
    MRI can be accelerated via (AI-based) reconstruction by undersampling k-space. Current methods typically ignore intra-scan motion, although even a few millimeters of motion can introduce severe blurring and ghosting artifacts that necessitate reacquisition. We investigate i) the effects of rigid-body motion on the quality of AI-based reconstructions, and ii) if this corruption can be mitigated by introducing motion-corrupted data during training. We observe an improvement from 0.819 to 0.867 in terms of SSIM when motion-corrupted brain data is included during training, demonstrating that training with motion-corrupted data can partially compensate for motion corruption.
---