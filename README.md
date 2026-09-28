# obesity-prediction-bangladesh-ml
Machine learning pipeline and comparative analysis for predicting obesity among Bangladeshi women using national health survey data, featuring feature selection via XGBoost and SHAP.

# Predicting Obesity Risk Among Bangladeshi Women Using Machine Learning

This repository contains the Python code and implementation details for a research project investigating the socioeconomic determinants of obesity among women of reproductive age in Bangladesh [^1].

## Project Overview
Obesity is an escalating public health concern, contributing significantly to chronic health issues such as cardiovascular diseases and diabetes. Utilizing data from the Bangladesh Demographic and Health Survey (BDHS), this project explores various machine learning and deep learning algorithms to predict obesity outcomes based on demographic and socioeconomic factors.

## Key Highlights
* **Dataset:** Extracted and preprocessed data from the 2022 BDHS dataset [^2].
* **Feature Selection:** Applied correlation analysis and XGBoost combined with SHAP (SHapley Additive exPlanations) to identify key determinants such as age, wealth group, partner occupation, and division.
* **Models Explored:** Evaluated multiple classification techniques including Decision Tree, Random Forest, K-Nearest Neighbors, Logistic Regression, Support Vector Machine, XGBoost, Multilayer Perceptron (MLP), TabNet, and a stacked ensemble model.
* **Key Findings:** Demonstrated that ensemble methods like Random Forest yield high predictive performance in identifying obesity risks.

## Requirements
* Python 3.x
* Libraries: `pandas`, `numpy`, `scikit-learn`, `xgboost`, `shap`, `pytorch-tabnet`, `tensorflow`, `seaborn`, `matplotlib`

## Usage
You can run the Jupyter Notebook directly in **Google Colab** by clicking the badge or download the `.ipynb` file to execute locally. Ensure you have access to the required dataset files or update the data loading path accordingly.

## Citation
If you use this code or reference this project in your research, please reach out to the corresponding author for the report submitted to the Department of Mathematical and Physical Sciences, East West University.

[^1]: Nahar, S. (2025). Comparative Analysis of Machine Learning Models in Predicting Obesity Risk among Bangladeshi Women. East West University.
[^2]: https://dhsprogram.com/data/dataset/Bangladesh_Standard-DHS_2022.cfm
