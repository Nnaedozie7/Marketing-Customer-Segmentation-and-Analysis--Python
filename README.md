# Marketing Customer Segmentation & Analysis (Python)

This project performs an **exploratory data analysis (EDA)** and **customer segmentation analysis** on marketing data using **Python**.  
The objective is to understand **customer behavior, spending patterns, demographics, and campaign response** to support data-driven marketing decisions.

---

## 📌 Project Overview

The goal of this project is to:
- Analyze customer demographics and purchasing behavior
- Segment customers based on income, education, age, and family size
- Evaluate product spending across different customer groups
- Measure customer response to marketing campaigns
- Identify key factors influencing customer engagement and spending

This project demonstrates **real-world marketing analytics** using structured data analysis and visualization techniques.

---

## 📊 Dataset Description

The dataset contains **2,205 customer records** with **39 original features**, including:

### Demographic Features
- `Income`
- `Age`
- `Marital Status` (encoded)
- `Education Level` (encoded)
- `Kidhome`, `Teenhome`

### Purchasing Behavior
- `MntWines`
- `MntFruits`
- `MntMeatProducts`
- `MntFishProducts`
- `MntSweetProducts`
- `MntGoldProds`
- `MntTotal`
- `MntRegularProds`

### Engagement & Campaign Data
- `NumWebPurchases`
- `NumCatalogPurchases`
- `NumStorePurchases`
- `NumWebVisitsMonth`
- `AcceptedCmp1–5`
- `AcceptedCmpOverall`
- `Response`

---

## 🧹 Data Cleaning & Feature Engineering

- Removed **duplicate records** (184 duplicates removed)
- Verified **no missing values**
- Created new engineered features:
  - `highEd` / `lowEd` (education grouping)
  - `numKids` (total children)
  - `fSize` (family size)
  - `f_Seg` (family segmentation: mono, duo, triad, tetra, mega)
  - `IncomeBrac` (income brackets)
  - `Age_Group` (Child, Teenager, Adult, Elderly)
- Standardized column naming format

A cleaned dataset was exported as:


---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Seaborn** – Statistical visualization
- **Matplotlib** – Plot customization
- **Jupyter Notebook**

---

## 🔍 Analysis Performed

### 👥 Customer Segmentation
- Segmentation by:
  - Income brackets
  - Education level
  - Age groups
  - Family size
- Identification of dominant customer segments

### 🛒 Product Spending Analysis
- Spending behavior across:
  - Wines
  - Meat products
  - Fruits
  - Fish products
  - Sweet products
  - Gold products
- Product preference comparison by:
  - Income
  - Age group
  - Marital status
  - Education level

### 📣 Marketing Campaign Response
- Analysis of customer response to past campaigns
- Comparison of campaign acceptance by:
  - Education level
  - Income group
  - Family size
  - Age group

### 🌐 Digital Engagement
- Website visits vs purchases
- Relationship between income, age, and online engagement

---

## 📊 Visualizations

The project includes:
- Bar plots for spending patterns
- Count plots for customer segments
- Comparative charts for campaign response
- Income, age, and education-based visual analysis

All visualizations were generated using **Seaborn** and **Matplotlib**.

---


