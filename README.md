# 🪔 Diwali Sales Analysis - Exploratory Data Analysis (EDA) Project

This Python project presents an **Exploratory Data Analysis (EDA)** of **Diwali sales data** using pandas, matplotlib, seaborn, and NumPy. The aim is to extract valuable business insights that can help retailers improve marketing strategies and target potential customers more effectively.

---

## 📌 Project Objective

Analyze the Diwali sales dataset to understand:
- Customer purchasing behavior across gender, age group, marital status, state, occupation
- Top-selling products and product categories
- Regions with the highest number of orders and sales
- Insights that can help businesses optimize their campaigns and inventory

---

## 🧰 Tools and Libraries Used

- **Python 3**
- **Jupyter Notebook**
- **Pandas** – Data manipulation
- **NumPy** – Numerical computing
- **Matplotlib & Seaborn** – Data visualization

---

## 📁 Dataset

- File Name: `Diwali Sales Data.csv`  
- Rows: `11251`  
- Columns: `15 (reduced to 13 after cleaning)`

**Note:** Dataset was encoded in `cp1252` to handle special characters.

---

## 🧹 Data Cleaning Steps

- Removed null values from the `Amount` column
- Dropped unnecessary columns like `Status`, `unnamed1`
- Converted `Amount` to integer data type

---

## 🔍 Key Insights

### 1. **Gender-Based Analysis**
- Female customers outnumber males in both quantity and purchase amount.

### 2. **Age Group Analysis**
- Most purchases were made by **26-35-year-old females**.

### 3. **State-Wise Sales**
- Top 3 states by sales:
  - **Uttar Pradesh**
  - **Maharashtra**
  - **Karnataka**

### 4. **Marital Status**
- **Married women** contribute the highest to overall sales.

### 5. **Occupational Trends**
- Highest purchases made by people in:
  - **IT sector**
  - **Healthcare**
  - **Aviation**

### 6. **Product Category**
- Top-selling categories:
  - **Food**
  - **Clothing**
  - **Electronics**

### 7. **Top Products**
- Most sold product IDs are visualized using bar plots.

---

## 📈 Visualizations

- Count plots, bar plots, and grouped aggregations
- Used `groupby()` and `describe()` for summary statistics
- Presented with `seaborn` for clarity and style

---

## 🧾 Conclusion

📝 Married women aged 26–35 from **Uttar Pradesh, Maharashtra, and Karnataka**, working in **IT, Healthcare, or Aviation**, are more likely to purchase products in the **Food, Clothing, and Electronics** categories during Diwali.

---

## 🖼️ Project Files

- `Diwali Sales Data.csv`: Dataset.
- `Diwali_Sales_Analysis.pdf`: Project report.
- `README.md`: Project documentation.
