# credit-risk-classification

The analysis provides a comprehensive evaluation of the logistic regression model's performance. It assesses how well the model predicts both healthy and high-risk loans, both before and after data resampling to address class imbalance. The provided classification reports and metrics offer insights into the model's precision, recall, and overall effectiveness in distinguishing between the two loan categories.
For Label 0 (Healthy Loan):

Precision: 1.00
Recall: 0.99
F1-Score: 1.00
Support: 15,001
The model predicts healthy loans (label 0) very well, with high precision, recall, and F1-score. The precision of 1.00 indicates that when it predicts a loan as healthy, it's highly likely to be correct. The recall of 0.99 shows that the model correctly identifies most of the healthy loans. The F1-score of 1.00 is excellent and indicates a good balance between precision and recall.

For Label 1 (High-Risk Loan):

Precision: 0.85
Recall: 0.99
F1-Score: 0.92
Support: 507
The model also performs well for high-risk loans (label 1). It has a relatively high precision of 0.85, meaning that when it predicts a loan as high-risk, it's correct most of the time. The recall of 0.99 indicates that it correctly identifies most of the high-risk loans. The F1-score of 0.92 is quite good and represents a balanced trade-off between precision and recall.

In summary, the logistic regression model, fit with oversampled data, performs very well for both healthy loans (label 0) and high-risk loans (label 1). It achieves high accuracy, precision, recall, and F1-scores for both classes, demonstrating its effectiveness in distinguishing between these two classes.

After resampling the data, I ran the classification report again.

For Label 0 (Healthy Loan):

Precision: 1.00
Recall: 1.00
F1-Score: 1.00
Support: 15,001
The model predicts healthy loans (label 0) extremely well, with a perfect precision, recall, and F1-score of 1.00. This means that when it predicts a loan as healthy, it is always correct, and it correctly identifies all healthy loans in the dataset.

For Label 1 (High-Risk Loan):

Precision: 0.86
Recall: 0.91
F1-Score: 0.88
Support: 507
The model also performs well for high-risk loans (label 1). It has a relatively high precision of 0.86, indicating that when it predicts a loan as high-risk, it's correct most of the time. The recall of 0.91 shows that the model correctly identifies a significant portion of the high-risk loans. The F1-score of 0.88 represents a balanced trade-off between precision and recall, indicating good overall performance.

In summary, the logistic regression model performs very well for both healthy loans (label 0) and high-risk loans (label 1). It achieves high accuracy, precision, recall, and F1-scores for both classes, demonstrating its effectiveness in distinguishing between these two classes.

Considering the high accuracy, balanced performance, and the model's robustness to class imbalance, the logistic regression model is a strong candidate for use by the company. 
It is capable of effectively distinguishing between healthy and high-risk loans, making it a valuable tool for risk assessment and decision-making in the lending process.
