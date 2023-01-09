# Credit_Risk_Analysis

## Overview of Analysis
The purpose of this analysis was to apply machine learning models to analyze credit card risk associated to borrowers based on historic data.
Credit risk is an unbalanced classification problem, as good loans outnumber risky loans, imbalanced-learn and scikit-learn libraries were used in jupyter notebooks to build and evaluate models using resampling techniques. 
Data was oversampled using RandomOverSampler and Smote algorithms, and undersampled using ClusterCentroids algorithm. A combination approach of over and undersampling was also taken using the SMOTEENN algorithm. Next, BalancedRandomForestClassifier and EasyEnsembleClassifier models, which help reduce bias, were compared to predict credit risk.

## Results
Random Oversampling Model:
- Balanced Accuracy Score: 65.47%
- Precision: 99%, high risk: 1%, low risk: 100%
- Recall: 59%, high risk: 72%, low risk: 59%

![Screen Shot 2023-01-09 at 10 44 20 AM](https://user-images.githubusercontent.com/111692952/211348482-e471369f-a0be-4128-8006-4933e59c7c79.png)

SMOTE Oversampling:
- Balanced Accuracy Score: 66.20%
- Precision: 99%, high risk: 1%, low risk: 100%
- Recall: 69%, high risk: 63%, low risk: 69%

![Screen Shot 2023-01-09 at 10 45 40 AM](https://user-images.githubusercontent.com/111692952/211348710-c163785a-2dc6-4b15-8ac9-0cea698fb3f6.png)

ClusterCentroids Undersampling:
- Balanced Accuracy Score: 54.47%
- Precision: 99%, high risk: 1%, low risk: 100%
- Recall: 40%, high risk: 69%, low risk: 40%

![Screen Shot 2023-01-09 at 10 47 01 AM](https://user-images.githubusercontent.com/111692952/211349049-6eb49480-5ea6-4de0-a290-34ef0a575768.png)

SMOTEENN Combination Sampling:
- Balanced Accuracy Score: 66.66%
- Precision: 99%, high risk: 1%, low risk: 100%
- Recall: 61%, high risk: 72%, low risk: 61%

![Screen Shot 2023-01-09 at 10 48 46 AM](https://user-images.githubusercontent.com/111692952/211349411-fe0bdaf7-692e-4249-b107-766b1258054f.png)

Balanced Random Forest Classifier:
- Balanced Accuracy Score: 78.88%
- Precision: 99%, high risk: 3%, low risk: 100%
- Recall: 87%, high risk: 70%, low risk: 87%

![Screen Shot 2023-01-09 at 10 51 32 AM](https://user-images.githubusercontent.com/111692952/211350078-6e3c2010-5ec7-4cea-a61f-052e17e2b616.png)

Easy Ensemble AdaBoost Classifier:
- Balanced Accuracy Score: 93.16%
- Precision: 99%, high risk: 9%, low risk: 100%
- Recall: 94%, high risk: 92%, low risk: 94%

![Screen Shot 2023-01-09 at 10 51 53 AM](https://user-images.githubusercontent.com/111692952/211350134-b0e01e29-ca73-44f1-bad6-b14f21210e00.png)




