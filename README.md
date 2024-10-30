# Lending Club Case Study
- This project involves a comprehensive Exploratory Data Analysis (EDA) of the Lending Club dataset with the objective of uncovering insights into how various consumer and loan attributes influence the tendency of borrowers to default. Lending Club, a peer-to-peer lending platform, provides a rich dataset encompassing numerous factors such as loan amounts, interest rates, employment information, credit history, and more.

## Objective:
The primary goal is to identify patterns, correlations, and trends that can indicate the likelihood of loan defaults. By analyzing these factors, we aim to provide valuable insights that could assist Lending Club in enhancing their risk assessment models, tailoring their lending strategies, and ultimately reducing the incidence of loan defaults.

## Key Aspects of Analysis:
- **Data Cleaning and Preprocessing:** Addressing missing values, outliers, and data inconsistencies to prepare a robust dataset for analysis
- **Univariate Analysis:** Examining individual variables such as loan amount, interest rates, annual income, and credit scores to understand their distribution and general characteristics.
- **Bivariate and Multivariate Analysis:** Exploring relationships between multiple variables, such as the impact of loan amount and income on default rates, or how credit scores and loan purposes interact to influence default likelihood.
- **Segmented Analysis:** Diving deeper into specific segments like loan terms, employment length, and home ownership status to analyze their effect on default tendencies.
- **Visualizations:** Employing various graphical techniques like histograms, box plots, scatter plots, and heat maps to visualize findings and trends effectively.
- **Insight Generation:** Drawing meaningful conclusions and actionable insights that can aid in decision-making processes for risk management and loan approval criteria.

## Conclusions
LendingClub has grown consistently over the period of years. However the defaults have also grown by the same rate. Few considerations that LC should have are as below:
- LendingClub should issue long term loans (60 months term) for Grade A cases only as other grades have higher tendency to default
- There is a higher tendancy to default when loan amount is hight. LC should perform higher due diligence in such cases
- Higher interest rates are levied to compensate for high risk loans. However there is a higher tendency to default when interest rates are higher. Implement stricter loan amount limits based on the borrower’s income and credit history. Lower limits for those with lower incomes or poorer credit scores could reduce default rates.
- LC should perform higher due diligence for the loans issued to borrowers from CA, FL and NY

## Technologies Used
- We used pandas for data analysis
- matplotlib.pyplot and seaborn were used for data visualization
- The entire analysis has been carried out in python 

## Acknowledgements
- This project was submitted as a part of AI ML Course by IIIT - B and upgrad

## Contact
Created by Rahul G and Vishwanath Madhu[@vismadhu] - feel free to contact us!
