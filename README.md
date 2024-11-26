# IS-6812-001-Fall-2024  
IS 6812-001 Fall 2024 MSBA Practice Project  

# Summary of Business Problem and Project Objective  

## Business Problem  
Home Credit is an international consumer finance provider focused on responsibly lending to individuals with little to no credit history. To continue serving the unbanked population, the company needs to confidently and accurately predict which prospective borrowers are likely to repay loans. Accurate loan repayment predictions enable Home Credit to foster financial inclusion while safeguarding the enterprise profitability necessary to sustain its mission.  

## Project Objective  
This project aims to build a predictive model that evaluates the loan repayment capability of individuals with limited or no traditional credit history. A successful model will allow Home Credit to assess applicants using alternative data, responsibly expanding credit access.  

# Solution to the Business Problem  
With an AUC score of 0.70311, our group's ensemble model reliably distinguishes between high-risk and low-risk borrowers. By integrating predictions from Random Forest, BART, Logistic Regression, and Extra Trees, this approach captures diverse aspects of the data for improved accuracy. The model offers Home Credit an opportunity to expand access to fair lending options for individuals who might otherwise have been excluded due to a lack of credit history.  

# The Business Value of the Solution  
By employing this predictive model, Home Credit has the potential to assess applicants based on alternative data, responsibly expanding credit access. This expansion will not only drive revenue growth for Home Credit but also balance increased loan approvals with low default rates. The result is growth that is both profitable and sustainable, ultimately enhancing Home Credit's competitive advantage.  

# Difficulties Encountered Along the Way  

## Exploratory Data Analysis  
  - Highly imbalanced target variable  
  - Missing values  
  - High cardinality in categorical variables  
  - Inconsistent factor levels  
  - Collinearity among predictors  
  - Potential outliers and noise  

## Modeling  
  - The dataset was extremely large, making it computationally intensive to train a model with more than 5% of the training data.  
  - A balanced subset of the data was created to efficiently build models, which likely reduced the model's potential predictive power.  

# My Contribution to the Project  
Working with three phenomenal teammates, my personal contributions to the project included:  
  - Conducting independent exploratory data analysis (EDA)  
  - Building several predictive models, including a majority classifier, logistic regression, penalized regression, and Naive Bayes  
  - Acting as a scribe for our team during the creation of the group modeling notebook  
  - Independently drafting several sections of the group modeling notebook, including "Main Takeaways"  
  - Creating a slide deck for the presentation, accessible and editable by all team members  
  - Coordinating group meetings, setting up Zoom sessions, and aligning schedules  

# Lessons Learned  

## Trying Various Applications of Multiple Models is Crucial  
Exploring different model types and configurations is essential. While some models perform well with minimal tuning, others require extensive parameter adjustments to maximize performance.  

## The Raw Data Alone is Not Sufficient — Feature Selection and Engineering are Key to Improving Model Performance  
Creating additional features captured meaningful patterns that better represented an applicant’s financial behavior and stability. Feature selection also played a critical role in improving model accuracy.  

## No Single Model is Likely to Solve Complex Business Problems — Ensemble Models Often Provide the Best Solution  
No single model effectively captured the complexity of the data. Some models, such as BART and LightGBM, offered strong individual results, but combining them in an ensemble improved predictive accuracy. Ultimately, the ensemble model outperformed any single algorithm by combining various predictions into a more robust result.  
