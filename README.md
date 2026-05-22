# FMCG Market Intelligence Report

## National vs Private Label Brand Analysis

This project analyzes FMCG sales data to understand how National Brands are performing against Private Label brands across different grocery departments.

The goal of this project was to identify where National Brands are winning, where Private Labels are gaining share, and whether discounting is helping brands defend their position or only reducing margins.

## Project Overview

This analysis is based on the Dunnhumby Complete Journey dataset, which contains grocery transaction data from Kroger households in the United States.

The project covers:

- 5,000 Kroger households
- 48 weeks of transaction data
- $3.2M in recorded sales
- National Brand vs Private Label comparison
- Department level market share analysis
- Discount intensity analysis
- Weekly sales trend analysis

## Key Business Question

Where are National Brands winning, and where are Private Labels quietly taking over?

## Key Findings

1. National Brands hold 72.97% overall market share, while Private Labels hold 27.03%.

2. Private Labels are strongest in:
   - Packaged Seafood: 64.69% Private Label share
   - Pastry: 52.14% Private Label share

3. The average discount rate is 17.6%, showing that brands are heavily using promotions to defend market share.

4. National Brands are discounting hardest in the same departments where they are losing share, which may protect short term sales but can hurt margins and brand value.

5. Private Label sales show a gradual upward trend, making weekly monitoring important for brand managers.

## Tools Used

- Microsoft Excel
- Power BI
- VLOOKUP
- Pivot Tables
- DAX Measures
- Data Cleaning
- Market Share Analysis
- Business Reporting

## Data Preparation

The original dataset contained separate files for transactions, products, and household demographics.

The transaction file was enriched using product level information such as brand type, category, and department.

Key calculated fields included:

- Discount Percentage
- Promo Flag
- Weekly Growth
- National Brand Share
- Private Label Share
- Average Discount Rate

## Dashboard Components

The Power BI dashboard includes:

- KPI Cards
- Brand Market Share Donut Chart
- Department Level Battleground Chart
- Weekly Sales Trend Line Chart
- Discount Intensity Chart
- Interactive Brand and Department Filters

## Business Recommendations

### 1. Defend Packaged Seafood and Pastry

National Brands should focus on these departments because Private Labels already hold a strong position there.

### 2. Reduce Discount Dependency

A 17.6% average discount rate is high. Brands should not rely only on price promotions because it can reduce margins over time.

### 3. Monitor Weekly Trends

Private Label growth should be tracked continuously so brands can respond early before losing more share.

## Files in This Repository

```text
FMCG_Market_Intelligence_Report.pdf
README.md
dashboard_screenshot.png
sample_data.csv
