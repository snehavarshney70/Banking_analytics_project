 Banking Risk Analytics Dashboard

This project provides a comprehensive analysis of core banking data using Power BI and Python. The goal is to extract actionable business insights related to financial risk, client segmentation, and capital exposure to minimize the risk of loan defaults and financial loss.

 Project Overview

The analysis is divided into three key areas, focused on providing a consolidated view of the bank's health and lending risk profile:

1. Executive Overview & Health Indicators
Key Performance Indicator (KPI)                	Value	                                                     Observation
Total Loan	                                    $4.38B	                             Total financial exposure (Bank Loans, Business Lending, Credit Cards).
Total Deposit                                 	$3.77B	                             Total customer capital held by the bank.
Total Clients                                  	2,940	                               Total unique client base.
Profit Margin (Total Fees)                    	$158.19M	                           Revenue generated from processing fees.

Visualizations:

Overall Loan vs. Deposit comparison

Total amounts held in Savings, Checking, and Foreign Currency accounts

2. Loan Risk & Segmentation

Focuses on dissecting the $1.77B in high-risk Bank Loans to identify where the bank is most exposed.

Key Breakdown Areas:

Risk by Income Band: Loan distribution across client income levels

Risk by Relationship: Exposure by Banking Relationship type (Private Bank, Retail, etc.)

Risk by Loyalty: Loan amounts compared against client Engagement Length

Visualizations:

Bar charts showing loan exposure by Income Band

Bar charts showing loan exposure by Banking Relationship

3. Profitability & Mitigation

Analyzes which client groups are most valuable and where mitigation efforts should be focused.

Fee Generation: Total fees by Loyalty Classification (Platinum, Gold, Silver, etc.)

Capital Gap Analysis: Total Loan vs. Total Deposit to identify capital stress

 Key Insights & Business Impact
1. Highest Risk Segment

Mid-Income clients account for 53% ($942M) of the total Bank Loan debt.
Impact: Bank should tighten lending standards for Mid-Income segment to reduce exposure.

2. Capital Warning

Total Loans ($4.38B) exceed Total Deposits ($3.77B).
Impact: Indicates a capital-risk concern — bank must encourage deposit growth or reduce lending.

3. Highest Value Clients

'Platinum' loyalty clients generate the highest processing fee revenue.
Impact: Strengthen customer retention programs targeting this segment.

 Files in This Repository
File Name	                                  Description
dashboard.pbix	                          Power BI dashboard file — open in Power BI Desktop.
banking_project.ipynb	                    Python notebook for connecting PostgreSQL, preprocessing, and feature engineering.
Banking Report.docx                     	Detailed project documentation: problem statement, data sources, metrics.
banking_dashboard_12.pdf                 	Exported PDF version of the final dashboard.
README.md	                                This project overview and documentation.

 Tools & Technologies

Power BI – Dashboard creation, data modeling, DAX KPIs

Python (pandas, SQLAlchemy) – Data preprocessing & PostgreSQL connection

GitHub – Version control and collaboration

Contact
For questions or collaboration, feel free to reach out via GitHub.

