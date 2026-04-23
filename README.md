# Bank-Loan-Analysis
End-to-end loan data analysis project leveraging Python (Pandas) for data cleaning, SQL for exploratory analysis, and Power BI &amp; Excel Pivot Tables for interactive dashboards — covering KPIs like loan trends, grade-wise revolving balance, payment verification, and state/month-wise loan status.
📌 Project Overview
This project performs a comprehensive analysis of loan data to uncover trends, risk patterns, and financial insights. The pipeline covers the full analytics workflow — from raw data cleaning to interactive dashboards — using industry-standard tools across each stage.
The goal is to help stakeholders understand borrower behavior, repayment patterns, and portfolio health through meaningful KPIs and visual storytelling.
🛠️ Tech Stack
Stage            ToolData 
Cleaning         Python (Pandas)
Data Analysis    SQL
Visualization    Dashboard & VizPower BI, Excel Pivot Tables

Business Problem:
A lending company is issuing loans without a data-driven understanding of borrower behavior, repayment patterns, and portfolio risk — leading to increased defaults, poor risk segmentation, and missed business opportunities.

📊 Key Performance Indicators (KPIs)
1. 📅 Year-wise Loan Amount Stats
Tracks how total loan disbursements have changed over the years, helping identify growth trends, peak lending periods, and year-over-year changes in loan volume and average loan size.
2. 🏷️ Grade and Sub-Grade wise Revolving Balance
Analyzes the revolving balance (revol_bal) segmented by loan grade (A–G) and sub-grade. This KPI highlights credit risk distribution — higher-grade borrowers typically maintain lower revolving balances, indicating healthier financial behavior.
3. ✅ Total Payment — Verified vs. Non-Verified Status
Compares total payments made by borrowers whose income is verified against those who are not verified. This insight is crucial for understanding how verification status correlates with repayment behavior and default risk.
4. 🗺️ State-wise and Month-wise Loan Status
A geographic and temporal breakdown of loan statuses (Fully Paid, Charged Off, Current, etc.). This KPI reveals regional lending patterns and seasonal fluctuations in loan performance across different states.
5. 🏠 Home Ownership vs. Last Payment Date Stats
Examines how a borrower's home ownership category (Own, Rent, Mortgage) correlates with their last payment date. This helps assess whether home ownership influences timely repayment behavior.

🔄 Project Workflow
 1.Raw Loan Data : Python (Pandas)
  - Data Cleaning 
  - Null handling     
  - Type conversion   
  - Outlier removal   
  - Feature formatting
 2. Data Analysis: SQL
  - Aggregations      
  - GROUP BY queries  
  - Filtering & joins 
  - KPI computation   
 3. Dashboard & Visualization : Power BI + Excel
  - Interactive Power BI reports  
  - Excel Pivot Table summaries   
  - Slicers, filters, drill-downs

📌 Key Insights:

- Loan issuance peaked in [2011], showing a sharp increase in personal loan demand.
- Grade B and C borrowers carry the highest revolving balances, indicating moderate credit risk.
- Verified borrowers contribute significantly higher total payments, suggesting better repayment discipline.
- States like CA, TX, and NY dominate loan volumes, with seasonal dips observed in Q1.
- Mortgage homeowners show more consistent last payment dates compared to renters.

## Dashboards:
Power BI Dashboard [preview] : https://github.com/anupamanagireddi01-DataAnalyst/Bank-Loan-Analysis/blob/main/Loan%20analaysis%20dashboard.PNG
Excel Dashboard [preview] : 



