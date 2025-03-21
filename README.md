# DSML Capstone: Heart Disease Prediction

![Heart Giphy](https://github.com/user-attachments/assets/9ec55a36-5020-4297-b900-e7176bfe13d1)

## Background:

Cardiovascular diseases are the primary cause of death throughout the world (approximately 20.5 million deaths), & carry large health care costs, with cost estimates over $400B for the period of 2018-2019. While preventive and medical interventions are effective in reducing cardiovascular disease, screening to diagnose heart disease before it becomes clinically apparent can reduce both the medical and economic burden. An ML predictive model would be instrumental as an early warning system against heart disease, the world's number one killer.

## Project Overview
This capstone project focuses on building a robust predictive model to assess the likelihood of heart disease in patients. Leveraging a large and imbalanced dataset, various machine learning techniques were employed to improve prediction accuracy. The project involved extensive data preprocessing, feature engineering, and model evaluation to enhance performance.

## Data Science Methodology

### 1. Data Collection & Preprocessing [Book1](https://github.com/FrankF2025/DSML_Capstone_Heart_Disease/blob/main/1.%20Exploratory%20Data%20Analysis.ipynb), [Book2](https://github.com/FrankF2025/DSML_Capstone_Heart_Disease/blob/main/2.%20Binary%20Conversion.ipynb)
- **Dataset:** Acquired a heart disease dataset from the Centre for Disease Control (CDC), on the [Kaggle](www.kaggle.com) website, containing over 300,000 patient records.
- **Data Cleaning:** Handled missing values and removed inconsistencies.
- **Data Conversion:** Yes and No responses were converted to 1 and 0, respectively to facilitate analysis [Book2](https://github.com/FrankF2025/DSML_Capstone_Heart_Disease/blob/main/2.%20Binary%20Conversion.ipynb).
- **Feature Engineering:** Converted categorical variables into numerical format and scaled continuous features.
- **Handling Imbalance:** Applied **SMOTE (Synthetic Minority Over-sampling Technique)** [Book5](https://github.com/FrankF2025/DSML_Capstone_Heart_Disease/blob/main/5.%20SMOTE.ipynb) and **downsampling** [Book4](https://github.com/FrankF2025/DSML_Capstone_Heart_Disease/blob/main/4.%20Downsampling.ipynb) to balance the dataset.

### 2. Exploratory Data Analysis (EDA) [Book1](https://github.com/FrankF2025/DSML_Capstone_Heart_Disease/blob/main/1.%20Exploratory%20Data%20Analysis.ipynb)
- **Correlation Analysis:** Assessed relationships between risk factors (smoking, alcohol drinking, gender, race and other medical conditions).
- **Statistical Insights:** Used chi-square tests, Cramer's V and Contingency Tables to understand significant predictors.
- **Visualization:** Created histograms, bar graphs, pie graphs and heatmaps to uncover trends in heart disease occurrence.

### 3. Model Development
- **Baseline Models:** Implemented Logistic Regression and Decision Trees as initial benchmarks.
- **Advanced Models:** Developed **Random Forest** [Book3](https://github.com/FrankF2025/DSML_Capstone_Heart_Disease/blob/main/3.%20Random%20Forest%20Classifier%20-%20Imbalance.ipynb), **XGBoost, and Neural Networks** for improved accuracy.
- **Deep Learning:** Integrated a **multi-layer perceptron (MLP) neural network** [Book4](https://github.com/FrankF2025/DSML_Capstone_Heart_Disease/blob/main/4.%20Downsampling.ipynb) to enhance prediction capabilities.
- **Hyperparameter Tuning:** Used Grid Search, Randomized Search and Balanced Random Forest [Book6](https://github.com/FrankF2025/DSML_Capstone_Heart_Disease/blob/main/6.%20Balanced%20Random%20Forest%20Classifier%20%26%20AUC.ipynb) to optimize model parameters.

### 4. Model Evaluation
- **Performance Metrics:**
  - Achieved **ROC-AUC: 0.83** using the best-performing model.
  - Compared models using Precision, Recall, F1-score, and Confusion Matrices.
- **Feature Importance:**
  - Identified top predictive features: Age, Gender, Smoking, Alcohol Drinking.
- **Cross-Validation:** Applied k-fold cross-validation to ensure model generalizability.

### 5. Results & Insights
- The **Random Forest model** provided strong interpretability with a balance of precision and recall.
- **Deep learning models** improved overall ROC-AUC but required careful tuning due to overfitting risks.
- Key Takeaway: **Feature selection and handling class imbalance significantly impacted model performance.**

## Future Work
- **Enhancing Feature Engineering:** Investigate additional medical variables to improve model accuracy.
- **Deploying the Model:** Convert the trained model into an API for real-world applications.
- **Exploring Explainability:** Utilize LIME and SHAP more extensively for black-box models like deep learning.

## Contact
For further discussion or collaboration, reach out through GitHub.

---

This project showcases expertise in **data preprocessing, EDA, machine learning, deep learning, and model interpretability**, making it a valuable portfolio piece for Data Science roles.
