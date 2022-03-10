# Credit_Risk_Analysis
## Overview
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. 

The following models were used to determine which one is better to use in the credit risk analysis:
- Random Forest Classifier
- Easy Ensemble AdaBoost Classifier
- Naive Random Oversampling
- SMOTE Oversampling
- ClusterCentroid with logistic regression
- SMOTEEN Sampling

## Results
### Random forest Classifier
A 100 n-estimators were used. 

![image](https://user-images.githubusercontent.com/21972342/157650652-76aed16a-a9c0-438c-9d6e-6f68aa7579e0.png)
    
The Accuracy of the model was: 68.30%
![image](https://user-images.githubusercontent.com/21972342/157650840-be1f827e-f052-4fd6-8198-1a5c7defb9fa.png)

The confusion matrix:
![image](https://user-images.githubusercontent.com/21972342/157651113-295adf51-206d-40b3-85ce-6a80b21052c3.png)

Imbalanced classification report:
![image](https://user-images.githubusercontent.com/21972342/157651208-ad9220bd-12d9-4937-a57f-cbb71eb13bfd.png)

Top features involved:
![image](https://user-images.githubusercontent.com/21972342/157651369-e894ca0e-f945-4971-aeba-3613ab10f55c.png)

### Easy Ensemble AdaBoost Classifier
A 100 n-estimators were used. 
![image](https://user-images.githubusercontent.com/21972342/157651651-c3779b9e-3829-423c-bde3-c19b06431e8d.png)
    
The Accuracy of the model was: 93.16%
![image](https://user-images.githubusercontent.com/21972342/157651711-b04ab1ae-0c18-461f-aa1c-8bdceaf7eea7.png)

The confusion matrix:
![image](https://user-images.githubusercontent.com/21972342/157651759-61cd7069-1090-4779-845a-a93c7a4de512.png)

Imbalanced classification report:
![image](https://user-images.githubusercontent.com/21972342/157651805-c29b37bf-6014-4bd2-ac81-fdc8ab0767b5.png)

### Naive Random Overssampling
![image](https://user-images.githubusercontent.com/21972342/157651933-601e17a3-67cf-4473-ab08-c731e322ed42.png)

The Accuracy of the model was: 64.38%
![image](https://user-images.githubusercontent.com/21972342/157652099-a1868568-59f4-45af-ab02-a31e71cdd02a.png)

The confusion matrix:
![image](https://user-images.githubusercontent.com/21972342/157652129-7a183a04-2567-48d5-a1a8-93db0c3a0b5e.png)

Imbalanced classification report:
![image](https://user-images.githubusercontent.com/21972342/157652174-8cabe598-52a2-43a9-9238-4f0aed37174a.png)

### SMOTE Oversampling
![image](https://user-images.githubusercontent.com/21972342/157652288-4ebdaec8-8767-403c-8501-873d25c199a8.png)

The Accuracy of the model was: 66.28%
![image](https://user-images.githubusercontent.com/21972342/157652346-023ad99e-3bdd-4c4d-a5ac-5138f38ab529.png)

The confusion matrix:
![image](https://user-images.githubusercontent.com/21972342/157652397-d8a76ed7-cf32-4b4c-8108-06559d89e939.png)

Imbalanced classification report:
![image](https://user-images.githubusercontent.com/21972342/157652442-ec8f22d2-fb72-4f78-9239-8e5f93698e11.png)

### ClusterCentroid with logistic regression
![image](https://user-images.githubusercontent.com/21972342/157652816-14af965c-da19-4c88-bf8a-d9d40974f40d.png)

The Accuracy of the model was: 54.47%
![image](https://user-images.githubusercontent.com/21972342/157652854-9308cac8-b2c1-4f45-bb4e-a630f54bf48d.png)

The confusion matrix:
![image](https://user-images.githubusercontent.com/21972342/157652912-3bff058d-b537-44f5-a431-1bc36bf90941.png)

Imbalanced classification report:
![image](https://user-images.githubusercontent.com/21972342/157652956-461eb5f6-f2db-48bd-adc8-ab28ca9b946f.png)

### SMOTEEN Sampling
![image](https://user-images.githubusercontent.com/21972342/157653002-4520fb83-9eb1-4f51-82cd-7189c841033e.png)

The Accuracy of the model was: 67.48%
![image](https://user-images.githubusercontent.com/21972342/157653033-e59b167f-6c5e-4e60-9451-0998cc014850.png)

The confusion matrix:
![image](https://user-images.githubusercontent.com/21972342/157653104-98474ef3-1471-4636-8cac-c1d304fc9a66.png)

Imbalanced classification report:
![image](https://user-images.githubusercontent.com/21972342/157653161-62c32833-e3b7-48d2-87e4-ff3670ba8439.png)

## Summary
I think that the best model to use in this scenario should be the Easy Ensemble AdaBoost Classifier due to is higher accuracy comapared to the others. The other model show an accuracy near 50%, similar to throwing a coin to make a decision.  
