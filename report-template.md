# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
--------------------------------------------------------------------------------------------------------------------------------------------------------
The overall purpose of this report seems to be to seperate classifications in the makings of a healthy loan & a high-risk loan. The use of these models are paramount in the ease of anaylsis when looking at the different variables that go into making a profitable decision for the buisness, these models when given the right information can be a make or break for many instances between loss and profits.

The logistic regression model does seem to perform very well in predicting both the 0 (healthy loan) and 1 (high-risk loan) labels, as indicated by the precision, recall, and F1-score metrics.

For the 0 label (healthy loan):

Precision is very high at 100%, indicating that among all instances predicted as class 0, all of them are actually class 0.
Recall is also very high at 99%, indicating that the model correctly identifies 99% of all actual class 0 instances.
The F1-score, which is the harmonic mean of precision and recall, is also very high at 1.00, indicating excellent performance.

For the 1 label (high-risk loan):

While precision is slightly lower at 84%, it still indicates that among all instances predicted as class 1, 84% of them are actually class 1.
Recall is also high at 94%, indicating that the model correctly identifies 94% of all actual class 1 instances.
The F1-score for class 1 is also good at 0.89, suggesting a good balance between precision and recall for this class.
Overall, the logistic regression model demonstrates strong predictive capability for both classes, with particularly impressive performance for the 0 label, and still very good performance for the 1 label.

