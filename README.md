# credit-risk-classification

## Overview
The purpose of this analysis is to assess the effectiveness of a logistic regression machine learning model in predicting credit risk. In the domain of lending and finance, correctly identifying the risk associated with a loan is crucial. An effective model can help financial institutions minimize losses by avoiding high-risk loans and can streamline the lending process by quickly approving low-risk loans.

## Model Performance Metrics
### Accuracy:
The model achieved an accuracy of approximately 99.37%. This indicates that the model is proficient in correctly identifying the overall loan status for most of the test data.

### Precision for High-risk Loans:
The model's precision for predicting high-risk loans is 0.84. This means when the model flags a loan as high-risk, it's correct 84% of the time. While high, there's room for improvement, as a 16% chance of misclassifying a healthy loan could lead to potential missed lending opportunities.

### Recall for High-risk Loans:
The recall score is 0.99, showcasing the model's capability to identify 99% of actual high-risk loans. A high recall is paramount in credit risk modeling, as failing to detect a high-risk loan can result in significant financial repercussions.

The logistic regression model, when trained with oversampled data, demonstrates exemplary performance, especially in detecting high-risk loans. The model's strengths lie in its high accuracy and recall for high-risk loans.

However, it's essential to consider the trade-offs:

While the model's high recall ensures most high-risk loans are identified, the precision indicates a potential for occasionally flagging healthy loans as high-risk. This could lead to missed lending opportunities but safeguards against potential bad loans.
Given the context of credit risk, where the cost of missing a high-risk loan could be much higher than erroneously classifying a healthy loan as high-risk, this model is commendable. Its strengths in risk detection combined with a generally high accuracy make it a strong candidate.

### Model Training & Evaluation:
Accuracy: The resampled model's accuracy remained impressive at 99.37%.
Precision and Recall: For high-risk loans, the model showcased a precision of 0.84 and a stellar recall of 0.99.


#### Recommendation:
I'd recommend the adoption of this model for a company's credit risk analysis, but with a continual assessment protocol. It's advisable to monitor the false positives and adjust the decision threshold if necessary, to find an optimal balance that aligns with the company's risk appetite and business goals.
