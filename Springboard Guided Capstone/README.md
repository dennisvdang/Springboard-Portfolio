# Big Mountain Resort Data Science Project Report

## Submitted by: Dennis Dang

## Executive Summary

Big Mountain Resort aims to optimize ski ticket prices to increase revenue. This report details the data-driven methodology used to explore, model, and recommend pricing strategies. A comprehensive analysis of resort data reveals opportunities to adjust pricing in line with value-added services, which is anticipated to increase profitability while maintaining customer satisfaction.

## Table of Contents

- [Executive Summary](#executive-summary)
- [Introduction](#introduction)
  - [Problem Statement](#problem-statement)
- [Methodology](#methodology)
  - [Data-Wrangling](#data-wrangling)
  - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Pre-Processing and Training Data Development](#pre-processing-and-training-data-development)
  - [Algorithms Used and Evaluation Metrics](#algorithms-used-and-evaluation-metrics)
- [Findings and Recommendations](#findings-and-recommendations)
  - [Winning Model](#winning-model)
  - [Scenario Modeling](#scenario-modeling)
  - [Pricing Recommendation](#pricing-recommendation)
- [Conclusion](#conclusion)
- [Future Scope of Work](#future-scope-of-work)

## Introduction

### Problem Statement

Big Mountain Resort charges premium ticket prices within their market segment but may not be fully capitalizing on their facilities. The Big Mountain Resort is aiming to increase its revenue for the 2024 snow season. To achieve this, we hypothesize that a thorough analysis of ticket pricing factors across the industry, combined with an optimization of our own pricing strategy, will unlock new growth opportunities. Success hinges on our ability to:

- Accurately identify the critical elements that drive ticket pricing.
- Develop strategic recommendations to inform pricing adjustments.

The scope of this initiative centers on dissecting industry-wide data from comparable ski resorts to pinpoint the determinants of ticket pricing and to understand how different pricing strategies might influence our revenue trajectory. We face the challenge of relying on the availability of precise and comprehensive industry and financial data.

Key insights into operational constraints and data management will be sought from Jimmy Blackburn (Director of Operations) and Alesha Eisen (Database Manager). The primary data source is a CSV file detailing attributes and pricing of 330 ski resorts, augmented by Big Mountain Resort's historical and projected revenue figures. This data-driven approach will guide our pursuit of our revenue increase target for the 2024 season. 

## Methodology

The methodology for optimizing ticket pricing at Big Mountain Resort is organized into four key stages: Data-Wrangling, Exploratory Data Analysis, Pre-processing and Training Data Development, and Modeling.

### Data-Wrangling

Our dataset contained resort characteristics and ticket pricing data of 330 ski resorts across the United States. A thorough examination was conducted to identify and rectify any inconsistencies, such as missing values or anomalies. Related information, like geographic data, was aggregated to provide a clearer picture of regional factors that may influence pricing strategies. Records missing our primary objective, ‘AdultWeekend’ ticket price were removed. The initial dataset contained 330 entries. After cleaning, we refined this number to 277 high-quality records. As demonstrated in Figure 1, we visualized the distributions of each variable to detect outliers or anomalies. By understanding what these variables represent, we can make informed decisions about how to handle irregular data.

### Exploratory Data Analysis (EDA)

Our EDA focused on a thorough investigation of both numerical and categorical variables within a dataset of 277 ski resorts. The goal was to uncover underlying patterns and relationships that could inform the development of a predictive pricing model.

**Numerical Features and Feature Generation**
Numerical features such as resort elevation, number of ski runs, and area available for night skiing were thoroughly examined. To augment our analysis, we generated insightful state-level features by aggregating state population data and state area in square miles. From these aggregates, we created nuanced features reflecting the density and availability of ski resort amenities relative to state statistics:
- resorts_per_100k_capita: The number of ski resorts per 100,000 people in the state.
- resorts_per_100ksq_mile: The number of ski resorts per 100,000 square miles of state land.

Additionally, we engineered several ratios to capture the proportionate scale of resort features within their respective states:
- resort_skiable_area_ac_state_ratio: The ratio of a resort's skiable area to the total skiable area available in the state.
- resort_terrain_park_state_ratio: The ratio of the number of terrain parks at a resort to the total number in the state.
- resort_night_skiing_state_ratio: The ratio of a resort's night skiing area to the total night skiing area available in the state.
- resort_days_open_state_ratio: The ratio of the number of days a resort is open to the total number of operational days for all resorts in the state.

These ratios provide a relative scale that contextualizes each resort's features within the broader state-level market. The engineered features also provide a nuanced view of market saturation and potential access to ski facilities for the population.


### Pre-Processing and Training Data Development

We partitioned the data into training and test sets, which is crucial for an objective evaluation of our predictive models.

### Algorithms Used and Evaluation Metrics

We compared the accuracy of our Linear Model and Random Forest Model to the baseline model that uses the mean as a constant prediction for ticket prices.

## Findings and Recommendations

### Winning Model

The Random Forest Regressor was ultimately chosen as the preferred model. It stood out for its lower MAE and the consistency of its cross-validation performance.

### Scenario Modeling

Our data-driven analysis of Big Mountain Resort's pricing strategy has revealed several scenarios that could influence the optimal ticket price.

### Pricing Recommendation

Given these scenarios, the most strategic recommendation for Big Mountain Resort is to pursue the developments outlined in Scenario 2.

## Conclusion

Our data-driven analysis suggests that Big Mountain Resort can increase its ticket prices for the 2024 season. Key features like the number of fast quad ski lifts, number of ski runs, and area of land covered by snow makers are highly correlated with ticket pricing.

## Future Scope of Work

Operational Testing, Comprehensive Cost Analysis, and Model Integration and Tool Development are suggested as future areas of work to refine and enhance the pricing strategy at Big Mountain Resort.


