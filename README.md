# 🍕 Pizza Sales Data Analysis w/ SQL & Power BI



This project presents an end-to-end analysis of 2015 pizza sales data. The workflow involved data extraction via SQL, robust data cleaning and transformation using **Power BI's internal ETL capabilities (Power Query)**, and dynamic visualization and business reporting.

---

## 1. Project Goal & Tools

* **Goal:** Provide an executive-level overview of annual performance and a deep-dive product analysis for the 'Classic' pizza category to support strategic decision-making.
* **Time Frame:** January 2015 - December 2015
* **Tools Used:**
    * **Visualization & Modeling:** Microsoft Power BI
    * **Data Transformation (ETL):** Power Query in Power BI
    * **Data Connection & Retrieval (Source):** Excel to SQL

---

## 2. Key Performance Indicators (KPIs) & Definitions

This dashboard contains two pages with distinct, yet related, KPIs.

### Page 1: Pizza Sales Dashboard (Overall Summary)

![Dashboard Page 1](/images/Dashboard.png)

| Metric | Value | Definition |
| :--- | :--- | :--- |
| **Total Revenue** | 817.86K | Total gross sales for the year. |
| **Total Order** | 21K | Total number of customer transactions. |
| **Avg Order Value (USD)** | 38.31 | **Average total revenue per customer transaction.** (i.e., Average Customer Spend) |
| **Avg Pizzas per Order** | 2.32 | The average number of pizzas sold in a single transaction. |

### Page 2: Pizza Category Drill Through 

![Dashboard Page 1](/images/Drill%20Through.png)

This page focuses on the detailed performance metrics for a selected pizza category (e.g., Classic).

| Metric | Definition |
| :--- | :--- |
| **Median Revenue per Order** | The **typical (50th percentile)** total customer transaction amount for the selected category. |
| **Total Order** | Total number of transactions for the selected category. |
| **Avg Order Value (USD)** | **Average revenue generated per single pizza item.** (i.e., Average Revenue per Pizza Item) for the selected category. |
| **Avg Pizzas per Order** | The average number of pizzas sold per transaction in the selected category. |

---

## 3. Skills Showcased 🛠️

* **Data Transformation (ETL):** Extensive use of **Power Query** (M Language) within Power BI for data cleaning, shaping, and establishing a robust analytical model.
* **Data Querying:** Writing and executing efficient **SQL** queries for initial data extraction and aggregation.
* **Power BI Modeling:** Creation of both **implicit and explicit measures** (using DAX) to define complex KPIs (e.g., Median Revenue, Avg Pizzas per Order).
* **Dashboard Design & Interactivity:** Implementing best practices in dashboard design, utilizing **buttons** for navigation, **slicers**, and **drill-through** functionality between pages.
* **Core Charting:** Effective use of **KPI Cards**, **Line Charts**, **Bar Charts**, **Column Charts**, and **Donut Charts** to communicate diverse insights.

---

## 4. Analytical Insights & Business Recommendations

* **Operational Peak:** **Friday** is the clear peak day for order volume, requiring maximum resource allocation. **July** was the highest-volume month.
* **Low-Value Segment Diagnostic:** The **Classic** category is high-volume but a low-value segment. The **Median Revenue per Order ($\$14.5$)** is significantly lower than the overall **Avg Customer Spend ($\$38.31$)**, indicating that the majority of sales are for single, lower-priced items.
* **Pricing Strategy:** The Classic category's transaction average $(\approx\$27.76)$ shows these customers spend approximately **\$10 less** per visit, highlighting a strong opportunity for targeted upselling (e.g., suggesting add-ons or bundles) to increase customer spend.
* **Product Focus:** The **Large** size is the dominant contributor to both revenue and sales volume.

## Conclusion

This analysis successfully segmented sales performance, identified immediate operational bottlenecks (Friday and July peaks), and provided actionable data for the pricing team to address the low-value nature of the Classic pizza segment. The dashboard provides a dynamic, single source of truth for all key stakeholders.