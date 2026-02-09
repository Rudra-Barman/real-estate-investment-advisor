---
# 🏠 Real Estate Investment Advisor
## Predicting Property Profitability & 5-Year Future Value using Machine Learning
---
## 📌 Project Overview

The **Real Estate Investment Advisor** is an end-to-end machine learning project designed to assist investors and buyers in making data-driven real estate decisions.
The system analyzes large-scale Indian housing data to:

- Predict the future property price after 5 years (Regression)

- Classify properties as Good or Not Good investments (Classification)

The project covers the complete data science lifecycle — from raw data preprocessing and exploratory analysis to model training, experiment tracking using MLflow, and deployment via a Streamlit application.

---
## 🎯 Objectives

- Analyze real estate data to uncover pricing and investment patterns

- Engineer meaningful features impacting property value

- Build high-accuracy regression and classification models

- Track experiments and models using **MLflow**

- Deploy predictions through an interactive **Streamlit app**

  ---

## 🗂️ Dataset Information

  The dataset consists of 250,000+ Indian property listings with details related to location, size, pricing, amenities, and infrastructure.

### Dataset Structure
```
data/
├── raw/
│   └── india_housing_prices.csv
│
└── processed/
    └── india_housing_prices_cleaned.csv
```
- **Raw Data**: Original unprocessed dataset

- **Processed Data**: Cleaned and feature-engineered dataset used for modeling

This separation ensures **data lineage, reproducibility, and clean experimentation**.

---

## 🧪 Exploratory Data Analysis (EDA)

**Key analyses performed**:

- Price and size distribution analysis

- Price per square foot comparison

- Location-based price trends

- Correlation analysis between features

- Outlier detection and treatment

More than **20 visualizations** were created to understand market behavior and data quality.

---

## 🧠 Feature Engineering

**Key engineered features include**:

- Amenities count and binary indicators

- Infrastructure composite score

- Size per BHK

- Investment score components

- 5-year future price growth logic

These features significantly improved model performance and interpretability.

---

## 🤖 Machine Learning Models
### 🔹 Regression (Future Price Prediction)

- Linear Regression

- Random Forest

- Gradient Boosting

- XGBoost / LightGBM

**Best Model Performance**:

- R² ≈ **0.99**

- Low RMSE and MAE

### 🔹 Classification (Good Investment Prediction)

- Logistic Regression

- Random Forest

- Gradient Boosting

- XGBoost

**Best Model Performance**:

- Accuracy ≈ 99%

- AUC ≈ 1.0

---

## 📊 MLflow Experiment Tracking

MLflow is integrated directly within the **Jupyter Notebook** to manage and track experiments.

MLflow is used to:
- Track multiple regression and classification experiments  
- Log model parameters and evaluation metrics  
- Compare model performance  
- Register best-performing models  

⚠️ **Note:**  
The `mlflow_runs/` directory is **auto-generated during notebook execution** and is **not committed**
to this repository to keep it lightweight.

### Run MLflow UI Locally
After running the notebook, start MLflow UI using:
```bash
mlflow ui
```
Then open:

```
http://127.0.0.1:5000
```
---

## 🖥️ Streamlit Application

An interactive **Streamlit application** is provided to:

- Enter property details

- Predict 5-year future price

- Classify investment quality

- Explore insights interactively

### Run Streamlit App
```
streamlit run streamlit_app.py
```
---

## 📁 Project Structure

```
real-estate-investment-advisor/
│
├── notebook/
│   └── Real_Estate_Investment_Advisor_End_to_End.ipynb
│
├── data/
│   ├── raw/
│   │   └── india_housing_prices.csv
│   └── processed/
│       └── india_housing_prices_cleaned.csv
│
├── streamlit_app.py
├── README.md
```
---

### ⚙️ Tech Stack

- Python

- Pandas, NumPy

- Scikit-learn

- XGBoost / LightGBM

- MLflow

- Matplotlib, Seaborn

- Streamlit

- Git & GitHub

---

### 🚀 How to Run the Project

1. **Clone the repository**:
```
git clone https://github.com/Rudra-Barman/real-estate-investment-advisor
```
---

2. **Install dependencies**:
```
pip install -r requirements.txt
```
---

3. **Run the notebook**:
```
jupyter notebook
```
---

4. **Launch Streamlit app**:
```
streamlit run streamlit_app.py
```
---

## 📈 Business Impact

- Enables data-driven real estate investment decisions

- Reduces risk of poor investments

- Identifies high-growth locations

- Saves time compared to manual analysis

---

## 👤 Author

## Rudra Barman
- 📧 Email: (rudrabarman7090@gmail.com)
- 🔗 LinkedIn: (https://www.linkedin.com/in/rudra-barman)
- 💻 GitHub: (https://github.com/Rudra-Barman/real-estate-investment-advisor)

---
