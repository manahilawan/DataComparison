# 🌾 FAOSTAT Data Analysis: Pakistan vs Turkey

## 📌 Project Overview
This project is a data analysis study using datasets from the **FAOSTAT (Food and Agriculture Organization of the United Nations)** website.  
It compares food and nutrition-related indicators between **Pakistan** and **Turkey** using Python and the Pandas library.

The main goal is to explore, clean, analyze, and compare both datasets to identify patterns, trends, and differences between the two countries.

---

## 📊 Datasets Used
- Pakistan FAOSTAT dataset (`pak`)
- Turkey FAOSTAT dataset (`turkiye`)

Both datasets include food and nutrition-related indicators across multiple years.

---

## 🛠️ Tools & Technologies
- Python 🐍
- Pandas 📊
- NumPy
- Jupyter Notebook
- Matplotlib (optional for visualization)

---

## ⚙️ Data Preprocessing & Operations

The following operations were applied to both datasets:

### 🔹 Basic Exploration
- `head()` and `tail()` → Preview data
- `shape` → Dataset size (rows & columns)
- `columns` → Column names
- `info()` → Data types & missing values

### 🔹 Data Cleaning
- `isnull().sum()` → Check missing values
- `dropna()` → Remove missing data
- `fillna()` → Handle missing values

### 🔹 Data Selection
- Column selection (`df['column']`)
- Multiple column selection (`df[['col1','col2']]`)
-  `iloc[]` indexing

### 🔹 Data Analysis
- `describe()` → Statistical summary
- `groupby()` → Year-wise comparison
- Filtering data based on conditions

### 🔹 Data Transformation
- Adding new columns
- Dropping unnecessary columns
- Sorting values

---

## 📈 Key Analysis Performed

- Comparison of Pakistan vs Turkey food-related indicators
- Year-wise trend analysis
- Identification of highest and lowest values
- Statistical summary comparison
- Data cleaning and preprocessing for better accuracy

---

## 📊 Comparison Objective
The main objective of this project is to:
- Compare food and nutrition trends between Pakistan and Turkey
- Analyze changes over time
- Identify differences in values and patterns
- Gain insights from FAOSTAT datasets using Pandas

---

## 📁 Project Structure
[Click here](C:\Users\manah\OneDrive\Desktop\DataComp\working.ipynb)
