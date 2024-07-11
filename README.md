# Heart Disease Prediction

## Introduction

This project aims to predict the risk of heart disease development using various machine learning algorithms. The dataset used contains over 4000 records with 14 attributes related to heart disease determinants, including demographic aspects, behavioral aspects, medical history, and current medical conditions.

## Exploratory Data Analysis Conclusions

- No obvious correlation between education level and tobacco usage.
- Males have a higher frequency of coronary heart disease development.
- Systolic and diastolic pressure have a clear positive correlation.
- The correlation between age and cholesterol has a steady positive trend.
- Glucose and diabetes are highly correlated.
- Patients aged 30-40 have a higher tendency to smoke.
- The lower the education level, the higher the frequency of heart disease development within the samples.
- Higher average consumption of cigarettes for patients with heart disease than those without.
- No relationship between BMI and heart disease.
- Having more medical issues doesn’t necessarily increase the risk of developing heart disease.
- The older the patient, the higher the frequency of heart disease within the samples.

## Machine Learning Problem Formulation

### Problem Statement

The main aim is to solve the classification problem of whether a patient has the risk of developing heart disease within 10 years (1 for yes and 0 for no).

### Algorithms Deployed

1. **Logistic Regression**
2. **Decision Tree Classifier**
3. **K-Nearest Neighbor (KNN)**
4. **Random Forest Classifier**
5. **Support Vector Machine (SVM)**
6. **Extreme Gradient Boost (XGBoost)**
7. **Naïve Bayes**

### Accuracy Improvement

- **Feature Selection**: Selected important features and eliminated redundant and irrelevant ones.
- **Feature Scaling**: Scaled features to improve the machine learning model.
- **Stack CV Classifier**: Combined multiple classification models via a meta-classifier.
- **Cross Validation**: Used to test models using limited training data and prevent overfitting.

## Machine Learning Flowchart

![Machine Learning Flowchart](path/to/flowchart.png)

## Results and Discussions

### Machine Learning Model Analysis

- **Logistic Regression**: Accuracy - 86.82%
- **Decision Tree**: Accuracy - 83.72%
- **K-Nearest Neighbor**: Accuracy - 87.21%
- **Random Forest**: Accuracy - 87.21%
- **Support Vector Machine**: Accuracy - 87.08%
- **Extreme Gradient Boost**: Accuracy - 87.08%
- **Naïve Bayes**: Accuracy - 85.92%

### Accuracy Improvement Processes

- **Feature Selection**: Improved accuracy for logistic regression to 87.6%.
- **Feature Scaling**: Further improved logistic regression accuracy to 87.8%.
- **Stack CV Classifier**: Resulted in an accuracy of 87.46%.
- **Cross Validation**: Highest accuracy achieved was 88.37%.

## Conclusion

In this project, seven classifier models and four improvement methods were deployed to find the best model for predicting a person's risk of coronary heart disease. The best model yielded an accuracy of 88.4% after applying cross-validation.

## Contributors

- **Betty Yuliani** - Data Analysis, Model Development
- **Daniel Agbay** - Data Preprocessing, Feature Engineering
- **Ekam Behl** - Model Evaluation, Accuracy Improvement
- **Gia Phu Tran** - Data Visualization, Documentation
- **Owen Tsao** - Algorithm Implementation, Code Optimization
