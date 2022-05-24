# Credit_Risk_Analysis
#### *Utilized several machine learning models to predict credit risk using Python's imbalanced-learn and scikit-learn libraries*

## Supervised Machine Learning: Overview of the analysis

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.



## Resources
- Dataset: 
  - LoanStats_2019Q1.csv

- Software used:
  - Python
  - Jupyter Notebook
  - NumPy, scikit-learn, and imbalanced-learn libraries
  - Logistic Regression and Random Forest models
  - Ensemble and resampling techinques

## Results

The results for all six machine learning algorithms are shown below with their outputs supported with images:


- Naive Random Oversampling:
![image](https://user-images.githubusercontent.com/97119920/170097349-0faa49d0-924f-4e21-8546-954b5b5b7e27.png)
![image](https://user-images.githubusercontent.com/97119920/170097384-c5428754-1f4d-445a-864b-1d253045ab36.png)

- SMOTE Oversampling:
![image](https://user-images.githubusercontent.com/97119920/170096952-c97abc58-cd96-4ec9-9dac-314b8a8dda21.png)


- Cluster Centroid Undersampling: 
![image](https://user-images.githubusercontent.com/97119920/170109463-cbf72715-9a46-48ad-934c-55f7cbe9736b.png)


- SMOTEENN Combination Sampling: 
![image](https://user-images.githubusercontent.com/97119920/170109517-ad271dda-5c8d-47ed-8050-7f3fe7cda109.png)


- Balanced Random Forest Classifier: 
![image](https://user-images.githubusercontent.com/97119920/170097152-0afc954e-ede9-45cd-9a63-576975c3aebf.png)

- Easy Ensemble AdaBoost Classifier:
![image](https://user-images.githubusercontent.com/97119920/170097045-6b50aa1d-907c-46fe-a747-d1fd2647568b.png)




