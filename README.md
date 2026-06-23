# Titanic Survival Prediction 🚢

## Project Overview

This project predicts whether a passenger survived the Titanic disaster using a **Logistic Regression** machine learning model. The project includes data cleaning, exploratory data analysis (EDA), feature engineering, and model evaluation.

---

## Dataset

The dataset contains passenger information such as:

* Passenger Class (Pclass)
* Gender (Sex)
* Age
* Fare
* Family Information (SibSp, Parch)
* Embarkation Port (Embarked)
* Survival Status (Target Variable)

---

## Data Preprocessing

* Filled missing values in **Age** using the median.
* Filled missing values in **Embarked** using the mode.
* Dropped the **Cabin** column due to excessive missing values.
* Encoded categorical features for machine learning.

---

## Exploratory Data Analysis (EDA)

### Key Findings

* Female passengers had a much higher survival rate than males.
* First-class passengers were more likely to survive than third-class passengers.
* Children had better survival chances compared to older passengers.

---

## Machine Learning Model

**Algorithm Used:** Logistic Regression

### Features Used

* Pclass
* Sex
* Age
* SibSp
* Parch
* Fare
* Embarked

### Train-Test Split

* Training Data: 75%
* Testing Data: 25%

---

## Results

### Model Accuracy

**≈ 80.7%**

### Evaluation Metrics

* Accuracy Score
* Classification Report
* Confusion Matrix

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Conclusion

The Logistic Regression model achieved approximately **80.7% accuracy** in predicting Titanic passenger survival. The analysis shows that **gender, passenger class, and age** were the most influential factors affecting survival.

---

**Author:** Tanul Sharma

