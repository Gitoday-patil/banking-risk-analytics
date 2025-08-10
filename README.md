# banking-risk-analytics
Interactive Power BI dashboard for banking risk analytics, providing insights on loans, deposits, and client engagement to support data-driven decision-making.

## 📌 Project Overview
This project focuses on **risk analytics in banking and financial services**, aiming to minimize the risk of losing money while lending to customers.  
It uses **Power BI** to visualize and analyze banking data, helping decision-makers approve or reject loan applications based on an applicant’s profile.

---

## 🎯 Problem Statement
Banks face the challenge of determining whether a loan applicant is likely to repay the loan.  
Our solution uses **interactive dashboards** to provide data-driven insights for better decision-making.

---

## 💡 Solution
- Created multiple Power BI dashboards using **the latest visualization tools**.
- Analyzed client profiles, deposits, loans, and account types.
- Used calculated columns, DAX functions, and KPIs for meaningful insights.
- Enabled **segmentation by income bands, engagement time, and loan types**.

---

## 📂 Dataset Information
The dataset contains multiple related tables linked via **primary and foreign keys**:
- **Banking Relationship**
- **Client-Banking**
- **Gender**
- **Investment Advisor**
- **Period**

---

## 🛠 Data Cleaning & Transformations
- Added **Engagement Timeframe** & **Engagement Days** columns.
- Created **Income Band** categories:  
  - Low: Income < 100,000  
  - Mid: Income < 300,000
- Calculated **Processing Fees** based on fee structure.

---

## 📐 Key DAX Calculations
- **SUM**: Total deposits, loans, and accounts.
- **DISTINCTCOUNT**: Unique clients.
- **SUMX**: Processing fee calculations.
- **DATEDIFF**: Engagement length in days.
- **SWITCH**: Conditional outputs.

---

## 📊 KPIs Included
- **Total Clients**  
- **Total Loan Amount**  
- **Bank Loan**  
- **Business Lending**  
- **Total Deposits**  
- **Processing Fees**  
- **Savings / Checking / Foreign Currency Accounts**  
- **Credit Card Balances**  
- **Engagement Length**

---

## 📈 Dashboards
1. **Home Dashboard**
2. **Loan Analysis**
3. **Deposit Analysis**
4. **Summary Dashboard**

---

## 📌 Results & Insights
- Private banks have the highest number of clients.
- Certain nationalities hold higher bank loans.
- Clear breakdown of amounts in different account types.
- Quick decision-making support for loan approvals.

---

## 🚀 Future Improvements
- Incorporate predictive analytics for loan default risk.
- Automate data refresh from live banking systems.
- Add customer segmentation for targeted marketing.

---

## 📷 Project Screenshots
*(Add screenshots of your Power BI dashboard here)*

---

## 📥 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/banking-dashboard.git
