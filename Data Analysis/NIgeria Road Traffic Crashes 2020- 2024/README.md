# Road Crash Data Analysis Report

## Table of Contents
1. [Introduction](#introduction)
2. [Research Questions](#research-questions)
3. [Data Overview](#data-overview)
4. [Data Cleaning and Preparation](#data-cleaning-and-preparation)
5. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
    1. [Which States Have the Highest Number of Crashes and Fatalities?](#which-states-have-the-highest-number-of-crashes-and-fatalities)
    2. [Most Common Contributing Factors to Road Crashes](#most-common-contributing-factors-to-road-crashes)
    3. [Relationship Between Number of Vehicles Involved and Accident Severity](#relationship-between-number-of-vehicles-involved-and-accident-severity)
    4. [Which Quarter Has the Most Accidents?](#which-quarter-has-the-most-accidents)
6. [Key Performance Indicators (KPIs)](#key-performance-indicators-kpis)
7. [Conclusion](#conclusion)

---

## Introduction

This report presents an analysis of road crash data, focusing on key patterns and insights. The dataset includes records from various states, containing information on total crashes, the number of injuries and fatalities, the number of vehicles involved, and contributing factors to the accidents. 

The goal of this analysis is to explore trends and relationships within the data to better understand the causes of accidents and identify areas that require interventions.

---

## Research Questions

1. Which states have the highest number of crashes and fatalities?
2. What are the most common contributing factors to road crashes?
3. What is the relationship between the number of vehicles involved and the severity of accidents?
4. Which quarter has the most accidents?

---

## Data Overview

The dataset includes the following columns:

- **Quarter**: The quarter in which the crashes occurred (e.g., Q4 2020).
- **State**: The state where the crash occurred.
- **Total_Crashes**: The number of crashes in that state for the quarter.
- **Num_Injured**: The number of individuals injured in crashes.
- **Num_Killed**: The number of fatalities in crashes.
- **Total_Vehicles_Involved**: The number of vehicles involved in the crashes.
- **Contributing Factors (SPV, DAD, PWR, FTQ, Other_Factors)**: These indicate specific causes or contributing factors to the crashes.

---

## Data Cleaning and Preparation

Before starting the analysis, the following steps were performed to clean and prepare the data:

- **Missing Data Handling**: Checked for any missing values and handled them using appropriate techniques (e.g., filling with median or removing rows).
- **Data Type Conversions**: Ensured that numerical columns were correctly formatted and that categorical data (e.g., states, quarters) were appropriately categorized.
- **Feature Engineering**: Created additional columns where necessary, such as total crashes per quarter or average vehicles involved per state.

---

## Exploratory Data Analysis (EDA)

### Which States Have the Highest Number of Crashes and Fatalities?

To answer this, we performed a state-wise aggregation of crashes and fatalities:

- **Graph**: Bar chart showing states with the highest number of crashes and fatalities.
- **Key Insights**: States like FCT and Ogun had the highest number of crashes. These states also ranked high in fatalities.

### Most Common Contributing Factors to Road Crashes

The dataset includes factors like SPV (Speed Violation), DAD (Driving Under Alcohol), etc. We examined which factors appeared most frequently.

- **Graph**: Pie chart or bar graph visualizing the distribution of contributing factors.
- **Key Insights**: The most common contributing factor was Speed Violation (SPV), accounting for 37.7% of the total crashes.

### Relationship Between Number of Vehicles Involved and Accident Severity

Here, we performed a correlation analysis between the number of vehicles involved and the number of fatalities and injuries.

- **Graph**: Scatter plot showing the relationship between vehicles involved and the number of fatalities.
- **Key Insights**: There is a 0.6154088002801272 correlation between the number of vehicles involved and accident severity, indicating that crashes involving more vehicles tend to have more fatalities.

### Which Quarter Has the Most Accidents?

We analyzed the data by quarters to find out which quarter had the highest number of crashes.

- **Graph**: Line graph comparing crashes across different quarters.
- **Key Insights**: Q4 2022 had the most crashes, suggesting seasonal or other temporal factors influencing road safety.

---

## Key Performance Indicators (KPIs)

Some important KPIs derived from the data include:

- **Total Crashes**: The overall number of crashes across all states and quarters.
    - Formula: `SUM(Total_Crashes)`
- **Total Fatalities**: Total number of deaths due to crashes.
    - Formula: `SUM(Num_Killed)`
- **Average Number of Vehicles Involved per Crash**: The average number of vehicles involved across all crashes.
    - Formula: `AVG(Total_Vehicles_Involved)`
- **Crash Severity Ratio**: Ratio of fatalities to total crashes.
    - Formula: `SUM(Num_Killed) / SUM(Total_Crashes)`

---

## Conclusion

The analysis of the road crash data provides several insights that can help in identifying high-risk states and common causes of road crashes. States like FCT and Ogun have higher crash rates, often driven by factors like Speed Violation (SPV). There is also a significant relationship between the number of vehicles involved and crash severity, which can inform traffic regulation policies.

Further research is needed to investigate the regional differences in crash causes and to develop targeted interventions.

---

