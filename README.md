# Comparision of various Regression Algorithms to Predict the Efficacy of a Marketing campaign to open cash deposits


This practical application conducted as part of the UC Berkeley Professional Certificate Course in AI&ML compares various Classification based ML models in predicting the success rate in converting a targeted customer via a marketing campaign to open a cash deposit. 

# Objective 

## Business objective: 

Predict which customers are most likely to deposit so the marketing team can prioritize outreach and allocate resources efficiently to increase the number of deposits.

## ML objective: 

Learn a mapping from customer features to a binary response label and evaluate competing classifiers using cross-validation and a held-out test set.


# Approach 

The [technical paper](CRISP-DM-BANK.pdf) `Using data mining for Bank Direct Marketing: An Application of the CRISP-DM Methodology` serves as the reference for this application. The paper claims they have observed differences in mass marketing campaigns and targeted marketing campains and say that targeted marketing campaigns are more effective in increasing the cash deposits at a particular bank. The observations from this analysis are showin the Jupyter Notebook [here](prompt_III.ipynb). 

The following models are compared. 
- k-Nearest Neighbors (KNN)
- Logistic Regression
- Decision Tree
- Support Vector Machine (SVM)

The approach follows a typical applied ML project that is based on CRISP-DM(Cross Industry Standard Process for Data Mining)
1) Understanding the data
2) Preparing features
3) Training/Validating multiple models
4) Tune hyperparameters, and
5) Summarize findings for nontechnical stakeholders.

# Data

The application uses the [data](data/bank-additional-full.csv) for understanding the customers backgrounds and the campaign information to determine the success rate of converting a targeted customer into a bank customer with fixed deposits. In other words the application measures the efficacy of the following 4 classification models in predicting the success rate of customers for cash deposits. 

# Findings 



# Summary 


