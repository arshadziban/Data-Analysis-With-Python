# Crop Yield Analysis in Bangladesh

This project analyzes crop yield data for rice production in Bangladesh using Python and the Polars library. The analysis provides insights into rice yields across different states, seasons, and their relationships with various factors such as rainfall, fertilizer use, and pesticide application.

## Features

- Data loading and preprocessing using Polars
- Exploratory data analysis of rice yields across different states and seasons
- Statistical analysis of yield distributions
- Correlation analysis between yield and environmental factors

## Key Findings

- The average annual rainfall in the dataset is approximately **1218.39 mm**, with a standard deviation of **991.99 mm** [1].
- **Narsingdi** has the highest average rice yield at **3.87 tons/hectare**, while **Tongi** has the lowest at **1.08 tons/hectare** [1].
- The highest recorded rice yield is **8.78 tons/hectare** in **Tangail** [1].
- There is a weak negative correlation between yield and annual rainfall (**-0.036**), suggesting that higher rainfall doesn't necessarily lead to increased yields [1].
- Fertilizer use shows a very weak negative correlation with yield (**-0.001**), indicating that increased fertilizer application may not significantly improve yields [1].

## Requirements

- Python 3.x
- Polars library
- Google Colab (for running the notebook)

## Usage

1. Mount your Google Drive in Colab.
2. Install the required libraries (Polars):
   ```bash
   pip install polars
