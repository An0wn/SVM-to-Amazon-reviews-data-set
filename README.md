# SVM-to-Amazon-reviews-data-set

SVM algorithm is applied on amazon reviews datasets to predict whether a review is positive or negative. 


Procedure to execute the above task is as follows: 

• Step1: Data Pre-processing is applied on given amazon reviews data-set.And Take sample of data from dataset because of computational limitations 

• Step2: Time based splitting on train and test datasets.

• Step3: Apply Feature generation techniques(Bow,tfidf,avg w2v,tfidfw2v)

• Step4: Apply SVM algorithm using each technique. 

• Step5: To find C(1/alpha) and gamma(=1/sigma) using gridsearch cross-validation and random cross-validation 


0.2 Objective: 

• To classify given reviews (positive (Rating of 4 or 5) &amp; negative (rating of 1 or 2)) using SVM algorithm. 
