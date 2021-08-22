* The purpose of this analysis is to use various techniques to train and evaluate models with imbalanced classes.
* Lending data was provided in order to create predictions using various techniques such as, RandomOverSamplerand Logistical Regression.
* The value_counts function was used to check the balance of the labels variable (y).
* Fitting a logistic regression model by using training data.
* Saving the predictions on the testing data labels by using the testing feature data and the fitted model.
* Evaluating the model’s performance by calculating the accuracy score of the model, generating a confusion matrix and printing the classification report.
* The multiple stage machine learning process consisted of splittling the data into training and testing datasets 

## Results


* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.

        precision    recall  f1-score   support

           0       1.00      1.00      1.00     18759
           1       0.87      0.89      0.88       625

    accuracy                           0.99     19384
    macro avg       0.94      0.94      0.94     19384
weighted avg       0.99      0.99      0.99     19384


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  
 precision    recall  f1-score   support

           0       1.00      1.00      1.00     18759
           1       0.87      1.00      0.93       625

    accuracy                           1.00     19384
   macro avg       0.94      1.00      0.96     19384
weighted avg       1.00      1.00      1.00     19384
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* After completing my analysis I believe Model 2 performed best due to having a higher accuracy while also having a high macro avg as well as weighted avg.

