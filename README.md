# Titanic_case_study
Exploratory data analysis of the Titanic passenger dataset to uncover survival patterns based on demographics and family structures.
# Titanic Survival Analysis

![Titanic](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fd/RMS_Titanic_3.jpg/800px-RMS_Titanic_3.jpg)

This project analyzes the Titanic passenger dataset to answer key questions about survival patterns. The Jupyter Notebook includes data cleaning, feature engineering, and visualizations to explore relationships between survival rates and factors like gender, family size, and fares.

## Key Questions Explored
1. Which gender had the highest survival rate?
2. Did passengers with larger families pay higher fares?
3. How did survival rates vary by age group?

## Dataset
- Source: Kaggle Titanic dataset (`train.csv`)
- Contains 891 passenger records with 12 features:
  - `PassengerId`, `Survived`, `Pclass`, `Name`, `Sex`, `Age`, `SibSp`, `Parch`, `Ticket`, `Fare`, `Cabin`, `Embarked`

## Data Cleaning Steps
1. **Handled missing values**:
   - Replaced null `Age` values with median age (28 years)
   - Dropped the `Cabin` column (77% missing data)
2. **Feature engineering**:
   - Created `familysize` = `SibSp` + `Parch` + 1
   - Calculated `fareperperson` = `Fare` / `familysize`

## Key Findings
### 1. Gender Survival Disparity
- **Female survival rate**: 74.2% (233 of 314 females survived)
- **Male survival rate**: 18.9% (109 of 577 males survived)

### 2. Family Size vs. Fares
| Family Size | Avg. Fare |
|-------------|-----------|
| 1 (Solo)    | $21.24   |
| 6           | $73.72   |
| 11          | $69.55   |

- Larger families paid higher total fares but **lower per-person costs**

### 3. Survival by Age Group
*(Analysis in progress - see notebook)*

## How to Run
1. Clone repository:
   ```bash
   git clone https://github.com/yourusername/titanic-analysis.git


### Key Files in Repository
- `TitanicCasestudy.ipynb`: Main analysis notebook
- `train.csv`: Titanic dataset
- `README.md`: Project documentation (this file)
- `requirements.txt`: Python dependencies

This structure provides clear documentation of the analysis process, findings, and technical setup for reproducibility. The README highlights the most impactful insights while making it easy for others to run the analysis themselves.
