# Real_Estate_Predictive_Analysis
Real Estate Predictive Analysis

1. Executive Summary

This project focuses on developing a robust real estate price prediction system using data-driven techniques. Through effective data cleaning and feature engineering, the model was designed to reflect real-world market behavior and economic logic.

2. Data Integrity (Outlier Handling)

The Interquartile Range (IQR) method was applied to detect and remove outliers.

Impact: Eliminating extreme values reduced noise caused by rare luxury properties or data inconsistencies, allowing the model to better capture typical market trends.

3. Key Insights (Feature Relationships)

The analysis revealed strong relationships between features and property prices:

Proximity to Transit: Properties closer to MRT stations tend to have higher prices.
Centrality: Houses located nearer to the city center show increased value.
Local Amenities: A higher number of nearby convenience stores positively impacts pricing.
Property Age: Newer properties generally have higher valuations, with limited exceptions.

4. Feature Engineering

Log Transformation: Applied to distance features to create a more linear and model-friendly relationship with price.
Feature Scaling: Normalization ensured fair contribution of all variables regardless of their units.

5. Model Development & Comparison

Two regression models were implemented and evaluated:

Linear Regression: Effective in capturing direct relationships between features and price.
Random Forest Regressor: Delivered superior performance by modeling complex, non-linear interactions between variables.

6. Conclusion

The final model achieves reliable and realistic predictions by combining clean data, meaningful feature engineering, and advanced algorithms. The results strongly reinforce the core principle of real estate: location remains the most critical factor in property valuation.
