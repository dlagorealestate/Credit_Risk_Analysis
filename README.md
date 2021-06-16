# Credit_Risk_Analysis

### Overview

 In this challenge our goal is to use algorithms to figure out someones credit risk. To do this we are using imbalanced-learn and scikit-learn libraries to build algorithms and evalute them using a resampling method. We used these algorithms to see what will give us the best accuracy and recall to best predict credit risk.


### Results

  * Naive Random Oversampling results:
<img width="1355" alt="99189223-34a2de80-272e-11eb-8044-b988f1a57823" src="https://user-images.githubusercontent.com/78887673/122307952-5ee19800-ced9-11eb-8e13-8240cce8d67f.png">

  * SMOTE oversampling results:
<img width="1286" alt="99189213-2e146700-272e-11eb-87e1-3d7f80ba662a" src="https://user-images.githubusercontent.com/78887673/122307954-5f7a2e80-ced9-11eb-9e07-b64fe82fd29c.png">

  * Undersampling results:
<img width="1293" alt="99189228-366ca200-272e-11eb-8f97-78bdacff4a43" src="https://user-images.githubusercontent.com/78887673/122307955-5f7a2e80-ced9-11eb-9a2f-172269eaab5f.png">

  * Over and Undersampling results: 
<img width="1353" alt="99189232-3a002900-272e-11eb-8077-9695c40fcc83" src="https://user-images.githubusercontent.com/78887673/122307957-6012c500-ced9-11eb-9734-9fa4f041c12f.png">

  * Balanced Random Forest Classifier results: 
<img width="1315" alt="99189216-31a7ee00-272e-11eb-88d0-de8b0acb1411" src="https://user-images.githubusercontent.com/78887673/122307958-6012c500-ced9-11eb-93cf-a53c4af4239b.png">

  * Easy Ensemble AdaBoost Classifier results:
<img width="1382" alt="99189208-2bb20d00-272e-11eb-8616-de6011dece3b" src="https://user-images.githubusercontent.com/78887673/122307960-6012c500-ced9-11eb-8235-8f97677b6759.png">    



 ### Summary
 
  First we undersampled, oversampled, then both to try and determine which formula is best at predicting high loan risk. We then resampled the data using ensemble to try and predict which which loans are high and low risk. The accuracy score is not as high as the ensemble. As we saw, the Easy Ensemble had the best results of all the the algorithms because of it's accuracy score and balance of precision and recall score.
