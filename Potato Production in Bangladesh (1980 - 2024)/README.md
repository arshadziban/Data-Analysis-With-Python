# Potato Production Analysis

This repository contains a Jupyter notebook that analyzes potato production data in Bangladesh from 1980 to 2024. The notebook uses Python and various data analysis libraries to explore and visualize trends in potato production, seed usage, harvested area, yield, and prices.

## Contents

The main file in this repository is `potato_production.ipynb`, which includes the following analyses:

1. Data loading and preprocessing
2. Exploratory data analysis
3. Correlation analysis
4. Time series visualization
5. Predictive modeling

## Data Description

The dataset `potato_production.csv` contains the following columns:

- Year
- Production (Tonnes)
- Seed (Tonnes)
- Area Harvested (Hectares)
- Yield (Tonnes/Hectare)
- Price (BDT/Tonne)

## Requirements

To run this notebook, you'll need the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Key Findings

- Potato production in Bangladesh has shown a steady increase from 1980 to 2024.
- There is a strong positive correlation between production, seed usage, and harvested area.
- Yield (Tonnes/Hectare) has a negative correlation with other variables, indicating a potential area for improvement.
- Prices have increased over time, correlating strongly with production and other factors.

## Models Evaluated

The notebook compares the performance of several regression models:

1. Linear Regression
2. Decision Tree
3. Random Forest
4. Gradient Boosting
5. Support Vector Regressor

Linear Regression shows the best performance for predicting potato prices, with an R2 score of 1.0.

## Usage

To use this notebook:

1. Clone the repository
2. Ensure you have the required libraries installed
3. Open the `potato_production.ipynb` file in Jupyter Notebook or JupyterLab
4. Run the cells sequentially to reproduce the analysis

Feel free to explore and modify the notebook to gain further insights into potato production trends in Bangladesh.



