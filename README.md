# 🌇 Real-estate-portfolio-analysis

## TL;DR
End-to-end analysis of a multi-unit residential real estate portfolio, originally tracked and explored in Excel, then validated with SQL and fully modeled in Power BI.
The report focuses on understanding long-term performance, cost and tax structure, occupancy dynamics, tenant behavior, and the impact of COVID, using exposure-aware and normalized metrics to avoid misleading comparisons and over-interpretation of short-term effects. 

**Privacy note**: All data used in the analysis have been anonymized and aggregated in accordance with basic data governance principles. No information allows for the identification of individual tenants or specific properties.

## Project Scope

### Overview

This project is an **end-to-end data analysis of a multi-unit residential real estate portfolio**, developed to analyze long-term performance, operational behavior, and risk indicators using Excel, SQL, and Power BI.  

The dataset was initially collected and maintained in Excel, where early exploratory analysis was performed.
As the portfolio and analytical needs grew, the data was progressively validated and analyzed using SQL, and finally formalized, integrated, and modeled in Power BI to create a structured, scalable analytical dashboard.  

The analysis focuses on understanding how key performance metrics evolved over time and whether observed outcomes align with underlying operational and structural conditions.  

A supporting analytical report is being developed to document assumptions, methodology, limitations, and key insights.  

The analysis covers multiple aspects of the portfolio performance over a long time period, including:

- Revenue, costs, profit, and margins
- Growth indicators (YoY, CAGR, weighted rates)
- Expense and taxation structure
- Occupancy and vacancy dynamics
- Tenant behavior (tenancy duration, turnover, early terminations)
- Tenant segmentation (profession, age group, household type)
- Pre-COVID vs during-COVID performance comparison

### Tasks & Analytical Structure

The dashboard is structured around a set of analytical tasks:
## 📊 Analytical Structure & Dashboard Pages

The report is organized from high-level outcomes to constraints, operational behavior, risk drivers, and external shocks.

1. **Executive Overview**
   - Portfolio snapshot: revenues, costs, profit, margins, occupancy, and overall trends.

2. **Revenues & Profit Growth Dynamics**
   - Revenue/profit evolution over time using multiple indicators (non-linear patterns, volatility-aware).

3. **Expenses Structure (Operational Constraints)**
   - Expenses by unit and over time; variability and efficiency relative to revenues.

4. **Taxation Structure (Structural Constraints)**
   - Taxes by unit and over time; structural differences across locations and regimes.

5. **Occupancy & Vacancy vs Profitability**
   - How utilization patterns relate to profit differences across cities and units.

6. **Average Occupancy/Vacancy vs Profitability**
   - Long-run utilization using averaged metrics to smooth short-term fluctuations.

7. **Tenancy Behavior & Turnover Effects**
   - Tenancy duration and turnover patterns and their association with profit/cost behavior.

8. **Early Termination & Payment Issues**
   - Contract stability and payment irregularities using exposure-aware metrics.

9. **Tenant Segmentation – Profession** & (9.1) **Segmentation Performances & Risks (Profession)**
   - Profession-based segmentation: utilization, revenue contribution, stability, and risk signals.

10. **Tenant Segmentation – Age**  & (10.1)**Segmentation Performances & Risks (Age)***
    - Age-group segmentation: utilization patterns, revenue contribution, and stability.

11. **Tenant Segmentation – Household Type**  & (11.1)**Segmentation Performances & Risks (Household Type)***
    - Household segmentation: utilization patterns, revenue contribution, and operational risk.

12. **COVID Impact Analysis**
    - 2020–2021 comparison vs 2019 baseline for revenues, occupancy, and taxation.

### Executive Summary
A dedicated Executive Summary section is included to present the key outcomes of the analysis in a concise and decision-oriented format. It is designed to provide a clear overview of results and implications for a less technical audience.

### Methodology

- Data was initially compiled and explored in Excel
- Data quality checks, aggregations, and validation were performed using SQL
- Final data modeling, metric definitions, and visualization were implemented in Power BI
- Measures were designed to be context-aware and, where appropriate, normalized to avoid misleading comparisons
- Trends and relationships are evaluated visually and descriptively

### Tools & Technologies

- Excel – initial data collection and exploratory analysis
- SQL – data validation, aggregation, and consistency checks
- Power BI – data modeling, DAX measures, and dashboard development

### Current Status

- ✅ Dashboard completed

- 🚧 Written analytical report in progress

The written report will expand on:

### Metric definitions

- Normalization choices
- Analytical limitations
- Interpretation framework
- Key takeaways
