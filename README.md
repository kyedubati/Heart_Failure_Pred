# SVM on Heart Disease Failure Prediction

This repository contains the implementation of a Support Vector Machine (SVM) model with a Radial Basis Function (RBF) kernel to predict heart disease failure. The model is trained on a heart disease dataset and achieves an accuracy of 91.85%.

## Project Overview

Heart disease is a global health concern, and early prediction is crucial for better diagnosis and treatment. This project explores the use of SVM, a supervised machine learning algorithm, to classify heart disease occurrences.

### Dataset
The dataset used in this project contains 918 records with various features related to patient health. Some of the critical features include:
- Age
- Sex
- Cholesterol Levels
- Maximum Heart Rate
- Exercise-induced Angina
- Chest Pain Type
- Resting ECG
- ST-Slope

**Dataset Source**: [Kaggle Heart Disease Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)

### Methodology

1. **Support Vector Machine (SVM)**:  
   The SVM classifier with an RBF kernel was used due to its ability to handle both linear and non-linear data. The model was evaluated using metrics such as precision, recall, F1-score, and a confusion matrix.

2. **Principal Component Analysis (PCA)**:  
   PCA was used to reduce the dimensionality of the dataset, retaining only the most critical features.

3. **K-means Clustering**:  
   K-means clustering was applied to identify patterns and subgroups in the data, aiding in risk assessment for heart disease.

### Results

- **Accuracy**: 91.85%
- **Precision for Class 0 (No heart disease)**: 94%
- **Recall for Class 0**: 85%
- **Precision for Class 1 (Heart disease)**: 91%
- **Recall for Class 1**: 96%

### Visualizations

1. PCA plot showing the reduced dimensions of the data.
2. SVM decision boundaries for different feature combinations such as Cholesterol vs. Maximum Heart Rate and Age vs. Cholesterol.

### How to Run the Code

1. Clone this repository:
   ```bash
   git clone https://github.com/kyedubati/Heart_Failure_Pred
