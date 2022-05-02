# Credit_Risk_Analysis

# Overview

In this challenge we used the machine learning methods to predict credit risk. We accomplished this by using imbalanced-learn and scikit-learn libraries. The mothodes applied in this analysis are: 

- RandomOverSampler
- Smote
- ClusterCentroids
- Smoteenn
- BalanacedRandomForestClassifier
- EasyEnsembleClassifier 

# Results

**Naive Random Oversampling**

- Accuracy Score: 0.6627143272304563
- Preciscion High Risk: 1%
- Preciscion Low Risk: 100%
- Recall High Risk: 68%
- Recall Low Risk: 66%

![Random Oversampling Accuracy](https://user-images.githubusercontent.com/95899763/166186722-9f6c48de-149e-4451-88ce-36cc0ba90ffb.PNG)

![Random Oversampling Confusion Matrix](https://user-images.githubusercontent.com/95899763/166186746-cfe01c3a-3305-4b7b-8c6d-04dc1cac571e.PNG)

![Random Oversampling Classification Report](https://user-images.githubusercontent.com/95899763/166186764-1f512e03-45c8-45ec-a9f2-24876253e4f9.PNG)

**SMOTE Oversampling**

- Accuracy Score: 0.6921825050857309
- Preciscion High Risk: 1%
- Preciscion Low Risk: 100%
- Recall High Risk: 68%
- Recall Low Risk: 69%

![SMOTE Oversampling accuracy](https://user-images.githubusercontent.com/95899763/166187306-924c43c7-7c72-41ba-bd27-848d173be7bf.PNG)

![SMOTE Oversampling Confusion matrix](https://user-images.githubusercontent.com/95899763/166187323-bb59fe43-8aac-4c00-8f97-6a713870dd32.PNG)

![SMOTE Oversampling classification report](https://user-images.githubusercontent.com/95899763/166187341-e7264ceb-5f79-41d8-ba5e-7b9af5670251.PNG)

**Cluster Centroid Undersampling*

- Accuracy Score: 0.4362685265911072
- Preciscion High Risk: 0%
- Preciscion Low Risk: 100%
- Recall High Risk: 61%
- Recall Low Risk: 44%

![Cluster Undersampling accuracy](https://user-images.githubusercontent.com/95899763/166188079-b0f87a8c-f883-4389-ad1f-ce263a56929b.PNG)

![Cluster undersdampling confusion matrix](https://user-images.githubusercontent.com/95899763/166188097-53cff27c-c325-4d5f-b1b7-c2b83a6704ae.PNG)

![Cluster undersampling classification report](https://user-images.githubusercontent.com/95899763/166188126-6664f2ec-f2d0-47d8-9c1b-7450afdb7158.PNG)

# Summary
