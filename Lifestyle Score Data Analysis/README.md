# Lifestyle Score Data Analysis

## Overview

This project performs a comprehensive analysis of holistic health and lifestyle data, utilizing machine learning techniques to predict overall health status based on various lifestyle metrics. The analysis combines exploratory data analysis (EDA), feature importance analysis, and classification modeling using K-Nearest Neighbors (KNN).

## Objectives

- Analyze relationships between lifestyle factors and overall health
- Identify the most important features contributing to health scores
- Build a classification model to predict health status categories
- Optimize the KNN model to achieve the best accuracy
- Demonstrate predictive capability on sample data

## Dataset

**Source:** Holistic Health and Lifestyle Score Dataset (from Kaggle)

### Dataset Columns

| Column | Description | Range |
|--------|-------------|-------|
| **Physical_Activity** | Minutes of moderate to vigorous exercise per day | 0–120 |
| **Nutrition_Score** | Diet quality score based on nutrient density, balance, and variety | 0–10 |
| **Stress_Level** | Self-reported stress level (10 = very high) | 1–10 |
| **Mindfulness** | Minutes per day spent in meditation, journaling, or mindful activity | 0–60 |
| **Sleep_Hours** | Average hours of sleep per night | 3–10 |
| **Hydration** | Liters of water consumed per day | 0.5–5.0 |
| **BMI** | Body Mass Index | 18–40 |
| **Alcohol** | Units of alcohol consumed per week | 0–20 |
| **Smoking** | Cigarettes smoked per day | 0–30 |
| **Overall_Health_Score** | Composite overall health score (target for regression) | - |
| **Health_Status** | Categorical health classification (*Poor*, *Average*, *Good*) | - |

## Analysis Components

### 1. Data Exploration
- Load and inspect dataset using pandas
- Examine data types and basic statistics
- Review data shape and describe dataset characteristics
- Display first few rows to understand data structure

### 2. Feature Importance Analysis
- Train a Random Forest Regressor model
- Extract feature importance scores
- Identify which lifestyle factors most strongly influence overall health scores
- Sort and visualize feature importance

### 3. Health Status Classification
- Encode categorical health status labels using LabelEncoder
- Split data into training (80%) and test (20%) sets with stratification
- Scale features using StandardScaler for KNN optimization
- Train K-Nearest Neighbors classifier

### 4. Model Optimization
- Evaluate KNN accuracy across multiple k values (1-20)
- Plot accuracy vs k to identify the optimal neighborhood size
- Select best k value (k=13 achieved best performance)
- Compute confusion matrix and classification report

### 5. Prediction on New Data
- Demonstrate prediction on a sample health profile
- Show predicted vs actual health status
- Display prediction probabilities for each class
- Calculate model confidence for predictions

## Technologies & Libraries

- **pandas**: Data manipulation and analysis
- **numpy**: Numerical computations
- **scikit-learn**: Machine learning (Random Forest, KNN, preprocessing)
  - `RandomForestRegressor`: Feature importance analysis
  - `KNeighborsClassifier`: Classification modeling
  - `train_test_split`: Data splitting
  - `StandardScaler`: Feature scaling
  - `LabelEncoder`: Categorical encoding
  - Metrics: `accuracy_score`, `confusion_matrix`, `classification_report`
- **matplotlib**: Data visualization

## Key Findings

- The analysis identifies which lifestyle factors contribute most significantly to overall health
- KNN with k=13 neighbors provides optimal classification accuracy
- Three health status categories (Poor, Average, Good) can be predicted based on lifestyle metrics
- Sample prediction demonstrates the model's ability to classify new individuals

## How to Use

1. **Load the data**: Execute initial cells to load the CSV file
2. **Explore the data**: Review summary statistics and data structure
3. **Analyze features**: Examine feature importance rankings
4. **Train and optimize**: Run KNN models with different k values
5. **Make predictions**: Use the trained model to predict health status for new data

## Workflow

```
1. Data Loading & Inspection
   ↓
2. Data Cleaning (Rounding values)
   ↓
3. Exploratory Data Analysis
   ↓
4. Feature Importance Analysis (Random Forest)
   ↓
5. Data Preprocessing (Encoding, Scaling, Splitting)
   ↓
6. KNN Model Optimization (k=1 to 20)
   ↓
7. Best Model Evaluation (k=13)
   ↓
8. Sample Prediction & Confidence Assessment
```

## Model Performance

- **Optimal k value**: 13
- **Evaluation Metrics**: 
  - Accuracy on test set
  - Confusion matrix analysis
  - Per-class precision, recall, and F1-scores
  - Prediction probability (confidence)

## Insights

- Lifestyle factors have varying degrees of impact on overall health
- K-Nearest Neighbors classification provides interpretable health status predictions
- The model can identify health profiles similar to the query individual
- Scaling features is crucial for KNN performance

## Notes

- Data values are rounded to 2 decimal places for consistency
- Stratified train-test split ensures class distribution is maintained
- StandardScaler is essential for KNN to prevent distance bias toward larger-scale features
- The sample prediction demonstrates moderate health status with specific lifestyle metrics

## Author & License

This analysis is part of the Data Analysis with Python learning project.

---

**Last Updated**: 2025  
**Dataset**: Holistic Health and Lifestyle Score Dataset
