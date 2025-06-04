# Titanic Case Study

![Titanic](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fd/RMS_Titanic_3.jpg/800px-RMS_Titanic_3.jpg)

This project analyzes the Titanic dataset to answer key questions about passenger survival, fare trends, and demographic patterns. Using Python, pandas, and matplotlib, the notebook explores the relationships between gender, family size, age group, and survival rates.

## Project Objectives

- **Determine which gender had the highest survival rate**
- **Analyze if passengers with larger families paid higher fares**
- **Examine how survival rates varied by age group**

## Data Source

The analysis uses the classic Titanic dataset (`train.csv`), which contains information about passengers such as age, sex, fare, family relations, and survival status.

## Key Steps

1. **Data Loading and Cleaning**
   - Load data using pandas
   - Fill missing age values with the median
   - Drop the 'Cabin' column due to excessive missing values

2. **Exploratory Data Analysis**
   - Calculate survival rates by gender
   - Compute average fare by family size
   - Divide passengers into age groups and analyze survival rates

3. **Visualization**
   - Plot trends of average fare by family size
   - Visualize survival rates across different age groups

## How to Run

1. Ensure you have Python installed (preferably 3.7+).
2. Install required libraries:
   ```
   pip install pandas matplotlib
   ```
3. Place `train.csv` in the project directory.
4. Open `TitanicCasestudy.ipynb` in Jupyter Notebook or VS Code.
5. Run the notebook cells sequentially to see the analysis and visualizations.

## Results Summary

- **Females had a much higher survival rate than males.**
- **Families with more members paid higher total fares, but the fare per person was lower.**
- **Survival rates varied by age group, with children and some adult groups having higher chances of survival.**

## Files

- `TitanicCasestudy.ipynb` — Main analysis notebook
- `train.csv` — Titanic dataset (not included; download from [Kaggle](https://www.kaggle.com/c/titanic/data))

---

**Author:**  
Nilesh Sharma 
**Date:**  
*June 2025*