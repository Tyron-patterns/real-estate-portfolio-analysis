
# 📈 Executive Summary 

## Scope of the analysis
The report is meant to analyze the performances of the portfolio (growth, occupancy, tenant segmentation, risk analysis, external shock resistance). The time window of the each category will change according to consideration related to the 

## Performance Summary
- A preliminary analysis on Revenues and profit portfolio showed an important growth over the entire timespan of the business.
- Simultenously, Costs showed a mild but steady decrease over time, especially if compared to early years where, which helped profit grow
- Occupancy normalized to the number of unit rented also risen (beyond the obivous incremeant in terms of more units rented)

## 1. Where does profit actually come from in the portfolio?

Portfolio profitability is driven by a combination of occupancy, tenancy stability, and structural constraints, rather than by a single dominant factor.  

**Occupancy is the strongest and most consistent driver of profit across both cities and individual units**.
Matrix-level comparisons (10. Metrics Comparison) show that higher occupancy periods align with higher profit. At city level, Rome outperforms Fiumicino primarily due to higher utilization, while at unit level, properties with comparable occupancy volumes generate similar profit levels regardless of rental prices.

**Vacancy directly erodes profitability**, particularly at city level.
Units and locations with higher vacant months contribute disproportionately less to total profit, confirming utilization as a critical performance lever.

**Tenant turnover has a differentiated impact by scale**.
At city level, higher turnover does not translate into improved profitability, indicating that volume of tenancy changes alone is not a positive driver. At unit level, however, more stable units are associated with either higher or comparable profit outcomes, suggesting that tenancy stability matters primarily at the asset level rather than in aggregate.

**Cost and tax structures act as constraining factors rather than primary drivers**.
Matrix comparisons indicate similar expense costs across cities, while differences in tax burden materially affect net profitability, particularly for Fiumicino units, as these have an additional taxation burden represente by IMU for second houses. These structural effects help explain profit discrepancies once occupancy is normalized.

## 2. Which units / locations are reliable vs volatile profit generators?

Despite turnovers being a possible cause for tenancy disruptions and gaps in occupancy, **average vacancy length has proven to be the most conspicuous source of volatility**, as in most cases tenant alternations were not followed by prolonged vacancies.

In fact, while Rome has experienced a much higher volume of turnovers than Fiumicino, **it is a unit in the latter location (FCO Giu) that exhibits the most unstable reliability pattern**. This is evidenced by an unusually long average vacancy duration when compared to all other units in the portfolio. Moreover, this unit has also shown **a concerning record of payment issues**, including both delayed and fully missed payments.

On the other hand, **FCO Su appears to be the most stable unit across the entire portfolio**, with only one tenant (no turnovers and no vacancy) throughout the observed period. This classification is not practically affected by the presence of a limited number of payment issues, as these occurrences are not structural, resolved in later payments and significantly fewer than those observed for FCO Giu; as such, they can be considered as effectively absorbed by the long tenancy duration.

As mentioned, **Rome units experienced a higher turnover volume, yet vacancy durations remained short** (both in absolute terms and relative to a full year and to FCO Su) and more homogeneous across units despite frequent tenant changes. No payment issues were recorded, **making these units—second only to FCO Su—a relatively stable source of income**.

### Note:
A more in-depth analysis of missing and delayed payments and their associated risks was conducted using tenant segmentation.

## 3. What structurally limits profitability (costs, taxes, vacancy)?  

As mentioned in the previous two points, vacancy is one of the most prominent factors
as it might seems obious, revenues can also impact profit, as klower revenues, a parita' di costi , can deflate profits. this is the case of small increments of rental prices whcih contributed to profit growth overtime
# 🌇 Real-estate-portfolio-analysis

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
