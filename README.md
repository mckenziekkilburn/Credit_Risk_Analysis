# Credit_Risk_Analysis
_________________________

### Overview of the Analysis
- Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, I was asked to employ different techniques to train and evaluate models with unbalanced classes. I was asked to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. 



# Results
_________________________

### Naive Random Oversampling
 - Balanced Accuracy Score
 ![naive_accuracy](https://github.com/mckenziekkilburn/Credit_Risk_Analysis/blob/master/images/naive_accuracy.PNG)
 
 
 - Confusion Matrix
  ![naive_confus](https://github.com/mckenziekkilburn/Credit_Risk_Analysis/blob/master/images/naive_confus.PNG)
  
  - Imbalanced Classification Report
  ![naive_report](https://github.com/mckenziekkilburn/Credit_Risk_Analysis/blob/master/images/naive_report.PNG)
  
 ###### As we can see we have a 66% accuracy score, which is not a very efficient model. For our recall value total we can see is 58% which is still a low calculations and we need a better sample. We can see that it did not do a good job at predicting who had a risky loan.
 
### SMOTE Oversampling
 - Balanced Accuracy Score
 ![smote_accu](https://github.com/mckenziekkilburn/Credit_Risk_Analysis/blob/master/images/smote_accu.PNG)
 
 
 - Confusion Matrix
  ![smote_confu](https://github.com/mckenziekkilburn/Credit_Risk_Analysis/blob/master/images/smote_confu.PNG)
  
  - Imbalanced Classification Report
  ![smote_report](https://github.com/mckenziekkilburn/Credit_Risk_Analysis/blob/master/images/smote_report.PNG)
  
  ###### For our Smote Oversampling model, we can determine that our results are actually better predicted than our first model. With a accuracy score estimated at 65% and our True Positive rate is totaled at 68%(recall). We can also see that our chances of predicting positive value are high for low risk but very low for the high risk. 
  
  ### Undersampling
 - Balanced Accuracy Score
 ![under_acc](https://github.com/mckenziekkilburn/Credit_Risk_Analysis/blob/master/images/images/under_acc.PNG)
 
 - Confusion Matrix
  ![under_con](https://github.com/mckenziekkilburn/Credit_Risk_Analysis/blob/master/images/images/under_con.PNG)
  
  - Imbalanced Classification Report
  ![under_report](https://github.com/mckenziekkilburn/Credit_Risk_Analysis/blob/master/images/images/under_report.PNG)
  
  ###### For our Undersampling model, we can determine a accuracy score estimated at 54%. For our High risk recallwe calculated 67%, and a 41% for our low risk. We can also see that our chances of predicting positive value are high for low risk but very low for the high risk. 
   
   ### Combination (Over and Under) Sampling
 - Balanced Accuracy Score
 ![combo_acc](https://github.com/mckenziekkilburn/Credit_Risk_Analysis/blob/master/images/images/combo_acc.PNG)
 
 - Confusion Matrix
  ![combo_con](https://github.com/mckenziekkilburn/Credit_Risk_Analysis/blob/master/images/images/combo_con.PNG)
  
  - Imbalanced Classification Report
  ![combo_report](https://github.com/mckenziekkilburn/Credit_Risk_Analysis/blob/master/images/images/combo_report.PNG)
  
  ###### For our Combo model, we can determine a accuracy score estimated at 64%. For our High risk recall we calculate 72%, and a 57% for our low risk. We can also see that our chances of predicting positive value are high for low risk but very low for the high risk. We can see that we have a higher chance at predicting/determining who is a high risk and who actually is high risk. 
  
  ### Balanced Random Forest Classifier
 - Balanced Accuracy Score
 ![random_acc](https://github.com/mckenziekkilburn/Credit_Risk_Analysis/blob/master/images/images/random_acc.PNG)
 
 - Confusion Matrix
  ![random_con](https://github.com/mckenziekkilburn/Credit_Risk_Analysis/blob/master/images/images/random_con.PNG)
  
  - Imbalanced Classification Report
  ![random_report](https://github.com/mckenziekkilburn/Credit_Risk_Analysis/blob/master/images/images/random_report.PNG)
  
  ###### For our Combo model, we can determine a accuracy score estimated at 78% which is our highest result yet. For our High risk recall we calculate 70%, and a 87% for our low risk. We can also see that our chances of predicting positive value are high for low risk but very low for the high risk. We can see that we have a higher chance at predicting/determining who is a high risk and who actually is high risk. If I was to choose between all of the models I would choose this one for it has a much high accuracy rate and results than any other. 
  
   ### Balanced Random Forest Classifier
 - Balanced Accuracy Score
 ![easy_acc](https://github.com/mckenziekkilburn/Credit_Risk_Analysis/blob/master/images/images/easy_acc.PNG)
 
 - Confusion Matrix
  ![easy_con](https://github.com/mckenziekkilburn/Credit_Risk_Analysis/blob/master/images/images/easy_con.PNG)
  
  - Imbalanced Classification Report
  ![easy_report](https://github.com/mckenziekkilburn/Credit_Risk_Analysis/blob/master/images/images/easy_report.PNG)
  
