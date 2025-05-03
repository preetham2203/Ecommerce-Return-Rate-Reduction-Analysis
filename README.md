# E-commerce Return Rate Reduction Analysis

## 📊 Project Overview

This project aims to analyze product return patterns in an e-commerce dataset and reduce return rates by identifying high-risk products. It includes data cleaning, dashboard creation using Power BI, and predictive modeling using Python.

---

## 📁 Project Deliverables

| File Name                           | Description                                        |
|------------------------------------|----------------------------------------------------|
| `cleaned_order_data.csv`           | Cleaned dataset used for modeling and dashboard    |
| `Project5_Ecommerce_Return_Analysis.pdf` | Power BI dashboard export (PDF format)         |
| `project5_model.ipynb`             | Jupyter notebook with return prediction model      |
| `high_risk_product.csv`            | Output file listing high-risk products to monitor  |
| `README.md`                        | Project summary and instructions                   |

---

## 📌 Objective

- Identify trends in product returns by product, year, and category
- Visualize key return metrics using Power BI
- Predict return likelihood using a classification model
- Flag high-risk products to help reduce future returns

---

## 🧹 Data Cleaning Summary

- Removed duplicates
- Converted data types
- Added binary `Returned` column
- Saved cleaned version as `cleaned_order_data.csv`

---

## 📊 Dashboard Insights (Power BI)

- **70.05K** total items sold  
- **11K** returned orders  
- **15.39%** average return rate  
- **Product P & H** had the highest number of returns  
- Returns increased significantly from **2018 to 2019**

> 📎 See `Project5_Ecommerce_Return_Analysis.pdf` for full dashboard.

---

## 🧠 Model Summary (Python)

- Model: Logistic Regression  
- Train/Test Split: 70/30  
- Accuracy: ~97%  
- Used classification report for precision/recall  
- Extracted high return risk items to `high_risk_product.csv`

---

## 📂 How to Use

1. View dashboard insights: Open the Power BI PDF
2. Run `project5_model.ipynb` to replicate model training
3. Check `high_risk_product.csv` for items needing attention

---

## 📬 Contact

**Preetham Reddy**  
Email: kovvuripreethamreddy@gmail.com  
GitHub: [Your GitHub Profile Link]

---

## ✅ Status

✔️ **Project Complete and Ready for Submission**
