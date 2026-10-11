# Bank Transaction Descriptive Analytics Report
A descriptive analytics report on daily bank transaction data — built on a synthetic dataset
modeled to mirror real retail-banking transaction patterns, since a real bank's core-banking
feed isn't publicly accessible.

## Dataset
- 60 branches × 10 transaction types × 8 regions
- 30 days (2026-07-16 to 2026-08-14)
- ~4.90 million simulated transactions, ~INR 4,809 Cr gross value

## What's inside
- **KPI Snapshot** — headline metrics (volume, value, ATV, success rate, cash risk)
- **Top transaction types & value performance** — value vs. volume leaders
- **Weekly volume trends & value trajectory**
- **Average transaction value distribution**
- **Channel tier allocation** (Branch/POS, Mobile App, Internet Banking, ATM)
- **Customer segment share** (Retail, Corporate, SME, Premium)
- **Regional & macro-regional demand distribution**
- **Cross-cutting synthesis** — region × transaction-type revenue concentration
- **Settlement network / payment rail preferences**
- **Transaction success rate & reliability analysis**
- **Cash / liquidity status & stockout risk**
- **Volume, value & risk elasticity (correlation) analysis**
- **Data limitations, references, appendix & glossary**

## Tools used
Python (Pandas, NumPy) for data aggregation, Matplotlib for charts, ReportLab for PDF generation.



# IBM Cognos Analytics – RetailPulse Practicals
A set of six hands-on practicals in **IBM Cognos Analytics (Reporting & Dashboards)**, built around a fictional retail company, *RetailPulse*. They cover the full path from a first list report to an interactive customer dashboard.

## Practicals
| # | Practical | Topic |
|---|-----------|-------|
| 1 | [Generate a First RetailPulse Report](Practical_1_First_Report.pdf) | Intro to Cognos Reporting, running list report |
| 2 | [Build a Grouped Sales List Report](Practical_2_Grouped_List_Report.pdf) | Grouping, currency formatting, footer totals, page header |
| 3 | [Filter Sales by Region and Date](Practical_3_Filters.pdf) | Simple and advanced detail filters, prompted filter |
| 4 | [Region × Product Crosstab](Practical_4_Region_Product_Crosstab.pdf) | Crosstab, multiple measures, summary totals |
| 5 | [Sales Prompt Report](Practical_5_Prompt_Report.pdf) | Value, date-range and cascading prompts |
| 6 | [Customer Insights Dashboard](Practical_6_Customer_Insights_Dashboard.pdf) | KPI card, line chart, bar chart, cross-filtering |

Each PDF contains the objective, materials required, step-by-step procedure, an illustrative output, and the expected outcome.

## Tools & Data
- IBM Cognos Analytics
- RetailPulse Sales package (Practicals 1–5)
- RetailPulse Customers data module (Practical 6)

## Note
The output screens in the PDFs are illustrative mock-ups using sample figures, not live RetailPulse data.

## Skills Demonstrated
List and crosstab reports · grouping & aggregation · filters · prompt pages & cascading prompts · dashboard design and cross-filtering


# RetailPulse Power BI Practicals
Lab work for **Business Analytics - IBM Cognos Analytics Unit**, covering Units 3 and 4 of the lab manual. All four practicals use the same fictional **RetailPulse** retail dataset (Sales, Product and Store tables) and build on one another: each practical continues from the `.pbix` file produced in the previous one.

## Contents
| # | Practical | Report | Unit |
|---|-----------|--------|------|
| 7 | Import and Transform RetailPulse Data in Power BI | [Practical_7_Import_Transform_RetailPulse.pdf](Practical_7_Import_Transform_RetailPulse.pdf) | 3 |
| 8 | Model, Calculate, and Publish a RetailPulse Sales Report | [Practical_8_Model_Calculate_Publish_RetailPulse.pdf](Practical_8_Model_Calculate_Publish_RetailPulse.pdf) | 3 |
| 9 | Time Intelligence and Advanced DAX for RetailPulse | [Practical_9_Time_Intelligence_DAX_RetailPulse.pdf](Practical_9_Time_Intelligence_DAX_RetailPulse.pdf) | 4 |
| 10 | Interactive Dashboard, Row-Level Security, and Power Platform Integration | [Practical_10_Dashboard_RLS_PowerPlatform_RetailPulse.pdf](Practical_10_Dashboard_RLS_PowerPlatform_RetailPulse.pdf) | 4 |

## Tools used
- Power BI Desktop and Power BI service
- Power Query (M) and DAX
- Power Automate and Power Apps (Practical 10)
- Dataset: `RetailPulse_Sales.xlsx` (Sales, Product, Store)

## Notes
- Figures and sample values in the PDFs are based on a sample RetailPulse dataset (Jan 2024 - Dec 2025). Results will differ slightly with a different workbook.
- Practical 10 Steps 4-6 require a Power BI Pro/Premium Per User licence and a work or school account.
