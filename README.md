# Credit_Risk_Analysis

---

### Overview:

---
The aim of this project was to apply machine learning methods to solve a real-world challenge: credit card risk. Estimating credit risk is a challenging classification problem because good loans easily outnumber risky loans. A number of different techniques were employed to train and evaluate models with unbalanced classes. Imbalanced-learn and scikit-learn libraries were used to build and evaluate models using resampling.
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. Then, a combinatorial approach of over- and undersampling was employed using the SMOTEENN algorithm. Next, two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, were used to predict credit risk. Finally, the performance of these models were evaluated to make recommendation on whether these models should be used to predict credit risk.

Tools

Methods: RandomOverSampler and SMOTE algorithms for over sampling, ClusterCentroids algorithm for undersampling, and SMOTEEN algorithm for combinatorial over and undersampling
Python, Pandas
Scikit Learn
Imbalanced-learn
Git

### Results:

---
Analysis results using Randon Oversampling, SMOTE Oversampling, Undersampling, SMOTEEN (Combination of Over and Undersampling), Balanced Random Forest Classifier, and Easy Ensemble AdaBoost Classifier algorithms are shown below. The confusion matrix and the balanced classification report is also included below.

### 1 Random Oversampling

1.1 The balanced accuracy score : 0.6304720361427014

1.2 The confusion matrix :

<img width="409" alt="Screen Shot 2022-07-29 at 1 40 15 PM" src="https://user-images.githubusercontent.com/98849217/181815003-bc730ff3-e497-4ecf-8d84-f89f0b35461d.png">

1.3 The imbalanced classification report:

<img width="728" alt="Screen Shot 2022-07-29 at 1 40 52 PM" src="https://user-images.githubusercontent.com/98849217/181815086-9de1e48f-ceec-4cc7-a592-330257145391.png">

---

### 2. SMOTE Oversampling

2.1 The balanced accuracy score

<img width="466" alt="Screen Shot 2022-07-29 at 1 44 46 PM" src="https://user-images.githubusercontent.com/98849217/181815697-128a7731-4615-40f9-bb08-2843328e2118.png">

2.2 The confusion matrix 

<img width="411" alt="Screen Shot 2022-07-29 at 1 45 24 PM" src="https://user-images.githubusercontent.com/98849217/181815786-84a0d318-c643-4230-afa6-3db09bbf12aa.png">

2.3 The imbalanced classification report

<img width="768" alt="Screen Shot 2022-07-29 at 1 46 02 PM" src="https://user-images.githubusercontent.com/98849217/181815886-44b479ba-f5de-4722-9f19-2a458855d952.png">

---

### 3. Undersampling - The Cluster Centroids algorithm

3.1 the balanced accuracy score = 0.6159507435206336

3.2 the confusion matrix 

<img width="400" alt="Screen Shot 2022-07-29 at 1 55 15 PM" src="https://user-images.githubusercontent.com/98849217/181817258-5dae77ec-7f33-41fa-95e3-8e7b843d21d4.png">


3.3 The imbalanced classification report:

<img width="780" alt="Screen Shot 2022-07-29 at 1 56 14 PM" src="https://user-images.githubusercontent.com/98849217/181817397-926249c8-b88f-4a79-89c3-5df9517d4d2c.png">

---

### 4 Combination (Over and Under) Sampling - The SMOTEENN algorithm

4.1 The balanced accuracy score :  0.5160196365189295 

4.2 The confusion matrix

<img width="426" alt="Screen Shot 2022-07-29 at 1 58 56 PM" src="https://user-images.githubusercontent.com/98849217/181817819-87df0a84-a2c4-404f-9b2b-e4dd68948983.png">

4.3 The imbalanced classification report

<img width="734" alt="Screen Shot 2022-07-29 at 1 59 14 PM" src="https://user-images.githubusercontent.com/98849217/181817853-501b624e-80e2-4e3b-a052-e955f9a8e0a2.png">


---

### 5 .Ensemble Learners - The Balanced Random Forest Classifier

the balanced accuracy score : 0.7877672625306695

the confusion matrix

<img width="274" alt="Screen Shot 2022-07-29 at 2 02 25 PM" src="https://user-images.githubusercontent.com/98849217/181818308-31d13bd5-db15-4c24-a4d0-1f87821c7727.png">

the imbalanced classification report

<img width="717" alt="Screen Shot 2022-07-29 at 2 03 20 PM" src="https://user-images.githubusercontent.com/98849217/181818431-fa7db8ae-0dde-437f-b976-aff01b41b4ba.png">

### 6. Ensemble Learners - Easy Ensemble AdaBoost classifier

6.1 The balanced accuracy score : 0.925427358175101

6.2 The confusion matrix : 

<img width="299" alt="Screen Shot 2022-07-29 at 2 06 56 PM" src="https://user-images.githubusercontent.com/98849217/181818926-6640d76b-c2c0-44f2-9aaa-dc9212e83781.png">


6.3 The imbalanced classification report:

<img width="731" alt="Screen Shot 2022-07-29 at 2 07 18 PM" src="https://user-images.githubusercontent.com/98849217/181818975-5b4fba7d-3278-4b1f-9869-77b7f65201ae.png">
