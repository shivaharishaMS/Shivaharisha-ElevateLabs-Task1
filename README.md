# Shivaharisha-ElevateLabs-Task1
# Netflix Dataset - Data Cleaning and Preprocessing

This repository contains the cleaned version of the Netflix Movies and TV Shows dataset from Kaggle, processed entirely using **Microsoft Excel**. The goal was to identify and address common data quality issues such as missing values, duplicates, and inconsistent formatting.

---

## 📊 Dataset Source

**Kaggle Dataset:** [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows?resource=download)

---

## 📁 Files Included

- `netflix_cleaned.xlsx` – Cleaned Excel file after preprocessing
- `README.md` – Summary of steps and documentation

---

## 🧹 Cleaning Summary

### 1. Missing Value Treatment
- Filled missing values in `director` and `cast` with `"Unknown"`

### 2. Duplicate Removal
- Removed exact duplicate rows using Excel's **Remove Duplicates** feature

### 3. Text Standardization
- Cleaned and formatted values using `TRIM()` and `PROPER()` functions

### 4. Date Formatting
- Converted `date_added` column to consistent `dd-mm-yyyy` format

### 5. Data Type Validation
- Ensured `release_year` is numeric
- Confirmed `date_added` is a valid date field
- Left `show_id` as text since it is an alphanumeric identifier

---

## 🔗 Author

**Shivaharisha M S**  
📍 Karur, Tamil Nadu  
📧 shivaharisha.m@gmail.com  
🔗 [GitHub](https://github.com/shivaharishaMS)  
🔗 [LinkedIn](https://www.linkedin.com/in/shivaharisha-m-s-9818b9342/)

