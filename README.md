# Teleconnect-Churn-Analysis

## Project Background and Overview

Teleconnect is a fictious telecommunication company that specializes in voice communication, internet services, data transformation, streaming services, network infrastructure and everything that has to do with telecommunication, they play a huge role in connecting people and businesses enabling communication and data exchange.

The company has a significant number of churn records. My contribution to the team is to thoroughly analyse and identify churn customers, that is, customers most likely to cancel subscription and understand the underlying customer patterns that greatly impact their decision to churn and also predict customers most likely to cancel their subscription.

Insights are provided in the following key areas:
- Customer Demographics: Identify which customer segments (age, gender, location, etc.) have the highest churn rates.
- Subscription Plans: Determine if certain tenure groups or contract type are associated with higher churn
- Usage Patterns: Analyze how usage frequency, duration, and type of service impact churn
- Predictive Modeling: Develop models to predict future churn and identify at-risk customers.

An interactive Power BI dashboard can be downloaded here
The SQL queries utilized to inspect and perform quality checks can be found here 
Targeted SQL queries regarding various business questions can be found here
The python notebook for predictive analysis queries can be found here

## Data Structure & Initial Checks

The dataset structure as seen below consists of 32 columns, with a total row count of 6418.

![Screenshot 2025-01-22 234715](https://github.com/user-attachments/assets/af33b0c9-a3c5-4ffe-99d4-ec6cdd3f64d1)

Prior to beginning the analysis, a variety of checks were conducted fo quality control and familiarization with the dataset. The SQL queries utilized to inspect and perform quality checks and validation are found on the above folder labeled "Churn analysis EDA script".

## Executive Summary
### Overview of Findings

Analysis reveal a significant divergence between total customers and churn rate within the tenure group of 24 months or more,suggesting that long-term customers may be experiencing issues or dissatisfaction that lead them to leave our service. Key perfomance indicators have shown that the overall churn rate is 27.0%, where 1732 customers out 6418 customers cancel their subscriptions, and the primary reason being that the competitor offer significantly better devices.  Notably,customers over the age of 50 account for 31.66% of customers who cancel their subscription. Total number of customers predicted to cancel their subscription in the near future are 381,

Below is an overview page of from the PowerBI dashboard. The entire interactive dashboard can be downloaded here.


