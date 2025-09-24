# Superstore Return-Rate Analysis

## Project Goal
The goal of this project was to analyze customer return patterns for E-commerce website. Our goal identify the root causes of returned orders. The CEO requested a clear understanding of why returns are occurring at such a high rate and what strategic actions can be taken to reduce them. The analysis aimed to quantify the financial and operational impact of returns and to provide data-driven insights that support process improvements.
<img src="dashboard.png" />

## Tools Used
Tableau (for data visualization and dashboard design)
Excel / Google Sheets (for data preparation and validation)
SQL (for data joins and calculated fields)
Pivot Tables and Filters (for exploratory analysis)

## Approach & Methodology

Data Preparation
Performed a LEFT JOIN of the Returns table with the Orders table.
Created a calculated field for returns, assigning “Yes = 1” and “Null = 0” to measure return rate (average) and total returns (sum).
    Exploratory Analysis
Scatterplot: Assessed correlation between sales and returns aggregated by product subcategory.
Bar Chart: Calculated return rate by product category to identify categories with disproportionate return behavior.
Customer Analysis: Evaluated return rate by customer, filtering out one-time buyers to detect patterns among repeat customers.
Geographic Map: Analyzed return rate by state and city to detect regional concentrations.
Time-Series: Tracked return rate by month to identify seasonal effects.
Composite Charts: Combined multiple dimensions (date, geography, product category) to uncover layered insights into return patterns.
    Dashboard Development
Designed an interactive Tableau dashboard with KPIs, filters, and visualizations to allow the CEO and leadership team to monitor and investigate return trends.

## Key Findings From the Data
High Return Categories:
Office Supplies and Furniture have the most returns compared to sales.
Could point to quality or shipping issues.

Sales vs. Returns
Big sellers like Chairs and Binders also get returned a lot.
High sales don’t fully explain the high return rates.

Customer Trends
Some repeat customers return items more often.
This may show dissatisfaction or overuse of return policies.

Geographic Patterns
Certain cities have higher return rates.
Could be linked to delivery or local fulfillment problems.

Seasonality
Returns spike in Q4 (holiday season).
Likely due to higher order volume stressing logistics and quality control.

## Recommendations

1. Improve Product Quality & Packaging
Focus on Office Supplies and Furniture to reduce return rates.
Add stricter quality checks and better packaging for fragile items.
2. Investigate High-Return Subcategories
Review Chairs and Binders for recurring defects or unclear product descriptions.
Update listings with clearer specs and images.
3. Address Repeat Customer Returns
Flag frequent returners and check for potential policy misuse.
Use feedback surveys or loyalty perks to improve satisfaction.
4. Fix Regional Fulfillment Issues
Audit delivery partners in high-return cities.
Consider alternative couriers or local warehouses.
5. Prepare for Seasonal Spikes
Strengthen quality control before Q4.
Add temporary logistics support to handle holiday demand.

