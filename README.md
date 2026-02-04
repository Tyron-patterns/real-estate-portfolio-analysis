# 🌇 Real-estate-portfolio-analysis

## TL;DR
End-to-end analysis of a multi-unit residential real estate portfolio, originally tracked and explored in Excel, then validated with SQL and fully modeled in Power BI.
The report focuses on understanding long-term performance, cost and tax structure, occupancy dynamics, tenant behavior, and the impact of COVID, using exposure-aware and normalized metrics to avoid misleading comparisons and over-interpretation of short-term effects. 

**Privacy note**: All data used in this analysis have been anonymized and aggregated in accordance with basic data governance principles. No information allows for the identification of individual tenants or specific properties.

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

The report reflects a **real-world business scenario**, where not all variables are fully controllable and outcomes are influenced by external constraints (e.g. regulation, taxation, market conditions).

### Tasks & Analytical Structure

The dashboard is structured around a set of analytical tasks:

1. **Executive Overview** (Executive Summary Repository)  
High-level summary of portfolio performance (revenues, costs, profit, margins, occupancy, general trends over time).
2. **Revenues & Profit Growth Dynamics**
Exploratory and descriptive analysis of revenue and profit evolution over time, using complementary indicators (trend direction, end-to-start change, and volatility measures) to capture non-linear and uneven performance patterns rather than smooth growth.
3. **Occupancy, Vacancy vs Profitability by City and Unit**
Assessment of how occupancy and vacancy patterns relate to profit differences across units and locations, to support hypothesis that utilization alone does not fully explain profitability and highlight the role of structural and contextual factors.
4. **Average Occupancy/Vacancy vs Profitability by City and Unit**
Analysis of average occupancy and vacancy rates by city and unit, designed to smooth short-term and year-specific fluctuations, and to assess how structural utilization patterns relate to long-term profitability
5. **Tenancy Behavior & Turnover Effects**
Analysis of tenancy duration and tenant turnover at unit level, examining their association with profit and cost behavior and testing whether higher stability translates into improved economic performance.
6. **Expenses Structure**
Detailed examination of expense levels, variability, and efficiency in relation to revenues over time, explicitly accounting for operational drivers of cost pressure.
7. **Taxation Structure**
Parallel analysis focused on taxation, examining its impact as an external, non-controllable but structurally relevant cost driver.
8. **Early Termination & Payment Issues Analysis** 
Descriptive assessment of contract stability and payment irregularities across units and time using exposure-aware metrics.
9. **Tenant Segmentation – Profession**  & (8.1) **Segmentation Performances & Risks (Profession)**
Analysis of how tenant profession relates to occupancy, revenue contribution, stability and observed operational risk across units.
10. **Tenant Segmentation – Age**  & (9.1) **Segmentation Performances & Risks (Age)**
Descriptive segmentation of tenants by age group to examine differences in occupancy patterns, revenue contribution,stability and observed operational risk across units.
11. **Tenant Segmentation – Household Type**  & (10.1)**Segmentation Performances & Risks (Household Type)***
Descriptive segmentation of tenants by household type to examine differences in occupancy patterns, revenue contribution, stability and observed operational risk across units.
12. **COVID Impact Analysis**  
Comparison of revenues, occupancy, and taxation during COVID years (2020–2021) relative to a 2019 baseline.

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
