# PRICE-DATA-ANALYSIS

# 💻 Laptop Price Prediction using Linear Regression

## 📌 Project Overview
Laptop prices vary greatly depending on hardware specifications such as **CPU frequency**, **RAM size**, and **weight**.  
The objective of this project is to build a **machine learning regression model** that can accurately predict the price of laptops based on these features.

This model can be useful for:
- Manufacturers planning pricing strategy
- Retailers evaluating competitive pricing
- Customers estimating realistic market value

---

## 🎯 Problem Statement
Develop a **predictive model** that estimates laptop prices (in Euros) based on hardware specifications using **Linear Regression**.

---

## 📂 Dataset Description
A custom CSV dataset containing laptop specifications and their prices was used.

| Feature | Description |
|--------|-------------|
| CPU_Frequency | Processor clock speed (GHz) |
| RAM | Memory size (GB) |
| Weight | Laptop weight (kg) |
| Price | Target variable (Euro) |

---

## 🔬 Exploratory Data Analysis (EDA)
To understand relationships between features and price, scatter plots were generated:
- CPU Frequency vs Price
- RAM vs Price
- Weight vs Price

EDA confirmed visible correlation between hardware specifications and price, validating feature selection.

---

## 🔧 Machine Learning Workflow
| Step | Action |
|-----|--------|
| Feature Selection | CPU_Frequency, RAM, Weight |
| Target Variable | Price |
| Train-Test Split | 80% training, 20% testing |
| Algorithm | Linear Regression |
| Performance Metrics | MSE and R² |

### Model Training Code Snippet
```python
model = LinearRegression()
model.fit(X_train, y_train)
y_pred = model.predict(X_test)


https://sites.google.com/d/1oU02joZ5IFI7H6JGdx2GeSvkbmQdFPJh/p/1ZeXyh7uKCudy2_lAvcth9MxzXx94BQX6/edit
