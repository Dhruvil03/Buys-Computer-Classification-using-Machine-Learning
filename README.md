# Buys Computer Classification using Machine Learning 💻📊

A machine learning project that predicts whether a customer will buy a computer based on their demographic and behavioral characteristics using various classification algorithms.

## 🌟 Project Overview

This project implements the K-Nearest Neighbors classification algorithm to predict customer purchasing behavior. The model analyzes customer attributes such as age, income, student status, and credit rating to determine the likelihood of computer purchase, demonstrating KNN algorithm implementation and optimization.

## 🚀 Features

- **KNN algorithm implementation** for customer behavior prediction
- **Customer behavior prediction** based on demographic data
- **Data preprocessing** pipeline for handling categorical and numerical features
- **Model evaluation** with performance metrics and accuracy analysis
- **Advanced visualization** with scatter matrix and 3D scatter plots
- **K-value comparison** with accuracy analysis for different k values
- **K-value optimization** analysis for optimal model performance

## 📊 Dataset

The model uses a customer dataset with the following features:
- **Age** - Customer age group (youth, middle_aged, senior)
- **Income** - Income level (high, medium, low)
- **Student** - Student status (yes, no)
- **Credit Rating** - Credit rating (fair, excellent)
- **Buys Computer** - Target variable (yes, no)

## 🏗️ Algorithm Implemented

The project uses the **K-Nearest Neighbors (KNN)** classification algorithm to predict customer purchasing behavior based on similar customer profiles in the dataset.

## 📈 Model Performance

KNN Classification Results with K-value optimization:

| K Value | Accuracy 
|---------|----------|
| k=2 | [10 %] | 
| k=4 | [10 %] |
| k=5 | [75 %] |
| k=6 | [50 %] | 
| k=8 | [50 %] |
| k=9 | [50 %] |

**Optimal K Value**: k=5 with 75% accuracy

## 🔍 Key Features

### Data Analysis
- Exploratory data analysis (EDA)
- **Scatter matrix** for feature relationship visualization
- **3D scatter plot** for multi-dimensional data exploration
- Data preprocessing and encoding

### Model Development
- KNN algorithm implementation
- **Comprehensive K-value testing** (k=1, 3, 5, 7, 9, etc.)
- **Accuracy comparison across different k values**
- Cross-validation for model validation
- Distance metric selection

### Evaluation
- Confusion matrix analysis
- **K-value accuracy comparison charts**
- **Scatter matrix visualization** for feature relationships
- **3D scatter plots** for data pattern analysis
- Model interpretation and insights

## 🎯 Key Analysis Features

### Visualization Components
- **Scatter Matrix**: Comprehensive pairwise feature relationship analysis
- **3D Scatter Plot**: Multi-dimensional data exploration and pattern recognition
- **K-Value Comparison**: Visual comparison of accuracy across different k values


### K-Value Optimization
The project systematically tests multiple k values to find the optimal parameter:
- Tests odd k values (1, 3, 5, 7, 9, etc.) to avoid ties
- Compares accuracy metrics for each k value
- Identifies the best performing k through cross-validation
- Visualizes the relationship between k and model performance

