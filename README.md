# Subscription Cancellation Analysis

## Executive Summary:
The company is experiencing high churn and substantial revenue loss, prompting leadership to seek deeper insights into why customers are canceling subscriptions. This analysis examines user-reported cancellation reasons to uncover patterns and generate recommendations aimed at improving retention moving forward.

## Business Problem:
Company leadership has identified a significant churn issue this year that has materially impacted revenue, prompting plans for a company-wide retention initiative. However, there is currently limited visibility into the underlying reasons behind customer cancellations. To address this gap, the analytics team is analyzing user-reported feedback collected during the in-product cancellation workflow to uncover trends and better understand why users are choosing to leave.

![Data Model](https://github.com/hoomanvahdat0-DataAnalysis/Subscription-Cancelation-Analysis/blob/main/Subscription%20Cancelation%20Analysis.png)

## Methodology:
1. EDA  Exploratory Data Analysis
2. Product Funnel Analysis
3. Data Visualization

## Skills:
1. SQL: CTEs, CASE, Union, View creation
2. Data Visualization
3. Data Wrangling
4. Data Cleaning
5. Data Science Notebook
6. Snowflake Data warehouse

## Results:
1. X% of users are selecting at least 1 additional cancelation reason (beyond the first required one), but most users are not selecting all 3 which suggests lack of interest and frustration for the user.
2. X% of users reported Y as the primary (first) cancelation reason. The top choices for the primary reason were _______.
Over time, here's how the cancelation reasons have changed: _____.

##    Business Recommendations:
1. Since most users have selected Expensive and Not Useful as the reasons to cancel, we should roll out better onboarding and provide more help early on in their subscription to ensure users understand the product and find it useful. If they find the product more useful and valuable, they may also become less cost-sensitive to its value.
   
2. For cost-conscious users, we could also launch a rescue tactic at the beginning of the cancellation workflow that offers them a large discount to stay and not cancel their subscription.
   
3. Since the most common cancellation reason for the secondary reason is Went to Competitor, we should research the market and ensure we're keeping up to date with industry trends.
