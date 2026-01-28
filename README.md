# Climate Variability and Maize Yield in Cameroon: A Comparative Analysis

## Overview
This study analyzes the impact of rainfall variability on maize yields, focusing on Cameroon and comparing findings with select African countries. Using annual time-series data, it investigates the extent to which short-term climate fluctuations influence long-term trends in agricultural productivity.

## Research Questions
- Does rainfall variability significantly affect maize yields?
- Are there lagged rainfall effects on agricultural output?
- How do yield dynamics in Cameroon compare to Ghana, Nigeria, and Côte d’Ivoire?

## Data Sources
- Maize yield data: FAOSTAT (Food and Agriculture Organization)
- Rainfall data: World Bank Climate Change Knowledge Portal

We clean and merge climate and agricultural datasets. We visualize yield and rainfall trends. We apply Ordinary Least Squares (OLS) regression using: contemporaneous rainfall, lagged rainfall, and time trend.

## Key Findings
Rainfall variables do not show statistical significance when long-term trends are incorporated.
Significant time trends point to structural influences on yields in Cameroon, Ghana, and Nigeria.
Cameroon shows a negative yield trend relative to the other countries.

## Tools
- Python (pandas, numpy, matplotlib, statsmodels)

## Repository Structure
- `data/`: raw and processed datasets
- `notebooks/`: analysis notebooks
- `figures/`: generated plots
- `report/`: final written report

## Author
Ngeyen Dorcas
