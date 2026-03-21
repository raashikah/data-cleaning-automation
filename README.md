# 🧹 Data Cleaning Automation & Sales EDA

A Python project that automates the cleaning and preparation 
of raw sales data using Pandas, transforming messy datasets 
into analysis-ready insights.

---

## 📌 Problem Statement
Raw sales data is often messy — duplicate records, missing 
values, inconsistent formatting. Manual cleaning is slow and 
error-prone. This project automates the entire process.

---

## ⚙️ Key Steps Performed
- ✅ Loaded raw sales data from CSV using Pandas
- ✅ Performed data quality checks for structure and nulls
- ✅ Removed duplicate records to avoid data inflation
- ✅ Handled missing values to improve data accuracy
- ✅ Standardised column names for consistency
- ✅ Exported cleaned dataset for downstream analytics

---

## 📊 EDA Insights
- Identified top revenue-generating products by category
- Analysed regional sales performance and trends
- Visualised year-wise sales patterns using Matplotlib

---

## 🛠️ Technologies Used
| Tool | Purpose |
|------|---------|
| Python | Core programming |
| Pandas | Data cleaning & manipulation |
| Matplotlib | Data visualisation |
| Jupyter Notebook | Analysis environment |

---

## 🚀 How to Run
```bash
git clone https://github.com/raashikah/data-cleaning-automation
pip install -r requirements.txt
jupyter notebook data_cleaning.ipynb
```

---

## 📁 Project Structure
```
data-cleaning-automation/
├── data/              # Raw and cleaned datasets
├── notebooks/         # Jupyter analysis notebooks
├── src/               # Python scripts
└── requirements.txt   # Dependencies
```
## Project 2: Sales Data Analysis (EDA)

### Overview
Performed exploratory data analysis on cleaned sales data to identify trends, top-performing products, and regional performance.

### Key Analysis Performed
- Overall sales, profit, and quantity analysis
- Sales and profit by category
- Top 10 products by revenue
- Regional sales distribution
- Year-wise sales trend analysis
- Data visualization using Matplotlib

### Key Insights
- A small set of products contributes significantly to total revenue.
- Certain categories and regions drive higher sales but vary in profitability.
- Sales show a clear trend over multiple years, supporting growth analysis.

### Tools Used
- Python
- Pandas
- Matplotlib
- Google Colab
