# Credit_Risk_Analysis

## Overview
The purpose of this analysis was to use machine learning to analyze and create models to evaluate credit risk for loans. 

## Results
###  Random Oversampling
The results for the random oversampling are as follows: </br>
![This is an image](https://github.com/smwhng/Credit_Risk_Analysis/blob/main/Images/oversampaccscore.PNG)</br>
![This is an image](https://github.com/smwhng/Credit_Risk_Analysis/blob/main/Images/oversampclassrep.PNG)</br>
  - The accuracy score is .65
  - The high risk precision score is .01 and the recall is .71
  - the low risk precision score is 1 and the recall is .58

### SMOTE Oversampling
![This is an image](https://github.com/smwhng/Credit_Risk_Analysis/blob/main/Images/SMOTEaccscore.PNG)</br>
![This is an image](https://github.com/smwhng/Credit_Risk_Analysis/blob/main/Images/SMOTEclassrep.PNG)</br>
  - The accuracy score is .66
  - The high risk precision score is .01 and the recall is .63
  - the low risk precision score is 1 and the recall is .68

### Cluster Centroids Undersampling
![This is an image](https://github.com/smwhng/Credit_Risk_Analysis/blob/main/Images/undersampaccsc.PNG)</br>
![This is an image](https://github.com/smwhng/Credit_Risk_Analysis/blob/main/Images/undersampclassrep.PNG)</br>
  - The accuracy score is .54
  - The high risk precision score is .01 and the recall is .69
  - the low risk precision score is 1 and the recall is .4

### SMOTEEN
![This is an image](https://github.com/smwhng/Credit_Risk_Analysis/blob/main/Images/smoteenaccscor.PNG)</br>
![This is an image](https://github.com/smwhng/Credit_Risk_Analysis/blob/main/Images/smoteenclassrep.PNG)</br>
  - The accuracy score is .65
  - The high risk precision score is .01 and the recall is .72
  - the low risk precision score is 1 and the recall is .57

### Balanced Random Forest
![This is an image](https://github.com/smwhng/Credit_Risk_Analysis/blob/main/Images/brfaccscore.PNG)</br>
![This is an image](https://github.com/smwhng/Credit_Risk_Analysis/blob/main/Images/brfclassrep.PNG)</br>
  - The accuracy score is .79
  - The high risk precision score is .03 and the recall is .7
  - the low risk precision score is 1 and the recall is .87

### Easy Ensamble
![This is an image](https://github.com/smwhng/Credit_Risk_Analysis/blob/main/Images/adaaccscore.PNG)</br>
![This is an image](https://github.com/smwhng/Credit_Risk_Analysis/blob/main/Images/adaclassrep.PNG)</br>
  - The accuracy score is .93
  - The high risk precision score is .09 and the recall is .92
  - the low risk precision score is 1 and the recall is .94

## Summary
The first four models represent both oversampling and undersampling, as well as a combination of the two. Of these models, the highest accuracy is the SMOTE Oversampling model, with an accuracy of 66%, and the lowest is the Cluster Centroid Undersampling model, with an accuracy of only 54%. All four of the models are lacking in terms of their accuracy. The ensemble classifiers however, performed much better. The Balanced Random Forest model had an accuracy of 79% and a higher precision that the previous 4 models while maintaining a similar recall in the high-risk category. The final Easy Ensemble model is the recommended model of all six due to its highest accuracy score, 93%, as well as highest precision and recall scores in the high-risk category as well as the low-risk category. 
