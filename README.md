# US Company Bankruptcy Prediction Dataset

## Problem Motivation
The motivation behind the U.S. Company Bankruptcy Prediction Dataset revolves around the critical need to predict the financial distress or bankruptcy of companies. This is an important aspect for investors, creditors, policymakers, and other stakeholders in the business world for several reasons:
1. Risk Management and Investment Decisions
2. Early Warning for Companies
3. Financial Market Stability
4. Policy Making and Economic Research
5. Credit Scoring and Financial Services
6. Legal and Compliance Implications
7. Supply Chain Management
8. Employee and Stakeholder Interests
In summary, the U.S. Company Bankruptcy Prediction Dataset serves as a crucial tool for various stakeholders to anticipate financial distress in companies, enabling proactive measures in investment, policy making, risk management, and strategic planning.


## Analysis Methodology
In the context of the U.S. Company Bankruptcy Prediction Dataset, the analysis methodology include the following stages:
1. Data Collection and Preparation:
    1. Data Collection: A novel dataset for bankruptcy prediction related to American public companies  listed on the New York Stock Exchange and NASDAQ is provided. The dataset comprises accounting data from 8,262 distinct companies recorded during the period spanning from 1999 to 2018.
    2. Data Cleaning: The data cleaning process for the US Company Bankruptcy Prediction Dataset involved three steps:
        1. Null Value Removal: Missing values were identified and eliminated to maintain data accuracy and integrity.
        2. Qualitative to Quantitative Transformation: Categorical data was converted into numerical format, making it compatible with statistical and machine learning models.
        3. Column Header Revision: Column names (X1 to X18) were standardized for clarity and consistency, enhancing the dataset's usability and readability.

2. Exploratory Data Analysis (EDA): Conducted the analyses like visualization, identifying patterns and correlations. The following analyses were conducted:
    1. Yearly Revenue and Yearly Liability Against Year.
    2. Yearly Net Sales, Yearly Gross Profit Against Year.
    3. Company Status Distribution.
    4. Total Revenue Trend Over the Year for Top 5 Companies.
    5. Depreciation Over the Year.
    6. Relation Between Total Income and Market Value for Top 10 Companies.

### Analysis result : 
It is an unbalanced data with 96% of data having an 'active' status, hence the prediction accuracy might be highly biased.

3. Models Used: KNN, Xgboost, Random Forest.

## Results and Conclusions
Random forest model produced the best results among the three models we used for analysis. The model predicts the output for ‘failed’ status with an accuracy of 59 percent and for the ‘active’ status with an accuracy of 98 percent. 
