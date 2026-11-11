# Analyzing Customer Behavior

**Business Analytics | ST2187 – Business Analytics, Applied Modelling and Prediction (2024–2025)**  
**Author:** Sara Abdulla Ahmed Dhaif

## Project Overview

This project explores customer purchasing behavior using transactional data from **2020 to 2023**. Through five analytical dashboards, it examines where customers are located, what they purchase, how discounts affect profitability, which customers are most valuable, and how customer segments and product combinations grow over time.

The goal is to translate customer and sales data into actionable business recommendations for retention, cross-selling, promotions, and profitability.

## Business Questions

1. Who are the customers, and how do customer segments contribute to sales and profit?
2. Which products are frequently purchased together?
3. Are existing discount strategies effective?
4. Which customers are loyal, occasional, or at risk of being lost?
5. How do customer segments and product combinations grow over time?

## Analysis and Dashboards

| Dashboard | Focus | Methods |
| --- | --- | --- |
| 1. Customer Overview | Geographic distribution, customer segments, sales and profitability | Descriptive analytics and visualizations |
| 2. Purchasing Patterns | Popular product subcategories and items bought together | Market basket analysis, co-occurrence, support and lift |
| 3. Discount Effectiveness | Discounts versus sales and profit | Subcategory and discount-level comparisons |
| 4. Customer Segmentation | Customer value and retention opportunities | Recency, Frequency and Monetary (RFM) analysis |
| 5. Growth Trends | Growth by customer segment and product combinations | Compound Annual Growth Rate (CAGR) |

## Key Findings

- **Customer base:** The United States has the largest customer concentration. Consumers represent just over half of customers, followed by corporate customers (30%) and home-office customers.
- **Business performance:** The report describes approximately **25,000 orders**, **$12 million in sales**, and **$1.5 million in profit**.
- **Popular products:** Binders are the leading subcategory by units sold, at approximately **21,000 units**.
- **Market basket analysis:** **Binders + Storage** has the highest reported support, while **Labels + Copiers** has the highest lift, suggesting potential cross-selling opportunities.
- **Discounting:** Tables have the highest average discount (**29%**) and show an **8% loss** in the report's analysis. For Binders, profit decreases as discounts increase, with losses reported at discounts of 40% or more.
- **RFM segmentation:** Occasional Buyers are the largest customer group, representing approximately **32%** of customers. The analysis identifies opportunities to increase loyalty and win back inactive customers.
- **Growth:** The “Potential to Become Best Customers” segment shows particularly strong profit growth in the final quarter. The **Appliances + Machines** combination has the highest reported CAGR among product combinations, approximately **90%**.

## Business Recommendations

- Create product bundles around frequently co-purchased subcategories, particularly Binders and Storage.
- Test targeted cross-selling offers for complementary products such as Labels and Copiers.
- Review high discount levels on Tables and avoid unnecessary discounts on already-popular products.
- Introduce loyalty incentives to encourage repeat purchases among Occasional Buyers.
- Use customer feedback, competitor analysis, and targeted service improvements to re-engage lost customers.
- Explore seasonal promotions based on segment-level growth patterns.

## Methods Explained

**Market basket analysis:** Examines which product subcategories appear together in orders. Support describes how frequently a combination occurs; lift compares its co-occurrence with what would be expected if purchases were independent.

**RFM analysis:** Groups customers based on how recently they purchased (Recency), how often they purchase (Frequency), and how much they spend (Monetary value). The report uses quartile-based scores to create customer segments.

**CAGR:** Summarizes the average compounded annual growth rate over a period, used here to explore changes in customer segments and product combinations.

## Report

The full report contains the five dashboards, charts, technical appendix, and references. See **`230713279.docx`** if it is included in this repository.

## Scope and Notes

This README summarizes the findings reported in the coursework. The underlying dataset, dashboard source files, and executable code were not provided alongside the report, so no installation or reproduction instructions are included. Findings describe observed associations and do not by themselves establish causation.

## References

The report references the *Customer Winback Benchmark Study* (WinBack Lab, 2023), Duffy (1998) on customer loyalty strategies, and Suite Feedback (2019) on customer experience. Full citations are provided in the report.
