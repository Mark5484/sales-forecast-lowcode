# sales-forecast-lowcode
Low-code project to forecast sales revenue for SuperKart using historical sales data and EDA-driven insights.
# 🛒 SuperKart Sales Forecasting (Low-Code Project)

This repository contains a **low-code sales forecasting solution** for **SuperKart**, a retail chain operating in multiple city tiers. The objective is to analyze historical sales data and generate actionable insights to optimize inventory and inform regional sales strategies.

---

## 📌 Project Overview

- **Problem**: SuperKart needs to forecast product-level sales per store for the upcoming quarter using historical sales data.
- **Approach**: Use a low-code methodology that focuses on business insight generation, exploratory data analysis (EDA), and visualization — not raw algorithm development.
- **Tools**: Google Colab, pandas, seaborn/matplotlib, Streamlit, Flask, Hugging Face Spaces

---

## 📊 Dataset Features

- `Product_Id`: Unique identifier for each product
- `Product_Weight`, `Product_Sugar_Content`, `Product_MRP`
- `Product_Allocated_Area`: Relative shelf/display space
- `Store_Id`, `Store_Size`, `Store_Location_City_Type`, `Store_Type`
- `Product_Store_Sales_Total`: Target variable — total sales per product per store

More details are provided in the project notebook.

---

## 🧠 Key Steps

1. **Exploratory Data Analysis (EDA)**  
   - Shape, datatypes, null values, summary stats
   - Univariate & bivariate plots  
   - Business insight generation

2. **Preprocessing & Insights**  
   - Handle missing/outlier values  
   - Encode categorical variables  
   - Feature engineering (if necessary)

3. **Model Experimentation (optional)**  
   - DecisionTree, RandomForest, or XGBoost  
   - Model performance comparison & improvement

4. **Deployment**  
   - Backend: Flask API hosted on Hugging Face Spaces  
   - Frontend: Streamlit app on Hugging Face Spaces  

5. **Business Presentation**  
   - Key insights  
   - Regional recommendations  
   - Forecast summary

---

## 🚀 Deployment Links

| Component | Hugging Face Space |
|----------|-------------------|
| 🔙 Flask API (Backend) | [Backend Space Link](#) |
| 🖥️ Streamlit App (Frontend) | [Frontend Space Link](#) |

*Replace the placeholders with your actual Hugging Face links after deployment.*

---

## 📁 Repository Structure

sales-forecast-lowcode/
├── notebook.ipynb # Main Google Colab notebook
├── presentation.pdf # Final business presentation
├── README.md # This file
├── LICENSE # MIT License
└── .gitignore # Files to ignore

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🤝 Credits

Developed as part of the **Great Learning Capstone Project**.  
For learning and academic evaluation purposes only.

---

