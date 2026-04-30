# 📊 Customer Purchase Behavior Analysis

## 📌 Project Overview

This project builds a complete **data preprocessing and feature engineering pipeline** using multi-source data:

* Excel (`users.xlsx`)
* JSON (`sales.json`)
* SQL (`inventory.sql`)

The goal is to clean, transform, and analyze customer purchase data to generate meaningful insights and prepare the dataset for machine learning.

---

## 🗂️ Project Structure

```
project/
│
├── main.ipynb
├── users.xlsx
├── sales.json
├── inventory.sql
├── final_cleaned_dataset.csv
└── README.md
```

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Scikit-learn
* JSON

---

## 🔄 Workflow

### 1. Data Loading

* Loaded data from Excel, JSON, and SQL sources

### 2. Data Cleaning

* Handled missing values
* Removed invalid entries
* Converted date formats

### 3. Outlier Detection

* Used **IQR method** to remove extreme values

### 4. Data Transformation

* Extracted date features (day, month, year)
* Applied encoding (Label Encoding)
* Binning (Low, Medium, High spending)
* Log transformation

### 5. Feature Scaling

* StandardScaler
* MinMaxScaler

### 6. Feature Engineering

* Average spend per user
* Purchase frequency
* Days since last purchase (recency)
* Category-wise spending

### 7. Data Merging

* Combined all features into a final dataset

---

## 📈 Key Insights

* Majority of users fall under **low to medium spending**
* Few users contribute significantly to revenue
* Digital payments (UPI, Wallet, Cards) dominate
* Recency and frequency are strong indicators of customer behavior
* Customer segmentation is possible based on spending patterns

---

## 📊 Output

Final dataset generated:

```
final_cleaned_dataset.csv
```

Contains:

* Cleaned data
* Engineered features
* Ready for ML models

---

## 🚀 How to Run

1. Install dependencies:

```
pip install pandas numpy scikit-learn
```

2. Run Jupyter Notebook:

```
jupyter notebook main.ipynb
```

3. Execute all cells

---

## 🎯 Project Outcome

* Built a complete data pipeline
* Extracted meaningful business insights
* Prepared dataset for machine learning

---

## 👨‍💻 Author

Alex Macwan

---
