# 🪔 Diwali Sales Analysis & Prediction

## 📌 Project Overview
This project analyzes Diwali sales data to uncover customer purchasing patterns and build a predictive sales model.  
The goal is to help businesses target the right customers, understand regional demand, and identify top-selling categories.

## 📊 Dataset
- **Source:** Diwali Sales Data (CSV)
- **Rows:** ~11,000+ transactions
- **Columns:** Customer demographics, purchase details, product categories, sales amount, and orders.

## ⚙️ Tools & Libraries
- **Python**
- **Pandas**, **NumPy** – Data cleaning & preprocessing
- **Matplotlib**, **Seaborn** – Data visualization
- **Scikit-Learn** – Machine learning
- **Jupyter Notebook** – Analysis environment

## 📂 Project Workflow
1. **Data Cleaning**
   - Removed unnecessary columns (`Status`, `unnamed1`)
   - Dropped missing values
   - Converted `Amount` to integer type

2. **Exploratory Data Analysis (EDA)**
   - Gender-wise sales
   - Age group sales
   - State-wise sales
   - Occupation-based purchases
   - Product category performance

3. **Feature Engineering**
   - Added `Total_Orders_Amount` column
   - One-hot encoded categorical variables

4. **Modeling**
   - Train-test split (80:20)
   - Linear Regression model to predict `Amount`
   - Evaluation: RMSE, R² score

## 📈 Key Insights
- **Women** purchase more during Diwali compared to men
- Age group **26–35 years** spends the most
- **Clothing & Apparel** dominate sales
- Top states: **Maharashtra, Karnataka, Uttar Pradesh**
- Higher sales from **married customers** with family

## 📸 Visualizations
![Sales by Gender](images/gender_sales.png)
![Sales by Age Group](images/age_sales.png)
![Top States by Sales](images/state_sales.png)
![Sales by Occupation](images/occupation_sales.png)
![Sales by Product Category](images/product_sales.png)
