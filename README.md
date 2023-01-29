# NASA Near Earth Objects Analysis

Project as a part of coursework for Data Science Programming taught in Summer Semester of UT Austin's MS Business Analytics Program 

## Introduction:

This project aims to predict whether a certified asteroid will be hazardous or not using certain variables. The dataset used consists of NASA-certified asteroids that are classified as the nearest earth object and contains information about several asteroids such as the diameter, relative velocity, and more.

Dataset Source: https://www.kaggle.com/datasets/sameepvani/nasa-nearest-earth-objects

## Importance:

* Space is often a topic that we are unfamiliar with due to factors such as distance, unknown, and dangerousness.
    
* By orbiting or existing near Earth, there is a certain probability that asteroids will disrupt Earth’s natural phenomena.
    
* Finding relevant factors or combination of factors for these asteroids to be hazardous to Earth will help scientists come up with crisis management plans beforehand and increase human welfare.

## Exploratory Analysis:

* The data consisted of 90836 rows and 10 columns and had 6 variables that were usable in our analysis.

* Variables used were the estimated diameter minimum, estimated diameter maximum, absolute magnitude, relative velocity, the distance it missed the earth, and our target variable, whether it was hazardous to earth or not.

* Data cleaning was done to remove the useless variables such as sentry object and orbiting body.

* Correlation chart showed the variable with the strongest relationship with our target variable was the absolute magnitude variable with a -.37 correlation.

* Group by functions showed that only 5% of asteroids under .25 kilometers were hazardous compared to all the other sizes greater than that which were hazardous at about a 40% rate.

* Absolute magnitude variable showed that the only asteroids that were hazardous were the asteroids that had an absolute magnitude of 24 or less.

* Machine learning was used to try and use these variables to help classify these asteroids as hazardous.

## Solution and Insights:

#### Naive Bayes:

* The data was run through Naive Bayes to find out the probability of hazard happening given each different factors that occured.

* The estimate diameter min & max was split into binary values that are higher than “2” and those that are under “2” which improved accuracy from 76% to 89%.

* Results showed that the Naive Bayes model was not performing well with an accuracy of 89.69% and 89.61%.

* Absolute magnitude was found to be the most important feature and miss distance was the least important feature.

* F1 score was low due to recall value being close to zero.

#### Logistic Regression:

* Logistic regression was used to understand the importance of each variable in predicting the change in hazardous.

* Dependent variable “hazardous” was made into binary numbers to run this regression.

* Results showed that variables such as relative velocity, miss distance, and estimated diameter minimum were important in predicting hazardous.

* Model was able to predict hazardous with an accuracy of 93.33%.

## Conclusion:

The project was able to identify relevant factors or combination of factors that make asteroids hazardous to Earth through exploratory analysis and machine learning techniques. These findings can help scientists come up with crisis management plans beforehand and increase human welfare.
