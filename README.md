# 🍽️ Restaurant Rating Prediction using Machine Learning

This project is part of **Cognifyz Level 3 – Task 1**. It focuses on building and evaluating **supervised regression models** to predict the **aggregate rating** of restaurants using key features available in the dataset. The solution involves preprocessing data, training multiple machine learning models, and comparing their performance using industry-standard metrics.

---

## 🚀 Project Goal

To build a machine learning pipeline that:

- Predicts the **aggregate rating** of a restaurant.
- Uses available features such as votes, average cost, and service availability.
- Trains and evaluates multiple regression algorithms.
- Compares the models based on **R² score** and **RMSE**.
- Visualizes performance through clear and insightful charts.

---

## 📦 Dataset

The dataset is assumed to be named: `Dataset .csv`

### 🔍 Columns Used:

| Feature               | Description                               |
|-----------------------|-------------------------------------------|
| `Votes`               | Total number of customer votes            |
| `Average Cost for two`| Average spending for two people           |
| `Price range`         | Price category of the restaurant          |
| `Has Online delivery` | Whether online delivery is available      |
| `Has Table booking`   | Whether table booking is available        |
| `Aggregate rating`    | ⭐ Target variable (rating out of 5)       |

---

## 🧠 Machine Learning Models Used

This project compares three popular supervised learning regression algorithms:

1. **Linear Regression**
   - Assumes a linear relationship between input and output.
2. **Decision Tree Regressor**
   - Non-linear model that splits data based on feature thresholds.
3. **Random Forest Regressor**
   - Ensemble of decision trees to reduce overfitting and improve accuracy.

---

## 📈 Evaluation Metrics

To measure how well the model predicts ratings:

- **R² Score (Coefficient of Determination)**  
  Measures the proportion of variance explained by the model. Closer to 1 is better.

- **RMSE (Root Mean Squared Error)**  
  Measures the average prediction error. Lower is better.

---

## 🧪 Model Training Pipeline

1. Upload dataset to Google Colab.
2. Clean the data and remove nulls/duplicates.
3. Encode categorical variables if necessary.
4. Select key features and split into train/test sets.
5. Train Linear Regression, Decision Tree, and Random Forest models.
6. Predict and evaluate using R² Score and RMSE.
7. Plot visual comparison of all models.

---

## 📊 Output Example

Bar charts will be displayed to compare:

- R² scores of all models
- RMSE of all models

These help visually identify the best performing algorithm.

---

## ⚙️ Installation

You can install required libraries with the following command:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
