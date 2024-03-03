# WiDS-Datathon-2024-Challenge-1

**Breast Cancer Diagnosis Timelines Prediction**
This repository contains code and data for predicting breast cancer diagnosis timelines using machine learning techniques. The dataset includes patient demographics, diagnosis and treatment information, socio-economic factors, and environmental data such as air quality. The goal is to predict whether a patient received a metastatic cancer diagnosis within 90 days of screening.

**Dataset Description**:
The dataset consists of approximately 39,000 records split into training and test sets.
Features include patient demographics, diagnosis codes, treatment information, socio-economic factors, and environmental data.
Target variable: Diagnosis Period Less Than 90 Days (indicating whether cancer was diagnosed within 90 days).
Approach:

**Data preprocessing**: Handling missing values, feature selection, and data cleaning.
**Model selection**: Trying various machine learning algorithms including CatBoost, XGBoost, and AutoGluon.
**Evaluation**: Assessing model performance using metrics such as AUC-ROC.
**Prediction**: Generating predictions for the test dataset to assess model generalization.
**Conclusion**:
CatBoost emerges as the top-performing model, showcasing its effectiveness in predicting breast cancer diagnosis timelines. The insights gained from this analysis can inform healthcare professionals and policymakers in improving early detection and treatment strategies for breast cancer patients.

