# Finance Analysis Dashboard (Power BI)

## 🎯 Project Objective
Developed a Finance Analysis dashboard to provide real-time insights into transactions, customers, and risk. The goal was to integrate raw financial data, model relationships, and deliver actionable metrics for decision-making in the financial services sector.

## ⚙️ Process
1. **Data Preparation (Power Query)**
   - Connected multiple raw data sources (transactions, customers, fees, taxes).
   - Cleaned and transformed data: duplicated, handled nulls, standardized formats, merged column.
  
2. **Data Modeling**
   - Built a star schema linking fact tables (transactions, amounts, fees, taxes) with dimension tables (date, customer).
   - Established relationships to enable cross-filtering and drill-down analysis.
   - Built Dynamic Metrics with DAX for measures:
     - **Total Amount**
     - **Total Transactions**
     - **Total Fees**
     - **Total Taxes**

3. **DAX Calculations**
   - Defined measures for KPIs:  
     - Total Amount, Total Transactions, Average Transaction Value.  
     - Total Fees and Taxes.  
   - Year-over-Year (YoY) growth percentages.
   - Dynamic measures supporting slicers (Year, Occupation, Category...)

4. **Visualization**
   - KPI cards with YoY comparison.
   - Line charts for monthly revenue trends.  
   - Donut charts for transaction status and gender distribution.  
   - Bar charts for customer segments and regional contributions.  
   - Tables for transaction type analysis (amounts, fees, taxes).  

## Key Results

| Metric                      | Value              | YoY Change     |
|----------------------------|--------------------|----------------|
| Total Amount               | $137.53 million    | +1.41%         |
| Total Transactions         | 14.94 thousand     | -0.57%         |
| Average Transaction Value  | 9.20 thousand      | +1.98%         |
| Total Fees                 | $216.94 thousand   | -0.17%         |
| Total Taxes                | $39.04 thousand    | -0.26%         |

**Other notable findings:**
- **Transaction Status**: 85.4% Successful, 10.4% Failed, 4.2% Pending
- **Customer Segment**: Retail contributes the highest revenue ($76 million)
- **Top State**: Maharashtra leads with $22 million
- **Top Transaction Type**: Loan EMI generates the highest amount ($40.02 million)
- **Gender Distribution**: Male 52.8% – Female 47.2%

---

## 📈 Business Insights
- **Revenue Growth:** Slight increase in total amount despite fewer transactions → higher average transaction value indicates stronger customer spending.  
- **Risk Management:** 10%+ failed transactions highlight areas for improving payment reliability and customer trust.  
- **Customer Segmentation:** Retail dominates revenue, but Premium and SME segments show significant contributions → opportunity for tailored financial products.  
- **Regional Strategy:** Maharashtra and Karnataka lead in revenue → prioritize regional campaigns and branch expansion.  
- **Product Focus:** Loan EMI and Deposits generate the largest share → optimize interest rates and cross-sell investment products.  
- **Gender Analysis:** Balanced male/female contribution → marketing strategies should remain inclusive and diversified.  

This project demonstrates end-to-end BI capabilities: data preparation, modeling, advanced DAX calculations, and visualization. The dashboard provides financial institutions with actionable insights to optimize product offerings, reduce transaction risk, and strengthen customer engagement.
