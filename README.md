# 🎬 Netflix Movies and TV Shows - Data Cleaning & Preprocessing

## 📌 Project Overview

This project demonstrates the process of cleaning and preprocessing the **Netflix Movies and TV Shows** dataset using **Python** and **Pandas**. The objective was to identify and resolve common data quality issues such as missing values, inconsistent formatting, and duplicate records to prepare the dataset for further analysis and visualization.

---

## 🎯 Objective

The objectives of this project are to:

* Clean raw data efficiently.
* Identify and handle missing values.
* Check and remove duplicate records.
* Standardize text values.
* Convert date formats into a consistent format.
* Verify data types.
* Create a clean dataset ready for analysis and machine learning.

---

## 🛠️ Tools & Technologies Used

* Python
* Pandas
* Jupyter Notebook

---

## 📂 Dataset

**Dataset Name:** Netflix Movies and TV Shows

The dataset contains information about Netflix content, including:

* Show ID
* Type (Movie / TV Show)
* Title
* Director
* Cast
* Country
* Date Added
* Release Year
* Rating
* Duration
* Genre
* Description

---

## 🔄 Data Cleaning Steps Performed

### 1. Data Exploration

* Loaded the dataset using Pandas.
* Checked dataset shape, column names, and data types.
* Identified missing values.

### 2. Missing Value Treatment

* Replaced missing values in **Director**, **Cast**, and **Country** with `"Unknown"`.
* Filled missing values in **Rating** using the most frequent value (Mode).
* Removed rows with missing values in **Date Added** and **Duration**.

### 3. Duplicate Record Check

* Checked for duplicate records.
* No duplicate records were found.

### 4. Text Standardization

* Removed leading and trailing spaces from all text columns.

### 5. Date Formatting

* Converted the **Date Added** column into the **DD-MM-YYYY** format.

### 6. Column & Data Type Verification

* Verified column names were clean and consistent.
* Checked that all data types were appropriate.

### 7. Export

* Saved the cleaned dataset as **`netflix_titles_cleaned.csv`**.

---

## 📈 Project Outcome

After completing the preprocessing steps:

* Missing values were handled successfully.
* Duplicate records were verified.
* Text values were standardized.
* Date formatting was made consistent.
* The dataset is clean, structured, and ready for data analysis, visualization, and machine learning tasks.

---

## 🚀 Future Scope

This cleaned dataset can be used for:

* Exploratory Data Analysis (EDA)
* Data Visualization
* Dashboard Development (Power BI / Tableau)
* Machine Learning Projects
* Statistical Analysis
