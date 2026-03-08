# Smoking & Health Data Analysis

Exploratory Data Analysis (EDA) project investigating relationships between smoking behavior and cardiovascular health indicators using Python.

This project demonstrates core **data analyst skills** including data cleaning, feature engineering, statistical analysis, and visual storytelling.

---

## Project Overview

Smoking is a major contributor to cardiovascular disease. This project explores how smoking behavior correlates with key health metrics such as:

- Cholesterol
- Heart rate
- Blood pressure
- Age demographics
- Cigarette consumption

The goal is to transform raw health data into **insightful visualizations and analytical findings**.

---

## Dataset Features

The dataset includes the following fields:

| Column | Description |
|------|-------------|
| age | Age of the individual |
| sex | Gender |
| current_smoker | Whether the individual currently smokes |
| cigs_per_day | Average cigarettes smoked per day |
| chol | Cholesterol level |
| heart_rate | Heart rate |
| blood_pressure | Blood pressure (systolic/diastolic format) |

---

## Key Tasks Performed

### 1. Data Cleaning
- Standardized categorical fields
- Converted blood pressure into:
  - systolic_bp
  - diastolic_bp
- Handled missing values
- Corrected cigarette counts for non-smokers

### 2. Feature Engineering
Created new analytical features:

- Pulse Pressure
- Mean Arterial Pressure
- Age Groups
- Cholesterol Categories
- Composite Health Risk Score

### 3. Exploratory Data Analysis
Investigated relationships between smoking and health indicators.

Key comparisons include:

- Smoking status distribution
- Cigarettes per day distribution
- Cholesterol differences between smokers and non-smokers
- Heart rate vs cigarette consumption
- Blood pressure comparisons
- Age group smoking trends

### 4. Data Visualization

Clear and presentation-ready charts were created using **Matplotlib and Seaborn**:

- Demographic distributions
- Smoking prevalence
- Health metric comparisons
- Scatter relationships
- Correlation heatmap
- Age group analysis

---

## Key Insights

Some patterns observed during analysis:

- Smoking behavior varies across age groups.
- Heavy smoking correlates with increased cardiovascular risk indicators.
- Cholesterol and blood pressure patterns can differ between smokers and non-smokers.
- Feature engineering allows better segmentation of high-risk individuals.

*(Note: This analysis is exploratory and not intended for clinical conclusions.)*

---

## Visual Examples

The notebook includes visualizations such as:

- Smoking distribution
- Heart rate vs cigarettes per day
- Blood pressure comparisons
- Age group smoking trends
- Correlation heatmap of health metrics

---

## Technologies Used

Python  
Pandas  
NumPy  
Matplotlib  
Seaborn  
Jupyter Notebook

---

## Project Structure
