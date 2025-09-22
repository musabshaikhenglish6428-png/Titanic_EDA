# Titanic Survival Analysis

## Project Overview
This project explores the **Titanic dataset** to understand which factors influenced passenger survival.  
It is a beginner-friendly project aimed at practicing **data cleaning, exploratory data analysis (EDA), and visualization** using Python.

---

## Dataset
- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)  
- The dataset contains details about passengers including age, gender, class, fare, and survival status.

---

## Key Steps in the Project
1. **Data Loading & Inspection**  
   - Loaded the dataset using **Pandas**  
   - Checked for missing values and data types  

2. **Data Cleaning**  
   - Filled missing values in `Age` and `Embarked`  
   - Dropped the `Cabin` column due to too many missing values  

3. **Feature Engineering**  
   - Created a new column `FamilySize = SibSp + Parch + 1` to analyze family influence on survival  

4. **Exploratory Data Analysis (EDA) & Visualizations**  
   - Survival distribution overall  
   - Survival by **gender**  
   - Survival by **passenger class**  
   - Age distribution  
   - Family size vs survival  
   - Fare vs survival  

5. **Insights and Observations**  
   - Women had a much higher survival rate than men  
   - 1st class passengers survived more than 2nd and 3rd class passengers  
   - Small families had slightly better survival chances  
   - Higher fare passengers had better survival rates  
   - Children and young adults had slightly higher survival probability  

---

## Tools & Libraries Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## Notebook
All visualizations and code are available in the notebook: **[Titanic_EDA.ipynb](Titanic_EDA.ipynb)**  

> Open the notebook to see the full analysis with plots and step-by-step insights.

