# Wine Quality Prediction (Classification & Regression)

## Overview

This project is focused on predicting the quality of wine using machine learning models. The goal is to predict the quality of wine based on physicochemical properties (like pH, alcohol content, sulfur dioxide levels, etc.). The project explores both **classification** and **regression** techniques to build accurate models for wine quality prediction.

- **Classification Task**: Predict whether a wine belongs to a certain quality category (low, medium, high).
- **Regression Task**: Predict the exact quality score of a wine.

## Objective

The main objective of this project is to:
- Apply machine learning models to classify and predict the quality of wine.
- Compare the performance of different algorithms, including **Logistic Regression**, **K-Nearest Neighbors (K-NN)**, and **Decision Tree**.
- Evaluate models based on their performance on both classification and regression tasks.

## Dataset

The dataset used for this project is derived from the Wine Quality dataset available on the UCI Machine Learning Repository. It contains **red** and **white** wine samples, each with various features like alcohol content, acidity, density, pH, residual sugar, etc., and a quality score (from 0 to 10).

### Features:
- **Fixed Acidity**
- **Volatile Acidity**
- **Citric Acid**
- **Residual Sugar**
- **Chlorides**
- **Free Sulfur Dioxide**
- **Total Sulfur Dioxide**
- **Density**
- **pH**
- **Sulphates**
- **Alcohol**

### Target:
- **Quality**: A score from 0 to 10 indicating the quality of the wine.

## Techniques Used

### 1. **Logistic Regression**
   - Used for classification, Logistic Regression helps to model the probability of wine quality belonging to a specific class based on input features.

### 2. **K-Nearest Neighbors (K-NN)**
   - A non-parametric algorithm that classifies wine samples based on the proximity to other labeled samples. It is used here to classify wines based on their features.

### 3. **Decision Tree**
   - A tree-based model that splits the data into subsets based on feature values, helping in both classification and regression tasks.


## Installation

To set up the environment and run the project, follow the steps below:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/niamat-sirrou/WineQuality_Classification_Regression
   cd WineQuality_Classification_Regression
