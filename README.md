# Mobile-Phone-and-Laptops-Prediction-


Here’s a **README** file for **Mobile Phones and Laptops Dataset**, based on analysis questions and it includes fields like Product Type, Brand, RAM, ROM/Storage, Price, Sales Volume, Revenue, and Region:

---

# 📊 Mobile Phones and Laptops Dataset - README

## 📁 Overview

This dataset contains detailed sales, product, and customer preference data for mobile phones and laptops. It is intended for business analysis, market trend discovery, and statistical modeling — including identifying top-performing products, features influencing customer purchases, and regional sales variations.

---

## 📂 Dataset Contents

Each row in the dataset represents an individual product (mobile phone or laptop) or a sales record. The dataset includes the following columns:

| Column Name                       | Description                                                        |
| --------------------------------- | ------------------------------------------------------------------ |
| **Product\_ID**                   | Unique identifier for each product                                 |
| **Product\_Type**                 | Type of product (e.g., Mobile, Laptop)                             |
| **Brand**                         | Manufacturer or brand name (e.g., Samsung, HP, Apple)              |
| **Model**                         | Specific model name/number of the product                          |
| **RAM (GB)**                      | Random Access Memory size in gigabytes                             |
| **ROM/Storage (GB)**              | Internal storage or hard disk space in gigabytes                   |
| **Processor**                     | Processor type (if applicable)                                     |
| **Price (USD or Local Currency)** | Selling price per unit                                             |
| **Sales\_Volume**                 | Number of units sold                                               |
| **Revenue**                       | Total revenue from the product (usually Price × Sales Volume)      |
| **Region**                        | Geographic location of the sale (e.g., North, South, Lagos, Abuja) |
| **Date** *(optional)*             | Date of sale or reporting                                          |

---

## 📌 Key Use Cases

You can use this dataset to answer questions like:

* ✅ Which **product** or **brand** has the **highest sales volume and revenue**?
* ✅ Which **regions** contribute the most to **overall sales**?
* ✅ Do **higher RAM and ROM** specifications correlate with **higher price** or **customer purchases**?
* ✅ What are the **geographic trends** in mobile vs laptop sales?
* ✅ What product features most influence **customer purchase decisions**?

---
📊 Regression Analysis Summary
Regression analysis was conducted to examine how RAM and ROM (storage) impact the product price and sales volume.

🎯 Model 1: Price ~ RAM + ROM
Objective: Assess whether RAM and ROM affect the price of mobile phones and laptops.

Result:

Weak positive correlation between features and price.

Model R² ≈ 0.0009, indicating a very low explanatory power.

Conclusion: RAM and ROM alone do not significantly explain price variations — other factors (brand, processor, display, etc.) likely have a stronger effect.

📈 Model 2: Sales Volume ~ RAM + ROM
Objective: Evaluate how RAM and ROM influence purchase behavior (via sales volume).

Result:

Mid-range RAM/ROM products had higher sales volume.

High-end specs didn’t always lead to more purchases.

Indicates customer preference for affordability and balanced features, rather than maximum specifications.

🛠️ Analysis Ideas
Pivot Tables: Summarize revenue/sales by product, brand, and region.

Regression Analysis: Explore further how product features affect price or customer demand.

Visualization: Use charts to show top-selling brands, feature impact, and regional distribution.

Filtering: Focus on product types (Mobiles vs Laptops) or specific regions for targeted insights.

📄 Data Quality Notes
Ensure missing values (e.g., blank RAM/ROM or price) are cleaned before analysis.

Prices and revenue should be in a consistent currency.

Sales volume and revenue should be numeric for analysis.



## 🛠️ Analysis Ideas

* **Pivot Tables**: Summarize revenue/sales by product, brand, and region.
* **Regression Analysis**: Examine how features (RAM, ROM, etc.) affect price or sales.
* **Visualization**: Use charts to show top-selling brands, feature impact, and regional distribution.
* **Filtering**: Focus on product types (Mobiles vs Laptops) or specific regions for targeted insights.

---

## 📅 Dataset Format

Typically stored as:

* Excel (`.xlsx`)
* CSV (`.csv`)
* Can be imported into Power BI, Excel Power Query, or Python/Pandas for analysis.

---
