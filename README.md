# Credit_Risk_Analysis

## Overview
In this challenge we utilize imbalanced-learn and scikit-learn libraries as well as six different models in order to help our friend predict credit card risk. The models we are using are Naive Random Sampling, SMOTE Oversampling, Undersampling, a Combination of both Over and Undersampling, the Balanced Random Forest Classifier, and the Easy Ensemble AdaBoost Classifier. 

## Results 

### Naive Random Oversampling
![Screen Shot 2022-02-27 at 7 47 41 PM](https://user-images.githubusercontent.com/92831268/155921390-2bba492b-67e2-43eb-b1f1-d998a1239cdc.png)
- Balanced Accuracy: 64.1%
- Precision: 99%
- Recall: 69%


### SMOTE Oversampling
![Screen Shot 2022-02-27 at 7 47 48 PM](https://user-images.githubusercontent.com/92831268/155921395-7db6c605-b890-40da-8e7c-49f98bdb4401.png)
- Balanced Accuracy: 63.7%
- Precision: 99%
- Recall: 64%

### Undersampling
![Screen Shot 2022-02-27 at 7 48 02 PM](https://user-images.githubusercontent.com/92831268/155921401-6f67fe5c-10e7-4373-a0d1-cc803ce010c1.png)
- Balanced Accuracy: 63.7%
- Precision: 99%
- Recall: 45%

### Combination (Over and Under) Sampling
![Screen Shot 2022-02-27 at 7 48 10 PM](https://user-images.githubusercontent.com/92831268/155921409-2d9676fb-06c1-44f5-9a02-6abe50abd177.png)
- Balanced Accuracy: 52.9%
- Precision: 99%
- Recall: 58%


### Balanced Random Forest Classifier
![Screen Shot 2022-02-27 at 7 48 25 PM](https://user-images.githubusercontent.com/92831268/155921419-a385a8f3-b86b-47d8-bedb-7b1d9ff7294c.png)
- Balanced Accuracy: 79.7%
- Precision: 99%, high risk at 3%
- Recall: 89%

### Easy Ensemble AdaBoost Classifier
![Screen Shot 2022-02-27 at 7 48 32 PM](https://user-images.githubusercontent.com/92831268/155921425-82ea1437-3b12-495b-ab2d-ffc10f78c974.png)
- Balanced Accuracy: 92.5%
- Precision: 99%, high risk at 7%
- Recall: 94%

## Summary 
From the six models that we did in this challenge, I would recommend using the Easy Ensemble AdaBoost Classifier. In the first four models that we used (Naive Over samping, SMOTE Oversamping, Undersampling, and Combination), we have relatively lost balanced accuracy scores compared to our classifier models. They all also predict that only 1% of loans will be high risk, which in highly unlikely. Whereas our classifers predict that 3-7% of loans will be high risk. A more likely outcome and better model to use is one to predict a balanced accuracy and recall score that are somewhat close to each other. This is why I would recommend that we use the Easy Ensemble AdaBoost Classifier model as it predicts a Balanced Accuracy Score of 92.5% and a Recall Score of 94% as a means to predict credit risk. 
