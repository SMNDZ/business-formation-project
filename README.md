# Predicting Business Formation Trends

![Small business image](https://images.unsplash.com/photo-1520607162513-77705c0f0d4a)

## Introduction
Have you ever noticed how some months feel packed with new businesses while others feel quieter? I wanted to explore whether public data could help explain these patterns and whether a simple model could make predictions about business formation activity.

## Questions of Interest
1. What factors are most useful for predicting business formation values?
2. Are there noticeable trends or patterns in the data?
3. How accurate is a simple prediction model?
4. What does the model predict in a realistic scenario?

## Key Findings
Exploratory analysis showed that the data is highly skewed, with many smaller values and a few very large ones. This suggests that business formation activity can spike during certain periods.

Using a Linear Regression model, the R2 score was approximately **0.08**, meaning the model explains a small portion of the variation in the data. This is expected given that many real-world factors influencing business formation are not captured in the dataset.

## Prediction Scenario
Using a sample data point, the model predicted a value of approximately **4,078**. This prediction represents an estimate based on the input features and should be interpreted as a general indication rather than an exact forecast.

## Conclusion
This project shows that even a simple model can identify basic patterns in business formation data. While the model is not highly precise, it demonstrates how public datasets and machine learning can be used to explore economic trends.

## Acknowledgments
Data source: U.S. Census Bureau Business Formation Statistics
