

# 📊 E-Commerce Sales Trend Analysis

A complete end-to-end Data Analysis project performed on the Superstore dataset to identify sales trends, profitability patterns, and business insights using Python.

---

## 📌 Project Overview

This project analyzes 9,000+ retail sales records to uncover:

* Sales growth trends over time
* Category-wise and region-wise performance
* Profitability analysis
* Discount impact on profit
* Business recommendations

The goal is to simulate a real-world Data Analyst workflow from raw data to actionable insights.

---

## 🗂 Dataset

**Dataset Used:** Superstore Sales Dataset
Source: Kaggle
File: `Sample - Superstore.csv`

The dataset contains:

* Order Date
* Sales
* Profit
* Category
* Region
* Discount
* Quantity
* Product Name

---

## 🛠 Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook / VS Code

---

## 📁 Project Structure

```
sales-analysis-project/
│
├── data/
│   └── Sample - Superstore.csv
│
├── analysis.ipynb
│
├── outputs/
│   ├── monthly_sales.csv
│   ├── plots/
│
└── README.md
```

---

## 🔎 Analysis Performed

### 1️⃣ Data Cleaning

* Converted date columns to datetime
* Checked missing values
* Sorted data chronologically

### 2️⃣ Feature Engineering

* Extracted Year, Month, Month Name
* Created rolling average for trend smoothing

### 3️⃣ Exploratory Data Analysis (EDA)

* Monthly Sales Trend
* Profit Trend
* Category-wise Sales
* Region-wise Performance
* Top 10 Products
* Growth Rate Analysis
* Correlation Heatmap

---

## 📈 Key Insights

✔ Sales show an overall upward trend
✔ Technology category generates highest revenue
✔ West region performs best in sales
✔ High discounts reduce profit margins
✔ Some products have high sales but negative profit

---

## 💡 Business Recommendations

* Reduce excessive discounting on low-margin products
* Increase marketing for high-performing categories
* Optimize inventory before peak sales months
* Improve sales strategy in low-performing regions

---

## 📊 Sample Visualizations

### Monthly Sales Trend



### Category Performance



---

## 📊 Growth Rate Analysis

* Calculated Month-over-Month growth %
* Identified peak and low sales periods
* Detected seasonal fluctuations

---

## 📌 How to Run the Project

### Step 1: Clone Repository

```
git clone https://github.com/your-username/sales-analysis-project.git
```

### Step 2: Install Dependencies

```
pip install pandas numpy matplotlib seaborn
```

### Step 3: Run

```
python analysis.ipynb
```

---

## 📌 What This Project Demonstrates

This project proves my ability to:

* Perform real-world data cleaning
* Conduct time-series trend analysis
* Generate business insights
* Create meaningful visualizations
* Communicate findings professionally

---

## 🚀 Future Improvements

* Build Power BI Dashboard
* Deploy interactive Streamlit dashboard
* Add Sales Forecasting model
* Store results in SQL database
* Deploy using FastAPI backend

---


