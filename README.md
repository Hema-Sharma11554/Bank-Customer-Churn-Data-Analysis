🏦 Bank Customer Churn Analysis - Power BI Dashboard
10K customers analyzed | 2,037 churned | 20.4% churn rate | Identify at-risk segments & retention strategy
![Live Dashboard](https://img.shields.io/badge/Live%20Dashboard-View%20Interactive%20Report-brightgreen?style=for-the-badge&logo=powerbi)
![GitHub](https://img.shields.io/badge/GitHub-View%20Code-black?style=for-the-badge&logo=github)
![Portfolio](https://img.shields.io/badge/Portfolio-7%20Projects-blue?style=for-the-badge)
🔗 Quick Links
Resource	Link
📊 Live Dashboard	Click to Interact - Novy.pro - Replace with your Novy.pro link
💻 GitHub Repo	https://github.com/Hema-Sharma11554/Bank-Customer-Churn-Data-Analysis
🌐 My Portfolio	https://hema-sharma11554.github.io/Portfolio-Hema-Sharma11554/

💰 Key KPIs
Metric	Value	Business Impact
Total Customers	10K	Base analyzed
Lost Customers	2,037	Churned customers
Churn Rate	20.4%	Critical - 1 in 5 leaving
Avg Churn Risk	France 50.14% customers	Highest risk geography

📊 Dashboard Walkthrough
Main Dashboard - Bank Churn Analysis Overview
Complete view of churn drivers: Gender, Activity Status, Credit Card, Country, Product, Age, Credit Score & Salary segments.
![Bank Churn Main Dashboard](Bank_Churn_Analysis_Dashboard.png)

Row 1 - KPI Cards:
10K Customers, 2037 Lost, 20.4% Churn Rate + Gauge chart 0-100%
Row 2 - Customer Segmentation:
Customers by Gender:
Male 54.57% (5K) vs Female 45.4% (5K) - Balanced base
<img width="400" alt="Gender" src="https://github.com/user-attachments/assets/REPLACE_GENDER" />
Customers by Activity Status:
Active 51.5% (5K) vs Inactive 48.4% (5K) - Inactive = high churn risk
Insight: Inactive users churn more
Customers by Credit Card Status:
Owned 70.55% (7K) vs Not Owned 29.45% (3K) - Card holders more loyal
Customers by Country:
France 50.14% (5K), Germany 25.x%, Spain 24.x%
France customers highest churn (from previous analysis)
Customers by Product:
Prod 1: 50.84% (5K), Prod 2: 45.9% (5K), Prod 3 & 4 <2%
Single product holders = churn risk
Row 3 - Churn Drivers - The Most Important:
Customers and Churn Rate by Age Groups (Left Chart):
Age 31-40: Largest segment 4K+ customers but low churn ~10%
Age 51-60: Highest churn ~55% | Age 61-70: ~31% churn
Action: Retention campaign for 41-60 age group
Customers and Churn Rate by Credit Score (Middle Chart - 400-800):
Credit Score <=400: 100% churn rate - Extremely high risk!
401-500: ~20% churn, 501-800: ~15-18% churn
Action: Tighten approval for <400 score or special retention
Customers and Churn Rate by Estimated Salary (Right Chart):
Salary 100K-200K: Largest segment 4K+ customers, churn ~20%
Salary 1K-10K: 100% churn rate - Low balance customers leaving
Salary >200K: Low count but moderate churn
Action: Focus on 100K-200K high value segment


🔍 Key Insights & Retention Strategy
Age Risk: Customers 51-60 have 55% churn - launch senior benefit program, personal RM
Credit Score Risk: Score <=400 = 100% churn - create secured card or counseling, not direct churn
Salary Risk: 1K-10K salary = 100% churn - low balance, need minimum balance waiver or micro-benefits
Geography: France 50.14% base but highest churn historically - region-specific offers
Product Risk: 96% customers hold only 1 product (Prod 1 or 2) - cross-sell Prod 3/4 to increase stickiness
Activity: 48.4% inactive - re-engagement campaign with cashback
Gender: Balanced, no bias - focus on behavior not gender

💡 Business Recommendations (What a Business Analyst Would Suggest)
Save $4M+: Reducing churn from 20.4% to 15% saves ~540 customers x avg lifetime value
Tiered Retention:
Tier 1 (Critical): Credit <400 & Salary 1K-10K & Age 51-60 = Immediate call
Tier 2 (High): France + Inactive + Single product = Email + offer
Tier 3 (Medium): 41-50 age = Loyalty points
Product Bundle: Offer Prod 1 + Prod 2 + Credit Card at discount to single-product holders
Proactive Alert: Build Power Automate flow - when credit score drops below 500, trigger RM call

🛠️ Tech Stack
Tools: Power BI, DAX (Churn Rate % measure), Power Query, Slicers (Churn Status)
Visuals: Donut Charts, Bar + Line Combo (Customers vs Churn Rate), Gauge, KPI Cards, Filters
Analysis: Cohort by Age, Credit Score binning, Salary segmentation, Country/Product mix
Domain: Banking, Customer Retention, Churn Analytics, Risk Management

📁 Dataset Details
Rows: 10,000 customers
Churned: 2,037 (20.4%)
Columns: Gender, Age, Geography (France/Germany/Spain), CreditScore, EstimatedSalary, HasCrCard, IsActiveMember, NumOfProducts, Exited (Churn)

👩‍💼 Author
Hemlata Sharma (Hema-Sharma11554) - Business Analyst Consultant
MBA Data Science & Business Analytics | SQL, Power BI, Excel, Microsoft Fabric, Python
Specializes in Churn Reduction, Sales Analytics, HR Analytics
Portfolio: https://hema-sharma11554.github.io/Portfolio-Hema-Sharma11554/
GitHub: https://github.com/Hema-Sharma11554

📌 Related Projects
Coffee Shop Sales - $698K
Ogul India Attrition - 19%
Clarte HR - 835 Employees
CRM Sales - 6,711 Opps

⭐ Star this repo! This is my most impactful churn project.
#BankChurn #PowerBI #ChurnAnalysis #CustomerRetention #BankingAnalytics #BusinessAnalyst #DataAnalytics
