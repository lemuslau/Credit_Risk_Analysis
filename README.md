# Credit Risk Analysis

## Overview 
The purpose of this analysis was to build and evaluate models using sampling for a data set for credit card credit. This dataset came from LendingClub and from the analysis it is meanto to recommend which model should be used to predict credit risk. 
For this Analysis the algorithms used were: 
- SMOTE
- SMOTEENN 
- ClusterCentroids
- BalancedRandomForestClassifier
- RandomOVERSampler
- EasyEnsembleClassifier

## Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.
1. Naive Random Sampling Results: 
- Accuracy Score: 65.7%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 71%
- Recall Low Risk: 60%
<img width="547" alt="Naive Random Sampling" src="https://user-images.githubusercontent.com/102635884/185518703-e330c7dc-7318-4726-85fe-3b852a249e19.PNG">

2. SMOTE Oversampling Results:
- Accuracy Score: 66.2%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 63%
- Recall Low Risk: 69%
<img width="660" alt="SMOTE Oversampling" src="https://user-images.githubusercontent.com/102635884/185519507-fa8f9477-ddba-4f31-9fba-cb79a18c28fa.PNG">

3. Undersampling Results:
- Accuracy Score: 56.4%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 65%
- Recall Low Risk: 48%
<img width="580" alt="Undersampling" src="https://user-images.githubusercontent.com/102635884/185519794-72f69b83-c938-4de1-aa72-1b447b38f608.PNG">

4.Combination (Over and Under) Sampling Results:
- Accuracy Score: 68.7%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 80%
- Recall Low Risk: 57%
<img width="605" alt="Combination" src="https://user-images.githubusercontent.com/102635884/185520151-0efa17d3-06c1-48f0-b979-c6fbc380afbd.PNG">

5. Balanced Random Forest Classifer Results: 
- Accuracy Score: 78.8%
- Precision High Risk: 3%
- Precision Low Risk: 100%
- Recall High Risk: 70%
- Recall Low Risk: 87%
<img width="665" alt="BRF" src="https://user-images.githubusercontent.com/102635884/185520547-f45a167e-99ce-4cfb-bd4a-8f574e559bb6.PNG">

6. Easy Ensemble Classifier Results: 
- Accuracy Score: 93.1%
- Precision High Risk: 9%
- Precision Low Risk: 100%
- Recall High Risk: 92%
- Recall Low Risk: 94%
<img width="603" alt="Easy" src="https://user-images.githubusercontent.com/102635884/185520893-f678f225-c4b2-4fd5-9789-7167b762e8b3.PNG">

## Summary:
After reviewing each of the 6 models, the one with the highest accurancy was Easy Ensemble Classifying at 91%. The other models ranged between 56% to 78% which means they would not be the best model to use for credit risk because of the gamble you would have. For credit risk you would want to operate on a higher accurancy model like the Easy Ensemble Classifier in this case. 
