# The Effect of Demographics on Income Outcomes

## Overview
This repository contains my micro-project analyzing how demographic factors influence income classification (>50K vs <=50K). The project uses the Adult Income dataset and applies logistic regression and a multilayer perceptron (MLP) to evaluate predictive power. 

## Content
- **Code**: Python scripts for data preprocessing, logistic regression models, and MLP training/evaluation.
- **Data**: Adult Income dataset (CSV) used for analysis.
- **Results**: Model outputs including accuracy, AUC, and precision metrics. 

## Methods
- Logistic Regression (Model 1: with financial predictors, Model 2: demographics only).
- Multilayer Perceptron (MLP) trained on the same demographic feature set as Model 2. 

## Results
- Model 1: Accuracy = 0.852, AUC = 0.88
- Model 2: Accuracy = 0.833, AUC = 0.90
- MLP: Accuracy = 0.830, AUC = 0.88, Precision = 0.723

## Conclusion
Demographic features significantly affect income classification. The null hypothesis is rejected, and evidence supports the alternative hypothesis. Policy recommendations focus on education access, gender equity, and occupational training. 
