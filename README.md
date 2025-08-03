# Titanic Survival Model Comparison

This project compares different machine learning models to predict passenger survival in the Titanic dataset. It includes both classification and regression models and evaluates their performance using appropriate metrics such as **accuracy** and **RMSE**.

---

## 📦 Dataset

The dataset used is the classic Titanic dataset (`titanic.csv`) containing features such as:

- Passenger class
- Sex
- Age
- Fare
- Embarked location
- and others

The target variable is:

- `Survived` (0 = No, 1 = Yes)

---

## 🔧 Models Compared

The following models are trained and evaluated:

- `LogisticRegression` (Classification)
- `KNeighborsClassifier` (Classification)
- `LinearRegression` (Regression)
- `KNeighborsRegressor` (Regression)

---

## 🧪 Evaluation Metrics

Each model is evaluated using the correct metric type:

- **Classification Models** → Accuracy Score
- **Regression Models** → Root Mean Squared Error (RMSE)

The script identifies the best model in each category:
- Highest accuracy for classification
- Lowest RMSE for regression

---

## 🚀 How to Run

1. Make sure you have Python 3 and the following packages installed:

```bash
pip install pandas numpy scikit-learn
