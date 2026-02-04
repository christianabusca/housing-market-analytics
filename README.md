# Housing Price Analysis

An exploratory data analysis project investigating what factors drive residential property prices using the Kaggle House Prices dataset.

## About This Project

This project analyzes 1,460 residential properties to answer: **"What makes houses expensive?"**

I explored the relationship between house prices and various features like size, quality, location, and age using Python data analysis tools.

## Key Findings

**Top 5 Factors That Affect Price:**
1. Overall Quality (correlation: 0.79)
2. Living Area Size (correlation: 0.71)
3. Garage Capacity (correlation: 0.64)
4. Garage Area (correlation: 0.62)
5. Basement Size (correlation: 0.61)

**Interesting Discoveries:**
- Houses with 0 bedrooms averaged $221K (higher than 1-6 bedroom homes!)
- Northridge neighborhood is 3.4x more expensive than Meadow Village
- Homes built after 2000 cost almost double those from the 1900s
- Price distribution is right-skewed with most houses around $150K-$180K

## Dataset

**Source**: [Kaggle House Prices Competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

**Note**: The dataset is NOT included in this repository. Download it from Kaggle.

- 1,460 residential properties
- 81 features (size, quality, location, age, etc.)
- Target: SalePrice (in USD)

## Tools Used

- **Python** - Programming language
- **Pandas** - Data manipulation
- **Matplotlib & Seaborn** - Data visualization
- **NumPy** - Numerical computing
- **Kaggle Notebooks** - Development environment

## Project Structure

```
housing-price-analysis/
├── notebooks/
│   └── housing_analysis.ipynb       # Main analysis notebook
├── images/
│   ├── dashboard.jpg                # Summary visualization
│   ├── price_distribution.jpg       # Price histogram
│   ├── correlation_heatmap.jpg      # Correlation matrix
│   ├── pairplot.jpg                 # Multivariate analysis
│   └── neighborhood_comparison.jpg  # Location analysis
├── reports/
│   └── housing_price_analysis_report.md  # Written findings
└── README.md                        # This file
```

**Note**: The `data` folder is **NOT included** in this repository due to licensing.


## What I Learned

- **Quality matters most** - Overall quality is the strongest price predictor
- **Location creates huge differences** - Same house can be 3x more expensive in different neighborhoods
- **Size and price are strongly related** - But there's still lots of variation
- **Newer homes cost more** - Modern construction commands premium prices
- **More bedrooms ≠ higher price** - Quality and location matter more than bedroom count

## Next Steps

- Build a machine learning model to predict house prices
- Try different regression algorithms
- Feature engineering for better predictions
- Create an interactive dashboard


---

**Dataset**: Kaggle House Prices Competition  
**Platform**: Kaggle Notebooks  
**Status**: Complete (February 2026)
