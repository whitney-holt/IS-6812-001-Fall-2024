# IS-6812-001-Fall-2024
IS 6812-001 Fall 2024 MSBA Practice Project

# Summary of business problem and project objective

## Business Problem
Home Credit is an international consumer finance provider focused on responsibly lending to people with little to no credit history. To continue serving the unbanked, the company needs to confidently and accurately predict which prospective borrowers are likely to repay loans. Accurate loan repayment predictions enable Home Credit to foster financial inclusion while safeguarding the necessary enterprise profitability to sustain its mission.

## Project Objective
This project aims to build a predictive model that evaluates loan repayment capability for individuals with limited or no traditional credit history. A successful model will allow Home Credit to assess applicants based on alternative data, expanding credit access responsibly.

# Solution to the business problem


# Difficulties encountered along the way

# The business value of the solution

# My contribution to the project

Working with 3 phenominal teammates, my cotributions to the project were:

  -  Conducting independent Exploratory Data Analysis (EDA)
  -  Building several predictive models, including: majority classifier, logistic regression, penalized regression, and Naive Bayes
  -  Acting as a scribe for our team when creating the group modeling notebook
  -  Independently drafting several sections of the group modeling notebook, including "Main Takeaways"
  -  Creating a slide deck for the presenation each team member could access and edit
  -  Coordinating group meeings, setting up zoom meetings and coordinating schedules

# What I learned in the project

## Trying various applications of multiple models is crucial

Through the modeling process, it became clear that exploring different model types and configurations is important; While some models may perform well with minimal tuning, others require extensive parameter adjustments or specialized techniques to bring out their full potential.

## The raw data alone is not sufficient — feature selection and engineering were key to improving model performance

By creating additional features were able to capture meaningful patterns that better represented an applicant’s financial behavior and stability. Feature selection also played a role in improving model performance.

## No single model is likely to solve complex business problems - ensemble models often provide the best solution

Throughout testing, it became evident that no single model did a great job of capturing the complexity of the data. Some models, like BART and LightGBM, offered strong individual results, but combining them in an ensemble added predictive accuracy. Ultimately, the ensemble model outperformed any single algorithm by combining various predictions into a single more robust prediction.

## Including additional data does not always have a high return on investment

The inclusion of several feature engineered columns from previous_application.csv may have marginally increased model performance and provided a more comprehensive view of each individual. This marginal increase may not be worth the additional time and effort required to include the columns.
