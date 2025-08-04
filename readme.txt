# 🧹 Customer Personality Data Cleaning

This project is part of **Internship Task 1**: Data Cleaning and Preprocessing using Python.

---

## 📌 Objective

To clean and preprocess the `customer_personality_150_raw.csv` dataset by:
- Handling missing values
- Standardizing formats
- Removing duplicates
- Making the data ready for analysis

---

## 📁 Dataset Overview

- **Filename:** `customer_personality_150_raw.csv`
- **Records:** 150 (before cleaning)
- **Columns:** 
  - ID
  - Name
  - Gender
  - Age
  - Country
  - Join Date
  - Spending Score

---

## 🧰 Tools Used

- Python 🐍
- Pandas 📊
- Jupyter Notebook 📒
- Visual Studio Code 💻

---

## 🔧 Cleaning Steps Performed

- Dropped rows with missing **Age**
- Filled missing values in **Gender** and **Country** with `'Unknown'`
- Standardized text case (`Gender`, `Country`)
- Converted **Join Date** to valid `datetime` format
- Removed exact duplicate records
- Renamed all columns to lowercase with underscores for consistency
- Saved the cleaned data as a new CSV

---

## 📄 Files Included

| File | Description |
|------|-------------|
| `customer_personality_150_raw.csv` | Original dataset |
| `customer_cleaning.ipynb` | Notebook with data cleaning code |
| `customer_personality_150_cleaned.csv` | Cleaned dataset |
| `README.md` | This documentation file |

---

## 👩‍💻 Author

**Priyanka Verma**  
Internship Project Submission  
August 2025