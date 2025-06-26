# Heart Disease Prediction Project

## Overview

This project aims to predict whether a person is likely to suffer from heart disease based on their medical and demographic data. The model uses supervised learning algorithms, including Decision Tree, Random Forest, Support Vector Classifier (SVC), and K-Nearest Neighbors (KNN), to classify individuals based on the given dataset.

## Features

+ Implementation of multiple machine learning algorithms.

+ Performance comparison of models based on accuracy.

+ Preprocessing of data for optimal model performance.

+ Visualization of results and key insights.

## Dataset

The dataset used in this project contains several features relevant to heart disease, such as:

+ age: Age of the person.

+ sex: Gender (1 = male, 0 = female).

+ cp: Chest pain type (0, 1, 2, 3).

- trestbps: Resting blood pressure (in mm Hg).

- chol: Serum cholesterol level (in mg/dl).

- fbs: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false).

- restecg: Resting electrocardiographic results (values 0, 1, 2).

- thalachh: Maximum heart rate achieved.

- exang: Exercise-induced angina (1 = yes; 0 = no).

- oldpeak: ST depression induced by exercise relative to rest.

- slope: Slope of the peak exercise ST segment (0, 1, 2).

- ca: Number of major vessels (0-3) colored by fluoroscopy.

- thal: Thalassemia (1 = normal; 2 = fixed defect; 3 = reversible defect).

- target: Presence of heart disease (1 = yes, 0 = no).

## Source

UCI Health Dataset Kaggle

## Algorithms Used

1. Decision Tree

   + A tree-based model for decision-making and classification.

2. Random Forest

   + An ensemble learning method combining multiple decision trees.

3. Support Vector Classifier (SVC)

   + A supervised learning model that finds the optimal hyperplane for classification.

4. K-Nearest Neighbors (KNN)

   + A simple, non-parametric algorithm that classifies based on the nearest neighbors.


## Results
### Model                                            Accuracy
+ Decision Tree : 96%
+ Random Forest : 96%
+ SVC : 93%
+ KNN : 95%
