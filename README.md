# LifeExpectancyAnalysis

This project analyzes global life expectancy data to uncover the key socio-economic and health-related factors that influence the average lifespan across countries. The analysis is based on a publicly available dataset from the World Health Organization (WHO), covering over 150 countries and a range of development indicators.

#Project Objective
The primary goal of this project is to:

- Explore how various factors like GDP, education (schooling), healthcare expenditure, and disease prevalence correlate with life expectancy.

- Use exploratory data analysis (EDA) and a linear regression model to identify the strongest predictors of life expectancy.

- Create clear, actionable insights that could guide policy decisions or business strategies in global health and development.

#Dataset
- Source: WHO Life Expectancy Dataset

- Records: ~2,000 observations from 153 countries (2000–2015)

- Key Features:

      Life expectancy
      
      GDP
      
      Schooling
      
      Adult mortality
      
      Alcohol consumption
      
      HIV/AIDS prevalence

      BMI, thinness, income composition, etc.

#Tools & Technologies Used:
      - Python (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn)
      
      - Jupyter Notebook
      
      - Data Cleaning & Preprocessing
      
      - Linear Regression Modeling
      
      - Correlation Heatmaps and Visualization

#Key Steps in the Project:
1. Data Cleaning
Handled missing values via imputation and dropping.

Removed or filled null values in important columns (e.g., GDP, BMI, Schooling).

Ensured correct data types for numeric and categorical variables.

2. Exploratory Data Analysis (EDA)
Analyzed distribution of life expectancy globally.

Compared life expectancy across developed vs developing countries.

Plotted relationships between life expectancy and key indicators (e.g., schooling, healthcare spending, infant deaths).

3. Correlation Analysis
Built a correlation matrix to examine relationships between features.

Found strong positive correlations between schooling, income composition, GDP and life expectancy.

Found strong negative correlations between infant deaths, HIV/AIDS prevalence, and life expectancy.

4. Regression Modeling
Built a linear regression model using Scikit-learn to predict life expectancy.

Evaluated the model using:

R² Score

Mean Squared Error

Used this to identify which features are statistically significant predictors of life expectancy.

📌 Insights & Recommendations
Education (schooling), income equality, and healthcare access were among the top positive contributors to higher life expectancy.

Higher infant mortality and HIV/AIDS prevalence significantly decreased life expectancy.

Developing nations showed higher variability, suggesting broader inequalities in public health and income distribution.

These insights could help:

Governments prioritize education and healthcare investment.

NGOs and health orgs target interventions for maximum impact.

Insurance and health-tech companies build more accurate actuarial models.

#Future Work:
1. Extend the model to include time-series forecasting.
2. Apply machine learning models (e.g., Random Forest, XGBoost) for better predictive performance.
