# Global Population Prediction in 2025

This project analyzes population trends from 2014 to 2024 and predicts the population for the year 2025 using a linear regression model. The dataset used for this analysis contains population data for various countries over the years.

## Dataset
The dataset used in this project is `global-population-dataset-20142024`, available on Kaggle.

### Dataset Link:
[Global Population Dataset 2014-2024](https://www.kaggle.com/datasets/ankushpanday1/global-population-dataset-20142024)

### Columns in the Dataset:
- `Country`: Names of countries.
- Year columns (e.g., `2014`, `2015`, ..., `2024`): Population data for respective years.

## Libraries Used
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For visualization.
- **NumPy**: For numerical operations.
- **Scikit-learn**: For building and evaluating the linear regression model.

## Steps Performed

1. **Data Import and Preprocessing**:
   - Imported the dataset.
   - Extracted years and population data.

2. **Visualization**:
   - Plotted population trends for all countries between 2014 and 2024.

3. **Prediction Model**:
   - Built a linear regression model to predict population trends.
   - Split data into training (2014-2023) and testing (2024).
   - Predicted the population for 2024 and 2025.

4. **Performance Metrics**:
   - Evaluated the model using:
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)
     - R² Score

## Results
- **Model Performance**:
  - MAE: Indicates the average error in predictions.
  - MSE: Measures the average squared error.
  - R² Score: Indicates how well the model explains the variability in the data.

- **Predictions**:
  - Predicted population for 2024.
  - Predicted population for 2025.

## Usage

### Requirements
- Python 3.x
- Libraries: pandas, matplotlib, numpy, scikit-learn

### Visualizations
- Population trends by country (2014-2024).
- Population predictions for 2024 and 2025.

### Example Output
- Predicted population for a sample country in 2024 and 2025.
- Visualization of actual vs predicted populations.
