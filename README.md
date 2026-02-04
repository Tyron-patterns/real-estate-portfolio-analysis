# 🌇 Real-estate-portfolio-analysis

## TL;DR
End-to-end analysis of a real residential real estate portfolio, originally tracked and explored in Excel, then validated with SQL and fully modeled in Power BI.
The project focuses on understanding long-term performance, occupancy dynamics, tenant behavior, cost and tax structure, and the impact of COVID, using descriptive and exposure-aware metrics rather than causal claims. 

**Privacy note**: All data used in this analysis have been anonymized and aggregated in accordance with basic data governance principles. No information allows for the identification of individual tenants or specific properties.
**Note**: The dashboards included in this repository differ in style as the entire report has been restyled to make the project clearer. At the moment, following some technical issues, only a part of the dahsboards from this most recent version were available for upload. Nonetheless, the list of the pages is updated to the newest version

## Project Scope

### Overview

This project is an **end-to-end data analysis of a multi-unit residential real estate portfolio**, developed to analyze long-term performance, operational behavior, and risk indicators using Excel, SQL, and Power BI.

The dataset was initially collected and maintained in Excel, where early exploratory analysis was performed.
As the portfolio and analytical needs grew, the data was progressively validated and analyzed using SQL, and finally formalized, integrated, and modeled in Power BI to create a structured, scalable analytical dashboard.

The goal of the project is descriptive and evaluative, not prescriptive:
it focuses on understanding how key metrics evolved over time and whether observed outcomes are consistent with business decisions, rather than claiming causal optimization.

A written analytical report is currently being built to formally document assumptions, methodology, limitations, and insights derived from the dashboard.
The analysis covers multiple dimensions of portfolio performance over a long time horizon, including:

- Revenue, costs, profit, and margins
- Occupancy and vacancy dynamics
- Growth indicators (YoY, CAGR, weighted rates)
- Tenant behavior (tenancy duration, turnover, early terminations)
- Tenant segmentation (profession, age group, household type)
- Expense and taxation structure
- Pre-COVID vs during-COVID performance comparison

The project reflects a **real-world business scenario**, where not all variables are fully controllable and outcomes are influenced by external constraints (e.g. regulation, taxation, market conditions).

### Tasks & Analytical Structure

The dashboard is structured around a set of analytical tasks:

1. **Executive Overview** (Executive Summary Repository)  
High-level summary of portfolio performance (revenues, costs, profit, margins, occupancy).
2. **Revenues & Profit Growth Dynamics**
Exploratory and descriptive analysis of revenue and profit evolution over time, using complementary indicators (trend direction, end-to-start change, and volatility measures) to capture non-linear and uneven performance patterns rather than assuming smooth growth.
3. **Occupancy, Vacancy & Profitability by City and Unit**
Assessment of how occupancy and vacancy patterns relate to profit differences across units and locations, showing that utilization alone does not fully explain profitability and highlighting the role of structural and contextual factors.
4. **Occupancy/Vacancy Average & Profitability by City and Unit**
Similar To the previous point but applied on Occupancy/Vacancy Averages to 
5. **Tenancy Behavior & Turnover Effects**
Analysis of tenancy duration and tenant turnover at unit level, examining their association with profit and cost behavior and testing whether higher stability translates into improved economic performance.
6. **Expenses, Taxation & Cost Structure**
Detailed examination of expenses and taxation separately, analyzing their levels, variability, and efficiency relative to revenues over time, while explicitly accounting for structural and external (non-controllable) drivers of cost pressure.
7. **Early Termination & Payment Issues Analysis** 
Descriptive assessment of contract stability and payment irregularities across units and time using exposure-aware metrics.
8. **Tenant Segmentation – Profession**  & (8.1) **Segmentation Performances (Profession)**
Analysis of how tenant profession relates to occupancy, revenue contribution, and observed operational risk across units.
9. **Tenant Segmentation – Age**  & (9.1) **Segmentation Performances (Age)**
Descriptive segmentation of tenants by age group to examine differences in occupancy patterns, revenue contribution, and stability.
10. **Tenant Segmentation – Household Type**  & (10.1)**Segmentation Performances (Household Type)***
Descriptive segmentation of tenants by household type to examine differences in occupancy patterns, revenue contribution, and stability.
11. **COVID Impact Analysis**  
Comparison of revenues, occupancy, and taxation during COVID years (2020–2021) relative to a 2019 baseline.

Additional exploratory pages were included to investigate tenant segmentation and risk-related indicators (early terminations, payment delays).

### Methodology

- Data was initially compiled and explored in Excel
- Data quality checks, aggregations, and validation were performed using SQL
- Final data modeling, metric definitions, and visualization were implemented in Power BI
- Measures were designed to be context-aware and, where appropriate, normalized to avoid misleading comparisons
- Trends and relationships are evaluated visually and descriptively

No causal claims are made unless explicitly supported by the data

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

## Notes

This project was built both as:

- A professional portfolio project for data/BI roles
- A realistic analytical case study, reflecting the ambiguity and constraints of real operational data
