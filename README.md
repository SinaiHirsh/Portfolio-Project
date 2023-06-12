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


You can include images of p![cm](https://github.com/SinaiHirsh/Portfolio-Project/assets/135940841/75bbfcbc-b02b-4ef4-b44b-ecbfd95cec22)
lots using the code below:

![Screenshot](image.png)

## (OPTIONAL: CONTACT DETAILS)
If you are planning on making your github repo public you may wish to include some contact information such as a link to your twitter or an email address. 

