# Heart Disease Dataset Analysis

This repository contains a Jupyter notebook for analyzing a heart disease dataset using Python. The analysis includes data exploration, visualization, and statistical insights.

## Dataset Description

The dataset (`heart.csv`) contains features related to heart health and a target variable indicating the presence or absence of heart disease. Key features include:

- `age`: Age of the patient
- `sex`: Sex of the patient (1 = male, 0 = female)
- `cp`: Chest pain type
- `trestbps`: Resting blood pressure (mm Hg)
- `chol`: Serum cholesterol level (mg/dl)
- `fbs`: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
- `restecg`: Resting electrocardiographic results
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise-induced angina (1 = yes, 0 = no)
- `oldpeak`: ST depression induced by exercise relative to rest
- `slope`: The slope of the peak exercise ST segment
- `ca`: Number of major vessels (0-3) colored by fluoroscopy
- `thal`: Thalassemia type (3 = normal, 6 = fixed defect, 7 = reversible defect)
- `target`: Presence of heart disease (1 = yes, 0 = no)

## Requirements

Ensure you have the following Python libraries installed:

```bash
pip install numpy pandas matplotlib seaborn
