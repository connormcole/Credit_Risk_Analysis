# Credit_Risk_Analysis

## Overview
Testing various supervised machine learning models on credit card purchase data to determine which is best at predicting fraudulent transactions. 

## Results

- Random oversampling balanced accuracy score, and precision and recall scores.
![image](https://user-images.githubusercontent.com/92554586/156945197-2cb8a79a-e5d0-4f7e-aabe-d6d89136a747.png)

![image](https://user-images.githubusercontent.com/92554586/156945115-578c4f3c-37cc-4beb-aba5-8df0ee9d2c7e.png)

- SMOTE oversampling balanced accuracy score, and precision and recall scores.
![image](https://user-images.githubusercontent.com/92554586/156945263-752c5d66-499f-4aab-8cdf-d5a35b828f56.png)

![image](https://user-images.githubusercontent.com/92554586/156945277-9240de69-9e31-4dc1-aa9c-47be234cc5b6.png)

- Cluster centroids undersampling balanced accuracy score, and precision and recall scores.
![image](https://user-images.githubusercontent.com/92554586/156945321-519734f2-2316-46a1-8977-783ca1cebf06.png)

![image](https://user-images.githubusercontent.com/92554586/156945333-53c71140-fc44-467c-adc4-0a3780da5d1b.png)

- SMOTEENN combination over and undersampling balanced accuracy score, and precision and recall scores.
![image](https://user-images.githubusercontent.com/92554586/156945385-45def974-e00f-4146-92f2-f11361cea9b1.png)

![image](https://user-images.githubusercontent.com/92554586/156945395-ce375474-ccd0-43a7-84da-318c3de9e286.png)

- Balanced Random Forest Classifier balanced accuracy score, and precision and recall scores.
![image](https://user-images.githubusercontent.com/92554586/156945649-9d24aaa7-9c30-4177-a5c5-4958f60a9ad0.png)

![image](https://user-images.githubusercontent.com/92554586/156945671-f1704655-5fcf-4ffc-83fe-b091e480d977.png)

- Easy Ensemble AdaBoost Classifier balanced accuracy score, and precision and recall scores. 
![image](https://user-images.githubusercontent.com/92554586/156945739-cc1fd329-8b01-468b-ad1c-92b8742eea1a.png)

![image](https://user-images.githubusercontent.com/92554586/156945745-4487c4e9-82ea-445c-a0ce-1ad394c30610.png)

## Summary
The first four models used (random oversampling, SMOTE oversampling, cluster centroid undersampling, and SMOTEENN combination sampling) all produced similar balanced accuracy scores. All had high precision scores for predicting low risk transactions, but low precision scores for high risk transactions. The recall scores were also similar for these models, with SMOTEENN having the highest recall score for high risk transactions; it was the best at predicting high risk transactions from the actual high risk transactions. The last two models, Balanced Random Forest and Easy Ensemble AdaBoost, were far better than the other models. Both had higher accuracy scores, and precision and recall scores. I would recommend the Easy Ensemble AdaBoost model because it had the highest accuracy score, precision scores, and recall scores across the board. It was far and away the best at catching high risk transactions.   
