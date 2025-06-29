# Wine-Quality-Prediction
This project uses machine learning techniques to predict the quality of wine based on physicochemical properties. The dataset includes features like acidity, alcohol content, sugar level, pH, and more. The model helps classify wine quality scores and can assist producers and analysts in quality control and product assessment.
📌 Project Overview

The main objective is to build a predictive model that estimates wine quality using features such as acidity, sugar content, alcohol, and more. The notebook includes data preprocessing, exploratory analysis, model training, and evaluation.
📁 Dataset Description

The dataset contains various physicochemical properties of wine, including:
Feature	Description
fixed acidity	Tartaric acid level
volatile acidity	Acetic acid content
citric acid	Citric acid level
residual sugar	Sugar remaining after fermentation
chlorides	Salt concentration
free sulfur dioxide	SO₂ that prevents microbial growth
total sulfur dioxide	Sum of free and bound forms
density	Wine density
pH	Acidity level
sulphates	Antimicrobial agent
alcohol	Alcohol content (%)
quality	Wine quality score (target)

Source: UCI Machine Learning Repository – Wine Quality Dataset
🧠 ML Workflow

    Data Preprocessing

        Handling missing values (if any)

        Feature scaling and normalization

        Train/test split

    Exploratory Data Analysis (EDA)

        Correlation heatmaps

        Distribution plots

        Boxplots and pairplots

    Model Training

        Logistic Regression

        Random Forest Classifier

        Support Vector Machine

        XGBoost (optional)

    Evaluation

        Confusion Matrix

        Accuracy Score

        Precision, Recall, F1-Score

📊 Model Output

Sample results from testing different models:
Model	Accuracy
Logistic Regression	65%
Random Forest	72%
SVM	68%
XGBoost	74%
