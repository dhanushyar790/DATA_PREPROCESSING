# 📊 Data Preprocessing

## 📌 Overview
The dataset was preprocessed before training the Machine Learning model to improve accuracy and performance.  
Preprocessing ensures the data is clean, consistent, and suitable for analysis.

---

## 🛠️ Steps Involved

1. **Data Import**
   - Imported the dataset from **Snowflake** into Python.

2. **Exploratory Checks**
   - Examined dataset structure using Pandas functions:
     - `head()`
     - `info()`
     - `describe()`

3. **Missing Values**
   - Identified missing values using:
     ```python
     df.isnull().sum()
     ```
   - Handled missing values by replacing them with suitable statistical values (mean, median, or mode).

4. **Data Cleaning**
   - Removed unnecessary or duplicate records if present.
   - Ensured correct data types for numerical and categorical features.

---

## ✅ Outcome
- Clean and structured dataset ready for **feature engineering** and **model training**.
- Improved model accuracy and performance by eliminating inconsistencies.
