# Financial-Risk-Modelling-and-Analysis

# 💳 Credit Risk Prediction using Machine Learning

## 📌 Overview

This project focuses on predicting the creditworthiness of individuals using machine learning techniques. The goal is to classify whether a customer is a **good credit risk** or a **bad credit risk**, helping financial institutions make informed lending decisions and minimize potential losses.


## 🎯 Objectives

* Build a predictive model to assess credit risk
* Handle class imbalance in the dataset
* Improve model performance using feature selection and resampling techniques
* Evaluate models using key classification metrics


## 📊 Dataset

The project uses the **German Credit Dataset**, which contains customer information such as:

* Age
* Credit history
* Loan amount
* Employment status
* Housing
* Duration of credit

Target Variable:

* `Good Credit (1)`
* `Bad Credit (0)`

## ⚙️ Technologies Used

* Python 🐍
* Pandas & NumPy
* Scikit-learn
* Matplotlib & Seaborn
* Imbalanced-learn (SMOTE)


## 🔍 Project Workflow

### 1. Data Preprocessing

* Handled missing values
* Encoded categorical variables
* Normalized numerical features

### 2. Exploratory Data Analysis (EDA)

* Analyzed feature distributions
* Visualized correlations
* Identified class imbalance

### 3. Handling Class Imbalance

* Initial dataset:

  * 700 Good Credit
  * 300 Bad Credit
* Applied **SMOTE (Synthetic Minority Oversampling Technique)** to balance classes

### 4. Feature Selection

* Used feature importance techniques to select the most relevant features
* Reduced noise and improved model efficiency

### 5. Model Building

Implemented and compared:

* Logistic Regression
* Decision Tree
* Naive Bayes


## 📈 Model Evaluation

Evaluation metrics used:

* Accuracy
* Precision
* Recall
* Confusion Matrix

Example Confusion Matrix:

[[50 10]
 [64 76]]
```

### 🔎 Key Insight:

After applying SMOTE, the model improved in identifying minority class cases (bad credit), but **false negatives increased**, indicating a trade-off between recall and precision.



## 🚀 Results

* Improved class balance using SMOTE
* Better detection of risky customers
* Trade-offs observed between precision and recall
* Feature selection enhanced model performance



## 📂 Project Structure

```
credit-risk-prediction/
│
├── dataset/
│   └── german_credit_data.csv
│
├── Transformation Analsysis & Machine Learning Models/
│   └── credit_risk_analysis.py
│
├── src/
│   ├── preprocessing.py
│   ├── model.py
│   └── evaluation.py
│
├── Final Report/
│   ├── Final Project Report and Presentation
├── requirements.txt
└── README.md

## 🛠️ Installation

```bash
git clone https://github.com/shahdata/Financial-Risk-Modelling-and-Analysis.git
cd credit-risk-prediction
pip install -r requirements.txt


## ▶️ Usage

Run the notebook:

```bash
jupyter notebook notebooks/credit_risk_analysis.ipynb
```

Or run scripts:

```bash
python src/model.py


## 📌 Future Improvements

* Hyperparameter tuning
* Try advanced models (XGBoost, Random Forest)
* Deploy model using Flask or FastAPI
* Build a dashboard for visualization



## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.



## 👤 Author

Abdullah Shaban
If you want, I can also:

* Make it more **recruiter-focused (for portfolio impact)**
* Add **badges (accuracy, license, Python version)**
* Or tailor it specifically for **LinkedIn + GitHub visibility**

