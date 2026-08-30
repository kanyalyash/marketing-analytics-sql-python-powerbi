
# Marketing Analytics | SQL, Python & Power BI

## Overview

This project analyzes customer, marketing, engagement, journey, and review data for an e-commerce business.

The analysis combines SQL for data preparation, Python for customer review sentiment analysis, and Power BI for interactive reporting and business insights.

## Business Objectives

- Analyze customer engagement and marketing performance
- Understand customer journey and conversion behavior
- Analyze customer reviews and sentiment
- Identify product and customer-level trends
- Build an interactive Power BI dashboard for decision-making

## Tools & Technologies

- SQL Server
- Python
- Pandas
- NLTK / VADER
- Power BI
- DAX
- Excel / CSV

## Project Workflow

### 1. SQL Data Preparation

SQL was used to:

- Clean and standardize customer review data
- Enrich customer data with geographic information
- Categorize products based on price
- Clean and transform marketing engagement data
- Identify and remove duplicate customer journey records
- Handle missing values and standardize fields

### 2. Python Sentiment Analysis

Python was used to analyze customer review text using VADER sentiment analysis.

The analysis generated:

- Sentiment Score
- Sentiment Category
- Sentiment Bucket

The enriched review dataset was then prepared for further analysis.

### 3. Power BI Dashboard

Power BI was used to create an interactive dashboard combining the prepared datasets.

The dashboard focuses on:

- Customer engagement
- Marketing performance
- Customer reviews
- Sentiment analysis
- Customer journey
- Product performance

A DAX calendar table was also created for time-based analysis.

## Key KPIs

- Conversion Rate
- Customer Engagement Rate
- Average Order Value
- Customer Feedback Score
- Marketing and campaign performance

## Repository Contents

```text
sql/       → SQL data cleaning and transformation scripts
python/    → Python sentiment analysis
powerbi/   → Power BI dashboard and DAX
dashboard/ → Dashboard screenshots and PDF
