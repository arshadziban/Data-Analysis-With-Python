# Quranic Data Analysis Project

This project leverages Python to perform data analysis and visualization on Quranic data, focusing on Surah characteristics and clustering based on Ayah counts. The analysis includes insights into Surah lengths, clustering, cumulative counts, and symmetric patterns.



## Table of Contents
1. [Overview](#overview)  
2. [Technologies Used](#technologies-used)  
3. [Features](#features)  
4. [Data Visualizations](#data-visualizations)  
5. [Clustering Analysis](#clustering-analysis)  
6. [Setup Instructions](#setup-instructions)  
7. [Future Enhancements](#future-enhancements)  



## Overview
This project analyzes a dataset containing Surah information from the Quran, including the total number of Ayahs for each Surah. Through visualizations and clustering, the project uncovers patterns and relationships, providing an engaging look at the structure of the Quran.



## Technologies Used
- **Python Libraries**:  
  - `pandas`: For data manipulation and analysis  
  - `numpy`: For numerical operations  
  - `matplotlib` & `seaborn`: For data visualization  
  - `scikit-learn`: For clustering with K-Means  

- **Google Colab**: For executing Python code  
- **GitHub**: To share and maintain the project  



## Features
1. **Data Summary**:  
   - Displays Surah number, name, and Ayah counts.  
   - Calculates cumulative Ayah counts.  
2. **Visualizations**:  
   - Line plot showing Surah numbers vs. total Ayahs.  
   - Area chart for cumulative Ayahs.  
   - Swarm plot of Surah numbers and total Ayahs.  
3. **Clustering Analysis**:  
   - Categorizes Surahs into `short`, `medium`, and `long` based on Ayah counts using K-Means.  
4. **Symmetric Matching**:  
   - Compares Ayah counts between Surahs in reverse order.  
5. **Data Insights**:  
   - Identifies interesting patterns in Quranic structure.  



## Data Visualizations

### Line Plot
A line graph visualizing Surah numbers vs. total Ayahs.  

### Area Chart
An area plot showing cumulative Ayah distribution over Surahs.  

### Swarm Plot
A swarm plot providing a detailed view of Ayah counts per Surah.  

## Clustering Analysis
Using K-Means, Surahs are grouped into clusters based on their Ayah counts:  
- **Short Surahs**: Low Ayah count (e.g., `Al-Fatihah`)  
- **Medium Surahs**: Moderate Ayah count (e.g., `Al-Maidah`)  
- **Long Surahs**: High Ayah count (e.g., `Al-Baqarah`)  




## Setup Instructions
1. **Environment Setup**:  
   Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

2. **Dataset**:  
   Ensure the dataset (`surah_info.csv`) is placed in the appropriate directory, such as `/content/drive/MyDrive/`.

3. **Run the Code**:  
   Execute the provided Python script in Google Colab or locally using Jupyter Notebook.


