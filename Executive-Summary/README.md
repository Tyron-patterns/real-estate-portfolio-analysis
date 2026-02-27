# 📈 Executive Summary 
**The analaysis was conducted both at city/location and unit level to differentiate effects between said categories.**
<p align="center">
  <img width="612" height="347" alt="Screenshot 2026-02-27 at 15 09 12" src="https://github.com/user-attachments/assets/d1346ddf-79f9-47b0-bfc8-0064ccb244dc" width="900">
</p>

- **Portfolio profitability is driven by a combination of occupancy, tenancy stability,
 and structural constraints, rather than by a single dominant factor.** 

[KPI Comparison Matrix](https://github.com/Tyron-patterns/real-estate-portfolio-analysis/blob/main/Executive-Summary/Comparison%20Matrix.png)



## 1. Where does profit actually come from in the portfolio?

**Portfolio profitability is driven by a combination of occupancy, tenancy stability,
 and structural constraints, rather than by a single dominant factor.**    

- **Occupancy/Vacancy are the strongest and most consistent drivers of profit across both cities and individual units**.  
Matrix-level comparisons show that higher occupancy periods align with higher profit. At city level, Rome outperforms Fiumicino primarily due to higher utilization, while at unit level, properties with comparable occupancy volumes generate similar profit regardless of rental prices.

- **Tenant turnover has a differentiated impact by scale**.  
At city level, higher turnover does not translate into improved profitability, indicating that changes in volume of tenancy alone are not a positive driver. At unit level, however, more stable units are associated with either higher or comparable profit outcomes, suggesting that tenancy stability matters primarily at this level rather than in aggregate.

- **Cost and tax structures act as constraining factors rather than primary drivers**.  
Matrix comparisons indicate similar expense costs across cities, while differences in tax burden materially affect net profitability, particularly for Fiumicino units, as these have an additional taxation burden represented by IMU for second houses. These structural effects help explain discrepancies once profits are normalized over occupancy.

#### Dashboard Reference:
[Revenues & Profit Growth Dynamics](https://github.com/Tyron-patterns/real-estate-portfolio-analysis/blob/main/Dashboards/02_Revenues%20%26%20Profit%20Growth%20Dynamics.png)  
[Occupancy & Vacancy vs Profitability](https://github.com/Tyron-patterns/real-estate-portfolio-analysis/blob/main/Dashboards/05_Occupancy%20%26%20Vacancy%20vs%20Profitability.png)  
[Average Occupancy & Vacancy vs Profitability](https://github.com/Tyron-patterns/real-estate-portfolio-analysis/blob/main/Dashboards/06_Average%20Occupancy%20%26%20Vacancy%20vs%20Profitability.png)  
[Expenses Structure (Operation Constraints)](https://github.com/Tyron-patterns/real-estate-portfolio-analysis/blob/main/Dashboards/03_Expenses%20Structure%20(Operation%20Constraints).png)  
[Taxation Structure (Structural Constraints)](https://github.com/Tyron-patterns/real-estate-portfolio-analysis/blob/main/Dashboards/04_Taxation%20Structure%20(Structural%20Constraints).png)


## 2. Which units / locations are reliable vs volatile profit generators?

**Average vacancy length has proven to be the most conspicuous source of volatility. In fact, while turnovers pose a possible cause for gaps in occupancy, in most cases tenant alternations were not followed by prolonged vacancies.**

- **FCO Giu exhibits the most unstable reliability pattern**  
despite Fiumicino location showing a low turnover volume. This is evidenced by an unusually long average vacancy duration when compared to all other units in the portfolio. Moreover, this unit has also shown **a concerning record of payment issues**, including both delayed and fully missed payments.

- **FCO Su appears to be the most stable unit across the entire portfolio**  
With only one tenant (no turnovers and no vacancy) throughout the observed period. This classification is not practically affected by the presence of a limited number of payment issues, as these occurrences are not structural, resolved in later payments and significantly fewer than those observed for FCO Giu (they can be considered absorbed by the long tenancy duration).

- **Rome units experienced a higher turnover volume, yet vacancy durations remained short**  
(both in absolute terms and relative to FCO Su) and more homogeneous across units despite frequent tenant changes. No payment issues were recorded, **making these units—second only to FCO Su in reliability**

### Note:
A more in-depth analysis of missing and delayed payments and their associated risks was conducted using tenant segmentation.

#### Dashboard Reference:
[Occupancy & Vacancy vs Profitability](https://github.com/Tyron-patterns/real-estate-portfolio-analysis/blob/main/Dashboards/05_Occupancy%20%26%20Vacancy%20vs%20Profitability.png)  
[Average Occupancy & Vacancy vs Profitability](https://github.com/Tyron-patterns/real-estate-portfolio-analysis/blob/main/Dashboards/06_Average%20Occupancy%20%26%20Vacancy%20vs%20Profitability.png)  
[Tenancy Behaviors & Turnovers Dynamics](https://github.com/Tyron-patterns/real-estate-portfolio-analysis/blob/main/Dashboards/07_Tenancy%20Beahaviors%20%26%20Turnovers%20Dynamics.png)  
[Early Terminations & Payment Issues Analysis](https://github.com/Tyron-patterns/real-estate-portfolio-analysis/blob/main/Dashboards/08_Early%20Terminations%20%26%20Payment%20Issues%20Analysis.png)

## 3. What structurally limits profitability?  

- **Vacancy is one of the most prominent structural factors affecting profitability**  
as the equation **vacancy = no profits** remains true and represents a major constraint on profit generation.

- **Revenues, in the form of rental prices, can partially be considered as a structural impact on profitability**  
This effect is particularly evident under Canone Concordato contracts, where prices are set by regulation based on property characteristics and amenities. In this context, small improvements and targeted investments contributed to part of the profit growth observed over time by allowing for modest increases in the maximum applicable rental prices.

- **Taxes, although largely externally determined, represent another important and unavoidable structural cap on profitability**.  
The data show that informed choices regarding taxation regimes can improve profitability, as observed after 2014. Conversely, higher tax burdens (Fiumicino units) help explain the margin differences observed between locations with comparable rental prices.
It is also worth noting that taxation is proportional to occupancy, reinforcing its role as an unavoidable constraint on profitability

#### Dashboard Reference:
[Expenses Structure (Operation Constraints)](https://github.com/Tyron-patterns/real-estate-portfolio-analysis/blob/main/Dashboards/03_Expenses%20Structure%20(Operation%20Constraints).png)  
[Taxation Structure (Structural Constraints)](https://github.com/Tyron-patterns/real-estate-portfolio-analysis/blob/main/Dashboards/04_Taxation%20Structure%20(Structural%20Constraints).png)  
[Occupancy & Vacancy vs Profitability](https://github.com/Tyron-patterns/real-estate-portfolio-analysis/blob/main/Dashboards/05_Occupancy%20%26%20Vacancy%20vs%20Profitability.png)  


## 4. What operational risks exist?

- **Expenses, such as maintenance and repair costs, are not structural but largely stochastic** (no periodic manteinance).  
Investment peaks observed at the start of the business confirm that expenses are, to a certain extent (unexpected accidents), controllable and containable, even if no property is fully immune from incidents

- **Tenants profiles are for sure an important operational risks**  
as shown by both FCO Su and FCO Giu, were there have been many instances of payments issues. Proper tenant profiling is therefore vital and, as data suggests, certain categories, which are associated primarily with Fiumicino's units, require some deeper attention. For example, increased awareness of higher-risk situation has allowed to implement targeted strategies (such as insurance against missed payments and structural damage, alongside legal assistance) to protect vulnerable units.
In any case, said measures should not be used blindly, as they come at a cost. It's therefore recomendable to protect only units that are more at risk, so not to encour in avoidable costs

- **Turnovers are intrinsically risky as they might come with vacancy periods**  
together with the fact new tenants per se require background assesment, which is expensive both in money and time and can introduce risks of payment issues. 

#### Dashboard Reference:
[Tenancy Behaviors & Turnovers Dynamics](https://github.com/Tyron-patterns/real-estate-portfolio-analysis/blob/main/Dashboards/07_Tenancy%20Beahaviors%20%26%20Turnovers%20Dynamics.png)  
[Early Terminations & Payment Issues Analysis](https://github.com/Tyron-patterns/real-estate-portfolio-analysis/blob/main/Dashboards/08_Early%20Terminations%20%26%20Payment%20Issues%20Analysis.png)  
[Tenant Segmentation - Profession](https://github.com/Tyron-patterns/real-estate-portfolio-analysis/blob/main/Dashboards/09_Tenant%20Segmentation%20-%20Profession.png)  
[Segmentation Performances & Risks - Profession](https://github.com/Tyron-patterns/real-estate-portfolio-analysis/blob/main/Dashboards/10_Segmentation%20Performances%20%26%20Risks%20-%20Profession.png)  
[Tenant Segmentation - Age](https://github.com/Tyron-patterns/real-estate-portfolio-analysis/blob/main/Dashboards/11_Tenant%20Segmentation%20-%20Age.png)  
[Segmentation Performances & Risks - Age](https://github.com/Tyron-patterns/real-estate-portfolio-analysis/blob/main/Dashboards/12_Segmentation%20Performances%20%26%20Risks%20-%20Age.png)  
[Tenant Segmentation - Household Type](https://github.com/Tyron-patterns/real-estate-portfolio-analysis/blob/main/Dashboards/13_Tenant%20Segmentation%20-%20Household%20Type.png)  
[Segmentation Performances & Risks - Household Type](https://github.com/Tyron-patterns/real-estate-portfolio-analysis/blob/main/Dashboards/14_Segmentation%20Performances%20%26%20Risks%20-%20Household%20Type.png)


## 5. How resilient is the portfolio to external shocks (COVID)?

**Analysis on the COVID period, segmented into wave 1 (2020) and wave 2 (2021) for comparison purposes, shows that flexibility in rental prices was associated with a moderate reduction in occupancy**  

- **Throughout wave 1, rental reduction measures were adopted to avoid vanacy.**
In this period, following a careful assessment of tenant profiles, temporary reductions were offered to more sensitive segments. This approach seems to have helped maintain occupancy, as well as tenant satifasfaction, at levels comparable to pre-COVID years (2019), while losses remained moderate relative to the same year.

- **Wave 2 was characterized by longer vacancy durations**  
as companies and universities increasingly adopted remote solutions, leading to a structural decline in demand for tenancies. This shift had a negative impact on profitability.

- **Overall, the data indicate that the business absorbed the shock of reduced demand, including during wave 2**  
This is probably associated with the presence of longer tenancies and tenant screening, which contributed to a more robust and resilient income base.

#### Dashboard Reference:
[COVID Impact Analysis](https://github.com/Tyron-patterns/real-estate-portfolio-analysis/blob/main/Dashboards/15_COVID%20Impact%20Analysis.png)

## 6. What trade-offs cannot be optimized simultaneously?

- **Rental prices and taxes are structurally proportional, since higher rents translate into a higher taxable base**  
As a result, there is no realistic scenario where rental prices increase while taxes decrease (excluding very specific or temporary situations). This creates a hard ceiling on how much additional revenue can be converted into profit, making it impossible to optimize both dimensions independently.

- **Investments made at the start of the business (renovations, improvements, adjustments) are often necessary to achieve higher occupancy and better tenant retention over time**  
even if they tend to reduce short-term profitability. Lower initial expenses may preserve early profits, but typically at the cost of weaker occupancy performance and lower long-term stability.

- **During COVID period, trade-offs emerged between maintaining occupancy and preserving short-term profit**  
Rental price reductions helped keep occupancy levels relatively high, but necessarily compressed margins. Conversely, prioritizing profit would have implied accepting higher vacancy and turnover. Both objectives could not be fully optimized at the same time under external demand shocks.

### Note: Reference Comparison Matrix
A compact comparison matrix is included as a numerical reference to support the conclusions presented above.
The matrix provides a side-by-side view of selected key metrics by city and unit — specifically those that do not require further visual or exploratory analysis — allowing quick verification of relative performance.

#### Dashboard Referece:
[Revenues & Profit Growth Dynamics](https://github.com/Tyron-patterns/real-estate-portfolio-analysis/blob/main/Dashboards/02_Revenues%20%26%20Profit%20Growth%20Dynamics.png)  
[Taxation Structure (Structural Constraints)](https://github.com/Tyron-patterns/real-estate-portfolio-analysis/blob/main/Dashboards/04_Taxation%20Structure%20(Structural%20Constraints).png)  
[Occupancy & Vacancy vs Profitability](https://github.com/Tyron-patterns/real-estate-portfolio-analysis/blob/main/Dashboards/05_Occupancy%20%26%20Vacancy%20vs%20Profitability.png)  
[COVID Impact Analysis](https://github.com/Tyron-patterns/real-estate-portfolio-analysis/blob/main/Dashboards/15_COVID%20Impact%20Analysis.png)
