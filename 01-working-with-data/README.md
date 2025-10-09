# Working with Data

This module focuses on the **foundations of data handling and preprocessing** — the first and arguably most important
step in any machine learning pipeline.  
I explored how to load, clean, transform, and prepare datasets for analysis and modeling.

## Overview

In this module, I worked primarily with **Pandas** for data manipulation, using **Matplotlib** and **Seaborn** for
exploratory visualization.  
I explored public data repositories like:

- [HuggingFace Datasets](https://huggingface.co/datasets)
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/)
- [Kaggle Datasets](https://www.kaggle.com/datasets)
- Independent datasets hosted on GitHub

By completing hands-on exercises on datasets such as **Iris** and **World Population**, I learned how to handle the
entire preprocessing lifecycle — from data loading to feature engineering.

## Topics Mentioned

### 1. Loading and Inspecting Data

- Downloading datasets from various repositories
- Loading with `pd.read_csv()` and inspecting data with:
    - `df.info()`
    - `df.describe()`
    - `df.select_dtypes()`

### 2. Data Cleaning

- Identifying and removing **duplicates**
- Handling **missing values** (imputation, dropping)
- Addressing **skewness** and **outliers**
- Filtering and slicing data for complex use cases

### 3. Feature Preparation (module 2)

- **Scaling** numerical data (MinMaxScaler, StandardScaler)
- **Encoding** categorical features (LabelEncoder, OneHotEncoder)
- **Feature engineering** to extract meaningful patterns and ratios

### 4. Exploratory Visualization (module 2)

- Visualizing feature distributions
- Correlation heatmaps for numeric data
- Pairplots and boxplots for understanding relationships

## Datasets Used

| Dataset              | Description                                           | Source  |
|----------------------|-------------------------------------------------------|---------|
| **Iris**             | Classic dataset for pattern recognition and basic EDA | Unknown |
| **World Population** | Demographic and growth data for global analysis       | Kaggle  |

## Tools and Libraries

- **Python**
- **Pandas** for data wrangling
- **Matplotlib** and **Seaborn** for visualization
- **Scikit-learn** for preprocessing utilities

## Skills Gained

- Confidently load and inspect datasets of various types
- Clean and preprocess data efficiently with Pandas
- Handle missing, duplicate, and skewed data
- Scale and encode features for machine learning
- Perform initial exploratory analysis and visualization