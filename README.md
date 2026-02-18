# Crime-Rate-Regression-Analysis

This project analyzes what factors are linked to crime rates across U.S. states using multiple regression models. The goal was to understand which social, economic, and demographic variables matter most, and to build a model that explains crime rates well while staying statistically sound.

We worked through model building step-by-step: starting with a full model, fixing multicollinearity, applying transformations, and then narrowing things down using variable selection. The final model highlights key predictors like education, poverty, youth demographics, and police spending.

## What’s in this project

- Exploratory data analysis (EDA)  
- Full regression model with diagnostics  
- Multicollinearity checks (VIF, correlations)  
- Box-Cox and log transformations  
- Backward elimination using AIC  
- Model comparison and interpretation  
- Hypothesis testing (male-to-female ratio effects)

## Tools & Methods

- R  
- Linear regression  
- Box-Cox transformation  
- AIC-based model selection  
- Residual diagnostics and influence analysis  

## Dataset

Crime and demographic data from U.S. states (1960), originally collected from government sources.

## Key takeaway

After testing several models, the final selected model shows that **education levels, poverty, youth demographics, and police spending** are strongly linked to crime rates. It balances good fit with interpretability.
