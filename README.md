# 🛒 Superstore Sales — Exploratory Data Analysis

A beginner-friendly EDA project on the Sample Superstore dataset using only **NumPy**, **Pandas**, and **Matplotlib**.

---

## 📁 Project Structure

```
superstore_eda/
├── Sample_-_Superstore.csv   # Raw dataset
├── eda.ipynb                 # Full analysis notebook
└── README.md
```

---

## 📊 Dataset Overview

| Property | Value |
|---|---|
| Rows | 9,994 |
| Columns | 21 |
| Period | January 2014 – December 2017 |
| Missing Values | None |

**Key columns:** Order Date, Ship Date, Segment, Region, Category, Sub-Category, Sales, Profit, Quantity, Discount

---

## 🔍 What's Covered in the Notebook

| # | Section |
|---|---|
| 1 | Imports & Load Data |
| 2 | Data Types & Missing Values |
| 3 | Basic Statistics (describe + NumPy) |
| 4 | Key Business Numbers |
| 5 | Sales & Profit by Category |
| 6 | Sub-Category Profit (loss detection) |
| 7 | Sales & Profit by Region |
| 8 | Segment Breakdown (pie chart) |
| 9 | Yearly Sales Trend |
| 10 | Monthly Seasonality |
| 11 | Sales & Profit Distributions |
| 12 | Boxplots |
| 13 | Outlier Detection (IQR method) |
| 14 | Correlation Heatmap |
| 15 | Discount vs Profit (scatter) |
| 16 | Avg Profit by Discount Bucket |
| 17 | Top 10 States by Sales |
| 18 | Key Findings |

---

## 💡 Key Findings

- 📦 **Technology** has the highest profit margin (~17%)
- 🪑 **Furniture** barely breaks even (~2.5% margin)
- ❌ **Tables, Bookcases, Supplies** are loss-making sub-categories
- 🏷️ Discounts above **20%** flip average profit negative
- 🌍 **West region** leads on both sales and profit
- 📈 Sales grew **51%** from 2014 to 2017
- 🎄 **November–December** is the strongest sales period each year

---

## ⚙️ Setup & Run

**1. Clone the repo**
```bash
git clone https://github.com/Shivi3022/Superstore-EDA.git
cd Superstore-EDA
```

**2. Install dependencies**
```bash
pip install numpy pandas matplotlib jupyter
```

**3. Open the notebook**
```bash
jupyter notebook eda.ipynb
```

---

## 🛠️ Libraries Used

| Library | Purpose |
|---|---|
| `pandas` | Data loading, cleaning, groupby analysis |
| `numpy` | Manual statistical calculations |
| `matplotlib` | All charts and visualizations |

---

## 📌 Dataset Source

[Sample Superstore — Tableau / Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
