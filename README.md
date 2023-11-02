# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
The purpose of this analysis is to create and evaluate a data model that predicts the creditworthiness of potential borrowers from peer-to-peer lending services. 
In other words, the goal is to develop a machine learning model that can assess whether a borrower is likely to repay a loan or pose a high risk of defaulting.

* Explain what financial information the data was on, and what you needed to predict.
The analysis aims to predict the "Loan Status" based on the provided financial information. It seeks to determine if a borrower is likely to
have a healthy loan (repaid on time) or if there is a higher risk of a loan default (high-risk loan). This prediction is vital for lending companies to 
make informed decisions about loan approvals and to manage their credit risk effectively. By accurately predicting loan outcomes, the company can minimize potential losses and
maintain a profitable lending business.

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
The variables that you were trying to predict were the f1-score, precision, balance accuracy, and y-test.

* Describe the stages of the machine learning process you went through as part of this analysis.
* Data Collection: The process began with the collection of relevant data, which likely included financial information about borrowers from peer-to-peer lending services. This data could have been obtained from various sources, cleaned, and organized for analysis.

Data Preprocessing: Before using the data for machine learning, it needed to be preprocessed. This stage likely involved handling missing values, dealing with outliers, and performing data normalization or scaling to ensure the data was in a suitable format for modeling.

Feature Selection/Engineering: Features (independent variables) were selected or engineered based on their relevance to predicting credit risk. Feature engineering may have included creating new variables or transforming existing ones to enhance the model's predictive power.

Data Splitting: The dataset was divided into a training set and a testing set. The training set was used to train the machine learning model, while the testing set was used to evaluate its performance.

Model Selection: A machine learning algorithm, in this case, likely logistic regression, was chosen as the model for predicting credit risk. The selection process may involve considering the nature of the problem, the dataset size, and the expected model performance.

Model Training: The selected model was trained using the training dataset. The model learned the relationships between the features and the target variable (Loan Status) to make predictions.

Model Evaluation: The model's performance was assessed using the testing dataset. Common evaluation metrics, such as accuracy, precision, recall, and the confusion matrix, were calculated to determine how well the model predicted both healthy and high-risk loans.

Model Tuning: If the model's performance was not satisfactory, hyperparameter tuning and optimization techniques might have been applied to improve its accuracy and robustness.

Report Generation: A credit risk analysis report, as requested, was generated to summarize the analysis, including the model's performance, key findings, and recommendations.

Recommendation: Based on the results, a recommendation was made regarding the use of the machine learning model for predicting credit risk. The recommendation considered the model's accuracy, precision, and recall, and whether it is suitable for the lending company's needs.

Deployment and Monitoring: If the model received a positive recommendation, it could be deployed in a real-world environment to aid in making lending decisions. Continuous monitoring and updating of the model may also be necessary to maintain its accuracy over time.

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
In the credit risk analysis described, the primary machine learning method used was logistic regression. Logistic regression is a commonly employed method for binary classification tasks, such as predicting whether a 
loan is a "Healthy Loan" (repaid on time) or a "High-Risk Loan" (defaulted or had a late payment).

## Results
The results that were found showed that the data that was gathered matched strongly with the models.

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
Accuracy: 0.99
Precision: macro 0.92, weighted: 0.99
Recall: macro 0.95, weight: 0.99


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
Accuracy: 0.99
Precision: macro 0.99, weighted: 0.99
Recall: macro 0.99, weight: 0.99
## Summary
Overall, model 2 was score better than model 1. 

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
Model 2 seems to perform the best based on the three categories (Accuracy, Precision, and Recall scores).
I know it performs the best because it has the highest percentages in all categories.
  
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
Performance helps with the problem that we are trying to solve but it will not be able to predict outside factors when it comes to loans defaulting.
With this being said I would be more comfortable using the stronger model but, with except the consequences when it comes to things I cannot predict.

If you do not recommend any of the models, please justify your reasoning.
