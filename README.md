# IS525-Final-Project

# Chicago Energy Consumption Forecasting

## Overview

This project aims to forecast future energy consumption and greenhouse gas emissions for properties in Chicago. The insights derived can guide the city's energy efficiency and sustainability initiatives.

## Dataset

The dataset used for this project is the **Chicago Energy Benchmarking - 2021 Data Reported in 2022**. This dataset contains information about various properties in Chicago, their energy consumption, greenhouse gas emissions, and other related attributes.

[Chicago Energy Benchmarking Dataset](https://data.cityofchicago.org/Environment-Sustainable-Development/Chicago-Energy-Benchmarking-2021-Data-Reported-in-/gkf4-txtp)

## Tools Used

- **Python**: For data cleaning, preprocessing, and analysis.
- **pandas & numpy**: Data manipulation and analysis.
- **scikit-learn**: Machine learning modeling.
- **matplotlib**: Data visualization.

## Methodology

1. **Data Cleaning**: Removed columns with more than 50% missing values. Imputed the remaining missing values. Handled outliers and converted data types for better analysis.
2. **Modeling**: Used a Random Forest Regressor to predict 'Electricity Use (kBtu)', 'Natural Gas Use (kBtu)', and 'Total GHG Emissions (Metric Tons CO2e)' based on 'Gross Floor Area - Buildings (sq ft)', 'Year Built', and 'Chicago Energy Rating'.

## Key Findings

- The gross floor area of a building is the most significant predictor of its energy consumption and emissions.
- Most properties in Chicago have relatively low energy consumption, but there are outliers with significantly higher consumption.
- Targeting larger, older buildings for energy efficiency improvements can have a significant impact on reducing overall energy consumption and emissions in Chicago.

## References

- Pérez-Lombard, L., Ortiz, J., & Pout, C. (2008). A review on buildings energy consumption information. Energy and buildings, 40(3), 394-398.
- International Energy Agency. (2006). Key World Energy Statistics.
- Energy Information Administration. (2006). Commercial Buildings Energy Consumption Survey (CBECS). U.S. Department of Energy.
- Gupta, G., Mathur, S., Mathur, J., & Nayak, B. K. (2023). Blending of energy benchmarks models for residential buildings. Energy and Buildings, 292, 113195.

## Author

Luwei Li (luweili2@illinois.edu)
