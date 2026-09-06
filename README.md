# Superstore Sales & Profit Analysis

## 📌 Project Overview

This project analyzes the Superstore dataset using Python to understand sales performance, profitability, loss-making products and sub-categories, regional performance, customer segments, discount impact, and shipping performance.

The main objective is to answer:

> **Where are sales and profits coming from, where is the business losing money, and what can be improved?**

---

## 🎯 Business Objectives

* Analyze overall sales and profit
* Identify top-performing categories and products
* Identify loss-making sub-categories and products
* Analyze regional performance
* Analyze customer segment performance
* Analyze monthly and yearly sales trends
* Understand the relationship between discount and profit
* Analyze shipping performance
* Provide actionable business recommendations

---

## 📊 Dataset

The dataset contains **9,994 records and 21 columns**.

Important columns include:

* Order Date
* Ship Date
* Ship Mode
* Customer Name
* Segment
* State
* Region
* Category
* Sub-Category
* Product Name
* Sales
* Quantity
* Discount
* Profit

---

## 🛠️ Tools & Technologies

* Python
* NumPy
* Pandas
* Matplotlib
* Jupyter Notebook

---

## 🔧 Data Cleaning

The following steps were performed:

* Checked dataset structure
* Checked missing values
* Checked duplicate records
* Converted Order Date and Ship Date to datetime format
* Created additional Month and Year columns
* Created Shipping Days column
* Created Profit/Loss status using NumPy

---

## 📈 Analysis Performed

### Sales Analysis

* Total sales
* Category-wise sales
* Sub-category sales
* Product sales
* Regional sales
* Customer segment sales
* Monthly sales
* Yearly sales

### Profit Analysis

* Total profit
* Category-wise profit
* Sub-category profit
* Product-level profit
* Regional profit
* Segment-wise profit
* Discount vs profit analysis

### Shipping Analysis

* Average shipping time
* Shipping time by shipping mode

---

## 🔍 Key Findings

### Category Performance

Technology is the strongest category in terms of both sales and profit.

* Technology Sales: approximately **$836K**
* Technology Profit: approximately **$145K**

### Regional Performance

The West region has the highest:

* Sales: approximately **$725K**
* Profit: approximately **$108K**

### Customer Segment

The Consumer segment contributes the highest sales and profit.

* Sales: approximately **$1.16M**
* Profit: approximately **$134K**

### Loss-Making Sub-Categories

The main loss-making sub-categories are:

* Tables: approximately **-$17.7K**
* Bookcases: approximately **-$3.5K**
* Supplies: approximately **-$1.2K**

### Discount Impact

Higher discount levels are generally associated with lower or negative profitability.

### Yearly Performance

2017 recorded the highest yearly sales and profit in the analyzed dataset.

---

## 💡 Business Recommendations

1. Review the pricing and cost structure of the Tables sub-category.
2. Investigate products with consistently negative profit.
3. Avoid excessive discounting where it reduces profit margins.
4. Focus on high-performing Technology products.
5. Continue strengthening sales in the West region.
6. Monitor product-level profitability instead of relying only on sales.
7. Develop pricing strategies that balance sales growth with profitability.

---

## 📊 Visualizations

The project includes Matplotlib visualizations for:

* Sales by Category
* Profit by Category
* Top 10 Products by Sales
* Sales by Region
* Profit by Customer Segment
* Monthly Sales Trend
* Yearly Sales
* Discount vs Profit

---

## 📁 Project Structure

```text
superstore-sales-analysis-python/
│
├── data/
│   └── superstore.csv
│
├── charts/
│   ├── sales_by_category.png
│   ├── profit_by_category.png
│   ├── top_10_products.png
│   ├── sales_by_region.png
│   ├── profit_by_segment.png
│   ├── monthly_sales.png
│   ├── yearly_sales.png
│   └── discount_vs_profit.png
│
├── Superstore_Sales_Analysis.ipynb
│
└── README.md
```

---

## 🏁 Conclusion

The analysis demonstrates how Python, Pandas, NumPy, and Matplotlib can be used to transform raw sales data into meaningful business insights.
The company performs strongly in Technology and the West region, while specific sub-categories and products create significant losses. The findings suggest that better pricing, discount control, and product-level profitability monitoring could help improve overall business performance.
