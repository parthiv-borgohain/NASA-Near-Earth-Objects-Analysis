# NASA Near Earth Objects Analysis

Project as a part of coursework for Data Science Programming taught in Summer Semester of UT Austin's MS Business Analytics Program 

## Overview:
This project aims to predict whether a certified asteroid will be hazardous to Earth by analyzing various variables such as diameter, relative velocity, and more using NASA's Near Earth Objects dataset. The dataset consists of 90836 rows and 10 columns, with 6 usable variables for analysis. Through exploratory analysis and machine learning techniques such as Naive Bayes, Logistic Regression, KNN, and Trees/Ensemble Methods, we aim to find the relevant factors or combination of factors that make these asteroids dangerous to Earth. By understanding these features, scientists can develop crisis management plans and increase human welfare. The project found that the absolute magnitude variable had the strongest relationship with the target variable, and that the closest objects to Earth are the most dangerous. The best performing model was Gradient Boosting with a test accuracy of 92.02%.

## Takeaways and Next Steps:

Key takeaways from the analysis include:

* Only 4 variables were used to predict whether a NFO is hazardous and the remaining variables were dropped before fitting the models.

* None of the 4 selected variables had a significant impact on the target variable and predictive models did not show significant improvement over the baseline model.

* The best model obtained a test accuracy of 92.015% compared to a baseline accuracy of 90% and an F1 score of around 0.48.

* The most important feature according to the best model was miss_distance.

* Next steps include working with a larger dataset and including more features to improve the predictive model.

#### Note: ####

I am unfortunately unable to find all of the codes we used for our analysis. So only a portion of this code is available in this repository.
