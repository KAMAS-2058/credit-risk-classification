# credit-risk-classification Machine Learning Analysis

The Purpose of this analysis was to use various Machine learning methods to train and evaluate a model based on loan risk. The dataset was based off historical data from a peer-to-peer lending service. The goal of the analysis was to examine the creditworthiness  of the borrowers.

## The Logistic Regression Model Results

By using a logistic regression model, we were provided with these results:

Balanced Accuracy Score: 0.9520479254722232

Confusion Matrix:
[18663,   102]
[   56,   563]

Classification Report:

            precision    recall  f1-score   support

   good loan       1.00      0.99      1.00     18765
  risky loan       0.85      0.91      0.88       619

    accuracy                           0.99     19384
   macro avg       0.92      0.95      0.94     19384
weighted avg       0.99      0.99      0.99     19384

## Logistic Regression Model Results after Resampling Data 

Balanced Accuracy Score: 0.9945026387334079

Confusion Matrix:
[74614,   422]
[  403, 74633]

Classification Report:

             precision    recall  f1-score   support

   good loan       0.99      0.99      0.99     75036
  risky loan       0.99      0.99      0.99     75036

    accuracy                           0.99    150072
   macro avg       0.99      0.99      0.99    150072
weighted avg       0.99      0.99      0.99    150072

## Conclusion

This model returned favorable results. The balanced accuracy score for both the original and resampled data was able to correctly classify the creditworthiness of the borrowers. This is reflected in the Confustion matrices, with both models showing the bulk of results being true positive or true negative.

The summary also showed good results for the original model and improved results for the second model. 

The first model showed high percision for good loans, at 100% and serviceable results for the riskly loans, 85%. In the recall column we can see that the first model predicted the outcomes correctly 99% and 91% of the time, for good and risky loans respectivly. The quality of the model is reaffirmed with the F1 scores. Using the percision and recall the F1 score showed 100% and 88% for good and risky loans respectivly.

The second model showed high percision for good loans, at 99% and good results for the riskly loans as well at 99%. In the recall column we can see that the second model predicted the outcomes correctly 99% and 99% of the time, for good and risky loans respectivly. The quality of the model is attested to with the F1 scores. Using the percision and recall the F1 score showed 99% and 99% for good and risky loans respectivly.
