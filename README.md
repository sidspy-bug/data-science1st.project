# 🛒 E-Commerce Customer Data Preprocessing & EDA

## 📌 Overview
This project demonstrates an **end-to-end data preprocessing and exploratory data analysis (EDA) pipeline** on a real-world e-commerce customer dataset.  
The raw data contained missing values, duplicates, inconsistent formats, mixed currencies, and outliers. Using Python, the dataset was cleaned, standardized, and analyzed to extract meaningful business insights.

---

## 🎯 Objectives
- Clean and preprocess messy e-commerce data  
- Handle missing values, duplicates, and incorrect data types  
- Standardize numerical, categorical, and date fields  
- Detect and treat outliers  
- Perform exploratory data analysis (EDA)  
- Prepare an analysis-ready dataset for machine learning tasks  

---

## 🧩 Dataset
- **Type:** E-Commerce Customer Dataset (CSV)
- **Features include:**
  - Customer demographics (age, gender, income)
  - Purchase details (quantity, purchase amount)
  - Product categories
  - Country & payment methods
- **Initial Issues:**
  - Missing values
  - Duplicate records
  - Mixed date & currency formats
  - Inconsistent categorical labels
  - Extreme outliers

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Environment:** Google Colab  
- **Libraries:**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - python-docx
  - python-pptx
  - ReportLab (optional)
 

---

## ✅ Results
- Cleaned and structured dataset
- Insightful visualizations
- Automated DOCX & PPT reports
- Dataset ready for ML applications like:
  - Customer segmentation
  - Revenue forecasting
  - Recommendation systems

---

## 🚀 Future Scope
- Customer segmentation using clustering  
- Predictive modeling for revenue  
- Recommendation systems  

---

## 👤 Author
**Siddhant Saurav**  
B.Tech – Computer Science & Engineering  
IILM University, Greater Noida  

---

⭐ If you found this project useful, consider giving it a star!


---

## ⚙️ Workflow
1. **Data Ingestion**
   - Load raw CSV into Pandas DataFrame  

2. **Data Cleaning & Preprocessing**
   - Missing value imputation (median/mode)
   - Duplicate removal
   - Currency and data type standardization
   - Date parsing
   - Outlier detection & capping  

3. **Feature Engineering**
   - Created `order_revenue = purchase_amount × quantity`

4. **Exploratory Data Analysis (EDA)**
   - Distribution plots
   - Bar charts
   - Boxplots
   - Correlation heatmaps  

---

## 📊 Key Insights
- Identified high-value customers  
- Found top revenue-generating product categories  
- Analyzed country-wise purchasing trends  
- Observed relationships between income, age, and spending  

## PROJECT STRUCTURE

📦 E-Commerce-EDA-Project
 ┣ 📜 eda_ready_data.csv
 ┣ 📊 Visualizations (PNG files)
 ┣ 📄 Completed_Project_Report.docx
 ┣ 📑 EDA_Report.pdf
 ┣ 📽 Data_Preprocessing_EDA_Project.pptx
 ┣ 📓 Jupyter Notebook / Colab File
 ┗ 📘 README.md

