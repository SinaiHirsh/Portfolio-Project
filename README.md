# Credit risk assesment 


## NON-TECHNICAL EXPLANATION
As a portfolio project summarises the course, I chose to concentrate on a problem of credit risk prediction.

The data was taken from Kaggle, as well as some of the codebase.

Our goal is to predict the probability of default based on a set of input variables. We will use logistic regression, so each observation gets a value between 0 and 1 - which is the probability of default.

We will use Grid Search for hyperparameter tuning, to ensure that we get the best combination of hyperparameters that make the accuracy the highest.
Our goal is to predict the probability of default based on a set of variables.

## DATA

We will use data from https://www.kaggle.com/datasets/urvishvekariya/credit-risk-assessment?datasetId=2995523
The data consists of 32,581 records of loans.
According to the inforamation on Kaggle, the data was last Updated 3 months ago.
 Urvish Vekariya. (2023). <i>Credit Risk Assessment</i> [Data set]. Kaggle. https://doi.org/10.34740/KAGGLE/DSV/5168573

## MODEL 

I used logistic regression because it is very common to use it for credit scorring in the banking sector. The shape of the sigmond function mathematiclly causes the values to be between 0 and 1 which is what we want when it comes to binary variable that we want to make probabilities for it. 

## HYPERPARAMETER OPTIMSATION

Logistic regression has several hyperparameters on Sklearn and I optimised the most significant ones. I take my basecode from here:
https://www.kaggle.com/code/funxexcel/p2-logistic-regression-hyperparameter-tuning/notebook
and here:
https://www.projectpro.io/recipes/optimize-hyper-parameters-of-logistic-regression-model-using-grid-search-in-python
The idea is using gread search for hyperparameter tuning, when the algorithm considers all the possible combinations between the hyperparameters that we want to tune and chooses the best one.  

## RESULTS

The accuracy is quite high both on train and test sets. After hyperparameter tuning the train accuracy slightly increased, while the test accuracy decreases a little bit. 

Accuracy on the training data set with the original hyperparameters:  0.8461875739904415

Accuracy on the training data set after hyperparameters tuning:  0.8466698820537554

Accuracy on the test data set with the original hyperparameters:  0.8473501125434827

Accuracy on the test data set after hyperparameters tuning:  0.8471454880294659


Confusion matrix:


![cm](https://github.com/SinaiHirsh/Portfolio-Project/assets/135940841/8481e77c-5a09-4372-bcd9-46c894ce244c)

 

