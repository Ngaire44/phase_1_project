# Aviation Risk Analysis Project

## 📊 Business Understanding

### Project Overview
As the company explores entry into the aviation industry, this project uses aviation accident data from the National Transportation Safety Board (1962–2023) to identify strategic opportunities and risk factors. By analyzing trends, causes, and survivability of aviation incidents, we aim to identify low-risk aircrafts to buy and guide data-informed decisions.
### Business Objective
Provide actionable insights to support aircraft purchase decisions that minimize operational risk. These insights will assist internal stakeholders, investors, and insurers in evaluating the safety profiles of aircraft types and aviation sectors.

## ❓ Key Business Questions
This analysis is guided by the following questions:

1. Which aircraft makes are least involved in accidents?
    Helps prioritize safer manufacturers and assess amateur-built risks.
2. What are the most common causes of accidents?
    Informs safety trends, age/model comparisons.
3. What factors affect accident survivability?
    Investigates impact of weather, engine types, and other conditions.
4. How do accident rates differ between commercial and private operators?
    Supports strategic entry into the most stable sector.
5. Are there seasonal patterns in accidents?
    Aids in weather contingency and planning.
6. What factors contribute most to fatal accidents?
    Guides aircraft specification requirements and safety features.

## 📂 Data Understanding

In this section, we explore the dataset to understand its structure, contents, and quality. The dataset includes over six decades of aviation accident records, so it’s important to assess its usability before analysis.
We examine:Column types and descriptions,
Missing data patterns,
Categorical variables and grouping,
Temporal and geographic coverage,
Data completeness, consistency, and uniqueness.
This initial assessment helps identify potential challenges and guides how we prepare the data for accurate and meaningful analysis.

## 🧼 Data Cleaning & Preparation

The goal of data cleaning is to transform the raw dataset into a structured and reliable format suitable for analysis. Key steps included:
Missing Value Handling,
Drop columns with excessive missing data,
Impute missing values using appropriate statistical or categorical strategies,
Data Filtering,
Remove irrelevant or incomplete records (e.g. non-aircraft incidents or missing key variables),
Categorical Grouping,
Group low-frequency entries under broader labels (e.g. "Other")
Data Type Correction,
Convert date columns to proper datetime format,
Ensure numerical columns were correctly typed for analysis, and
Outlier Treatment.

These steps ensure we have a clean, consistent, and relevant dataset to move forward with meaningful visualizations and business insights.


