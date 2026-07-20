# Medical Insurance Cost Prediction

### Multiple Linear Regression

## Objective

The objective of this project is to develop a Multiple Linear Regression model to predict medical insurance charges based on customer information such as age, sex, BMI, number of children, smoking status, and region.

---

## Dataset

**Medical Cost Personal Insurance Dataset**

**Kaggle Link:**  
https://www.kaggle.com/datasets/mirichoi0218/insurance

---

## Libraries Used

- pandas
- numpy
- matplotlib
- scikit-learn

---

## Methodology

1. Loaded the insurance dataset using Pandas.
2. Displayed the first five records.
3. Identified numerical, categorical, and target variables.
4. Checked for missing values.
5. Encoded categorical variables using One-Hot Encoding.
6. Split the dataset into 80% training and 20% testing.
7. Built a Multiple Linear Regression model.
8. Predicted insurance charges for the test dataset.
9. Evaluated the model using:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score
10. Visualized the model performance using an Actual vs Predicted scatter plot.

---

## Results

| Metric | Value |
|--------|------:|
| Mean Absolute Error (MAE) | 4181.19 |
| Mean Squared Error (MSE) | 33596915.85 |
| R² Score | 0.7836 |

---

## Repository Structure

```text
Medical-Insurance-Cost-Prediction/
│
├── Assignment-1.ipynb
├── README.md
└── .gitignore
```

---

## Conclusion

This project demonstrates the use of Multiple Linear Regression for predicting medical insurance charges. The model uses customer information such as age, BMI, smoking status, number of children, sex, and region to estimate insurance costs. Among these factors, smoking status has the greatest influence on insurance charges, followed by age and BMI. The model provides a good baseline for prediction; however, it assumes a linear relationship between the input features and the target variable. More advanced machine learning algorithms such as Random Forest or XGBoost can be used to improve prediction accuracy.

---


