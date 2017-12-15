
# Recommendation System for Amazon Apps

### Columbia University E4571 Personalization: Theory & Application
### Project Part 2 - Modern Personalization Frameworks and Algorithms


### Team Members:
##### Pin-Hao Chen - UNI: phc2121 
##### Leshen Sui - UNI: ls3452
##### Siwen Tang - UNI: st3101
##### Jingyi Wang - UNI: jw3562




## Contents:

+ AmazonAppReview.csv: Data file can be accessed through this link https://drive.google.com/file/d/1F0lMOwRTiLBedkMPjjGosH0POF6dgwF5/view?usp=sharing.

+ Data cleaning & Contend based clustering.ipynb: Cleans the AmazonAppReview.csv file and cluster categories through NLP and PCA Featrue extraction.

+ KNN With LSH.ipynb: LSH Algorithm Implementation and Evaluation.

+ PMF.ipynb: PMF Algorithm Implementation and Evaluation.

+ FM_Model.ipynd: FM Model Implementation and Evaluation.

+ Hybrid model & evaluation.ipynb: Hybrid model evaluation.

+ Recommendation System for Amazon Apps.pdf: Project Report.

+ Intermediate Data Folder:

  description.csv: Items listed with Index and Description

  data.pickle: Dictionary of NLP Category Clustering with Item Index

  test_in_categoty.csv: In-category Prediction Scores of three models for a subset of AmazonAppReview data. The format is   
  (User, Item, Predicted, Observation). [Shown Report Section 3.4.2 Hybrid Model Evaluation]

  test_cross_categoty.csv: Cross-category Prediction Scores of three models for a subset of AmazonAppReview data. The format 
  is (User, Category, Predicted, Observation). [Shown Report Section 3.4.2 Hybrid Model Evaluation]
  
+ 3 Model Prediction On Entire AmazonAppReview data
  PMF_crosscategory_result.csv: PMF Cross Category Prediction https://drive.google.com/open?id=15_HvX1kBtpQjqbV-DKXKE2zN-AydE0MB
  PMF_in_category_result.csv.zip:PMF Cross Category Prediction https://drive.google.com/open?id=1pJV8XxcenqOk8U_UZNb63011d3EYCYI3
   
+ 
https://drive.google.com/open?id=1pJV8XxcenqOk8U_UZNb63011d3EYCYI3
