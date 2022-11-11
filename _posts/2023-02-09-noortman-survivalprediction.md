---
title: "Survival Prediction in cancer patients"
date: 2023-02-09 16:00:00 CET
categories: meetup 
links:
location: V-01-022
logo: /assets/logo-lumc.png
talks:
- title: "Development and external validation of a PET radiomic model for prognostication of head and neck cancer"
  speaker:
    name: "Wyanne Noortman,"
    twitter: 
    github: 
    scholar: K-w-IAQAAAAJ
    linkedin: wyanne-noortman
  abstract: |
    **Introduction**: External validation of radiomic studies is limited, although of utmost importance for the clinical implementation of radiomic models. The purpose is to build and externally validate a [18F]FDG PET radiomic model to predict overall survival in patients with head and neck squamous cell carcinoma (HNSCC).

    **Methods**: Two multicentre datasets of patients with operable HNSCC treated with neoadjuvant afatinib who underwent a baseline [18F]FDG PET/CT scan were included (EORTC 90111 trial: n=23, Unicancer Predictor trial: n=20). Tumours were delineated using an adaptive threshold of 50% SUVpeak, wherefrom 48 radiomic features were extracted. Each cohort was used once as training and once as an external validation set for the prediction of overall survival. Features were scaled (centred around 0, standard deviation of 1) and redundancy filtering was performed (r=0.95). Supervised feature selection was performed using variable hunting with variable importance, which was repeated 1,000 times, selecting the top 2 features (i.e. 1 feature per 10 subjects) ranked in terms of occurrence. A Cox proportional hazards regression model using selected radiomic features and clinical characteristics (age and HPV status) was fitted on the training dataset and validated in the external validation set. Model performances are expressed by the concordance-index (C-index).

    **Results**: Based on the EORTC dataset, a radiomic signature with the features sphericity (shape) and interquartile range (first order) was constructed and returned a C-index of 0.69. External validation in the Unicancer dataset resulted in a C-index of 0.70. Vice versa, the Unicancer radiomic signature using the features cluster prominence (grey level cooccurrence matrix) and grey level non-uniformity normalised (grey level run length matrix) resulted in a C-index of 0.73. External validation in the EORTC dataset resulted in a C-index of 0.60. Clinical characteristics alone were unable to predict overall survival with C-indexes for the EORTC and Unicancer models of 0.53 (Unicancer validation: 0.32) and 0.66 (EORTC validation: 0.47), respectively. The combination of radiomic features and clinical characteristics resulted in overfitted models with C-indexes for the EORTC and Unicancer model of 0.70 (Unicancer validation: 0.64) and 0.77 (EORTC validation: 0.57), respectively.
    
    **Conclusion**: Although assessed in two small, but independent, cohorts, a [18F]FDG-PET radiomic signature seems promising for the prediction of overall survival in HNSSC treated with neoadjuvant afatinib. The robustness and clinical applicability of this radiomic signature will be further investigated by increasing the Unicancer cohort by 20 patients.

---