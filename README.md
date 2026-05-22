# FMCG Market Intelligence Analysis

## National Brands vs Private Labels

This project analyzes FMCG transaction data to understand how National Brands are performing against Private Label brands across key grocery departments.

The objective was to identify where National Brands are still dominant, where Private Labels are gaining share, and whether promotional discounting is protecting market share or creating margin pressure.

---

## Business Context

Consumer packaged goods brands are facing increasing competition from retailer owned Private Labels. These products often compete on price, shelf placement, and perceived value.

For brand managers, the key challenge is not only knowing overall market share, but understanding exactly which departments are becoming vulnerable and whether discounts are actually helping defend the brand position.

This project focuses on three core business questions:

1. Where are Private Labels gaining share against National Brands?
2. Which departments are the biggest competitive battlegrounds?
3. Are National Brands using discounts effectively, or are they buying short term sales at the cost of margin?

---

## Data Source

The analysis is based on the **Dunnhumby Complete Journey dataset**, a public retail dataset released by **84.51° / Kroger** and available on Kaggle.

Dataset details:

- Retailer: Kroger
- Country: United States
- Households: 5,000 loyal Kroger shoppers
- Time period: 48 weeks
- Data type: Household level grocery transactions
- Key files used:
  - `transaction_data.csv`
  - `product.csv`
  - `hh_demographic.csv`

The full CSV files are not included in this repository due to file size. A sample dataset is added only for reference. The original dataset should be downloaded directly from Kaggle.

---

## Project Scope

The project covers:

- Brand share analysis
- National Brand vs Private Label comparison
- Department level performance tracking
- Discount intensity analysis
- Weekly sales trend analysis
- Business recommendations for FMCG and CPG stakeholders

---

## Tools Used

- Microsoft Excel
- Power BI
- VLOOKUP
- Pivot Tables
- DAX Measures
- Data Cleaning
- Business Reporting

---

## Data Preparation

The raw transaction data contained product level purchase information but did not directly include brand type, category, or department details.

To prepare the data for analysis, the transaction file was enriched using the product master file.

Key preparation steps:

- Joined transaction data with product level attributes
- Added brand type, category, and department fields
- Created discount percentage calculations
- Flagged promotional transactions
- Prepared department level summaries
- Built weekly sales trend views
- Created measures for National Brand share, Private Label share, and average discount rate

---

## Key Metrics

| Metric | Value |
|---|---:|
| Total Recorded Sales | $3.2M |
| National Brand Share | 72.97% |
| Private Label Share | 27.03% |
| Average Discount Rate | 17.6% |
| Analysis Period | 48 Weeks |
| Households Covered | 5,000 |

---

## Key Findings

### 1. National Brands lead overall, but the risk is hidden at department level

National Brands hold **72.97%** of total recorded sales, while Private Labels account for **27.03%**.

At the overall level, National Brands appear strong. However, department level analysis shows that Private Labels are already leading in selected categories.

---

### 2. Private Labels are strongest in Packaged Seafood and Pastry

The most competitive departments are:

| Department | National Brand Share | Private Label Share |
|---|---:|---:|
| Packaged Seafood | 35.31% | 64.69% |
| Pastry | 47.86% | 52.14% |
| Grocery | 73.12% | 26.88% |
| Deli | 76.93% | 23.07% |
| Packaged Meat | 79.03% | 20.97% |

Packaged Seafood is the biggest risk area, with Private Labels holding nearly two thirds of sales. Pastry is also at a critical point, with Private Labels slightly ahead of National Brands.

---

### 3. Discounts are highest where National Brands are weakest

The average discount rate across the market is **17.6%**.

The analysis shows that National Brands are discounting heavily in the same departments where Private Labels are gaining share. This suggests that brands may be defending volume through promotions, but not solving the underlying value perception problem.

---

### 4. Private Label growth needs continuous monitoring

The weekly trend shows National Brands maintaining higher absolute sales, but Private Labels show gradual upward movement over time.

A Week 48 anomaly was identified due to incomplete transaction data and was treated separately during trend interpretation.

---

## Dashboard Summary

The Power BI dashboard was designed as a single page business intelligence report focused on decision making.

Dashboard components include:

- KPI cards for total sales, brand share, and discount rate
- Brand market share chart
- Department level battleground analysis
- Weekly sales trend
- Discount intensity by department
- Interactive filters for brand and department

The dashboard avoids unnecessary visuals and focuses only on metrics that support business decisions.

---

## Business Recommendations

### 1. Prioritize Packaged Seafood and Pastry

National Brands should treat Packaged Seafood and Pastry as priority departments. Private Labels are already leading in these areas, which indicates a stronger consumer shift toward value driven alternatives.

---

### 2. Reduce dependency on price promotions

A high discount rate may protect short term sales, but it can weaken margins and train customers to wait for promotions.

National Brands should focus more on product differentiation, value communication, packaging, and category specific positioning instead of relying only on discounts.

---

### 3. Track Private Label movement weekly

Private Label growth should be monitored continuously at the department level. Early detection can help brands respond before the shift becomes difficult to reverse.

---

## Final Insight

National Brands still lead the market overall, but Private Labels are already winning in specific departments.

The real risk is not visible in the total market share number. It appears only when the data is analyzed at department level.

This project shows how raw retail transaction data can be converted into market intelligence that supports pricing, promotion, and category strategy decisions.

---

## Author

**Ujwal Amin**  
