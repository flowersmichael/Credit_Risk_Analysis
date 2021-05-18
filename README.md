# Credit_Risk_Analysis
Assessing credit risk using supervised learning


## Overview of the Analysis
The purpose of this analysis is to apply machine learning to solve the real-world challenge, credit card risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, we need to use multiple different techniques to train and evaluate models with unbalanced classes.

## Results
Using bulleted lists, describe the **balanced accuracy scores** and the **precision** and **recall** scores of all six machine learning models. Use screenshots of your outputs to support your results.

### Naive Random Oversampling

![image](https://user-images.githubusercontent.com/74375396/118431437-34f34680-b68b-11eb-8def-e3d56a175732.png)


### SMOTE Oversampling

![image](https://user-images.githubusercontent.com/74375396/118431758-e98d6800-b68b-11eb-8307-cc5bf24428ae.png)


### Undersampling

![image](https://user-images.githubusercontent.com/74375396/118431838-117ccb80-b68c-11eb-87df-26ea28ac2177.png)


### Combination Sampling

![image](https://user-images.githubusercontent.com/74375396/118431895-3113f400-b68c-11eb-9ad7-65d4c99015b1.png)


### Balanced Random Forest Classifier

![image](https://user-images.githubusercontent.com/74375396/118432197-d4650900-b68c-11eb-861a-26f199d02ae1.png)


### Easy Ensemble AdaBoost Classifier

![image](https://user-images.githubusercontent.com/74375396/118433490-fa3fdd00-b68f-11eb-889d-1821768b46b9.png)




## Summary
For credit risk, from a lender's perspective, while it is important from a time and resources perspective to not label too many low-risk loans as possibly-high risk, the "false positive" risk can be addressed with closer scrutiny in further steps. 

The most important quality, however, is to not evaluate actual high-risk loans incorrectly, and to label them low-risk. Enough bad loans can ruin a lender.

From this perspective, the best model is the Easy Ensemble AdaBoost Classifier, which predicted a low number of loans as low-risk that were actually high-risk.


