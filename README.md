# 🌍 World Happiness Report 2015-2019 Trends
Interactive Excel Dashboard for World Happiness Analysis


## Overview
The project analyses the World Happiness Report database for the period 2015-2019, using Excel for cleaning, analysis and visualisation.
The goal is to identify trends over the period and explore correlations between happiness and other factors such as GDP per capita and corruption perception, and compare those on 
a country and region-level through an interactive dashboard.


## Tools Used
- Microsoft Excel – Power Query, Pivot Tables, Charts, and Slicers


## Data Cleaning Steps
- Appended tables for the separate years using PowerQuery
- Removed duplicates
- Standardised country names and regions
- Unified column/factor names across years for consistency
- Handled missing values


## Analysis and Charts
1. Happiness Score Trends (2015 - 2019)
- Line chart with slicers to filter by country and/or region

2. Biggest % Changes in Happiness Score
- Top 5 countries with the biggest positive and negative % change, respectively
- Visualised with a column chart

3. Happiness vs Corruption
- Correlation visualised with a scatter plot

4. Happiness vs GDP per Capita
- Scatter plot showing the relationship

5. Regional Happiness Trends
- Multi-line chart comparing happiness trends by region over the period


## Dashboard Preview
![image](https://github.com/user-attachments/assets/d550fb72-522d-47b5-8053-d5ec0c6ed291)

## Key Insights
- The overall happiness score has increased over the observed period
- However, only 4 out of the 10 regions experienced an upward trend; the remaining 6 saw a decline
- The biggest positive and negative % changes in happiness scores were observed predominantly in Sub-Saharan Africa
- There is a strong positive correlation between happiness and GDP per capita
- A weaker positive correlation exists between happiness and perceived corruption, suggesting that lower perceived corruption is linked to higher happiness

## Dataset Information

**Source:** [World Happiness Report (via Kaggle)](https://www.kaggle.com/datasets/unsdsn/world-happiness/data)

**Years Covered:** 2015–2019

**File Format:** CSV files imported into Excel

**Key Columns:** 
- Country, Region, Year
- Happiness Score, GDP per Capita, Perceived Corruption







