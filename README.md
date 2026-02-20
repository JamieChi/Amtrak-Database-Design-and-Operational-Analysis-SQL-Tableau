## Project Overview
We built a centralized relational database and conducted SQL-based analysis to support strategic decision-making in resource planning, route optimization, and customer loyalty programs.

## Data Overview
The original dataset contained
general information about Amtrak stations, while the data set we processed
focused on ridership, OTP, AGR, procurement for each state. We have added a
unique ID to each dataset to ensure that each record can be uniquely identified
and to support cross-table analysis and queries.

## Objectives
To enhance Amtrak’s operational performance and customer satisfaction by leveraging
data-driven insights to analyze ridership trends, optimize resource allocation, enhance
on-time performance, and maximize the value of AGR membership programs.

## Database Design
- Entity-Relationship Diagram (ERD)
- Relational Schema
- SQL - Create tables

## Business Transactions & Key Insights
**1. Budget Allocation & Procurement**
- Question:** What are the average procurement expenses for all states over the past three years?
- Insight:** California and New York dominate procurement spending. We recommend optimizing budget allocation for these high-spending states and assessing regional cost factors (e.g., Virginia's significant drop in expenses).

**2. Ridership Trends**
- Question: Which states experienced the fastest ridership growth over the past three years? 
- Insight: Vermont experienced an extraordinary 513.1% growth, indicating a massive emerging demand.

**3. Operational Bottlenecks **
- Question: Which routes had an average Ontime Performance rate (OTP) below 50% over the past three years? 
- Insight: Long-distance routes like the Sunset Limited (30.7%) and Southwest Chief (32.7%) face significant delays due to the complexity of multi-state operations and logistical challenges.

**4. Loyalty Program Forecasting**
- Question: What are the predicted AGR membership numbers for all states in FY24, based on FY21-FY23 growth rates? 
- Insight: California leads by a wide margin with an expected 2.28M members and a 22.03% growth rate.
