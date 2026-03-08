
# Smoking & Health Data Analysis

Exploratory Data Analysis (EDA) project investigating the relationship between smoking behavior and cardiovascular health indicators using Python.

This project demonstrates core **data analyst skills** including:

- Data cleaning
- Feature engineering
- Exploratory data analysis
- Data visualization
- Insight communication

The goal is to transform raw health data into **clear analytical insights and visualizations suitable for a data analyst portfolio.**

---

# Project Overview

Smoking is a major contributor to cardiovascular and respiratory diseases. This project analyzes health-related variables to explore patterns between smoking behavior and key health indicators such as:

- Cholesterol levels
- Heart rate
- Blood pressure
- Age distribution
- Cigarette consumption

The analysis focuses on comparing **smokers vs non-smokers** and identifying patterns across demographic groups.

---

# Dataset

The dataset used in this project is publicly available on Kaggle.

**Source:**  
Smoker's Health Data – Kaggle  
https://www.kaggle.com/datasets/jaceprater/smokers-health-data

The dataset was curated by **Jace Prater** and filtered from a larger hypertension risk dataset to explore the potential health effects of smoking compared to non-smokers. :contentReference[oaicite:0]{index=0}

---

# Dataset Features

| Column | Description |
|------|-------------|
| age | Age of the individual |
| sex | Gender |
| current_smoker | Whether the individual currently smokes |
| cigs_per_day | Average number of cigarettes smoked per day |
| chol | Cholesterol level |
| heart_rate | Heart rate |
| blood_pressure | Blood pressure (systolic/diastolic format) |

---

# Project Objectives

The main goals of this analysis were to:

1. Clean and preprocess the dataset
2. Engineer useful analytical features
3. Explore relationships between smoking and health metrics
4. Create clear visualizations for storytelling
5. Identify patterns and potential risk indicators

---

# Data Processing Steps

## 1. Data Cleaning

- Standardized categorical fields
- Handled missing values
- Converted blood pressure into numeric columns
- Corrected cigarette counts for non-smokers

Blood pressure was transformed into:

- **systolic_bp**
- **diastolic_bp**

This made it possible to perform numerical analysis on cardiovascular indicators.

---

# Feature Engineering

Several new variables were created to improve analysis:

| Feature | Description |
|------|-------------|
| pulse_pressure | Difference between systolic and diastolic BP |
| mean_arterial_pressure | Average arterial pressure estimate |
| age_group | Age segmentation for demographic analysis |
| chol_category | Cholesterol health category |
| health_risk_score | Composite indicator combining key health metrics |

These features help identify **higher-risk health patterns**.

---

# Exploratory Data Analysis

The analysis investigates relationships between smoking behavior and health indicators.

Key comparisons include:

- Smoking distribution in the dataset
- Cigarettes per day analysis
- Cholesterol differences between smokers and non-smokers
- Heart rate vs cigarette consumption
- Blood pressure comparison
- Age-group smoking patterns

---

# Visualizations

The project includes multiple portfolio-quality charts built using **Matplotlib and Seaborn**, including:

- Demographic distributions
- Smoking prevalence
- Cigarettes per day distribution
- Heart rate vs cigarette consumption
- Blood pressure comparisons
- Age group analysis
- Correlation heatmap

These visuals are designed to be **clear, readable, and presentation-ready**.

---

# Key Insights

Some exploratory patterns observed:

- Smoking rates vary across age groups.
- Higher cigarette consumption may align with increased cardiovascular risk indicators.
- Cholesterol and blood pressure patterns differ between smokers and non-smokers.
- Feature engineering helps identify individuals with higher potential health risk.

Note:  
This analysis is **exploratory and not intended for medical conclusions**.

---

# Technologies Used

Python  
Pandas  
NumPy  
Matplotlib  
Seaborn  
Jupyter Notebook  

---

# Project Structure

```

smoking-health-analysis/
│
├── smoking_health_portfolio_project.ipynb
├── smoking_health_data_final.csv
├── cleaned_smoking_health_data.csv
└── README.md

````

---

# How to Run the Project

### 1 Clone the repository

```bash
git clone https://github.com/yourusername/smoking-health-analysis.git
````

### 2 Navigate to the project folder

```bash
cd smoking-health-analysis
```

### 3 Install dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4 Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5 Open the notebook

```
smoking_health_portfolio_project.ipynb
```

---

# Skills Demonstrated

This project highlights important **data analyst competencies**:

* Data cleaning and preprocessing
* Feature engineering
* Exploratory data analysis
* Data visualization
* Statistical reasoning
* Insight communication
* Portfolio-ready documentation

---

# Future Improvements

Potential extensions for this project:

* Logistic regression predicting smoking status
* Cardiovascular risk prediction model
* Interactive dashboard (Tableau or Power BI)
* Machine learning classification models
* Larger healthcare datasets

---

# Author

Data Analyst Portfolio Project

If you found this project useful, feel free to ⭐ the repository.


