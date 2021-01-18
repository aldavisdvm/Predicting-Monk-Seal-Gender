# Predicting-Monk-Seal-Gender
## Project Description
The purpose of this project is to see if gender can be predicted using blood chemistry values, with and 
without mass as a feature. A regression model is then compared to a TPOT classifer used to find a best fit.

### Methods Used

* Data Cleaning
* Machine Learning
* Data Visualization
* Predictive Modeling
* Linear Regression
* TPOT Classifier

### Technologies

* Jupyter Notebook
* Python
* Pandas and Numpy
* Scikit-Learn
* Seaborn and Matplotlib

### Data was obtained from:

Lander, Michelle; Fadely, Brian; Gelatt, Thomas; Rea, Lorrie; Loughlin, Thomas (2015).
Alaska Steller sea lion pups blood serum chemistry and hematology values measured from 1998-06-01 to 2011-07-15
(NCEI Accession 0137994). NOAA National Centers for Environmental Information.

Dataset:
https://doi.org/10.7289/v58913vh


## Project Summary

Data was explored, cleaned, and analyzed. Regression and TPOT classifier models were created
first with mass included as a feature, then without it.

It was not surprising to see that the model that included mass as a feature had the better predictive
value. The TPOT classifer came up with a weighted KNN classifer as being the best fit for this data set, with
a ROC AUC score of 76% using K-nearest neighbors = 79. When a KNN classifier model was run to double check
the parameters, it had a maximum accuracy of 71%. This is compared to the logistic regression model that had
an accuracy of 68%.
