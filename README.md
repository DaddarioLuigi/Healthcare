# ML/DL Healthcare Projects

## Overview
Welcome to our ML/DL Healthcare Projects repository! This repository hosts various machine learning and deep learning projects focusing on healthcare applications. From medical image analysis to predictive diagnostics, we aim to leverage the power of AI to improve patient outcomes, optimize healthcare operations, and advance medical research.

## Projects
Here are some of the key projects within this repository:

1. **Epilepsy Type Classification**
   - **Description:** This project focuses on classifying epilepsy types using EEG signals to assist in accurate diagnosis and treatment planning.
   - **Technologies:** ScikitLearn, Numpy, Pandas, MatPlotLib
   - **Dataset:** EEG datasets labeled with epilepsy types, containing recordings from patients with different types of epilepsy.

2. **Breast Insight - Breast Cancer Segmentation and Classification**
   - **Description:** This project explores a system to support doctors and radiologists in identifying breast masses in MRI images. It combines segmentation using a fine-tuned Segment Anything Model (SAM) with classification based on radiomic features extracted using PyRadiomics. SVM and Random Forest classifiers are compared, including variants using SMOTE to address class imbalance, with hyperparameter tuning and stratified cross-validation.
   - **Technologies:** Segment Anything Model (SAM), PyRadiomics, SVM, Random Forest, SMOTE, GridSearchCV.
   - **Web Service:** The presentation describes a private web application with user registration, login, image upload, segmentation, and classification workflows.
   - **Reported Results:** Mean Dice score of 0.85 and IoU of 0.78 for segmentation; test accuracy of 94.0% and F1 score of 0.902 for the SVM with SMOTE classifier.
   - **Documentation:** [Project presentation](Project2/InsightsBreast.pdf). The repository currently includes the presentation only; source code and datasets are not provided in this folder.
