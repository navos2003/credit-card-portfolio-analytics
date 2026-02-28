# Credit Card Portfolio Risk Analytics

## Overview

This project simulates how a financial institution monitors credit card portfolio health, customer engagement, and risk exposure using a cloud-based analytics workflow.

The goal was to recreate a realistic card analytics environment leveraging AWS, SQL, Python, and Power BI to evaluate behavioral risk signals and portfolio composition.

The project analyzes 10,000+ customer records to identify patterns in utilization, engagement, product mix, and demographic segmentation.


## Architecture

S3 (Data Storage)  
→ Amazon Athena (Serverless SQL Querying)  
→ Python (Feature Engineering & Risk Indicators)  
→ Power BI (Executive Dashboard & Reporting)


## Business Objectives

- Monitor portfolio health and risk exposure
- Identify behavioral drivers of elevated risk
- Analyze demographic and product segmentation
- Evaluate engagement and relationship depth signals
- Deliver executive-level reporting dashboard


## Key Analyses

### Portfolio Overview
- Total customers
- Total portfolio spend
- Average credit utilization
- High-risk customer percentage

### Risk Segmentation
- Risk distribution across income segments
- Risk concentration by card tier
- Gender-based risk variation
- Behavioral risk signals (utilization, inactivity, contacts)

### Engagement & Behavior
- Relationship depth analysis
- Activity segmentation
- Credit utilization distribution
- Open-to-buy analysis


## Feature Engineering (Python)

Behavioral risk indicators were engineered using:

- Credit utilization ratios
- Inactivity flags
- Contact frequency indicators
- Composite risk segmentation logic
