# Titanic Data Analysis Project 🚢

## 📌 Project Overview

This project focuses on data analysis using the Titanic dataset. The goal is to understand survival patterns by analyzing different features such as gender, passenger class, and age.

The project is divided into two main parts:

* Creating a custom dataset
* Analyzing the Titanic dataset using pandas

---

## 🛠️ Tools & Technologies

* Python
* pandas
* Kaggle Notebook

---

## 🔷 Part 1: Custom Dataset

A dataset was created manually using a Python dictionary.

### Features:

* PassengerId
* Survived
* Pclass
* Sex
* Age

### Details:

* 5 columns
* 15 rows
* Custom index applied

This step helps in understanding how structured data works before analyzing real-world datasets.

---

## 🔷 Part 2: Titanic Dataset Analysis

### 📂 Dataset

The dataset was loaded from Kaggle using the following path:

```
/kaggle/input/datasets/nesihamohammed/titanic-dataset/dataset-2.csv
```

---

## 🔶 Step 1: Data Exploration

* Used `.head()` to preview the dataset
* Used `.info()` to understand data types and missing values
* Used `.describe()` for statistical summary

---

## 🔶 Step 2: Data Cleaning

* Standardized column names
* Filled missing values:

  * Age → median
  * Embarked → mode (if available)
* Dropped Cabin column (if present)
* Removed duplicate rows

---

## 🔶 Step 3: Data Analysis

Performed analysis using `groupby()`:

* Survival rate by gender
* Survival rate by passenger class
* Average age per class
* Survival rate by age group

Created a new feature:

* AgeGroup (Child, Teen, Adult, Senior)

---

## 🔶 Step 4: Data Filtering

Extracted specific groups:

* Female passengers who survived
* Children who survived
* First-class passengers who survived

---

## 🔶 Step 5: Insights

Key findings from the analysis:

* Females were more likely to survive than males
* Passenger class had a strong impact on survival
* Children had higher survival rates, indicating prioritization
* The highest survival rate was observed among female passengers in first class

---

## ✅ Conclusion

This project demonstrates how to:

* Clean real-world data
* Perform exploratory data analysis
* Extract meaningful insights using pandas

It highlights how factors like gender, age, and class influenced survival in the Titanic disaster.

---

## 📎 How to Run the Project

1. Open the notebook in Kaggle or Jupyter
2. Install pandas if needed
3. Run all cells

---

## 👤 Author

[Your Name]
# titanic-
