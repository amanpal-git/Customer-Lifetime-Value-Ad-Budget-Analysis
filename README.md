# Customer Acquisition Analysis

## Overview
This project analyzes customer acquisition strategies for company, focusing on customer lifetime value (LTV), advertising budget efficiency, and profitability forecasting. The analysis compares different acquisition models and provides data-driven recommendations to optimize ad spending and maximize returns.

## Key Insights
- **Base LTV:** £90
- **Avg Adjusted LTV:** £92.70 (Calculated using XLOOKUP)
- **Estimated CAC:** £330,000
- **Total Ad Budget (CPM Method):** £10,000
- **Expected Revenue:** £87,282
- **Profitability Finding:** CPM method is 3.6x more profitable than CAC

## Objective
This project aims to:
- Provide insights into customer value (LTV)
- Evaluate the impact of ad budgets on acquisition
- Forecast profitability for strategic decision-making

## Methodology
1. **Data Preparation**
   - Customer segmentation using `CHOOSE` and `RANDBETWEEN` functions
   - LTV adjustments using `XLOOKUP`
2. **Calculations**
   - LTV = `(Monthly Subscription × Gross Margin) / Churn Rate`
   - Estimated CAC = `1000 * Average CAC per Customer`
   - Ad Budget Impressions = `(1000 / 5%) * 100%`
   - Ad Budget Cost = `(Impressions / 1000) * CPM`
3. **Visualization & Dashboarding**
   - Customer segment distribution
   - Budget vs returns comparison
   - Profit forecasting (CPM method)

## Files Included
- `Analysis_report.pdf`: Contains the final analysis and visualizations
- `Analysis.xlsx`: Raw data and calculations

## Tools Used
- **Microsoft Excel / Google Sheets** for data manipulation and visualization
- **Power BI** (optional) for advanced data visualization

## How to Use
1. Open the `Analysis.docx` to review the key findings.
2. Analyze the included Excel file for detailed calculations.
3. Use the methodology to refine or expand the analysis with updated data.

## Conclusion
The analysis demonstrates that optimizing ad spend using the **CPM model** leads to significantly higher profitability. Businesses should prioritize **CPM-based acquisition strategies** while focusing on high-LTV customer segments to maximize ROI.

---

