# 📊 Sales Trend Visualisation

A beginner-level Data Analytics project that analyses Indian retail sales data to uncover trends across product categories, payment methods, and states — built entirely using **Google Sheets** (no coding required).

---

## 📁 Dataset

Two CSV files are used in this project:

| File | Rows | Description |
|------|------|-------------|
| `Orders.csv` | 500 | Customer orders with Order ID, Date, Customer Name, State, City |
| `Details.csv` | 1500 | Transaction details with Amount, Profit, Quantity, Category, Sub-Category, PaymentMode |

> Both files are linked using the **Order ID** column.

---

## 🎯 Objectives

- Analyse total sales across product categories (Electronics, Furniture, Clothing)
- Identify the most popular payment methods (COD, EMI, Credit Card, UPI, Debit Card)
- Find which Indian states have the highest sales
- Visualise all findings using charts

---

## 🛠️ Tool Used

**Google Sheets** — free, browser-based, no installation needed.

Features used:
- CSV Import
- SUMIF Formula (to link both files)
- Pivot Tables (to group and summarise data)
- Bar Charts & Pie Charts

---

## 📊 Charts Created

| Chart | Type | Insight |
|-------|------|---------|
| Sales by Category | Bar Chart | Which category earns the most revenue |
| Sales by Payment Mode | Pie Chart | Which payment method is used most |
| Top States by Sales | Bar Chart | Which Indian states have highest sales |

---

## 📂 Repository Structure

```
sales-trend-visualisation/
│
├── dataset/
│   ├── Orders.csv
│   └── Details.csv
│
├── analysis/
│   └── sales_analysis.xlsx
│
├── charts/
│   ├── chart1_category.png
│   ├── chart2_payment.png
│   └── chart3_states.png
│
├── screenshots/
│   └── output_screenshot.png
│
├── docs/
│   └── documentation.pdf
│
└── README.md
```

---

## 🔍 Key Findings

- **3 product categories** analysed: Electronics, Furniture, and Clothing
- **5 payment modes** used by customers across 500 orders
- Sales data spans **multiple Indian states** including Uttar Pradesh, Delhi, Maharashtra, and Madhya Pradesh
- A total of **1500 product line items** were analysed from 500 unique orders

---

## 🚀 How to View This Project

1. Download `Sales_analysis.xlsx` from the `Analysis/` folder
2. Open it in Google Sheets or Microsoft Excel
3. Each sheet tab contains a Pivot Table or chart
4. View the charts in the `charts/` folder for visual summaries
5. Read `docs/documentation.pdf` for the full project report

---

## 👤 About

This is my **first Data Analytics project**, completed as part of a data analytics course.  
No programming was used — the entire analysis was done using Google Sheets.

---

## 📌 Project Status

✅ Completed# sales-trend-viusalisation
