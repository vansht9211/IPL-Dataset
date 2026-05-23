# 🏏 IPL Data Analysis using Python & Pandas

## 📌 Overview
This project is based on IPL player statistics analysis using Python and Pandas.  
The main goal of this project is to perform data analysis on IPL datasets and understand how real-world cricket data can be handled using DataFrames.

---

## 🚀 Technologies Used
- Python
- Pandas
- Jupyter Notebook

---

## 📂 Features
✔ Data Cleaning  
✔ DataFrame Operations  
✔ Filtering Data using Conditions  
✔ Sorting Data  
✔ Using `loc` and `iloc`  
✔ Player Performance Analysis  

---

## 📊 Sample Operations

### Select players where Runs > 500 and SR > 140

```python
df[(df["Runs"] > 500) & (df["SR"] > 140)]
