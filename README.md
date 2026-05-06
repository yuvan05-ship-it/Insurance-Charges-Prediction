# 🧠 Insurance Charges Prediction

## 📌 Project Overview

This project predicts medical insurance charges based on user attributes such as age, BMI, smoking habits, and other personal factors.

The goal is to analyze how different features influence insurance costs and build a machine learning model to estimate charges.

---

## 🎯 Problem Statement

Insurance companies need accurate methods to estimate customer medical costs.
This project aims to develop a predictive model using machine learning to estimate insurance charges based on customer data.

---

## 📊 Dataset Information

The dataset contains 1338 records with the following features:

* **Age** – Age of the individual
* **Sex** – Gender
* **BMI** – Body Mass Index
* **Children** – Number of dependents
* **Smoker** – Smoking status
* **Region** – Residential area
* **Charges** – Insurance cost (Target variable)

---

## 🔍 Exploratory Data Analysis

Performed analysis to understand relationships between variables:

* Age vs Charges
* BMI vs Charges
* Smoker vs Charges
* Distribution of features

### Key Insight:

👉 Smokers have significantly higher insurance charges compared to non-smokers

---

## ⚙️ Data Preprocessing

* Converted categorical data into numerical format using Label Encoding
* Checked for missing values (none found)
* Selected features and target variable

---

## 🤖 Model Building

* Algorithm: **Linear Regression**
* Data split: 80% training, 20% testing
* Model trained on processed dataset

---

## 📈 Model Evaluation

Metrics used:

* R² Score
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)

---

## 📉 Visualization

* Scatter plots for relationships
* Boxplots for categorical comparison
* Prediction line graph (Age vs Charges)

---

## 🚀 Results & Insights

* Smoking is the most influential factor on insurance cost
* Age has a strong positive correlation with charges
* BMI moderately affects charges
* Linear Regression provides a good baseline model

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📁 Project Structure

```
Insurance-Charges-Prediction/
│── insurance.csv
│── Insurance Charges Prediction Project.ipynb
│── README.md
```

---

## ▶️ How to Run

1. Clone the repository
2. Install dependencies:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run the notebook

---

## 🔮 Future Improvements

* Use advanced models (Random Forest, XGBoost)
* Perform feature scaling
* Hyperparameter tuning
* Deploy using Flask or Streamlit

---

## 🙌 Acknowledgement

Dataset used for educational purposes.

---

## 📬 Connect with Me

Feel free to connect with me on LinkedIn for feedback and collaboration.

---

⭐ If you like this project, give it a star!
