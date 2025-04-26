**Business Problem**

Many individuals, especially those who are unbanked or underbanked, face significant challenges when trying to access loans from traditional financial institutions. This is often due to a lack of formal credit history, which prevents them from building credit and owning property, further limiting their financial opportunities. Home Credit seeks to address this issue by offering credit services to underserved populations. However, accurately predicting the risk of loan defaults is essential to balancing financial accessibility with sustainable lending practices. By utilizing predictive analytics, Home Credit can better identify low-risk borrowers, increase revenue, and minimize losses associated with defaults, ultimately improving both access to credit and financial stability for its customers.

**Project Objective**

The goal of this project is to develop a predictive model that assists Home Credit in assessing the likelihood of loan applicants defaulting on their payments. The model will analyze alternative data sources—such as transactional history, demographic information, and telecommunications data—to improve risk assessment for individuals who have little to no traditional credit history. By enhancing the ability to evaluate these applicants, Home Credit can make more informed lending decisions, providing responsible financial solutions while also promoting greater financial inclusion.

**Proposed Solution**

Through exploratory data analysis (EDA) and feature engineering, we identified that utilizing an auxiliary dataset was key to identifying creditworthy applicants. By merging and analyzing data from multiple sources, we were able to generate more accurate predictions of default risk. This approach allows Home Credit to gain deeper insights into applicants who might otherwise be overlooked by traditional credit scoring systems.

**Contribution**

In this project, I played a key role in creating the joined dataset, which provided the foundation for our model. I also built the logistic regression model, which served as our baseline for evaluating the performance of future models. Additionally, I contributed to fine-tuning the model, improving its accuracy over time, and collaborated in the cleaning and feature engineering processes to ensure the data was well-structured for analysis. This hands-on involvement helped ensure the model's effectiveness and performance throughout the project.

[Home Credit Project - EDA](https://github.com/lindsahlander/Data-Projects/blob/main/HomeCredit_EDA.Rmd)

This file explores the datasets from the Kaggle Home Credit competition, focusing on exploratory data analysis (EDA). It includes data cleaning, visualization, and an in-depth look at various features to better understand the factors influencing loan defaults.

[Home Credit Project - EDA Joined](https://github.com/lindsahlander/Data-Projects/blob/main/HomeCredit_EDA_Joined.Rmd)

Building on the initial EDA, this file merges different datasets to provide a more comprehensive view of the data. It includes further analysis to uncover hidden relationships and insights that can enhance model performance in predicting loan defaults.

[Home Credit Project - Logistic Regression Model](https://github.com/lindsahlander/Data-Projects/blob/main/HomeCredit_LR_Model.Rmd)

This file builds a logistic regression model to predict loan defaults using the Home Credit dataset. The project involves data cleaning, feature exploration, and model evaluation. The goal is to help Home Credit assess the risk of loan defaults based on factors like income, credit score, and asset ownership.

Using key predictors found from previous exploratory data analysis such as income, credit history, and asset ownership, my logistic regression model predicts the likelihood of default with 72% accuracy. This model can assist lenders in making data-driven decisions, potentially reducing financial risk and improving loan approval processes.

**Business Value**

With our model, Home Credit would be able to accurately predict an additional 29% of applicants who would have otherwise been denied credit based solely on their application data. This improvement in risk prediction could potentially generate an estimated $61 million in additional revenue. By enabling Home Credit to extend credit to more qualified individuals, the model enhances both financial inclusion and profitability for the company.

**Challenges Faced**

This project presented several challenges along the way. One significant roadblock was the large size of the application data, which contained over 300,000 applicants. This created computational challenges that we mitigated by downsampling the dataset and removing unnecessary variables. We also cleaned the data by eliminating predictors with too many missing values, ensuring the dataset was both manageable and meaningful for modeling. Additionally, during the Kaggle submission process, we encountered a submission issue that initially caught us off guard. However, through diligent troubleshooting, we were able to identify and resolve the issue, ensuring our submission was successful.



