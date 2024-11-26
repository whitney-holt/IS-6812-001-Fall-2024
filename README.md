# IS-6812-001-Fall-2024
IS 6812-001 Fall 2024 MSBA Practice Project

# Summary of business problem and project objective
## Business Problem
Home Credit is an international consumer finance provider focused on responsibly lending to people with little to no credit history. To continue serving the unbanked, the company needs to confidently and accurately predict which prospective borrowers are likely to repay loans. Accurate loan repayment predictions enable Home Credit to foster financial inclusion while safeguarding the necessary enterprise profitability to sustain its mission.

## Project Objective
This project aims to build a predictive model that evaluates loan repayment capability for individuals with limited or no traditional credit history. A successful model will allow Home Credit to assess applicants based on alternative data, expanding credit access responsibly.

# Solution to the business problem
With an AUC score of 0.70311, our group's ensemble model reliably distinguishes between high-risk and low-risk borrowers. By integrating predictions from Random Forest, BART, Logistic Regression, and Extra Trees, this approach captures diverse aspects of the data for improved prediction. The model offers Home Credit an opportunity to expand access to fair lending options for individuals who might otherwise have been excluded due to a lack of credit history.

# The business value of the solution
By employing this predictive model, Home Credit has the potential to assess applicants based on alternative data, expanding credit access responsibly. This expansion of credit access will drive revenue growth for Home Credit. The model allows for balance between increasing loan approvals and keeping default rates low, ensuring that the growth is both profitable and sustainable, ultimately providing Home Credit with an enhanced competitive advantage. 

# Difficulties encountered along the way

## Exploratory Data Analysis

  -  Highly Imbalanced Target Variable
  -  Missing Values
  -  High Cardinality in Categorical Values
  -  Inconsistent Factor Levels
  -  Collinearity Among Predictors
  -  Potential Outliers & Noise

## Modeling

  -  The data set is extremely large, and training a model with more than 5% of the training data set would be incredibly computationally intensive.
  -  A balanced subset of the data needed to be created in order to efficiently build models, but this likely decreased the model's potential predictive power.

# My contribution to the project
Working with 3 phenomenal teammates, my personal contributions to the project were:

  -  Conducting independent Exploratory Data Analysis (EDA)
  -  Building several predictive models, including a majority classifier, logistic regression, penalized regression, and Naive Bayes
  -  Acting as a scribe for our team when creating the group modeling notebook
  -  Independently drafting several sections of the group modeling notebook, including "Main Takeaways"
  -  Creating a slide deck for the presentation each team member could access and edit
  -  Coordinating group meetings, setting up zoom meetings and coordinating schedules

# Lessons Learned

## Trying various applications of multiple models is crucial
Exploring different model types and configurations is important; While some models perform well with minimal tuning, others require extensive parameter adjustments to maximize performance.

## The raw data alone is not sufficient — feature selection and engineering were key to improving model performance
Creating additional features captured meaningful patterns that better represented an applicant’s financial behavior and stability. Feature selection also played a role in improving model performance.

## No single model is likely to solve complex business problems - ensemble models often provide the best solution
No single model did a great job of capturing the complexity of the data. Some models, like BART and LightGBM, offered strong individual results, but combining them in an ensemble improved predictive accuracy. Ultimately, the ensemble model outperformed any single algorithm by combining various predictions into a single more robust prediction.
