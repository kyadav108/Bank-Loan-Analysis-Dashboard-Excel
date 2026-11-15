# 🏦 Bank Loan Analysis Dashboard | Excel

An Excel analytics project that turns **38,576 loan records (2021)** into KPI dashboards for tracking loan performance and credit risk.

## 🎯 Objective
Help a lending team see how much is being lent, how much is coming back, how it changes month to month, and where the risk is.

## 📂 Dataset
- **38,576 loans**, issued Jan–Dec 2021, across 50 US states and DC
- Fields cover borrower details, loan terms (amount, term, grade, purpose, interest rate, DTI) and repayment status

## 🗂 Workbook Sheets
| Sheet | Purpose |
|---|---|
| `Financial loan data` | Cleaned dataset (Excel Table) with a derived **Good Vs Bad Loan** column |
| `loan API` | 15 PivotTables and PivotCharts behind every KPI |
| `Summry Dashbord` | Headline KPIs, MTD / MoM, Good vs Bad loan analysis |
| `Overview Dashbord` | Trends by month, state, term, employment length, purpose, home ownership |

## 🛠 What I Did
1. Cleaned and structured the data as an Excel Table
2. Created `Good Vs Bad Loan`: *Fully Paid / Current* = Good, *Charged Off* = Bad
3. Built PivotTables and `GETPIVOTDATA` KPI cards (MTD, MoM)
4. Designed two dashboards with PivotCharts and **Grade / Purpose slicers**

## 📏 Key KPIs
| KPI | Value |
|---|---|
| Loan Applications | 38,576 |
| Funded Amount | $435.76M |
| Amount Received | $473.07M |
| Avg Interest Rate | 12.05% |
| Avg DTI | 13.33% |
| Good / Bad Loans | 86.18% / 13.82% |

## 🔍 Key Insights
- Monthly applications grew **85%** (2,332 in Jan to 4,314 in Dec)
- Bad loans were funded **$65.5M** but only **$37.3M** has been recovered
- Bad-loan rate rises from **5.7% (Grade A)** to about **31% (Grades F–G)**
- **60-month** loans default at **22.3%** vs **10.7%** for 36-month loans
- **Debt consolidation** is the top purpose (47% of applications); California leads by state

## 📸 Dashboards
![Summary](images/summary_dashboard.png)
![Overview](images/overview_dashboard.png)

## 🧰 Skills
`Excel` · `Data Cleaning` · `PivotTables` · `PivotCharts` · `Slicers` · `KPI Design` · `Dashboard Design` · `Credit-Risk Analytics`
