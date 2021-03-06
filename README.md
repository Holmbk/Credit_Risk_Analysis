# Credit_Risk_Analysis
## Overview
Credit risk analysis using different techniques to train and evaluate models with unbalanced classes.

## Results
## Resampling Models to Predict Credit Risk
### Random Over Sampling

![Naive Random](https://user-images.githubusercontent.com/98991575/177057508-2ae8b887-b98c-43dc-84e3-783c8776f0a7.png)

### SMOTE

![Smote](https://user-images.githubusercontent.com/98991575/177057505-83163bc1-19f8-4cfa-aee0-3cfde9263cf9.png)

### Under Sampling

![Undersampling](https://user-images.githubusercontent.com/98991575/177057503-3b77e426-f36f-4509-a912-95f4522a4a8d.png)


## Using SMOTEENN Algorithm to Predict Credit Risk
![Combination](https://user-images.githubusercontent.com/98991575/177057741-98b00a4b-9ca7-4884-8075-7295760f5b4e.png)

## Using Ensemble Classifier to Predict Credit Risk

### Balanced Random Forest Classifier
![Balanced](https://user-images.githubusercontent.com/98991575/177055490-aeb6be5e-357b-4abb-b5cd-0cb1fe9f4a45.png)

### Easy Ensemble Classifier
![Easy](https://user-images.githubusercontent.com/98991575/177055474-fde596a9-f0ac-4bfe-a8f6-a1fdcf8311ff.png)

## Summary
The models are inadequately predictive, and are not recommended for commercial application.  Random over sampling, SMOTE and under sampling did not give faverable results.  Naive and SMOTE did not produce usable model for the prediction of the bad loans.  Naive resulted in a precision score of 0.01 and recall of 0.62. The F1 score of 0.02 reflected the low recision score.  SMOTE resulted in a precision of 0.01 and recall of 0.61 with a F1 score of 0.02.  The under  sampling resulted with a precision score of 0.01, a recall of 0.65 and F1 of 0.01

Combination sampling had a precision score of 0.01, a recall of 0.70 and a F1 of 0.02 The performance is low.

The balanced random forest classifier and the easy ensemble classifier had low precision.  The balanced precision was 0.04 a recall of 0.67 and F1 of 0.07.  The Easy ensemble classified precision was 0.09, a recall of 0.92 and a F1 of 0.16.  These models are insufficient for commercial application.
