**🏡 Regression Analysis of King County Housing Prices**

**📌 Overview**

This project is a regression analysis lab report conducted at the Transport and Telecommunication Institute (TSI) in collaboration with UWE Bristol. The dataset contains 21,597 housing records from King County, Washington (including Seattle), with 18 variables describing property features. The primary goal is to predict house prices using statistical and machine learning methods.

**📂 Contents**

The report is organized into the following sections:

Introduction – Dataset description and objectives

Data Cleaning – Handling missing values, type conversions, and feature consistency

Dependent Variable Statistics – Summary statistics of house prices

Distribution Analysis – Histogram and skewness of price data

Exploratory Data Analysis (EDA) – Boxplots, scatterplots, and LOESS smoothing

Correlation Analysis – Pairplots and heatmaps to identify strong predictors

Feature Engineering – Dummy variables, transformations, and new features (e.g., house_age, lot_to_living_ratio)

Linear Regression Modeling – Model estimation, goodness of fit, coefficient significance

Residual Analysis – Histograms, scatterplots, and outlier detection

Model Refinement – Outlier removal, stepwise elimination of insignificant variables

Prediction Analysis – Confidence intervals and performance comparison

Random Forest Regression – Non-linear modeling for improved accuracy

Conclusion – Insights and pricing model summary

⚙️** Methodology**


Tools Used: Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels)

**Techniques Applied:**

Linear regression

Feature engineering (dummy encoding, ratio variables)

Outlier detection and removal

Stepwise regression

Random forest regression for comparison

**📊 Key Findings**
Strong predictors of price:

sqft_living (living area)

grade (construction quality)

bathrooms

sqft_living15 (recent living area)

Weak predictors: lot size (sqft_lot), basement size (sqft_basement)

Outliers: Ultra-luxury homes skew the distribution, requiring careful handling

**Model Performance:**

Linear regression explains much of the variance but suffers from heteroscedasticity

Random forest regression improves predictive accuracy by capturing non-linear effects

**🚀 How to Use**


Open the report (st86860 Anjali Shibu lab 3 regression analysis.pdf)

Follow the step-by-step methodology for data cleaning, EDA, and regression modeling

Replicate the analysis using the provided dataset (King County housing data)

Extend the model with additional features or alternative ML algorithms

**📌 Conclusion**


This analysis demonstrates how statistical regression and machine learning can be applied to real estate pricing. The final pricing model highlights the importance of living area, quality grade, and bathrooms as key drivers of housing prices in King County.
