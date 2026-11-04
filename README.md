# Data Cleaning and Preprocessing Using Python

## Project Overview

This project focuses on performing basic data cleaning and preprocessing techniques using a synthetic dataset. It demonstrates how to identify and handle missing values, apply statistical imputation methods, and convert categorical data into numerical format using Python.

The project uses **Pandas, NumPy, and Scikit-learn** to explore and preprocess the dataset.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## Dataset Information

The project uses a synthetic dataset containing 4,362 records and 5 columns:

| Column | Description |
|---|---|
| Category | Product category |
| Price | Product price |
| Rating | Product rating |
| Stock | Stock availability |
| Discount | Discount percentage |

The dataset contains missing values in multiple columns, making it suitable for practicing data cleaning techniques.

## Data Preprocessing Techniques

### 1. Data Exploration
- Displayed the first and last records using `head()` and `tail()`.
- Examined dataset structure using `info()`.
- Identified missing values using `isnull()`.

### 2. Handling Missing Values
- Used `dropna()` to remove rows containing missing values.
- Used `fillna()` to replace missing values.
- Explored different approaches to handling missing data.

### 3. Statistical Imputation
- Applied mean imputation to fill missing numerical values.
- Explored median and mode as alternative imputation techniques.

### 4. Categorical Encoding
- Used `LabelEncoder` from Scikit-learn to convert categorical stock values into numerical representations.

## Key Learnings

- Understanding dataset structure and data types.
- Identifying and handling missing values.
- Understanding mean, median, and mode imputation.
- Applying categorical encoding techniques.
- Working with Pandas and NumPy for data preprocessing.

## Project Purpose

This project was developed as a hands-on learning exercise to strengthen my understanding of data cleaning and preprocessing, which are essential steps in Data Analytics and Machine Learning workflows.

## Repository Contents

- `synthetic.ipynb` – Jupyter Notebook containing the data cleaning and preprocessing steps.
- `synthetic_dataset.csv` – Synthetic dataset used for practice.

---

**Author:** Mythili Kalidhasan
