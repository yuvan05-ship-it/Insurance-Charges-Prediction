# 🧠 Insurance Charges Prediction using Machine Learning

## 📌 Overview

This project focuses on predicting medical insurance charges based on individual attributes such as age, BMI, smoking habits, and more.
The goal is to analyze key factors influencing insurance costs and build a machine learning model to estimate charges accurately.

---

## 🎯 Problem Statement

Insurance companies need reliable methods to estimate medical costs based on customer data.
This project aims to develop a predictive model that helps understand how different features impact insurance charges.

---

## 📊 Dataset Features

The dataset contains the following attributes:

* **Age** – Age of the individual
* **Sex** – Gender (Male/Female)
* **BMI** – Body Mass Index
* **Children** – Number of dependents
* **Smoker** – Smoking status (Yes/No)
* **Region** – Residential area
* **Charges** – Medical insurance cost (Target Variable)

---

## 🔍 Exploratory Data Analysis (EDA)

Performed detailed analysis to understand patterns and relationships:

* Distribution of age and BMI
* Impact of smoking on insurance charges
* Relationship between age and medical expenses
* Visualization using Matplotlib and Seaborn

---

## ⚙️ Data Preprocessing

* Converted categorical variables into numerical format using **Label Encoding**
* Checked for missing values (none found)
* Prepared features and target variables

---

## 🤖 Machine Learning Model

* **Algorithm Used:** Linear Regression
* Split dataset into training and testing sets
* Trained the model on training data
* Predicted insurance charges on test data

---

## 📈 Model Evaluation

Performance metrics used:

* **R² Score** – Measures model accuracy
* **Mean Absolute Error (MAE)**
* **Root Mean Squared Error (RMSE)**

---

## 📉 Visualization

* Scatter plots for feature relationships
* Boxplots for categorical comparisons
* Prediction line graph (Age vs Charges)

---

## 🚀 Key Insights

* Smoking significantly increases insurance charges
* Age has a strong positive correlation with medical expenses
* BMI moderately affects insurance cost
* Linear Regression provides a good baseline model

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Libraries:**

  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn
  * Scikit-learn

---

## 📁 Project Structure

```
├── insurance.csv
├── Insurance Charges Prediction Project.ipynb
└── README.md
```

---

## 🔮 Future Improvements

* Implement advanced models (Random Forest, Gradient Boosting)
* Perform feature scaling and hyperparameter tuning
* Deploy the model using Flask or Streamlit

---

## 📌 How to Run the Project

1. Clone the repository
2. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Run the Jupyter Notebook

---

## 🙌 Acknowledgements

Dataset used for learning and educational purposes.

---

## 📬 Contact

If you have any suggestions or feedback, feel free to connect with me on LinkedIn!

---

⭐ If you found this project useful, consider giving it a star!
