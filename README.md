# Credit_Risk_Analysis
## Overview 
In this anaylsis, supervised machine learning is used to predict credit card risk. There were six models tested. The accuracy, precision, and recall were anaylzed for those models to determine which model would work best for the data. 

### Purpose
The purpose of this analysis was to work with Supervised Machine Learning. While conducting the analysis, the following tools were used:
- Scikit Learn
- Random Over Sampler
- SMOTE Oversampling
- ClusterCentroids (UnderSampling)
- SMOTEENN (over and under sampling)
- Balanced Random Forest Classifier
- Easy Ensemble AdaBoost Classifier

### Results
Six machine learning algorithms were ran on the data. The balanced accuracy, precision, and recall will be recorded for each of the algorithms. 
1. **RandonOverSample**
![aml1](https://user-images.githubusercontent.com/105830665/200974589-703ef09d-7c56-49e0-8481-efbbba82c365.png)
- Balanced Accuracy: 0.6504008094916134; Ranking 4 of 6 at 65% accuracy.
    
![ml1](https://user-images.githubusercontent.com/105830665/200974637-9ca950bf-4182-4732-962d-53226d279e05.png)    
- Precision: high_risk= 0.01 and low_risk= 1.00 
- Recall: high_risk= 0.62 and low_risk= 0.68
2. **SMOTE**
![aml2](https://user-images.githubusercontent.com/105830665/200974770-bbb91fea-e764-4d98-ba94-04de9102dfa4.png)
- Balanced Accuracy: 0.6583599806425919; Ranking 3 of 6 at 66% accuracy.

![ml2](https://user-images.githubusercontent.com/105830665/200974820-bb4bbf0c-9feb-422e-b87c-f0b32c1c99dd.png)
- Precision: high_risk= 0.01 and low_risk= 1.00 
- Recall: high_risk= 0.63 and low_risk= 0.68 
3. **ClusterCentroids**
![aml3](https://user-images.githubusercontent.com/105830665/200974868-fdf6e74d-342d-4c12-be32-288cdc230333.png)
- Balanced Accuracy: 0.544061547759079; Ranking 6 of 6 at 54% accuracy.

![ml3](https://user-images.githubusercontent.com/105830665/200974933-39403030-c630-4d01-a9e2-010ed6ac1d2d.png)    
- Precision: high_risk= 0.01 and low_risk= 1.00;  
- Recall: high_risk= 0.69 and low_risk= 0.40
4. **SMOTEENN**
![aml4](https://user-images.githubusercontent.com/105830665/200977043-0207bc44-37de-46c3-ae58-0afaa49648e1.png)
- Balanced Accuracy: 0.6449163069955265; Ranking 5 of 6 at 64% accuracy.

![ml4](https://user-images.githubusercontent.com/105830665/200977145-c5173bdb-3b76-4177-b0cc-4a6c83a37436.png)

- Precision: high_risk= 0.01 and low_risk= 1.00 
- Recall: high_risk= 0.72 and low_risk= 0.57
5. **BalancedRandomForestClassifier**
![aml5](https://user-images.githubusercontent.com/105830665/200977188-cf34b9c2-78dd-43d6-a0c6-8768953dd364.png)
- Balanced Accuracy: 0.7877672625306695; Ranking 2 of 6 at 79% accuracy.

![ml5](https://user-images.githubusercontent.com/105830665/200977229-98841a5f-11d3-4b0d-b725-062970989f56.png)
- Precision: high_risk= 0.04 and low_risk= 1.00 
- Recall: high_risk= 0.67 and low_risk= 0.91 
6. **EasyEnsembleAdaBoostClassifier**
![aml6](https://user-images.githubusercontent.com/105830665/200977269-320997cf-85d0-4839-97f7-c2e720ae644f.png)
- Balanced Accuracy: 0.925427358175101; Ranking 1 of 6 at 93% accuracy. 

![ml6](https://user-images.githubusercontent.com/105830665/200977333-d77ddb1f-acef-4e30-83f1-505cdb25ed90.png)
- Precision: high_risk= 0.07 and low_risk= 1.00 
- Recall: high_risk= 0.91 and low_risk= 0.94

### Summary
The credit card risk analysis used six algorithms to help predit credit risk. The precision for all six algorithms ran low for high-risk and high for low-risk. The Recall varied for models. The recall for the Easy Ensemble AdaBoost Classifier was high for both high risk and low risk. The Recalls for high risk and low risk for the other five models all were under 0.75, except for Balanced Random Forest Classifier's low risk( 0.91). 
The algorithm that shows the highest potential to predict credit card risk is the Easy Ensemble Adaboost Classifier. This algorithm has the highest balanced accuracy, 0.93. 