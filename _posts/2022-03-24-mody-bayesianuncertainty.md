---
title: "Bayesian Deep Learning for Error Detection"
date: 2022-03-24 16:00:00 CET
categories: meetup 
links:
location: None
logo: /assets/logo-lkeb.png
talks:
- title: "Towards faster error detection of deep learning contours using Bayesian uncertainty heatmaps in radiotherapy"
  speaker:
    name: "Prerak Mody"
    twitter: modybaba101
    github: prerakmody
    scholar: KufX7AYAAAAJ
    linkedin: prerakmody
  abstract: |
    Bayesian Neural Nets (BNN) are increasingly used for robust organ auto-contouring. Uncertainty heatmaps extracted from BNNs have been shown to correspond to inaccurate regions. To help speed up the mandatory quality assessment (QA) of contours in radiotherapy, these heatmaps could be used as stimuli to direct visual attention of clinicians to potential inaccuracies. In practice, this is non-trivial to achieve since many accurate regions also exhibit uncertainty. 
    <br/>
    To influence the output uncertainty of a BNN, we propose a modified accuracy-versus-uncertainty (AvU) metric as an additional objective during model training that penalizes both accurate regions exhibiting uncertainty as well as inaccurate regions exhibiting certainty. For evaluation, we propose an uncertainty-ROC curve that can help differentiate between Bayesian models by comparing the probability of uncertainty in inaccurate versus accurate regions.
    <br/>
    We train and evaluate a FlipOut BNN model on the MICCAI2015 Head and Neck Segmentation challenge dataset and on the DeepMind-TCIA dataset, and observed an increase in the AUC of uncertainty-ROC curves by 5.6% and 5.9%, respectively, when using the AvU objective. The AvU objective primarily reduced false positives regions (uncertain and accurate), drawing less visual attention to these regions, thereby potentially improving the speed of error detection.
    <br/>
    You can find code for this work [here](https://github.com/prerakmody/hansegmentation-uncertainty-errordetection) and read the paper submitted to the [UNSURE2022](https://unsuremiccai.github.io/) workshop [here](https://link.springer.com/chapter/10.1007/978-3-031-16749-2_7)

---