# LifeExpectancyAnalysis

This project analyzes global life expectancy data to uncover the key socio-economic and health-related factors that influence the average lifespan across countries. The analysis is based on a publicly available dataset from the World Health Organization (WHO), covering over 150 countries and a range of development indicators.

# Project Objective:

The primary goal of this project is to:

- Explore how various factors like GDP, education (schooling), healthcare expenditure, and disease prevalence correlate with life expectancy.

- Use exploratory data analysis (EDA) and a linear regression model to identify the strongest predictors of life expectancy.

- Create clear, actionable insights that could guide policy decisions or business strategies in global health and development.

- This project aims to answer the following key questions:

      - Does various predicting factors which has been chosen initially really affect the Life expectancy? What are the predicting variables actually affecting the life expectancy?
      - Should a country having a lower life expectancy value(<65) increase its healthcare expenditure in order to improve its average lifespan?
      - How does Infant and Adult mortality rates affect life expectancy?
      - Does Life Expectancy has positive or negative correlation with eating habits, lifestyle, exercise, smoking, drinking alcohol etc.
      - What is the impact of schooling on the lifespan of humans?
      - Does Life Expectancy have positive or negative relationship with drinking alcohol?
      - Do densely populated countries tend to have lower life expectancy?
      - What is the impact of Immunization coverage on life Expectancy?

# Dataset:

- Source: WHO Life Expectancy Dataset

- Records: ~2,000 observations from 153 countries (2000–2015)

- Key Features:

      - Life expectancy
      
      - GDP
      
      - Schooling
      
      - Adult mortality
      
      - Alcohol consumption
      
      - HIV/AIDS prevalence

      - BMI, thinness, income composition, etc.

# Tools & Technologies Used:

      - Python (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn)
      
      - Jupyter Notebook
      
      - Data Cleaning & Preprocessing
      
      - Linear Regression Modeling
      
      - Correlation Heatmaps and Visualization

# Key Steps in the Project:

**1. Data Cleaning:**
1. Handled missing values via imputation and dropping.

2. Removed or filled null values in important columns (e.g., GDP, BMI, Schooling).

3. Ensured correct data types for numeric and categorical variables.


**2. Exploratory Data Analysis (EDA) :**
1. Analyzed distribution of life expectancy globally.

2. Compared life expectancy across developed vs developing countries.

3. Plotted relationships between life expectancy and key indicators (e.g., schooling, healthcare spending, infant deaths).


**3. Correlation Analysis:**
1. Built a correlation matrix to examine relationships between features.

2. Found strong positive correlations between schooling, income composition, GDP and life expectancy.

3. Found strong negative correlations between infant deaths, HIV/AIDS prevalence, and life expectancy.


**4. Regression Modeling:**
1. Built a linear regression model using Scikit-learn to predict life expectancy.

2. Evaluated the model using:

            - R² Score

            - Mean Squared Error

3. Used this to identify which features are statistically significant predictors of life expectancy.


# Observations:

_**1. Life Expectancy is Higher in Developed Countries**_

- Countries marked as “Developed” have an average life expectancy significantly higher than “Developing” countries.
- Development level influences access to healthcare, nutrition, and infrastructure—key life-saving factors.

_**2. Education (Schooling) is a Strong Positive Predictor**_

- There’s a strong positive correlation between average years of schooling and life expectancy.
- Better-educated populations tend to have better health awareness, job opportunities, and healthcare access.

_**3. Countries with Higher GDP Live longer**_

- GDP per capita is positively correlated with life expectancy.
- Because Wealthier nations can invest more in public health, infrastructure, and education—improving quality of life.

_**4. Healthcare Expenditure Impacts Life Expectancy**_

- Countries that spend more on healthcare (as % of GDP) tend to have higher life expectancy.
- Direct indicator that public health spending saves lives, especially in early childhood and old age care.

_**5. HIV/AIDS and Infant Mortality are Major Threats**_

- High rates of HIV/AIDS drastically reduce life expectancy.
- Infant deaths are one of the top negative correlators.
- These are target areas for global health interventions.

_**6. Income Inequality Affects Life Expectancy**_

- “Income composition of resources” (how equally resources are distributed) is positively correlated with life expectancy.
- It’s not just how rich a country is, but how fairly the resources are shared.

_**7. Alcohol and Thinness Indicators Have Mixed Effects**_

- High alcohol consumption shows a weak but negative effect on life expectancy in developing nations.
- Malnutrition (thinness in children and adolescents) negatively affects long-term health outcomes.

_**8. Linear Regression Model Predicts Life Expectancy**_

- A simple regression model using features like GDP, schooling, and mortality can predict life expectancy fairly well.
- This model can be used to estimate how much improvement in a factor (like education) could improve life span.

  

# Conclusion:

1. Education (schooling), income equality, and healthcare access were among the top positive contributors to higher life expectancy.

2. Higher infant mortality and HIV/AIDS prevalence significantly decreased life expectancy.

3. Developing nations showed higher variability, suggesting broader inequalities in public health and income distribution.

4. The project highlights how public policy and global health programs can strategically focus on these variables to extend life spans and improve quality of life in both developing and developed countries. Additionally, a basic predictive model reinforces the importance of targeted investments in schooling, healthcare, and income equality.



These insights could help:

    - Governments prioritize education and healthcare investment.

    - NGOs and health orgs target interventions for maximum impact.

    - Insurance and health-tech companies build more accurate actuarial models.

# Future Work:

1. Extend the model to include time-series forecasting.
2. Apply machine learning models (e.g., Random Forest, XGBoost) for better predictive performance.
