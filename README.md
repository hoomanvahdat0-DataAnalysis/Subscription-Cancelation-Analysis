# Subscription Cancellation Analysis

## Executive Summary:
The dataset under analysis comes from a software-as-a-service (SaaS) company that offers subscription-based products with recurring renewals. When customers cancel their subscriptions, they are required to select at least one reason, with the option to choose up to three. However, it is reasonable to assume that many dissatisfied users prefer to complete the cancellation process quickly and may not take the time to select multiple reasons.

## Business Problem:
The company is facing a customer retention problem, as a significant number of users choose not to renew their subscriptions.
The goal of the analysis is to identify the factors contributing to this higher-than-expected churn rate. To address this, data analysis tools—such as SQL—are used to examine cancellation patterns, including the most frequently cited reasons and any emerging trends.

![Data Model](https://github.com/hoomanvahdat0-DataAnalysis/Subscription-Cancelation-Analysis/blob/main/Subscription%20Cancelation%20Analysis.png)

## Methodology:
1. EDA  Exploratory Data Analysis
2. Product Funnel Analysis
3. Data Visualization
EDA shows that the most commonly selected primary reason for cancellation is “not useful,” followed by “expensive.” For the second reason, “went to competitor” appears most frequently, again followed by “expensive.” The third reason is most often listed as “none,” suggesting that few users go beyond the minimum requirement.
  

## Skills:
1. SQL: CTEs, CASE, Union, View creation
2. Data Visualization
3. Data Wrangling
4. Data Cleaning
5. Data Science Notebook
6. Snowflake Data warehouse

##    Business Recommendations:
1. Since most users have selected Expensive and Not Useful as the reasons to cancel, we should roll out better onboarding and provide more help early on in their subscription to ensure users understand the product and find it useful. If they find the product more useful and valuable, they may also become less cost-sensitive to its value.
   
2. For cost-conscious users, we could also launch a rescue tactic at the beginning of the cancellation workflow that offers them a large discount to stay and not cancel their subscription.
   
3. Since the most common cancellation reason for the secondary reason is Went to Competitor, we should research the market and ensure we're keeping up to date with industry trends.
