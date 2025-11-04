# SONAR Rock vs Mine Prediction

A machine learning project that uses Logistic Regression to classify underwater objects as either rocks or mines based on sonar signal data. This implementation addresses a critical military defense scenario where submarines need to accurately distinguish between underwater mines and natural rock formations.

## 📋 Project Overview

In a simulated warfare scenario, this system helps submarines detect enemy mines planted in ocean waters by analyzing sonar return signals. The model processes frequency data from sonar echoes to classify objects as either:
- **Mine (M)** 💣 - Metal cylinders representing explosives
- **Rock (R)** 🗿 - Natural rock formations

## Technical Implementation

### Features
- **Data Processing**: Handles the classic UCI Sonar Dataset with 208 instances and 60 frequency features
- **Model Training**: Implements Logistic Regression for binary classification
- **Model Evaluation**: Achieves 76% accuracy on test data with proper train-test splitting
- **Predictive System**: Ready-to-use prediction pipeline for new sonar readings

### Tech Stack
- **Python** with scikit-learn, pandas, numpy
- **Logistic Regression** for binary classification
- **Stratified Sampling** to maintain class balance
- **Model Evaluation** using accuracy_score metric

## 📊 Dataset Details
- **208 samples** with 60 frequency features each
- **Balanced classes (almost)**: 111 Mines vs 97 Rocks
- **Features**: Normalized sonar return frequencies (0-1 scale)
- **Target**: Binary classification (M/R)
