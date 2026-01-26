
# 📈 Executive Summary 

## Scope of the analysis
The report is meant to analyze the performances of the portfolio (growth, occupancy, tenant segmentation, risk analysis, external shock resistance). The time window of the each category will change according to consideration related to the 

## Performance Summary
- A preliminary analysis on Revenues and profit portfolio shows and important growth in terms of these two indicators. This is not only a result of  rented over the years.  
- Simultenously, Costs show a mild but steady decrease over time, especially in early years where, which helped profit grow
- Occupancy normalized to the number of unit rented also risen (beyond the obivous incremeant in terms of more units rented)

## Revenues and Profit Drivers
Apparently there's no one single driver for profit, instead it's a combination of all the following effects that infleunce incomes:
- **Occupancy - Vacancy (Occupancy-Adjusted Profit)**:
 - **City level**: lower occuapancy volumes comes along with lower profit, with Fiumicino showing worst performances than Rome, same goes for vacancy. 
 - **Unit level**: here too, higher occupancy voleumes correspond to higher profit, with FCO Su leading the trend as the highest occupancy-profit unit, while units  
                   with comparable occupancy volumes are in the same range of profit, regardless of rental prices  
- **Turnovers*: 
 - ** City level**: lower number of turnovers for city (with Rome presenting a much bigger number than Fiumicino) tranlsate to lower profit.
 - ** Unit level**: what just said for the city doesn't apply here, where more stable unit either come with higher (FCO Su) or similar profit regardless of 
                    stability 
This changes as we analyze the profit at a **unit level**, where unit associated with **higher occupancy volumes** are also **more profitable**.
This might be explained by looking at taxation burden which is higher (both at a city level and at unit level) for Fiumicino Units who are also affected by additional
taxes (IMU). 
- A higher **Turnovers Volume** seems to not affect profit at a city level, while at a unit level longer and more stable tenancy align with **higer profits**

- Expenses are not an indicator for profit at a city level as they are practically the same in both cities. at a uni

### NOTE: normalization of rental price for number of unit in a city is not needed as the total profit for all units in different cities is comparable # 🌇 Real-estate-portfolio-analysis

## TL;DR
End-to-end analysis of a real residential real estate portfolio, originally tracked and explored in Excel, then validated with SQL and fully modeled in Power BI.
The project focuses on understanding long-term performance, occupancy dynamics, tenant behavior, cost and tax structure, and the impact of COVID, using descriptive and exposure-aware metrics rather than causal claims.
Project Scope


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

1. **Executive Overview**  
High-level summary of portfolio performance (revenues, costs, profit, margins, occupancy).
2. **Revenues & Profit Growth analysis**  
Overview of revenue and profit evolution using multiple growth indicators to reflect non-linear and uneven performance over time.
3. **Occupation vs Profitability by City & Unit**  
Assessment of how occupancy levels relate to profit distribution across units, including occupancy-adjusted profit.
4. **Tenancy Behavior Analysis**  
Exploration of average tenancy duration, tenant turnover, and their relationship with profit and costs.
5. **Expenses, Taxation & Cost Structure**  
Analysis of expenses and taxes by unit and over time, acknowledging external (non-controllable) drivers.
6. **Early Termination & Payment Issues Analysis** 
Descriptive assessment of contract stability and payment irregularities across units and time using exposure-aware metrics.
7. **Tenant Segmentation – Profession**  
Analysis of how tenant profession relates to occupancy, revenue contribution, and observed operational risk across units.
8. **Tenant Segmentation – Age & Household**  
Descriptive segmentation of tenants by age group and household type to examine differences in occupancy patterns, revenue contribution, and stability.
9. **COVID Impact Analysis**  
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
- Key takeaways without overclaiming causality

## Notes

This project was built both as:

- A professional portfolio project for data/BI roles
- A realistic analytical case study, reflecting the ambiguity and constraints of real operational data
