# Titanic Exploratory Data Analysis (EDA)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SnowArchitect60/EDA-with-ML/blob/main/EDA_and_ML_Titanic.ipynb)

This repository contains the supplementary notebook for the lecture on **Exploratory Data Analysis (EDA)**.

The notebook walks through the complete EDA workflow discussed in the lecture, then applies what we learn to build a machine learning model. We use the **Titanic** dataset—a classic machine learning dataset where the goal is to predict whether a passenger survived the disaster.

> Dataset: https://www.kaggle.com/competitions/titanic

---

## What you'll learn

| Section | Topics |
|---------|--------|
| **1. Problem Statement & Data Collection** | Define the problem, obtain and load the dataset |
| **2. Exploration & Data Cleaning** | Dataset overview, data types, duplicates, irrelevant columns |
| **3. Univariate Analysis** | Understanding the distribution of individual variables |
| **4. Bivariate & Multivariate Analysis** | Exploring relationships between variables |
| **5. Feature Engineering** | Handling missing values, treating outliers, creating new features, scaling |
| **6. Feature Selection** | Identifying the most informative predictors |
| **7. Machine Learning Model** | Training, evaluating, and interpreting a classification model |

---

## Setup

This project uses **uv** for dependency management.

```bash
uv sync
````

## Repository Structure

```
EDA-with-ML
├── .gitignore
├── .python-version
├── EDA_and_ML_Titanic.ipynb
├── pyproject.toml
├── README.md
└── uv.lock
```

---

## License

CC BY 4.0. This repository is intended for educational purposes.