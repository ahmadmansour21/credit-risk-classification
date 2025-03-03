# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis: allows us to identify the creditworthiness of individuals based on their predicted scores of '0' or '1'.
* Explain what financial information the data was on, and what you needed to predict: need to predict loan status and whether it is '0' or '1' based on information such as loan size, interest rates, total debt and more.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`): loan status is the variable that will inform us on whether someone's creditworthiness is healthy or not.
* Describe the stages of the machine learning process you went through as part of this analysis: loan status was identified as the label/y and the rest were identified as features/X. Then, using train_test_split, we split the X and y. We then used the logisticregression model to predict and used .fit to fit our X and y into this model. Then, predictions were made. Finally, a classification report is formed to analyze the accuracy of the model.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
The model seemed to predict scores of '0' with 1.00 precision and scores of '1' with 0.84 precision. Furthermore, they have recalls of 0.99 and 0.94 respectively. Finally, there is an average of 0.92 precision overall, indicating that this is an accurate model to make such predictions.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

Due to the accuracy of the model, LogisticRegression can indeed be used to make such predictions. It is more important to predict the '0' as it is what deems someone's creditworthiness as healthy.
