# Kiva Crowdfunding Data Science Project

## Overview

This project presents an end-to-end Data Science workflow using the **Kiva Loans** dataset. The objective is not only to build a machine learning model but also to demonstrate a complete industry-oriented Data Science pipeline, from business understanding and exploratory data analysis to model development and business recommendations.

The repository is designed as a professional portfolio project that follows real-world Data Science practices, emphasizing reproducibility, maintainability, and business-driven decision making.

---

## Objectives

* Understand the business context behind Kiva crowdfunding.
* Explore and assess data quality.
* Perform data cleaning and feature engineering.
* Develop and compare machine learning models.
* Interpret model performance.
* Provide actionable business recommendations based on analytical findings.

---

## Dataset

This project uses the **Kiva Loans** dataset provided by Kaggle.

**Dataset Source**

https://www.kaggle.com/datasets/kiva/data-science-for-good-kiva-crowdfunding

For this project, the analysis is performed using the provided **Parquet** dataset.

---

## Project Structure (RAWWW)

```text
project-root/
│
├── data/
│   ├── raw/                # Original dataset
│   ├── interim/            # Intermediate processed data
│   ├── processed/          # Final datasets for modeling
│   └── external/           # External supporting data (if required)
│
├── notebooks/ 
│   ├── 01_data_understanding.ipynb
│   ├── 02_data_preprocessing_feature_engineering.ipynb
│   ├── 03_model_development.ipynb
│   ├── 04_model_evaluation_interpretation.ipynb
│   └── 05_business_recommendation.ipynb
│
├── src/
│   ├── config/
│   ├── data/
│   ├── features/
│   ├── models/
│   ├── visualization/
│   ├── pipelines/
│   └── utils/
│
├── models/                 # Saved models and preprocessing objects
├── reports/                # Figures and final reports
├── docs/                   # Project documentation
├── tests/                  # Testing scripts
│
├── requirements.txt
├── README.md
├── .gitignore
└── LICENSE
```

---

## Workflow

The project follows a structured end-to-end workflow:

1. **Business & Data Understanding**
2. **Exploratory Data Analysis (EDA)**
3. **Data Cleaning & Preprocessing**
4. **Feature Engineering**
5. **Model Development**
6. **Model Evaluation & Interpretation**
7. **Business Recommendation**

---

## Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* SHAP
* Jupyter Notebook

---

## Repository Goals

This repository demonstrates:

* End-to-end Data Science workflow
* Business-oriented problem solving
* Feature engineering
* Machine learning model development
* Model interpretation
* Professional project organization
* Reproducible analysis

Rather than focusing solely on model performance, this project emphasizes decision-making, explainability, and practical business value.

---

## License

This project is intended for educational and portfolio purposes.

Dataset ownership remains with the original Kiva Data Science for Good initiative and its respective contributors.
