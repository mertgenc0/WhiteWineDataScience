# 🍇 White Wine Quality Prediction

This repository contains a data science project focused on predicting the quality of white wines using machine learning models. The project goes through essential steps, including data analysis, data preprocessing, data visualization, and machine learning model implementation.

## 📋 Project Overview

This project uses a dataset containing various chemical properties of white wines, such as acidity, chlorides, and alcohol content, to predict their quality scores. The data is first analyzed and visualized to gain insights into the factors impacting wine quality, then processed for optimal model performance. Finally, different machine learning models are trained and evaluated to determine the best performing model for wine quality prediction.

## Dataset

The dataset used in this project is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality). It contains several physicochemical tests on white wine samples along with their quality ratings.

### Features

The dataset includes the following features:

- **fixed acidity**: Tartaric acid (g/dm³)
- **volatile acidity**: Acetic acid (g/dm³)
- **citric acid**: Citric acid (g/dm³)
- **residual sugar**: Sugar (g/dm³)
- **chlorides**: Sodium chloride (g/dm³)
- **free sulfur dioxide**: Free SO2 (mg/dm³)
- **total sulfur dioxide**: Total SO2 (mg/dm³)
- **density**: Density (g/cm³)
- **pH**: pH value
- **sulphates**: Sulphates (g/dm³)
- **alcohol**: Alcohol (volume %)
- **quality**: Quality (score between 0 and 10)
- 
## Data Analysis 
  Exploratory Data Analysis (EDA) was conducted to understand the dataset and its distribution. Key findings included:
   1. Understanding correlations between features.
   2. Identifying outliers and missing values.
   3. Discovering which features impact the quality score.

## Data Visualization
  To enhance the understanding of the dataset and model performance, various visualizations have been created:
   1. **Heat Map:** Displays the correlation matrix of the features, helping to identify relationships between different attributes and quality scores.
   2. **Scatter Plots:** Visual representations of the relationship between two features, allowing for the observation of trends and distributions.

## Models Used
  The following machine learning models are implemented in this project:
   1. Logistic Regression
   2. Decision Tree Classifier
   3. Support Vector Machine
   4. Random Forest
      
## Evaluation Metrics
  The models are evaluated using the following metrics:
   1. Mean Absolute Error (MAE)
   2. Mean Squared Error (MSE)
   3. Model Accuracy
   4. Model F1 Score
