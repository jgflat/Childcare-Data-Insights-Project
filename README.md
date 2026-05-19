# Childcare Data Insights Project

## Overview
This project analyzes national childcare pricing data in the United States to understand affordability trends, regional differences, and the relationship between childcare costs and household income.

The analysis focuses on:
- Infant, toddler, and preschool childcare costs
- Cost burden as a percentage of household income
- Geographic differences across states and counties
- Time-based trends in childcare affordability
- Relationship between childcare costs and socioeconomic indicators

---

## Important Note About the Dataset
The original dataset used in this project (`nationaldatabaseofchildcareprices.xlsx`) is large and stored locally during development. Due to file size limitations, it is not included in this GitHub repository.

Instead, a cleaned and processed dataset is provided:

- `childcare_cleaned_long.csv`

This file contains transformed and analysis-ready data used for visualization and modeling.

---

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## How to Run This Project

### Option 1 (Recommended)
Run the notebook locally with the original dataset:

1. Place `nationaldatabaseofchildcareprices.xlsx` in the same folder as the notebook
2. Run all cells in order

### Option 2 (GitHub Version)
Use the provided cleaned dataset:

```python
df = pd.read_csv('childcare_cleaned_long.csv')
```

Note: Some original transformations and visualizations may differ when using the cleaned dataset.

---

## Key Analyses
- Data cleaning and preprocessing
- Affordability calculations (cost as % of income)
- Correlation analysis between childcare costs and household income
- Geographic comparison across states and counties
- Time series trends in childcare costs
- Visualization of affordability thresholds

---

## Key Insights
- Infant care represents the highest financial burden for families
- Childcare costs vary significantly by state and county
- In many regions, childcare consumes a large portion of household income
- Cost growth has increased faster than income in several areas
- Regional disparities highlight economic inequality in childcare access

---

## Files in This Repository
- `childcare_data_insights.ipynb` → Full analysis notebook
- `childcare_cleaned_long.csv` → Cleaned dataset for analysis

---

## Author
Jeremy Granflaten
