🚗 Motor Insurance Claim Prediction & Risk Analytics
Developed by Puttimej Praomsin 

Applied Mathematics Student | Aspiring Data Analyst

📌 Project Objective
The goal of this project is to develop a predictive model that estimates the probability of "Car Insurance Claims" based on a dataset of 10,000 customers. By leveraging historical data, this tool assists insurance companies in Risk Management and Pricing Optimization by identifying high-risk policyholders before they file a claim.

🛠 Tech Stack & Tools
Programming: Python (Pandas, NumPy, Matplotlib, Seaborn) 
Machine Learning: Scikit-learn (Logistic Regression, Random Forest Classifier) 
Optimization: RandomizedSearchCV for Hyperparameter Tuning
Visualization: Power BI Desktop

📊 Project Workflow
1. Data Cleaning & Preprocessing
Handling Missing Values: Applied Median Imputation to CREDIT_SCORE and ANNUAL_MILEAGE to maintain statistical consistency.
Feature Encoding: * Ordinal Encoding: Applied to hierarchical data such as AGE, INCOME, and DRIVING_EXPERIENCE.
Binary Mapping: Converted categorical variables like GENDER and VEHICLE_YEAR into numeric formats.
Feature Scaling: Implemented StandardScaler for Logistic Regression to ensure the model converges efficiently and coefficients are comparable.

2. Exploratory Data Analysis (EDA)
Identified that the overall Claim Rate is 31.33%.
Discovered that drivers aged 16-25 and those with <10 years of experience represent the highest risk segments.
Observed a negative correlation between Credit Score and claim probability, validating the "Financial Responsibility" hypothesis in insurance underwriting.

3. Machine Learning Modeling
Two models were evaluated to determine the best predictive performance:
Logistic Regression: Built as a statistical baseline using the sigmoid function
Random Forest: Optimized via RandomizedSearchCV to handle potential non-linear relationships and prevent overfitting.
<img width="421" height="395" alt="image" src="https://github.com/user-attachments/assets/2938491b-dbdb-49a4-8a87-2359487cee23" />
Key Insight: Logistic Regression performed exceptionally well (AUC = 0.90), indicating a strong linear relationship between the chosen features and the claim outcome.

📈 Power BI Dashboard Features
The interactive dashboard is structured into three main views:
Executive Summary: High-level KPIs including Total Policies, Claim Rate, and Revenue Risk.
Risk Profile Analysis: Deep dive into demographics (Age, Income, Marriage status) vs. Claim Outcomes.
ML Insights & Simulation: A "What-If" Parameter tool allowing users to simulate claim probabilities by adjusting inputs like Credit Score and Annual Mileage.

<img width="1000" height="800" alt="rf_feature_importance_tuned" src="https://github.com/user-attachments/assets/bd8dc406-7a83-40cc-99c6-cf8eb695384a" />


