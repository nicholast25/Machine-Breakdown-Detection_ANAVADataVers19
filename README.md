# Machine Breakdown Detection - Data Science Competition ANAVA DataVers UGM (Universitas Gadjah Mada)

## Overview
This project presents our solution for a data science competition on machine breakdown detection, where our team achieved a Top 9 (waiting list) finish. The objective was to predict machine failures using statistical analysis, feature selection, and machine learning models. Our approach involved handling class imbalance by splitting the dataset into majority and minority cases while ensuring robust evaluation and feature engineering.

## Key Features
1. Non-Parametric Statistical Testing: Applied Kruskal-Wallis and Chi-Square tests to analyze feature significance.
2. Multicollinearity Analysis: Used Variance Inflation Factor (VIF) to detect and remove redundant numerical features.
3. Dimensionality Reduction: Implemented Principal Component Analysis (PCA) that represents at least 80% of data variance to enhance model efficiency.
4. Machine Learning Models: Developed a Random Forest Classifier for robust prediction.
5. Imbalanced Data Handling: Split data into majority and minority classes to improve model learning.

## Results & Insights
1. Significant Features Identified: RPM-1, Machine Type, and Country of Manufacture had the most impact on failure prediction.
2. PCA-transformed components PC2, PC7, PC8, PC10, PC12, PC13, PC14, PC15, PC16, PC17, PC18 correlated with machine deterioration.
