# Stats 506 Final Project: Enhancing Model Interpretability and Exploring Urbanization Levels with k-means Clustering

This repository contains the data analysis and visualization codes for my Stats 506 final project at the University of Michigan. The project investigates the correlations between healthcare payments and income levels with urbanization, utilizing k-means clustering for enhanced interpretability and deeper insights.

## Introduction

In the healthcare industry, analyzing the costs and payments for medical services is essential for public health management and economic studies. This project leverages Medicare data, specifically the "Medicare Physician & Other Practitioners" dataset, and combines it with the "2021 ZIP Code Data" from the U.S. Internal Revenue Service to explore potential connections between medical payments and regional economic conditions.

## Data Description and Preprocessing

The project uses two main data sources:
- **Medicare Provider Payment Data:** Includes details on the payments for medical services billed to Medicare.
- **IRS Tax Data:** Features individual income tax statistics, providing a unique perspective on community economic status.

### Preprocessing Steps

The data undergo rigorous cleaning and preprocessing to ensure robust analysis, including handling missing values, treating outliers, standardizing monetary variables, and transforming total incomes into averages weighted by the number of taxpayers.

## k-means Clustering Analysis

### Exploring Correlations

We focus on the relationships between Average Medicare Payment Amounts and Average Adjusted Gross Income (Avg AGI). Various k-values were tested to find the best structure that captures the inherent data patterns effectively.

### Enhancing Model Interpretability

By segmenting the data into distinct clusters, we construct independent linear regression models to enhance interpretability and explanatory power. This involves comparing models based on different clustering approaches, including a Random Segment Model and a Clustered Segment Model.

### Urbanization Level Analysis

The project also assesses how healthcare payments and income levels correlate with urbanization levels, quantified by RUCA codes. The analysis includes detailed visualizations of RUCA code distributions across clusters, highlighting significant patterns based on urbanization levels.

## Conclusion and Recommendations

The findings suggest significant correlations between healthcare payments and income levels with urbanization degrees. Policy recommendations are provided to tailor medical resource allocation based on urbanization levels.


## Acknowledgments

- Data provided by Medicare and the U.S. Internal Revenue Service.
- Statistical guidance and support provided by Dr. Josh Errickson, PhD, Department of Statistics, University of Michigan.

For more information on the datasets used:
- [Medicare Provider Utilization and Payment Data](https://data.cms.gov/provider-summary-by-type-of-service/medicare-physician-other-practitioners/medicare-physician-other-practitioners-by-geography-and-service)
- [IRS 2021 ZIP Code Data](https://www.irs.gov/statistics/soi-tax-stats-individual-income-tax-statistics-2021-zip-code-data-soi)

