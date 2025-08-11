# task-5-EDA
Performed Exploratory Data Analysis (EDA) on the Titanic dataset using Python (Pandas, Matplotlib, Seaborn) to clean data, handle missing values, and visualize patterns. Analyzed passenger demographics, survival rates, and correlations to uncover key insights for further modeling.
## 🎯 Objectives
- Understand the dataset structure and features
- Clean missing and irrelevant data
- Analyze data through visualizations
- Identify trends and patterns related to passenger survival

## 🛠 Tools & Libraries
- **Python**
- **Pandas** (Data manipulation)
- **Matplotlib & Seaborn** (Data visualization)
- **Jupyter Notebook**

## 🔍 Steps Performed
1. **Data Cleaning**
   - Removed irrelevant columns (`Cabin`, `Ticket`)
   - Filled missing `Age` values with median
   - Filled missing `Embarked` values with mode
   - Converted categorical columns (`Survived`, `Pclass`) to category type
   - Removed duplicate rows

2. **Exploratory Data Analysis**
   - **Univariate Analysis:** Age distribution, Fare distribution
   - **Bivariate Analysis:** Survival rate by gender and passenger class
   - **Correlation Analysis:** Heatmap and Pairplot
   - **Outlier Detection:** Boxplots for numerical features

3. **Key Insights**
   - Most passengers were between **20–40 years old**
   - **Females** had a higher survival rate than males
   - **1st Class** passengers had better survival chances
   - Higher fare was associated with higher survival probability
   - Missing data was found in `Age` and `Embarked`

## 📂 Deliverables
- **Jupyter Notebook:** Code + Visualizations + Observations
- **PDF Report:** Summary of findings

## 📊 Outcome
This EDA helped in understanding how passenger demographics and ticket details influenced survival chances. The insights gained can be used for further predictive modeling.

---
