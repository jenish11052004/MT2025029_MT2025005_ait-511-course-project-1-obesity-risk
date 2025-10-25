# Obesity Risk Prediction

A machine learning project to predict obesity risk levels based on individual characteristics, eating habits, and physical condition.

## 📋 Project Overview

This project develops predictive models to classify individuals into different obesity risk categories using various machine learning algorithms. The solution addresses the growing concern of obesity by providing an automated risk assessment tool.

## 🎯 Objectives

- Build accurate machine learning models for obesity risk prediction
- Compare performance of different algorithms (XGBoost, Random Forest, etc.)
- Identify key factors contributing to obesity risk
- Create an ensemble model for improved prediction accuracy

## 📊 Dataset

The dataset contains various features related to:
- **Demographics**: Age, Gender, Height, Weight
- **Eating Habits**: Frequency of consumption of high-calorie food, vegetables, main meals, etc.
- **Physical Condition**: Family history, FAF (Physical Activity Frequency), TUE (Time Using Technology Devices)
- **Lifestyle Factors**: Smoking, Alcohol consumption, Transportation used

### Target Variable
Obesity risk levels including:
- Insufficient Weight
- Normal Weight
- Overweight Level I
- Overweight Level II
- Obesity Type I
- Obesity Type II
- Obesity Type III

## 🛠️ Installation

### Prerequisites
- Python 3.8+
- pip package manager

### Setup
```bash
# Clone the repository
git clone https://github.com/jenish11052004/MT2025029_MT2025005_ait-511-course-project-1-obesity-risk.git
cd MT2025029_MT2025005_ait-511-course-project-1-obesity-risk

# Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
