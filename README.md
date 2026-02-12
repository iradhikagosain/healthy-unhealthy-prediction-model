# healthy-unhealthy-prediction-model

# Population Health Risk Classification using Machine Learning

This project focuses on building a predictive classification system to identify individuals as **healthy** or **unhealthy** based on biomedical and lifestyle indicators. The dataset contains health records from 9,800 participants collected across multiple observational studies, including physiological measurements, lifestyle attributes, and medical history features.

## Objective

Develop a reliable machine learning pipeline to support biomedical research decisions such as participant selection for clinical trials and risk-based population stratification.

## Approach

* Performed data preprocessing, missing value handling, encoding of categorical variables, and feature scaling.
* Implemented and compared multiple supervised learning algorithms:

  * Logistic Regression
  * K-Nearest Neighbors (KNN)
  * Random Forest
  * Support Vector Machine (SVM)
  * AdaBoost
* Evaluated models using classification metrics including accuracy, precision, recall, and confusion matrix analysis.

## Results

* Achieved **95% accuracy** using AdaBoost combined with Support Vector Classifier (SVC).
* The model demonstrates strong generalization performance for health risk classification tasks.

## Tech Stack

Python, Scikit-Learn, Pandas

## Impact

This project showcases how machine learning can assist biomedical researchers in improving participant selection, enabling data-driven health risk assessment and population analysis.
