# Housing Price Analysis Report

## Executive Summary

The dataset contains 1,460 residential properties, with an average house price of approximately $180,000. Most house prices fall within the range of $130,000 to $214,000, representing the typical market segment. The relatively high average and wide price range are influenced by outliers, particularly a small number of high-value properties that pull the mean upward.

## Top Price Drivers

Based on the analysis, five key features were found to have a strong impact on house prices:

1. **Overall Quality** (r = 0.79)
2. **Above-Ground Living Area** (sq ft) (r = 0.71)
3. **Garage Capacity** (Number of Cars) (r = 0.64)
4. **Garage Area** (sq ft) (r = 0.62)
5. **Total Basement Area** (sq ft) (r = 0.61)

These features suggest that both structural quality and usable living space play a significant role in determining property value.

## Surprising Findings

### The Bedroom Paradox

Interestingly, the most expensive properties in the dataset tend to have few or no bedrooms, which indicates that price is not driven solely by bedroom count. Many of these high-priced homes are single-family detached units, with some classified as duplexes or townhouse end units, likely reflecting premium locations or larger open living spaces. 

In contrast, the least expensive properties often have six bedrooms and are commonly found in duplexes or two-family conversion units, suggesting that higher bedroom counts do not necessarily translate to higher value.

**Key Statistics:**
- 0-bedroom homes: Average price $221,493 | Average living area 1,371 sq ft
- 6-bedroom homes: Average price $143,779
- 4-bedroom homes command the highest premium at $220,421 average

## Temporal Trends

Additionally, housing prices show a strong upward trend over time, with a noticeable increase starting around 1970 and continuing to the present. Homes built in the 2000s emerge as the most expensive, highlighting the impact of newer construction, modern design, and updated amenities on pricing.

**Price by Era:**
- 1900s: $125,908 average
- 1970s: $156,024 average  
- 2000s: $244,527 average

The 1970s marked an inflection point where prices began accelerating upward, nearly doubling from pre-1970 levels to modern prices.

## Geographic Variation

Neighborhood analysis further reveals significant variation in house prices. **Northridge** stands out as the most expensive neighborhood, with an average house price of approximately $335,000, while **Meadow Village** is the least expensive, with an average price of around $99,000. This underscores the importance of location as a major determinant of housing value.

The price difference of $236,719 between the most and least expensive neighborhoods represents a **339% premium** for top locations, demonstrating that location can override other factors like size in determining value.

**Interesting Finding:** Despite commanding premium prices, Northridge homes average 2,509 sq ft compared to Meadow Village's 1,059 sq ft, suggesting both location AND size contribute to the price differential.

## Key Insights

1. **Quality over Quantity**: Overall quality rating is the strongest predictor of price, more so than square footage or bedroom count
2. **The 1970s Inflection**: Housing prices remained relatively stable from the 1850s through the 1960s, then began rapid appreciation
3. **Location Premium**: Geographic location can create a 3.4x price multiplier independent of home characteristics
4. **Modern Construction Premium**: Homes built in the 2000s command approximately double the price of early 1900s construction
5. **Building Type Matters**: Single-family detached homes show the widest price variance and highest outlier potential

## Future Research Directions

In future work, after gaining a stronger foundation in machine learning and advanced statistical methods, I plan to extend this analysis by developing predictive models to forecast house prices. Specifically, I aim to:

- Explore whether property values are likely to increase or decrease over time
- Identify which features contribute most strongly to future price trends
- Investigate the 0-bedroom anomaly more deeply to understand these unique properties
- Analyze interaction effects between features (e.g., does quality matter more in certain neighborhoods?)
- Examine whether the temporal trend continues or if market saturation occurs

## Methodology Notes

**Dataset:** 1,460 residential properties with 81 features including physical characteristics, location data, and sale information

**Key Variables Analyzed:**
- Numeric: SalePrice, GrLivArea, OverallQual, YearBuilt, BedroomAbvGr, and 33 other numeric features
- Categorical: Neighborhood, BldgType, and 43 other categorical features

**Analysis Techniques:**
- Descriptive statistics and distribution analysis
- Correlation analysis
- Group comparisons and aggregations
- Temporal trend analysis
- Visualization through histograms, scatter plots, box plots, heatmaps, and pair plots

---

*Analysis completed: February 2026*  
*Dataset: Kaggle House Prices - Advanced Regression Techniques*
