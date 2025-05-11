# Diabetes Prediction Using Decision Trees

This project uses machine learning techniques to predict diabetes status based on various health metrics. The implementation uses a decision tree classifier to categorize patients into diabetic and non-diabetic groups.

## Project Overview

The Jupyter notebook `predicting_diabetes.ipynb` contains a complete data analysis workflow for diabetes prediction using decision trees. The project demonstrates the application of machine learning techniques to healthcare data.

## Dataset

The project uses the "Diabetes Prediction Dataset" from Kaggle, which is downloaded using the `kagglehub` library. This dataset contains various health metrics and patient information that can be used to predict diabetes status.

## Project Structure

The main components of this project include:

- `predicting_diabetes.ipynb`: Jupyter notebook containing the complete analysis
- Data acquisition using KaggleHub
- Data preprocessing and exploration
- Model building using decision trees
- Model evaluation and visualization


## Exploratory Data Analysis
### Class Distribution
The dataset exhibits a significant class imbalance, with most patients being non-diabetic (Class 0), fewer prediabetic (Class 1), and even fewer diabetic (Class 2). This imbalance may impact model performance.

![Distribution of Diabetes Classes](images/1.png "Histogram showing the distribution of diabetes classes")

### Correlation Analysis
The correlation matrix reveals relationships between features and the target variable (CLASS). Notably, HbA1c and BMI show strong positive correlations with diabetes status, making them key predictors.

![Correlation Matrix](images/2.png "Heatmap showing correlations between features and CLASS")



## Decision Tree Model
The decision tree classifier was trained on the preprocessed dataset. The tree primarily splits on features like HbA1c, BMI, and AGE, which are strong predictors of diabetes status as identified in the correlation analysis.

![Decision Tree](images/3.png "Decision tree structure for diabetes prediction")

## Requirements

To run this notebook, you'll need:

```

python 3.x
pandas
numpy
matplotlib
seaborn
scikit-learn
kagglehub
jupyter notebook

````

## Getting Started

1. Clone this repository
2. Install the required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn kagglehub jupyter
````

3. Open the Jupyter notebook:

   ```bash
   jupyter notebook "predicting_diabetes.ipynb"
   ```

## Features

* Data preprocessing and cleaning
* Exploratory data analysis with visualizations
* Feature selection and engineering
* Decision tree model implementation
* Model evaluation and performance metrics



## Acknowledgments

* Dataset provided by Kaggle user marshalpatel3558