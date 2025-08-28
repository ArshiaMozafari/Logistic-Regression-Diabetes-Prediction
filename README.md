# Logistic-Regression-Diabetes-Prediction
This project explores logistic regression applied to the Diabetes dataset, showcasing the iterative process of improving model performance with a focus on recall.
# Diabetes Prediction Using Logistic Regression

## Overview

This project uses **logistic regression** to predict the likelihood of diabetes onset based on various health metrics. The dataset contains features such as glucose levels, BMI, age, and more, aiming to assist in early detection and preventive healthcare.

## 📊 Dataset

The dataset used in this project is sourced from [insert dataset source here]. It contains the following features:

- **Pregnancies**: Number of times pregnant  
- **Glucose**: Plasma glucose concentration  
- **BloodPressure**: Diastolic blood pressure (mm Hg)  
- **SkinThickness**: Triceps skin fold thickness (mm)  
- **Insulin**: 2-Hour serum insulin (mu U/ml)  
- **BMI**: Body mass index (weight in kg/(height in m)^2)  
- **DiabetesPedigreeFunction**: Diabetes pedigree function  
- **Age**: Age (years)  
- **Outcome**: Class variable (0 or 1)  

## ⚙️ Methodology

### Data Preprocessing
- Loaded the dataset into a Pandas DataFrame.  
- Handled missing values and performed necessary data cleaning.  

### Feature Scaling
- Applied standard scaling to normalize the feature values, ensuring uniformity and improving model performance.  

### Model Implementation
- Implemented Logistic Regression using Scikit-learn.  
- Evaluated the model's performance using metrics such as **recall score**.  

### Model Evaluation
- Achieved a recall score of **0.82**, indicating a good balance between sensitivity and specificity.  

## 📈 Results

- **Initial Model**: Logistic Regression with default settings achieved a recall score of **0.71** of cross validation scorea and **0.75** of train/test split recall.
- **Model Improvements**: Further tuning and experimentation led to enhanced model performance (0.74 cross validation recall score, 0.82 train/test split recall)

## Key Insights

- Logistic regression is a **strong baseline** for binary classification tasks.  
- **Recall optimization** is crucial in medical datasets.  
- Iterative experimentation improves model performance without sacrificing interpretability.


## How to Run

```bash
# Clone the repository
git clone https://github.com/ArshiaMozafari/Logistic-Regression-Diabetes-Prediction.git
cd Logistic-Regression-Diabetes-Prediction

# Install dependencies
pip install -r requirements.txt

# Launch the notebook
jupyter notebook
