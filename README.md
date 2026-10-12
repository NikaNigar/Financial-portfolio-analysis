# Financial-portfolio-analysis
End-to-end financial portfolio analysis using SQL Server, Power Query, and Power BI. An interactive 3-page dashboard analyzing portfolio risk, overdue payments, PAR30/PAR90, collections, and partner performance using synthetic data.
# Financial Portfolio Analysis | SQL Server, Power Query & Power BI

## Project Overview

This project focuses on analyzing a financial portfolio to evaluate portfolio performance, identify credit risk indicators, monitor collection efficiency, and compare partner performance.

The project demonstrates an end-to-end data analytics workflow, from data querying and cleaning to KPI development and interactive dashboard design, using **SQL Server, Power Query, and Power BI**.

The dashboard consists of three interactive report pages designed to support data-driven business analysis and decision-making.

**Note:** This is a portfolio project created for educational and demonstration purposes using synthetic data. No real company or customer data was used.

## Business Objectives

The main objectives of this project are to:

- Monitor the overall financial portfolio and outstanding balances.
- Identify overdue contracts and assess portfolio risk.
- Calculate and analyze PAR30 and PAR90 indicators.
- Evaluate monthly financing and collection performance.
- Identify partners with higher overdue payment levels.
- Explore first payment default (FPD30) trends across campaign months.
- Present key performance indicators through an interactive Power BI dashboard.

## Tools & Technologies

- **SQL Server** — Data querying, joins, aggregations, CTEs, window functions, and financial KPI calculations.
- **Power Query** — Data cleaning, duplicate removal, data standardization, and transformation.
- **Power BI** — Interactive dashboard development, data modeling, DAX measures, and data visualization.
- **DAX** — KPI calculations, portfolio metrics, collection rates, and risk indicators.

## Project Workflow

### 1. Data Extraction & Analysis — SQL Server

SQL Server was used to query and prepare data for portfolio analysis.

Key techniques included:

- JOIN operations to combine related datasets.
- Common Table Expressions (CTEs) to structure complex queries.
- GROUP BY and aggregate functions for financial summaries.
- Window functions for analytical calculations.
- Date functions for monthly reporting and overdue analysis.
- Conditional logic to calculate outstanding balances and delinquency indicators.

Key metrics analyzed:

- Total financing amount.
- Outstanding portfolio balance.
- Number of contracts.
- Days Past Due (DPD).
- Portfolio at Risk 30 days (PAR30).
- Portfolio at Risk 90 days (PAR90).
- Collection rate.
- First Payment Default 30 days (FPD30).

### 2. Data Cleaning & Transformation — Power Query

Power Query was used to improve data consistency and prepare the data for reporting.

Key activities included:

- Removing duplicate records where appropriate.
- Correcting inconsistent and misspelled categorical values.
- Standardizing date and phone number formats.
- Handling missing and inconsistent values.
- Preparing data for analysis and visualization.

### 3. Dashboard Development — Power BI

An interactive three-page dashboard was developed to present portfolio performance, collection efficiency, and credit risk indicators.

**Page 1 — Portfolio Overview**

- Total outstanding portfolio balance.
- Number of active contracts.
- PAR30 and PAR90 indicators.
- Portfolio status and overdue balance distribution.

**Page 2 — Financing & Collections**

- Monthly financing trends.
- Monthly collection performance.
- Expected versus collected payments.
- Collection rate analysis.

**Page 3 — Risk & Partner Performance**

- Portfolio risk indicators by partner.
- Overdue balances and delinquency analysis.
- PAR30 and PAR90 comparisons.
- FPD30 trends across campaign months.

The dashboard uses interactive filters and visualizations to explore the data from different perspectives.

## Key Findings

The following findings were observed in the synthetic dataset used for this project:

- **Portfolio Risk:** PAR30 reached 15.1%, exceeding the illustrative 10% target used in the project.
- **First Payment Default:** FPD30 reached approximately 15–19% in certain campaign months, highlighting periods that warrant further investigation.
- **Partner Performance:** Some partners showed higher overdue payment indicators, suggesting opportunities for deeper risk analysis.
- **Collection Efficiency:** The September collection rate was 82%, providing a basis for further investigation of payment collection performance.

These findings are specific to the synthetic dataset and should not be interpreted as results from a real financial institution.

## Business Value

This project demonstrates how data analytics can help transform raw financial data into actionable insights.

The analysis can support:

- Portfolio monitoring and risk assessment.
- Identification of potential collection issues.
- Comparison of partner performance.
- Investigation of payment default patterns.
- Data-driven discussions about portfolio quality and collection processes.

The results highlight the importance of combining data preparation, SQL analysis, and interactive reporting to support business decisions.

## Skills Demonstrated

- SQL querying and data aggregation.
- Data cleaning and transformation.
- Financial KPI development.
- DAX measure creation.
- Power BI dashboard design.
- Credit risk and collection analysis.
- Business-oriented data interpretation.
- Data storytelling and visualization.

## Repository Structure

```text
financial-portfolio-analysis/
│
├── SQL/
│   └── portfolio_analysis.sql
│
├── PowerBI/
│   └── financial_portfolio_dashboard.pbix
│
├── Screenshots/
│   ├── portfolio_overview.png
│   ├── financing_collections.png
│   └── risk_partner_performance.png
│
└── README.md
```

*The structure above is a suggested repository layout. Include only the folders and files that are actually available in your repository.*

## Conclusion

This project represents a practical application of SQL Server, Power Query, and Power BI in financial portfolio analysis.

By combining data transformation, analytical SQL queries, KPI calculations, and interactive visualizations, the project demonstrates an end-to-end approach to turning raw data into meaningful business insights.

I continue to develop my data analytics skills through practical projects focused on business intelligence, financial analysis, and data-driven decision-making.
