# DATA-PIPELINE-DEVELOPMENT

*COMPANY* :  CODETECH IT SOLUTIONS

*NAME* :  S.NIRANJANA

*INTERN ID* :  CT04DH2216

*DOMAIN* :  DATA SCIENCE

*DURATION* :  4WEEKS

*MENTOR* :  NEELA SANTOSH KUMAR


## 🔍 Overview

This repository contains a complete **ETL (Extract, Transform, Load) data pipeline** built using **Python**, **pandas**, and **scikit-learn**. The task was assigned as part of a data science internship at **CodTech**, and it focuses on automating data preprocessing workflows—an essential step in any data analytics or machine learning project.

The ETL pipeline processes the **Iris flower dataset**, a classic multivariate dataset used frequently for classification tasks. The final cleaned and transformed data is saved as a CSV file and is ready for downstream machine learning or statistical analysis.

---

## 🎯 Objective

The goal of this project is to:

- Understand and implement the core steps of a data pipeline.
- Extract data from a source (in this case, from scikit-learn’s built-in dataset).
- Apply preprocessing techniques such as scaling and encoding.
- Automate the transformation process using reusable code.
- Save the cleaned dataset in a structured format (CSV) for further use.

This project helps build foundational skills for real-world data engineering and data science workflows.

---

## 🛠️ Tools & Libraries

- **Python** – Programming language
- **pandas** – Data manipulation and analysis
- **scikit-learn** – Machine learning library used for preprocessing
- **StandardScaler** – For feature normalization
- **LabelEncoder** – For target label encoding
- **Jupyter Notebook** – Used for interactive development and explanation

---

## 📂 Folder Structure


---

## 🔄 ETL Pipeline Steps

### 1. **Extract**
The dataset used in this project is the well-known **Iris dataset**, which is loaded using `sklearn.datasets.load_iris()`. It contains 150 samples from three different species of Iris (Setosa, Versicolor, Virginica), with four numerical features:

- sepal length  
- sepal width  
- petal length  
- petal width

### 2. **Transform**
Transformation involves cleaning and preparing the data:

- **StandardScaler** is used to normalize all numerical features so they have zero mean and unit variance. This step is important for many ML algorithms.
- **LabelEncoder** is used to convert species names (`Setosa`, `Versicolor`, `Virginica`) into numeric labels (0, 1, 2), which are easier for machine learning models to process.

### 3. **Load**
The final transformed dataset is stored in a CSV file named `iris_cleaned.csv` inside the `data/processed/` directory. This step simulates the "loading" part of a real-world ETL pipeline, where the final product is saved for modeling or storage in a database.

---

## 📈 Use Cases

This pipeline is ideal for:

- Data preprocessing demonstration in machine learning.
- Training classification models on the cleaned Iris dataset.
- Learning how to modularize and automate common data transformation steps.

---
