# 🏥 ACME Annual Medical Expenditure Predictor

**👤 Creator:** [Divesh Sanjay Kshirsagar](https://github.com/Divesh-Kshirsagar)   
**📓 Notebook:** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1eHPM9Sc4HAv-7UygTRsvCS6C8AGqUzMb?usp=sharing)    
**💻 GitHub:** [ACME-Annual-Insurance-Premium-Predictor](https://github.com/Divesh-Kshirsagar/ACME-Annual-Insurance-Premium-Predictor/)    
**📜 License:** [MIT](https://opensource.org/licenses/MIT)

---

## 📌 Overview

This notebook builds a **📈 linear regression model** to estimate annual medical expenditures for new customers of **ACME Insurance Inc.** The model uses customer attributes such as **age, sex, BMI, number of children, smoking habits, and region** to predict medical charges. These predictions help determine the **annual insurance premium** offered to each customer.

---

## 🎯 Problem Statement

ACME Insurance Inc. needs an **automated, explainable system** to estimate medical charges for new customers. The system must use **verified historical data** and provide **transparent predictions** to comply with regulatory requirements.

---

## 🚀 Notebook Workflow

### 1️⃣ **Data Retrieval & Initial Inspection**
- 📤 Load medical charges data from a CSV file.
- 🔍 Perform initial data inspection using `df.head()`, `df.info()`, and `df.describe()`.

### 2️⃣ **Data Visualization & Distribution Analysis**
- 📊 Visualize distributions of **age, BMI, and charges**.
- 🔎 Explore relationships between features and medical charges using **scatter plots** and **histograms**.

### 3️⃣ **Categorical Data Analysis**
- 📌 Analyze the impact of categorical features: **'smoker', 'region', 'sex', and 'children'** on medical charges.

### 4️⃣ **Data Pre-processing**
- 🔢 Convert categorical features (**'smoker', 'sex'**) to numerical representations.
- 🏷️ One-hot encode the **'region'** feature.

### 5️⃣ **Correlation Analysis**
- 🔗 Generate a **correlation matrix** to identify relationships between numerical features and charges.

### 6️⃣ **Linear Regression Modeling**
- 🤖 Build and evaluate **simple and multiple linear regression models**.
- 🚭 Separate models for **smokers and non-smokers**.
- 📉 Analyze the **reduction in loss** as more features are added.

---

## 🛠️ Usage

### 📋 Prerequisites
- Python 3.x
- Required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

### 🚀 Run the Notebook
- Open the [Colab Notebook](https://colab.research.google.com/drive/1eHPM9Sc4HAv-7UygTRsvCS6C8AGqUzMb?usp=sharing) and run all cells.
- Or, clone the GitHub repository and run the notebook locally.

### 📂 Data
- The notebook uses a **CSV file** containing historical data for over **1300 customers**.

---

## 📜 License

This project is licensed under the **MIT License**.
