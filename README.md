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

**Cluster Centroid Undersampling**

- Accuracy Score: 0.4362685265911072
- Preciscion High Risk: 0%
- Preciscion Low Risk: 100%
- Recall High Risk: 61%
- Recall Low Risk: 44%

![Cluster Undersampling accuracy](https://user-images.githubusercontent.com/95899763/166188079-b0f87a8c-f883-4389-ad1f-ce263a56929b.PNG)

![Cluster undersdampling confusion matrix](https://user-images.githubusercontent.com/95899763/166188097-53cff27c-c325-4d5f-b1b7-c2b83a6704ae.PNG)

![Cluster undersampling classification report](https://user-images.githubusercontent.com/95899763/166188126-6664f2ec-f2d0-47d8-9c1b-7450afdb7158.PNG)

**SMOTEENN**

- Preciscion High Risk: 1%
- Preciscion Low Risk: 100%
- Recall High Risk: 77%
- Recall Low Risk: 55%

![SMOTEENN confusion matrix](https://user-images.githubusercontent.com/95899763/166189116-fd878463-68ec-4826-9675-25d4c35c6a9f.PNG)

![SMOTEENN clasiification report](https://user-images.githubusercontent.com/95899763/166189145-1d8e45ed-13ca-4a8c-9175-5393577f2478.PNG)

**Balanced Random Forest Classifier**

- Accuracy Score: 0.6481524721265542
- Preciscion High Risk: 56%
- Preciscion Low Risk: 100%
- Recall High Risk: 30%
- Recall Low Risk: 100%

![Balanced Random Forest confusion matrix](https://user-images.githubusercontent.com/95899763/166189444-6e68c58c-d45c-4de1-8eba-058ee582647a.PNG)

![Balanced Random Forest classification report](https://user-images.githubusercontent.com/95899763/166189476-2b2dd1d1-6537-4411-9a9b-2b386ba2f608.PNG)

**Easy Ensemble AdaBoost Classifier**

- Accuracy Score: 0.9229904850855175
- Preciscion High Risk: 6%
- Preciscion Low Risk: 100%
- Recall High Risk: 91%
- Recall Low Risk: 94%

![Easy Ensemble AdaBoost confusion matrix](https://user-images.githubusercontent.com/95899763/166189814-c2333f2a-99d2-4408-9493-a0406592c132.PNG)

![Easy Ensemble AdaBoost classification report](https://user-images.githubusercontent.com/95899763/166189846-6b130917-31eb-4073-a11a-26ee196057ca.PNG)

# Summary
