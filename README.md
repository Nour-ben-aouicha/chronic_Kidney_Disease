# 🩺 Chronic Kidney Disease Identification Project 🩺

## Project Overview
In this project, we addressed the classification problem of identifying whether an individual might have chronic kidney disease based on symptoms diagnosis. The methodology followed the insights from two scientific articles, incorporating various machine learning techniques for data preparation, feature selection, and model evaluation.

## Data Preparation
Drawing inspiration from scientific articles, data preparation involved thorough techniques such as handling missing values, detecting outliers, and data normalization. Feature selection was a critical step, incorporating a Correlation Matrix (Correlation-based Feature Selection - CFS) from the first article and Recursive Feature Elimination (RFE) from the second article.

## Modeling
In the first article, we applied multiple machine learning models, including Naive Bayes (NB), Support Vector Machine (SVM), and k-Nearest Neighbors (KNN), both with and without feature selection (CFS). The second article extended the modeling phase by introducing additional models: Adaboost optimizer, Random Forest classifier, Decision Tree classifier, SVM, and KNN, all with feature selection (CFS).

## ML Techniques and Models
### From the First Article
- Naive Bayes (NB)
- Support Vector Machine (SVM)
- k-Nearest Neighbors (KNN) <br>
**NB: All being trained with and without the Feature Selection (CFS)**

### From the Second Article
- Naive Bayes (NB)
- Support Vector Machine (SVM)
- k-Nearest Neighbors (KNN) 
- Random Forest classifier
- Decision Tree classifier <br>
**NB: For some of these models we also used the Adaboost optimizer.**

## Evaluation
The models' performances were assessed using various machine learning evaluation metrics, providing insights into their effectiveness in identifying chronic kidney disease. This comprehensive approach allowed for a thorough comparison of different models and techniques, contributing to robust decision-making in disease diagnosis.

Feel free to delve into the project details and explore the report above! 🩺📊
