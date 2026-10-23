# TastyBites Product Pricing & Profitability Analysis

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/Analytics-Pricing%20%26%20Profitability-4472C4" alt="Pricing and Profitability">
  <img src="https://img.shields.io/badge/Status-Completed-green" alt="Completed">
</p>

<p align="center">
  <strong>A Power BI business analytics project examining product revenue, costs, profit margins, and discount-related pricing decisions.</strong>
</p>

---

## Table of Contents

- [Project Abstract](#project-abstract)
- [Business Scenario](#business-scenario)
- [Business Objectives](#business-objectives)
- [Business Questions](#business-questions)
- [Dataset Overview](#dataset-overview)
- [Tools and Techniques](#tools-and-techniques)
- [Methodology](#methodology)
- [Dashboard Preview](#dashboard-preview)
- [Key Findings](#key-findings)
- [Business Recommendations](#business-recommendations)
- [Project Structure](#project-structure)
- [How to Review the Project](#how-to-review-the-project)
- [Limitations](#limitations)
- [Author](#author)

---

## Project Abstract

TastyBites is a product pricing and profitability case study focused on understanding how revenue, product costs, sales volumes, and discounts relate to product-level profitability. The project uses Power BI to compare products and categories and identify areas for further pricing and promotional analysis.

The dashboard brings together commercial measures to help distinguish products that generate substantial sales from those that contribute stronger profit margins. The analysis supports recommendations related to discount management, product promotion, and potential bundling opportunities.

The project uses the defined calculation of profit as revenue minus cost. Because delivery expenses and other operating costs are excluded, the calculated profit should be interpreted as product-level profit under the project's assumptions rather than complete business net profit.

## Business Scenario

TastyBites is presented as a food delivery business operating across multiple cities. Management wants to understand why some products generate low profit despite high sales while other products contribute more strongly to profitability.

## Business Objectives

- Compare revenue and profit across products and categories.
- Examine product-level profit margins.
- Investigate discount-related patterns.
- Identify products for further pricing or promotional review.
- Recommend practical ways to improve product-level profitability.

## Business Questions

1. Which products and categories generate the highest revenue and profit?
2. How do product margins differ?
3. How are discounts associated with profitability?
4. Which products combine strong sales with relatively low margins?
5. Which promotional or bundling opportunities merit further testing?

## Dataset Overview

| Attribute | Description |
|---|---|
| Dataset | `tastybites_orders.csv` |
| Format | CSV |
| Analysis tool | Microsoft Power BI |
| Business domain | Product pricing and profitability |

The supplied dataset supports product- and category-level analysis. Refer to the CSV and report for the exact fields and calculation definitions.

## Tools and Techniques

- Microsoft Power BI
- Data preparation
- KPI cards and DAX measures
- Product and category comparisons
- Revenue and profit analysis
- Margin calculations
- Discount analysis
- Data visualization

## Methodology

### 1. Data Preparation

Inspect the source data and prepare the product, sales, cost, and discount fields used in the analysis.

### 2. KPI Calculation

Calculate the available revenue, cost, profit, and margin measures.

**Project profit formula:**

`Profit = Revenue - Cost`

**Project profit margin formula:**

`Profit Margin = Profit / Revenue × 100`

These calculations exclude delivery costs and other operating expenses.

### 3. Product and Category Analysis

Compare sales, revenue, profit, and margin to understand differences in commercial performance.

### 4. Discount Analysis

Examine how discounts relate to the available product-level profitability measures.

### 5. Business Recommendations

Identify products and categories that merit further review and propose pricing or promotional actions based on the observed results.

## Dashboard Preview

![TastyBites Pricing and Profitability Dashboard](images/TastyBites_Pricing_Profitability_Dashboard.png)

[Open the dashboard PDF](dashboard/TastyBites_Pricing_Profitability_Dashboard.pdf)

## Key Findings

The analysis compares product and category performance using revenue, profit, and profit margin.

The project findings include product-level margin differences. For example, the analysis identified a profit margin of approximately 27.73% for Veg Pizza and approximately 30.86% for Meals under the project's profit definition.

These values should be interpreted using the report's calculation rules, which exclude delivery and other operating expenses.

Refer to the final report and dashboard for the complete findings.

## Business Recommendations

- Evaluate product performance using both revenue and profit margin.
- Review discount strategies where promotional activity coincides with weaker margins.
- Consider testing bundles that combine complementary products.
- Monitor results after pricing or promotional changes.
- Avoid treating product-level profit as net profit when delivery and operating costs are excluded.

## Project Structure

```text
TastyBites-Pricing-Profitability-Analysis/
├── README.md
├── data/
│   └── tastybites_orders.csv
├── dashboard/
│   ├── TastyBites_Pricing_Profitability_Dashboard.pbix
│   └── TastyBites_Pricing_Profitability_Dashboard.pdf
├── report/
│   └── TastyBites_Pricing_Profitability_Report.pdf
└── presentation/
    ├── TastyBites_Executive_Presentation.pptx
    └── TastyBites_Executive_Presentation.pdf
