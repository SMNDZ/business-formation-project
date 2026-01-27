# Understanding Business Formation Trends in the U.S.

![Small business image](https://images.unsplash.com/photo-1520607162513-77705c0f0d4a)

## Motivation

Business formation is an important indicator of economic activity. Understanding when and where new businesses are created can help policymakers, analysts, and stakeholders recognize trends, identify growth sectors, and make informed decisions.

This project explores the U.S. Census Bureau Business Formation Statistics dataset to understand patterns in business formation activity and determine whether simple modeling techniques can help explain or predict these trends.

## Libraries Used

- pandas  
- matplotlib  
- scikit-learn  

## Files in This Repository

- **business_formation_analysis.ipynb** — Main analysis notebook following the CRISP-DM process
- **BFS-mf.csv** — Dataset used for the analysis
- **README.md** — Project overview and summary

## Business Questions Explored

1. How does business formation activity change over time?
2. How are business formation values distributed overall?
3. Which industries contribute the most to business formation activity?
4. How well can a simple model predict business formation values?

## Summary of Findings

- Business formation activity shows noticeable spikes and drops across time periods.
- The distribution of values is highly skewed, with many small values and a few very large spikes.
- Certain categories contribute far more to overall business formation activity than others.
- A simple linear regression model captures general patterns but is not highly predictive, suggesting many real-world factors are not present in the dataset.

## Blog Post

A full stakeholder-friendly explanation of this analysis can be found here:

👉 **https://medium.com/@siggraph21/predicting-business-formation-trends-76172e166f89**

## Acknowledgements

Dataset provided by the U.S. Census Bureau Business Formation Statistics.
