# 🏥 Medical Insurance Cost Prediction

A machine learning project that predicts medical insurance charges using demographic and lifestyle-related features.

## 📌 Overview

This project demonstrates a regression-based approach for predicting medical insurance costs using Multiple Linear Regression.

The model uses features such as age, BMI, smoking status, number of children, sex, and region to estimate insurance charges.

## 🎯 Objective

- Load and explore the insurance dataset
- Identify numerical and categorical features
- Check for missing values
- Encode categorical variables
- Split the dataset into training and testing sets
- Train a Multiple Linear Regression model
- Evaluate prediction performance

## 📊 Dataset

The dataset contains **1,338 records** and the following features:

| Feature | Description |
|---|---|
| `age` | Age of the individual |
| `sex` | Sex of the individual |
| `bmi` | Body Mass Index |
| `children` | Number of children |
| `smoker` | Smoking status |
| `region` | Residential region |
| `charges` | Medical insurance charges (target) |

The dataset contains **no missing values**.

> The dataset file is not included in this repository. The notebook expects the dataset to be available as `insurance.csv`.

## ⚙️ Methodology

### 1. Data Preparation

- Loaded the dataset using Pandas
- Inspected dataset shape and data types
- Checked for missing values
- Separated features and target variable

### 2. Preprocessing

Categorical features were encoded using `OneHotEncoder`:

```text
sex
smoker
region
