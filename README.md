# Part 1
## RecommenderSystem for Dating Website
The project is a dating website recommendation system.
Here we build two collaborative filtering models, KNN and SVD. We select the most popular 10000 male and 1000 female users' ratings from Czech dating site libiseti in 2006 http://www.occamslab.com/petricek/data/ (where poplairy is calculated by the number of rating received).
The goal is to provide users with personalized dating candidates, according to the rating history of a user to the others. This project implements collaborative filtering algorithms in two parts: "building from scratch" and "using Surprise package." Each part would construct two models based on neighborhood-based or model-based algorithms. Through tuning the hyper parameter, evaluating the coverage, and calculating the accuracy, the models are continuously optimized. 

# Part 2

## Recommendation System for Amazon Apps

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

  PMF_crosscategory_result.csv: PMF Cross Category Prediction 
  
  https://drive.google.com/open?id=15_HvX1kBtpQjqbV-DKXKE2zN-AydE0MB
   
  PMF_in_category_result.csv.zip: PMF In Category Prediction 
  
  https://drive.google.com/open?id=1pJV8XxcenqOk8U_UZNb63011d3EYCYI3

  FM Model Intermidate Prediction: In-Category & Cross-Category Prediction
  
  https://drive.google.com/file/d/1HldijujIP70UNzPjzjsxF5QYhkMWYotK/view?usp=sharing
  
  KNNWithLSH_in_category_result.csv.zip: KNN With LSH Model In-Category Prediction

  https://drive.google.com/open?id=1GhTgxcIjFZYYDapz0bcCQkEyqOhk5Lnj
